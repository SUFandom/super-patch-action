<div align=center>
<h1> Super Patch In Action</h1>
A Samsung super.img Editor for you to install GSI (Geneeric System Image) on the web!

No Linux, or WSL, or Termux Needed!
</div>

----

<div align=center>
<h3>Badges</h3>

![alttext](https://img.shields.io/static/v1?label=Status&message=Working&color=brightgreen) ![alttext](https://img.shields.io/badge/Version-v0.1-blue) ![alttext](https://img.shields.io/badge/SFTP_to_SourceForge-GOOD-BrightGreen?style=flat&logo=Sourceforge) 

[![alttext](https://img.shields.io/badge/-Visit_SUFandom/Xynoxx's_SourceForge_By_clicking_ME-blue?style=for-the-badge&logo=Sourceforge&logoColor=f5f5f5)](https://sourceforge.net/projects/xynoxx-prebuilt-gsi/files/) 

![alttext](https://img.shields.io/badge/Requires_Github_Enterprise_to_get_Beyond_2gb_Limit-Yes_that's_why_there's_sourceforge_requirement_in_here-red) 

[![alttext](https://img.shields.io/badge/-Check_out_the_Offline_Version_Instead_by_clicking_ME!-purple?style=for-the-badge)](https://github.com/SUFandom/super-patch) 

[![alttext](https://img.shields.io/badge/-Check_us_on_Telegram,_Exynos_850_Testing_&_Development_By_Clicking_me-yellow?style=for-the-badge&logo=Telegram)](https://t.me/a12schat)

*thats a **LOT** of Badges*
</div>

----


<div align=center> 
<h3>What is this?</h3>

This is a repository that can make your inserting your favourite ROM to your samsung device, best, with no more pesky hardware requirements, " *looking at you, super-patch with no proper WSL support* "

Right now, the options are very confusing at best:

![wth](images/cvs-recipt.png) 

istg this is hell-looking, im still new with the yaml stuff

and the source structure is uhhhhhhh:

![oh_naw_hell_naw_tf_man](images/someone-dont-let-him-cook-yaml-because-this-is-beyond-raiden-ei-cooking-here.png)

![frieren](images/Sousou-no-Frieren-Frieren-portada.webp)

I swear ill clean this up, in the coming updates of the script and make it easy to use at least

<div align=center>

## Why is this

Yeah, what's the reason why this is the 'best' option of patching super.img?

Table:

| Conditions            	| SUPER-PATCH [LOCAL]                                                                                                                                                                                                                                                     	| **THE ALL NEW SUPER-PATCH-ACTIONS**                                                         	|
|-----------------------	|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------	|
| Hardware Requirements 	| **Linux**<br><br>- 4GB OF RAM WITH 128GB OR MORE **SSD** RECOMMENDED, **AMD64 ONLY**<br><br>**WINDOWS**<br><br>- 8GB OF RAM + WSL 2 (Core i3, 7th Gen or Later), **SSD ONLY**<br><br>**ANDROID**<br><br>- (64 BIT ONLY) 4GB OF RAM + ARM CORTEX A55 OR LATER, 128GB STORAGE 	| Just fast Internet, and a supported Web3 Browser, LMAO                                      	|
| STORAGE               	| 128GB AS MINIMUM, DESKTOP (SATA/NVMe SSD ONLY, FOR WINDOWS), (eMMC, SATA, NVME FOR LINUX)                                                                                                                                                                               	| 15-20GB ONLY                                                                                	|
| TIME BUILD            	| 13 Mins at Max                                                                                                                                                                                                                                                          	| 7 Min to 10 Min at Max                                                                      	|
| SHARE YOUR BUILD      	| REQUIRES UPLOADING, THEN SHARING LINK FOR ONLY THAT BUILD                                                                                                                                                                                                               	| LISTS AVAILABLE IN JUST ONE LINK                                                            	|
| NETWORK               	| Data Plan consuming                                                                                                                                                                                                                                                     	| ONE TIME UPLOAD BASE ASSETS, THEN YOU CAN JUST REUSE SUPER.IMG FILES, SAVING MORE DATA PLAN 	|



</div>



</div>

<div align=center>
<h2>Table of Contents</h2>
<p align=center>
1 . <a href=#preparation>Preparation</a>
<br>
2. <a href=#upload>Upload</a>
<br>
3. <a href=#build>Build</a>

</div>

<div align=center>

## Preparation 

<p align=left>
1. Fork this repository, by Pressing Fork on the Page
<br>
2. Name it what you want
<br>
3. Done!
<br>
4. Create a Sourceforge Account (Strictly necessary), follow the steps they provide and if the form box says <code>(optional)</code> , you can just leave them blank, and also don't forget to verify yourself.
<br>
5. Create a Project, any name will do
<br>
6. After creating a project, and followed every instruction provided by sourceforge, log in to <code>sftp</code>.
<br>
6.1. Go to Terminal, enter <code>sftp (ur username)@frs.sourceforge.net</code> , then enter
<br>
6.2. After that, type <code>cd /home/pfs/project/(your created project in sourceforge)</code>, and you should be in that root project directory
<br>
6.2.1. Make sure that you entered in should be followed by the link site of your project, for example:
<br>
</p>

![frieren x task force 141](images/image-goes-hard.png)

<p align=left>
The red line must be the same as the target
<br>
6.3. Try entering <code>mkdir test</code>, enter then refresh the page, check files tab. You should see the test directory there, which means it's working
<br>
7. after that please head to your repository settings and go to secrets > action, then create credentials
<br>
7.1. Create a Repository Secret
<br>
7.2. Name it: <code>SOURCEFORGE_USERNAME</code>
<br>
7.3. Then enter your username 
<br>
7.4. After creating the username, create another secret, called <code>SOURCEFORGE_PASSWORD</code>
<br>
7.5. Enter your password there, don't worry, your credentials are safe and non-duplicate
7.6. Create another secret, name it: <code>SOURCEFORGE_REPO_TARGET</code>, see 6.2.1, copy and paste that red line
<br>
8. and you are Done
</p>

![fern happy yipee](https://i.redd.it/5xnf0r8i5whc1.gif)

</div>

---

<div align=center>

## Upload

<p align=left>
1. Create an account that would host your super.img file, i would recommend uploading the files to Internet Archive or file.io for some people that are familiar with their service
<br>
2. Upload your super.img file, (For Internet Archive Uploaders, please name your page title when you upload, properly)
<br>
3. Go to the files directory
<br>
<img src=images/red-circle-what-de-hell.png>
<br>
<img src=images/dir.png>
<br>
4. And confirmed that it's there!
</p>
</div>

---

<div align=center>

## Build

Here is your CVS Recipt, People!

<img src=images/another-cvs-recipt.png>

<p align=left>
1. Copy the link of uploaded super file, can be tar, lz4, or img file, just put them in the respective boxes, and only one of them are allowed, REMEMBER THAT AND STOP SENDING ISSUE PAGE ABOUT IT
<br>
2. enter what archive name you want it to be called, Default: <code>GSI-build-proto</code>
3. Compression Type:
<br>
Note: setting to uncompressed, wont apply any name u entered, just <code>super.img</code>
<br>
Another note: Selecting all, can have issues pushing to artifact, or releases , check the sourceforge instead
<br>
<br>
Set compression Types
<br>
- Tar (No compression, but contained, available in sourceforge)
<br>
- xz (Level 9 compression Type, can be on artifact build, releases, or sourceforge)
<br>
- 7z (a bit larger than xz but can be available on artifact, releases, and sourceforge)
<br>
- raw (super.img only)
<br>
- all (name says so, but some only available on artifacts and releases, while fully available on sourceforge)
<br>
4.1. Set GSI Link in img format, just copy and paste the source link, similar method to internet archive 
<br>
4.2. Set GSI link, compressed to .xz, commonly found on Phhusson's partner releases, just copy download link and paste it here, if there's an issue, please download manually, upload it and copy and paste a proper link.
<br>
5.Enter what directory subfolder, if you created a folder there (Sourceforge), type the folder there and add slash at the end, like: <code>FOLDER/</code>
<br>
6. Build!
<br>
7. DONE!!!

</p>

</div>