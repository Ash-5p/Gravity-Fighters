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

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to quickly navigate to the recipes that interest me, so that I can avoid having to scroll down the whole page to get to the one I want. | ![screenshot](documentation/features/feature-recipe-nav.png) |
| As a returning site user, I would like to see a confirmation when I have entered the competition, so that I can clearly see that my entry has been successful. | ![screenshot](documentation/features/feature-confirmation.png) |
| As a returning site user, I would like to be able to collapse the workouts down, so that I can see a list of available workouts without the page being too full. | ![screenshot](documentation/features/feature-workouts-detail.png) |

## Bugs

- Overflow on confirmation page

    ![screenshot](documentation/bugs/bug-confirmation-overflow.png)

    - To fix this, I removed the css width property of the competition section.

- Overflow on recipes page

    ![screenshot](documentation/bugs/bug-recipes-overflow.png)

    - To fix this, I set the margin of the nav-5 div to 0.


## Unfixed Bugs

> [!NOTE]  
> There are no remaining bugs that I am aware of.
