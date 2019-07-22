# DoXTract

Very Fast Pure JS Text Extractor For Your Office Files.

[![NPM](https://nodei.co/npm/doxtract.png?compact=true)](https://nodei.co/npm/doxtract/)

[![install size](https://packagephobia.now.sh/badge?p=doxtract)](https://packagephobia.now.sh/result?p=doxtract)
[![NPM Downloads](https://img.shields.io/npm/dm/doxtract.svg?style=flat)](https://npmcharts.com/compare/doxtract?minimal=true)

## Installation

```bash
npm i doxtract
```

## Example

```js
const { extractText } = require('doxtract');
extractText('./file.docx').then(console.log).catch(console.error);
```

## Contribution

Please send your proposed changes as a [pull request](https://help.github.com/en/articles/about-pull-requests) [here](https://github.com/sorleone/doxtract/pulls) thanks. If you can't find a solution report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/sorleone/doxtract/issues).

### Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/InfSpell">
        <img src="https://avatars.githubusercontent.com/u/36854593" width="100px;" alt="Yuriy Kryvets"/>
        <br/>
        <b>Yuriy Kryvets</b>
      </a>
    </td>
  </tr>
</table>

<p align="center">
  <br/>
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0">
    <img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc-sa.svg"/>
  </a>
  <br/>
  Copyright &copy; 2019
</p>
