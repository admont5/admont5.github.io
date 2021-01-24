# Horiseon Accessibility Challenge

In this example, Horiseon asked that we perform a code refactor for their website to make it accessible and fit quality standards.

## Semantic HTML Elements

The HTML is split between the following semantic sections:
1. header
2. div class="hero"
3. main (consisting of 3 articles)
4. aside
5. footer

## Logical Structure Independent of Styling and Positioning

The HTML now follow a logical structure. All HTML sections are clearly noted. Further, all CSS elements are commented and grouped into cascading sections.

## Accessible Alt Image Attributes

All picture images, except for the background image, are readable by a screen reader. The background image was given an aria label and a title element in the html as follows. All icon images were given a alt="" to mark them as non-necessary to screen readers. 

## Title Element

Title element is set to: Horiseon — SEO, Online Reputation Management, and Social Media Marketing.
Further the webpage is prepared to have meta input for search engine optimization and can be changed as needed.