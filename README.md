# GIC-Assessment
User Guid

Clone the repository by gitclone

UI:
  1.UI react project placed in 'UI' Folder and should give 'npm install' inside the folder by opening command prompt.
  
  2.Open a CMD inside the UI folder and run 'npm run dev' to run the UI, backend should be running in background .

BackEnd API:

  1.GICAssesmentProject.sln will open the solution for the BackEnd api.
        Includes 
          ApplicationCore
          ApplicationInfrastructure
          DistributedServices
    
  2.Structured as per the clean architecture.

  3.Import the db from 'DB' file, having both script and .bak file with data.
  
  4.Change appsetting as required for the connection string on you connection properties.
  
  5.Run the GIC.Service.API which includes api and it will be running on http://localhost:5008/ locally.
  
  6.Please change the UI port if it is running on different port than usual.
  
            policy.WithOrigins("http://localhost:5174") // Replace with your frontend URL
              .AllowAnyMethod()
              .AllowAnyHeader();


  
