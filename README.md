# custom-monokai-vscode-settings
A colorful costomization to the default vscode monokai theme. To activate paste the following into vscode settings.json and switch to monokai theme
```json
{
    "editor.tokenColorCustomizations": {
        "[Monokai]": {
            "functions": "#e600ff",
            "variables": "#f9fece",
            "strings": "#00ff8c",
            "textMateRules": [
                {
                    "scope": "entity.name.type, entity.name.class, entity.name.namespace, entity.name.scope-resolution",
                    "settings": {
                        "fontStyle": ""
                    }
                },
                {
                    "scope": "punctuation.separator",
                    "settings": {
                        "foreground": "#F92672"
                    }
                },
                {
                    "scope": "variable.other.property, variable.other.enummember, variable.other.constant.property, meta.member.access",
                    "settings": {
                        "foreground": "#66D9EF"
                    }
                },
                {
                "scope": "meta.function-call, entity.name.function.member",
                    "settings": {
                        "foreground": "#A6E22E"
                    }
                },
            ]
        }
    }
}
```
