# jk-easy-nodes

# Installation

## Manager

#TODO

## Manual install
1. Clone the repository:
`git clone https://github.com/kostenickj/comfyui-jk-easy-nodes.git`  
to your ComfyUI `custom_nodes` directory

- For uninstallation:
  - Delete the cloned repo in `custom_nodes`

## Manual Update
1. Navigate to the cloned repo e.g. `custom_nodes/comfyui-jk-easy-nodes`
2. `git pull`

# Features

## Custom Feed Window
A custom feed window that can be moved to another monitor
1. Grid mode or single image

## Custom Autocomplete (modified from ComfyUI-Custom-Scripts)
![image](https://github.com/pythongosssss/ComfyUI-Custom-Scripts/assets/125205205/b5971135-414f-4f4e-a6cf-2650dc01085f)  
A customized version of the custom autocomplete from pythongosssss' ComfyUI-Custom-Scripts that includes some bugfixes and the following features:
1. <b>FEATURE</b>: the ability to automatically insert preferred activation text and weight for a lora
   - ![image](todo)
2. Save and edit your preferences by opening the lora info via
   1. either right clicking a lora in the comfy ui sidebar
   2. clicking the info icon inside the autocomplete entry
   3. it will bring up the lora info dialog from ComfyUI-Custom-Scripts with some additional areas where you can set your preferences for the lora
      1. ![image](todo)
3. <b>FEATURE</b>: wildcard autocomplete
   - automatically detects installed wildcards in any extensions that support them (i think)
4. Add custom word files by putting them in the /tags dir of the extension, comes with danbooru.csv by default
   1. supports text or csv

NOTE: it will conflict with the original version if you have it installed, so disable one of them

<br>
<br>
