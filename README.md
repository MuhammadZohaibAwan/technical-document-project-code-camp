# [Build a Technical Documentation Page](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-technical-documentation-page)
## [Free Code Camp](https://www.freecodecamp.org) - Responsive Web Design Projects

## Objective
Build a technical documentation page that is functionally similar to the [example page](https://codepen.io/freeCodeCamp/full/NdrKKL).

The [completed page](https://elrolfe-fcc-rwd.gitlab.io/techdoc) was coded with HTML and CSS.

## User Stories
The technical documentation page fulfills the following user stories provided by FreeCodeCamp.org:
1. I can see a `main` element with a corresponding `id="main-doc"`, which contains the page's main content (technical documentation).
2. Within the `#main-doc` element, I can see several `section` elements, each with a class of `main-section`. There should be a minimum of 5.
3. The first element within each `.main-section` should be a `header` element which contains text that describes the topic of that section.
4. Each `section` element with a class of `.main-section` should also have an id that corresponds with the text of each `header` contained within it. Any spaces should be replaced with underscores (e.g. The `section` that contains the header "Javascript and Java" should have a corresponding `id="Javascript_and_Java").
5. The `.main-section` elements should contain at least 10 `p` elements total (not each).
6. The `.main-section` elements should contain at least 5 `code` elements total (not each).
7. The `.main-section` elements should contain at least 5 `li` items total (not each).
8. I can see a `nav` element with a corresponding `id="navbar"`.
9. The navbar element should contain one `header` element which contains text that describes the topic of the technical documentation.
10. Additionally, the navbar should contain link (`a`) elements with the class of `nav-link`. There should be one for every element with the class `main-section`.
11. The `header` element in the navbar must come before any link (`a`) elements in the navbar.
12. Each element with the class of `nav-link` should contain text that corresponds to the `header` text within each `section` (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world").
13. When I click on a navbar element, the page should navigate to the corresponding section of the `main-doc` element (e.g. if I click on a `nav-link` element that contains the text "Hello world", the page navigates to a `section` element that has that id and contains the corresponding `header`).
14. On regular sized devices (laptops, desktops), the element with `id="navbar"` should be shown on th eleft side of the screen and should always be visible to the user.
15. My Technical Documentation page should use at least one media query.