# Full Stack Web Development — Lab 2

**Topic:** Advanced CSS & Bootstrap Flex Utilities  
**Student Name:** Abdullah Khan  
**Repository:** [https://github.com/abdullah0501232/lab02-fullstack](https://github.com/abdullah0501232/lab02-fullstack)

---

## Overview

This repository contains solutions for all practical tasks of **Lab 2**, developed both as standalone task modules (`task1.html` – `task4.html`) and as an integrated master single-page student portfolio (`index.html`).

---

## Lab Tasks Breakdown

### 🔹 [Task 1 — Responsive Student Profile Layout](task1.html)
- **Files:** `task1.html` & `task1.css`
- **Features & Requirements:**
  - Student Profile containing student image, name, degree/program, short introduction, and three core skills.
  - Side-by-side flex layout using `display: flex;`, `justify-content: space-between;`, and `align-items: center;`.
  - Responsive adaptation: On mobile viewports (&le; 768px), the layout automatically stacks vertically with centered alignment.

### 🔹 [Task 2 — Interactive Project Cards](task2.html)
- **Files:** `task2.html` & `task2.css`
- **Features & Requirements:**
  - Three project cards: **Web Development Project**, **Database Project**, and **AI/ML Project**.
  - Each card contains an image, title, description, and action button.
  - Flexbox arrangement (`display: flex; justify-content: center; flex-wrap: wrap; gap: ...;`).
  - Interactive CSS transitions & transforms: cards move upward (`translateY(-10px)`) and scale smoothly on hover.
  - CSS Filters (`grayscale`, `sepia`, `contrast`) applied to images, which are dynamically removed/cleared on hover.

### 🔹 [Task 3 — Profile Badge Using CSS Positioning and Pseudo-elements](task3.html)
- **Files:** `task3.html` & `task3.css`
- **Features & Requirements:**
  - Student Achievement Card with Student Name, Achievement Title, Short Description, Date, and a Featured Badge.
  - Main card uses `position: relative;`.
  - Featured badge uses `position: absolute;` pinned to the **top-right corner**.
  - Decorative accents built with `::before` (custom ribbon badge) and `::after` (gradient line beneath title).

### 🔹 [Task 4 — Bootstrap Flexbox Dashboard](task4.html)
- **Files:** `task4.html` & `task4.css`
- **Features & Requirements:**
  - Small Student Dashboard containing four metric cards: **Courses**, **Assignments**, **Projects**, and **Attendance**.
  - **Restriction strictly satisfied:** The main dashboard layout uses Bootstrap Flex utility classes (`d-flex`, `justify-content-between`, `align-items-center`, `flex-wrap`, `gap-3`) with **zero custom `display: flex` container CSS**.
  - Row layout on desktop screens with automatic wrapping and equal spacing on mobile/tablet viewports.

### 🔹 [Task 5 — Complete Mini Portfolio Challenge](index.html)
- **Files:** `index.html` & `style.css`
- **Features & Requirements:**
  - Single-page Student Portfolio uniting all lab components in the prescribed sequence:
    1. **Navigation** (Sticky navbar with direct links to sections and individual task pages)
    2. **Student Introduction** (Task 1 Flexbox profile layout)
    3. **Skills** (Flexbox skill cards with hover transform transitions)
    4. **Projects** (Task 2 interactive project cards with CSS image filters)
    5. **Achievement** (Task 3 relative/absolute positioning card with pseudo-elements)
    6. **Dashboard** (Task 4 Bootstrap Flex utility dashboard)
    7. **Footer**
  - Demonstrates all 7 core Lab 2 concepts:
    1. Flexbox
    2. Positioning
    3. Pseudo-elements
    4. CSS filters
    5. CSS transitions/transforms
    6. Bootstrap Flex utilities
    7. Responsive design

---

## Technologies Used
- **HTML5** (Semantic Elements)
- **CSS3** (Flexbox, Positioning, Filters, Transitions, Transforms, Pseudo-elements)
- **Bootstrap 5.3.3** (Flex Utilities & Components)
- **Bootstrap Icons 1.11.3**
- **Git & GitHub**

---

## Git Submission Instructions

```bash
git add .
git commit -m "Complete Lab 2 practical task"
git push
```
