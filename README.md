# Photocraft V1.1 — The Photography Companion

**AI assists the person. It never replaces the photographer.**

## Product rule

**The camera creates. Photocraft teaches.**

V1.1 closes the core loop by adding a persistent **Personal Kit Bag** and **Scout**. The phone can scout a scene; the dedicated camera makes the final photograph.

## V1.1 journey

SEE → NOTICE → CHOOSE → SCOUT → SHOOT → REVIEW → RESHOOT → REMEMBER

- **Shoot:** camera-aware photographic problems, intentions and approaches.
- **Learn:** short lessons designed for a real camera.
- **Scout:** upload a quick wide phone reference; Photocraft suggests photographic opportunities using the user’s actual kit.
- **Review:** upload a photograph made with a dedicated camera; local visual measurements are translated into honest photographic observations.
- **Reshoot:** one-variable experiment generated from the review.
- **Project:** compact prompts for building a body of work.
- **Personal Kit Bag:** camera, format, lenses, support and accessories persist locally and influence recommendations.
- **Future equipment insight:** architecture is prepared for later analysis of actual use patterns, redundancy and capability gaps; V1.1 does not push purchases.

## Kit Bag principle

Photocraft should suggest **what you can make with what you own**, not generic gear recommendations. Future equipment suggestions should explain the photographic capability gained and should only appear after enough real usage data exists.

## Important boundary

The V1.1 Scout and Review engines use local image characteristics. They are intentionally not presented as human art direction or full vision-AI scene understanding. A future secure vision-AI backend can deepen both experiences without changing the photographer-first workflow.

## Deploy

Static site. Render can serve this repository using `render.yaml`.

## Validation

Run `node --check` on the inline JavaScript extracted from `index.html`, then perform live smoke tests on desktop and Android. V1.1 has not been declared 100% runtime-certified until those tests are completed.
