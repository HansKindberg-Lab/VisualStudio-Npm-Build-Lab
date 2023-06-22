# VisualStudio-Npm-Build-Lab

This is an example solution where I use msbuild-targets to build npm-stuff. I find gulp / grunt tasks a bit complicated so I want to do it in another way. Found this:

- [Running npm tasks when building a .NET project](https://www.meziantou.net/running-npm-tasks-when-building-a-dotnet-project.htm)

At the moment sass is built to css. Bootstrap is included.

## 1 Development

You may have to run Visual Studio as an administrator.

At my work we have AppLocker group-policys in our domain. So when I build this project I get:

	MSB3073 The command "npm install" exited with code 1.

If I run Visual Studio as administrator I get around the error.

## 2 Links

- [Running npm tasks when building a .NET project](https://www.meziantou.net/running-npm-tasks-when-building-a-dotnet-project.htm)
- [Incremental builds](https://learn.microsoft.com/en-us/visualstudio/msbuild/incremental-builds)