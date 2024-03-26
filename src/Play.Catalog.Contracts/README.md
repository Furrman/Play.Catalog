# Common library
Library with published contract between Catalog service and other services

## Building app
dotnet build

## Specify dotnet local Nuget Package source path (you need to do it only once)
dotnet nuget add source "<Asbosule_path_to_package_folder>" -n PlayEconom

## Pack library and export to output folder
dotnet pack -o ../../../packages/
dotnet pack -o ../../../packages/ -p PackageVersion=1.0.1 