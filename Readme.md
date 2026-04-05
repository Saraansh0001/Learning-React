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

// <> </>these are fragment which help us group thing together without nay extra div , only in react

// <div>
//   <input />
//   <button>Send</button>
// </div>
// due to this , we have extra divs in out=r website , lets now study how we can remove thies divs  and the code simpler


//props goes as input in a function in react and we can use it to pass data from one component to another component

// function ChatMessages(props){

// const message = props.message;
// const {sender} = props;

// const {message,sender} = props; 

// this is called destructuring/deconstructing in js and it is used to extract values from an object and assign them to variables with the same name as the keys in the object

// if (sender === "robot"){
//   return(
//   <div>
//     <img src="robot.png" alt="User"  width="50" />
//     {message}
//   </div>
// );
// // }

//shortcut for if statement in react , if sender is robot then only the image will be rendered otherwise it will not be rendered

// <img src="user.png" alt="User"  width="50" />

// the message attribute is the prop which we are passing to the chatmessage component and we can use it in the chatmessage component as props.message

in react while displaying msg , the compenent requires id which is uniqe and is used to identify it

state = data that is connected to html

 // ...arrayName spread operator to copy the array messages & add new message to existing messages

    react uses calss name to set class as class is itself a reserved keyword in js