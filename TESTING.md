# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
|  | 404.html | ![screenshot](documentation/validation/validation-404.png) | no errors shown |
|  | confirmation.html | ![screenshot](documentation/validation/validation-confirmation.png) | no errors shown |
|  | index.html | ![screenshot](documentation/validation/validation-home.png) | no errors shown |
|  | recipes.html | ![screenshot](documentation/validation/validation-recipes.png) | no errors shown |
|  | workouts.html | ![screenshot](documentation/validation/validation-workouts.png) | no errors shown |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
| assets | style.css | ![screenshot](documentation/validation/validation-css.png) | no errors shown |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Workouts | Recipes | 404 | Confirmation | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/browsers/browser-chrome-home.png) | ![screenshot](documentation/browsers/browser-chrome-workouts.png) | ![screenshot](documentation/browsers/browser-chrome-recipes.png) | ![screenshot](documentation/browsers/browser-chrome-404.png) | ![screenshot](documentation/browsers/browser-chrome-confirmation.png) | Works as expected |
| Edge | ![screenshot](documentation/browsers/browser-edge-home.png) | ![screenshot](documentation/browsers/browser-edge-workouts.png) | ![screenshot](documentation/browsers/browser-edge-recipes.png) | ![screenshot](documentation/browsers/browser-edge-404.png) | ![screenshot](documentation/browsers/browser-edge-confirmation.png) | Works as expected |
| Opera | ![screenshot](documentation/browsers/browser-opera-home.png) | ![screenshot](documentation/browsers/browser-opera-workouts.png) | ![screenshot](documentation/browsers/browser-opera-recipes.png) | ![screenshot](documentation/browsers/browser-opera-404.png) | ![screenshot](documentation/browsers/browser-opera-confirmation.png) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Workouts | Recipes | 404 | Confirmation | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsiveness/responsive-mobile-home.png) | ![screenshot](documentation/responsiveness/responsive-mobile-workouts.png) | ![screenshot](documentation/responsiveness/responsive-mobile-recipes.png) | ![screenshot](documentation/responsiveness/responsive-mobile-404.png) | ![screenshot](documentation/responsiveness/responsive-mobile-confirmation.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/responsiveness/responsive-tablet-home.png) | ![screenshot](documentation/responsiveness/responsive-tablet-workouts.png) | ![screenshot](documentation/responsiveness/responsive-tablet-recipes.png) | ![screenshot](documentation/responsiveness/responsive-tablet-404.png) | ![screenshot](documentation/responsiveness/responsive-tablet-confirmation.png) | Works as expected |
| Desktop | ![screenshot](documentation/responsiveness/responsive-desktop-home.png) | ![screenshot](documentation/responsiveness/responsive-desktop-workouts.png) | ![screenshot](documentation/responsiveness/responsive-desktop-recipes.png) | ![screenshot](documentation/responsiveness/responsive-desktop-404.png) | ![screenshot](documentation/responsiveness/responsive-desktop-confirmation.png) | Works as expected |
| 4K Monitor | ![screenshot](documentation/responsiveness/responsive-4k-home.png) | ![screenshot](documentation/responsiveness/responsive-4k-workouts.png) | ![screenshot](documentation/responsiveness/responsive-4k-recipes.png) | ![screenshot](documentation/responsiveness/responsive-4k-404.png) | ![screenshot](documentation/responsiveness/responsive-4k-confirmation.png) | Minor scaling issues with hero image |
| Google Pixel 7 Pro | ![screenshot](documentation/responsiveness/responsive-pixel-7-pro-home.png) | ![screenshot](documentation/responsiveness/responsive-pixel-7-pro-workouts.png) | ![screenshot](documentation/responsiveness/responsive-pixel-7-pro-recipes.png) | ![screenshot](documentation/responsiveness/responsive-pixel-7-pro-404.png) | ![screenshot](documentation/responsiveness/responsive-pixel-7-pro-confirmation.png) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/lighthouse-home-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-home-desktop.png) | Issues with response time on mobile due to large hero image. Minor issues with response time on desktop |
| Workouts | ![screenshot](documentation/lighthouse/lighthouse-workouts-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-workouts-desktop.png) | Issues with response time on mobile due to large layout shifts. Minor issues with response time on desktop |
| Recipes | ![screenshot](documentation/lighthouse/lighthouse-recipes-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-recipes-desktop.png) | Issues with response time on mobile due to large images. Minor issues with response time on desktop |
| Confirmation | ![screenshot](documentation/lighthouse/lighthouse-confirmation-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-confirmation-desktop.png) | Minor issues with performance on mobile. Minor accessability issue caused by page redirection feature (feature needed for confirmation page) |
| 404 | ![screenshot](documentation/lighthouse/lighthouse-404-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-404-desktop.png) | Issues with performance on mobile due to layout shifts. No issues on desktop |


## User Story Testing

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

Testing user stories is actually quite simple, once you've already got the stories defined on your README.

Most of your project's **features** should already align with the **user stories**,
so this should as simple as creating a table with the user story, matching with the re-used screenshot
from the respective feature.

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature01.png) |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature02.png) |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature03.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature04.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature05.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature06.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/features/feature07.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/features/feature08.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/features/feature09.png) |
| repeat for all remaining user stories | x |

## Bugs

- Overflow on confirmation page

    ![screenshot](documentation/bugs/bug-confirmation-overflow.png)

    - To fix this, I removed the css width property of the competition section.

- Overflow on recipes page

    ![screenshot](documentation/bugs/bug-recipes-overflow.png)

    - To fix this, I set the margin of the nav-5 div to 0.


## Unfixed Bugs

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

You will need to mention unfixed bugs and why they were not fixed.
This section should include shortcomings of the frameworks or technologies used.
Although time can be a big variable to consider, paucity of time and difficulty understanding
implementation is not a valid reason to leave bugs unfixed.

If you've identified any unfixed bugs, no matter how small, be sure to list them here.
It's better to be honest and list them, because if it's not documented and an assessor finds the issue,
they need to know whether or not you're aware of them as well, and why you've not corrected/fixed them.

Some examples:

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

- On devices smaller than 375px, the page starts to have `overflow-x` scrolling.

    ![screenshot](documentation/bugs/unfixed-bug01.png)

    - Attempted fix: I tried to add additional media queries to handle this, but things started becoming too small to read.

- For PP3, when using a helper `clear()` function, any text above the height of the terminal does not clear, and remains when you scroll up.

    ![screenshot](documentation/bugs/unfixed-bug02.png)

    - Attempted fix: I tried to adjust the terminal size, but it only resizes the actual terminal, not the allowable area for text.

- When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.

    ![screenshot](documentation/bugs/unfixed-bug03.png)

    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's dynamically added via JS.

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

If you legitimately cannot find any unfixed bugs or warnings, then use the following sentence:

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

> [!NOTE]  
> There are no remaining bugs that I am aware of.
