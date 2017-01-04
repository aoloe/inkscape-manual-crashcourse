# Inkscape Crash Course

## Key Concepts

- A "path" is a collection of nodes connected by Bezier splines; nodes can connect them smoothly or in a cusp.
- A path has an outline (with color, line thickness, etc) and a fill (none, a flat color, or a gradient).
- An "object" is either a path, a constrained path (like a rectangle or a circle / arc), a bitmap, or a text, or a group of these. You can nest groups arbitrarily.

## Key tools

- Pointer, the arrow, shortcut F1. This is your main tool. Used to select, move, rotate, stretch objects. Shift-click to select multiple objects. Click-drag to select objects within a rectangle. Ctrl+click to select inside a group. Alt+click to select things under the object on top. Space bar switches between this tool and your other tools.
- Node pointer, the triangle, shortcut F2. Used to edit paths. Click-drag on a path to change curvature, or click on nodes to move / edit them, or ctrl+click to add a node, or drag the spline handles. Does different things to rectangles, circles, stars, by moving their control points.
- Rectangle (F4) and circle (F5) are good starting points for most things.
- Line / polygon drawing tool (Shift+F6). Click on places where you want nodes, press Enter to finish. Press F2 to move nodes and make segments curved.
- Curve drawing tool (F6). Click-drag to draw a freehand curve. Ctrl+L to smooth down the curve.
- Text tool (F8). Click where you want your text, type. When frustrated, press Esc, click the text, Shift+Ctrl+T, edit the text in a convenient dialog.

## Most useful actions:

- Cursor keys: move the selected object(s) by a small amount.
- Shift+Ctrl+F: fill / stroke dialog (if clicking on colors is not precise enough).
- Ctrl+D: duplicate the current object.
- Intersect and difference
- Ctrl+G: group selected objects, or ungroup a selected group.
- PgUp / Pgdn: move the object up / down in Z-order.
- Shift+Ctrl+A: align and distribute things.
- Shift+Ctrl+M: precisely transform things.
- Space: Switch back to pointer from your current tool.
- Press space, click+drag: scroll the window.

Context menus, accessible by right click, are your friends.

- Re symmetries: look at the star tool (press asterisk).
- Explore clones: clone an object with Shift+D, mirror it with H or V, then try editing the original object. Shift+D brings you from a clone to the original.
