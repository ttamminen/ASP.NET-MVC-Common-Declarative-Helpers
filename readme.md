ASP.NET MVC Common Declarative Helpers
======================================

Overview
--------
The idea is to provide simple and easily customizable helpers that will make your Razor views slightly cleaner.

Sometimes using built-in html helpers can cause ugly syntax when you don't find exactly correct overrides. For example simple thing like creating a form is done using helper that has 11 overrides. There are no optional parameters or named arguments.

Installation
------------
* create folder "App_Code" to the root of your web project
* copy any cshtml files that you need to the "App_Code" folder

Usage
-----
Examples how to use Assets helper.

To load a css file

```csharp
@Assets.CSS("main.css")
```

To load a javascript file

```csharp
@Assets.Script("main.css")
```