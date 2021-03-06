---
title: Grid Column Pinning - Grid Feature
_description: The Grid Column Pinning is a mechanism to pin selected columns of a scrollable Grid.
_keywords: Design Systems, Design Systems UX, UI kit, Sketch, Ignite UI for Angular, Sketch to Angular, Sketch to Angular, Angular, Angular Design System, Export code from Sketch, Design Kits for Angular, Sketch HTML, Sketch to HTML, Sketch UI kits
---

## Grid Column Pinning

Use the Grid Column Pinning as a mechanism to fix the first few columns of a scrollable Grid to the left. Now, when the user scrolls, all other columns move left and right except for the pinned ones. The pinned columns always appear on top of the scrollable ones. The Grid Column Pinning is visually identical to the [Ignite UI for Angular Grid Column Pinning Feature](https://www.infragistics.com/products/ignite-ui-angular/angular/components/grid_column_pinning.html)

### Grid Column Pinning Demo

<img class="responsive-img" src="../images/grid_column_pinning_demo.png" srcset="../images/grid_column_pinning_demo@2x.png 2x" />

### Header Cell Feature

In order to pin a column use either the `Feature Left` or `Feature Right` overrides and set it to `Pinning`. Of course, you would probably also want to rearrange the column order so that the pinned ones come first when looking left to right.

### Cell Right Border

The right-most pinned column should have its `Right Border` override to indicate `Pinned Line` both for the Header and all Body Cells of the column. This shown on the image below for all cells of the second column since both the Row Selectors and the Subject columns are pinned.

<img class="responsive-img" src="../images/grid_column_pinning_demo.png" srcset="../images/grid_column_pinning_demo@2x.png 2x" />

## Additional Resources

Related topic:

- [Grid](grid.md)
  <div class="divider--half"></div>

Our community is active and always welcoming to new ideas.
