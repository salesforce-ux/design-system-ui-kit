<p align="center">
<a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip"><img src="https://user-images.githubusercontent.com/1750832/41082861-8013ecba-69e4-11e8-8149-7eaa94825b19.png" alt="Design System UI Kit" /></a>
</p>
<br />
<h1 align="center" style="border-bottom:none;">Lightning Design System UI Kit</h1>
<p align="center">
A collection of Sketch Libraries including <a href="https://www.lightningdesignsystem.com">Lightning Design System</a> components and design patterns.
</p>
<p align="center"><i>Always stay up to date by installing the latest SLDS Component Library as a Sketch Library.</i>
<br />
  <strong>» Copy/paste the URL below in any browser address bar «</strong></p>
<h3 align="center"><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-rss.xml</code></h3>
<p align="center"><a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip">or download the latest</a></p>
<br />
<br />

----

## Requirements

### Sketch

Download the most recent version of [Sketch](https://www.sketchapp.com/).

### Salesforce Sans fonts

1. Download the [Salesforce Sans fonts](https://github.com/salesforce-ux/design-system/tree/master/assets/fonts) from the Design System repository
2. Install the fonts on your system

## Getting Started

**Welcome to the Spring '19 SLDS Component Library Sketch UI Kit**

The Salesforce UX team has made optimizations with this Sketch Library so you can more efficiently create Salesforce Lightning interfaces. In the instructions below, we’ll cover the basics and some tips for you to get started. You can still use this SLDS Component Library Sketch UI Kit just like you have in previous releases, by downloading it, but the Salesforce UX team believes these files are best used as a Sketch Library.

Sketch Libraries allow you to have SLDS components and patterns available from Sketch’s symbols menu in any file you open. Sketch Libraries will automatically update your designs when the library is updated. Your designs will never be out of date if they’re linked to this Sketch Library document.
<br />
<br />

**How to use the SLDS Component Library as a Sketch Library**

Copy and paste this link in any browser: `sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-rss.xml`. This will subscribe your Sketch application to automatically download and install new versions of the SLDS Component Library Sketch UI Kit.

![You can see all of your Sketch Libraries in Sketch > Preferences > Libraries](https://user-images.githubusercontent.com/1750832/41635016-3aa5d32a-73fb-11e8-97dd-41cf9e940735.png)
<br />
<br />

**Artboard Navigation**

All components have their own artboards in this SLDS Component Library document. Finding the component symbol you want to use a breeze since the lightningdesignsystem.com website menu is mapped to the Sketch artboard list.

![lightingdesignsystem.com Menu](https://user-images.githubusercontent.com/1750832/41117594-58d53dbc-6a42-11e8-82d9-7b188bbd2f74.png)
![SLDS Component Library Artboards](https://user-images.githubusercontent.com/1750832/41117593-58b16270-6a42-11e8-9585-372732bfe673.png)
<br />
<br />

**Nested Symbols**

Sketch Symbols allow you to use and reuse a self-contained design element across a Sketch document. Any changes made to a symbol will update across your whole document. It’s really handy! Nested symbols allow for even more customization, without breaking the symbol from its source, by adding symbols inside other symbols. These nested symbols are used throughout the Sketch file so that you can customize your designs as much as possible without detaching your Symbol.

To see nested symbols in action, open any Sketch document and insert a symbol from the SLDS Component Library `Insert > Symbols > SLDS Component Library`. In Sketch’s right side panel you’ll see all the symbol overrides or customizations you can make to that symbol without having to detach the symbol--keeping the automatic update feature in tact.

![The right side overrides setion in Sketch allows for tab title and state to be customized](https://user-images.githubusercontent.com/1750832/41117591-587bdd58-6a42-11e8-8213-0b0c84f7eb21.png)
![The tab symbol uses nested symbols for Hover, Default and Selected states](https://user-images.githubusercontent.com/1750832/41117592-58941256-6a42-11e8-9be7-d9a8bbe9b339.png)
<br />
<br />

**Color Token and Typography Layer Styles**

Salesforce Lightning Design System uses design tokens as named entities that store visual design attributes. The SLDS Component Library uses Sketch Layer Styles and Sketch Text Styles to mimic [Lightning Design System design tokens](https://www.lightningdesignsystem.com/design-tokens/). This allows Sketch designs to use the equivalent of a design token--saving you time spec'ing your designs for development.

In symbols, like icons, that contain solid color backgrounds, you’ll find the background is a layer style which defines the icon background. This allows us to easily make file-wide changes to colors when new visual styles are introduced in SLDS. Instead of changing fill colors individually in hundreds of shapes in this document, we can just update a color symbol or point the shape to another color symbol.
<br />
<br />

## How to use icon symbols

**Across Salesforce, you'll frequently see [Lightning Design System icons](https://www.lightningdesignsystem.com/icons/). We’ve constructed them to be easily used individually and as nested symbols. The steps below cover how to place icon symbols individually by using the SLDS Component Library as a Sketch Library**

1. **Choose an icon type**. SLDS has four types of icons. Utility icons are used for everything except Salesforce object icons. Utility icons are what you’ll want to use 95% of the time. Action icons are primarily used in mobile applications. Custom icons are to be used for custom Salesforce objects. Standard icons are used for standard Salesforce objects. 
2. **Place your icon type symbol**. Once you’ve chosen the type of icon you’d like to use (Utility, right?) place that symbol where you’d like in your Sketch document.
3. **Choose your icon glyph**. In Sketch’s right overrides panel, choose the icon glyph you’d like to use from the dropdown menu.
4. **(Optional) Choose an icon glyph color**. In Sketch’s right overrides panel, choose the icon glyph color you’d like to use from the dropdown menu.
5. **(Optional, for Action, Custom and Standard Icon Types) Choose an icon background color**. In Sketch’s right overrides panel, choose the icon background color you’d like to use from the dropdown menu.
<br />

## SLDS Component Library Sketch File Architecture

**SLDS Component Library** -> Base Library with SLDS components used in all SLDS Sketch documents

**SLDS Pattern - Builder** -> Extends SLDS Component Library and adds component customizations to be used specifically in SLDS Builder patterns

![SLDS Component Library is the base library. SLDS Pattern documents extend SLDS Component Library. Your designs can inherit any of the SLDS Sketch Library symbols!](https://user-images.githubusercontent.com/1750832/41634584-3e97204e-73f9-11e8-97c4-77a648f38768.png?s=100)
<br />
<br />


## Contributing, Feature Requests and Bug Reporting

The SLDS team welcomes your help in maintaining the SLDS Component Library. Please add any bugs or feature requests under the [Issues](https://github.com/salesforce-ux/design-system-ui-kit/issues) tab of this repository.

**Public contributions are currently closed.** Salesforce designers contribute to this kit while designing Salesforce releases through an application called Abstract. These releases are completed four months before being released to the public, therefore public contributions to this kit are essentially contributing to a four month old stale release. This become unmanagable to merge Sketch binary files and isn't fair to contributors who work hard on a contribution only to have it closed without a merge.
<br />
<br />


## License

All icons and images are licensed under [Creative Commons Attribution-NoDerivatives 4.0](https://github.com/salesforce-ux/licenses/blob/master/LICENSE-icons-images.txt)
<br />
<br />
<p align="center">
<a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip"><img src="https://user-images.githubusercontent.com/1750832/41082860-7ffe3c1c-69e4-11e8-9b0f-813cf9be1395.png" alt="Design System UI Kit" /></a>
</p>
