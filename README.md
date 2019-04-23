# Giraffe Example F# dotnet core project

This sample web application demonstrates how to get started with Giraffe to create a simple web application.

# Steps to re-create this Giraffe project from scratch:

1. dotnet new -i giraffe-template::*

2. Create an empty folder named "giraffe-sample".

3. Open a command prompt at that folder.

4. dotnet new giraffe -lang F#

5. dotnet restore

6. dotnet run

7. Open a browser and navigate to localhost:5000

	You should see "Hello world, from Giraffe!"

8. Navigate to http://localhost:5000/hello/Fred

	You should see "Hello Fred, from Giraffe!"
	
# Links

https://github.com/giraffe-fsharp/Giraffe

https://www.hanselman.com/blog/AFunctionalWebWithASPNETCoreAndFsGiraffe.aspx

https://www.youtube.com/watch?v=HyRzsPZ0f0k

https://dusted.codes/functional-aspnet-core-part-2-hello-world-from-giraffe
