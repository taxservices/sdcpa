# sandiegocpa.com [![Netlify Status](https://api.netlify.com/api/v1/badges/fddbda55-af42-41ef-9c09-13af26f1cc20/deploy-status)](https://app.netlify.com/sites/sdcpa/deploys)

## v2

* [Netlify](https://netlify.com)
* [Netlify CMS](https://www.netlifycms.org/)
* [Netlify Forms](https://www.netlify.com/products/forms/)
* [Netlify Functions](https://www.netlify.com/products/functions/)
* [Gatsby](https://gatsbyjs.org)
* [Styled Components](https://www.styled-components.com/)
* [Theme-UI](https://theme-ui.com/)

### Time estimate

> 100+ hours total

Deadline: 1st of November

<details>
<summary>
  Estimates per task
</summary>

* Homepage template [20]
  * Header
  * Hero section component [1]
    * Content component [0.5]
    * CTA component [0.5]
  * CPA services section component [2]
    * Post excerpt component
    * Read more button
    * Call button
  * Featured posts section component [2]
  * Footer
* Article template [2]
  * Header
  * Content component
  * Next / Previous Article [2]
  * Footer
* Blog page [2.5]
  * Header
  * List of articles component [1]
    * Title component [0.5]
    * Excerpt component [0.5]
    * Read more Button
  * Footer
* FAQ page [4]
* Contact page [10]
  * Social media link list component [2]
  * Form component [5]
  * Serverless function to send email component [3]
* Common components [18.5]
  * Content component (global styles) [3]
  * Header component [4]
    * Logo component [0.5]
    * Mobile nav component [3]
    * Desktop nav component [2]
    * Promo bar component [0.5]
  * Footer component [1]
  * Phone CTA component [2.5]
  * Buttons component [2]
* Commitizen [1]
* Theme-UI [3]
* Styled-components [1] ?
* CMS configutarion [6]
* Dev documentation [3]
* Author documentation [3]
* Animations & transitions [4]
* Gatsby Themes [2]

</details>

#### Routing

* Logo - `/`
* Services - `/services`
* Taxation service - `/taxation`
* Consulting service - `/consulting`
* Accounting service - `/accounting`
* FAQ - `/faq`
* Blog - `/blog`
* Contact us - `/contacts`

```
https://sandiegocpa.com/services                  - template
  https://sandiegocpa.com/taxation                - page
  https://sandiegocpa.com/consulting              - page
  https://sandiegocpa.com/accounting              - page
https://sandiegocpa.com/blog                      - page
  https://sandiegocpa.com/blog/corporate-taxation - template
```

### Workflow

CMS => Git => CDN

### Resources

* [Gatsby Netlify CMS Starter](https://github.com/netlify-templates/gatsby-starter-netlify-cms)