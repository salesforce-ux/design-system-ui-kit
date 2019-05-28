<p align="center">
<a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip"><img src="https://user-images.githubusercontent.com/1750832/41082861-8013ecba-69e4-11e8-8149-7eaa94825b19.png" alt="Design System UI Kit" /></a>
</p>
<br />
<h1 align="center" style="border-bottom:none;">Salesforce Lightning Design System (SLDS) UI Kit</h1>
<p align="center">
The SLDS UI Kit is a collection of Sketch Libraries of <a href="https://www.lightningdesignsystem.com">Lightning Design System</a> components and design patterns. The thousands of customers and partners who build applications on the Salesforce platform can use these resources to quickly visualize and test designs before they're implemented in their Salesforce organizations.
</p>
<p align="center">Install and always stay up to date by subscribing to the Sketch Library links below.
<br />
<strong>» Copy/paste the URLs below in any browser address bar «</strong></p>
<ol>
<li><b>Component Library</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-rss.xml</code></li>
<li><b>Builder Patterns</b> (optional)
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-builder-rss.xml</code></li>
<li><b>Chart Patterns</b> (optional)
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-chart-rss.xml</code></li>
<li><b>Rules, Filters, and Logic Patterns</b> (optional)
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-rfl-rss.xml</code></li>
<li><b>User Engagement Patterns</b> (optional)
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-user-engagement-rss.xml</code></li>
</ol>
<br />
<p align="center"><a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip">or download and install these files manually</a></p>
<br />
<br />

----

## Requirements

### Sketch

Download the most recent version of [Sketch](https://www.sketchapp.com/).
<br />
<i>These files are optimized for Sketch but if you don't have it you can use a free application with less functionality called <a href="https://www.figma.com/" target="_blank" title="Figma">Figma</a> instead</i>

### Salesforce Sans fonts

1. Download the [Salesforce Sans fonts](https://github.com/salesforce-ux/design-system/tree/master/assets/fonts) from the Design System repository
2. Install the Salesforce Sans fonts on your system

<br />
<br />

## Getting Started

**Welcome to the Summer '19 Salesforce Lightning Design System (SLDS) Sketch UI Kit**

The Salesforce UX team has made optimizations with this Sketch Library so you can more efficiently create Salesforce Lightning interfaces. In the instructions below, we’ll cover the basics and some tips for you to get started. You can still use this SLDS Component Library Sketch UI Kit just like you have in previous releases, by downloading it, but the Salesforce UX team believes these files are best used as a Sketch Library.

Sketch Libraries allow you to have SLDS components and patterns available from Sketch’s symbols menu in any file you open. Sketch Libraries will automatically update your designs when the library is updated. Your designs will never be out of date if they’re linked to this Sketch Library document.
<br />
<br />

**How to use the SLDS Sketch UI Kits as Sketch Libraries**

Copy and paste the following links, one by one, in any browser. This will subscribe your Sketch application to automatically download and install new versions of the SLDS Sketch UI Kits.

1. Component Library
   * <code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-rss.xml</code>
2. Builder Patterns (optional)
   * <code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-builder-rss.xml</code>
3. Chart Patterns (optional)
   * <code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-chart-rss.xml</code>
4. Rules, Filters, and Logic Patterns (optional)
   * <code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-rfl-rss.xml</code>
5. User Engagement Patterns (optional)
   * <code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-user-engagement-rss.xml</code>

Alternatively, download the Sketch Libraries in this repository you'd like to install. Open `Sketch > Preferences > Libraries` and click `Add Library...`. Select the library you'd like to install.

Verify that you've successfully installed the Sketch Libraries by opening `Sketch > Preferences > Libraries`. You should see all of the libraries you installed above.

![You can see all of your Sketch Libraries in Sketch > Preferences > Libraries](https://user-images.githubusercontent.com/1750832/41635016-3aa5d32a-73fb-11e8-97dd-41cf9e940735.png)
<br />
<br />

**That's it! Now you can supercharge your designs for the Salesforce platform.**

<br />
<br />

## How to Structure your Sketch project

The SLDS UI Kit is optimized to mimic the code structure of a design system but within the bounds of Sketch. The main resource is the SLDS Component Library. This file is a replica of SLDS components and tokens. Also in the kit are multiple pattern files. These files inherit symbols from the SLDS Component Library then are composed to create examples for each pattern. If you're designing for Lightning, you'll always need the SLDS Component Library file. Depending on the patterns you're designing, you may need one or all of the pattern files.

To structure your Sketch project, create a file for your designs. Make sure that your Sketch application has the SLDS UI Kit libraries installed. Use the SLDS website as a reference as you decide which components to use. When you know which you'll need, insert the appropriate symbol into your Sketch file. Try not to detach symbols whenever possible. If you do, you are then out of sync when the next SLDS UI Kit updates are released. 

![SLDS Component Library is the base library. SLDS Pattern documents extend SLDS Component Library. Your designs can inherit any of the SLDS Sketch Library symbols!](https://user-images.githubusercontent.com/1750832/41634584-3e97204e-73f9-11e8-97c4-77a648f38768.png?s=100)

**SLDS Component Library** -> Base Library with SLDS components used in all SLDS Sketch documents
<br />
**SLDS Pattern - Builder** -> Extends SLDS Component Library and composes components for <a href="https://www.lightningdesignsystem.com/guidelines/builder/" target="_blank" title="Salesforce builders">Salesforce builder</a> patterns
<br />
**SLDS Pattern - Chart** -> Extends SLDS Component Library and composes components for charts patterns
<br />
**SLDS Pattern - Rules, Filters, and Logic** -> Extends SLDS Component Library and composes components for rules, filters, and logic patterns
<br />
**SLDS Pattern - User Engagement** -> Extends SLDS Component Library and composes components for <a href="https://www.lightningdesignsystem.com/guidelines/user-engagement/overview/" target="_blank" title="Salesforce builders">user engagement</a> patterns

<br />
<br />

## Learn More

**Artboard Navigation**

In the primary SLDS Component Library Sketch file, all components have their own artboards. Finding the component symbol you want to use a breeze since the lightningdesignsystem.com website menu is mapped to the Sketch artboard list.

![lightingdesignsystem.com Menu](https://user-images.githubusercontent.com/1750832/41117594-58d53dbc-6a42-11e8-82d9-7b188bbd2f74.png)
![SLDS Component Library Artboards](https://user-images.githubusercontent.com/1750832/41117593-58b16270-6a42-11e8-9585-372732bfe673.png)
<br />
<br />

**Nested Symbols**

Sketch symbols allow you to use and reuse a self-contained design element across a Sketch document. Any changes made to a symbol will update across your whole document. It’s really handy! Nested symbols allow for even more customization, without breaking the symbol from its source, by adding symbols inside other symbols. These nested symbols are used throughout the Sketch file so that you can customize designs as much as possible without detaching the symbol.

![The right side overrides setion in Sketch allows for tab title and state to be customized](https://user-images.githubusercontent.com/1750832/41117591-587bdd58-6a42-11e8-8213-0b0c84f7eb21.png)
![The tab symbol uses nested symbols for Hover, Default and Selected states](https://user-images.githubusercontent.com/1750832/41117592-58941256-6a42-11e8-9be7-d9a8bbe9b339.png)
<br />
<br />

**Tokens as Layer and Typography Styles**

Salesforce Lightning Design System uses tokens to store visual design attributes. The SLDS Component Library uses Sketch Layer Styles and Sketch Text Styles to mimic [Lightning Design System design tokens](https://www.lightningdesignsystem.com/design-tokens/). This allows Sketch designs to use the equivalent of a design token; saving you time spec'ing your designs for development.

In symbols that contain solid color backgrounds, like icons, you’ll find the background is a layer style. This allows us to easily make file-wide changes to colors when new visual styles are introduced in SLDS. Instead of changing fill colors individually in hundreds of shapes in this document, we can just update a color symbol or point the shape to another color symbol.
<br />
<br />

**How to use Icon Symbols**

Across Salesforce, you'll frequently see [Lightning Design System icons](https://www.lightningdesignsystem.com/icons/). We’ve constructed them to be easily used individually and as nested symbols. The steps below cover how to place icon symbols individually by using the SLDS Component Library as a Sketch Library

1. **Choose an icon type**. SLDS has four types of icons. Utility icons are used for everything except Salesforce object icons. Utility icons are what you’ll want to use 95% of the time. Action icons are primarily used in mobile applications. Custom icons are to be used for custom Salesforce objects. Standard icons are used for standard Salesforce objects. 
2. **Place your icon type symbol**. Once you’ve chosen the type of icon you’d like to use (Utility, right?) place that symbol where you’d like in your Sketch document.
3. **Choose your icon glyph**. In Sketch’s right overrides panel, choose the icon glyph you’d like to use from the dropdown menu.
4. **(Optional) Choose an icon glyph color**. In Sketch’s right overrides panel, choose the icon glyph color you’d like to use from the dropdown menu.
5. **(Optional, for Action, Custom and Standard Icon Types) Choose an icon background color**. In Sketch’s right overrides panel, choose the icon background color you’d like to use from the dropdown menu.

<br />
<br />

## Contributing, Feature Requests and Bug Reporting

The SLDS team welcomes your help in maintaining the SLDS Component Library. Please add any bugs or feature requests under the [Issues](https://github.com/salesforce-ux/design-system-ui-kit/issues) tab of this repository.

**External contributions are currently closed**
<br />
Throughout a release, Salesforce's design team contributes to these Sketch files through an application called <a href="https://www.abstract.com/" target="_blank" title="Abstract">Abstract</a>. These releases are completed at least four months before being released to the public. Public contributions become unmanagable to merge since they are added to a version that is four months or more old.
<br />
<br />


## License

All icons and images are licensed under [Creative Commons Attribution-NoDerivatives 4.0](https://github.com/salesforce-ux/licenses/blob/master/LICENSE-icons-images.txt)
<br />
<br />
<p align="center">
<a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip"><img src="https://user-images.githubusercontent.com/1750832/41082860-7ffe3c1c-69e4-11e8-9b0f-813cf9be1395.png" alt="Design System UI Kit" /></a>
</p>
