# Polish JetBrains (IntelliJ, PhpStorm etc.) dictionary
**Polish dictionary for JetBrains IDEs / Polski słownik do IDE JetBrains**

I searched a lot over internet and I don't notice any valuable dictionary made for IntelliJ. You know for sure that if you are working on translations it is much better to have something to check text which you are typing.

I used some info from this site: [JetBrains forum](https://intellij-support.jetbrains.com/hc/en-us/community/posts/205803169-How-to-install-dictionary-polish-example) and Polish doctionary from this site: [Dictionary of Polish Language](https://sjp.pl/slownik/odmiany/) and made pl_PL.dic file which is compatibile with IntelliJ dictionary format.

## Usage

### New Jetbrains tools
User @egel (https://github.com/dominik59/polish_intellij_dictionary/issues/3) has suggested that in newer versions of Jetbrain tools (PhpStorm, IntelliJ etc.) procedure of dictionary is much simpler:
0. Download repo and extract pl_Pl.dic
0. Open IDE (PhpStorm, IntelliJ etc.) -> File -> Settings -> Editor -> Proofreading -> Spelling -> (Dictionaries tab) -> +
0. Select previously extracted pl_Pl.dic
0. Done

### Old Jetbrains tools
You need to download **pl_PL.dic** (which is inside **pl_PL.zip** archive) file to some directory on your computer. It's important to make new directory, because in JetBrains programs you need to select whole directory which contains user defined dictionaries, not just one file.

Lets assume that you have created new **dictionary** folder in your **home** directory (your path to that directory should look like that: **home/dictionary**). Next you need to paste downloaded file to that directory (so new path to this file will look like that: **home/dictionary/pl_PL.dic**).

After that you need to open up any JetBrains program (PHPStorm, IntelliJ etc.) and go to **File->Settings->Editor->Spelling->Dictionaries**. Next you need to click on **+** next to "Custom Dictionaries Folder" and select your folder which contains pl_PL.dic file. After that click **OK**.

In next step you need to click: **File->Invalidate Caches...** and select **Invalidate and Exit**. Run your JetBrains program and enjoy your complete Polish dictionary :)
