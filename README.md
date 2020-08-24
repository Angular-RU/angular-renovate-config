## Sharable Renovate config

[![](https://github.com/angular-ru/angular-ru-sdk/workflows/Angular-RU%20SDK%20CI/badge.svg)](https://github.com/Angular-RU/angular-renovate-config/actions?query=workflow%3A%22Angular-RU+Renovate+CI%22)

#### Usage

[Documentation config presets](https://docs.renovatebot.com/config-presets/)

-   Create file `renovate.json`

```json
{
    "extends": ["github>Angular-RU/angular-renovate-config"],
    "baseBranches": ["master"]
}
```

-   Custom rules and custom branch

```json5
{
    extends: ['github>Angular-RU/angular-renovate-config'],
    baseBranches: ['develop'],
    packageRules: [
        // override rules
    ]
}
```
