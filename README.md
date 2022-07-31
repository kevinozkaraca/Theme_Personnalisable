# Thème personnalisable pour VSCode

## Comment personnaliser VSCode ?

![image](https://user-images.githubusercontent.com/80677798/182047090-4bc8d320-6817-430c-b123-2f399ff7c68e.png)

### 1. Télécharger une font qui vous plait et installer la sur votre ordinateur (exemple ici avec JetBrains Mono):

![image](https://user-images.githubusercontent.com/80677798/182047011-eb56d6c5-905d-4a6a-beae-1434b7832e4f.png)

Le nom à indiquer dans les parametres de VSCode est le nom indiqué lors de l'installation : "JetBrains Mono"

### 2. Choisir un thème qui vous plait

Rendez vous dans la section des extensions et tapez :

```
@category:"themes" @popular 
```
![image](https://user-images.githubusercontent.com/80677798/182046937-56a6dc24-f2b6-4988-8e9b-a5e20927d008.png)


### 3. Apres avoir installé votre thème, définissez votre thème (exemple ici avec le thème AYU - Light bordererd)

![image](https://user-images.githubusercontent.com/80677798/182047241-84c79d07-b20a-4317-bbdf-6e96fead0d23.png)

### 4. Selectionnez ce que vous voulez modifier : 

```
  "workbench.colorCustomizations": {
    "list.inactiveSelectionBackground": "#025591",
    "sideBar.background": "#f0f0f0",
    "sideBar.foreground": "#000000",
    "sideBarSectionHeader.background": "#287f9c",
    "sideBarSectionHeader.foreground": "#e4e4e4",
    "sideBarTitle.foreground": "#000000",
    "editor.background": "#f0f0f0",
    "editor.foreground": "#e4e4e4",
    "editorGroup.border": "#e4e4e4",
    "editor.findMatchBorder": "#ff0000", 
    "foreground": "#000000",
    "activityBar.border": "#7a7a7a",
    "activityBar.foreground":"#34e6fa",
    "activityBar.background": "#303030",
    "statusBar.background": "#3794a2",
    "badge.background": "#094050",
    "tab.activeBackground": "#f0f0f0",  
    "tab.activeForeground": "#ffffff",
    "tab.activeBorder": "#ffffff",
    "tab.inactiveBackground": "#363636",
    "titleBar.activeForeground": "#ffffff",
    "titleBar.activeBackground": "#484848",
    
},
"editor.tokenColorCustomizations": {
  "numbers": "#ec8740",
  "comments": "#87998b",
  "functions": "#eaea37",
  "keywords": "#4598dc",
  "variables": "#48d2f1",
  "types": "#24c23e",
  "strings": "#cd7783",
},
"editor.semanticTokenColorCustomizations": {
  "rules": {
      "keyword":"#4598dc",
      "variable": "#69c9de",
      "method": "#ffffff",
      "parameter": "#ffffff",
      "event": "#ffffff",
      "type": "#24c23e",
      "function": "#fafa36",
      "string": "#e66e7e",
      "label": "#ffffff",
      "module": "#ffffff",
      "number": "#63c73f",
      "namespace": "#ffffff",
      "operator": "#ffcc88",
      "typeParameter": "#ffffff",
      "selfParameter": "#ffffff",
      "comment": "#87998b",
      "property": "#257388", }
},
"workbench.colorTheme": "Default Light+"

```
