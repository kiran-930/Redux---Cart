
                                MERAN STACK TOPICS COVERED IN CLASS
                            --------------------------------------------
    
    -----------------------------------------
        HTML - HyperText Markup Languauge
    -----------------------------------------

    1. Display contents in webpage
    2. HTML 5 Structure
    3. HTML Elements : <starting-tag>COntent</ending-tag>
    4. Basic Tags
        - Headings : h1 - h6 Tags
        - Paragraph : p tag
        - bold : b tag
        - Italics :  em tag
        - Highlight content : mark tag
        - Strike content : s tag
        - Superlative : sup tag
        - Subscript : sub tag
        - anchor / link tag : a tag
        - list 
            - ordered list - ol tag
            - unordered list - ul tag
            - list item - li tag
        - table ( display contenet row and column) : table tag
            - thead : table head
            - tbody : table body
            - tr tag : row
            - th / td tag : column
        - image : img tag
        - video tag
        - iframe tag
        - hr tag
        - Container Tags
            - div tag
        - Forms : form tag - used to hold all inputed data 
            - input tag : used to input user data (date,DateTime,time,email,tel,color,range,number,url)
            - button tag
            - check box : use input tag type : check
            - radio button : use input tag type: radio
            - lable tag : dispaly text content in form tag
            - drop down list : use select 
            - file : use input tag , type:file
    5. Classify HTML elements based on its display
        - Block Elements : display using entire width of a line in browser
        - Inline elements : display contents in same line with other items
    6. Semantic Tags
        - header tag
        - section tag
            - div tag
        - aside tag
        - footer tag


    
    ------------------------------------
        CSS - Cascading Style Sheet
    ------------------------------------

    1. Used style html elements
    2. DIfferent ways to apply CSS in HTML elements
        - Inline CSS : use style attribute
            - syntax : style="css-property:value;"
        - Internal CSS : use style tag 
            - syntax : <style> css-selectors{ css-property:value; } </style>
        - External CSS : apply style via External css file
            - syntax : <style> css-selectors{ css-property:value; } </style>
            - use link tag inside head tag : to link External css file with html page 
    3. CSS Selectors : used to select html elements into css 
        - use tag name
        - use id
        - use class
        - Universal Selector tag
        - Grouping selectors
        - CSS Combinators 
            - Descendant Selector : using space
            - Child Selector : using >
            - Sibling Selector : using ~
            - Immeadiate Sibling Selector : using +
    4. Box Model 
        - Margin : space between border and browser
        - Padding : space between border and content
    5. CSS Property
        - float : float the html elements
        - position : manage positoin of html elements
            - static : default position
            - fixed : 
            - relative
            - absolute
            - sticky
        - flex : To arrange html elements in row and column wise
            - flex-container : style conatiner to get flex, display : flex
            - flex items
            - justify-content : spacing horizontally
            - align-items : spacing vertically
            - flex-wrap
            - flex-grow
            - flex-shrink
        - grid :
        - z-index
        - transition
        - transform
        - Pseudoclass in css
            - syntax : selectors:pseudo-class{property: value;}        
        - Animation 
            - Keyframes
        - 
    6. Media Queries : used to build responsive website
        - syntax:
        @media not|only mediatype and (media feature) and (media feature) {
            CSS-Code;
            }
  

    ------------------------------------
        Bootstrap - Framework for CSS
    -------------------------------------

    1. Build fast, responsive sites
    2. Commonly used classes for styling
        - container
        - container-fluid
        - m/mt/mb/ms/me-1/2/3/4/5 
        - border 
        - p/pt/pb/ps/pe-1/2/3/4/5 
        - color : primary/danger/success/warning/dark/light/secondary/info
        - img-fluid / img-thumbnail
        - w-25/50/75/100
        - text-center
        - text-color
        - bg-color
        - fs-1/2/3/4/5
        - btn btn-color 
        - d-flex justify-content-evenly align-items-center flex-row
           
           
    -----------------------------------------------       
        JAVASCRIPT - Programming Concepts
    -----------------------------------------------

    1. Node JS - provide runtime environment and js library 
    2. Basic Concepts in JS
        - Display content : console.log(content)
        - Data Types in JS : use typeof
            - string
            - number
            - boolean
            - object
        - Identifiers : set of rules for set up name for a variable
        - Variable : use to store data
            - Using var keyword :
                syntax : var variableName / var variable_name = value
            - Using const keyword :
                syntax : const variable_name = value
            - Using let keyword
                syntax : let variable_name = value
        - Hoisting in JS : using a data before creating it
        - Differece between type of variable
        --------var-----------          ------const---------------      ---------let-------------
        - use var keyword               use const keyword               use let keyword
        - can reassigned its value      cannot reassign its value       can reassign its value
        - Global scope                  Block scope                     Block scope
        - Hoisted with undefined        Hoisted without a value         Hoisted without a value
        - Joining different type of datas in js
            - using commas
            - using + operator ( concantenation )
            - using ` (template literals)
        - Operators in JS
            - Assignment Operators : variable_name = value
            - Arithmentic Operators : + - * / % **
            - Relational Operators : > >= < <= == != === 
            - Logical Operators : && || !
                -------AND------ -------OR------- -----NOT--------
                    T && T = T      T || T = T      !T = F
                    T && F = F      T || F = T      !F = T
                    F && T = F      F || T = T 
                    F && F = F      F || F = F 
            - Increment / Decrement Operators : ++ --
            - Short hand Operators : += -= 
            - Ternary Operators : condition?Statements when condition become true:Statements when condition become false
            - Truthy operator : condition && Statements when condition become true
            - Spread operator ... : used to expand an iterating variable to a single iterating variable
            - Rest operator ... : used to combine rest of the data to a single array
        - Conditional Statements
            - if Statements :
                syntax : if(condition){ if body: executes when condition satisfy }
            - if-else Statements :
                syntax : if(condition){ if body: executes when condition satisfy }else { executes when condition false }
            - else-if ladders
            - Switch cases
        - Looping Statements : Repeating same task multiple times
            - while loop 
                syntax : 
                    1. Initialise a variable with a value
                    2. while(condition should includes that Initialised variable){
                        while body executes when condition become true
                    3. Change the value of variable that used in the condition
                    }
            - for loop
                syntax : for(Initialise a variable with a value;condition should includes that Initialised variable;Change the value of variable that used in the condition){
                    for body executes when condition become true
                }
                - break Statements 
                - continue Statements
            - nested loop : A loop inside another loop
        - Function : used to perform specific task during the code
            - 2 parts
                - Function Definition : defining the task to be performed
                    syntax : function function-name(parameters used to perform task){
                        defining task in function body
                    }
                - Function  Call : to execute a function
                    syntax : function-name(arguments to be passed to the function Definition)
            - return Statements : return data from function Definition to function Call
            - Types of function
                - Arrow function : alternative for function definition, function-name = (parameters used to perform task)=>{ defining task in function body }
                - Predefined function : console.log(), Math.floor()
                - Callback function : A function definition inside another function call, completes its executin only after completion of the function inside it
                - Anonymous function : Self executing function , nameless function
                - Nested function : A function definition inside another function definition
                - Closure property : 
                - Recursive function : Calling a function inside its own definition
        - Array : used to hold multiple values in a single variable
            - to access each value from an array use its index , array-name[index-number]
            - Total count of items in array : length 
            - type of array : object
            - To access array items one by one
                - using normal for loop
                - using for - of loop : for(let variable-name of array-name){} return array items
                - using for - in loop : for(let variable-name in array-name){} return array index
            - Methods : array-name.method()
                - push(item) : used to insert data at end of an existing array
                - unshift(item) : used to insert data at first of an existing array
                - pop() : used to remove data at end of an existing array
                - shift() : used to remove data at first of an existing array
                - sort(compareFn) : used to sort array
                    - compareFn : (num1,num2)=>num1-num2 (ascending sort)
                                : (num1,num2)=>num2-num1 (descending sort)
                - forEach(callbackfn:(value,index,array)=>void) : Alternative to for-of loop
                - filter(callbackfn) : return a new array with items satisfying the condition from an existing array
                - find(callbackfn) :  return an items satisfying the condition from an existing array
                - map(callbackfn) : return a new array with values after applying a mapping function to existing array
                - reduce(callbackfn) : return a single value which is either smallest/largest/total sum from an existing array after applying reduce function
                - reduceRight(callbackfn) : return a single value (either smallest/largest) which is the first item  from an existing array after applying reduce function
                - some(callbackfn) : return true / false based on a condition applied to all items in given array
                - flat(depth) : return array with corresponding depth as dimension, to convert to 1 dimension use depth as 'Infinity'
                - includes(key) : return boolean based on the key present in the given array 
                - indexOf(item) : return index number corresponding to the 
                - splice(startingIndex, delete count) : used to delete items from an array and return array with removed item
                - join(seperator) : return a string with array value separated using the given seperator
        - String : 
            - Methods
                - substring() : Returns the substring at the specified location within a String object
                - toLowerCase()
                - toUpperCase()
                - startsWith()
                - endsWith()
                - trim()
                - includes()
                - split()
                - slice()
            - eval(string-expression) : used evaluate an expression as a string
        - Object : Data storing as a {key:value} pair
            - use key  : To access value from an object
                syntax : object-name['key'] / object-name.key
            - using in operator we can check a key is in object, return a boolean
                syntax : "key" in object-name
            - Insert value to an exsiting object
                object-name["key"] = value / object-name.key = value
            - Object.values(object-name) : return an array of value of the given object
            - Object.keys(object-name) : return an array of keys of the given object
            - Object.assign(target-object,source) : used to insert data in an existing target obejct
            - Methods
                - hasOwnProperty(key) : we can check a key is in object, return a boolean
        - Access Specifiers : used to specify the access of a variable / function
            - public
            - private
            - protected
        - Object Oriented Programming (OOPs)
            - Object : real time entity
            - Class : Blueprint of object
            - Reference : used to refer property to its class
            - constructor() : method used to initialise class property
            - Features of OOPs
                - Inheritance : used to get data from one class to another
                    - Classical Inheritance : use extends keyword
                    - Prototype Inheritance : use __proto__
                - Polymorphism : to implement Polymorphism in js use REST operator (...)
                - Abstraction : hiding the important Data from user 
                - Encapsulation : Data inside another data like class
        - Try-Catch-finally Block  : used to handle runtime error
    ------------------------------------------
        JAVASCRIPT - Front end Concepts
    ------------------------------------------  

    - Used to provide behavior to Web page
    - Ways to applying JS in HTML
        - Internal JS : use 'script tag' to provide js code in HTML
        - External JS : link External js file with HTML using script tag
    - DOM : Document object Model for a web page
        - A tree structure corresponding to a webpage , there will be a single root/node (html tag) which is made of js object
        - js can access webpage / HTML elements via DOM using 'document' object
    - DOM Methods : Selecting HTML elements to js code 
        - using tag name : document.getElementsByTagName('tag-name')
        - using class name : document.getElementsByClassName('class-name')
        - using id : document.getElementsById('id-name')
        - Using querySelector : document.querySelector('tag/#id/.class-name')
        - Using querySelectorAll : document.querySelectorAll('tag/#id/.class-name')
    - Event : triggered by user actions 
        - Mouse Related Events : click, move, drag ...
        - Keyboaord Related Events : keypressdown, keyup ....
        - Text based Events
    - Access / Update content of a tag
        - innerHTML 
        - innerText
    - Permanent Data storage in Browser
        - Using Local Storage
        - Using Session Storage
        - Methods : Both key and value must be string type
            - setItem(key,value) : Used to store data in local /Session storage
            - getItem(key) : Used to get data from local /Session storage
            - removeItem(key) : Used to delete data from local /Session storage
    - API : Application Programming Interface - used to communicate Application in internet
        - URL : Uniform Resource Locator 
            ex: https://jsonplaceholder.typicode.com/users/1
            baseURL : https://jsonplaceholder.typicode.com/
        - URI : Uniform Resource Identifier : ex: users
        - Path Parameter : ex : 1
        - Query Parameter : values followed with ?  in url
            ex: https://in.search.yahoo.com/search?fr=mcafee&type=E211IN1274G0&p=jsplaceholder
        - Body Parameter : 
        - Types of API Architectural
            - REST API : HTTP, JSON 
            - SOAP API : HTTP, XML
            - GRAPHL
    - JSON : JAVASCRIPT Object Notation
        - {"key" : value}
    - HTTP (Hyper Text Transfer Protocol)
        - HTTP Requests
            - GET (to get a data from server to client)
            - POST (to store/add data to server from client)
            - PUT (to edit/update existing data to server from client)
            - DELETE (to remove a data from server)
        - HTTP Response Codes : to identify the status of client request by browser
            - 1xx : Informational
            - 2xx : Success
            - 3xx : Redirection
            - 4xx : Client error
            - 5xx : Server error
    - Resolving Function Call  in JS
        - Synchronus Function : execute function without delay
        - Asynchrous function : execute function with a delay
        - JS Use a single Call Stack (Single Threaded Programming Language) to monitor it use event loop
            - Types of Asynchrous function
                - Callback hold in callback queue
                - API call hold in Microtask queue (priority queue)
            - Resolving Asynchrous functions
                - if we use callback to resolve Asynchrous function it may lead 'Callback Hell : Nesting of callback function' scenario
                - Promise : aviod callback hell
                    - Has 2 states
                        - Resolved state : use 'then' method to get the Response
                        - Reject state : use 'catch' method to get the reason to fail the function call
                        - Pending state : waiting duration to get response for Asynchrous function call
                    - Async-Await keyword : To resolve promise 
                        - 'async' keyword is used in to function to indicate its Asynchrous
                        - use 'await' keyword in-front of async function call, to wait till its completion
                        - only resolved state will get after await to completes the asyc function call
                        - to get reject state use try-catch block 
    - API Call Using JS 
        - using XMLHTTPRequest : AJAX (Asynchrous JS & XML)
        - fetch() : returns promise
        - axios library : return promise

    ------------------------------------------------
        REACT - ADVANCED Front end TECHNOLOGY
    -------------------------------------------------

    - Basic Concepts 
        - React App is a Collection of different Library 
        - React App is a Collection of Components 
            - Components are arranged in a tree structure
            - There will be a root Component in React app which is commonly known as 'App' 
        - React used to create Single Page Application
        - Pure functions : which doesnot cause side effects, used to create react functional compoenent, 
        - Declarative Approach 
        - *Virtual DOM : Light weight memory representation of real DOM
            - Reconciliation 
        - *JSX (JAVASCRIPT XML) : (Language used to write code in React) - used to display content in browser 
            - ex: JSX Elements :  const heading = <h1>Heading 1</h1>
            - Rules for Using JSX 
                - Every JSX elements must be inside a single parent tag
                - Parent Tag can be any container tag /  react fragment ( <>...</> )
                - Every tag must has a closing tag. ex: <h1>heading</h1> , <br/> (self closing tags)
                - JSX using camel case
                - Instead of Attribute 'class' use 'className' in JSX
                - Instead of Attribute 'for' use 'htmlFor' in JSX
                - use { js-expression } : To provide js expression in JSX
        - React App Creation
            - CRA (using create-react-app commanad)
            - Vite : build tool for web projects
                - Installing vite Globally : npm i -g create-vite
                - React app using vite : npm create vite@latest react-app -- --template react
        - React App File & Folder structure
            - package.json file : npm configuaration file for the project
            - package-lock.json file : contains version history all packages installed in the project
            - .gitignore file : contains files/folder name which is ignored while adding to git
            - index.html file : entry page to react app 
            - node-modules folder : used to hold copies of dependent libraries of react project (we can install using command : npm install)
            - public folder : react project can access data stored in public folder as Globally 
            - src folder : define react app here
                - assets folder : used to hold media files used in react app
                - main.jsx file : create ReactDOM with parent node as div with id as 'root', and render the  parent (App) Component inside the node
            - to run react app : use command 'npm run dev'
            - Babel library : transpile JSX code to simple react function which is understood by Browser
        - *High Performance
        - *Data Binding / Shairing : One way Data binding (from parent to child)
        - *Components : Part of User Interface, independent and reusable code
            - General Rules for Creating components
                - create a js / jsx file, file name must starts with capital letter
            - Different Types compenents
                - Class Based Compoenets : use 'class' to create compoenent it cam inherit react component class
                    - Statefull Component , because it can create state 
                - Functional Based Componets : use 'function' to create compoenent, return jsx code 
                    - Stateless componenet : it cannot create state
            - Life cycle methods of React Component
                - Mounting Phase : Putting JSX to DOM
                    - constructor()
                    - getDerivedStateFromProps()
                    - render()
                    - componentDidMount()
                - Updating Phase : When component is updating
                    - getDerivedStateFromProps()
                    - shouldComponentUpdate()
                    - render()
                    - getSnapshotBeforeUpdate()
                    - componentDidUpdate()
                - Unmounting Phase : Removing component from DOM
                    - componentWillUnmount()
        - Difference between functional and class based compoenent
        -------------------------------------------------------------------------------------------------
                Functional Component                        Class Compoenent
        -------------------------------------------------------------------------------------------------
            1.  JS Pure function to accept props        1. Is class extended from react compoenent
            and return JSX Element                          it render function return JSX Element 
            2. It executes from top to bottom, once     2. Compoent alive depending on different life
            it return JSX, then it cannot be alive          cycle
            3. Stateless component                      3. Statefull component
            4. Hooks are used                           4. Hooks are not used
            5. Life cycle method is not available       5. Can use life cycle method in component
            6. No need render function                  6. It requires render to return JSX
            7. No need of constructor                   7. Constructor used to initialise state

        - Props Object : Property of a component, Using props a component can get the shared data from its parent, props will be get as an 'argument' of functional component 
        - Styling JSX Elements in React Component - using CSS
            - Using Inline CSS : using style attribute
                - syntax : style={{property:value}}
            - Using External CSS : using external css file, import css file to compeonent file
            - CSS Module file : file with extension as .module.css is known as CSS Module file, import module filein compoenet
        - React Events Binding
            - Binding a function without argument : event={function-name}
            - Binding a function with argument : event={()=>function-name(arg)}
            - Binding a function with argument as event : event={(e)=>function-name(e)}
        - Conditional Rendering : Based on a condition we can control the jsx element in browser
            - if statement : use opertaor &&
            - if - else statements : use operator ?:
        - React State : Is an object used to store data / information regarding a compoenent, whenever state changes, the component re-renders
            - use setState(value) : to update state 
        - React Hooks : Is a predefined functions used to provide react component features to functional component
            - Hooks are function with function name starts with 'use' keyword
            - to use a hook in functional component, we must call the hook
            - Rule for calling hooks in functional component
                - Import hook from react, in component
                - Hooks can called at the top level of a component
                - Hooks cannot be conditional
            - Types of Hooks
                - Predefined Hooks
                    - useState(initial-value) : to help functionanl component to create state
                    syntax : const [state-name,state updating function name] = useState(initial-value)
                    - useEffect(function, dependency) : used to provide side effects to your component
                        - function : used define side effects applied to compoent
                        - dependency : based on dependency, useEffect will get called, side effect will applied to the component
                            - no dependency : useEffect hook will call all time in compoenet
                            - [] : useEffect hook will call only at the time in compoenet creation
                            - [data] : useEffect hook will call  at the time in compoenet creation as well as data changes
                    - useParams() : Returns an object of key/value pairs of the dynamic params from the current URL that were matched by the route path
                - Customised Hook : 
                    - Create a function with name starts with 'use' keyword
        - Handling List/Array using React
            - using 'map' method
            - to uniquely identify each item in a list use 'key' attribute in component
        - Styling Frameworks in REACT                
            - Material UI : npm install @mui/material @emotion/react @emotion/styled
            - React Bootstrap : npm install react-bootstrap bootstrap , we have to add bootstrap theme to properly work bootstrap, bootswatch.com will provide the theme, choose a theme and download its bootstrap.min.css file into project src folder, import bootstrap.min.css into main.jsx file
        - React Forms
            - Controlled Components : data changes in the form is handled by the compoenet by storing its state using change event
            - Uncontrolled Components : form handled by real DOM
            - To submit form, to prevent it from reloading use preventDefault() method compoenet    
        - Set up path for Compoenet in React
            - install react-router-dom :   npm i react-router-dom  
            - React app must render inside 'BrowserRouter' component
            - Compoenets needs to set up path must inside 'Routes' COmpoenent of react router dom in App.jsx
            - using Route compoenet define each compoenet path 
            - Link compoenet used to redirect from one page to another within the app
        - Higher Order Component (HOC) : A compoenet is argument / props to another compoenet
        - react-toastify : Library for notification in react - npm i react-toastify
        - API Call in React
            - Axios library : npm i axios
            - Create folder for services
        - To create the build for production of your react app use command : npm run build


        ----------------------------------------
                JSON SERVER
        ----------------------------------------
        1. Create a folder to hold json file
        2. Create package.json file inside the folder : npm init -y
        3. Create db.json file inside the folder and resources as key to the json file
        4. To run json file install json-server : npm i json-server / npm i json-server@0.17.4
        5. To run json file in localhost use : npx json-server db.json / node index.js
        -------------------------------------------------
              Deploying A  JSON FILE  using NODE JS
        -------------------------------------------------
        1. Create index.js file server folder
        2. update script in package.json file as "start":"node index.js"
        3. create .gitignore file and add 'node_modules' folder
        4. Define json-server to run json file in index.js
            - import json-server
            - create server run json file using create() method of jsonServer
            - create middleware used by JSON Server.
            - set up route for json file in server
            - use middleware, route in server app
            - listen the app in given port to resolve client request
        5. To run the app, use 'node index.js'

        ------------------------------------------------------
                REDUX - STATE MANAGEMENT TOOL
        ------------------------------------------------------
        1. To avoid 'props drilling' and its manage state in a react app
        2. Libraries needs to implement redux
            - React-Redux : Official React bindings for Redux
            - Redux Toolkit : toolset for efficient Redux development
            - install libraries : npm install @reduxjs/toolkit react-redux
        3. REDUX Features
            - Store : using 'configureStore()' to create redux store, use 'Provider' component to make the store available for the react app
            - Action : define logic to update state
            - Reducer : used to hold updated state to store
            - createSlice() - used to combine action and reducer together, it reurns actions and reducer, to create slice we have to pass configuration with following data : name, initial state, reducers where we will define action to update the state
                - when compoenet dispatch action with argument to update the state with argument then action function will get from its 'payload'
            - Redux DevTools Extension : used for debugging application's state changes.
            - useSelector hook : use state from store to component, syntax : useSelector(state=>state.reducer-name)
            - useDispatch hook : used to execute the action from componenet
            - createAsyncThunk() : A function that accepts a Redux action type string and a callback function that should return a promise.
                - returns a standard Redux thunk action creator, pending, fulfilled, and rejected cases
                - its output returns extraReducer, where we can add cases using builder class


