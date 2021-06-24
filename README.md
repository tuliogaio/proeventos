# Tutorial to create .NET Project

**Create global.json by CLI**

```
dotnet new globaljson --version-sdk 5.0.301 
```

**Create new Project**

```
dotnet new webapi -n ProjectName.API
```

**Run project**

Navigate to the folder created above

```
dotnet run
```

**Run project with HTTPS**

```
dotnet dev-certs https --trust
dotnet run
```

**Run project in mode watch**

```
dotnet watch run
```

**Create gitignore**

```
dotnet new gitignore
```