---
layout: post
title: "Development Environment"
---
# One Year Thoughts on Windows Subsytem for Linux 2 

I have been using Windows Subsystem for Linux 2 for a little over a year now and want to share my general experience and thoughts on my new development environment. The short answer: I highly recommend trying out WSL2 - if you are willing to put in the effort. The main advantages are the integration, isolated distros, and speed/performance. The setbacks I have faced are VPN, windows insider updates, configuration setup, and paradoxically sppeed/performance. 

Windows Subsytem for Linux 2, WSL2 for short, is a virtualization container on the Windows Operating System. As shown from the image below, I am able to simutanously run Windows programs like Adobe Illustrator with a Ubuntu command line. 

[ screenshot of images ]

If you have used a Mac, its like running Parrerl or booting up from USB drive. But unlike virtual machines like Virtual Box, WSL2 is integrated with windows allowing you to intereact with wsl2 and Window files all in the shell. Some clear benefits from the start is not needing to boot up when you want to switch operating systems and completely (montiarly) free. 

## PROS
### Integrated windows with linux
clearly the bi
### Isolated Distros
  Failure rate - lost backup
### Memorey & performance
Before I googled anything, WSL2 default consumes 50% of my 8GB allocated memory.
Usually my day to day routine I have multiple tmux sessions running but mainly
as window holders for my day coding and my night coding. Through configuration,
which will be talked about later on this piece, WSL2 takes a fraction of
memorey. 

## CONS
### VPN connection
### Windows Insider
I use to be part of the Early Windoes Insider Program but for the sake of my
deev environment not breaking with every unkown update. Shaking apprehension
when I wake up the next morning seeing my laptop has done an automatic update
and not knowing if Ubuntu shell would open. That is the nature of the Early
Insider Program and since I am not tech savvy as the true hackers in that space,
I downgraded to.
### Configuration And Setup

### Performance/memory

## Conclusions

For the most part, the journey with WSL2 has been a great expereince and
impressed with the Microsoft team work on this. I need to
setup more contingency on my setup without it being an nuisance for my regular
use. Excited to see what the WSL2 team at Microsoft. Will release another post
about the specifics of my setup but in the meantime you can check my dotfiles on
Github that has the information. If interested in setting it up, Frank Pigeon
has a great tutorial on getting WSL2 setup.
