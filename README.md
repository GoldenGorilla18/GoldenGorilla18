- 👋 Hi, I’m @GoldenGorilla18
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
GoldenGorilla18/GoldenGorilla18 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
            - name: Setup .NET Core SDK
  uses: actions/setup-dotnet@v4.3.0
  with:
    # Optional SDK version(s) to use. If not provided, will install global.json version when available. Examples: 2.2.104, 3.1, 3.1.x, 3.x, 6.0.2xx
    dotnet-version: # optional
    # Optional quality of the build. The possible values are: daily, signed, validated, preview, ga.
    dotnet-quality: # optional
    # Optional global.json location, if your global.json isn't located in the root of the repo.
    global-json-file: # optional
    # Optional package source for which to set up authentication. Will consult any existing NuGet.config in the root of the repo and provide a temporary NuGet.config using the NUGET_AUTH_TOKEN environment variable as a ClearTextPassword
    source-url: # optional
    # Optional OWNER for using packages from GitHub Package Registry organizations/users other than the current repository's owner. Only used if a GPR URL is also provided in source-url
    owner: # optional
    # Optional NuGet.config location, if your NuGet.config isn't located in the root of the repo.
    config-file: # optional
    # Optional input to enable caching of the NuGet global-packages folder
    cache: # optional
    # Used to specify the path to a dependency file: packages.lock.json. Supports wildcards or a list of file names for caching multiple dependencies.
    cache-dependency-path: # optional
          