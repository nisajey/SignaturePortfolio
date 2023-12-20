Project 3: St. Paul Crime RESTful Web Server

I worked on creating a user-friendly web server to handle St. Paul crime data. This was part one of a two-part project. I got the data from St. Paul's public dataset and carefully stored it in an SQLite3 database. The database had three tables - Codes, Neighborhoods, and Incidents - storing important details about crime incidents, like codes, neighborhoods, and specific incident info.In setting up the RESTful web server, I made sure to follow good practices. I organized the package.json file neatly, specifying the author, contributors, and repository URL. I managed dependencies well and kept the GitHub repository clean by excluding unnecessary files.

I created API routes to fetch valuable insights into St. Paul crime data. These routes returned organized JSON responses, covering crime codes, neighborhood details, and incident data. I also added routes to upload new incidents and remove existing ones from the database.To make the server more user-friendly, I added query options for GET routes. This allowed users to filter results based on specific criteria like crime codes, neighborhood IDs, date ranges, and more.

Project 4: St. Paul Crime Interactive Web Application

In Project 4, I stepped into dynamic web application development to create an engaging single-page application about crimes in St. Paul. I used Leaflet, Nominatim, and the API from Project 3, along with Vue JS for efficiency. The application featured a visually appealing Leaflet map with pan and zoom functions, focusing on St. Paul for a better user experience. I implemented an easy-to-use input box and 'Go' button for users to explore locations seamlessly.

A key feature was fetching data from the St. Paul Crime API, showing the 1,000 most recent crimes by default. The data was presented in an organized table, ordered by recency. I added markers on the map for each neighborhood, offering a visual representation of crime occurrences.I also contributed to creating a new incident upload form for users to easily add new incidents to the database. Additionally, I participated in building the "About the Project" page, giving insights into our team, tools used, and a video demo showcasing the application.

To enhance user experience, I played a role in adding features like UI controls for filtering crime data, background color styling for crime categorization, and a 'delete' button for each crime in the table. These refinements resulted in an interactive and informative web application, making it easy for users to explore St. Paul crime data.

