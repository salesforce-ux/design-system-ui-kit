<p align="center">
<a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip"><img src="https://user-images.githubusercontent.com/1750832/41082861-8013ecba-69e4-11e8-8149-7eaa94825b19.png" alt="Design System UI Kit" /></a>
</p>
<br />
<h1 align="center" style="border-bottom:none;">Lightning Design System UI Kit</h1>
<p align="center">
A collection of Sketch Libraries including <a href="https://www.lightningdesignsystem.com">Lightning Design System</a> components and design patterns.
</p>
<h3 align="center"><a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip">» Download the latest kit now «</a></h3>
<br />
<br />

----

## Requirements

### Sketch

Download the most recent version of [Sketch](https://www.sketchapp.com/).

### Salesforce Sans fonts

1. [Download the Design System Zip](https://www.lightningdesignsystem.com/resources/downloads/)
2. Find the fonts located in the `/assets/fonts` directory
3. Install the fonts on your system

## Getting Started

**Welcome to the Summer ’18 Sketch Library kit**

The Salesforce UX team has made quite a few changes to this kit since the last release. We made optimizations so you can more efficiently create Salesforce Lightning interfaces. In the instructions below, we’ll cover the basics and some tips for you to get started with this Sketch Library kit. You can still use this kit just like you have in previous releases, but the Salesforce UX team believes these files are best used as a Sketch Libraries. What does that mean and why should you use them that way? We’ll answer those questions below.
<br />
<br />

**Why use these files as a Sketch Libraries?**

Sketch has released a feature that allowed any Sketch file’s symbols to be accessed and used across all of your Sketch documents. They called this feature Sketch Libraries. You can now have all SLDS components and patterns available from Sketch’s symbols menu in any file you open. Another powerful feature is that Sketch Libraries will automatically update your designs when the Library is updated. Your designs will never be out of date if they’re linked to this Sketch Library document.
<br />
<br />

**How to use these Sketch documents as a Sketch Libraries in two quick steps**

1. **Save this kit to your local computer**. To use this as a Sketch Library, first you’ll need to place this document somewhere permanent. Try saving it to, `Users/[YourName]/Documents/SLDS/` .
2. **“Add as Library” in the Sketch menu**. Next you need to open each SLDS Sketch Library document in this kit that you would like to use and select `File > Add as Library`. Boom! Now you’re all set. All SLDS components and patterns are available in your Sketch Symbols menu to use in any Sketch document you work in.

![You can see all of your Sketch Libraries in Sketch > Preferences > Libraries](https://user-images.githubusercontent.com/1750832/41635016-3aa5d32a-73fb-11e8-97dd-41cf9e940735.png)
<br />
<br />

**Artboards Everywhere**

Another big change we’ve made is we moved all components to their own artboards in the SLDS Component Library document. This makes finding the component symbol you want to use a breeze by mapping the lightningdesignsystem.com website’s menu, which you should be familiar with, to match the left hand artboard menu in Sketch.

![lightingdesignsystem.com Menu](https://user-images.githubusercontent.com/1750832/41117594-58d53dbc-6a42-11e8-82d9-7b188bbd2f74.png)
![SLDS Component Library Artboards](https://user-images.githubusercontent.com/1750832/41117593-58b16270-6a42-11e8-9585-372732bfe673.png)
<br />
<br />

**Nested Symbols Galore**

Sketch Symbols allow you to use and reuse a self-contained design element across a Sketch document. Any changes made to a symbol will update across your whole document. It’s really handy! Nested symbols allow for even more customization, without breaking the symbol from its source, by adding symbols in symbols. Nested symbols are used throughout this Sketch file so that you can customize your designs as much as possible without detaching your Symbol.

There is a backlog of SLDS component symbols that are not yet nested, but we’re actively working on getting 100% of symbols in a place where you can customize them without detaching. Once a symbol is detached, then you won’t receive automatic updates when a new a new kit is released.

Most nested symbols are denoted in this document’s structure under the folders called “z-embedded”. You should never need to add a symbol from those folders. Please ignore them. They contain symbols that are nested in the parent component symbol.

To see nested symbols in action, open any Sketch document and insert a symbol from the SLDS Component Library `Insert > Symbols > SLDS Component Library'. In Sketch’s right side panel you’ll see all the symbol overrides or customizations you can make to that symbol without having to detach the symbol--keeping the automatic update feature in tact.

![The right side overrides setion in Sketch allows for tab title and state to be customized](https://user-images.githubusercontent.com/1750832/41117591-587bdd58-6a42-11e8-8213-0b0c84f7eb21.png)
![The tab symbol uses nested symbols for Hover, Default and Selected states](https://user-images.githubusercontent.com/1750832/41117592-58941256-6a42-11e8-9be7-d9a8bbe9b339.png)
<br />
<br />

**Color Token Symbols**

Salesforce Lightning Design System uses design tokens as named entities that store visual design attributes. The SLDS Component Library document uses color symbols to mimic [Lightning Design System design tokens](https://www.lightningdesignsystem.com/design-tokens/) with color values. This allows the structure of a symbol to use the equivalent of a design token.

In symbols, like icons, that contain solid color backgrounds, you’ll find the background is a mask which reveals the color symbol as if it was a shape fill. This allows us to easily make file-wide changes to colors when new visual styles are introduced in SLDS. Instead of changing fill colors in hundreds of shapes in this document, we can just update a color symbol or point the shape to another color symbol.
<br />
<br />

## How to use the icon symbols

**Across Salesforce, you'll frequently see [Lightning Design System icons](https://www.lightningdesignsystem.com/icons/). We’ve constructed them to be easily used individually and as nested symbols. The steps below cover how to place icon symbols individually by using the SLDS Component Library as a Sketch Library**

1. **Choose an icon type**. SLDS has four types of icons. Utility icons are used for everything except Salesforce object icons. Utility icons are what you’ll want to use 95% of the time. Action icons are primarily used in mobile applications. Custom icons are to be used for custom Salesforce objects. Standard icons are used for standard Salesforce objects. 
2. **Place your icon type symbol**. Once you’ve chosen the type of icon you’d like to use (Utility, right?) place that symbol where you’d like in your Sketch document.
3. **Choose your icon glyph**. In Sketch’s right overrides panel, choose the icon glyph you’d like to use from the dropdown menu.
4. **(Optional) Choose an icon glyph color**. In Sketch’s right overrides panel, choose the icon glyph color you’d like to use from the dropdown menu.
5. **(Optional, for Action, Custom and Standard Icon Types) Choose an icon background color**. In Sketch’s right overrides panel, choose the icon background color you’d like to use from the dropdown menu.
<br />

## Lightning Design System Sketch Library Architecture

**SLDS Component Library** -> Base Library with SLDS components used in all SLDS Sketch documents

**SLDS Pattern - Builder** -> Extends SLDS Component Library and adds component customizations to be used specifically in SLDS Builder patterns

![SLDS Component Library is the base library. SLDS Pattern documents extend SLDS Component Library. Your designs can inherit any of the SLDS Sketch Library symbols!](https://user-images.githubusercontent.com/1750832/41634584-3e97204e-73f9-11e8-97c4-77a648f38768.png?s=100)
<br />
<br />

## Recommended Sketch Plugins

**Paddy**

Paddy allows you to add automated padding and spacing for Sketch layers. Paddy is used throughout this Sketch document. It is not required, but is extremely helpful when adding text overrides in a symbol and having the symbol adjust to your customization with perfect padding and spacing without having to detach the symbol from this Sketch Library.
https://github.com/DWilliames/paddy-sketch-plugin

**Runner**

Sketch Runner helps you to get around Sketch quicker by giving you an intuitive interface to run commands directly from your keyboard. Runner allows you to skip Sketch navigation, buttons or menus and quickly type the action you want to take like, “insert desktop tab” to add a tab component symbol to your artboard.
[https://sketchrunner.com](https://sketchrunner.com/)
<br />
<br />

## Contribute!

The SLDS team welcomes your help in maintaining and growing this UI kit.

Here are a few of the kinds of contributions we are looking for:

1. **Bug fixes:** fixing goofs in the Sketch file where what it has for a component doesn’t match what we are displaying for that component in the code-based documentation
2. **New Pattern:** sharing your design for arranging several components into a useful UI widget
3. **New Template:** sharing a more complex design that contains components and patterns arranged into an entire screen layout

### Got something to add?

Great! Please take a look at our [contribution guidelines](https://github.com/salesforce-ux/design-system-ui-kit/blob/master/CONTRIBUTING.md) for instructions on how to proceed.
<br />
<br />

## License

All icons and images are licensed under [Creative Commons Attribution-NoDerivatives 4.0](https://github.com/salesforce-ux/licenses/blob/master/LICENSE-icons-images.txt)
<br />
<br />
<p align="center">
<a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip"><img src="https://user-images.githubusercontent.com/1750832/41082860-7ffe3c1c-69e4-11e8-9b0f-813cf9be1395.png" alt="Design System UI Kit" /></a>
</p>
