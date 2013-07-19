kernel-cleaner
==============

Designed for:

<ul>
<li>Find and remove kernels without availables source/modules directories .</li>
<li>Find and remove directories in /usr/src/, which haven't kernel's sources.</li>
<li>Find and remove directories in /lib/modules, which haven't parents as kernels in /boot.</li>
<li>Find and remove unused initramfses and configs</li>
</ul>

Features:
<ul>
<li>Kernel/initramfs/config name independent ( hello, eclean-kernel :3 ).</li>
<li>Correct work with EXTRAVERSION and LOCALVERSION.</li>
<li>Ignore custom files, directories, packages and versions.</li>
<li>Force remove custom files, directories, packages and versions.</li>
</ul>
