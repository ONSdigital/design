# Accessibilty checklist

Typography
----------

*   Nest headings in order (for example, H2s only appear after H1s)
*   Don't skip heading levels
*   Use semantic mark-up (for example, headings, lists and blockquotes)
*   Links should look like links (for example, blue and underlined)
*   Don't use link title attribute
*   Lines are less than 80 characters wide
*   Suitable vertical spacing between lines and paragraphs
*   Avoid italics, block capitals or justified text
*   Use a san-serif font with thick letters
*   Make sure text can be resized

Content
-------

*   Use plain English
*   Explain unusual words and jargon
*   Put the most important information at the start
*   Explain what a user has to do in a clear and concise way
*   Use headings and lists to break the content into chunks
*   Download links labels must include file format and size
*   Headings, links and button text must be unique and descriptive
*   Each page must have unique, descriptive h1 and page title

Tables
------

*   [Tables are accessible](https://www.gov.uk/guidance/content-design/tables#how-to-make-tables-accessible)
*   Only use tables to present data
*   Tables can be used as accessible alternatives to charts and infographics
*   Split complex tables into multiple small ones
*   Tables must have the correct tags for header and data cells, so screen reader users can understand and navigate them

Colour and contrast
-------------------

*   [Check colour contrast](http://webaim.org/resources/contrastchecker/) between text and background meets standards
*   Check design works in black and white
*   Don't communicate using colour alone
*   Check design works in high contrast mode

Interaction
-----------

*   Check design is functional when using a keyboard to navigate
*   It must be visually apparent which page element has the current keyboard focus
*   Complex interface components, like sliders, should be avoided when simple solutions, like a text input, can be used instead
*   If an experience cannot be made accessible, create another route for users to get that information

Forms
-----

*   All form inputs have labels
*   Forms and interactive elements should have useful hints
*   Error messages must suggest ways to fix error
*   Error messages should show a summary of errors above the h1 and move focus to it
*   Error message summary should include an h1 message that tells the screen reader user there is a problem, and gives a list of descriptive errors with links to the relevant fields

Images
------

*   Images must have good alternative text
*   Avoid using images of text

Layout and structure
--------------------

*   Layout is consistent and predictable
*   Do not rely upon shape, size, or visual location (for example, "Click the square icon to continue" or "Instructions are in the right-hand column")
*   Reading and navigation order is logical
*   The page makes sense with CSS off
*   The page is readable and functional when the text size is doubled
*   Frames are appropriately titled

iframes
-------

*   Use the iframe title attribute to give the content a descriptive title
*   Make sure interactive elements inside an iframe are usable with a keyboard
*   Make sure interative elements have a clear focus style
*   Test the iframe is readable and functional with browser zoom at 200%
*   Test the content doesn't overflow or become truncated when font size is increased

Manual tests
------------

*   Use the service with a keyboard only - no mouse
*   Increase font size to 200%
*   Test in high contrast mode
*   Check html mark-up is valid
*   Check in all [supported browsers](http://onsdigital.github.io/ons-pattern-library-starter/gettingstarted/)
*   Check in all [supported assistive technologies](https://www.ons.gov.uk/help/accessibility)

Resources
---------

*   [Making your service accessible: an introduction](https://www.gov.uk/service-manual/helping-people-to-use-your-service/making-your-service-accessible-an-introduction)
*   [WebAIM's WCAG 2.0 Checklist](http://webaim.org/standards/wcag/checklist)
*   [18F Accessibility Guide Checklist](https://accessibility.18f.gov/checklist/)
*   [Inclusive Design Principles by Paciello Group](http://inclusivedesignprinciples.org/)
*   [Vox Media Accessibility Guidelines](http://accessibility.voxmedia.com/)
*   [Dos and don'ts on designing for accessibility](https://accessibility.blog.gov.uk/2016/09/02/dos-and-donts-on-designing-for-accessibility/)
*   [Coop Design Manual Accessibility](http://coop-design-manual.herokuapp.com/accessibility.html)
*   [Accessibility Acceptance Criteria](https://github.com/alphagov/accessible-autocomplete/blob/master/accessibility-criteria.md)
*   [Tips for Creating Accessible SVG](https://www.sitepoint.com/tips-accessible-svg/)
*   [SVG ARIA polyfill](http://decks.tink.uk/2017/lws/index.html#cover)
*   [Accessible SVG line graphs](https://tink.uk/accessible-svg-line-graphs/)
*   [Color advice for maps](http://colorbrewer2.org/)
