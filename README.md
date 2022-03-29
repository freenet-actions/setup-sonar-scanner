# setup-sonar-scanner
[![LICENSE](https://img.shields.io/github/license/freenet-actions/setup-sonar-scanner)](https://github.com/freenet-actions/setup-sonar-scanner/blob/main/LICENSE)

This action sets up sonar-scanner tool. It downloads sonar-scanner binaries from https://binaries.sonarsource.com/Distribution/sonar-scanner-cli and adds path to PATH

   
# Usage
## Set up default sonar scanner version (4.4.0.2170)
```yaml
- uses: freenet-actions/setup-sonar-scanner@v1
```
## Set up specific sonar scanner version
```yaml
- uses: freenet-actions/setup-sonar-scanner@v1
  with:
    version: 4.4.0.2170
```
