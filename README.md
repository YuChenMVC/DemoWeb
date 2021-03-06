# Simple ASP.NET Core WebApi
<br>

![APM](https://img.shields.io/apm/l/vim-mode?color=lightgrey&label=license&logo=.net&logoColor=lightgrey)

![GitHub commit checks state](https://img.shields.io/github/checks-status/YuChenMVC/DemoWeb/5b233a3e5b4225fd16b6d22f1fc2fa985bbf1126?color=ff69b4&label=DemoWeb&logo=github&logoColor=%23FC60A8&style=plastic)

![png](https://github.com/YuChenMVC/DemoWeb/blob/master/wwwroot/api.png)

## Folder
>/appsettings.json 組態資料<br>
>/launchSettings.json 環境設定<br>
>/Program.cs EntryPoint&註冊DI<br>
>/.gitattributes Git版控<br>
>/DemoWeb.csproj 相關套件<br><br>

## Language
```C#
C#
```

## Table Schema Script
><br>DemoWeb/wwwroot/Company.sql
><br>DemoWeb/wwwroot/Customer.sql
><br>DemoWeb/wwwroot/House.sql
><br>DemoWeb/wwwroot/UploadFile.sql
><br>DemoWeb/wwwroot/User.sql<br><br>

## Tools Version
><br>Visual Studio 2022<br>
>SQL Server Express 2019<br>
>SQL Server Management Studio 18<br><br>

## Example
><br>請求<br>
>GET /api/List/{id}/ information HTTP/1.1<br>
>參數說明<br>
>[HttpGet("{id}")]<br>
>回應<br>
>HTTP/1.1 200 OK + json格式資料回傳<br><br>

## Contributing
><br>請使用pull request<br><br>

## License
><br>[MIT](https://choosealicense.com/licenses/mit/)<br><br>

## Resource
- Azure CI/CD
- Automated Unit Testing
- Markdown Syntax <https://www.markdownguide.org/basic-syntax/>
- <https://docs.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-6.0&tabs=visual-studio>
- <https://docs.microsoft.com/en-us/aspnet/core/release-notes/aspnetcore-6.0?view=aspnetcore-6.0>
