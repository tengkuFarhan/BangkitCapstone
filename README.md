# Agroclima Web Service

Agroclima web service is the web service that can make you access the application to predict the plants that you want to plant according to soil conditions and several factors that affect plants from the area by inputting them into the form in the client's view.

You need to know, to access the prediction system you need to authenticate first. You need to login into the application. After logging in, you can make plant predictions from the data that is input into the form.

<blockquote> Base url for development <a href='http://localhost:5000/'>http://localhost:5000/</blockquote>
  
  API documentation of this service :
  
  * Authentications 
  <pre>POST /authentications</pre>
  <pre>PUT  /authentications</pre>
  <pre>DEL  /authentications</pre>
  
  
  * Users
  <pre>GET  /users/{userId}</pre>
  <pre>POST /users</pre>
  <pre>PUT  /users/{userId}</pre>
  <pre>DEL is not avalable now</pre>
  
  
   * Predictions
  <pre>POST /predictions/cassava</pre>
  <pre>POST /predictions/rice</pre>
  <pre>POST /predictions/tomato</pre>
