# Designing webpages with CSS

### What is CSS?
* CSS (Cascading Style Sheets) allows you to create great-looking web pages! 
* CSS can be used for basic document text styling, such as - changing the text size or color of headings and links.
* CSS is a ruled based language, you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

### How do you use CSS for your website?
* There are 3 different ways to add CSS to your webpage:
 * External CSS - You can create a separate file and link it to your main HTML file.
      * One way to do this is to use the ***touch*** command in the console to add a new .css file to your local repository.
        
          ``` touch example.css ```
  * Internal CSS - You can use a style tag within the header of your HTML file, and place the rules in there.
        * Example:
        
             <style>
                     h1 {
                        text-align: center;
                        color: white;
                    }
                    
                     h3 {
                        text-align: right;
                        color:white;
                    }
             </style> 
  * Inline CSS - You can place your CSS rules within the same line as your body contents.
        * Example:
        
             <h3 style="padding-right: 500px;">Pros of Desktop Gaming</h3>
         
             <p style="color:red;">This is a paragraph.</p> 
