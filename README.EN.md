<h1 align="center">
  <img src="https://s21.ax1x.com/2024/09/18/pAKnSzV.png" alt="ATReader"></img>
  <br></br>
  ATReader
  <br></br>
</h1>

<div align="center">

<h2>An e-book reader for VSCode extension</h2>

[![Version](https://img.shields.io/badge/Version-v1.0.0-blue)](https://github.com/AegeanTec/ATReader)
[![Installs](https://img.shields.io/badge/Installs-1+-darkgreen)](https://github.com/AegeanTec/ATReader)
[![Rating](https://img.shields.io/badge/Rating-★★★★★-brightgreen)](https://github.com/AegeanTec/ATReader)

[简体中文](https://github.com/AegeanTec/ATReader/README.md) | English

</div>

## TOC

- [TOC](#toc)
- [Features](#features)
- [Requirements](#requirements)
- [Configuration](#configuration)
- [Usage](#usage)
- [Change log](#change-log)
- [Issues](#issues)
- [Acknowledgements](#acknowledgements)
- [Declaration](#declaration)

## Features

- Compact: The plugin has a small size, low resource consumption, and runs smoothly.
- Refreshing: Status bar displayed line by line, without invading the core workspace.
- Powerful: Easy to operate, powerful, supports various shortcut keys.

## Requirements

- VSCode 1.93.0+

## Configuration


1. Prepare a configuration file (eg: 'D:\XS\config.json'),[Example](https://github.com/AegeanTec/ATReader/blob/main/config.json)

```json
{
  "books": [
    {
      "url": "Book URL (required), please refer to the actual supported website for details."
    }
  ]
}
```

2. Click the ATReader icon to enter the books library, click the button to select the configuration file (which can be modified later in the settings).

![Init](https://s21.ax1x.com/2024/09/18/pAK1JYQ.png)

3. Update book catalog:

![UpdateBook](https://s21.ax1x.com/2024/09/18/pAK11w8.png)

## Usage

| Shortcut keys | function      | note                                           |
| :-----------: | :-----------: | :--------------------------------------------: |
| Alt + X       | Boss key      | **Status bar display default is turned off.**  |
| Alt + A       | Prev-Chapter  |                                                |
| Alt + W       | Prev-Row      |                                                |
| Alt + S       | Next-Row      |                                                |
| Alt + D       | Next-Chapter  |                                                |

![StatusBar](https://s21.ax1x.com/2024/09/18/pAK13TS.png)

![Useage](https://s21.ax1x.com/2024/09/18/pAK1YWj.png)



## Change log

- [Change log](https://github.com/AegeanTec/ATReader/CHANGELOG.md)


## Issues

- [GitHub Issues](https://github.com/AegeanTec/ATReader/issues)


## Acknowledgements

- [cloudmusic-vscode](https://github.com/YXL76/cloudmusic-vscode)
- [read-book-status-bar](https://github.com/1826888766/read-book-status-bar)


## Declaration

- This project may access textual content from third-party websites, and the author is not responsible for its content. 
- If you are the content owner, please contact us via [email](mailto:AegeanTec@163.com), we will immediately block the relevant content.
