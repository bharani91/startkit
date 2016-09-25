## StartKit Business Template

StartKit is a modern Bootstrap template that is best suited for **startup websites, software products, mobile app landing pages, SaaS products & small businesses**.

It is built with Bootstrap 3.3.6, jQuery, HTML5 & CSS3 (using SCSS preprecessor). It has over **25 pages** - pretty much everything you need to launch a product/startup website.

------

**[Demo & Details](#)**

------

**NOTE:** You can freely use this template for your personal & commercial projects. If you are looking to customize this template or integrate it with other backends like Ruby on Rails, Node.js etc, I would recommend that you take a look at the **Premium version of this template**. You can purchase that for $15 from my website and purchasing it will give you the following benefits -

- **Gulp based tooling** - It comes with Gulp tasks this will take care of converting SCSS to CSS, concatenating & minifying CSS & JS files and creating a production-ready build.
- Easier customization using a built in **development server with Live Reload & BrowserSync**. Your changes will be instantly reflected in the browser.
- Nunjucks based templating system - **no need to copy the same changes across multiple HTML files**.
- Full **SCSS source code** with nicely organized modules (Please check the section called "[File structure & Organization](...)" below for more details)
- Pre-built **integrations with Ruby on Rails and Node.js** (Express) backends to get you up to speed really quick.
- **6 PSD files** for quickly changing mockups images that are used in the demo (e.g: showcasing your product screenshot on a Macbook/iPad/Browser window mockup)
- Priority **email support**.

### [Purchase the Premium version now for $15 &rarr;](#)

-----------


### Overview of Features
- **Responsive** layout (works on Mobiles, Tablets & Desktops)
- **Fully AJAX with smooth page transitions**
- Over **25 Pages** - About, Features, Services, Portfolio, Gallery, Testimonials etc. Everything that is needed to launch a product/startup website.
- Very **well organized file structure** with maintainable SCSS & JS code.
- 100% hand coded with valid HTML5 code.
- Built with new Bootstrap 3.3.6
- Integration with many **modern jQuery plugins**
- Hundreds of icons from Font Awesome & Glyphicons
- Smooth & Subtle CSS3 Animations
- Multiple background images & header styles to choose from
- SCSS preprecessor for styling
- Nunjucks based HTML templating
- Ruby on Rails & Node.js integrations
- Modern tooling & development workflow.


-----------

### Included Pages

- Index Page
  - Variant 1: For Small businesses, web applications & startups
  - Variant 2: For Software products, SaaS apps, Startup website
  - Variant 3: For iPhone, Android mobile applications
- About
- Services
- Features
- Testimonials
- Contact Page
- Pricing
- Portfolio
  - 1 Column Portfolio
  - 2 Column Portfolio - with Isotope/masonry filtering
  - 3 Column Portfolio - with Isotope/masonry filtering
  - Portfolio Show Page
- Gallery Page
- Full-width page
- Sidebar page - content page e.g: Term & Conditions, Privacy Policy etc.
- FAQs
- Support/Knowledge Base Page
- Blog Listing Page
- Single Blog Post  
- Micro-blog (Tumblr)
- Login
- Signup
- Errors (404, 500)


-----------

### Modern Tooling & Easy Development
*Available only in Premium Version*

StartKit's premium version comes with a **modern tooling system to make development and customization easier**. StartKit's gulp based tasks takes care of the following tasks -

1. Converting Nunjucks templates to HTML
2. Compiling SCSS files to CSS
3. Minimizing & Compressing fonts and images
4. Concatenating & compressing CSS files using CSSNano
5. Concatenating & compressing JS files using Useref & Uglify
6. Automatically reloading the browser to reflect your changes (**live reload & browserSync**)
7. Creating production version that is ready for deployment.


--------------


### File Structure & Organization

#### SCSS
```
src/scss/
├── bootstrap
│   ├── _bootstrap.scss
│   └── bootstrap
│       ├── _alerts.scss
│       ├── _badges.scss
│       ├── _breadcrumbs.scss
│       ├── _button-groups.scss
│       ├── _buttons.scss
│       ├── _carousel.scss
│       ├── _close.scss
│       ├── _code.scss
│       ├── _component-animations.scss
│       ├── _dropdowns.scss
│       ├── _forms.scss
│       ├── _glyphicons.scss
│       ├── _grid.scss
│       ├── _input-groups.scss
│       ├── _jumbotron.scss
│       ├── _labels.scss
│       ├── _list-group.scss
│       ├── _media.scss
│       ├── _mixins.scss
│       ├── _modals.scss
│       ├── _navbar.scss
│       ├── _navs.scss
│       ├── _normalize.scss
│       ├── _pager.scss
│       ├── _pagination.scss
│       ├── _panels.scss
│       ├── _popovers.scss
│       ├── _print.scss
│       ├── _progress-bars.scss
│       ├── _responsive-embed.scss
│       ├── _responsive-utilities.scss
│       ├── _scaffolding.scss
│       ├── _tables.scss
│       ├── _theme.scss
│       ├── _thumbnails.scss
│       ├── _tooltip.scss
│       ├── _type.scss
│       ├── _utilities.scss
│       ├── _variables.scss
│       ├── _wells.scss
│       └── mixins
│           ├── _alerts.scss
│           ├── _background-variant.scss
│           ├── _border-radius.scss
│           ├── _buttons.scss
│           ├── _center-block.scss
│           ├── _clearfix.scss
│           ├── _forms.scss
│           ├── _gradients.scss
│           ├── _grid-framework.scss
│           ├── _grid.scss
│           ├── _hide-text.scss
│           ├── _image.scss
│           ├── _labels.scss
│           ├── _list-group.scss
│           ├── _nav-divider.scss
│           ├── _nav-vertical-align.scss
│           ├── _opacity.scss
│           ├── _pagination.scss
│           ├── _panels.scss
│           ├── _progress-bar.scss
│           ├── _reset-filter.scss
│           ├── _reset-text.scss
│           ├── _resize.scss
│           ├── _responsive-visibility.scss
│           ├── _size.scss
│           ├── _tab-focus.scss
│           ├── _table-row.scss
│           ├── _text-emphasis.scss
│           ├── _text-overflow.scss
│           └── _vendor-prefixes.scss
├── components
│   ├── _alert.scss
│   ├── _btn.scss
│   ├── _dropdown.scss
│   ├── _feature-list.scss
│   ├── _features-boxed.scss
│   ├── _features-split.scss
│   ├── _features.scss
│   ├── _footer.scss
│   ├── _header.scss
│   ├── _horizontal-features.scss
│   ├── _logo-slider.scss
│   ├── _modal-transition.scss
│   ├── _page-sidebar.scss
│   ├── _pricing-table.scss
│   ├── _shared.scss
│   ├── _sticky-note.scss
│   ├── _testimonial.scss
│   └── _widget.scss
├── fonts
│   └── bootstrap
│       ├── glyphicons-halflings-regular.eot
│       ├── glyphicons-halflings-regular.svg
│       ├── glyphicons-halflings-regular.ttf
│       ├── glyphicons-halflings-regular.woff
│       └── glyphicons-halflings-regular.woff2
├── modules
│   ├── _bootstrap-overrides.scss
│   ├── _material-colors.scss
│   ├── _mixins.scss
│   ├── _overrides.scss
│   └── _variables.scss
├── pages
│   ├── _about.scss
│   ├── _blog.scss
│   ├── _contact.scss
│   ├── _error.scss
│   ├── _faq.scss
│   ├── _features.scss
│   ├── _gallery.scss
│   ├── _index-slider.scss
│   ├── _index-video.scss
│   ├── _index.scss
│   ├── _login.scss
│   ├── _portfolio.scss
│   ├── _pricing.scss
│   ├── _services.scss
│   ├── _sidebar-page.scss
│   └── _support.scss
├── styles.scss
└── vendor
    ├── magic-check
    │   ├── _all.scss
    │   ├── _checkbox.scss
    │   ├── _common.scss
    │   ├── _radio.scss
    │   └── _variable.scss
    └── slick
        ├── _base.scss
        └── _theme.scss
```


#### HTML Templates
```
src/templates/
├── 404.html
├── about.html
├── blank.html
├── blog-home-1.html
├── blog-home-2.html
├── blog-post.html
├── contact-us.html
├── faq.html
├── features.html
├── full-width.html
├── gallery-4-col.html
├── index-2.html
├── index-3.html
├── index.html
├── layouts
│   ├── application.html
│   └── blank.html
├── login.html
├── partials
│   ├── blog-sidebar.html
│   ├── boxed-features-list.html
│   ├── contact-form.html
│   ├── footer.html
│   ├── header.html
│   ├── horizontal-features.html
│   ├── logo-slider.html
│   ├── meta.html
│   ├── pricing-table.html
│   └── testimonials.html
├── portfolio-1-col.html
├── portfolio-2-col.html
├── portfolio-3-col.html
├── portfolio-item.html
├── pricing.html
├── services.html
├── sidebar.html
├── signup.html
└── support.html
```

-------------

### Node JS integration
*Available only in Premium Version*

Open the `starkit-express` folder and run the following commands from the terminal to start up a demo Express.js application
```
npm install
npm start
```
Open your browser and navigate to http://localhost:8000/


-------------

### Ruby on Rails integration
*Available only in Premium Version*

This template comes with a Rails 4.2 integration. To run the Rails app, open the startkit-rails folder in the terminal and run the following commands -
```
bundle install
rake db:create
rails server
```
Open your browser and navigate to http://localhost:3000/


--------

### Feature Comparision

Features | Free Version | Premium Version
------------ | ------------- | -------------
Responsive layout (works well on mobiles, tablets & large screens) | :heavy_check_mark: | :heavy_check_mark:
25+ Pages (Home page, Features, Pricing, About, Knowledge base, Blog etc) | :heavy_check_mark: | :heavy_check_mark:
Fully AJAX with smooth page transitions | :heavy_check_mark: | :heavy_check_mark:
100% hand coded with valid HTML5 code. | :heavy_check_mark: | :heavy_check_mark:
Full SCSS code with nicely organized modules. | :x: | :heavy_check_mark:
Nunjucks based templates for making easy HTML changes | :x: | :heavy_check_mark:
Gulp based workflow for compiling SCSS to CSS, minifying CSS, JS & HTML files and creating production ready builds | :x: | :heavy_check_mark:
Development server with live-reloading & browserSync for easier development and customization experience | :x: | :heavy_check_mark:
Prebuilt integrations with Ruby on Rails & Node.js backends | :x: | :heavy_check_mark:
6 PSD files for easily replacing images used in demo with your own product images | :x: | :heavy_check_mark:
Priority Email Support | :x: | :heavy_check_mark:
**Pricing & Download** | FREE ([Download](#)) | $15 ([**Purchase**](#))


--------


### Credits
- AOS (Animate On Scroll) - https://github.com/michalsnik/aos
- Bootstrap - http://getbootstrap.com
- Isotope - http://isotope.metafizzy.co
- Magnific Popup - http://dimsemenov.com/plugins/magnific-popup/
- Slick Slider - http://kenwheeler.github.io/slick/
- Magic Check - https://github.com/forsigner/magic-check
- FontAwesome - http://fontawesome.io
- Material Icons - https://design.google.com/icons/
- Barba - http://barbajs.com
- Smallicons - https://www.smashingmagazine.com/2013/11/freebie-smallicons-icon-set/
- Circle Icons - https://www.elegantthemes.com/blog/freebie-of-the-week/beautiful-flat-icons-for-free

- Photos used in thumbnails
  - Unsplash - http://unsplash.com
- Background Images
  - All images are provided in scaled/compressed form and in original sizes
  - Sunrise - https://www.pexels.com/photo/green-grass-field-107927/
  - Mist - http://getcraftwork.com/cool-water-by-jose-murillo/
  - Dawn - https://www.pexels.com/photo/dawn-landscape-mountains-nature-1852/
  - Starry - https://www.pexels.com/photo/silhouette-of-mountain-with-galactic-background-during-daytime-25996/


--------


### Support, Bug Reports & Customization Requests
Please send all your support requests, suggestions, comments and bug requests to **bharani@authenticpixels.com**. I will get back to you within 24 working hours.
