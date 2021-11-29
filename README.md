# FL Settings

## FL Folders
Fruity loop path
C:\Program Files\Image-Line\FL Studio 20

32bit VSTs path (asked at FL installation)
C:\Program Files\Common Files\VST2\

32bit VSTs path (asked at FL installation)
C:\Program Files\Common Files (x86)\VstPlugins

## Plugins
Program files x86 contains 32 bit apps, and program files contain 64 bit apps
*VST3 is the new standard, more efficient, should be used when possible.
VST and VST2 should only be used when compatibility issues are encountered.
*The plugin scanner will find 3 Formats for plugins: FL, VST, and VST3.
FL is for FL stock plugins, while
### Other places with plugins

### 64 bit versions
C:\Program Files\Image-Line\FL Studio 20\Plugins\Fruity (effects and generators in subfolders)
C:\Program Files\Common Files     # VST2 and VST3 separated in subfolders

### 32 bit versions
C:\Program Files (x86)\Steinberg  # Izotope plugins are placed here upon installation
C:\Program Files (x86)\VstPlugins # contains stock FL plugins (FL format)

## Instructions

This repository manages custom settings and presets that should be saved from the
C:\Users\"user"\Documents\Image-Line folder containing all user data.

Save personal settings by starting their name with "my" otherwise they will be discarded.

FL project .flp files will be saved, but without their project bones.

##Installation
clone the repository in a temporary location, i.e. C:\Users\"user"\Documents\FL_settings
copy the .git folder to the intended location, i.e. C:\Users\"user"\Documents\Image-Line
change the repo location when prompted that the repo location has changed or was deleted
Virgin FL studio documents will show unstaged file deletions, can discard these changes
Delete the previous temporary repo location