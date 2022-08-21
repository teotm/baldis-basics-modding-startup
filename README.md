<h1 class="SelectedElement">Have you ever wanted to mod Baldi's Basics?</h1>
Well no worries, this guide is here to help you with that! There is listed everything you should need to know when starting your modding adventure.
<br>
Before heading into modyfying, here's some information that you would need to use for later.
<h2>What textures and audios every <code>.assets</code> file contains</h2>
<ul>
<li>globalgamemanagers - The cursor, Mystman12 and Meta Game Jam logos that appear while booting up the game.</li>
<li>sharedassets0 - The warning screen</li>
<li>sharedassets1 - Title Screen</li>
<li>sharedassets2 - Pretty much everything that you can find in school</li>
<li>sharedassets3 - Game Over Screens</li>
<li>sharedassets4 - Normal ending screen that you get when finishing the game</li>
<li>sharedassets5 - Secret ending where you meet Filename2</li>
<li>sharedassets6 - The Test Room you enter when you answer with <code>31718</code> to any math question</li>
</ul>
<h2>Recommended programs to use for modding</h2>
<ul>
<li>For modyfying textures
<ul>
<li><a href="https://www.dotpdn.com/downloads/pdn.html">Paint.net</a></li>
</ul>
</li>
<li>For modyfying audio
<ul>
<li><a href="https://www.audacityteam.org/download/">Audacity</a></li>
</ul>
</li>
<li>For modyfying text files (dumps)
<ul>
<li><a href="https://notepad-plus-plus.org/downloads/">Notepad++</a></li>
<li><a href="https://code.visualstudio.com/download">Visual Studio Code</a></li>
</ul>
</li>
</ul>
<hr>
<h1 class="SelectedElement">Modding Textures</h1>
<h2>Required program</h2>
<ul>
<li><a href="https://github.com/SeriousCache/UABE/releases/tag/2.2stabled">Unity Assets Bundle Extractor</a> (UABE)</li>
</ul>
<h2>How to modify textures?</h2>
Once you have UABE installed, open it, press "File" and "Open".
<br>
After that, search for the directory where is your Baldi's Basics copy located.
<br>
Go to BALDI_Data and select the <code>.assets</code> file, that you want to edit.
<br>
If you did open the <code>.assets</code> file, your UABE should look like that.
<br>
<img src="https://raw.githubusercontent.com/teotm/baldis-basics-modding-startup/main/images/textures/let-the-funny-begin.png">
<br>
Next, sort the assets by Type, by clicking Type in your UABE. To select all assets with the one specific type (which for this case is Texture2D), you can just select the first asset, then scroll down to the last Texture2D and press <code>Ctrl+Shift+Click</code>.
<br>
After that, click "Plugins" button and Export the assets to <code>.png</code> <span class="Spoiler">(or <code>.tga</code> if you have Paint.net)</span> and click OK.
<br>
Then, make a new folder where the assets be will extracted. Although I recommend you to make these 3 folders:
<ol>
<li>Folder with the all original assets from Baldi's Basics untouched as a backup</li>
<li>Folder with the original assets and the modified ones</li>
<li>Folder with <b>only</b> the modified textures</li>
</ol>
You can now go modify the images that you want. After you're done, go to UABE and open the <code>.assets</code> file once again. Now, if you want to replace a single image, just click it. However if you want to edit multiple images, select then by using <code>Ctrl+Click</code>. Next, press "Plugins".
<h3>Modyfying a single image</h3>
After pressing "Plugins" choose "Edit". After that, search for the image that you want replace the asset with.
<h3>Modyfying multiple images</h3>
When you pressed "Plugins" choose "Batch import" next. After that, you'll need to search for the folder with the assets you want to replace and then select the folder.
<br>
<br>
<br>
If you see <code>*</code> in the row of the asset, it means you successfully managed to modify the asset. When you're done, save the modified <code>.assets</code> file by pressing "OK" or "File" then "Save" and replace it. I recommend you to make a backup file of the original <code>.assets</code> file too, just in case if you mess something up.
<br>
You can now go open the game and see if you modified the assets. If the textures got modified, then congratulations! You're incredible!
<hr>
<h1 class="SelectedElement">Modding Audio</h1>
<h2>Required programs</h2>
<ul>
<li>UnityEX method
<ul>
<li><a href="https://www.mediafire.com/file/t8umkb9empr7vz7/UnityEX.zip/file">UnityEX</a></li>
</ul>
</li>
<li>Unity method (more difficult)
<ul>
<li><a href="https://github.com/SeriousCache/UABE/releases/tag/2.2stabled">Unity Assets Bundle Extractor</a> (UABE)
<ul>
<li><i>Note: It can be helpful while using UnityEX method too</i></li>
</ul>
</li>
<li><a href="https://unity3d.com/unity/whats-new/2019.3.12">Unity 2019.3.12</a> (UABE)</li>
</ul>
</li>
</ul>
<h2>How to modify audio? - UnityEX method</h2>
Once you've opened UnityEX, press "Open Acrhive Unity" button, go to <code>BALDI_Data</code> and then search for the <code>.assets</code> file with the audio file(s) you want to modify.
<br>
Select the AudioClip you want to modify, press Right mouse button and press "Export with convert". To select multiple audios, use <code>Ctrl+Click</code>.
<br>
Now, in your <code>BALDI_Data</code> folder, there should be a new <code>Unity_Assets_Files</code> folder. Go inside that folder and search for the <code>.snd.fsb</code> file(s) that you extracted using UnityEX.
<br>
Once you got your voicelines ready, convert them to .wav (if you haven't did that already). Then, <b>rename</b> the <code>.wav</code> file format to <code>.snd.fsb</code> <span class="Spoiler"><i>(since .wav and .snd are kinda the same I guess)</i></span>.
<br>
Now, open UnityEX once again and open the Unity archive you want to modify. Next, press <code>Import all files</code>, close UnityEX and you should be done.
<br>
<ul>
<li><i>Optional: You can delete the <code>Unity_Assets_Files</code> folder. It just contains the extracted audio and deleting won't affect your gameplay.</i></li>
</ul>
<h2>How to modify audio? - Unity method</h2>
Open up UABE and follow the instructions above in the <b>How to modify textures?</b> section, until you sort assets by type.
<br>
After that, select all <code>AudioClip</code> assets, press "Pugins" and export the assets to <code>.wav</code> in a folder with the stored assets.
<br>
Just like in Modding Textures section, I recommend you to make these folders too:
<ol>
<li>Folder with the all original audio from Baldi's Basics untouched as a backup</li>
<li>Folder with the original audios and the modified ones</li>
<li>Folder with <b>only</b> the modified audio</li>
</ol>
<ul>
<li><i>Note: The audio format needs to be <code>.wav</code>.</i></li>
</ul>
After you modified the audio, open up Unity Hub and make a new 3D Project, set the editor version to "2019.3.12f1" and name it whatever you like.
<br>
Open up the project in Unity and drag the modded audio files into your Unity Project. The audio files you just added to your Unity Project need to be dragged to the 3D void. <i>Image of the void is shown below:</i>
<img src="https://raw.githubusercontent.com/teotm/baldis-basics-modding-startup/main/images/audio/selectTheAudioInUnity.png">
<ol>
<li><i>OPTIONAL STEP: Select the audio force it to Mono, and Apply the Changes.</i></li>
</ol>
When you're finished adding the audios to the Unity Project, go to the left bottom of Unity, press "File", choose "Build Settings" and next go to "Build". After that, select the folder where your Unity Project will be built.
<br>
While done building the game, open UABE and this time, search for the folder where you built your Unity project, go to <code>MYPROJECTNAME_DATA</code> folder and select <code>sharedassets0.assets</code> file. Your UABE should show that it can't find a file database, so scroll down and select the last option (2019.2.0f1) from the list and press OK.
<br>
Select all the audio, press Export Dump and make a new folder where you will store your dumps. Open extracted the text files in Notepad++ or Visual Studio Code and search for the <code>Replace in Files</code> option, to make removing file name suffixes faster. Then replace the <code>-sharedassetsX.assets-</code> with an empty text. After you do that, delete the numbers that are next to in the Audio name, so the name for exaple would look lke that: <code>1PR_AmComing</code>. Next, replace the <code>sharedassets0.resource</code> with <code>myCustomName.resource</code> <i>(you can set the name to whatever you like, obviously)</i> and save all the Text files.
<br>
When the text files are edited, open your folder with the dumps in your File Explorer and remove the suffixes from the file names <i>(again, example to show how it should look like: <code>1PR_AmComing.txt</code>)</i>.
<br>
Next, open up UABE and search for your Baldi's Basics folder and open the <code>sharedassetsX.assets</code> file with the audio you want to modify.
<br>
Click the audio name you want to modify, next press Import Dump and search for the Dump that matches with the name of the audio. Repeat this, until you do this with all the audios that you want to modify and click save the changes.
<br>
Finally, copy the <code>sharedassets0.resource</code> file from your Unity project, rename the file to <code>myCustomName.resource</code> and drag it into the <code>BALDI_Data</code> folder.
<hr>
<h1 class="SelectedElement">Coding</h1>
<h2>Required program</h2>
<ul>
<li><a href="https://github.com/dnSpy/dnSpy/releases/tag/v6.1.8">dnSpy</a></li>
</ul>
<h2>How to change the game's code</h2>
Open dnSpy and search for <code>Assembly-CSharp.dll</code>, which is located in <code>BALDI_Data/Managed</code> directory.
<br>
At the left column, there's a file list. Search for the file you opened, and click on the little arrow next to the file name and do it again. Now, you should see three file contents which are <code>PE</code>, <code>Type References</code> and <code>-</code>. Click on the <code>-</code> and you'll see a bunch of the game scripts.
<br>
Next, choose the game script you would want to edit and click on it.
<br>
Now, if you want to edit the script, click Right mouse button on the game code and choose <code>Edit Method (C#)</code> or <code>Edit Class (C#)</code>.
<br>
After you're done editing the code, press <code>Compile</code>
<ul>
<li>Note: You can't compile the scripts, when errors are detected.</li>
</ul>
When you managed to compile the code, you can now click "File" at the left top of dnSpy, choose "Save Module" and press OK.
<hr>
<h1 class="SelectedElement">The End</h1>
I hope this guide I made, helped you. I also plan to add decompiling guide here too, so check out later if I add this. Made this with passion :)
<br>
I know, there is already a guide out there too, but I wanted to make my own version too.