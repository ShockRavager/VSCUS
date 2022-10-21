# VSCUS
VS Code User Settings

"editor.semanticTokenColorCustomizations": {
        "[Default Dark+]": {
            "rules": {
                "method": {
                    "foreground": "#40E0D0",
                    "bold": false
                },
                "enumMember": {
                    "foreground": "#00FFFF",
                    "bold": false
                },
                "function": {
                    "foreground": "#40E0D0", // 4EC9B0
                    "bold": false
                },
                "class": {
                    "foreground": "#9B9B00", // #DCDCAA
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
                    "foreground": "#DCDCAA", // #DCDCAA
                    "bold": false
                },
                "variable": {
                    "foreground": "#B0C4DE",
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
                        "foreground": "#40E0D0" 
                    }
                },
                {
                    "scope": "storage.type.class",
                    "settings": {
                        "foreground": "#2887D5", // 2887D5
                        "fontStyle": "bold"
                    }
                },
                {
                    "scope": "storage.type.function",
                    "settings": {
                        "foreground": "#2887D5",
                        "fontStyle": "bold"
                    }
                },
                {
                    "scope": "keyword.control.flow",
                    "settings": {
                        "foreground": "#2887D5",
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
                        "foreground": "#2887D5",
                        "fontStyle": "bold"
                    }
                },
                {
                    "scope": "string.quoted",
                    "settings": {
                        "foreground": "#00A100", // 00FF80
                        "fontStyle": ""
                    }
                },
                {
                    "scope": "constant.character.escape",
                    "settings": {
                        "foreground": "#00FF00",
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
                },
                {
                    "scope": "entity.name.function.decorator",
                    "settings": {
                        "foreground": "#00FFFF",
                        "fontStyle": ""
                    }
                },
                {
                    "scope": "constant.other",
                    "settings": {
                        "foreground": "#00FFFF",
                        "fontStyle": ""
                    }
                },
                {
                    "scope": "keyword.operator.logical.python",
                    "settings": {
                        "foreground": "#00BFFF",
                        "fontStyle": ""
                    }
                }
            ]
        }
    }
