# C# Umbraco Skills

Build an Umbraco Site

## Setup

Run the following:

    dotnet new install Umbraco.Templates --force && dotnet new sln --name "workshop" && dotnet new umbraco --force -n "workshop.wwwsite"  --friendly-name "Administrator" --email "nigel@nigel.nigel" --password "1234567890" --development-database-type SQLite && dotnet sln add "workshop.wwwsite" && dotnet new umbraco-compose -P "workshop.wwwsite" && dotnet run --project "workshop.wwwsite"

Then in your browser visit the site login page in the console! Log in with the credentials in the above command.
