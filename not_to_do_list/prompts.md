# Project: Not To Do List

> - **Files:** not-to-do-list.html
> - **Dates:** 2026-11-03 → 2026-11-03
> - **Defaults:** Copilot SDK in VS Code · TBD
> - **Status:** prototype
> - **Use:** none yet
> - **Reusability:** artifact medium · prompt pattern medium
> - **Tags:** single-file-html, productivity
> - **Takeaway:** A small list app benefits from a deliberately constrained suggestion pool and a clear cap message.
> - **Story value:** anecdote
> - **Surprises:** TBD

# Prompt 1 (what this prompt is for):

> - **Tool:** Copilot SDK in VS Code · 2026-11-03
> - **Session:** fresh · attached: [CONVENTIONS.md]
> - **Verified:** agent-tested
> - **Human edits:** none

Review conventions.md.

Start a new project, "not_to_do_list".

Generate a list of 100-120 things that would be bad to do. For example: impractical things: "Don't try to board a spacecraft today." Or immoral things: "Don't deregulate sports betting." Or plays on traditional to-do list items: "Don't grocery shop, forget an item, and go back a second time in one day." The tone should be uniformly dry and tasklist-like.

The web app is a simple page with a plain header that says "Not To Do List". Beneath it, there's a to do list. It starts blank, but the user can either type their own entries in, or click "Add suggested list items" and five random items from the previously generated list will be added. Once the list is 20 items long, the button shouldn't add items anymore, it should throw a message like, "That's plenty of to-don't items for one day. Complete some of the existing items to add more."

Once a list item exists, there should be a check box where the user can click and mark it completed.

There's also a button that says "Clear list", that marks all items as completed and then empties the screen.

## Output 1:

Built [not-to-do-list.html](./not-to-do-list.html), a self-contained not-to-do list with 120 dry suggested items, custom entries, checkbox completion, a five-item random suggestion button capped at 20 items, and a clear button that completes and removes the list.

# Prompt 2 (what this prompt is for):

> - **Tool:** Copilot SDK in VS Code · 2026-11-03
> - **Session:** continued · attached: none
> - **Verified:** agent-tested
> - **Human edits:** none

Review each suggestion so it describes a possible task, relates to a classic to-do-list scenario, and avoids duplicates. Reduce the pool to approximately 80 high-quality suggestions. Also make the visual design neutral and add a light/dark mode toggle.

## Output 2:

Revised [not-to-do-list.html](./not-to-do-list.html) with 80 realistic work, home, planning, finance, health, and productivity suggestions, plus a neutral light/dark mode toggle with saved preference.
