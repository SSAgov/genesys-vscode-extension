![Genesys logo](https://github.com/SSAgov/genesys-vscode-extension/blob/main/genesys.png) Genesys Snippets
================

[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
![](https://vsmarketplacebadge.apphb.com/version/CraigCecil.genesys-snippets.svg)
![Last Commit](https://img.shields.io/github/last-commit/SSAgov/genesys-vscode-extension)

A set of Genesys Snippets for Visual Studio Code.

Genesys is a prototyping toolkit for use with VSCode. It enables designers and UI developers to quickly create low to high-fidelity prototypes, or even production-ready UI. Genesys provides support for most major design systems (Bootstrap, Material Design, Foundation, Ionic, Tailwind, Tachyons, et. al.) and you can add any others. Additional features include multi-lingual support, automated walk-throughs, on-screen comments, A/B testing, conditional logic, animation, and more--all through markup.

[Install Genesys Snippets](https://marketplace.visualstudio.com/items?itemName=CraigCecil.genesys-snippets)

**Page Templates**

Create new pages based on common design systems. Create a new HTML document and type `!!` to see the available page templates.

Trigger | Description | Documentation
------- | ----------- | -------------
!html | Plain HTML5 page | https://www.w3schools.com/html/default.asp
!!atlassian | Atlassian page | https://www.atlassian.design/components/
!!bs3 | Bootstrap 3 page | https://getbootstrap.com/docs/3.4/components/
!!bs4 | Bootstrap 4 page | https://getbootstrap.com/docs/4.5/getting-started/introduction/
!!bs5 | Bootstrap 5 page | https://v5.getbootstrap.com/docs/5.0/getting-started/introduction/
!!bulma | Bulma page | https://bulma.io/documentation/
!!fabric | Microsoft Fabric page | https://developer.microsoft.com/en-us/fluentui#/controls/web
!!fluent | Microsoft Fluent page | https://learn.microsoft.com/en-us/fluent-ui/web-components/
!!foundation| Foundation page | https://get.foundation/sites/docs/
!!ionic | Ionic page | https://ionicframework.com/docs/components
!!patternfly | Red Hat PatternFly page | https://www.patternfly.org/v4/
!!pure | Pure.css page | https://purecss.io/
!!mdb | Material Design Bootstrap page | https://mdbootstrap.com/
!!mds | M-Design System page | https://m-docs.org/
!!material | Material Design page | https://material.io/components
!!material-lite | Material Design Lite page | https://getmdl.io/components/index.html
!!materialize |  Materialize page | https://materializecss.com/
!!metro | Metro UI page | https://metroui.org.ua/intro.html
!!paper | PaperCSS page | https://www.getpapercss.com/
!!reveal | Reveal.js presentation | https://revealjs.com/
!!semantic | Semantic UI page | https://semantic-ui.com/
!!shoelace | Shoelace Web Components page | https://shoelace.style/
!!tailwind | Tailwind CSS page | https://tailwindcss.com/
!!uikit | UIKit page | https://getuikit.com/docs/introduction
!!vue | Vue.js page | https://vuejs.org/v2/guide/
!!webslides | WebSlides presentation | https://github.com/webslides/webslides/

**Libraries**

Trigger | Description
------- | -----------
gns-add-genesys-lite | Add the basic Genesys prototyping tools to the page
gns-add-genesys-full | Add all of the Genesys prototyping tools to the page
gns-add-analytics | Add the analytics library to the page
gns-add-animation | Add the Animate & AniJS libraries
gns-add-atlas | Add the Atlassian Design System
gns-add-basscss | Add the Basscss CSS Low-Level Toolkit
gns-add-bulma | Add the Bulma CSS Framework
gns-add-diagram-library | Add the Flowchart & Diagramming Library (Mermaid)
gns-add-fluent | Add the Microsoft Fluent UI Web Component library
gns-add-font-awesome | Add the Font Awesome icon library
gns-add-mdbootstrap | Add the Material Design Bootstrap library
gns-add-mdesignsystem | Add the M-Design System Web Component library
gns-add-metro | Add the Microsoft-based Metro UI library
gns-add-modulz | Add the Modulz CSS library
gns-add-paper | Add the Paper CSS library
gns-add-patternfly | Add the Red Hat PatterFly library
gns-add-pure | Add the Pure.css library
gns-add-page-testing | Add automated page testing using Gremlins
gns-add-persistence | Add the Persistence library (Mavo)
gns-add-roles | Add the User Roles (PolyPage) library
gns-add-shoelace | Add the Shoelace Web Component library
gns-add-tachyons | Add the Tachyons CSS Toolkit
gns-add-tailwind | Add the Tailwind CSS framework
gns-add-turret | Add the Turret CSS Framework
gns-add-uilang | Add the UILang library
gns-add-walkthru | Add Intro.js library

**Site Maps**

Trigger | Description
------- | -----------
gns-sitemap-add-page | Connect a new page block to your sitemap page

**Flowcharting & Diagramming**

Trigger | Description
------- | -----------
gns-insert-diagram | Insert a flowchart or diagram

**Design Placeholders**

Trigger | Description
------- | -----------
gns-placeholder-block | Generic Block placeholder
gns-placeholder-image | Image placeholder

**Common UI Elements**

Trigger | Description
------- | -----------
gns-button | Button
gns-header | Heading Level (1-6)
gns-link | Hyperlink
gns-icon | Icon (Font Awesome)

**Including Master Page Components**

Trigger | Description
------- | -----------
gns-include | Include a partial, reusable page component

**Virtual Pages**

Trigger | Description
------- | -----------
gns-virtual-page | Add a new Virtual Page

**Annotations & Comments**

Trigger | Description
------- | -----------
gns-add-note-library | Add the Annotation library
gns-add-note | Annotation

**Blur, Redact, Hide Data**

Trigger | Description
------- | -----------
gns-blur | Blur fake/realistic data and user input
gns-redact | Redact fake/realistic data and user input
gns-invisible-ink | Hide fake/realistic data and user input

**A/B Testing**

Trigger | Description
------- | -----------
gns-add-ab-testing | Add the A/B testing library to the page
gns-add-ab-testing-config | Add the A/B/ testing library configuration settings
gns-insert-ab-test-scenarios | Insert A/B test scenario sections

**Measuring Perceived Usability**

Trigger | Description
------- | -----------
gns-feedback-seq | Add the Single Ease Question (SEQ) to your page
gns-feedback-sus | Add the System Usability Scale (SUS) to your page
gns-feedback-tlx | Add the Task Load Index (TLX) to your page

Genesys Page Settings
---------------------

Add any of the following CSS class names to your prototype page's BODY element. Note that the Genesys Toolbar provides real-time interactive access to these functions as you view your prototypes.

BODY Class | What It Does
-----------| ------------
gns-grid | Display the page with visible outlines of all page layout grids
gns-inspect | Display the Genesys Page Inspector
gns-lofi | Display the page in Low-Fidelity mode
gns-notes | Display the page with all (any) page notes/annotations visible
gns-redact | Display the page with all fake/realistic data redacted
gns-test | Display the page with automated interactive tests running
gns-walkthru | Display the page with the automated Walthru feature activated (if present)
gns-toolbar-hide | Hide the Genesys Toolbar
gns-footer-hide | Hide the Genesys Page Footer

Genesys Object Settings
-----------------------

Add any of the following CSS class names to any page element.

BODY Class | What It Does
-----------| ------------
gns-text-left | Left align text
gns-text-center | Center text
gns-text-right | Right align text
gns-float-left | Push the element to the left as far as possible
gns-float-right | Push the element to the right as far as possible

----------------------------------------------------

**Building the Extension**
--------------------------

For first time builders, make sure you have [Node.js](https://nodejs.org/en/) installed, then run:

`npm install -g vsce`

To build the extension:

1. If you have made changes, update the `package.json` file version number appropriately, using [Semantic Versioning](https://semver.org/) rules.
2. Run `vsce package`


