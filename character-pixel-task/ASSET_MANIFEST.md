# Asset manifest · 7 characters

## Important
The source image files and generated draft image files belong to the ChatGPT conversation and have **not yet been uploaded to GitHub**. The filenames below are exact expected names; these are not GitHub links. Attach or copy them into the indicated paths before image-dependent Codex work.

| Character | Source image expected at | First-round generated image expected at |
|---|---|---|
| Alyce | `character-pixel-task/references/Alyce(8).png` | `character-pixel-task/generated/Alyce.png` |
| Betty | `character-pixel-task/references/Betty(5).png` | `character-pixel-task/generated/Betty.png` |
| Ivy | `character-pixel-task/references/Ivy(2).png` | `character-pixel-task/generated/Ivy.png` |
| Jinny | `character-pixel-task/references/Jinny(2).png` | `character-pixel-task/generated/Jinny.png` |
| Lulu | `character-pixel-task/references/Lulu(3).png` | `character-pixel-task/generated/Lulu.png` |
| Qiana | `character-pixel-task/references/Qiana(3).png` | `character-pixel-task/generated/Qiana.png` |
| Xiu | `character-pixel-task/references/Xiu(3).png` | `character-pixel-task/generated/Xiu.png` |

## Existing generated drafts in the conversation
The user has seven Q-version pixel character turnaround drafts produced in the preceding ChatGPT image-generation turn. These are references only and require quality review against their matching source images. The conversation also contains a file named `imagegen.png`; do not rely on that ambiguous name to identify which character it depicts.

## Product-specific handling
The character sheets belong to an idol-companion visual project. Preserve distinct identity and silhouettes at the reduced sizes expected in indoor diorama scenes; check a 1× preview at intended in-app rendering scale. Do not invent character lore, personality, names beyond those above, or add unrequested props.

## Expected deliverables
```text
character-pixel-task/
  TASK.md
  ASSET_MANIFEST.md
  references/                 # 7 user-provided source images (pending transfer)
  generated/                  # 7 first-round ChatGPT pixel drafts (pending transfer)
  scripts/                    # preprocessing/verification tools (Codex to create)
  outputs/
    Alyce/{front,side,back,turnaround}.png
    Betty/{front,side,back,turnaround}.png
    Ivy/{front,side,back,turnaround}.png
    Jinny/{front,side,back,turnaround}.png
    Lulu/{front,side,back,turnaround}.png
    Qiana/{front,side,back,turnaround}.png
    Xiu/{front,side,back,turnaround}.png
    all-characters-preview.png
```
