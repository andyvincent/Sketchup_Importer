# pyslapi
Python bindings for the official Sketchup API and an importer for blender based on them

# Release Note
* ##### 2024-01-03
    1. support `Blender 4.1 alpha`
    2. Support `Sketchup 2023.2`

* ##### 2022-02-12
    1.  Support `Blender 3.2`
    2. Supoort `Sketchup 2022`

* ##### 2021-03-29
    1. Support `Blender 2.93 Alpha `
    2. Support `Sketchup 2021`

* ##### 2020-07-14
    1. Support `Sketchup 2020`

# Install
1. download `sketchup_importer.zip
` from [Last Release](https://github.com/RedHaloStudio/Sketchup_Importer/releases)
2. open `Edit` → `Preferences` menu in Blender. At the `Add-ons` tab, use the Install button and locate the Add-on file. 
3. Enable the Add-on, and it will include an option to import SKP files in your `File` → `Import` menu in Blender.

# Building
Copy `sdk\headersSketchUpAPI` to python application `include`
Copy all files from `sdk\binaries\sketchup\x64` to python application `libs`


python setup.py build_ext --inplace