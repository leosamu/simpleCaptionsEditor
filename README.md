# simpleCaptionsEditor
Paella Player standalone plugin for editing captions 

This plugin allows to edit a captions file and then export as srt,vtt and other formats.

This editor is based on the work of [alexdemartos](https://github.com/alexdemartos/paella) and widly modified to work as a standalone plugin.

## Installation
To install you will need a working [paella player v6.2](https://github.com/polimediaupv/paella).

1. Add **es.upv.paella.captionsEditorPlugins** to the plugins folder.

2. Modify the config/config.json file in order to activate the plugin adding the line 

`"es.upv.paella.captionsEditorPlugin": {"enabled":true, "showSaveButton":false},`

on the list of plugins.

3. Run **npm run serve** you should be capable of view the editor if the video has captions added.

The standard test repository has some avaiable at:

**http://localhost:8000/player/index.html?id=webvtt-captions**

Enjoy!
