# Ride Start — empty starter

**PF 101 · Object-Oriented Programming · Pre-final**

Garage UI only. `js/` starts empty on purpose — you type every class.

## How to run

1. Open this folder in VS Code (or fork/clone your own copy).
2. Double-click `index.html` (or Live Server).
3. Create the files below. Browser 404s until each file exists — that is expected.

## Files you type

| Order | File | Job |
|---|---|---|
| 1 | `js/ride.js` | Parent — `start()`, `maxPassengers()`, `sakay(n)` |
| 2 | `js/jeepney.js` | Jeepney — `Para!` · max 18 |
| 3 | `js/tricycle.js` | Tricycle — `Broom broom` · max 4 |
| 4 | `js/motorcycle.js` | Habal-habal — `Vroom` · max **3** |
| 5 | `js/garage.js` | Composition — calls methods only, no `instanceof` |
| 6 | `js/main.js` | Wire the list, Start, and Sakay |

## Rules

- New project. Do not paste Fighter Arena or Campus Feed code.
- Garage never asks the ride type.
- Habal `sakay(10)` → illegal recruitment. `sakay(2)` → Swakto.

## Stretch (optional)

Add more rides later (`lantsa`, `tsinelas`, …). Garage stays the same — only `main.js` adds them, and you add a `<script>` tag before `garage.js` / `main.js`.

## Proof of done

1. Habal → Start → `Vroom`
2. Habal → passengers `10` → Sakay → illegal recruitment
3. Habal → passengers `2` → Sakay → Swakto
4. Paper: write `Motorcycle.maxPassengers()` with the file closed
