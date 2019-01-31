---
layout: post
title: "Code Snippet: Bash Script to Unrar Files to Same-named Subdirectories"
categories:
- code-snippets
---

{% highlight bash %}
{% raw %}
#! /bin/sh

# unrar all rar files in current dir to same-named subdirectories 
# ref: http://bashscripts.org/forum/viewtopic.php?f=8&t=908
# ref : http://www.linuxquestions.org/questions/programming-9/unrar-multiple-files-into-seprated-directory-base-on-their-name-927127/

echo "starting unrar in folders"

# for everything named *.rar
for filename in *.rar

do

foldername=$(basename "$filename" .rar)
echo $foldername
mkdir "$foldername"
cd "$foldername"
unrar x ../"$filename"
cd ..

done 

echo "finished unrar in folders"
{% endraw %}
{% endhighlight %}