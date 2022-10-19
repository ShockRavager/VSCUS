# VSCUS
VS Code User Settings

{
    "workbench.colorTheme": "Default Dark+",
    "editor.bracketPairColorization.enabled": false,

    "editor.semanticTokenColorCustomizations": {
        "[Default Dark+]": {
            "rules": {
                "method": {
                    "foreground": "#4EC9B0",
                    "bold": false
                },
                "function": {
                    "foreground": "#4EC9B0",
                    "bold": false
                },
                "class": {
                    "foreground": "#DCDCAA",
                    "bold": false
                },
                "property": {
                    "foreground": "#FFFFFF",
                    "bold": false
                },
                "parameter": {
                    "foreground": "#A3A3A3",
                    "bold": false
                },
                "selfParameter": {
                    "foreground": "#c548ff",
                    "bold": false
                },
                "builtinConstant": {
                    "foreground": "#ffa1fa",
                    "bold": false
                },
                "module": {
                    "foreground": "#DCDCAA",
                    "bold": false
                },
                "variable": {
                    "foreground": "#c1e8ff",
                    "bold": false
                }
            }
        } 
    },

    "editor.tokenColorCustomizations": {
        "[Default Dark+]": {
            "textMateRules": [
                {
                    "scope": "keyword.operator",
                    "settings": {
                        "foreground": "#4EC9B0"
                    }
                },
                {
                    "scope": "storage.type.class",
                    "settings": {
                        "foreground": "#2887d5",
                        "fontStyle": "bold"
                    }
                },
                {
                    "scope": "storage.type.function",
                    "settings": {
                        "foreground": "#2887d5",
                        "fontStyle": "bold"
                    }
                },
                {
                    "scope": "keyword.control.flow",
                    "settings": {
                        "foreground": "#2887d5",
                        "fontStyle": "bold"
                    }
                },
                {
                    "scope": "meta.attribute",
                    "settings": {
                        "foreground": "#FFFFFF",
                        "fontStyle": ""
                    }
                },
                {
                    "scope": "keyword.operator",
                    "settings": {
                        "foreground": "#D4D4D4",
                        "fontStyle": ""
                    }
                },
                {
                    "scope": "keyword.control",
                    "settings": {
                        "foreground": "#2887d5",
                        "fontStyle": "bold"
                    }
                },
                {
                    "scope": "string.quoted",
                    "settings": {
                        "foreground": "#00FF80",
                        "fontStyle": ""
                    }
                },
                {
                    "scope": "constant.character.escape",
                    "settings": {
                        "foreground": "#9CDCFE",
                        "fontStyle": ""
                    }
                },
                {
                    "scope": "constant.numeric",
                    "settings": {
                        "foreground": "#FFFF00",
                        "fontStyle": ""
                    }
                },
                {
                    "scope": "keyword.codetag.notation",
                    "settings": {
                        "foreground": "#00FF00",
                        "fontStyle": ""
                    }
                }
            ]
        }
    }
}
