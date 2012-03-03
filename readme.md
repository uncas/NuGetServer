Simple NuGet package server.

The project is created by following the steps here: http://docs.nuget.org/docs/creating-packages/hosting-your-own-nuget-feeds.

The project uses the NuGet package NuGet.Server.

To set up the NuGet package server:

* Clone the repository
* Configure package path and api key in web.config\appSettings\packagesPath and apiKey
* Build the solution
* Mount the website