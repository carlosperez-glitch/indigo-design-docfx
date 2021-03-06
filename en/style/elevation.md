---
title: Elevation - Design System Styling
_description: The Elevation Symbols in Styling are used to mimic the relative position between surfaces stacked on top of one another.
_keywords: Design Systems, Design Systems UX, UI kit, Sketch, Ignite UI for Angular, Sketch to Angular, Sketch to Angular, Angular, Angular Design System, Export code from Sketch, Design Kits for Angular, Sketch HTML, Sketch to HTML, Sketch UI kits
---

## Elevation

Elevations are used across Components and Patterns to establish shadows that are floating elements, such as a Floating Action Button, Card, or a Login Form. These should cast on the underlying content and background. The Elevations in Styling are identical to the [Material Design Elevation](https://material.io/design/environment/elevation.html#) & [Ignite UI for Angular Shadows](https://www.infragistics.com/products/ignite-ui-angular/angular/components/shadows.html).

### Support for elevations

There are 24 Elevations available and the higher the number of the Elevation, the more prominent the shadow. Shadows come as a combination of three stacked shadow colors, umbra, penumbra, and ambient, whose values match the Material Design definition.

<img class="responsive-img" src="../images/elevation_people.png" srcset="../images/elevation_people@2x.png 2x" />

With the introduction of Library Styles in Sketch and our support for Shared Elevation Styles, we have applied the appropriate style to the correct layer inside of the Component, which is most often a Mask layer, or a specially designated `Elevation` native Sketch rectangle.

> [!Note]
> Changing the Elevation in a Component by changing its style is possible in Sketch and will produce the expected outcome, but the same will not be achievable with Ignite UI for Angular yet.

### Use of standalone elevations

It is also possible to use Elevation on its own to lift one part of the content and draw more focus to it than the rest. In such scenarios, simply drag the Elevation of your choice and match it to the size of the content you would like to enhance.

<img class="responsive-img" src="../images/elevation_standalone.png" srcset="../images/elevation_standalone@2x.png 2x" />

## Additional Resources

Related topics:

- [Button](../components/button.md)
- [Card](../components/cards.md)
- [Forms](../patterns/form.md)
  <div class="divider--half"></div>

Our community is active and always welcoming to new ideas.


