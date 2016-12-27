# Introduction-to-forms-list-and-buttons-

For this exercise, I create a simple form that allows a user to submit a review for a restaurant based on the following specifications:

* The form must submit to the URL using the method `post`. I use the server's url `http://kraigh.com/cse104/reviews.php` that I used to be given when I was taking the related course.

* The form must have two fieldsets- one for name and email fields, and one for the review fields.

* All form fields must be properly labeled 
* The form must have the following fields with the specified name:
    * Full name using the name `name`
    * Email using the HTML5 `email` input type and name `email`
    * Menu selection drop-down using the name `menu` and options with values `steak`, `chicken`, and `vegetarian`
    * Rating radio buttons with name `rating` and values `1` - `5`
    * Checkboxes for the user to indicate if they were greeted upon entering and existing the restaurant. Use name `greeted[]` and values `entered` and `exited`
    * Textarea for comments with  name `comments`

Upon submitting your form, you will be taken to a page where you can see all reviews for the restaurant. 
Email field will not appear on this page for privacy reasons.
