<p align="center">
<a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip" target="_blank"><img src="https://user-images.githubusercontent.com/1750832/41082861-8013ecba-69e4-11e8-8149-7eaa94825b19.png" alt="Design System UI Kit" /></a>
</p>
<br />
<h1 style="border-bottom:none;">Salesforce Lightning Design System (SLDS) UI Kit</h1>
<p>
The Salesforce Lightning Design System (SLDS) UI Kit is a collection of resources to support designing and prototyping using <a href="https://www.lightningdesignsystem.com" target="_blank">Lightning Design System</a> components, tokens, and design patterns. There are also useful resources to help make design workflows more efficient with artifacts like page templates, wireframes, key product screens, and components for writing specifications. 
</p>
<b>» To install, copy/paste the URLs below in any browser address bar «</b></p>
<em>Required libraries</em>
<ul>
<li><b>SLDS Icons</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-icon-rss.xml</code></li>
<li><b>SLDS Components for Web</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-rss.xml</code></li>
</ul>
<em>Optional Libraries</em>
<ul>
<li><b>Builder Patterns</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-builder-rss.xml</code></li>
<li><b>Chart Patterns</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-chart-rss.xml</code></li>
<li><b>Rules, Filters, and Logic Patterns</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-rfl-rss.xml</code></li>
<li><b>User Engagement Patterns</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-user-engagement-rss.xml</code></li>
</ul>
<em>Other Resources</em>
<ul>
<li><b>Artboard Templates</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-artboard-rss.xml</code></li>
<li><b>Specification Library</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-spec-rss.xml</code></li>
<li><b>Key Mobile Product Screens</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-key-screens-rss.xml</code></li>
<li><b>Wireframe Library</b>
<br /><code>sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-wireframe-rss.xml</code></li>
</ul>
<br />
<br />

## Requirements

### Sketch

Download the most recent version of [Sketch](https://www.sketchapp.com/).
<br />
<em>If you do not have Sketch, you can use the <a href="https://github.com/salesforce-ux/design-system-ui-kit-framerx" target="_blank" title="Framer SLDS UI Kit">Framer SLDS UI Kit</a> or <a href="https://www.figma.com/file/5dgFdCHB6FGjfOPAZEDNVK/Lightning-Design-System-Components-for-Web?node-id=0%3A1" target="_blank" title="Figma SLDS Components for Web">Figma SLDS Components for Web</a> and <a href="https://www.figma.com/file/5dgFdCHB6FGjfOPAZEDNVK/Lightning-Design-System-Components-for-Web?node-id=0%3A1" target="_blank" title="Figma SLDS Icons">Figma SLDS Icons</a> libraries, however, they may not be as up-to-date as the Sketch files.</em>

### Salesforce Sans fonts

1. Download the [Salesforce Sans fonts](https://github.com/salesforce-ux/design-system/tree/master/assets/fonts) from the Design System repository
2. Install the Salesforce Sans fonts on your system

<br />
<br />

## Getting Started

**Welcome to the Salesforce Lightning Design System (SLDS) Sketch UI Kit**

The Salesforce Design Systems team has made optimizations with this Sketch Library so you can more efficiently create Salesforce Lightning interfaces. In the instructions below, we’ll cover the basics and some tips for you to get started.

Sketch Libraries allow you to have SLDS components and patterns available from Sketch’s symbols menu in any file you open. Sketch Libraries will automatically update your designs when the library is updated. Your designs will never be out of date if they’re linked to this Sketch Library document.

**How to use the SLDS Sketch UI Kits as Sketch Libraries**

Copy and paste the following links to each of the required libraries below in any browser. This will subscribe your Sketch application to automatically download and install the SLDS Sketch UI Kits and will automatically update when new versions are released. All other libraries in this UI kit are optional.

**SLDS Icons**

    sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-rss.xml
**SLDS Components for Web**
    
    sketch://add-library?url=https://www.lightningdesignsystem.com/sketch-library-icons-rss.xml

Alternatively, download the Sketch Libraries in this repository you'd like to install. Open `Sketch > Preferences > Libraries` and click `Add Library...`. Select the library you'd like to install. If you do this method, you'll have to frequently come back to this repository, download the new version, and repeat this installation. This method is not recommended because it's such a hassle.

Verify that you've successfully installed the Sketch Libraries by opening `Sketch > Preferences > Libraries`. You should see all of the libraries you installed above.

![You can see all of your Sketch Libraries in Sketch > Preferences > Libraries](https://user-images.githubusercontent.com/1750832/41635016-3aa5d32a-73fb-11e8-97dd-41cf9e940735.png)
<br />
<br />

**That's it! Now you can supercharge your design workflow for building on the Salesforce platform.**

<br />
<br />

## Sketch UI Kit Architecture

The SLDS UI Kit is optimized to mimic the code structure of a design system but within the bounds of Sketch. The two main, and required, resources are the SLDS Icon Library and the SLDS Web Component Library. The SLDS Icon Library is, well, each icon in SLDS. The SLDS Web Component Library file is a replica of SLDS web components and tokens. 

Also in the kit are multiple pattern files. These files inherit the symbols from the icon and generic-styled components from the required libraries above, then are composed to create accurate examples for each pattern as you'd find it in the product today. 

To structure your Sketch project, create a file for your designs like you normally would do. Hopefully you've verified that the libraries are installed if you followed the instructions in the previous section. If you have, then in Sketch you can click `Insert > Symbols > SLDS Icon Library` or `Insert > Symbols > SLDS Components for Web`, select the symbol you would like to use, then drop it onto your Sketch file's artboard.

![SLDS Icons and Web Component Libraries are the base libraries that help build. SLDS Pattern documents extend the icon and component libraries to customize components for specific use cases. Your designs can inherit any or all of the SLDS UI Kit symbols!](https://user-images.githubusercontent.com/1750832/74075531-b27bd180-49c7-11ea-9a33-167aa1cb58e2.png)

**Design System Tokens are represented as Layer Styles and Text Styles in Sketch**

Salesforce Lightning Design System uses tokens to store visual design attributes. The SLDS Web Component Library uses Sketch Layer Styles and Sketch Text Styles to mimic [tokens](https://www.lightningdesignsystem.com/design-tokens/). This allows Sketch designs to use the equivalent of a token; saving you time spec'ing your designs for development and making sure your designs use accurate platform specifications.

In symbols that contain solid color backgrounds, like icons, you’ll find the background is a layer style. This allows us to easily make file-wide changes to colors when new visual styles are introduced in SLDS. Instead of changing fill colors individually in hundreds of shapes in this document, we can just update a color symbol or point the shape to another color symbol.
<br />
<br />

## Design File Descriptions

**SLDS Components for Web**
<br />
Sketch equivalents of [component blueprints](https://www.lightningdesignsystem.com/components/overview/) and [tokens](https://www.lightningdesignsystem.com/design-tokens/) as seen on the SLDS website


**SLDS Components for Mobile (coming soon)**
<br />
Sketch collection of native mobile patterns and mobile web coded components


**SLDS Icon Library**
<br />
A file of [design system icons](https://www.lightningdesignsystem.com/icons/) which is automatically generated from design system code


**Pattern: Builder**
<br />
[Builder design guideline](https://www.lightningdesignsystem.com/guidelines/builder/) customized component symbols


**Pattern: User Engagement**
<br />
[User engagement design guideline](https://www.lightningdesignsystem.com/guidelines/user-engagement/overview/) customized component symbols


**Pattern: Chart**
<br />
[Chart design guideline](https://www.lightningdesignsystem.com/guidelines/charts/) customized component symbols


**Pattern: Rules, Filters, and Logic**
<br />
[RFL design guideline](https://www.lightningdesignsystem.com/guidelines/rules-filters-logic/) customized component symbols


**Standard Artboards**
<br />
Based on user data, Sketch artboards are sized to the common viewport dimensions used


**Spec Library**
<br />
A collection of symbols to use when documenting dimensions and details of designs for engineers


**Wireframes**
<br />
Grey box stencils of common Lightning interfaces

**Key Screens**
<br />
A collection of the most common product screens on mobile (and desktop coming soon)

<br />
<br />

## Contributing, Feature Requests and Bug Reporting

The SLDS team welcomes your feedback to help maintain these design resources. Please add any bugs or feature requests under the [Issues](https://github.com/salesforce-ux/design-system-ui-kit/issues) tab of this repository.

**External contributions are currently closed**
<br />
Throughout a release, Salesforce's design team contributes to these Sketch files through an application called <a href="https://www.abstract.com/" target="_blank" title="Abstract">Abstract</a>. Public contributions become unmanagable to review and merge since GitHub doesn't have the capability to view binary files.
<br />
<br />


## License

All icons and images are licensed under [Creative Commons Attribution-NoDerivatives 4.0](https://github.com/salesforce-ux/licenses/blob/master/LICENSE-icons-images.txt)
<br />
<br />
<p align="center">
<a href="https://github.com/salesforce-ux/design-system-ui-kit/archive/master.zip" target="_blank"><img src="https://user-images.githubusercontent.com/1750832/41082860-7ffe3c1c-69e4-11e8-9b0f-813cf9be1395.png" alt="Design System UI Kit" /></a>
</p>
