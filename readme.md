ASP.NET MVC Common Declarative Helpers
======================================

Overview
--------
The idea is to provide simple and easily customizable helpers that will make your Razor views slightly cleaner.


Installation
------------
* create folder "App_Code" to the root of your web project
* copy any cshtml files that you need to the "App_Code" folder

Usage
-----
For example to load a CSS file

     @Assets.CSS("main.css")
