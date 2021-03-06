---
title: Known Issues - Design System
_description: The issues and limitations that we are aware of with the guidance how to avoid or recover in case you run into them.
_keywords: Design Systems, Design Systems UX, UI kit, Sketch, Ignite UI for Angular, Sketch to Angular, Sketch to Angular, Angular, Angular Design System, Export code from Sketch, Design Kits for Angular, Sketch HTML, Sketch to HTML, Sketch UI kits
---

## Known Issues

This topic describes the issues and limitations we have run into or observed when using the Indigo Design Sketch Libraries. Where applicable we will be providing the necessary guidance to avoid the occurence of issues or recover from them once they occur.

### Detached Symbols

As you may have already seen in the other topics `Detach from Symbol` usually results in the loss of capability for code generation. However, a few components like the List and the Grid are basically repeaters of items and cells and come as a Generic~ that is supposed to be detached to allow you to create the number of items, rows and columns that you would need. As we enhance individual items with functionality in the upcoming versions of the libraries, such updates should propagate easily, however enhancements made to the collection of items named Generic~ will not propagate for detached instances of these components.

### Getting Invalid Overrides

When using nested overrides to customize the look and feel of a Component, we have discovered that sometimes after tweaking overrides deep in the nesting hierarchy and then changing an override above with a different underlying structure, Sketch gets confused and assigns values to this structure that are by no means appropriate for or matching it.

If you run in such a situation, just make sure that you pick the correct value for each on the underlying overrides and leave the Component in a valid state. Otherwise, it will not only reflect an impossible configuration, but will be impossible to read for our code generation engine.

### Images and Code Generation

In Sketch, there are two ways to insert images:

1.  Drag & drop an image onto an artboard
2.  Draw a Rectangle and set its Fill to be an image

Both of these are supported however the image will be generated with the dimensions defined in the Sketch file, and will not be responsive.

Images that were created using the first method above and are used as backgrounds will not be code generated as a background but as a normal image element.

Images that were created using the second method above and are used as backgrounds will be code generated as a background.

> [!Note]
> A future release will feature an Image Component that will generate code for responsive images.

### Illustrations and Code Generation

At the moment we support Illustrations only at design time and once you proceed to generate Angular code from your design, they will be skipped. However, if you still want to have the key visual as a code asset, you may export it as a PNG and insert it in your design file as an image.

> [!Note]
> A future release will handle Illustrations as SVG files in order to render them correclty with the colors applied as a theme.

### Currently Not Supported

The following Indigo.Design components are not implemented for code generation yet:

- Cards
- Navigation -> NavDrawer
- Calendar
- Dropdown

The following Sketch components are not implemented for code generation yet:

- Shapes
  - Line
  - Arrow
  - Star
  - Polygon
  - Triangle
- Vector
- Pencil
- Mask
- Elevation

> [!Note]
> Future releases will include these components.

### Proportional widths not completed

As this is not completed we give each element 100% width instead of calculating a specific percent based on their width relative to other row elements:
[Proportional Width Sizing](codegen/layout-codegen.md#proportional-width-sizing)

Our community is active and always welcoming to new ideas.
