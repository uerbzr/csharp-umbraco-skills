# C# Umbraco Skills

Build an Umbraco Site

```
dotnet new install Umbraco.Templates --force && dotnet new sln --name "workshop" && dotnet new umbraco --force -n "workshop.wwwsite"  --friendly-name "Administrator" --email "nigel@nigel.nigel" --password "1234567890" --development-database-type SQLite && dotnet sln add "workshop.wwwsite" && dotnet new umbraco-compose -P "workshop.wwwsite" && dotnet run --project "workshop.wwwsite"
```
