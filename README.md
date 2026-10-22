# Sazenka – planting plans from D5 Render for Archicad

**Sazenka** turns the plants you placed in **D5 Render** into a planting plan for **Archicad**:
50 plant symbols, boxed T/P labels (type / quantity), lines joining plant groups, areas for plants painted with the D5 brush and a plant schedule.

![Sazenka](https://kadcad.cz/static/sazenka/screenshot.jpg)

- 🌐 **Web version (no install):** https://kadcad.cz/sazenka
- 🧩 **Archicad 29 add-on:** in preparation – it will place native Archicad objects with element ID and plant name, so Interactive Schedules count the plants. Downloads will appear under [Releases](../../releases).

Languages: čeština, slovenčina, polski, українська, English, Deutsch, magyar, hrvatski/srpski, español.

## How it works
1. Save the scene in D5 (Ctrl+S).
2. In Sazenka choose the D5 project folder (the one with the `.drs` file).
3. Check the plants – name, category, symbol, diameter, colour. The catalogue remembers your choices.
4. Download the DXF and, in Archicad, use **File → Interoperability → Merge** (unit 1 metre, insertion point 0; 0). Then select everything on the `PP_*` layers and use **Display Order → Bring to Front**.

D5 stores plant positions in the coordinates of the model synced via **LiveSync**, so the plants land exactly on your Archicad model.
Your D5 project stays on your computer – only plant names and positions are sent to compute the plan.

## Česky
Sazenka z rostlin rozmístěných v D5 Render vytvoří osazovací plán pro Archicad: symboly, popisky T/P v rámečku,
spojnice skupin, plochy rostlin malovaných štětcem a výkaz rostlin. Webová verze: https://kadcad.cz/sazenka

## Українською
Sazenka перетворює рослини, розставлені в D5 Render, на посадковий план для Archicad: символи, підписи T/P,
з'єднувальні лінії груп, області рослин, намальованих пензлем, і відомість рослин. Веб-версія: https://kadcad.cz/sazenka

## Feedback
Found a bug or missing a feature? Open an [issue](../../issues) – attach the D5 project's `asset/1.save` if you can.

## Support
Sazenka is free. If it saves you time, you can support further development (link coming soon).

---
© 2026 Vladyslav Barkov · Barkov Studio. Free to use; see [LICENSE](LICENSE.md).
D5 Render is a trademark of D5 Render; Archicad is a trademark of Graphisoft SE. Sazenka is an independent tool and is not affiliated with them.
