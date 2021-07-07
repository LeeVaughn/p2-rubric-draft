# Grading Rubric

## Overall Grading Template Boilerplate

For staff reviews, we have boilerplate messaging for each grading level. This feedback is a starting point and can be modified by the reviewer.

### Needs Work

### Meets Expectations

### Exceeds Expectations

---

## Rubric / Grading Requirements

Add one of these sections for each requirement in a project.

---



### External Vanilla JavaScript

Highest grade: **exceeds expectations**

#### Needs work

##### Needs Work Criteria

```
Needs work if any of the following are true:
* Project uses jQuery, some other library, or one or more code snippets or plugins.	
* Uses inline JavaScript instead of keeping all JavaScript in external JS files.
* Components of the HTML markup for the student list or pagination buttons are added directly in the HTML instead of being created dynamically with JavaScript.
```

##### Need Work Feedback Template

```
It looks like you utilized snippets, plugins, or libraries in your project or there's a problem with how you're adding the student data and pagination buttons.
```

#### Meets Expectations

##### Meets Expectations Criteria

```
Meets expectations if all of the following are true:
* Project contains only plain “vanilla” JavaScript and doesn't rely on jQuery, some other library, or any code snippets or plugins.
* No inline JavaScript is used. All JavaScript is linked from external files.
* Uses external JavaScript to append markup for the student list and pagination buttons so that none of the markup is added directly into the HTML.
``` 
  
##### Meets Expectations Template

```
Excellent work using your “vanilla” JavaScript skills and external JavaScript files to build this project!
```
<!--TODO to do below -->
#### Exceeds Expectations

##### Exceeds Expectations Criteria

```
Exceeds expectations if meets expectations plus the following are true:
* Uses JavaScript to append HTML for a search bar.
* Search bar matches layout in the mockup file, `examples/example-exceeds.png`, or has custom styling.
```

##### Exceeds Expectations Template

```
Yes! A search bar -- nicely done.

And nice work writing all your own vanilla JavaScript and linking it to the HTML from an external JavaScript file.  Bravo!
``` 

##### Notes
* Check to make sure the HTML pagination links are being added dynamically with JavaScript and have not been hardcoded onto the page. 


* For the “Exceeds Expectations” search bar portion of this project, the students are given the following HTML for to add dynamically with JavaScript:

```html
<label for="search" class="student-search">
  <span>Search by name</span>
  <input id="search" placeholder="Search by name...">
  <button type="button"><img src="img/icn-search.svg" alt="Search icon"></button>
</label>
```

---

### Pagination Buttons

Highest grade: **Exceeds expectations**

#### Needs work

##### Needs Work Criteria

```
Needs work if any of the following are true:
* Incorrect number or numbering of pagination buttons.
* Pagination buttons don't show the correct page.
* Clicking between or outside of pagination buttons triggers the click event.
* The `active` class is not added to the first pagination button when the application loads.
* The `active` class name is not added to the most recently clicked pagination button, or is present on more than one button at any given time.
```

##### Need Work Feedback Template

```
There appears to be a problem with your pagination buttons.
```

#### Meets Expectations

##### Meets Expectations Criteria

```
Meets expectations if all of the following are true:
* Pagination buttons display the correct page.
* Clicking between or outside of pagination buttons does not trigger the click event.
* The `active` class is added to the first pagination button when the application loads.
* The `active` class name is added to the most recently clicked pagination button, and is never present on more than one button at any given time.
* Project has the correct number of pagination buttons and they are numbered correctly. For example, if there are 42 students there should be 5 pagination buttons, numbering 1 through 5.
```
  
##### Meets Expectations Template

```
Awesome!  Your pagination button number correctly and work well!  Applause!!
```

#### Exceeds Expectations

##### Exceeds Expectations Criteria

```
Exceeds expectations if meets expectations plus the following are true:
* The number of pages and pagination buttons change based on how many search results are returned. For example, if 9 or fewer results are returned, 0 or 1 pagination buttons are displayed, if 22 search results are returned, 3 pagination buttons are displayed.
```

##### Exceeds Expectations Template

```
Your pagination button number correctly and work well!  And you've gone above and beyond by paginating the search results. This is awesome and not an easy task, so be proud! 

Applause!!
```

##### Notes

None

---

### Paging

Highest grade: **Exceeds expectations**

#### Needs work

##### Needs Work Criteria

```
Needs work if any of the following are true:
* The first 9 students from the array of objects in the `js/data.js` file are not displayed when the page first loads.
* Clicked pagination buttons fail to display the correct students or the correct number of students.
```

##### Need Work Feedback Template

```
Looks like your paging is off. The pagination buttons are not properly displaying the student data.
```

#### Meets Expectations

##### Meets Expectations Criteria

```
Meets expectations if all of the following are true:
* The first 9 students from the array of objects in the `js/data.js` file are displayed when the page first loads.
* Clicking on a pagination button displays the correct number of students. For example, clicking on the  “1” button should show students 1 to 9, clicking the “2” should show 10 to 18, etc. 
```
  
##### Meets Expectations Template

```
Awesome -- you're displaying the correct number of students per page and the students shown properly reflect the button clicked.
``` 

#### Exceeds Expectations

##### Exceeds Expectations Criteria

```
Exceeds expectations if meets expectations plus the following are true:
* When a search yields 0 results, a "No results" message is displayed on the page, and is removed or hidden when students are displayed on the page again.
* After a search, pages only display students that match the search criteria and pages display the correct number of students. For example, if 22 search results are returned, the third and final page should only display four students.
```

##### Exceeds Expectations Template

```
Awesome!  Your project displays the correct number of students per page and the search provides feedback when no students were found to match the search criteria. Nicely done.
```

##### Notes

None

---

### Code Quality

Highest grade: **Meets expectations**

#### Needs work

##### Needs Work Criteria

```
Needs work if any of the following are true:
* No new comments have been added to the `js/script.js` file.
* Uncaught errors appear in the Chrome DevTools console while using the Pagination app in Chrome.
```

##### Need Work Feedback Template

```
Looks like there's a problem with your code comments or errors showing up in the console.

Remember, code comments are important for helping others understand how your code functions.

And resolving any and all errors before submitting your work is a hallmark of a great developer
```

#### Meets Expectations

##### Meets Expectations Criteria

```
Meets expectations if all of the following are true:
* Any new comments have been added to the `js/script.js` file.
* No uncaught errors appear in the Chrome DevTools console while using the Pagination app in Chrome.
```

##### Meets Expectations Template

```
No errors in the console, and your code comments help demonstrate at a glance how your code works and what it does. Your fellow developers and your future self will thank you for making a habit of adding smart code comments to your projects. Keep up the great work!
```

#### Exceeds Expectations

##### Exceeds Expectations Criteria

```
* N/A
```

##### Exceeds Expectations Template

##### Notes

None

---