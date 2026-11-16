# WinRelease Helper downloads

The WinRelease Helper is a small program that builds MSIs on your own PC for [WinRelease](https://winrelease.geappsolutions.com), a free MSI builder for Windows (beta).

**Download:** the newest file is on the [Releases](../../releases) page. Older versions marked "superseded" still work, but use the newest.

**Check what you downloaded:** each release lists a SHA-256. In PowerShell, run `Get-FileHash .\WinRelease.Helper.exe -Algorithm SHA256` and compare the result with the release notes and the website's Settings page. Early releases are not code-signed yet, so Windows may warn before running them.

**See what it does:** the [source is published for inspection](https://github.com/grantis19-create/winrelease-source) (it is not open source).

**Feedback:** use the [public tracker](https://github.com/grantis19-create/winrelease-feedback). **Security problems:** please use the [private report form](https://github.com/grantis19-create/winrelease-source/security/advisories/new), not a public issue.

Everything in this repository is a downloadable release; it holds no source code.
