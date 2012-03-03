Simple NuGet package server.

The project is created by following the steps here: http://docs.nuget.org/docs/creating-packages/hosting-your-own-nuget-feeds.

The project uses the NuGet package NuGet.Server.

To set up the NuGet package server:

* Clone the repository
* Configure path of package folder and api key in web.config\appSettings\packagesPath and web.config\appSettings\apiKey
* Put NuGet packages (*.nupkg) in the package folder
* Build the solution
* Mount the website