listen make sure that now your server will listen request from client.
express adds it as a dependency and for dev dependecy use npm i package name and thennpm io express -dev
app.use((req, res) => {
res.send("hello from the server");
});==> Request handler

this will send hello to everyone
thats why app.use needs a route to make this working differently for diffeerent work like
app.use("/test)=> this will only got this route / then test
