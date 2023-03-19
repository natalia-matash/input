
> Follow [this instructions](https://mate-academy.github.io/layout_task-guideline/#how-to-solve-the-layout-tasks-on-github)

## ❗️❗️❗️ DON'T FORGET TO PROOFREAD YOUR CODE WITH [CHECKLIST](https://github.com/mate-academy/layout_search-bar-airbnb/blob/master/checklist.md) BEFORE SENDING YOUR PULL REQUEST❗️❗️❗️

## The task
> Create HTML page with two search bars as designed in [the mockup](https://www.figma.com/file/kf3AWulK9elrNk34wtpjPw/Airbnb-Search-bar?node-id=0%3A1). This search bar will be part of big project.

### Requirements:
- use images from [src/images](src/images)
- there must be two search bars
- search bar must have width 100%
- distance between two search bars must be 20px
- the big search bar must have top indent 20px
- follow styles from the mock
- default `font-weight` must be 300
- a search bar has 3 state default, `hover` and `focus`
- don't use JavaScript

### Tips & Hints
- Text `Try "Los Angeles"` is a placeholder.
- Use `&quot;` instead of `"` in the placeholder.
- You have to put `input` inside the `form` for correct data processing. Form should have `action` and `method`
attributes.
- Each search bar be inside its own `form` element.
- Task has styling for `:focus` state. Forms, labels, divs are not focusable by default. Consider it when selecting your
layout.
- Remember that inputs and other interactive elements don’t inherit font styles by default.
- Remember that placeholder has its own set of styles available using `::placeholder` pseudo-element.