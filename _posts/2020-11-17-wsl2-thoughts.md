---
layout: post
title: One Year Thoughts on Windows Subsystem for Linux 2
---
I have been using Windows Subsystem for Linux 2 for a little over a year now and wanted to share my general experience and thoughts on my new development environment. The quick conclusion: I highly recommend trying out WSL2 - if you are willing to put in the effort. 

Windows Subsytem for Linux 2, WSL2 for short, is a virtualization container on the Windows Operating System. As shown from the image below, I am able to simutanously run programs like Adobe Illustrator with a Ubuntu shell. 

[ screenshot of images ]

If you have used a Mac, its like running Parallel or booting up with Boot Camp. But unlike virtual machines like Virtual Box, WSL2 is integrated with windows allowing you to intereact with wsl2 and Window files all in the shell. Some clear benefits from the start is not needing to boot up when you want to switch operating systems and is completely free. 

The main advantages are the integration with Windows OS, allowing isolated distros, and speed/performance. The setbacks I have faced are VPN, windows insider updates, configuration setup, and paradoxically speed/performance. 

The development windows system and I have not clicked yet and altough it is vast much better when I started coding years ago with VSCode, I miss Unix cli. But at the same time of my gripes with Windows, Mac development experience was great but the surronding ecosystem was very limited. 

## Pros
### Integrated windows with linux
In it's name
### Isolated Distros
A great is easy speration of linux distros. My default is Ubuntu and as seen in the image there is. Sometimes I like to test new configs with wsl2 distro but do not want to break my main dev setup.
### Memory & performance
Before I googled anything, WSL2 default consumes 50% of my 8GB allocated memory. Usually my day to day routine I have multiple tmux sessions running but mainlyas window holders for my day coding and my night coding. Through configuration, which will be talked about later on this piece, WSL2 takes a fraction of overall memorey. 

## Cons
### Instabilty
Many times I lose Name resolutions either when change Wi-fi, VPN settings, or when I put my laptop to sleep. 

Another major problem which is a known issue beyond WSL2 is infamous Windows automatic updates. I use to be part of the Early Windows Insider Program (a checkbox on the Windows Settings Screen) but for the sake of my deev environment not breaking with every unkown update. Shaking apprehension when I wake up the next morning seeing my laptop has done an automatic update and not knowing if Ubuntu shell would open. That is the nature of the Early Insider Program and since I am not tech savvy as the true hackers in that space, I downgraded to.
### Configuration And Setup
Like tools tmux and vim, wsl2 is not a plug-and-play setup especially if one is tryinging to have it done . I was reaching a bottleneck with having the shell open taking a majority of my ram. 

Alot of these cons could be fixed with being more active on the forums as for example on the name resolution problem, that has been talked about in much detail with users posting scripts, i just have not

## Conclusions
For the most part, the journey with WSL2 has been a great expereince and impressed with the Microsoft team work on this. I need to setup more contingency on my setup without it being an nuisance for my regular use. Excited to see what the WSL2 team at Microsoft. Will release another post about the specifics of my setup but in the meantime you can check my dotfiles on Github that has the information. If interested in setting it up, Frank Pigeon has a great tutorial on getting WSL2 setup.
