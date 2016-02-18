# kc15
Public release of the ancient (but possibly revivable) KC1 project, regeneration no. 5
or "KC15", for short.

TODO

1. Verify files can actually be built on a modern system  
2. To that end, DJGPP and DOXBOX will likely be necessary, so stencil time to explain that in public instructions.
3. Remove any boring cruft from the source
4. Complete local studio to "good enough" status (need to replace dead servers and regenerate backup plan)
5. After ensuring the code can build, even if under DOS32 emulation, then put it in local github
6. Push it out to this account as the "old" branch 
7. Depending on available time, may upgrade it or forget it. 
8. Also, explain why the board game is a good candidate for a central project for a programming "baptismo"
9. Next time use checkboxes as this list is not really a sequence of events I plan to follow in order.
10. Enjoy life more abundantly, or something like that. 

Well, that's it for now.

Just for the curious to not become furious, I didn't just slap the code up here because I don't have time curretnly, and I need to make sure it can actually work before I upload it anyhow. But, it is called "regeneration no. 5" because I re-implemented it from scratch four times before. Only this first variant seem to have survived...

The regenerations.

1. DOS32 with Allegro 4 (DJGPP based). Started on a Windows 9x box and last revise c. 2002.
2. Pygame re-implementation from scratch. It had nice context menus and explictly used FSMs [Finite State Machine] in the design, but I seem to have lost it totally. If only I had used github, eh? Or been priviledged to have a staff, for doing backups faithfully. 
3. Python textual version. Using Python 2.7.x, I think, it was a command-line-driven type application where I was aiming to vbuild a more elegant core which would then be called as a library from a front end. It too seems to have been lost.
4. A revised version of #1, which somehow I have a zillion backups off, and even had uploaded to geocities back before it went the way of the null, and became void. Since I could always find it, I could always tweak it, despite it being the worse codebase (since I never refactord it, only added random stuff as I learnt Allegro and C/C++). It had sound (PCM/wave out but from DOS so prob. using the Allegro SB-based routines(?) and gamepad support, but, again, this was lost.
5. This upcoming one. If it isn't lost by some act of misfortune.

