# Project: CORS Practice

> - **Files:** cors-practice.html
> - **Dates:** 2026-11-03 → 2026-11-03
> - **Defaults:** Copilot SDK in VS Code · TBD
> - **Status:** keeper
> - **Use:** used for actual education by the creator
> - **Reusability:** artifact: high · prompt pattern: low
> - **Tags:** single-file-html, teaching-example, drag-drop, theming
> - **Takeaway:** AI agents are great at making multiple choice tests, but not so good at making bespoke testing content
> - **Story value:** anecdote
> - **Surprises:** TBD

# Prompt 1 (what this prompt is for):

> - **Tool:** Copilot SDK in VS Code · 2026-11-03
> - **Session:** fresh · attached: [CONVENTIONS.md]
> - **Verified:** agent-tested
> - **Human edits:** adjusted title and subtitle

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

Built [cors-practice.html](./cors-practice.html), a self-contained progressive CORS practice app with nine scenarios covering origins, a concrete travel-blog image example, diagram labeling, a one-word OPTIONS checkpoint, browser-vs-network controls, credentials, multiple APIs, short answers, and request ordering. It includes immediate feedback, dark mode, accessible keyboard alternatives for drag-and-drop ordering, and guarded scenario transitions.

# Prompt 2 (what this prompt is for):

> - **Tool:** Copilot SDK in VS Code · 2026-11-03
> - **Session:** continued · attached: none
> - **Verified:** agent-tested
> - **Human edits:** none

Add more context to the learning materials, including a travel blog displaying an image from a country's tourism website, and a scenario distinguishing browser-level controls from network-level controls. Add more diverse interactions, including diagram labels and short-answer text boxes. Before longer short answers, add very short text answers for terms such as OPTIONS. Also fix the bug where repeatedly clicking "Next scenario" could advance too quickly.

## Output 2:

Expanded the learning sequence with richer real-world context, a browser-vs-network explanation scenario, diagram-labeling questions, a one-word OPTIONS checkpoint, and a preflight-header short-answer exercise. Added guarded scenario transitions so repeated clicks cannot skip scenarios, reset interaction state reliably, and validated the new interactions in the browser.
