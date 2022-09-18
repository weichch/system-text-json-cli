# SystemTextJson Command-Line Interface

A JSON manipulation command-line tool based on System.Text.Json.

## An idea in a nutshell...

At the very beginning, I needed some decent JSON tool to create a lot of large valid JSON objects to test my [`SystemTextJson.JsonDiffPatch`](https://github.com/weichch/system-text-json-jsondiffpatch) library.

It soon got me into a mess when I started learning DTLs required by random object generating libraries or websites.

I'm very suprised I can barely find a JSON manipulation command line tool written in .NET, compared to how many are there writte in JavaScript. So, this brought me into this idea in a nutshell, a JSON CLI based on native .NET technology.

My initial plan:
- I want to create JSON objects like [`jo`](https://github.com/jpmens/jo) does
- I want to run my diff and patch library via command-line
- I want to filter JSON object using a path

Ideally the commands should be run as a `dotnet` command:

```
dotnet json output
dotnet json diff
dotnet json patch
dotnet json select
```

If you feel like this is a useful tool and have some ideas, please let me know by submitting a general issue.
