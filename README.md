### win10tweaks.reg
windows 10/11 optimization  tweaks 

### Hello, friend!
do it on your risk if you dont know scripting and what is regedit than dont use at your risk this script change parameters on core settings so make restore point (follow below guide) its not need as i have tested and using right now but still.

### How to create system restore point
Here's a general guide on how to create a system restore point in Windows:

Open the Start menu and type "System Properties" in the search bar. Click on the first result that appears.

In the System Properties window, click on the "System Protection" tab.

Under the "Protection Settings" section, select the drive that you want to create a restore point for.

Click on the "Create" button to start creating the restore point.

In the "Create a restore point" window, type a name for the restore point in the "Restore point name" field. This name will help you identify the restore point later on.

Click on the "Create" button to create the restore point. The process may take a few minutes, depending on the size of the drive and the amount of data it contains.

Once the restore point is created, you will see a message saying that the restore point was created successfully.

Click on "OK" to close the System Properties window.

### About this app 
**This Utility is a compilation of windows tasks I perform on each Windows system I use. It is meant to streamline installs, debloat with tweaks, troubleshoot with config, and fix Windows updates. Feel free to push and pull.


It is the easiest and fastest app of its kind to set numerous settings with just one click. 

### How to use
just execute script that is relatedble to your usage.

### Notes
tweaks im working and teseted on my system below listed tweaks are with negetive or no effect due to low end configs check on your own may be you will get benefit if you have high-end system. 

Superfetch Hkey_local_machine\SYSTEM\CurrentControlSet \Control\Session Manager\Memory Management\PrefetchParameters\EnableSuperfet ch. Set to 0. EnableSuperfetch is a setting in the File-Based Write Filter (FBWF) and Enhanced Write Filter with HORM (EWF) packages. It specifies how to run SuperFetch, a tool that can load application data into memory before it is demanded.

Prefetch Hkey_local_machine\SYSTEM\CurrentControlSet \Control\Session Manager\Memory Management\PrefetchParameters\EnablePrefetch . Set to 0. Prefetch is a utility that is intended to improve Windows and application startup performance by loading application data into memory before it is demanded. When using EWF with a RAM overly to protect the boot volume, Prefetch is unable to persist its data from startup to startup.

PENDING

Hibernation HKEY_LOCAL_MACHINE\SYSTEM\CurrentContro lSet\Control\Power\HibernateEnabled. Set to 0. HibernateEnabled specifies whether the user of a device will be given the option of turning on or turning off hibernation.

Automatic Defragmentation HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft
Dfrg\BootOptimizeFunction\Background Disk Defragmentation Disable Defragmentation is the process of moving portions of files around on a disk to defragment files, that is, the process of moving file clusters on a disk to make them contiguous

NO EFFECT OR NAGATIVE

NTFS Memory Usage HKEY_LOCAL_MACHINE\SYSTEM\CurrentContro lSet\Contr ol\FileSystem\NtfsMemoryUsage. Set to 2. NTFS increases the size of its lookaside lists and memory thresholds.

Large System Cache HKEY_LOCAL_MACHINE\SYSTEM\CurrentContro lSet\Control\SessionManager\MemoryManagem ent\LargeSystemCache. Set to 1. Optimize memory for system performance.

### Requirements
The app is currently developed for Windows 10 and Windows 11


