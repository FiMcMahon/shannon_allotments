Testing
The Shannon Allotments site has been tested in the following ways -

* Code Validation
* W3C HTML Validator
* W3C CSS Validator
* Lighthouse
* Responsiveness
* A11y Color Contrast Accessibility Checker
* Browser Compatibility
* Testing User Stories
* Peer Review
* Bugs
* Resolved
* Unresolved

## Code Validation
### W3C HTML Validator

I validated both my HTML and CSS code multiple times whilst building the website, I did this so that there were not a huge amount of errors/warnings at the final stages of development for me to deal with. This allowed me to incrementally improve my code and upon completion, there were 0 errors found.

All pages passed the CSS validator without error.

W3C CSS Validator test result

Lighthouse
I Used Lighthouse in Chrome Developer Tools to test each of the pages for:

Performance - How the page performs whilst loading.
Accessibility - How accessible is the site for all users and how can it be improved.
Best Practices - How does the site conform to industry best practices.
SEO - Search engine optimisation. Is the site optimised for search engine result rankings.
After some below 90 scores on initial mobile tests, I compressed the site images and re-tested each page. On these secondary tests, no score came below 94.

As an example, the results for the Shannon Allotments Home Page for both Mobile & Desktop are below.
Lighthouse Testing Mobile

Lighthouse testing Desktop

Responsiveness
Responsive design tests were carried out manually using Google Chrome DevTools.

This included:

Iphone SE, XR, 12pro
Pixel 5
Samsung Galaxy S8, S20 Ultra, A51/71
Ipad Air & Mini
Surface pro 7 & duo
Galaxy Fold
Nest Hub & Hub Max
I also tested on iphone13, Ipad Pro, Macbook and Galaxy Note 8. The only known issues are with the Galaxy fold, where images are not rendering correctly. In future this could be solved via more specific media queires. Otherwise all content and imagery appeared to render as inteneded on all sited devices.

A11y Color Contrast Accessibility Checker
Colour contrast tests were carried out across the website and all came back without issue.

Colour Contrast Checks

Browser Compatibility
The site was tested on Google Chrome, Microsoft Edge, Safari and Mozilla Firefox, with no visible issues for the user. Appearance, functionality and responsiveness were consistent throughout for a range of device sizes and browsers.

Testing User Stories
Understand the purpose of the site on loading
* Understand the purpose of the site on loading
* Navigate through the site smoothly
    The pages can be accessed in the same way on every page, via a very simply navigational menu.
* See examples of ongoing work on the allotment plots
    There is an extensive gallery page and other images on the other pages that the user can browse at leisure.
* Be able to contact the allotment group easily
    An enquiry form on the 'Contact' page, allows for the Allotment group to be contacted directly.
    Location details are on the bottom of the 'Home' page .
    Social media links are also apparent on each page as a secondary means of contact.
* Be able to join a newsletter
    An option to join a newsletter about the Allotments is available on the Contact form.
* Learn more about gardening
    Content on the 'News' page details information about biodiversity and gardening.
* Grow my own vegetables
    An embedded Youtube video on the 'News Page' links to a channel dedicated to informing and guidung beginner gardeners on growing their own fruits and vegetables.
* Learn more about community groups in my area
    The 'Home' page details information about the Allotments and the work the allotment community are doing. 
* Volunteer with community groups
    The oppertunity to volunteer is presented on the 'News'page and a user can contact the Allotment group using the direct contaact form. 
* Understand more about biodiversity
    A section of the 'News' pages is dedicated to information on biodiversity.
* Connect with the Allotment group on social media
    Links to social media are present on each page, in the footer.

Bugs
Resolved
During validation the following bugs occurred.

W3C Resolved Bug W3C Resolved Bug

Both were oversights in the building process and were easily rectified by changing the incriminating file names to spaceless ones and changing the section tag to a div.

Unresolved
There is a bug in the learn page which is a sizing and overflow issue, which had I more time I would solve by more experimentation with the current code. 