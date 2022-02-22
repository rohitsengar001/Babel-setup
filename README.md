# Babel-setup
> Sample Project For setting up Babel in Javascript project
>Pre-Requistive
>
> >**Download three dev-dependencies**
>
> - @babel/cli
>   : used to compile from commandline
> - @babel/core
>   : Used for understand the babelrc
> - @babel/preset-env

#
>Steps  
> - Create a ==\.babelrc== file at the root level  
>   ``` 
>     {"preset" :["@babel/preset-env"]}
>   
>   ```
> - npm init to initialzing package.json
>   - open it
>      - put this script for compilation  
>        ```
>          "script":
>          {  
>            
>             "build" : /"babel <targeted-file> -o <destination-file>",  
>
>             "start" : "npm run build && nodemon prd/index.js"
>          }
>
>          ```
> - 
