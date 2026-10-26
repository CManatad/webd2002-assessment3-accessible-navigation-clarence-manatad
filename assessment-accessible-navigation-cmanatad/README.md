# Accessible Navigation (10%)

In this assessment, you will build a responsive, accessible global navigation component from the provided Figma file. Working from the Figma and starter files, you will write the HTML and CSS to implement the navigation across multiple screen sizes and apply JavaScript to bring the interactive patterns to life. At narrow and wide views, the navigation should have full support for keyboard, mouse (pointer), and touch input.

You will implement two navigation patterns: a hamburger/disclosure menu for narrow viewports and a multi-level menu for large viewports. Both patterns must meet WCAG 2.2 accessibility requirements across structure, interactivity, state communication, and visual design. This assessment also draws on earlier module work in colour contrast, focus visibility, and accessible SVG, applying those skills directly in a navigation context.

Your solution must include a working skip link, correct semantic landmarks and HTML, appropriate ARIA attributes to communicate state, clearly visible focus rings with sufficient contrast, accessible SVG icons, appropriately sized touch targets, and code comments that identify your key pattern and ARIA decisions.

## REQUIREMENTS

Figma and Starter Files
-   The starter and Figma files will be available on GitHub. Please fork the starter and Figma files from this link in Brightspace.

-   The Figma is the complete visuals for both viewports, including colours, typography, spacing, layout, and focus styles. The starter files include the base menu HTML and the narrow viewport CSS. The navigation should match the Figma file as closely as possible.

Your navigation must include the following:
-   Skip link
-   Semantic structure and ARIA landmarks
-   Hamburger/Disclosure pattern
-   Multi-level menu
-   Keyboard operability and focus management
-   Focus indicators and contrast
-   Touch and pointer support
-   Code comments


## SUBMISSION

You must submit the following to Brightspace by the due date and time:

1. A GitHub link to your completed version of the starter code, Accessible Navigation project folder that was forked
from the original repostitory.

Late submissions will **not** be accepted. See Digital Design’s Assessment Extension Guidelines


## ACADEMIC INTEGRITY

### Use of Generative AI Tools
For this assessment, the use of any Generative Artificial Intelligence (AI) tools is not permitted. This assessment is intended to measure your ability to generate your own work. Your unique comprehension and interpretation of the course content must be demonstrated in order to be successful. Using prohibited resources will be considered academic misconduct and addressed following SR 1.3 Academic Integrity Procedure.

### Incremental Development
You must demonstrate incremental development of your solution. This means you must begin work as soon as possible and commit often to the assignment repository. Each commit must demonstrate functional improvements to the solution. Just like in a professional environment, leaving a task untouched until right before the deadline is not acceptable — start early and make consistent progress.

Ensure all required code comments have been included.

Push your completed assessment to GitHub repository (this repo should be forked from the original) and the link submitted to Brightspace before the due date and time. Late pushes will be counted as late submissions and will not be accepted unless prior arrangements have been made. See Digital Design's Assessment Extension Guideline.


## Rubric (total 42)

- Skip link (2)
- Visual Design (2)
- Semantic Structure & ARIA Landmarks (2)
- Hamburger / Disclosure (12)
- Multi-Level Menu (8)
- Keyboard & Focus Management (8)
- Focus Indicators & Contrast (4)
- Touch & Pointer (2)
- Code Comments (2)

### Skip Link

| Criterion | Completed (2 pts) | Satisfactory (1 pt) | Incomplete (0 pts) | Score |
|---|---|---|---|---|
| Skip Link | Skip link is the first focusable element on the page; correctly targets the main content; becomes visible when focused; accessible name clearly describes its purpose. | Skip link is present and targets the correct element; one minor issue with visibility on focus or accessible name. | Skip link is absent, does not function, or is never visible when focused. | / 2 |

### Visual Design

| Criterion | Completed (2 pts) | Satisfactory (1 pt) | Incomplete (0 pts) | Score |
|---|---|---|---|---|
| Figma Fidelity | The navigation closely matches the Figma design across both viewports; colours (focus and hover states), spacing, and layout are implemented as specified. | The navigation mostly matches the Figma; minor deviations in spacing, colour, or layout across one viewport. | The navigation does not reflect the Figma design; significant deviations across both viewports. | / 2 |

### Semantic Structure & ARIA Landmarks

| Criterion | Completed (2 pts) | Satisfactory (1 pt) | Incomplete (0 pts) | Score |
|---|---|---|---|---|
| HTML Structure, ARIA Landmarks & Accessible Name | All major sectioning elements are used correctly and in the right order; landmark regions are present, correctly structured, and free of duplicates or omissions; the navigation has a correct and descriptive accessible name. | Most sectioning elements and landmarks are correct; one minor omission or error (e.g. navigation missing an accessible name, or one region using a non-semantic element). | Semantic sectioning elements and landmark regions are largely absent or incorrectly applied; no accessible name on the navigation. | / 2 |

### Hamburger / Disclosure Pattern

| Criterion | Excellent (4 pts) | Good (3 pts) | Satisfactory (2 pts) | Developing (1 pt) | Incomplete (0 pts) | Score |
|---|---|---|---|---|---|---|
| Toggle, Icon & Accessible Name | An appropriate interactive element is used as the menu toggle; the toggle has a descriptive accessible name; the hamburger icon is accessible and does not interfere with the toggle's accessible name. | An appropriate interactive element is used with a descriptive accessible name; the icon has one minor accessibility issue, such as an ambiguous label or slight interference with the accessible name, that does not affect usability. | An appropriate interactive element is used; either the accessible name is present but generic, or the icon is not fully accessible to assistive technology, but not both. | More than one issue is present across the toggle element, accessible name, and icon; for example, the accessible name is missing or unclear and the icon is also not accessible. | An inappropriate or non-interactive element is used as the toggle; no accessible name provided; icon is not accessible. | / 4 |
| State Communication | The open and closed state of the menu is correctly communicated to assistive technology at all times. | State is correctly communicated to assistive technology in nearly all interactions; one instance updates with a brief delay that does not affect usability. | State is communicated to assistive technology in most interactions; one or two instances use an incorrect or missing state value. | State is communicated in only some interactions; several instances are missing the state value or use an incorrect one, creating noticeable gaps for assistive technology users. | State is not communicated to assistive technology. | / 4 |
| Motion | Animation respects the user's motion preference; the menu is fully functional with motion reduced or removed. | Motion preference is respected across nearly all animations; one minor animation persists briefly when reduced motion is set but does not affect usability. | Motion preference is respected for most animations; one animation is reduced but not fully removed when required. | Motion preference is only partially implemented; several animations continue to play, or are only partially reduced, when reduced motion is set. | Motion preference is not respected. | / 4 |

### Multi-Level Menu

| Criterion | Excellent (4 pts) | Good (3 pts) | Satisfactory (2 pts) | Developing (1 pt) | Incomplete (0 pts) | Score |
|---|---|---|---|---|---|---|
| Semantic Grouping | Sub-navigation content is correctly grouped using semantic structure; groupings are logical and consistent throughout the menu. | Sub-navigation content is grouped using semantic structure; minor inconsistency in one grouping. | Grouping is mostly correct; one panel uses a non-semantic approach or is inconsistently structured. | Grouping is partially semantic; multiple panels use non-semantic approaches or inconsistent structure. | Sub-navigation content is not grouped semantically. | / 4 |
| State Communication | The open and closed state of each sub-navigation panel is correctly communicated to assistive technology. | State is communicated on all panels; one minor inconsistency that does not affect usability. | State is communicated on most panels; one panel is missing or has an error. | State is communicated on some panels; multiple panels are missing or have errors. | Panel state is not communicated to assistive technology. | / 4 |

### Keyboard & Focus Management

| Criterion | Excellent (4 pts) | Good (3 pts) | Satisfactory (2 pts) | Developing (1 pt) | Incomplete (0 pts) | Score |
|---|---|---|---|---|---|---|
| Hamburger Pattern | Escape closes the open menu and returns focus to the trigger; keyboard focus is not trapped in the open menu; page scroll is not locked when the menu is open. | All three criteria are addressed; one has a minor implementation issue, such as a brief delay before focus returns to the trigger, that does not significantly affect usability. | Two of the three criteria are fully met; the third, such as scroll locking or Escape closing the menu, is inconsistently implemented. | Only one of the three criteria is reliably met; the other two are missing or only partially implemented. | Keyboard focus is trapped, scroll is locked, or Escape does not close the menu. | / 4 |
| Multi-Level Menu | The menu is fully keyboard operable with a logical and predictable tab order; the menu is fully operable without a mouse; focus is managed correctly when panels open and close. | The menu is fully keyboard operable with one minor deviation in tab order or focus management, such as a single element out of sequence, that does not prevent use. | The menu is keyboard operable overall; one panel has a tab order issue or a focus management gap that requires extra effort to navigate but does not block access. | The menu is only partially keyboard operable; more than one panel has tab order or focus management issues that prevent some content from being reached. | The menu is not keyboard operable or is entirely mouse-dependent. | / 4 |

### Focus Indicators & Contrast

| Criterion | Excellent (4 pts) | Good (3 pts) | Satisfactory (2 pts) | Developing (1 pt) | Incomplete (0 pts) | Score |
|---|---|---|---|---|---|---|
| Focus Indicators & Contrast | Focus indicators are implemented as specified in the Figma on all focusable elements; all text and non-text contrast meets WCAG 2.2 AA requirements throughout both patterns. | Focus indicators are implemented on all focusable elements; one minor contrast shortfall in a non-critical area. | Focus indicators present on most elements; one element missing a focus indicator or one minor contrast shortfall. | Focus indicators are present on some elements; multiple contrast shortfalls or missing indicators. | Focus indicators absent on most elements; colour values not implemented from the Figma. | / 4 |

### Touch & Pointer Support

| Criterion | Completed (2 pts) | Satisfactory (1 pt) | Incomplete (0 pts) | Score |
|---|---|---|---|---|
| Touch & Pointer Support | All interactive targets are sized and spaced as specified in the Figma and meet WCAG 2.5.8; no interaction relies on hover alone. | Most targets are correctly sized and spaced; one minor sizing, spacing, or hover-only issue. | Touch target sizing and spacing not addressed; hover-only interactions present. | / 2 |

### Code Comments

| Criterion | Completed (1 pt) | Incomplete (0 pts) | Score |
|---|---|---|---|
| HTML Comments | Each major navigation pattern and key accessibility decisions are identified with a comment in the HTML. | Comments are absent or too minimal to be meaningful. | / 1 |
| CSS Comments | Key accessibility decisions are identified with a comment in the CSS. | Comments are absent or too minimal to be meaningful. | / 1 |