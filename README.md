# Inclusive Web Design Checklist

Aims to be the **biggest** checklist of inclusive design considerations for the web _ever_. Includes items for accessibility, performance, device support, interoperability, and language. Pull requests welcome!

- [ ] [Minify CSS and JS, and remove unused/redundant code](https://developers.google.com/speed/docs/insights/MinifyResources)
- [ ] Maintain terse HTML, without over-reliance on `<div>` scaffolding
- [ ] [Use screen reader and keyboard accessible HTML](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)
- [ ] [Compress raster images](https://www.html5rocks.com/en/tutorials/speed/img-compression/)
- [ ] [Optimize SVG path data](https://web-design-weekly.com/2014/10/22/optimizing-svg-web/)
- [ ] [Make sure heading levels describe a logical section/subsection structure](https://webaim.org/techniques/semanticstructure/)
- [ ] Only include heading elements where they introduce sections of content
- [ ] [Remove potentially insensitive or uninclusive language (use 'singular they')](http://alexjs.com/)
- [ ] Give video content captions and transcripts
- [ ] Provide transcripts for audio content  
- [ ] [Make sure main body (paragraph) text is no smaller than the default (user agent) size](https://www.smashingmagazine.com/2011/10/16-pixels-body-copy-anything-less-costly-mistake/)
- [ ] Support 'pinch zoom' (remove `user-scalable=no` if present)
- [ ] Use relative units (`em`, `rem`, and `ch`), especially for font metrics
- [ ] [Make sure styles and scripts are not render blocking](https://csabapalfi.github.io/eliminate-render-blocking/)
- [ ] [Install a service worker and cache all applicable assets](https://css-tricks.com/serviceworker-for-offline/)
- [ ] [Use content-based, not device-specific, media queries](http://bradfrost.com/blog/post/7-habits-of-highly-effective-media-queries/#content)
- [ ] Provide alternatives and/or descriptions for complex visualizations
- [ ] Include only clear, meaningful animations
- [ ] Honor requests to remove animation via the `prefers-reduced-motion` media query
- [ ] Make sure controls do not elicit unexpected or jarring behavior
- [ ] Do not include third parties that compromise user privacy
- [ ] Do not recreate supported and expected browser behaviors with bespoke scripts
- [ ] Support Windows high contrast mode (use images, not background images)
- [ ] Provide alternative text for salient images
- [ ] Apply `alt=""` or `aria-hidden="true"` to decorative images
- [ ] Make sure text and background colors contrast sufficiently
- [ ] Provide `<title>`s that name the site and the specific page
- [ ] Provide large touch 'targets' for interactive elements
- [ ] Use data tables (`<table>`) for data only, not visual layout purposes
- [ ] Make scrollable elements focusable for keyboard users
- [ ] Do not rely on color for differentiation of visual elements
- [ ] Use the same design patterns to solve the same problems
- [ ] Ensure keyboard focus order is logical regarding visual layout
- [ ] Lazy load large image assets
- [ ] [Honour DNT (Do Not Track) header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/DNT)
- [ ] Translate / spell out acronyms the first time you use them
- [ ] Do not hijack standard scrolling behavior
- [ ] Move focus between dialogs and the controls that invoked them
- [ ] Give all form elements permanently visible labels
- [ ] Give grouped form elements group labels
- [ ] Place labels above form elements
- [ ] Provide status and error messages as WAI-ARIA live regions
- [ ] Provide clear, unambiguous focus styles
- [ ] Employ well-balanced, highly legible fonts (not too complex or elaborate)
- [ ] Do not use very thin font faces
- [ ] Ensure states (pressed, expanded, invalid, etc) are communicated to assistive software
- [ ] Match semantics to behavior for assistive technology users
- [ ] Provide a default language and use `lang="[ISO code]"` for subsections in different languages
- [ ] Make controls look like controls; give them strong perceived affordance
- [ ] Underline links — at least in body copy
- [ ] Make sure all content belongs to a landmark element (`<header>`, `<footer>`, `<nav>`, `<main>`, etc)
- [ ] Avoid pure white or pure black shades
- [ ] Mark invalid fields clearly and provide associated error messages
- [ ] Ensure content is not obscured through zooming (no fixed widths)
- [ ] Provide a `manifest.json` file for identifiable homescreen entries
- [ ] Indicate swipe gesture support clearly, and provide simple tap-based alternatives
- [ ] Make sure data tables wider than their container can be scrolled horizontally
- [ ] Avoid time constraints where possible; provide a clear warning and option to extend where not possible 
- [ ] Label and describe the same things with the same terminology
- [ ] Ensure disabled controls are not focusable
- [ ] Do not instate 'infinite scroll' by default; provide buttons to load more items
- [ ] [Avoid justified body text](https://www.w3.org/TR/WCAG20-TECHS/F88.html)
- [ ] [Provide enough spacing between lines of text (`line-height`)](https://www.w3.org/TR/WCAG20-TECHS/C21.html)
- [ ] [Ensure PDF content is accessible (include tags)](https://webaim.org/techniques/acrobat/)
- [ ] [Provide a skip link if necessary](https://webaim.org/techniques/skipnav/) 
- [ ] [Avoid all-caps text](https://github.com/humanmade/hm-pattern-library/issues/75)
- [ ] [Ensure that content is written as clearly and simply as possible](https://www.w3.org/TR/UNDERSTANDING-WCAG20/meaning-supplements.html)
- [ ] Provide descriptive captions for figures
- [ ] Warn users of links that have unusual behaviors, like linking off-site, or loading a new tab
- [ ] [Make content easier to find and improve search results with structured data](https://developers.google.com/search/docs/guides/prototype)
- [ ] Use textual labels to make voice activation cues obvious
- [ ] Do not mark up subheadings/straplines with separate heading elements
- [ ] Ensure primary calls to action are easy to recognize and reach
- [ ] Avoid images of text — text that cannot be translated, selected, or understood by assistive tech
- [ ] Provide a print stylesheet (single column, with interactive content hidden)
- [ ] Use well-established, therefore recognizable, icons and symbols
- [ ] Subset fonts to just the characters you need
- [ ] Instead of obstructing users with CAPTCHAs, use [honeypots](https://en.wikipedia.org/wiki/Honeypot_(computing))
- [ ] Begin long, multi-section documents with a table of contents
- [ ] Don't make users perform actions to reveal content unless completely necessary
- [ ] If content is meant to be hidden, ensure it is properly hidden to all users
- [ ] Make sure controls within hidden content are not focusable
- [ ] Use `srcset` to tailor images to devices and reduce bandwidth costs
- [ ] Do not auto focus form fields, on page load
- [ ] Break up long and complex forms into discrete sections and/or screens 
- [ ] Make forms as short as possible; offer shortcuts like autocompleting the address using the postcode.
