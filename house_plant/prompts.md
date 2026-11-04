# Project: House Plant

> - **Files:** house-plant.html
> - **Dates:** 2026-11-03 → 2026-11-03
> - **Defaults:** Copilot · AI assistant using Copilot SDK in VS Code
> - **Status:** prototype
> - **Use:** none yet
> - **Reusability:** artifact: TBD · prompt pattern: TBD
> - **Tags:** single-file-html, game, localStorage
> - **Takeaway:** TBD
> - **Story value:** TBD
> - **Surprises:** TBD

# Prompt 1 (house plant prototype):

> - **Tool:** Copilot · AI assistant using Copilot SDK in VS Code · 2026-11-03
> - **Session:** fresh · attached: [CONVENTIONS.md]
> - **Verified:** agent-tested
> - **Human edits:** none

Review conventions.

Make a new project called house_plant. It will start as a prototype. Also add it to index.html, and add a thumbnail.

It's a tomagatchi-style game called "House Plant". There should be a colorful, chaotic, and wonderful title screen, lots of bursting rainbow colors and leaves unfolding in a sort of cornocopia that holds the title ("House Plant"). There's a play button, which the user presses to dismiss this title screen and proceed to the game.

The game is 2D. There's a wall-mounted wood shelf (seen from the side, so, a rectangle) with a terra cotta pot on it. It has a house plant inside it, an aloe. The background is off-white. There's nothing else visible, just the shelf and the plant. There's a plain button next to the plant that says "water".

The user can mouse-over the base of the plant/the upper part of the pot to see the "Soil Moisture". The moisture is between 0.0000 and 5.0000. It is always displayed with those five decimals, e.x. 4.23448. It takes 7 to 10 days (the exact rate should be calculated randomly when the house plant "pet" is first instantiated, and re-calculated when the plant is watered) for the plant's moisture to decrease by 4.0000. Watering always adds between 3.7000 to 4.3000 (random, at time of watering) to the moisture.

If a plant spends too long - say 24 hrs - above 4.0000 moisture, it gets sick (see below). If a plant spends too long - say 24 hrs - below 1.0000 moisture, it gets sick and its health steadily decreases (at a rate of 1 per 24 hours) until it is out of the danger zone (either below 1 or above 4).

The player can mouse-over the upper leaves the house-plant to see the plant health, represented just like moisture (between 0.0000 and 5.0000). When the houseplant's mositure level is between 1.0000 and 4.0000 and the health is below full, the health steadily increases at a rate of 1.0000 per 860 hours.

## Output 1:

Built [house-plant.html](./house-plant.html), a self-contained prototype with a colorful title screen, playable water interaction, persistent plant state, four-decimal moisture and health readouts, and time-based sickness and recovery behavior. Added the project to the landing page and created an SVG thumbnail.

# Prompt 2 (scene cleanup):

> - **Tool:** Copilot · AI assistant using Copilot SDK in VS Code · 2026-11-03
> - **Session:** continued · attached: none
> - **Verified:** agent-tested
> - **Human edits:** Removed title screen subtitle

Remove the text on the screen: "a quiet corner" and the text readout "Your aloe is doing fine."

Move the aloe and pot visually down so that the pot sits on the shelf. Remove the "leg" on the shelf.

## Output 2:

Updated [house-plant.html](./house-plant.html) by removing the requested scene text, positioning the aloe and pot on the shelf, and removing the shelf support leg. Browser loading and JavaScript syntax were verified.
