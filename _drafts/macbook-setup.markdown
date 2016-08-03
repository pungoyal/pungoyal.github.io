---
layout: post
title:  "Macbook Setup"
date:   2016-08-01 15:10:21 +0530
categories: machine setup bootstrap macbook
---
How I setup my laptop has evolved over the years. It started with taking a backup of my [dotfiles][dotfiles-wiki]{:target="_blank_"} on hard-disks to getting them put on github. I have changed multiple machines (maybe 15, if not more) ever since.

The setup I have now allows me to have a new macbook up and running within minutes.

## [![alfred]({{ site.url }}/assets/alfred.png)][alfred]{:target="_blank_"} Alfred

[Alfred][alfred]{:target="_blank_"} is a better replacement for the native spotlight. Though spotlight has improved over the MacOS releases, I still do not like it as my default launcher. Alfred is lightweight and simplifies mundane tasks like calculator etc. It remembers recent matches. 

## [![iterm]({{ site.url }}/assets/iterm2.jpg)][iterm]{:target="_blank_"} iTerm

[iTerm][iterm]{:target="_blank_"} is a must have native terminal replacement, so much that this is the first thing I install on a new machine. I just cannot bear to write a single word on the crap mac terminal.

Best thing about this is that all my preferences, including custom shortcuts are backed up and reused instantly. More on this later.

## [![homebrew]({{ site.url }}/assets/homebrew.png)][homebrew]{:target="_blank_"} homebrew

[Homebrew][homebrew]{:target="_blank_"} is first thing I install on the minty fresh iterm is

## [![oh-my-zsh]({{ site.url }}/assets/oh-my-zsh.png)][oh-my-zsh]{:target="_blank_"} Oh My ZSH

## zsh

{% highlight shell %}
ln -sf ~/Dropbox/Laptop/dotfiles/.zshrc ~/.zshrc # get the zsh config
{% endhighlight %}

## Dropbox
[Dropbox][dropbox-web]{:target="_blank_"} has become a necessity. I use it to backup my files across computers. This glorified `rsync` is very helpful in instant sharing of ssh keys across machines. After downloading and setting up dropbox, I go for :

{% highlight shell %}
ln -sf ~/Dropbox/Laptop/dotfiles/.zshrc ~/.zshrc # get the zsh config
ln -s ~/Dropbox/Laptop/.ssh ~/.ssh # get the ssh keys in place
{% endhighlight %}



### link the dotfiles

### link the .ssh folder

### git flow


[alfred]: https://itunes.apple.com/in/app/alfred/id405843582?mt=12
[iterm]: https://www.iterm2.com/version3.html
[homebrew]: http://brew.sh/
[oh-my-zsh]: http://ohmyz.sh/
[dotfiles]: https://en.wikipedia.org/wiki/Dot-file
[dropbox]: https://www.dropbox.com/
