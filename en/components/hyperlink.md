---
title: Hyperlink - Design System Component
_description: The Hyperlink Component Symbol is used to allow the user follow a reference in a text paragraph. 
_keywords: Design Systems, Design Systems UX, UI kit, Sketch, Ignite UI for Angular, Sketch to Angular, Sketch to Angular, Angular, Angular Design System, Export code from Sketch, Design Kits for Angular, Sketch HTML, Sketch to HTML, Sketch UI kits
---

## Hyperlink

Use the Hyperlink Component to allow the user access additional information related to a styled piece of text in a paragraph like the mentioning of the Terms of Use or the Privacy Policy in a form.

### Hyperlink Demo

<img class="responsive-img" src="../images/hyperlink_demo.png" srcset="../images/hyperlink_demo@2x.png 2x" />

### Size

The Hyperlink comes in two different sizes matching the available sizes for paragraph text: a 16pt Body 1 and a 14pt Body 2.

<img class="responsive-img" src="../images/hyperlink_sizes.png" srcset="../images/hyperlink_sizes@2x.png 2x" />

### Styling

The Hyperlink can be styled through the Styling library by changing its default blue color to another one.

<img class="responsive-img" src="../images/calendar_styling.png" srcset="../images/calendar_styling@2x.png 2x" />

## Usage

Always choose a Hyperlink text color that makes it stand out in a paragraph. Avoid using the same color or similar nuances of it and pick a consistent color across your complete design.

| Do                                                                                   | Don't                                                                                    |
| ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| <img class="responsive-img" src="../images/hyperlink_do1.png" srcset="../images/hyperlink_do1@2x.png 2x" /> | <img class="responsive-img" src="../images/hyperlink_dont1.png" srcset="../images/hyperlink_dont1@2x.png 2x" /> |

## Code Generation

This section describes some important overrides and how they affect code generation.

> [!WARNING]
> Triggering `Detach from Symbol` on an instance of the Hyperlink in your design is very likely to result in loss of code generation capability for the Hyperlink.

### Event Property

When supplied, this property is used to create a method in the component TypeScript and add an Angular click signature in the HTML. When supplied the event must be specified using the curly braces format: {onEventName}.

### LinkURL

The LinkURL accepts a URL or a [binding](../codegen/data-binding.md). When supplied these values will be assigned to the href property on the HTML control.

- Example URL: http://www.infragistics.com
- Example binding: {companyWebsite}

### Text

The Text property may contain text, [binding text](../codegen/data-binding.md), or a combination of the two, examples:

- Settings
- {settingsLabel}
- Important {labelText}

When supplied the Text property is used to fill in the text to display for the Hyperlink.

## Additional Resources

Related topic:

- [Form Pattern](../patterns/form.md)
- [Data Binding](../codegen/data-binding.md)
  <div class="divider--half"></div>

Our community is active and always welcoming to new ideas.


