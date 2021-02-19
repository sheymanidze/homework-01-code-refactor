# homework01
## Code Refactor

## Table of contents

* General info
* Changes
* Screenshot
* Deployment of application
* Tests
* Revision


## General Info
Code needed to be adjusted to follow accessibility standarts, have better structure, and have sequential order. In order to do so, the folllowing steps were been taken:

## Changes

HTML:
* Replacement of non-semantic elements with semantic such as 
1. <div class="header"> to <header class="header">;
2. <div class="footer"> to <footer class="footer">;
3. <div> to <section>;
* Adding alt to every img 
* Fixing SEO link by adding id="Search Engine Optimization"
* Adding word "group" for elements: benefit-lead, benefit-brand, and bemefit-cost. It will let us to make changes in css for all "group" class instead of listing every single one separately. 
*Adding word line for elements: search-engine-optimization, social-media-marketing; search-engine-optimization img, online-reputation-managemnet img, social-media-marketing img; search-engine-optimization h2, and online-reputation-managemnet h2.

CSS:
* .search-engine-optimization, .online-reputation-managemnet, .social-media-marketing; .search-engine-optimization img, .online-reputation-managemnet img, .social-media-marketing img; and .search-engine-optimization h2, online-reputation-managemnet h2, .social-media-marketing h2 were put after.content to follow sequential order.
* Repetitive components were deleted and replaced with .group, .group img, .group h3


## Screenshot
 
 [Finished-product](/Users/Anastasia/homework01/assets/images/horiseon-website.png)

## Deployment of application
To run a project, please follow the link [https://sheymanidze.github.io/homework-01-code-refactor/](https://sheymanidze.github.io/homework-01-code-refactor/)

## Test

After checking page for accessibility [https://wave.webaim.org/](https://wave.webaim.org/) several errors and alerts were found [errors-and-alerts](./assets/images/errors-and-alerts.png):
1. 3 Contrast Errors "Very low contrast" 
[adjustments-within-wave-report](./assets/images/adjustments-within-wave.png)
2. 3 Alerts "Redundant alternitive text"

## Revisions

Changing alt text for the img's in order not to be repetitive, 
Contrast has to be changed/adjusted since it is fail accessibility test
In the future: buttons for keyboard users has to be added as well as screen size changing depending on the device.