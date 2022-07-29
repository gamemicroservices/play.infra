# Play.Infra
A infrastructure component used by the Play services.

## Add the GitHub package source
```powershell
$owner="gamemicroservices"
$gh_pat="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"

dotnet nuget add source --username andretheprogrammer --password $gh_pat --store-password-in-clear-text --name github "https://nuget.pkg.github.com/$owner/index.json"
```