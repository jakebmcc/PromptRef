
```
__________                               __ __________        _____ 
\______   \_______  ____   _____ _______/  |\______   \ _____/ ____\
 |     ___/\_  __ \/  _ \ /     \\____ \   __\       _// __ \   __\ 
 |    |     |  | \(  <_> )  Y Y  \  |_> >  | |    |   \  ___/|  |   
 |____|     |__|   \____/|__|_|  /   __/|__| |____|_  /\___  >__|   
                               \/|__|               \/     \/       

PromptRef — reference once, reuse forever
```

## Why PromptRef

Writing great AI prompts is hard when each chat window starts from a blank page. PromptRef removes that friction by letting you **store rich, inter‑linked prompt “building blocks”** (files, notes, background context) and paste them into any AI chat with a single click.

- **Pain:** No more scattered snippets or rewriting the same background every time.  
- **Gain:** Faster, repeatable prompt flows and consistent context injection.

The familiar split‑pane layout—directory, editor, preview—keeps source and output in sync and focuses on the specific job of **curating and reusing prompts**.

---

## Quick Start (60 seconds)

1. **Open** <https://prompref.com> — nothing to install; runs entirely client‑side (works in any modern Chromium‑based or Firefox browser).  
2. **Create a folder or note** in the left‑hand **Directory Pane**  
   * *Add Folder* ➜ groups related prompts  
   * *Add Note*   ➜ new Markdown file  
   * *Delete*     ➜ cleans as needed  
3. **Draft your prompt** in the middle **Editor Pane**.  
   * Type `/` to autocomplete and **reference any other note** inline.  
4. **Preview & copy**  
   * Right‑hand **Preview Pane** renders the full Markdown.  
   * Click **Copy** to grab the compiled text—references resolved—to your clipboard.  
5. **Paste into ChatGPT (or any LLM)**. Your entire prompt flow, background docs and all, arrive in one shot.

---

## UI Anatomy

| Pane | Purpose | Key Actions |
|------|---------|-------------|
| **Directory (left)** | Tree of folders & notes for deep prompt hierarchies. | `Add Folder`, `Add Note`, `Delete` |
| **Markdown Editor (center)** | Where you write prompts and drop `/references`. Live character‑pairing, syntax highlighting. | `/` auto‑link, standard Markdown |
| **Preview (right)** | Renders the full document, expanding every reference. | `Copy` (one‑click clipboard) |

---

## Tips & Best Practices

- **Think in blocks.** Store reusable “About Us”, “Tone Guide”, or dataset descriptions as separate notes; link them with `/`.  
- **Start with the task job.** Write the user request first, then pull in supporting context blocks.  
- **Keep folders purposeful.** Align them to products, clients, or prompt types (analysis, creative, debugging).  
- **Iterate fast.** Because everything is local, edits preview instantly; no network lag.  

---

## Roadmap & Feedback

PromptRef is an **early concept I’m dog‑fooding**. Planned explorations:

- Optional keyboard shortcuts (quick open, global reference palette)  
- Drag‑and‑drop folder re‑ordering  
- Export / import vaults  
- Community templates gallery  

> **Help shape the future**: open an issue or DM feedback from the site footer link.

---

Happy prompting! 🪄
