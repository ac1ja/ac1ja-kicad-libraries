# AC1JA's Custom KiCAD libraries


# Add this lib to a project

```
git submodule add https://github.com/ac1ja/ac1ja-kicad-libraries
```

If you want 3D models, you'll need to
open `Preferences` and `Configure Paths` then add the following enviorment variable:

```
Name: AC1JA_3DMODELS
Path: <Path to folder>
```

And if you use kibot, add this to your `pre_flight`

```
preflight:
  ...
  set_text_variables:
    - name: "AC1JA_3DMODELS" # 3D models for KenwoodFox Library
      command: "echo 'Hardware/Board/Libraries/ac1ja-kicad-libraries/3d'"
```

# Projects using this lib:

...
