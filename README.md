# Frontend Checklist

##HEAD##

- [ ] Doctype: The Doctype is HTML5 and is at the top of all your HTML pages.

- [ ] Charset: The charset declared (UTF-8) is declared correctly.

- [ ] Viewport: The viewport is declared correctly.

- [ ] Title: A title is used on all pages

- [ ] Description: A meta description is provided, it is unique and doesn't possess more than 150 characters.

- [ ] Favicons: Each favicon has been created and displays correctly.

- [ ] CSS order: All CSS files are loaded before any JavaScript files in the HEAD

##HTML##

- [ ] HTML5 Semantic Elements: HTML5 Semantic Elements are used appropriately (header, section, footer, main...).

- [ ] Error pages: Error 404 page and 5xx exist

- [ ] W3C compliant: All pages need to be tested with the W3C validator to identify possible issues in the HTML code.

- [ ] Link checker: There are no broken links in my page, verify that you don't have any 404 error.

##CSS##

- [ ] Webfont format: WOFF, WOFF2 and TTF are supported by all modern browsers.

- [ ] Webfont size: Webfont sizes don't exceed 2 MB (all variants included).

- [ ] Responsive Web Design: The website is using responsive web design.

- [ ] JS prefix: All classes (or id- used in JavaScript files) begin with js- and are not styled into the CSS files.

- [ ] Vendor prefixes: CSS vendor prefixes are used and are generated accordingly with your browser support compatibility.

- [ ] Concatenation: CSS files are concatenated in a single file (Not for HTTP/2).

- [ ] Minification: All CSS files are minified.

- [ ] Stylelint: All CSS or SCSS files are without any errors.

- [ ] Desktop Browsers: All pages were tested on all current desktop browsers (Safari, Firefox, Chrome, Internet Explorer, EDGE...)

- [ ] Mobile Browsers: All pages were tested on all current mobile browsers (Native browser, Chrome, Safari...)

- [ ] OS: All pages were tested on all current OS (Windows, Android, iOS, Mac...)

- [ ] Non-blocking: CSS files need to be non-blocking to prevent the DOM from taking time to load.

##Javascript##

- [ ] JavaScript Inline: You don't have any JavaScript code inline (mixed with your HTML code).

- [ ] Concatenation: JavaScript files are concatenated.

- [ ] Minification: JavaScript files are minified (you can add the .min suffix).

- [ ] JavaScript security:

- [ ] Non-blocking: JavaScript files are loaded asynchronously using async or deferred using defer attribute.

- [ ] ESLint: No errors are flagged by ESLint (based on your configuration or standards rules).

##Images##

- [ ] Optimization: All images are optimized to be rendered in the browser. WebP format could be used for critical pages (like Homepage)

- [ ] Sprite: Small images are in a sprite file (in the case of icons, they can be in an SVG sprite image).

- [ ] Width and Height: Set width and height attributes on if the final rendered image size is known (can be omitted for CSS sizing).

- [ ] Alternative text: All have an alternative text which describe the image visually.

- [ ] Lazy loading: Images are lazyloaded (A noscript fallback is always provided).

##Accessibility##

- [ ] H1: All pages have an H1 which is not the title of the website.

- [ ] Headings: Headings should be used properly and in the right order (H1 to H6).

- [ ] Label: A label is associated with each input form element. In case a label can't be displayed, use aria-label instead.

- [ ] Accessibility standards testing: Use the WAVE tool to test if your page respects the accessibility standards.

- [ ] Keyboard navigation: Test your website using only your keyboard in a previsible order. All interactive elements are reachable and usable.

##Performance##

- [ ] Page weight: The weight of each page is between 0 and 500 KB.

- [ ] Google PageSpeed: All your pages were tested (not only the homepage) and have a score of at least 90/100.

##SEO##

- [ ] Google Analytics: Google Analytics is installed and correctly configured.

- [ ] sitemap.xml: A sitemap.xml exists and was submitted to Google Search Console.

- [ ] robots.txt: The robots.txt is not blocking webpages.

- [ ] Structured Data: Pages using structured data are tested and are without errors.
