# [**DOWNLOAD THE MOD HERE**](https://github.com/GreenPinguinMods/ModRenamer-ETS2-ATS-V1.0.0/releases)





# **ModRenamer (V1.0.0) by GreenPinguin (August 6th 2026)**



Hi!



I've made a program that enables the user to change the names inside the whole mod file, including the content of the files themselves, so that the renaming is clean and correct. I used Python and some help from AI to code this, and I hope this is something useful for you.



##### **Why did I make this mod?**



Some locked mods are incompatible with some truck mods, like soundmods, and it isn't possible to open them. So, for example, if there is a sound mod only available for Mod A (the mod is locked) and you wanted to make Mod B compatible, you just use this program to change Mod B's def names to Mod A's def name.



##### **Functionality**



Important feature: this program does not modify .tobj files (because they are not fully text files, they have a binary part in them which, if you modify the text inside it, can break parts of the mod. If the .tobj files call to the original def name, there is a feature later in this description which can help with this issue (the "Target folders to DUPLICATE (Keep original + create copy)" feature).



*"Mod archive file"*:

The mod you want to modify its def name(s)



*"Text to search for"*:

With the same example as before (Mod A and Mod B), if you want to replace Mod B's name with Mod A's, you just type Mod B's **def name** here.



*"Replace with"*:

Replaces any mention of the text (even within the files themselves) entered in "Text to search for" by what is in the "Replace with" box. Same example as before, here you should put Mod A's name.



*"Target folders to MODIFY (In-place replacement)"*:

You can tell the program to modify only the folders that you have selected, by checking the boxes.

**If no box is ticked, the program will modify every folder.**

Every folder available is detected automatically by the program, these folders are the "top" ones (the first folders you see when opening the mod file)



*"Custom folder(s)"*:

You can add other folders (folders inside folders for example) which are not detected by the program.



*"Target folders to DUPLICATE (Keep original + create copy)"*:

**This feature is very important if a mod is breaking when you execute the program.** It usually happens because the .tobj files are referring to a def name which doesn't exist anymore inside the mod itself. To correct this, this feature enables the user to copy a problematic folder, and keep its original def name(s), while also making another folder which has the modified def names.

Contrary to the "Target folders to MODIFY" feature, if you don't check any box, nothing will be duplicated.



###### **If this kind of error is happening (.tobj, materials or texture linked errors), usually it is linked to the "vehicle" folder, so, if you encounter these errors, try to check the "vehicle" folder box. If it still shows errors, check the in-game log and try to find error messages corresponding to your mod.**



###### **So, for example, if the corresponding errors indicate problems linked to the "material" folder, try to check the "material" folder box in "Target folders to DUPLICATE".**



**The three coloured boxes are indicator lights, which are better explained in my GitHub documentation.**



##### **Installation**



Download the mod from my [GitHub repository](https://github.com/GreenPinguinMods/ModRenamer-ETS2-ATS-V1.0.0) (in the "Releases" tab) and execute the .exe file inside the downloaded .zip file.





##### **IMPORTANT: If you have any error message, please refer to the .pdf file in the GitHub repository.**

##### 

If WinRar asks you: "Several files extracted from ETS2\_ATS\_Mod\_Renamer.zip have been modified. Do you want to update them in the archive?" when you close the .exe file (program), click "Yes", this updates the program's log (useful for troubleshooting).



##### **Supporting the mod**



If you have any suggestions, feel free to add them here or on GitHub, as well as reporting issues/bugs.



And, if you want to leave me a tip, you can send it on my Ko-fi account!





##### [**Click here to support my work**](https://ko-fi.com/greenpinguin)

