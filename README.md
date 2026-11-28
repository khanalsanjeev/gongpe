# Gongpe

**Enterprise Support and Technology Solutions**

Gongpe is a business group based in Kathmandu, Nepal. It brings together
focused consulting and technology practices, supporting businesses
through clearer decisions, stronger systems, and practical digital
solutions.

Website: <https://gongpe.com>\
Location: Kathmandu, Nepal

## About Gongpe

Gongpe develops and supports practical business activities with a focus
on enterprise support and technology solutions.

At present, the group's active work is concentrated in two practices:

-   **Gongpe Consulting** --- financial and business advisory.
-   **Gongpe Technologies** --- digital tools, platforms, and
    information systems.

The group provides a shared foundation while allowing each practice to
operate with clear priorities.

## Our Practices

### 1. Gongpe Consulting

**Financial & Business Consulting**

Gongpe Consulting helps businesses strengthen financial visibility,
improve operational systems, and support informed decisions.

The practice works with growing enterprises, established businesses, and
new ventures on:

-   Financial modelling
-   Business analysis
-   Accounting systems
-   Organisation of financial information

Website: [consulting.gongpe.com](https://consulting.gongpe.com)

### 2. Gongpe Technologies

**Technology Solutions**

Gongpe Technologies develops practical digital tools and platforms that
support business operations and information management.

Areas of focus include:

-   Digital platforms
-   Business applications
-   Data and information systems
-   Workflow automation

Website: [tech.gongpe.com](https://tech.gongpe.com)

## Operating Priorities

Gongpe's work is guided by three priorities:

### Focused activity

Concentrating resources on a small number of practical businesses rather
than a wide set of loosely related units.

### Operating relevance

Shaping solutions around real information, process, and decision needs
in the operating environment.

### Longer horizon

Building capabilities that can be sustained, evaluated, and improved
over time.

## Products

The Gongpe website also features the following products:

-   **1Pana Accounting** --- [1pana.com](https://1pana.com)
-   **Nepal Venture** --- [nepalventure.com](https://nepalventure.com)

## Contact

For matters related to a specific practice, please use the relevant
website:

-   **General group-level enquiries:** [gongpe.com](https://gongpe.com)
-   **Consulting:**
    [consulting.gongpe.com](https://consulting.gongpe.com)
-   **Technologies:** [tech.gongpe.com](https://tech.gongpe.com)

**Location:** Kathmandu, Nepal

## Website Repository

This repository contains the source files for the Gongpe corporate
website.

The website presents the group, its two practices, its products, and
contact information. It is a static website intended for deployment
through GitHub Pages.

### Technology

-   HTML
-   Tailwind CSS
-   Static assets
-   GitHub Pages

Tailwind CSS is compiled into a local stylesheet for production. The
deployed website serves the compiled CSS as a static asset and does not
need a Tailwind CDN or server-side runtime.

## Local Development

Node.js and npm are required to install the development dependency and
rebuild the Tailwind stylesheet.

Install dependencies:

``` bash
npm install
```

Start the Tailwind watcher during development:

``` bash
npm run dev
```

Build the minified production stylesheet:

``` bash
npm run build
```

The generated stylesheet is written to:

``` text
assets/css/tailwind.css
```

Commit the generated stylesheet along with the website changes before
deployment. The `node_modules` directory is not required in the deployed
repository.

## Deployment

The website is designed for static hosting with GitHub Pages.

Ensure the repository includes the website HTML, required assets, and
the compiled stylesheet. Configure GitHub Pages to publish the
repository's selected branch or deployment source, then push the updated
files.

No server-side application or Tailwind compilation is required on GitHub
Pages. The production stylesheet is generated before deployment and
served as a static file.

------------------------------------------------------------------------

© Gongpe. All rights reserved.
