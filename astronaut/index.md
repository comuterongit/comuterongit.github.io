# Astronaut Documentation
This is the Astronaut user manual. Video guides are not finished yet, and will most probably release end of 2025.

# Table of Contents
> [1 - Integration](#1%20-%20Integration)  
> 	[1.1 - Join Shortcuts Method](#1.1%20-%20Join%20Shortcuts%20Method)  
> 		[1.1.1 - Installation Links for Join Shortcuts by @gluebyte](#1.1.1%20-%20Installation%20Links%20for%20Join%20Shortcuts%20by%20@gluebyte)  
> 		[1.1.2 - Joining your shortcut](#1.1.2%20-%20Joining%20your%20shortcut)  
> 		[1.1.3 - Video Help - Join Shortcuts](#1.1.3%20-%20Video%20Help%20-%20Join%20Shortcuts)  
> 	[1.2 - "Start from Scratch" Method](#1.2%20-%20"Start%20from%20Scratch"%20Method)  
> [2 - Setup](#2%20-%20Setup)  
> 	[2.1 - Dictionary Values](#2.1%20-%20Dictionary%20Values)  
> 		[2.1.1 - UpdateCheck](#2.1.1%20-%20UpdateCheck)  
> 		[2.1.2 - Shortcut Name](#2.1.2%20-%20Shortcut%20Name)  
> 		[2.1.3 - Shortcut Author](#2.1.3%20-%20Shortcut%20Author)  
> 		[2.1.4 - VerNumURL](#2.1.4%20-%20VerNumURL)  
> 		[2.1.5 - CurrentVer](#2.1.5%20-%20CurrentVer)  
> 		[2.1.6 - ChangelogURL](#2.1.6%20-%20ChangelogURL)  
> 		[2.1.7 - UpdateURL](#2.1.7%20-%20UpdateURL)  
> 		[2.1.8 - StopWhenError](#2.1.8%20-%20StopWhenError)  
> 		[2.1.9 - DisplayErrors](#2.1.9%20-%20DisplayErrors)  
> 		[2.1.10 - Rollbacks](#2.1.10%20-%20Rollbacks)  
> 		[2.1.11 - MUIAllowed](#2.1.11%20-%20MUIAllowed)  
> 		[2.1.12 OutputErrorCodes](#2.1.12%20OutputErrorCodes)  
> 	[2.2 - MUI (Mini User Interface)](#2.2%20-%20MUI%20(Mini%20User%20Interface))  
> 		[2.2.1 - Video Help - MUI](#2.2.1%20-%20Video%20Help%20-%20MUI)  
> 	[2.3 - Creating VerNumURL, ChangelogURL and UpdateURL files using GitHub](#100%20-%20Document%20Error)  
> 		[2.3.1 - Creating a new repository](#2.3.1%20-%20Creating%20a%20new%20repository)  
> 		[2.3.2 - Adding the version file](#2.3.2%20-%20Adding%20the%20version%20file)  
> 		[2.3.3 - Adding the changelog file](#2.3.3%20-%20Adding%20the%20changelog%20file)  
> 		[2.3.4 - Adding the iCloud URL file](#2.3.4%20-%20Adding%20the%20iCloud%20URL%20file)  
> 		[2.3.5 - Getting the Raw Links](#2.3.5%20-%20Getting%20the%20Raw%20Links)  
> 		[2.3.6 - Video Help - Using GitHub](#2.3.6%20-%20Video%20Help%20-%20Using%20GitHub)  
> [3 - Pushing an Update](#3%20-%20Pushing%20an%20Update)  
> [4 - More infos on Astronaut](#4%20-%20More%20infos%20on%20Astronaut)  
> 	[4.1 - Why choose Astronaut](#4.1%20-%20Why%20choose%20Astronaut)  
> 	[4.2 - Why not to choose Astronaut](#4.2%20-%20Why%20not%20to%20choose%20Astronaut)  
> 	[4.3 - Other things that you might or might not wanna know](#4.3%20-%20Other%20things%20that%20you%20might%20or%20might%20not%20wanna%20know)  
> 	[4.4 - Error Codes List & Fixes](#4.4%20-%20Error%20Codes%20List%20&%20Fixes)  
> 	[4.5 - Credits](#4.5%20-%20Credits)  
> [5 - Other/External](#5%20-%20Other/External)  
> 	[5.1 - GitHub Paragraph Bug](#5.1%20-%20GitHub%20Paragraph%20Bug)  
> 	[5.2 - xx Version Structure](#5.2%20-%20xx%20Version%20Structure)  
> [6 - Did we miss anything? Do you need further assistance?](#6%20-%20Did%20we%20miss%20anything?%20Do%20you%20need%20further%20assistance?)  
> 	[6.1 - Video Help - Everything Astronaut](#6.1%20-%20Video%20Help%20-%20Everything%20Astronaut)
> [100 - Document Error](#100%20-%20Document%20Error)  


# 1 - Integration  
## 1.1 - Join Shortcuts Method  
### 1.1.1 - Installation Links for Join Shortcuts by @gluebyte
Install these shortcuts:  
https://routinehub.co/shortcut/10038/  
https://routinehub.co/shortcut/10060/  
### 1.1.2 - Joining your shortcut  
 Make sure you are running on iOS 14 or above.  
 Select Astronaut as your main shortcut. If Join Shortcuts asks you for a name, just type `Astronaut` and select Astronaut from the list, if one pops up. After selecting Astronaut as your main shortcut, a menu will show up asking you where to insert your shortcut. Scroll to the very bottom and tap `End of Astronaut`. Join Shortcuts will ask you if you'd like to insert the shortcut into `If` and `End if`; simply say no. Next, enter the name of **your** shortcut, and select it from the list. Then, select `Remote Sign` and finish joining.
 
 **ℹ️ Make sure to have a second copy of your shortcut without Astronaut, so you can edit it without bugs.**  
### 1.1.3 - Video Help - Join Shortcuts  
**ℹ️ The Astronaut video guides are still under construction**  
## 1.2 - "Start from Scratch" Method  
Create a new copy of Astronaut, scroll to the very bottom of it and start building your shortcut with Astronaut as a base. Rename and/or change the icon to whatever you like. This should be difficult and buggy, since Astronaut is large.

**⚠️ This is not recommended as the shortcuts app will most likely bug and crash.**  
# 2 - Setup  
## 2.1 - Dictionary Values  
### 2.1.1 - UpdateCheck  
Pretty self-explanatory. But fine. Enables/Disables the update engine.  
> **Options/Values**  
> True - Enables Astronaut  
> False - Disables Astronaut

ℹ️ **When disabling [UpdateCheck](#2.1.1%20-%20UpdateCheck), set [DisplayErrors](#2.1.9%20-%20DisplayErrors) to false to avoid an error for each boot.**  
### 2.1.2 - Shortcut Name  
Self-explanatory aswell. The text you enter will appear on the update menu as your shortcut's name. Enter your shortcut's name for the best results.  
> **Options/Values**  
> Text Input  
### 2.1.3 - Shortcut Author  
The input will appear on the update menu aswell.  
> **Options/Values**  
> Text Input  
### 2.1.4 - VerNumURL  
Enter a URL path to a .txt file containing the **newest version** **number** of your shortcut. Astronaut will grab the number from the URL and check if it's greater than the shortcut version.  
> **Options/Values**  
> Text Input (URL Example: https://example.com/example.txt)

**⚠️ Astronaut has limited compability with version structures other than the [xx version structure](#5.2%20-%20xx%20Version%20Structure).**  
### 2.1.5 - CurrentVer  
Enter the number of the current shortcut version.  
> **Options/Values**  
> Number Input (Example: 42)

**⚠️ Astronaut has limited compability with version structures other than the [xx version structure](#5.2%20-%20xx%20Version%20Structure).**  
### 2.1.6 - ChangelogURL  
Similar to [VerNumURL](#2.1.4%20-%20VerNumURL), ChangelogURL needs a URL which links to a .txt file containing your changelog. If no changelog available, just create a file telling the user that no changelog is available.  
> **Options/Values**  
> Text Input (URL Example: https://example.com/example.txt)  
### 2.1.7 - UpdateURL  
Just like [VerNumURL](#2.1.4%20-%20VerNumURL) and [ChangelogURL](#2.1.6%20-%20ChangelogURL), UpdateURL needs a URL path to a .txt file containing an iCloud link or similar containing the newest version of your Shortcut.  
> **Options/Values**  
> Text Input (URL Example: https://example.com/example.txt)

**ℹ️ UpdateURLs look like this: https://icloud.com/shortcuts/123456789, https://routinehub.co/shortcut/123456 or shortcuts://123456789.**  
### 2.1.8 - StopWhenError  
Toggles stopping the shortcut if an update error occurs.  
> **Options/Values**  
> True - Stops the shortcut when an error occurs  
> False - Continues even if an error was found  
### 2.1.9 - DisplayErrors  
Displays error messages as they occur. WARNING: Setting this to false is not a good idea if [StopWhenError](#2.1.8%20-%20StopWhenError) is set to true.  
> **Options/Values**  
> True - Displays errors as they occur  
> False - Hides errors  
### 2.1.10 - Rollbacks  
Rollbacks are the opposite of updating. Instead of going up a version, you go down a version. This setting asks your users to downgrade if the number in the [VerNumURL](#2.1.4%20-%20VerNumURL) link is less than the [CurrentVer](#2.1.5%20-%20CurrentVer) number.  
> **Options/Values**  
> True - Enable rollbacks  
> False - Disable rollbacks (Version can't decrease)  
### 2.1.11 - MUIAllowed  
The Mini User Interface (Acronym: MUI) is a small menu in the update engine. The MUI lets you "manually" check for updates and view your shortcut's changelog. To set it up, see [2.2 - MUI (Mini User Interface)](#2.2%20-%20MUI%20(Mini%20User%20Interface)). The dictionary value lets you enable/disable the MUI.  
> **Options/Values**  
> True - Enables the MUI  
> False - Disables the MUI  
### 2.1.12 OutputErrorCodes  
This one works only if [StopWhenError](#2.1.8%20-%20StopWhenError) is set to true. Enabling this feature will output error codes **if** this shortcut is being run from another shortcut.  
> **Options/Values**  
> True - Enable Error Code Output  
> False - Disable Error Code Output  
## 2.2 - MUI (Mini User Interface)  
The MUI is a small menu that can be accessed by inputting `MUI` as text into the shortcut running Astronaut. The MUI is optional and is enabled by default, but you can disable it in the dictionary (see [2.1.11 - MUIAllowed](#2.1.11%20-%20MUIAllowed)).  
### 2.2.1 - Video Help - MUI  
**ℹ️ The Astronaut video guides are still under construction**  
## 2.3 - Creating [VerNumURL](#2.1.4%20-%20VerNumURL), [ChangelogURL](#2.1.6%20-%20ChangelogURL) and [UpdateURL](#2.1.7%20-%20UpdateURL) files using [GitHub](https://github.com/) (Desktop)
### 2.3.1 - Creating a new repository  
Log in (or sign up) to a [GitHub](https://github.com/) account. Next, create a new repository by tapping the green add button on the top right and selecting "New Repository" from the dropdown menu. Now type any name you want for the repository and any description. If you can't decide for a license, we recommend "The Unlicense". Click on create and now you have a new repository.  
### 2.3.2 - Adding the version file  
Open the repository used for your shortcut and click "Add file". On the top of the screen, rename the file to anything, but make sure it ends with ".txt". as for the body (the text you put in the file) type "1", or whatever version your shortcut is on (Examples: 3, 67, 241). Then click commit changes, click commit changes again and a file is there  
### 2.3.3 - Adding the changelog file  
Similar to above, create a new file and rename the file to whatever, as long as it ends with ".txt". Next, insert your changelog insde of the body. **All of the files can be edited later.** The structure of your changelog doesn't matter, what you type will be displayed in the Update Engine/[MUI](#2.2%20-%20MUI%20(Mini%20User%20Interface)).  
### 2.3.4 - Adding the iCloud URL file  
Same as above, make a file then paste the iCloud URL to your shortcut, click commit changes, click commit changes again and there you have it.

**ℹ️ To make updating faster, replace "https://icloud.com/shortcuts/" with "shortcuts://"**
### 2.3.5 - Getting the Raw Links  
After you have created all your files, click on the repositoy you have created on the left sidebar then click on the file with the version number. On the top right, there's an icon displaying "Raw". Click on that, then copy the link of the new tab that was opened. Now just paste that link inside of the specified dictionary value (Version Number Raw - [VerNumURL](#2.1.4%20-%20VerNumURL); Changelog - [ChangelogURL](#2.1.6%20-%20ChangelogURL); iCloud URL - [UpdateURL](#2.1.7%20-%20UpdateURL))  
### 2.3.6 - Video Help - Using GitHub  
**ℹ️ The Astronaut video guides are still under construction**  
# 3 - Pushing an Update  
**Step 1**  
Update the [CurrentVer](#2.1.5%20-%20CurrentVer) in the shortcut you want to push. Replace the previous number with a new, greater number.

**Step 2**  
Generate an iCloud link for your new shortcut and replace the previous iCloud link with the new one. In this step we are talking about the [iCloud URL file](#2.3.4%20-%20Adding%20the%20iCloud%20URL%20file) that you should have created earlier.

**ℹ️ To make updating faster, replace "https://icloud.com/shortcuts/" with "shortcuts://"**

**Step 3 (Optional)**  
Commit changes to your [Adding the changelog file](#2.3.3%20-%20Adding%20the%20changelog%20file). The new changelog will instantly appear in all of the shortcuts.  
# 4 - More infos on Astronaut  
## 4.1 - Why choose Astronaut  
Astronaut is advanced but difficult, so here are a few pros in using it.  
**Pros**
- Advanced
- **Very** customizable
- **Very** customizable (x2)
- Open-Source + No Copyright ([UNLICENSE.org](https://unlicense.org/); You may republish)
- vCard update menu
- [GitHub Paragraph Bug](#4.1%20-%20GitHub%20Paragraph%20Bug) fix
- Changelog support
- Free
- Removable Watermark
## 4.2 - Why not to choose Astronaut
There are a few downs on the update engine. Here's a list:  
**Cons**  
- Limited xx.xx version number support ([xx version structure](#4.2%20-%20xx%20Version%20Structure) is recommended)
- No alphabetical version support
- Very Slow
- No RH API support
- Difficult
- Requires some kind of file host
- Large
## 4.3 - Other things that you might or might not wanna know  
- Integration-type update engine
- In Developmentn't (Still squashing a few bugs. Maybe.)
- We have the super duper cool useless[MUI (Mini User Interface)](#2.2%20-%20MUI%20(Mini%20User%20Interface))
## 4.4 - Error Codes List & Fixes
- 0 error: UpdateCheck boolean set to false
- 0 fix: Set [UpdateCheck](#2.1.1%20-%20UpdateCheck) to true
- 1 & 1a error: IP-Address is empty
- 1 & 1a fix: Connect to a WiFi network that provides internet
- 1 & 1a fix: Allow permission to view your IP-Address
- 2 error: Rollback successful (Hidden error, [OutputErrorCodes](#2.1.12%20OutputErrorCodes) only)
- 2 fix: N/A
- 3 error: Update successful (Hidden error, [OutputErrorCodes](#2.1.12%20OutputErrorCodes) only)
- 3 fix: N/A
- 4 error: MUI unavaliable. Occurs when having exactly `MUI` as shortcut input
- 4 fix: set [MUIAllowed](#2.1.11%20-%20MUIAllowed) to true
## 4.5 - Credits
Credit is verily appreciated and we are fine with none, but if you do want to support and help us, please insert one of these:
`Using [Astronaut Update Engine](LINK TO RH PAGE) made by [Team Comuter](https://routinehub.co/user/comuterdevs)`
or
`[![Using Astronaut Update Engine](IMAGE)](LINK)`
# 5 - Other/External
## 5.1 - GitHub Paragraph Bug
The GitHub paragraph bug is not quite a bug. When creating a, for example, .txt file, GitHub always adds an empty new line at the end of the file. To fix this, Astronaut uses the "Replace Text" block to delete the line. Its that simple.
## 5.2 - xx Version Structure
The xx version structure uses full numbers only for versions.
**Example**
1
2
3

Never use a period or a letter in the xx version structure. Just increase a whole number.
# 6 - Did we miss anything? Do you need further assistance?
Send us an Email over at q@comuter.at. If you wanna chat, you can join our [Discord Server](https://discord.gg/zspyAFnCsn), we'd be happy to assist you!
## 6.1 - Video Help - Everything Astronaut
The following video is a **full guide** on Astronaut
**ℹ️ The Astronaut video guides are still under construction**















# 100 - Document Error
> **:(**
> 
> **==An error occured while finding that article. That article might have invalid characters in its header.==**
