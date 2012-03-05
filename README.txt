CONTENTS OF THIS FILE
---------------------
  * Introduction
  * Usage
  * To Do

INTRODUCTION
------------
This module uses webform to calculate answers for a "personality test" type quiz based on select options.
It counts the number of occurences an option is chosen and if there is a tie will then select the first option it comes across.

USAGE
-----
1. Make sure webform module is installed & enabled
2. Create webform for quiz, note the webform id.
3. Change webform id in function dosomething_quiz_form_webform_client_form_#_alter
4. Create select questions with a, b, c, d as safe_keys
   i.e. a|This is an answer for apples
        b|This is an answer for bananas
		c|This is an answer for chocolate
  a) Set questions to required/mandatory
  b) Set questions to random by Display -> Randomize options
5. Set drupal_goto values to corresponding result pages

TO DO
-----
* Abstract code
* Add functionality and interface to manage quizzes and results