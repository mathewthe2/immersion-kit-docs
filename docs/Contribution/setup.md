# Setup

## movies2anki

**Go to its source code in Anki and replace the image height's from 360 to 480.**

On Mac, click on Desktop and it should show Finder as the default app. Click *Go* and then *Go to Folder*.

![Image](../../assets/setup-go-to-folder.png)

Enter `~/Library/Application Support`.

Select *Anki2*, or if there isn't, *Anki*.

![Image](../../assets/anki-folder-location.png)

Select the folder with the name containg the keyword *addons*, such as *addons21*. 

![Image](../../assets/anki-folder.png)

Find the folder containing the addon for movies2anki. This folder should contain the file *movies2anki.py*

![Image](../../assets/anki-addon-folder.png)

Open *movies2anki.py* with your text editor and search or the keyword *360*. you should be able to find the line where it assigns the value to *video_height*.

Replace it with **480** or higher. 

![Image](../../assets/setup-update-movies2anki-dimensions.png)