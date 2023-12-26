to create frontend templet:

        npm create vite@latest client --templet vanilla

then we select the framework that is vanilla

then we will select the varient that javascript

then we go to the client folder and 

        npm install


for teh server create teh server folder and create the server

        npm init -y

this will create the package.json file in server folder

then we will install some other helper packages

        npm install cors dotenv express nodemon openai

then we will go to the openai api and create the new api key

and create a .env file in server and put the api key in it

        OPENAI_API_KEY="*********************"

to deploy our server we have used the render.com 

        there you can create the new > Web service
        add the public git repository of your application into web service 
        to add the repositery past the repo link to it 
        then it will show the setting of the web service
        
        you can put the name
        
        you can put the region
        
        choose the branch of our repo
        
        then the important part you have to choose the root repository of your web service
        here we are putting the server so put the server
        
        enviroment is going the node
        
        then put the build command yarn or npm
        
        then the important start command of your server  
         npm run server

        then it will show you the package you can choose the free

        then click on the button create the web service

        then you have to go to the enviroment and add the enviroment variables 
        there you have to add the enviroment variable that we have written inside the .env file
        
        now when our server is deployed successfully on the render.com it will give you a live link copy that link


past the link you get from server into the client side where ever we have put the http://localhost:5000 

now we are ready to deploy out front end online

we are going to deploy our frontend on vercel.com

for that select our git repository and select th eroot repository to client folder and continue and click deploy



---------------
we create new api key at date 26-12-2023 for chat gpt clone and on render deployed server we have change the api key