# Horiseon 
#### Example of Code Refracting to improve accessibility and code cleanup. 
#### 'Client' Requested to make their website more accessible so that the website is optimized for search engines.

## Improvements:
### Head Section:
- Changed title to match header [*accessiblity improvement*]
- added `<meta>` tags for description and them color to improve SEO [*accessibility improvement*]

### Header:
- Corrected header section from `<div>` to `<header>` 
- Corrected `<div>` for header links to `<nav>` 

### Hero Section:
- Changed hero tag from `<div>` to `<section>` 
- added img role and aria-label to provide alt text to background image in hero section. [*accessibility improvement*]

### Content Section: 
- Changed content tag from `<div>` to `<section>`
- Changed class for the 3 `<div>` tags in content section to `main-content` to reduce redundent styling in css sheet [*css cleanup*]
- Added `alt` to `img` tags [*accessibility improvement*]

### Right Side Section:
- Changed benefits tag from `<div>` to `<section>`
- Changed class for the 3 `<div>` tags in right side section to `benefit-details` to reduce redundent styling in css sheet [*css cleanup*]
- Changed `background-color` style of `benefits` class to `#0072bb` to create more contrast, improving readablity. [*accessibility improvement*]
- Added `alt` to `img` tags [*accessibility improvement*]

### Footer Section:
- Changed `<div>` tag to `<footer>` 

### CSS:
- Changed `.header` and `.footer` to `header` and `footer`  
