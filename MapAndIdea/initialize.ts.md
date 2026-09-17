## initialize the following components

bottom-bar.ts

chain.ts

editorMain.ts

external-api.ts

import.ts
	
initialize.ts

internal-sidebar.ts

main.ts

right-click-context.ts

search.ts

sideSerial.ts

top-bar.ts

---

check the DIR status of the files are they present at the right dir location or not.

---

## theme initialization 

[ Start: App Launch ]
         |
         v
  / Check Cache \
 <  Is Theme     > --- ( Yes ) ---> [ Run Cached Theme ] ---> [ Theme Loaded ]
  \ Cached?     /
         |
      ( No )
         |
         v
[ Read preference.editor.json ]
         |
         v
[ Identify Theme File Name ]
         |
         v
  / Check File System \
 <  Does Theme File    > --- ( No ) ---> [ Load Default Theme ] ---> [ Theme Loaded ]
  \ Exist?            /
         |
      ( Yes )
         |
         v
[ Run / Load Theme ]
         |
         v
[ Cache Theme Data ]
         |
         v
[ Theme Loaded ]


--------------------------------------------------------------------------------

[ User Triggers "Flush Cache" ]
         |
         v
[ Clear Saved Theme Cache ]
         |
         v
( Next launch skips cache and re-reads preference.editor.json )
