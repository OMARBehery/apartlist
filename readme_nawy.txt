===========technologies and lib used========================

react js , react native , bootstrap, node js , express, mongodb , mongoose , bycrypt etc...

client :

 1) react js : path= nawy_project/client/frontend/apartmobile
               dev server running on port 3000,localhost by def.
               need to install nodemodules to test here 
 2)react native: path = nawy_project/client/frontend/mobile/apartmobile
                 if tested from web dev server running on port 8081,localhost by def.
                  (if port changed you have to change it in the cors option object in the server)
                   need to install nodemodules to test here 


server: 

 1)  arch.: MVC approach
     listening on port 5000,localhost by default
     path: nawy_project/server
     need to install nodemodules to test here 

API: the backend containing a full login and sign up with jwt but not present in the client.
   
    apartRouthes:
    1)'/apart-list': get all apartments 
    2)'/add-apart': post apartment to db
    3)'/:id': get a single apartment by id 


database: OOD mongodb with mongoose lib 


