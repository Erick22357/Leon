# Leon
steps: - uses: actions/checkout@v3 - uses: actions/setup-dotnet@v3   with:     global-json-file: csharp/global.json - run: dotnet build &lt;my project>   working-directory: csharp
