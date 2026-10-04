# Assignment 3. Responsive Web Design

Name: Fariddin
Group: 4

## Part 1. Media Queries

### Task 0. Responsive Typography

Make a simple page with headings and paragraphs and change the font sizes for mobile, tablet and desktop with media queries.

Files: task0.html, task0.css

![task0 desktop](screenshots/task0-desktop.png)
![task0 tablet](screenshots/task0-tablet.png)
![task0 mobile](screenshots/task0-mobile.png)

### Task 1. Responsive Layout with Media Queries

Make a page with three boxes. Desktop: three in a row. Tablet: two in a row. Mobile: one under another. Only CSS media queries, without Bootstrap.

Files: task1.html, task1.css

![task1 desktop](screenshots/task1-desktop.png)
![task1 tablet](screenshots/task1-tablet.png)
![task1 mobile](screenshots/task1-mobile.png)

## Part 2. Bootstrap Grid System

### Task 2. Bootstrap Responsive Columns

Make a layout with three columns using the 12-column grid. Desktop: 4 columns each. Tablet: two columns in the first row and one in the second. Mobile: all columns stacked.

File: task2.html

![task2 desktop](screenshots/task2-desktop.png)
![task2 tablet](screenshots/task2-tablet.png)
![task2 mobile](screenshots/task2-mobile.png)

### Task 3. Bootstrap Navigation Bar

Make a responsive navbar with a logo on the left, links on the right and a hamburger menu on small screens.

File: task3.html

![task3 desktop](screenshots/task3-desktop.png)
![task3 mobile](screenshots/task3-mobile.png)
![task3 mobile menu open](screenshots/task3-mobile-open.png)

## Part 3. Combined Project

### Task 4. Responsive Portfolio Page

Make a portfolio page with Bootstrap grid and media queries: header with navbar, projects on the left as cards, sidebar with info and contacts on the right, footer at the bottom. Custom media queries change font sizes, spacing and hide some elements on mobile.

Files: task4.html, task4.css

![task4 desktop](screenshots/task4-desktop.png)
![task4 tablet](screenshots/task4-tablet.png)
![task4 mobile](screenshots/task4-mobile.png)

## Summary

First I did the media queries part with font sizes and a flex layout. I used breakpoints 992px for tablet and 768px for mobile in tasks 0 and 1. Then I did the Bootstrap part with col-12, col-md-6 and col-lg-4 classes and a navbar that collapses with navbar-expand-md. In the last task I combined both: Bootstrap grid and cards for the layout and my own media queries (991px and 767px, to match Bootstrap) for font sizes, padding and hiding extra text on mobile.
