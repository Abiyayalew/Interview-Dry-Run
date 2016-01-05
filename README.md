#  Interview Dry-Run

### Question 1
**What is the most influential book or blog post you’ve read regarding web development?**

My most influential book I have read regarding front-end web development is Learning Web Design: by Jennifer Niederst Robbins. It introduce me basic beginners level knowledge for web development using HTML,CSS and JavaScript’s, and I developed my first websites using this tools. This definitely inspired me to learn more about emerging front-end web technologies.

Since then I have started explore different tools and study formal front-end web development program from Udacity. 


### Question 2
**If you could master one technology this year, what would it be and why?**

There was one question always came in mind, how could i debagging websites like I have done in  java or C#, for me it was very hard to trace JavaScripts .Chrome dev tools right solution for my question.

Dev tools are set of web debugging tools built in google chrome. Which provide web developer deep access into web application.

What interest me to knew about Dev tools was it has capable of track down layout issues, set JavaScript breakpoints, get insights for code optimization and it has console that help us debug web page as well as interact with document.

### Question 3
 **Describe any front-end web application framework (preferably one that you use). How does it work? What are the upsides and downsides?**

Bootstrap framework is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web. Bootstrap easily and efficiently scales your websites and applications with a single code base, from phones to tablets to desktops with CSS media queries.

Upsides of  bootstrap is  easy to get started,  has great grid system,  has styling for most HTML elements such as Typography, tables, form and image and it has bundled JavaScript plugins for navigation bar, dropdown menu etc.

Downsides of Bootstraps lead to a lack of understanding the underlying css because you learn only framework not language. Bootstrap is built with LESS and doesn’t provide native support SASS. And has limited JavaScript’s component.


### Question 4
**Write a function that takes only one argument——another function——and returns a "memoized" version of that function. A "memoized" version of a function caches and returns the results of its call so that when it is called again with the same input, it doesn’t run its computation but instead returns the results from cache. Note that previous results should be retrievable in any order without re-computation.**

    function memoize() {
       var meno = {};
       return function(x) {
         var value;
         if (x in meno) {
            value = meno[x];
         } else {
            value = x + 5;
            meno[x] = value;
         }
         console.log(value);
       }
    }
    var memoizedFoo = memoize();
    memoizedFoo(12);
    memoizedFoo(8);
    memoizedFoo(10);
    memoizedFoo(12);
    

### Question 5
**Create a simple webpage that has a cow image in the middle (centered horizontally on the page) and a counter label below it. Add the necessary code so that every time you click the cow image, the counter is incremented by 1. The counter should start with a value of 0.**
 
     <!DOCTYPE html>
     <html>
     <head>
       <title>Caw clicker</title>

       <!-- Align the image center -->
       <style type="text/css">
         #cow-clicker {
            text-align: center;
         }
       </style>

    </head>
    <body>

      <div id="cow-clicker">
          <img src="Cow_cartoon_04.svg" alt="cartoon-cow" onclick="updateCounter()">
          <div id=counted></div>
      </div>

      <script type="text/javascript">
    
         //varible used to hold the number of clicks.
           var count = 0;
        
         //Function used to update counter.
         //The user click the image counter will increase  by one and display on screen.
         function updateCounter() {
            count++;
            document.getElementById("counted").innerHTML = "This has been clicked " + count +"times.";
         }
      </script>
    </body>
    </html>

### Question 6
**If you were to start your front-end position today, what would be your goals a year from now?  [Front-end web developer](https://sandiego.craigslist.org/csd/web/5387587845.html)**

My goal is to have deep understanding of tools we are going to used for development of front end web development. I would to be integral part of my team and forefront for implementation of new technologies. I would like to share my knowledge and   start study to become full stack web developer.
