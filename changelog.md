CoffeeSCad: v0.1.0 3/11/2012
============================
   - Done: re-map the gl axes to the more understandable "Z-up" logic
   - Fixed: camera movement issues
   - Fixed: backbone localstorage persistence 
   - Fixed: add settings persistence
   - Fixed: views refresh when creating new file
   - Fixed: cannot save ProjectFile(s)
   - Fixed: issue with old model still appearing if there was a script error
   - Done: make the settings view actually set the settings
   - Fixed: save & load (ui side)
   - Fixed: grid/shadowing issues

CoffeeSCad: v0.2.0 3/12/2012
============================
   - Fixed: save & load (ui side)
   - Fixed: grid/shadowing issues
   - Fixed: add "console" view to see error output from script compiling
   - Done: allow resizing of main views 
   - Done: add various usefull enhancements to the code editor
   - Done: cleanup "App" code (as in , the Marionette.App instance)
   - Done: make grid , well, "gridier"
   - Fixed: add "syntaxic sugar" on top of csg.js
   - Fixed: add search & replace functionality for code
   - Fixed: add "include" statement to reference other files
   - Done: correctly define level of indentation for scripts
   - Done: handle edited but unsaved files correctly
   - Done: improve view controls 
   - Done: add finer grain option for csg compiling 
   - Done: add help and examples , accessible within the ui
   - Fixed: only open one editor at once

CoffeeSCad: v0.3.3 31/7/2013
============================
   - Fixed: add light rotation with camera
   - Fixed: cylinder doesn't move?
   - Fixed: recent project list viewing
   - Done: add theme support
   - Done: add a "BOM" (bill of materials) type system
   - Done: add openscad-like hull()
   - Done: code editor stays in front of other windows
   - Done: (Re) Add background processing for speedup
   - Done: define clearly the notions of part & assembly 
   - Done: windows Cakefile
   - Done: change axes size.
   - Fixed: add "actual" file browser 
   - Fixed: project deletion bug 
   - Fixed: panning
   - Done: find a way to create a library like system
   - Done: add log system
   - Done: allow passing in array of 2d shapes to hull
   - Done: code Editor too big
   - Fixed: bom issues
   - Done: "change" event triggering in case of compile failure
   - Done: using the coffeescad.org domain name
   - Done: object translation applied to original object not a copy
   - Done: aspect ratio of rendered object is relative to browser window. 
   - Done: parse error in src/app/config.coffee
   - Done: add "structural" object rendering 
   - Done: shadows
   - Done: add option to set grid numbering on the border of the grid
   - Done: grid transparency issues
   - Fixed: display correct line number for errors
   - Done: display log messages AND errors 
   - Done: make code editor window transparent
   - Done: add auto save
   - Fixed: solve Z-fighting issues
   - Fixed: grid numbering blurriness in the distance
   - Fixed: object (3d) visual style applying for complex hiearchies
   - Done: move to LESS for stylesheets
   - Done: dev
   - Done: code folding
   - Done: code Editor indentation problems
   - Fixed: correct self shadowing/ object to object shadows
   - Done: add code editor theming
   - Fixed: localstorage projects list erasion issue
   - Fixed: crash in project overwrite (etc) dialog
   - Done: add save/load of COMPILED assembly
   - Fixed: style sheet compile failure
   - Done: add option to reset settings to defaults
   - Fixed: browserStore project's list clearing bug
   - Fixed: add option to "dump" a full store
   - Fixed: thumbnails system
   - Done: parameters
   - Done: improve display of dimensions when selecting an object
   - Fixed: add volume calculation for objects
   - Fixed: add "crease edge"+"outline" detection shader 
   - Done: subtracting an intersecting shape
   - Fixed: issue with black screen at visual editor startup
   - Fixed: issue with visual editor lateral offset in firefox
   - Fixed: add option to turn outlines on /off
   - Fixed: axis overlay display
   - Fixed: slight outline bluriness issue after resize
   - Fixed: lessc compiling on recent version of node/less
   - Fixed: switching between orthographic and perspecitve 
   - Done: move view settings : ortho, left right etc to main toolbar
   - Fixed: bug with auto reloaded project -> new project -> compile not updating in stl and bom exporters
   - Fixed: bug : axis overlay should also be changed when switching view modes

