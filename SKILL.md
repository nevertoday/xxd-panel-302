---
name: xxd-panel-302
description: "XXD Panel 302｜New Folk Emblem: keeps the photo and condenses its most recognisable subject into one small neo-naive handmade emblem — a wobbly hand-drawn contour, flat colour blocks with gouache and wax-crayon texture, gently exaggerated proportions, two to five warm, bright colours taken from the photo, paper grain and slight risograph misregistration, wide whitespace and a few tiny words or letters in a small hand-printed editorial type. Outputs PNG top-bottom or left-right comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. Use when the user invokes xxd-panel-302 or asks for a neo-naive folk emblem, handmade logo mark or risograph-style symbol from a photo."
---

# XXD Panel 302

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

The transformed design is one neo-naive emblem, not a scene and not a commercial logo. Use a wobbling hand contour, flat color blocks and simplified geometry. A very small related symbol may sit nearby, still not a scene. Gouache, crayon and risograph misregistration stay visible. Use two to five colors taken from the photograph, warm and clear, not candy-cartoon. The emblem is small in a large field. Type is a tiny independent-press word set apart. Reject a full figure illustration, 3D, smooth vector and a template.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-302/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-302-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
