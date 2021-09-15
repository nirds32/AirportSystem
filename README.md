# AirportSystem BY NIR ASSRAF
Airport Departers and arrivels managment system Based on .NET Core - WPF application for client-side and ASP.NET for the server side which communicate with the client by SignalR service,  and save the information by Entity Framework into DB.

# EXTRACT AirportServer.rar
# OPEN .sln file
# in solution explorer right click on AirportServer project, click 'Manage User Secrets' 
# paste your connection string in the pattern:

{
     "ConnectionStrings": 
      {
        "AirportConnection": "Data Source=YOURCONNECTIONAME;Initial Catalog=Airport;Integrated Security=True"
      }
}
# SAVE the file
# Make sure the startup project are both server and client.
# Run the project.
