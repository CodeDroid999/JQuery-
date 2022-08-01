#learn jQuery, the most popular JavaScript tool of all time.


#Clone the JQuery Playground file and practice the following on it.


#steps to add jquery to a HTML Document 

1.Script Tags and Document Ready	
   - add a script element at the top of your page. Be sure to close it on the following line.
   - Inside your script element, add this code:
         $(document).ready(function() {  
     to your script.Then close it on the following line (still inside your script element)
     with: 
            });

     #Code you put inside this function will run as soon as your browser has loaded your page.
    This is important because without your document ready function, your code may run before                                        
    your HTML is rendered, which would cause bugs.

2.Target HTML Elements with Selectors Using jQuery
   - write your first jQuery statement. All jQuery functions start with a $, usually referred 
     to as a dollar sign operator, or as bling.
     #jQuery often selects an HTML element with a selector, then does something to that element.
   -For example,make all of your button elements bounce.Add this code inside your document ready function:
      $("button").addClass("animated bounce");

   #Note include both the jQuery library and the Animate.css library in the background so that 
    you can use them in the editor. So you are using jQuery to apply the Animate.css bounce class
    to your button elements.
   #You just used jQuery's .addClass() function, which allows you to add classes to elements.

3.Target Elements by Class Using jQuery
    -target your div elements with the class well by using the $(".well") selector.Then use 
     jQuery's .addClass() function to add the classes animated and shake.ie:
      $(".well").addClass("animated shake") 
    #

5.Target Elements by id Using jQuery
    -target your button element with the id target3 by using the $("#target3") selector.Then 
     use jQuery's .addClass() function to add the classes animated and fadeOut.ie:
     
       $("#target3").addClass("animated fadeOut");

    -Note that, just like with CSS declarations, you type a # before the id's name.

6.Delete Your jQuery Functions
    -These animations were cool at first, but now they're getting kind of distracting.Delete all three of
     these jQuery functions from your document ready function, but leave your document ready function itself
     intact.

7.Target the Same Element with Multiple jQuery Selectors.
    -Although it is possible to add multiple classes in a single .addClass() call, let's add them to the same
     element in three separate ways.Using .addClass(), add only one class at a time to the same element, three
     different ways:
      *Add the animated class to all elements with type button.ie;
          $("button").addclass("animated")
      
      *Add the shake class to all the butto  Add the btn-primary class to the button with id #target1
s with class .btn.ie:
          $("btn").addclass("shake")

      *Add the btn-primary class to the button with id #target1.ie:



8.Remove Classes from an Element with jQuery
    -remove the btn-default class from all of our button elements.ie
      $("button").removeClass("btn-default");

 9.Change the CSS of an Element Using jQuery
    -jQuery has a function called .css() that allows you to change the CSS of an element.
    -Delete your jQuery selectors, leaving an empty document ready function.Select target1 and change its color to red.ie
      $("#target1").css("color", "red");

10.Disable an Element Using jQuery
   -Disable only the target1 button.ie
      $("target1").prop("disabled", true);

   #When you disable a button, it will become grayed-out and can no longer be clicked.jQuery has a function called .
   prop() that allows you to adjust the properties of elements.

11.Change Text Inside an Element Using jQuery
  -Using jQuery, you can change the text between the start and end tags of an element. You can even change HTML markup.jQuery
  has a function called .html() that lets you add HTML tags and text within an element. Any content previously within the
  element will be completely replaced with the content you provide using this function.

  - rewrite and emphasize the text of our heading:ie
      $("h3").html("<em>jQuery Playground</em>"); 

   -Query also has a similar function called .text() that only alters text without adding tags.
   =Change the button with id target4 by emphasizing its text.ie
       $("#target4").html("<em>#target4</em>");

12.Remove an Element Using jQuery
  -jQuery has a function called .remove() that will remove an HTML element entirely
  -Remove the #target4 element from the page by using the .remove() function.ie.
      $(document).remove("#target4")   

13.Use appendTo to Move Elements with jQuery
  -Move your target2 element from your left-well to your right-well.ie'
    $("#target2").appendTo("#right-well");

14.Clone an Element Using jQuery
  -A function called clone() that makes a copy of an element.   
  -Clone your target5 element and append it to your left-well.ie;
     $("#target5").clone().appendTo("#left-well");

  #Notice this involves sticking two jQuery functions together? This is called function chaining and it's a 
  convenient way to get things done with jQuery.   

15.Target the Parent of an Element Using jQuery
  -jQuery has a function called parent() that allows you to access the parent of whichever element you've selected.
  -Give the parent of the #target1 element a background-color of red.

16.Target the Children of an Element Using jQuery
  -jQuery has a function called children() that allows you to access the children of whichever element you've selected.
  -Give all the children of your right-well element the color orange.ie;
      $("#right-well").children().css("color", "orange")

17.Target a Specific Child of an Element Using jQuery
  -The target:nth-child(n) CSS selector allows you to select all the nth elements with the target class or element type.
  -Make the second child in each of your well elements bounce. You must select the elements' children with the target class.ie;
      $(".target:nth-child(2)").addClass("animated bounce");   

18.Target Even Elements Using jQuery
  -You can also target elements based on their positions using :odd or :even selectors.
  -Select all the even target elements and giving them the classes of animated and shake.ie;
      $(".target:even").addClass("animated shake"); 

19.Use jQuery to Modify the Entire Page
  -jQuery can target the body element as well.
  -example:
     $("body").addClass("animated fadeOut");

       and;
    $("body").addClass("animated hinge");


           

        

           






