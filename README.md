# Bow Tintin Template Snippets

Bow Tintin snippets and syntax highlight support for Visual Studio Code.

> Suggest to install Bow related extension: [Bow Tintin Snippets](https://marketplace.visualstudio.com/items?itemName=papac.bow-tintin)

## User Settings

Open `Preferences` -> `Settings`

```json
"emmet.triggerExpansionOnTab": true, // enable tab to expanse emmet tags
"tintin.format.enable": true,         // if you would like to enable Tintin format
```

Specific settings for Tintin language

```json
"[tintin]": {
    "editor.autoClosingBrackets": "always"
},
```

## Features

- Tintin syntax highlight
- Tintin snippets
- Emmet works in Tintin template
- Tintin formatting

## Tintin Syntax Hightlight

- Auto detected with `.tintin.php` extension
- Manually switch language mode to `tintin` (`Ctrl + K, M` or `⌘ + K, M`)

## Bow Tintin Snippets

| Trigger             | Snippet                                   |
| ------------------- | ----------------------------------------- |
| t:extends           | #extends                                  |
| t:block             | #block ... #endblock                      |
| t:include           | #include                                  |
| t:inject            | #inject                                   |
| t:if                | #if...#endif                              |
| t:if-else           | #if...#else...#endif                      |
| t:unless            | #unless                                   |
| t:while             | #while...#endwhile                        |
| t:for               | #for...#endfor                            |
| t:loop              | #loop...#endloop                          |
| t:comment           | #for...#endcomment                        |
| t:echo              | {{ '' }}                                  |
| t:jump              | #jump()                                   |
| t:stop              | #stop()                                   |

## Contact

- [@tchirktema](https://twitter.com/tchirktema)

## Credits

- Tintin language grammar is based on [Medalink syntax definition](https://github.com/bowphp/tintin)

## License

Please read [License](LICENSE.md) for more information
