# Subtitle Chopstick

Chrome extension for translation team of cn.udacity.com, download vtt files with on click. Download and install from chrome with install from unpacked extension option.

### How it works

+ Grab all track tag of the page
+ Create a tag for each track element and set href of a tag to track.src
+ Trigger a tag by `a.click();`
+ Struggle with chrome extension manifest, permissions and pain in debugging...

### Todo List

+ Fixation: a.download attribute does not work when downloading vtt files, thus unable to rename them