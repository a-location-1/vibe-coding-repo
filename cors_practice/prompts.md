# Project: CORS Practice

> - **Files:** cors-practice.html
> - **Dates:** 2026-11-03 → 2026-11-03
> - **Defaults:** Copilot SDK in VS Code · TBD
> - **Status:** prototype
> - **Use:** none yet
> - **Reusability:** artifact high · prompt pattern medium
> - **Tags:** single-file-html, teaching-example, drag-drop, theming
> - **Takeaway:** TBD
> - **Story value:** anecdote
> - **Surprises:** TBD

# Prompt 1 (what this prompt is for):

> - **Tool:** Copilot SDK in VS Code · 2026-11-03
> - **Session:** fresh · attached: [CONVENTIONS.md]
> - **Verified:** agent-tested
> - **Human edits:** none

Review conventions.md.

We're going to make a project called "cors_practice". It's a web app that presents a series of scenarios that help the user get familiar with how CORS functions.

Example scenarios:
1. An abstract scenario: Website A requests a resource from Website B, etc.
2. A blog scenario: the blog requests an image from...
3. A frontend/backend setup involving an API.
4. A setup involving multiple external APIs.

Example interactions:
- The user might be presented with a scenario via diagram and asked to label which requests are allowed and which are rejected.
- The user might label certain requests with the appropriate code, like OPTIONS.
- The user might be asked to drag and drop items into the correct order, and the items describe the steps of how CORS plays out.

The scenarios should be progressive, it should start very simple and each scenario should add an additional element, vocabulary set, or wrinkle. By the end of the scenarios, the user should have a strong grasp of the different contexts in which CORS is used, and how it functions.

## Output 1:

Built [cors-practice.html](./cors-practice.html), a self-contained progressive CORS practice app with six scenarios covering origins, resource display, OPTIONS preflight, credentials, multiple APIs, and request ordering. It includes diagrams, immediate feedback, dark mode, and accessible drag-and-drop ordering controls.
