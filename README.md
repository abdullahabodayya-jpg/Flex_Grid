# CSS Flex & Grid — Same Design Version

All exercises use one external `style.css` and the same header, hero, navigation frame, buttons, and footer design as the provided CSS Practice example.

# Flexbox & Grid Exercises

A collection of practical CSS exercises focused on **Flexbox** and **CSS Grid**.

These exercises are designed to build a strong understanding of modern CSS layout techniques through small, focused tasks and progressively more complex page layouts.

---

## Exercises

### 01 — Four Boxes Using Flexbox

A basic exercise to practice creating and arranging four boxes using **CSS Flexbox**.

**Topics practiced:**

* `display: flex`
* `flex-direction`
* Spacing between elements
* Basic alignment
* Flex containers and flex items

---

### 02 — Center a Div Using Flexbox

A simple exercise focused on perfectly centering an element inside its container.

**Topics practiced:**

* `justify-content`
* `align-items`
* Horizontal and vertical centering
* Flexbox alignment

---

### 03 — Flexible Content Boxes

An exercise for creating content boxes that can dynamically adapt to the available space.

**Topics practiced:**

* Flexible widths
* `flex-grow`
* `flex-shrink`
* `flex-basis`
* Responsive Flexbox layouts

---

### 04 — Vegetables Using Flexbox

A practical layout exercise using Flexbox to arrange vegetable items in a clean and organized way.

**Topics practiced:**

* Flexbox layout
* Row and column arrangements
* Spacing
* Alignment
* Wrapping elements

---

### 05 — `align-self` Exercise

An exercise focused on controlling the alignment of individual flex items independently from the other items.

**Topics practiced:**

* `align-self`
* `align-items`
* Individual item alignment
* Flexbox cross-axis behavior

---

### 06 — Web Page Mockup

A complete web page layout created using modern CSS layout techniques.

**Topics practiced:**

* Page structure
* Flexbox
* Section alignment
* Navigation/layout components
* Responsive structure
* Combining multiple CSS properties

---

### 07 — YouTube Layout Mockup

A practice project that recreates the basic structure of a YouTube-style interface.

**Topics practiced:**

* Flexbox
* Grid
* Navigation layout
* Video/content cards
* Sidebar layouts
* Responsive content organization

---

### 08 — Basic Page Layout Using Grid

A basic introduction to building complete page layouts using **CSS Grid**.

**Topics practiced:**

* `display: grid`
* `grid-template-columns`
* `grid-template-rows`
* `gap`
* Grid areas
* Page structure

---

### 09 — Image Cards Using Grid

A card-based layout where images and content are organized using CSS Grid.

**Topics practiced:**

* CSS Grid
* Grid columns
* Grid gaps
* Image cards
* Responsive layouts
* Reusable components

---

### 10 — Complex Nested Grid

An advanced exercise that combines multiple Grid containers to create a more complex layout.

**Topics practiced:**

* Nested CSS Grid
* Multiple grid containers
* Grid rows and columns
* Grid alignment
* Complex layouts
* Combining Grid with Flexbox

---

## Technologies Used

* HTML5
* CSS3
* CSS Flexbox
* CSS Grid

---

## Learning Objectives

By completing these exercises, the main goals are to:

* Understand how CSS Flexbox works.
* Understand how CSS Grid works.
* Learn the difference between Flexbox and Grid.
* Practice horizontal and vertical alignment.
* Build responsive layouts.
* Create reusable content/card layouts.
* Work with complex nested layouts.
* Combine Flexbox and Grid in real-world page structures.

---

## Difficulty Progression

The exercises gradually increase in complexity:

| Exercise | Topic                  | Level        |
| -------- | ---------------------- | ------------ |
| 01       | Four Boxes             | Beginner     |
| 02       | Center a Div           | Beginner     |
| 03       | Flexible Content Boxes | Beginner     |
| 04       | Vegetables Layout      | Beginner     |
| 05       | `align-self`           | Beginner     |
| 06       | Web Page Mockup        | Intermediate |
| 07       | YouTube Layout         | Intermediate |
| 08       | Basic Grid Layout      | Intermediate |
| 09       | Image Cards            | Intermediate |
| 10       | Nested Grid            | Advanced     |

---

## Flexbox vs Grid

### Flexbox

Flexbox is mainly designed for **one-dimensional layouts**.

It is useful when arranging elements:

* In a row
* In a column
* Along a main axis
* Along a cross axis

Example:

```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
}
```

### CSS Grid

CSS Grid is designed for **two-dimensional layouts**.

It is useful when working with:

* Rows
* Columns
* Complex page layouts
* Card grids
* Nested layouts

Example:

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}
```

---

## What I Practiced

Throughout these exercises, I practiced:

* Creating Flexbox containers
* Aligning elements horizontally and vertically
* Controlling spacing between elements
* Making elements flexible
* Using `align-self`
* Creating page layouts
* Building card-based interfaces
* Creating CSS Grid layouts
* Working with rows and columns
* Creating nested grids
* Combining Flexbox and Grid

---

## Project Structure

A possible project structure:

```text
Flexbox-Grid-Exercises/
│
├── 01-four-boxes/
│   ├── index.html
│   └── style.css
│
├── 02-center-div/
│   ├── index.html
│   └── style.css
│
├── 03-flexible-content-boxes/
│   ├── index.html
│   └── style.css
│
├── 04-vegetables/
│   ├── index.html
│   └── style.css
│
├── 05-align-self/
│   ├── index.html
│   └── style.css
│
├── 06-web-page-mockup/
│   ├── index.html
│   └── style.css
│
├── 07-youtube-layout/
│   ├── index.html
│   └── style.css
│
├── 08-basic-grid-layout/
│   ├── index.html
│   └── style.css
│
├── 09-image-cards/
│   ├── index.html
│   └── style.css
│
├── 10-complex-nested-grid/
│   ├── index.html
│   └── style.css
│
└── README.md
```

---

## Conclusion

These exercises provide practical experience with modern CSS layout systems.

Starting with simple Flexbox layouts and progressing toward complex Grid structures, the exercises help develop the skills needed to build clean, responsive, and organized web interfaces.

**Main focus:**
`HTML → CSS → Flexbox → Grid → Responsive Layouts`


## Author

Abdullah Abu Dayeh
Frontend development learner focused on building a strong foundation in HTML, CSS, JavaScript, and modern web development technologies.

## License

This project was created for learning and practice purposes.

You are welcome to explore the code and use it as a reference for learning HTML and CSS.