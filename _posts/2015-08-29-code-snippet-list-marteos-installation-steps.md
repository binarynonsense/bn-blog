---
layout: post
title: "Code Snippet: Marte OS installation steps"
categories:
- code-snippets
---

{% highlight bash %}
{% raw %}
cd bin/
cd gnat-gpl-2014-x86-linux-bin/
sudo apt-get install build-essential
./doinstall
cd ..
ln -s gnat_gpl_2014/ gnat
echo $PATH
cd bin
ln -s marte_1.9_21Aug2014 marte
cd marte_1.9_21Aug2014/
cd ..
cd marte
ls
./minstall
#msetcurrentarch x86 i386
msetcurrentarch x86 pii
mkrtsmarteuc && mkmarte
cd examples/
mgcc hello_world_c.c -o mprogram
#testing one of my programs
sudo apt-get install qemu
qemu-system-i386 -kernel mprogram
cd ..
cd _source/
cd life_marteos_20090613/
make
qemu-system-i386 -kernel life.exe 
{% endraw %}
{% endhighlight %}