for highlighting errors etc by linters we will expose apis for that that linters can use 

```
get.errors.in.editor()
get.warnings.in.editor()
get.diagnostics.in.editor()

add.error.in.editor()
add.warning.in.editor()
add.info.in.editor()
add.hint.in.editor()

set.diagnostics.in.editor()
clear.diagnostics.in.editor()
clear.errors.in.editor()
clear.warnings.in.editor()

highlight.error.line.in.editor()
highlight.error.range.in.editor()
clear.error.highlights.in.editor()

show.error.hover.in.editor()
hide.error.hover.in.editor()

goto.next.error.in.editor()
goto.previous.error.in.editor()
goto.next.warning.in.editor()
goto.previous.warning.in.editor()

apply.quick.fix.in.editor()
get.available.quick.fixes.in.editor()

```
