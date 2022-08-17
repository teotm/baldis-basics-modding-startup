# Modyfying Audio (UnityEX Method)

- Note: UABE is not needed for this, but can be helpful to check the file names you want to replace.

Once you've opened UnityEX, press `Open Acrhive Unity` button and then search for the `.assets` file with the audio file(s) you want to modify.

Select the AudioClip you want to modify, press Right mouse button and click `Export with convert`. To select multiple audios, use `Ctrl+Click`.

Now, in your `BALDI_Data` folder, there should be a new `Unity_Assets_Files` folder. Go inside that folder and search for the `.snd.fsb` file(s) that you extracted using UnityEX.

Once you got your voicelines ready, convert them to .wav (if you haven't did that already). Then, **rename** the `.wav` file format to `.snd.fsb`.

Now, open UnityEX once again and open the Unity archive you want to modify.

Press `Import all files`, close UnityEX and you should be done.

Optional: You can delete the `Unity_Assets_Files` folder. It just contains the extracted audio and deleting won't affect your gameplay.