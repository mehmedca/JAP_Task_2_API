# JAP_Task_2_API
<hr>
<p>This is a <b>.NET Core Web API project</b> made for the purposes of completing SECOND task of <b>JAP</b>. The idea was to make a small and simple web app similar to IMDB.com but much much more simple and rudimentary. </p>
<hr>

<h2>*** Quick reminder - Open image on the link below *** 
    <br>
    Since there is no UI support for this particular task, before testing this (movies/buy-ticket) endpoint, please try the above one first. The GET will get you screenings with available tickets to purchase. Thank you! </h2>
![movieAPIsnip](https://user-images.githubusercontent.com/89463590/134086022-e5a1d1ea-1945-4ab7-9189-48deccbb468c.PNG)

<br>
<h2>Some of the guidelines in order to start up the project below:</h2>
<ul> 
    <li>
        PostgreSQL was used as a DB provider. So, after the initial clone of the project check appsettings.json -> adjust DB connection string then run  <span syle="font-weight: 600; color: #84a0b8">"update-database"</span> in npm console in order to create a new db instance on your machine.
    </li>
    <li>
        Startup the app, you should see swagger running on localhost:25398, you can test the endpoints straight from there. Authentication is implemented on swagger as well, and most of the endpoints are protected so you need to authenticate using /auth/login then paste the JWT token which you'll receive as a response. You can also register using /auth/register endpoint.
    </li>
    <li>
        Credentials: 
        <br>
        <p> <span syle="font-weight: 600; color: #84a0b8">admin</span> -  <span syle="font-weight: 600; color: #84a0b8">P4$$word</span</p>
        <p>moderator - P4$$word</p>
        <p>user - P4$$word</p>
    </li>
</ul>

<hr>
<br>
