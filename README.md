PSX
===
<br />
PSX Bare Metal Code by krom (Peter Lemon).<br />
<br />
All code compiles out of box with the Armips assembler by Kingcom.<br />
https://github.com/Kingcom/armips/<br />
http://buildbot.orphis.net/armips/<br />
I have included binaries & executables of all the demos.<br />
<br />
Special thanks to the Hitmen demo group, who with their asm sources, helped me get into PSX Coding =D<br />
http://hitmen.c02.at/html/psx_sources.html<br />
<br />
Also I'd like to thank ARM9, who made the bin2exe.py file, to convert my PSX binaries into PSX exectuables.<br />
https://github.com/ARM9/psxdev/blob/master/libpsx/tools/bin2exe.py<br />
<br />
Please check out NO$PSX, a PSX emulator/debugger by Martin Korth:<br />
http://problemkaputt.de/psx.htm<br />
<br />
Also MAME has a great PSX emulator/debugger by smf:<br />
https://www.mamedev.org/<br />
<br />
Howto Compile:<br />
All the code compiles into a single binary & executable (NAME.EXE) file.<br />
Using Armips Run: make.bat<br />
<br />
Howto Run:<br />
I only test with a real PSX.<br />
<br />
You can also use PSX emulators like NO$PSX which can load PSX executables directly, & MAME using this command:<br />
mame pse -quik NAME.EXE
