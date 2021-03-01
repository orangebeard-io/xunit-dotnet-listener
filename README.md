# xunit-dotnet-listener
Orangebeard listener for xUnit.net tests
<h1 align="center">
  <a href="https://github.com/orangebeard-io/xunit-dotnet-listener">
    <img src="https://raw.githubusercontent.com/orangebeard-io/xunit-dotnet-listener/main/.github/logo.svg" alt="Orangebeard.io xUnit.net Test Listener" height="200">
  </a>
  <br>Orangebeard.io xUnit.net Listener<br>
</h1>

<h4 align="center">A Listener to report xUnit.net tests in Orangebeard.</h4>

<p align="center">
  <a href="https://github.com/orangebeard-io/xunit-dotnet-listener/blob/main/LICENSE.txt">
    <img src="https://img.shields.io/github/license/orangebeard-io/xunit-dotnet-listener?style=flat-square"
      alt="License" />
  </a>
</p>

<div align="center">
  <h4>
    <a href="https://orangebeard.io">Orangebeard</a> |
    <a href="#build">Build</a> |
    <a href="#install">Install</a>
  </h4>
</div>

## Build
 * Clone this repository
 * Build the build using MSBuild

## Install

```cs
    Environment.SetEnvironmentVariable("orangebeard.endpoint", "https://your-instance.orangebeard.app");
    Environment.SetEnvironmentVariable("orangebeard.accessToken", "api-token-for-orangebeard");
    Environment.SetEnvironmentVariable("orangebeard.project", "projectname");
    Environment.SetEnvironmentVariable("orangebeard.testrun", "Test Run name");
    Environment.SetEnvironmentVariable("orangebeard.fileupload.patterns", @".*\.txt;.*\.bat"); //OPTIONAL
```

Now run your test as you normally do and see the results fly in to Orangebeard!
