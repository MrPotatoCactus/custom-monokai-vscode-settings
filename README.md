# monokai-vscode-settings
Paste this into vscode settings.json and switch to monokai theme
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
                    "scope": "variable.other.property, variable.other.enummember",
                    "settings": {
                        "foreground": "#66D9EF"
                    }
                },
                {
                "scope": "entity.name.function.member",
                    "settings": {
                        "foreground": "#e600ff"
                    }
                },
            ]
        }
    }
}
