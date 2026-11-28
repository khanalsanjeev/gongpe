# Gongpe

**A diversified business group developing enterprises across distinct
areas of economic activity.**

Official website: <https://gongpe.com>\
Headquarters: Kathmandu, Nepal

Gongpe brings together different business interests, develops new
enterprises, and pursues opportunities to create lasting value. The
group provides a shared corporate foundation and strategic direction for
business units operating across distinct markets and sectors.

## About the Group

Gongpe is being developed with a long-term perspective: building
businesses, strengthening capabilities, and organising resources around
meaningful economic opportunities.

Our approach is guided by:

-   **Purposeful activity** --- organising capital, capabilities, and
    expertise around real opportunities.
-   **A shared foundation** --- maintaining central strategic direction
    while allowing individual business units to focus on their markets
    and operations.
-   **Adaptability** --- evolving as economic environments change and
    new opportunities emerge.
-   **Value creation** --- prioritising sustainable economic activity
    and long-term continuity.

## Business Units

Gongpe's current business interests span the following areas:

  ----------------------------------------------------------------------------------------------------
  Business                Focus                   Website
  ----------------------- ----------------------- ----------------------------------------------------
  **Gongpe Finance**      Financial services,     [finance.gongpe.com](https://finance.gongpe.com)
                          corporate finance,      
                          accounting, capital     
                          advisory, and financial 
                          management.             

  **Gongpe Commerce**     Commercial activities,  [commerce.gongpe.com](https://commerce.gongpe.com)
                          product trade,          
                          sourcing, and           
                          distribution networks.  

  **Gongpe Travel**       Travel, tourism,        [travel.gongpe.com](https://travel.gongpe.com)
                          destinations,           
                          hospitality, and        
                          curated travel          
                          experiences.            

  **Gongpe                Media production,       [media.gongpe.com](https://media.gongpe.com)
  Entertainment**         digital content,        
                          events, and creative    
                          experiences.            

  **Gongpe Technologies** Software development,   [tech.gongpe.com](https://tech.gongpe.com)
                          digital platforms,      
                          cloud infrastructure,   
                          and technology          
                          solutions.              
  ----------------------------------------------------------------------------------------------------

Each business unit has its own focus, market, and operating direction,
supported by the broader vision and development of the group. The group
may explore additional sectors and opportunities as its capabilities and
market conditions evolve.

## Organisation

At the group level, Gongpe focuses on:

-   Overall strategic direction and corporate vision
-   Resource allocation and capital oversight
-   Business-unit governance and ethics
-   New venture development and expansion

Individual business units focus on their respective markets, customer
relationships, products and services, and day-to-day commercial
operations.

## Website

This repository contains the source files for the Gongpe corporate
website.

The website serves as an institutional presentation platform for the
group. It introduces Gongpe, presents its business structure, and
provides corporate information and enquiry routes. Business-specific
information and commercial details are provided through the respective
business-unit websites.

### Technology

-   HTML
-   Tailwind CSS 4
-   Static assets
-   GitHub Pages

Tailwind CSS is compiled into a local, minified stylesheet. The deployed
website does not rely on the Tailwind CDN or require a server-side
runtime.

## Local Development

You need [Node.js](https://nodejs.org/) and npm to rebuild the
stylesheet.

1.  Clone or download this repository.

2.  Open a terminal in the project directory.

3.  Install the development dependencies:

    ``` bash
    npm install
    ```

4.  Start the Tailwind watcher while editing:

    ``` bash
    npm run dev
    ```

5.  Before publishing, generate the production stylesheet:

    ``` bash
    npm run build
    ```

The compiled stylesheet is written to:

``` text
assets/css/tailwind.css
```

Commit the generated stylesheet together with any HTML or source CSS
changes.

## Deployment

The website is designed for static hosting through GitHub Pages.

1.  Ensure the repository contains `index.html`, the `assets/`
    directory, and the compiled `assets/css/tailwind.css` file.
2.  Configure GitHub Pages for the repository using the publishing
    source selected for the project.
3.  Commit and push the website files.
4.  Ensure the custom domain `gongpe.com` is configured in the
    repository's Pages settings and that its DNS records point to GitHub
    Pages.

No Tailwind build step is required on the hosting server. The production
CSS is generated before deployment and served as a static file.

Do not commit `node_modules/`; it is only used locally to build the CSS.

## Repository Structure

``` text
.
├── index.html
├── assets/
│   ├── css/
│   │   └── tailwind.css
│   ├── gongpe-headquarters.png
│   ├── favicon.ico          # add the site favicon
│   └── favicon.png          # add the site favicon
├── src/
│   └── input.css
├── package.json
├── package-lock.json        # generated by npm install
├── sitemap.xml
├── robots.txt
└── README.md
```

The favicon files should be placed in `assets/` if they are not already
present in the repository.

## Corporate Enquiries

For group-level enquiries and corporate information, visit
[gongpe.com](https://gongpe.com). For enquiries relating to a specific
business unit, use the corresponding website listed above.

## Important Information

Information on the corporate website describes Gongpe as a parent
business group and outlines the development direction of its business
units. It is provided for general and institutional information and does
not, by itself, constitute a direct commercial offer or financial
solicitation. Specific products, services, availability, and commercial
terms are determined by the relevant business unit.

------------------------------------------------------------------------

© Gongpe. All rights reserved.
