React is bascially an ext lib used to create website easily

 
    we're using superSimpledev url as the version of react might chaneg and in roder to omplete tehcourse , we need the same version
    
    THERE are 2 lib for react , the react is the mobile and weeb combine while the dom is ewb specifc lib, so we need both to make it work in the web page

ReactDOM.createRoot sets up react
.render is used to display the text or whatever

    babel is another ext lib , aka js compiler , as react is written in jsx JavaScript Xml 
    Browser doenst understand jsx, so we need babel to compile it to regular js

<script type="text/babel"> this tag tells babel to traslate jsx into normal js

    we cant render multiple vars using render ,and we cant store multiple tags into 1 variable , for this we use div element

how it makes it easierr ???? 
1. no dom needed ( more natural )
2. unmatchig tags get noticed automatially + i ahve vs code extension so no rpoblrm at all
3. we can inserted js code directly into jsx

    compenent is just a peice of a website
    syntax :- 
        function ChatInput(){
            // name should start from a captial letter
            return();
        }

        <chatInput></ChatInput> // this is a compenent

    this is the main idea of react, we can create our own tags and use them as components
    in react , everything needs a closing tag , no matter what 

we can return only 1 value , so we need a div everytime as a parent element