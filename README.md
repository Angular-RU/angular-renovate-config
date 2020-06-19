## Sharable Renovate config

![](https://travis-ci.org/Angular-RU/angular-renovate-config.svg?branch=master)

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
