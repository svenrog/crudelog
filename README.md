# Crude log formatter

A way to simplify console logging from the default C# fancy 2 line logging that provides way too much information for simple applications.

- Has some simple coloring related to log levels.
- Has some highlight formatting when placing text between single quotes ''.

## Usage

`dotnet add package Crude.Logging.Console`

In your startup code

```
var builder = Host.CreateApplicationBuilder(arguments);
builder.Logging.AddConsoleLogging();
```

## Package maintainer

https://github.com/svenrog

## Changelog

[Changelog](CHANGELOG.md)
