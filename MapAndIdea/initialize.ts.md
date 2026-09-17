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

```markdown
[ App Start ]
   ↓
( Is Theme Cached? )
   ├── [ YES ] ──> [ Run Cached Theme ] ──> [ Theme Active ]
   └── [ NO  ] ──> [ Read preference.editor.json ]
                         ↓
                   [ Identify Theme File Name ]
                         ↓
                   ( Does File Exist? )
                      ├── [ YES ] ──> [ Run Theme ] ──> [ Cache Theme ] ──> [ Theme Active ]
                      └── [ NO  ] ──> [ Load Default Theme ] ─────────────> [ Theme Active ]


[ Flush Cache Action ] ──> [ Delete Saved Cache ] ──> ( Forces JSON re-read on next launch )

```
