# ES-Syntax-Highlighter

## Overview

Endless Sky syntax highlighter for Notepad++

`EScriptThemeLight.xml` is the User Defined Language for ES and is made to look nice with the Default Notepad++ theme (black text on a white background).

`EScriptThemeDark.xml` is the User Defined Language for ES and is made to look nice with the `Default Dark theme.xml` theme (white text on a black background). Default Dark theme is a global dark background for NP++. Regular text editing will look fine in this, but I haven't bothered to edit the other languages so they all look really weird.

This ES syntax highlighting was mostly made for mission development, because that is where the most errors happen. I did add some support for other parts of the ES code, there were waaaay too many keywords to deal with, but of feel free to clean up or add to the theme if you get frustrated with the lack of Map syntax highlighting or something.

## Installation: 

You should only install one of these two options (light or dark, depending on your preference):

### Light (Normal/Default) Notepad++ Theme

#### EScriptThemeLight.xml
  Under the `Language` menu, select `User Defined Language` -> `Define your language...`. The `User Defined Language` dialog should appear. Press  the `Import...` button, then navigate to and select `EScriptThemeLight.xml`. After import, select the theme called `Endless Sky Data` and then click the `Save As...` button and call it `Endless Sky Data File`. You can now delete the imported `Endless Sky Data` language. The syntax highlighting will now be available under the `Language` dropdown called `Endless Sky Data File` and all `.txt` files you load will automatically have the syntax highlighting applied.

### Dark Notepad++ Theme

#### EScriptThemeDark.xml
  Under the `Language` menu, select `User Defined Language` -> `Define your language...`. The `User Defined Language` dialog should appear. Press  the `Import...` button, then navigate to and select `EScriptThemeDark.xml`. After import, select the theme called `Endless Sky Data` and then click the `Save As...` button and call it `Endless Sky Data File`. You can now delete the imported `Endless Sky Data` language. The syntax highlighting  will now be available under the `Language` dropdown called `Endless Sky Data File` and all `.txt` files you load will automatically have the syntax highlighting applied.
  
#### Default Dark theme.xml
  Under the `Settings` dropdown menu, go to `Import` > `Import style theme(s)...`, then navigate to and select `Default Dark theme.xml`. Go back to the `Settings` dropdown, select `Style Configurator`, and under the Select Theme dropdown menu select the Default Dark theme option. Save & Close and you're all set. As long as you like dark themes. Otherwise, use the Light Theme version above.
