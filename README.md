# Front-End-developer-Interview-Questions

- What is the difference difference between  ==  and  ===?

  === and !== are strict comparison operators.
  
  JavaScript has both strict and type-converting equality comparison. For strict equality the objects being compared must have the same type and
  two strings are strictly equal when they have the same sequence of characters, same length, and same characters in corresponding positions.

  Two numbers are strictly equal when they are numerically equal (have the same number value). NaN is not equal to anything, including NaN. Positive and negative zeros are equal to one another.
  Two Boolean operands are strictly equal if both are true or both are false.
  Two objects are strictly equal if they refer to the same Object.
  Using the triple equals, the values must be equal in type as well.
  
  Examples - 
  ```
  0 == false          // true

  0 === false         // false, because they are of a different type
  1 == "1"            // true, auto type coercion
  1 === "1"           // false, because they are of a different type
  null == undefined   // true
  null === undefined  // false
  '0' == false        // true
  '0' === false       // false
  ```
  Try this Fiddle - http://jsfiddle.net/vaibhavslab/jgsLa6eg/

  Reference - 
  
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators


- How to find find length of an object in JS?

  Reference -
  
  http://stackoverflow.com/questions/5223/length-of-javascript-object-ie-associative-array<br/>
  http://stackoverflow.com/questions/5533192/how-to-get-object-length<br/>
  http://css-tricks.com/snippets/javascript/get-object-size/<br/>
  http://jsperf.com/get-length-of-js-object


- Describe OOPS in Java Script.

  Reference -
  
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript<br/>
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Details_of_the_Object_Model<br/>
  http://www.sitepoint.com/javascript-inheritance/<br/>
  http://ejohn.org/apps/learn/#75<br/>
  http://help.adobe.com/en_US/Director/11.5/UsingScripting/WSc3ff6d0ea77859461172e0811d64c1a1b3-7fdb.html<br/>
  http://phrogz.net/JS/classes/OOPinJS.html<br/>
  http://www.javascriptkit.com/javatutors/oopjs.shtml


- What are Closures?

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/z44e3gbm/
  
  Reference -
  
  http://stackoverflow.com/questions/111102/how-do-javascript-closures-work/111111<br/>
  http://ejohn.org/apps/learn/#48

- What is W3C event model?

  Reference -
  
  http://www.quirksmode.org/js/events_order.html


- Differentiate between IE box model and W3C box model.

  Reference -
  
  http://programmers.stackexchange.com/questions/147587/the-box-model-internet-explorer-vs-w3c<br/>
  http://quirksmode.org/css/user-interface/boxsizing.html<br/>
  http://www.designedbyaturtle.co.uk/2012/traditional-box-model-vs-w3c-box-model/


- Describe scoping in Java Script.

  Reference -
  
  http://toddmotto.com/everything-you-wanted-to-know-about-javascript-scope/<br/>
  http://javascriptissexy.com/javascript-variable-scope-and-hoisting-explained/


- Explain Hoisting in Java Script.

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/t7t9rhnx/
  
  Reference -
  
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var<br/>
  http://code.tutsplus.com/tutorials/javascript-hoisting-explained--net-15092<br/>
  http://www.w3schools.com/js/js_hoisting.asp


- Differentiate between typeof and instanceof.

  Reference -
  
  http://bonsaiden.github.io/JavaScript-Garden/#types.typeof<br/>
  http://bonsaiden.github.io/JavaScript-Garden/#types.instanceof


- What is the advantage of using Sprites?

  Reference -
  
  http://stackoverflow.com/questions/1191961/what-are-the-advantages-of-using-css-sprites-in-web-applications<br/>
  http://www.dtelepathy.com/blog/graveyard/are-css-sprites-really-faster<br/>
  http://www.smashingmagazine.com/2010/03/26/css-sprites-useful-technique-or-potential-nuisance/<br/>
  http://css-tricks.com/css-sprites/


- What is the difference between live, delegate and on in jquery? 

  Reference - 
  
  http://www.elijahmanor.com/differences-between-jquery-bind-vs-live-vs-delegate-vs-on/<br/>
  http://stackoverflow.com/questions/2954932/difference-between-jquery-click-bind-live-delegate-trigger-and-on<br/>
  http://www.codeproject.com/Articles/662949/Differences-Among-Bind-Live-Delegate-Trigger-in-jQ<br/>
  http://www.alfajango.com/blog/the-difference-between-jquerys-bind-live-and-delegate/<br/>
  http://www.jquerybyexample.net/2010/08/bind-vs-live-vs-delegate-function.html<br/>
  http://code.tutsplus.com/tutorials/quick-tip-the-difference-between-live-and-delegate--net-9841


- What are self executing anonymous functions?

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/pyr4y3dm/
  
  Reference -
  
  http://markdalgleish.com/2011/03/self-executing-anonymous-functions/<br/>
  http://mahtonu.wordpress.com/2010/05/19/self-executing-functions-in-javascript/<br/>
  http://esbueno.noahstokes.com/post/77292606977/self-executing-anonymous-functions-or-how-to-write


- Differentiate between window.onload and onDocumentReady?

  Reference -
  
  http://www.codeproject.com/Tips/632672/JavaScripts-document-ready-vs-window-load


- Differentiate between call() and apply().

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/dck0v1ru/

  Reference -
  
  http://hangar.runway7.net/javascript/difference-call-apply<br/>
  http://designpepper.com/blog/drips/invoking-javascript-functions-with-call-and-apply<br/>
  http://pivotallabs.com/how-i-remember-the-difference-between-function-call-and-function-apply/
  

- What are callbacks and how can we implement them?

  Reference -
  
  http://recurial.com/programming/understanding-callback-functions-in-javascript/<br/>
  http://dreamerslab.com/blog/en/javascript-callbacks/


- What are various ways to optimize Java Script?

  Reference - 
  
  https://developers.google.com/speed/articles/javascript-dom<br/>
  http://blog.monitis.com/2011/05/15/30-tips-to-improve-javascript-performance/<br/>
  http://hungred.com/useful-information/jquery-optimization-tips-and-tricks/<br/>
  http://jonraasch.com/blog/10-advanced-jquery-performance-tuning-tips-from-paul-irish<br/>
  http://desalasworks.com/article/javascript-performance-techniques/<br/>
  https://developer.yahoo.com/performance/rules.html#min_dom<br/>
  http://oreilly.com/server-administration/excerpts/even-faster-websites/writing-efficient-javascript.html#the_switch_statement<br/>
  http://jonraasch.com/blog/10-javascript-performance-boosting-tips-from-nicholas-zakas<br/>
  http://www.smashingmagazine.com/2012/11/05/writing-fast-memory-efficient-javascript/<br/>
  http://ericleads.com/2013/04/youre-optimizing-the-wrong-things/

- Find the final colour of text.

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/vptrm9e3/


- How can we access nth child using jquery?

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/qn40pqos/


- How can we delete property of an object at runtime?

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/vxjcj1fo/

  Reference -
  
  http://perfectionkills.com/understanding-delete/<br/>
  http://stackoverflow.com/questions/208105/how-to-remove-a-property-from-a-javascript-object<br/>
  http://jsperf.com/delete-vs-undefined-vs-null/16


- What are the differences between GET and POST?

- List a few $.ajax options.

- What are different types defined in Java Script. What is the difference between null and undefined?

- Find the output.
  ```
      function func(x){
          console.log(x);
      }

      func(y=12);
  ```

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/ee0oywhq/


- Find the missing number in array.

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/32ww7rhd/
  
  Reference -
  
  http://www.geeksforgeeks.org/find-the-missing-number/

- Describe Templating in Java Script.

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/9L7vpkhd/


- Print the following star sequence using Java Script.
  ```
      *
      **
      ***
  ```

  Try this Fiddle - http://jsfiddle.net/vaibhavslab/qdxw4afu/


- Describe new tags in HTML5.
  
  - New Semantic Elements: These are like \<header>, \<footer>, and \<section>.
  - Forms 2.0: Improvements to HTML web forms where new attributes have been introduced for <input> tag.
  - Persistent Local Storage: To achieve without resorting to third-party plugins.
  - WebSocket: A a next-generation bidirectional communication technology for web applications.
  - Server-Sent Events: HTML5 introduces events which flow from web server to the web browsers and they are called Server-Sent Events (SSE).
  - Canvas: This supports a two-dimensional drawing surface that you can program with JavaScript.
  - Audio & Video: You can embed audio or video on your web pages without resorting to third-party plugins.
  - Geolocation: Now visitors can choose to share their physical location with your web application.
  - Microdata: This lets you create your own vocabularies beyond HTML5 and extend your web pages with custom semantics.
  - Drag and drop: Drag and drop the items from one location to another location on a the same webpage.
  
  Reference -
  
  https://rawgit.com/whatwg/html-differences/master/Overview.html#new-elements<br/>
  https://developer.mozilla.org/en/docs/Web/Guide/HTML/HTML5/HTML5_element_list<br/>
  http://www.html-5-tutorial.com/all-html-tags.htm<br/>
  http://www.tutorialspoint.com/html5/html5_new_tags.htm<br/>
  http://www.webmonkey.com/2010/02/building_web_pages_with_html_5/<br/>
  http://html5doctor.com/element-index/


- Describe \<header> and \<footer>. Can we use these tags interchangeably? Can there be multiple \<header> and \<footer> tags? 

  Reference -
  
  http://www.w3schools.com/html/html5_semantic_elements.asp<br/>
  http://html5doctor.com/the-header-element/<br/>
  http://stackoverflow.com/questions/4837269/html5-using-header-or-footer-tag-twice<br/>
  http://www.quackit.com/html_5/tags/html_footer_tag.cfm<br/>
  

- Differentiate between LocalStorage and Cookies.

  Reference -
  
  http://www.html5rocks.com/en/features/storage<br/>
  http://www.sitepoint.com/html5-web-storage/<br/>
  https://developer.mozilla.org/en/docs/Web/Guide/API/DOM/Storage

- Describe DOCTYPE.

  The <!DOCTYPE> declaration is not an HTML tag; it is an instruction to the web browser about what version of HTML the page is written in. When omitted, browsers tend to use a different rendering mode that is incompatible with some specifications. Doctypes are simply a way to tell the browser—or any other parsers—what type of document they’re looking at. In the case of HTML files, they refer to the specific version and flavor of HTML. Including the DOCTYPE in a document ensures that the browser makes a best-effort attempt at following the relevant specifications.
  
  Reference -
  
  http://www.cssnewbie.com/standards-vs-quirks-mode/#.U_xkq1ehias<br/>
  http://www.motive.co.nz/glossary/quirks-mode.php<br/>
  http://reference.sitepoint.com/css/doctypesniffing<br/>
  https://www.cs.tut.fi/~jkorpela/quirks-mode.html<br/>
  http://www.w3.org/QA/Tips/Doctype<br/>
  http://www.htmlbasictutor.ca/doctype-declaration.htm<br/>
  http://ejohn.org/blog/html5-doctype/<br/>
  http://webdesign.about.com/od/dtds/qt/tipdoctype.htm<br/>
  http://www.w3schools.com/tags/tag_doctype.asp<br/>
  https://hsivonen.fi/doctype/<br/>
  http://www.w3.org/wiki/Doctypes_and_markup_styles<br/>
  http://www.quirksmode.org/css/quirksmode.html


- What will be the output of following statements?
  ```
      var object1 = { same: 'same' };
      var object2 = { same: 'same' };
      console.log(object1 === object2);
  ```
  
  Logs false. JavaScript does not care that they are identical and of the same object type.When comparing complex objects, they are equal only when they reference the same object (i.e., have the same address). Two variables containing identical objects are not equal to each other since they do not actually point at the same object.
  Objects are sometimes called reference types to distinguish them from JavaScript’s primitive types. Using this terminology, object values are references, and we say that objects are compared by reference: two object values are the same if and only if they refer to the same underlying object. As you can see from the code above, assigning an object (or array) to a variable simply assigns the reference: it does not create a new copy of the object. If you want to make a new copy of an object or array, you must explicitly copy the properties of the object or the elements of the array. This example demonstrates using a for loop:
  ```
  var a = ['a','b','c'];              // An array we want to copy
  var b = [];                         // A distinct array we'll copy into
  for(var i = 0; i < a.length; i++) { // For each index of a[]
      b[i] = a[i];                    // Copy an element of a into b
  }
  ```
  Try this Fiddle - http://jsfiddle.net/vaibhavslab/z1nex81x/

  Reference -
  
  http://snook.ca/archives/javascript/javascript_pass/


- What will be the output? 
  ```
     4 + "1"
     4 - "1"
  ```
  Try this Fiddle - http://jsfiddle.net/vaibhavslab/bmqroLzw/


- What is the difference between global variable defined using var and implied global variable?

  There’s one slight difference between implied globals and explicitly defined ones—the difference is in the ability to undefine these variables using the delete operator:
  - Globals created with var (those created in the program outside of any function) cannot be deleted.
  - Implied globals created without var (regardless if created inside functions) can be deleted.
  This shows that implied globals are technically not real variables, but they are properties of the global object. Properties can be deleted with the delete operator whereas variables cannot.


