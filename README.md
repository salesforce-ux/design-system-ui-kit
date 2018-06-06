<h1 align="center">Lightning Design System UI Kit</h1>

<p align="center">
<a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip"><img src="https://cloud.githubusercontent.com/assets/85783/15560157/af4a1abc-229d-11e6-9a3d-6c3f4b81220b.png" alt="Design System UI Kit" /></a>
<br />
<br />
A <a href="https://www.sketchapp.com/">Sketch</a> file of common design patterns from the <a href="https://www.lightningdesignsystem.com">Lightning Design System</a>.
<br />
</p>
<h3 align="center"><a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip">» Download the latest version «</a></h3>
<br />

[![UI Kit Preview](https://user-images.githubusercontent.com/12544709/34635155-66068cc2-f240-11e7-9043-e6b77b4e5ff4.png)](https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip)


----

## Requirements

### Sketch

Download the most recent version of [Sketch](https://www.sketchapp.com/).

### Salesforce Sans fonts

1. [Download the Design System Zip](https://www.lightningdesignsystem.com/resources/downloads/)
2. Find the fonts located in the `/assets/fonts` directory
3. Install the fonts on your system

## Getting Started

**Welcome to the Summer ’18 Sketch Library document**

The Salesforce UX team has made quite a few changes to this document since the last release. We made optimizations so you can more efficiently create Salesforce Lightning interfaces. In the instructions below, we’ll cover the basics and some tips for you to get started with this Sketch Library document. You can still use this document just like you have in previous releases, but the Salesforce UX team believes this file is best used as a Sketch Library. What does that mean and why should you use it that way? We’ll answer those questions below.

**Why use this file as a Sketch Library?**

Sketch has released a feature that allowed any Sketch file’s symbols to be accessed and used across all of your Sketch documents. They called this feature Sketch Libraries. You can now have all SLDS components available from Sketch’s symbols menu in any file you open. Another powerful feature is that Sketch Libraries will automatically update your designs when the Library is updated. Your designs will never be out of date if they’re linked to this Sketch Library document.

**How to use this document as a Sketch Library in two quick steps**

1. **Save this file to your local computer**. To use this as a Sketch Library, first you’ll need to place this document somewhere permanent. Try saving it to, `Users/[YourName]/Documents/SLDS/` .
2. **“Add as Library” in the Sketch menu**. Next you’ll want to open the SLDS Component Library document and select `File > Add as Library` . Boom! Now you’re all set. All SLDS components are available in your Sketch Symbols menu to use in any Sketch document you work in. You can close SLDS Component Library document.

**Artboards Everywhere**

Another big change we’ve made with this Sketch Library document is we moved all components to their own artboards. This makes finding the component symbol you want to use a breeze by mapping the lightningdesignsystem.com website’s menu, which you should be familiar with, to match the left hand artboard menu in Sketch.

**Nested Symbols Galore**

Sketch Symbols allow you to use and reuse a self-contained design element across a Sketch document. Any changes made to a symbol will update across your whole document. It’s really handy! Nested symbols allow for even more customization, without breaking the symbol from its source, by adding symbols in symbols. Nested symbols are used throughout this Sketch file so that you can customize your designs as much as possible without detaching your Symbol.

There is a backlog of SLDS component symbols that are not yet nested, but we’re actively working on getting 100% of symbols in a place where you can customize them without detaching. Once a symbol is detached, then you won’t receive automatic updates when a new SLDS Component Library document is released.

Most nested symbols are denoted in this document’s structure under the folders called “z-embedded”. You should never need to add a symbol from those folders. Please ignore them. They contain symbols that are nested in the parent component symbol.

To see nested symbols in action, add a symbol from the SLDS Component Library to your Sketch document. In Sketch’s right side panel you’ll see all the symbol overrides or customizations you can make to that symbol without having to detach it and keeping the automatic update feature in tact.

**Color Token Symbols**

Salesforce Lightning Design System uses design tokens as named entities that store visual design attributes. This Sketch document uses color symbols to mimic SLDS design tokens with color values. This allows the structure of a symbol to use the equivalent of a design token.

In symbols, like icons, that contain solid color backgrounds, you’ll find the background is a mask which reveals the color symbol as if it was a shape fill. This allows us to easily make file-wide changes to colors when new visual styles are introduced in SLDS. Instead of changing fill colors in hundreds of shapes in this document, we can just update a color symbol or point the shape to another color symbol.

## How to use the icon symbols

**Icons are used frequently across Lightning Design System. We’ve constructed them to be easily used individually and as nested symbols. The steps below cover how to place icon symbols individually.**

1. **Choose an icon type**. SLDS has four types of icons. Utility icons are used for everything except Salesforce object icons. Utility icons are what you’ll want to use 95% of the time. Action icons are primarily used in mobile applications. Custom icons are to be used for custom Salesforce objects. Standard icons are used for standard Salesforce objects. 
2. **Place your icon type symbol**. Once you’ve chosen the type of icon you’d like to use (Utility, right?) place that symbol where you’d like in your Sketch document.
3. **Choose your icon glyph**. In Sketch’s right overrides panel, choose the icon glyph you’d like to use from the dropdown menu.
4. **(Optional) Choose an icon glyph color**. In Sketch’s right overrides panel, choose the icon glyph color you’d like to use from the dropdown menu.
5. **(Optional, for Action, Custom and Standard Icon Types) Choose an icon background color**. In Sketch’s right overrides panel, choose the icon background color you’d like to use from the dropdown menu.

## Recommended Sketch Plugins

**Paddy**

Paddy allows you to add automated padding and spacing for Sketch layers. Paddy is used throughout this Sketch document. It is not required, but is extremely helpful when adding text overrides in a symbol and having the symbol adjust to your customization with perfect padding and spacing without having to detach the symbol from this Sketch Library.
https://github.com/DWilliames/paddy-sketch-plugin

**Runner**

Sketch Runner helps you to get around Sketch quicker by giving you an intuitive interface to run commands directly from your keyboard. Runner allows you to skip Sketch navigation, buttons or menus and quickly type the action you want to take like, “insert desktop tab” to add a tab component symbol to your artboard.
[https://sketchrunner.com](https://sketchrunner.com/)

## Contribute!

The SLDS team welcomes your help in maintaining and growing this UI kit.

Here are a few of the kinds of contributions we are looking for:

1. **Bug fixes:** fixing goofs in the Sketch file where what it has for a component doesn’t match what we are displaying for that component in the code-based documentation
2. **New Pattern:** sharing your design for arranging several components into a useful UI widget
3. **New Template:** sharing a more complex design that contains components and patterns arranged into an entire screen layout

### Got something to add?

Great! Please take a look at our [contribution guidelines](https://github.com/salesforce-ux/design-system-ui-kit/blob/master/CONTRIBUTING.md) for instructions on how to proceed.

## License

All icons and images are licensed under [Creative Commons Attribution-NoDerivatives 4.0](https://github.com/salesforce-ux/licenses/blob/master/LICENSE-icons-images.txt)
