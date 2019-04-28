# Giraffe Example F# dotnet core project

This sample web application demonstrates how to get started with Giraffe to create a simple web application.

# Steps to re-create this Giraffe project from scratch:

1. dotnet new -i giraffe-template::*

2. Create an empty folder named "giraffe-sample".

3. Open a command prompt at that folder.

4. dotnet new giraffe -lang F#

5. .\build.bat

	NOTE: If the folder name contains hyphens, then you will need to edit the build.bat to replace the underscores with hyphens.

6. dotnet run --project src/giraffe-sample/giraffe-sample.fsproj

	or dotnet watch --project src/giraffe-sample/giraffe-sample.fsproj run

7. Open a browser and navigate to http://localhost:5000/

	You should see "Hello world, from Giraffe!"

8. Navigate to http://localhost:5000/hello/Fred

	You should see "Hello Fred, from Giraffe!"

# Resources

https://github.com/giraffe-fsharp/Giraffe

https://www.hanselman.com/blog/AFunctionalWebWithASPNETCoreAndFsGiraffe.aspx

https://www.youtube.com/watch?v=HyRzsPZ0f0k

https://dusted.codes/functional-aspnet-core-part-2-hello-world-from-giraffe
