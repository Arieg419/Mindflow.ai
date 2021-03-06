# MindFlow.ai
Mindflow.ai is SaaS platform that runs in the background of your dev environment, and creates documentation based on your workflow.

## Want to join our Alpha release?
Email me at arieg419@gmail.com and we'll get you set up :zap:

### Getting Started

These instructions will show you how to use Mindflow.

### Quick Start

So far Mindflow.ai supports
* [Git integration](#gitintegration)
* [File watching](#filewatch)
* [Adding copied text](#copytext)
* [Adding images](#copyimages)  
* [Embedding youtube videos](#copyvideos)
* [Custom notes](#customnotes)
* [Drag and Drop](#dd)
* [Search Timeline](#search)
* [Generate Documentation](#generate)

Navigate to the timeline tab. It should be empty.

![#gettingstarted](https://github.com/Arieg419/Mindflow.ai/blob/master/assets/img/mindflow_intro.gif "Get started")

### <a name="gitintegration"></a>Git integration

1. Navigate to the Home tab.

2. Click on Open Timeline

3. Select a directory with a .git directory.

![#watchfile](https://github.com/Arieg419/Mindflow.ai/blob/master/assets/img/mindflow_git.gif)

### <a name="copytext"></a> Copying text

Copy some text to your clipboard. Now run `Cmd-C` (Ctrl-C for Windows or Linux). Flip back to Mindflow and navigate to the timeline tab.
Now run 'Cmd-H' (Ctrl-H for Windows or Linux), You should see the text on the timeline.

![#copytext](https://github.com/Arieg419/Mindflow.ai/blob/master/assets/img/mindflow_copytext.gif "Copy text")


### <a name="copyimages"></a> Copying images

Copy an image to your clipboard. Now run `Cmd-I` (Ctrl-I for Windows or Linux). Flip back to Mindflow and navigate to the timeline tab. You should see the copied image on your timeline.

![#copyimages](https://github.com/Arieg419/Mindflow.ai/blob/master/assets/img/mindflow_copyimage.gif "Get started")

### <a name="copyvideos"></a> Embed Youtube Videos

Embed a youtube video Go to youtube and copy the url of a video like this one to your clipboard https://www.youtube.com/watch?v=s1Rd4UShDxQ. Now run `Cmd-Y` (Ctrl-Y for Windows or Linux).

![#copyvideo](https://github.com/Arieg419/Mindflow.ai/blob/master/assets/img/mindflow_video.gif "Get started")

### <a name="customnotes"></a> Custom notes

Add a note

![#customnotes](https://github.com/Arieg419/Mindflow.ai/blob/master/assets/img/add_note.gif)

### <a name="dd"></a> Drag and Drop timeline nodes

![#dd](https://github.com/Arieg419/Mindflow.ai/blob/master/assets/img/mindflow_dragAndDrop.gif "Get started")

### <a name="search"></a> Search timeline**

![#search](https://github.com/Arieg419/Mindflow.ai/blob/master/assets/img/mindflow_search.gif "Search timeline")


### <a name="filewatch"></a>Watching JS files for changes

1. Navigate to the Home tab.

2. Click on watch a JS file

3. Select a JS file to be watched.

4. Edit JS file. The changes made to the file should now be reflected on your timeline.
(This feature currently works on 1 file only)

![#watchfile](https://github.com/Arieg419/Mindflow.ai/blob/master/assets/img/mindflow_code_snippet.gif "File Change")

### <a name="generate"></a>Generate Documentation

1. Navigate to timeline view.

2. Run `Cmd-G` (Mac) or `Ctrl-G` (Windows)

![#generate](https://github.com/Arieg419/Mindflow.ai/blob/master/assets/img/mindflow_generatedoc.gif "Generate Documentation")

**Saving your timeline**

Mindflow.ai creates a hidden `.mf` folder with your timelines data in a selected directory.

1. To save your timeline, click on the save file button. You will be prompted to select a directory to save to.

2. Once your timeline has been saved you can close Mindflow via the CLI (`Ctrl-C`) or GUI.

**Loading previous timelines**
 1. Open Mindflow.ai and navigate to the "Sources" tab.
 2. Click the button under existing timelines and navigate to the directory where you saved the timeline.
 3. Navigate to the "Timeline" tab to see your previous work.

## Contributing

Found a bug? Want a specific feature implemented? Please open a github issue so we can git (😄) to it ASAP.

Thanks!
