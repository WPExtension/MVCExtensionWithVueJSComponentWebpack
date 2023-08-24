# MVCExtensionWithVueJSComponentWebpack
MVCExtension + VueJS and Component + Webpack fully optimized for production application

Installing Webpack

 *Step 1
 npm install webpack webpack-cli --save-dev
 
 *Step 2
 import and export function from js file
 - func.js

   /* <!-- this is inside the func.js file --> */ 
   - function funcName() { console.log( This is the function exported ); }
   - export default funcName;
   /* <!-- this is inside the func.js file --> */  
  
  *Step 3 export function to main js app
 - main.js (This where you can use all JS exported function)

   /* <!-- this is inside the main.js file --> */ 
   - import funcNameAlias from './func.js'
   - /* the function available to use now ! */ 
     funcName();
   /* <!-- this is inside the main.js file --> */ 
   
   
   
