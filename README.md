# Live Projects
This repository consists of the work I did while working on a team with Prosper IT Consulting

## Live Project April
During this project I used Python and the Django framework to create a full functioning CRUD application as an addition to a hobby tracking website. I worked on back end processes connected to a database and front end styles for user friendly appearance and direction. I worked with a team of developers, with daily stand-ups and a weekly retrospective I was able to communicate well with the team on where I was at and if I was bugged. I had the opportunity to troubleshoot with other developers for the solutions when there was a bug. Troubleshooting together helped my software developer way of thinking grow. 

### Back End:
I created a model for "shark lovers" that would be converted into a form and connected to a database. Within the model I had two areas that gave a certian list of given choices for the user. 

<img width="535" alt="Model" src="https://user-images.githubusercontent.com/76531384/121251838-8b0b7200-c864-11eb-8e9d-cfda0f9d86b9.PNG">

This is the form to create a new item. It is linked to the create html page. That page has the form and the form is styled for a user friendly look. 

<img width="463" alt="CreateForm" src="https://user-images.githubusercontent.com/76531384/121251090-b6da2800-c863-11eb-8458-90c4d6c0ec49.PNG">

I made a method to display the main columns from the database on a display html page. It is displayed in a table form. From this page the user can click for further details of one table item, after clicking the details page is displayed using a details method I created that displays all the details of the specific database item in the same table look of the display html page for consistency. In order to get one items details to display I passed the primary key of the selected item from the views page to the method and then to the details view page. 

<img width="488" alt="DisplayViews" src="https://user-images.githubusercontent.com/76531384/121251145-cb1e2500-c863-11eb-9f65-4be75727c9e6.PNG">

From the details view page the user can then choose to delete or update the item. Each option has a method I created that, again passes the primary key of the item to delete or update that specific it in the database. 

<img width="477" alt="Update_Delete" src="https://user-images.githubusercontent.com/76531384/121251182-d3766000-c863-11eb-816d-f75875ac2d45.PNG">

### Front End:
I made a Base HTML page for all other pages to be made from in order to keep the application consistent. The other pages include: home, details, display, delete, and update.

<img width="547" alt="BaseHTML" src="https://user-images.githubusercontent.com/76531384/121265314-daa66980-c875-11eb-8981-e05019e988ed.PNG">
 
I used css to style the form.

<img width="323" alt="FormStyle" src="https://user-images.githubusercontent.com/76531384/121287327-8e235400-c89e-11eb-804c-3f17ba209d3d.PNG">
 
<img width="336" alt="InputStyle" src="https://user-images.githubusercontent.com/76531384/121287351-99767f80-c89e-11eb-8fff-05a863f1e4bb.PNG">

And for the table style.

<img width="326" alt="TableStyle" src="https://user-images.githubusercontent.com/76531384/121287467-d5a9e000-c89e-11eb-9d71-f712a219b16f.PNG">

## Live Project May
During this project I used C#, ASP.Net MVC, and Entity Framework to build upon an existing project for a website for a client. Using code first I added an MVC application to a portion of the website. 

### Back End:
I created a model for Cast Members with many different input options, including an enum.

<img width="357" alt="CastMemModel" src="https://user-images.githubusercontent.com/76531384/121293484-ec553480-c8a8-11eb-936f-0a302ce16a07.PNG">

My main task was creating an area for a user to upload photo from their own computer to the database in an easy user friendly way. I converted the photo to a byte array to save in the database.

<img width="388" alt="PhotoToBytes" src="https://user-images.githubusercontent.com/76531384/121293832-84ebb480-c8a9-11eb-96a8-6428a0dae559.PNG">

When editing the photo, I created a way for the user to view the original photo they chose and either keep that photo or select another. I used an if statement for the separate choices.

<img width="655" alt="EditPhoto" src="https://user-images.githubusercontent.com/76531384/121294161-28d56000-c8aa-11eb-9940-0d0d3c83d4f3.PNG">

In order to display the photo on every view page I had to create a method to convert the byte array back to the image for display.

<img width="519" alt="PhotoDisplay" src="https://user-images.githubusercontent.com/76531384/121294786-3212fc80-c8ab-11eb-90c6-382174a01644.PNG">


### Front End:
I created an input area for the user to browse their photos and select one. 

<img width="619" alt="CreateView" src="https://user-images.githubusercontent.com/76531384/121294399-8d90ba80-c8aa-11eb-916b-f3f4e11743be.PNG">

I also created a display for the photo on each view page, and included a new input area on the edit view.

<img width="616" alt="EditView" src="https://user-images.githubusercontent.com/76531384/121294806-3a6b3780-c8ab-11eb-9410-1d4ef356fc4b.PNG">

The additional divs surrounding the input area helped me establish user friendly buttons for browsing and submiting, that also matched the theme if the site.

<img width="273" alt="BrowseBtnStyle" src="https://user-images.githubusercontent.com/76531384/121295181-d5fca800-c8ab-11eb-8fc2-c7de3080ede4.PNG">


### Additional Story Front and Back End
I used JavaScript to get a count of all the developers working on this project and bootstrap to display the amount. 

<img width="337" alt="ScriptCount" src="https://user-images.githubusercontent.com/76531384/121291009-c75ec280-c8a4-11eb-84fd-e56ed71f2355.PNG">

<img width="709" alt="Bootstrap" src="https://user-images.githubusercontent.com/76531384/121291025-cfb6fd80-c8a4-11eb-9b5c-3daefbcd2d06.PNG">



