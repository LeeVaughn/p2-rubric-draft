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

#### Exceeds Expectations

##### Exceeds Expectations Criteria

```
Exceeds expectations if meets expectations plus the following is true:	
* Uses JavaScript to append HTML for a search bar.
```

##### Exceeds Expectations Template

```
Excellent work using your “vanilla” JavaScript skills and external JavaScript files to build this project, including adding the search feature!
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
* An incorrect number of pagination buttons are created or they do not have the proper page numbers.
* Clicking between or outside of pagination buttons triggers the click event.
* The `active` class is not added to the first pagination button when the application loads.
* When a pagination button is clicked, the `active` class is not added to the clicked pagination button or is not removed from any other pagination buttons.
```

##### Need Work Feedback Template

```
Your pagination buttons are not working properly or are hard-coded into the HTML.
```

#### Meets Expectations

##### Meets Expectations Criteria

```
Meets expectations if all of the following are true:
* The correct number of pagination buttons are created and they have the proper page numbers. For example, if there are 42 students there should be five pagination buttons and they should be numbered 1 through 5.
* Clicking between or outside of pagination buttons does not trigger the click event.
* The `active` class is added to the first pagination button when the application loads.
* When a pagination button is clicked, the `active` class is added to the clicked pagination button and removed from any other pagination buttons.
```
  
##### Meets Expectations Template

```
Great job on creating the correct number of pagination buttons and for properly applying the `active` class to them as needed.
```

#### Exceeds Expectations

##### Exceeds Expectations Criteria

```
Exceeds expectations if meets expectations plus the following is true:
* The number of pagination buttons changes based on how many search results are returned. For example, if nine or fewer results are returned, zero or one pagination buttons are displayed. If 22 search results are returned, three pagination buttons are displayed.
```

##### Exceeds Expectations Template

```
Excellent! You've gone above and beyond and paginated the search results. This is awesome and not an easy task, so be proud!
```

##### Notes

None

---
<!--TODO to do below -->
### Paging

Highest grade: **Exceeds expectations**

#### Needs work

##### Needs Work Criteria

```
Needs work if any of the following are true:
* The first nine students aren’t shown when the page loads or more than nine students show on the page.
* Nothing happens when the buttons are clicked or the wrong students/incorrect number of students are displayed when clicked.
```

##### Need Work Feedback Template

```
Looks like your pagination buttons are not properly displaying the student data.
```

#### Meets Expectations

##### Meets Expectations Criteria

```
Meets expectations if all of the following are true:
* The first nine students are displayed when the page loads.
* Clicking on a pagination button displays the correct nine students. For example, clicking on the  “1” button should show students one to nine, clicking the “2” should show students 10 to 18, etc.
```
  
##### Meets Expectations Template

```
The pagination works great and displays the correct nine students depending on which button is clicked. Nicely done!
``` 

#### Exceeds Expectations

##### Exceeds Expectations Criteria

```
Exceeds expectations if meets expectations plus the following are true:
* When a search yields no matches a message is displayed on the page informing the user that no results have been found.
```

##### Exceeds Expectations Template

```
Your project displays the correct number of students per page and the search provides feedback when no students were found that match the search criteria. Nicely done!
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