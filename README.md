<div align="center">

## Testing Installations and Installing Windows in Under 5 Minutes\.


</div>

### Description

Need to test installs on different operating systems? Need a new operating system fast? Infected by virus?...Read this - it may help.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[MrBobo](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mrbobo.md)
**Level**          |Advanced
**User Rating**    |4.9 (44 globes from 9 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) , VBA MS Access, VBA MS Excel
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mrbobo-testing-installations-and-installing-windows-in-under-5-minutes__1-34520/archive/master.zip)





### Source Code

<p><b><font color="#FF0000" size="4">Novice users should not attempt this. You will
need to know what you are doing.</font></b></p>
<p>
<font size="3" COLOR="#000000">
A question that often comes up, in the discussion forum is "It worked on
my computer, but when I install on my friends it has faults and wont run, what
can I do ?". There are many things that may have gone wrong in the writing
of the application, and I dont intend addressing all these. Let's assume the
code is correct and the P&D wizard was used to build a package. How to test
it ? If you had half a dozen computers with different operating systems on each,
freshly installed with no other applications installed, you could install your
app on each machine for testing.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Great, who has half a dozen computers at home - not me ! This is what I do, I
dont say it's the best way, or the only way - it's just the method I employ.
Dont try this at home kids, unless you're backed up, know what you're doing and
promise not to blame me if it all turns to....
</font>
</p>
<p><u><b><font size="3" color="#0000FF">Requirements:</font></b></u></p>
<p>
<font size="3" COLOR="#000000">
Enough spare time to install a few operating systems. Patience. Bravery.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
A computer with 2 hard drives - one for storage of files, the other for
operating systems with four primary partitions.
</font>
</p>
<font SIZE="1" COLOR="#000000">
<p> </p>
</font>
<p><u><b><font size="3" color="#0000FF">Partitions</font></b></u></p>
<p>
<font size="3" COLOR="#000000">
1. Main development OS - I recommend Windows 2000 Pro.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
2 to 4 - Test OS's - depending on your needs - say 95,98,XP
</font>
</p>
<p><b><u><font size="3" color="#0000FF">Setting Up.</font></u></b></p>
<p>
<font size="3" COLOR="#000000">
Back up files you cant afford to lose.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
On your 'Master' hard drive - format, and create four partitions.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Keep in mind: Win 95,98 - partitions need only to be a few hundred Mb.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
XP - ideally at least 1.5 Gb. I suggest these partitions be Fat32, but thats
up to you.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Set up your development OS
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Set the next partition to 'Active', boot to that OS.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Set up your first test OS.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Repeat the process until all partitions have an OS installed.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Assuming all is well, set your development OS 'Active' and start coding. To
test a package, copy the setup files to your 'Slave' or storage hard drive, set
one of your test OS's 'Active' and boot to it.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Install your application, test for bugs. Repeat the process with the OS's you
wish to test on.
</font>
</p>
<p><b><u><font size="3" color="#0000FF">Issues:</font> </u></b></p>
<p><font size="3" COLOR="#000000">OK, we've tested an installation on a
partition - now that OS is no longer 'virgin', future testing may be
compromised. For NT based OS's the only fix is to re-install - if you feel it is
required. For all versions of Win95/98 however there is a solution. These
operating systems can be zipped up for later use but you will need a partition
utility - FDisk is not sufficient for our needs - (I recommend 'Partition
Magic')
</font>
</p>
<font SIZE="1" COLOR="#000000">
<p> </p>
</font>
<p><b><u><font size="3" color="#0000FF">Zipping Operating Systems</font></u></b></p>
<p>
<font size="3" COLOR="#000000">
Assumes Zip program installed - WinZip for example.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Boot to a Win 95 or Win98 partition.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Use this zip application to create a zip file of your entire C drive, saving
this zip file to your storage partition. You should make this zip as soon as you
have installed the OS - remember, you only have to do this once.
</font>
</p>
<p><b><u><font size="3" color="#0000FF">Unzipping an Operating System</font></u></b></p>
<p>
<font size="3" COLOR="#000000">
Using your partition utility - not FDisk, set 'Active' a Win95 or Win98
partition(NOT the partition you wish to unzip to), AND set the partition you
wish to unzip to 'Visible'(Normally only the 'Active' primary partition is
visible in My Computer, but we need to see the partition in order to unzip to
it, this is why FDisk is not used - FDisk cant set a 'non-Active' primary
partition visible). While we're in the partition utility, format this drive
you're going to unzip to. Boot to the 'Active' partition. In My Computer, there
will appear another drive. It is important not to do too much while both these
primary partitions are visible - there's two primary partitions here and drive
letters have changed, keep activity to a minimum ! If you browse to this new
drive you will see it is empty - we just formatted it. From your storage
partition, unzip your previously zipped OS to this empty drive. Browse to 'C:\'
drive - this will set the 'CurDir' to 'C:\'.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
From the run menu, type "sys e:" or which ever drive letter you
need to unzip to. This command copies system files required by your new OS to
that drive.(Sometimes this is unneccesary - but just to be safe).
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Set this drive 'Active' and boot to it. You now have a complete OS setup in
under 5 minutes ! All settings, drivers, any applications installed are all
there - the lot.
</font>
</p>
<p><u><b><font size="3" color="#0000FF">Example zips I have on my storage drive:</font></b></u></p>
<p>
<font size="3" COLOR="#000000">
Win98SE with VB6
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Win98SE with VB6-SP4
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Win98SE with VB6-SP5
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Win95B - minimum setup
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Win95D - minimum setup
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Win98 - minimum setup
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Win98SE - minimum setup
</font>
</p>
<font SIZE="1" COLOR="#000000">
<p> </p>
</font>
<p>
<font size="3" COLOR="#000000">
Naturally there are many combinations of drives/partitions you could use,
this is just an example.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
There are applications that promise more than four primary partitions(32 or
more). I dont recommend such partition applications, I have found such systems
to be unstable. Four operating systems seems to work, I haven't had a glitch in
four years.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
Once you've done this once or twice and seen how easy it is, you will never
bother with the tedious task of setting up Win95/98 again. Simply unzip a
previously zipped OS. Helps greatly if infected by virus etc.
</font>
</p>
<p>
<font size="3" COLOR="#000000">
or have just destroyed your OS through overuse or incompetence !
</font>
</p>
<font SIZE="1" COLOR="#000000">
<p> Below : Updated 8th May </p>
</font>
<p><u><font size="5" color="#FF0000"><b>Before commenting</b></font></u></p>
<p><font size="3" color="#008000">First, before commenting please read this
article in order to understand exactly what it achieves, how it goes about it,
and it's limitations. I say this in the hope of avoiding some <b> unrelated comments</b>
due to misunderstanding the concept I am putting forward.</font></p>
<p><font size="3" color="#0000FF"><b><u>Target usage:</u></b></font></p>
<p><font size="3" color="#008000"><b>Stand-alone PC</b>, with no expensive software
needed for implementation.</font></p>
<p><b><u><font size="3" color="#0000FF">What it can do:</font></u></b></p>
<p><font size="3" color="#008000">Set up an entire operating system on an empty
hard drive in <b> under 5 minutes</b>.
Run multiple OS's on a stand-alone PC <b> without multi-booting</b>. Provide excellent protection/recovery ability
from both <b> virus and hacker</b>. Provide a method of storing many OS's using a
minimum of storage space.</font></p>
<p><b><u><font size="3" color="#0000FF">Advantages:</font></u></b></p>
<p><font size="3" color="#008000"><b>Cheap, simple, flexible, fast, reliable</b>.
Leaves you in total control of your partitions, not some automated process. Very
little time spent in DOS. Results in REAL OS's - not virtual OS's with the
consequent performance losses.</font></p>
<p><b><u><font size="3" color="#0000FF">Disadvantages:</font></u></b></p>
<p><font size="3" color="#008000">Wont backup NT based OS's.</font></p>
<p><b><u><font size="3" color="#0000FF">Required:</font></u></b></p>
<p><font size="3" color="#008000">Some <b> REAL LIFE </b> experience with hard drives and
partitioning. If your knowledge is based on what the books say, please keep an
open mind and think for yourself.</font></p>
<p><b><u><font size="3" color="#0000FF">To the doubters:</font></u></b></p>
<p><font size="3" color="#008000">The system described <b>WORKS</b>, and has been
tested over many years, in many different situations. I am not some kid, I've
been around the block more than a few times.</font></p>
<p><b><u><font size="3" color="#0000FF">Warnings:</font></u></b></p>
<p><font size="3" color="#008000">Compaq users, sorry, not for you. It may work,
but I've heard horror stories.</font></p>
<font SIZE="1" COLOR="#000000">
<p> </p>
<p> </p>
<p> </p>
</font>
<p><font size="3" color="#0000FF">Please feel free to comment/ask questions.</font></p>
<font SIZE="1" COLOR="#000000">
<p> Below : Updated 9th May </p>
</font>
<p><font size="3" color="#008000">There are a lot of comments on this
submission. here is a summary of comments so far, but please read them in full
as they answer in more detail some of the questions you may have regarding how
to implement the methods I have alluded to in this submission.</font> </p>
<p><font color="#008000">Get <b>friends to test</b> apps</font> <font color="#0000FF">-
only addresses part of this submissions concept</font></p>
<p><font size="3" color="#008000">Use <b>Backup</b> instead of zipping - </font><font size="3" color="#0000FF">doesn't
achieve desired results</font></p>
<p><font size="3" color="#008000">Be careful how you install <b>multi-boot</b>
systems</font><font size="3" color="#0000FF"> - this submission has nothing to
do with multi-booting</font></p>
<p><font color="#008000"><b>Zip</b> files are unreliable</font> <font color="#0000FF">-
no they're not</font></p>
<p><font color="#008000"><span style="background-color: #FFFFFF">Use </span><b><span style="background-color: #FFFFFF">Norton
Ghost</span> </b></font><font color="#0000FF">- this submission requires NO
expensive software, and Norton Ghost has a reputation for not working on
everyone's machine, and only addresses part of what this submission can do.</font></p>
<p><font color="#008000"><b>Use 2 computers</b></font> <font color="#0000FF">-
this is for folks with only one computer</font></p>
<p><font color="#008000">Use<b> VMware</b> or other 'Virtual OS' software</font>
<font color="#0000FF">- this submission requires NO expensive software, and is
designed for slow and fast machines alike. And like Norton Ghost only addresses </font>
<font color="#0000FF">part of what this submission can do.</font></p>
<p>&nbsp;</p>
<p>&nbsp;</p>

