# Polish IntelliJ dictionary
**Polish dictionary for IntelliJ / Polski słownik do IntelliJ**

I searched a lot over internet and i don't notice any valuable dictionary made for Intellij. You know for sure that if You are working on translations it is much better to have something to check text which You are typing.

I used some info from this site: [JetBrains forum](https://intellij-support.jetbrains.com/hc/en-us/community/posts/205803169-How-to-install-dictionary-polish-example) and Polish doctionary from this site: [Dictionary of Polish Language](https://sjp.pl/slownik/odmiany/) and made pl_PL.dic file which is compatibile with IntelliJ dictionary format.

## Usage

You need to download **pl_PL.dic** (which is inside **pl_PL.zip** archive) file to some directory on Your computer. It's important to make new directory, because in IntelliJ You need to select whole directory which contains user defined dictionaries, not just one file.

Lets assume that You have created new **dictionary** folder in Your **home** directory (Your path to that directory should look like that: **home/dictionary**). Next You need to paste downloaded file to that directory (so new path to this file will look like that **home/dictionary/pl_PL.dic**).

After that You need to open up IntelliJ program (PHPStorm,JetBrains etc.) and go to **File->Settings->Editor->Spelling->Dictionaries**. Next You need to click on **+** next to "Custom Dictionaries Folder" and select Your folder which contains pl_PL.dic file. After that click **OK**.

In next step You need to click: **File->Invalidate Caches...** and select **Invalidate and Exit**. Run Your IntelliJ program and enjoy Your complete Polish dictionary :)
