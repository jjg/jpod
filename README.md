# jpod

## Why?

After years of frustration with digital music players I really need to design and build one that works the way I want it to.

## What?

I was very satisfied with my first iPod (third-generation, 40GB), in fact I would simply keep using it now but for the fact that I don't have a way to get music onto it, and it doesn't play files in my preferred lossless format (FLAC).  It's also failing mechanically, and despite my efforts to repair it, I'm unable to get it working with anything other than the original (dieing) mechanical hard disk.

Over the years I've tried using other devices, or my phone (both built-in music player features and aftermarket applications) but they all fail at the essential features I need:

* Play lossless audio files
* Play them in the expected order (Album order, playlist order, random)
* Simple physical interface
* Work with standard accessories (headphones, SD cards, power supplies)
* Uses simple, standard means of adding music to the device (USB storage, SD card, etc.)
* High-quality audio output (no noise, interruptions, etc.)
* Works offline
* At least a day worth of battery life

Most devices I've used fail because they try to be too clever.  They have so many features that they are frustrating to use, or are unreliable, or have excessive battery consumption, etc.  What I need is something I can easily put lots of music on and listen to for a very long time without fatigue.  This doesn't seem like it should be hard, but apparently it is.

So I guess I'm going to have to build it.

## How?

Ideally I'd use as much off-the-shelf tech as possible to expedite the process.  That said, I've already waited so long to solve this problem what's another year or two?  So, if I can't find what I need on the shelf, I'm not opposed to fabricating something from "scratch" even if that takes a little longer.

I see two ways to approach this:

1. Scour the web for existing parts that provide the needed functionality and can be stuck together to achieve the design goals
2. Identify the ideal components and start designing circuits to combine them

To some degree I've done the first thing, and that seems like the more reasonable place to start, but I could easily do that forever, searching for just the right part, so I think if I go that route I'm going to "timebox" the work.

The second option is very attractive, in no small part because I've recently started experimenting with FPGAs and I can see how I might be able to accomplish a lot of the design goals with a single chip and the right "software".

The risk in option two is that it could take a very long time to produce something usable. In the long run it's the better option, and frankly the work is more interesting, but it may not solve the problem this project set-out to address.



## References

* https://github.com/ultraembedded?tab=repositories
* https://hackaday.com/2012/03/13/playing-mp3s-from-an-fpga/
* https://sites.google.com/site/tgptechnologies/fpga-project/fpga-audio-fpga-based-mp3-wav-player
* https://web.physics.ucsb.edu/~martinisgroup/classnotes/fpgainstructions/Instructions_Lab9.pdf
* http://ee.bradley.edu/projects/proj2010/fpgamp3/FPGAMP3_Project_Report.pdf
* https://sites.google.com/site/hquadproject/
* http://www.mp3-tech.org/programmer/docs/linneman_thesis.pdf
* 
