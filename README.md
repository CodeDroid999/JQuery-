### Learn jQuery, the most popular JavaScript tool of all time.

## Getting started:

## Get the Code

```
$ git clone https://github.com/CodeDroid999/JQuery.git
---

<ol>
<li>Clone the JQuery Playground Repository or<a href="https://github.com/CodeDroid999/JQuery-/archive/refs/heads/main.zip"> download zip file here</a></li>
<li>cd into the dirsctory and open the file with a text editor</li>
<li>Practice the following steps on the file</li>
</ol>


## Steps to add jquery to a HTML Document 

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


           



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/o_name">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">project_title</h3>

  <p align="center">
    project_description
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Report Bug</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `github_username`, `repo_name`, `twitter_handle`, `linkedin_username`, `email_client`, `email`, `project_title`, `project_description`

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![Vue][Vue.js]][Vue-url]
* [![Angular][Angular.io]][Angular-url]
* [![Svelte][Svelte.dev]][Svelte-url]
* [![Laravel][Laravel.com]][Laravel-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 

        

           






