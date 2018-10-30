create a new solution folder FolderX

cd to the solution folder FolderX and run  dotnet new sln

within the solution FolderX, create a new folder ProjectX

cd into ProjectX and run dotnet new webapi

cd to the solution folder FolderX and run dotnet sln add .\ProjectX\ProjectX.csproj

within the solution FolderX add another folder ProjectXTest

cd to ProjectXTest and create a test project by running dotnet new xunit

within ProjectXTest  run dotnet add refence ..\ ProjectX\ProjectX.csproj

