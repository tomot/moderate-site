# moderate-site

## Description
本リポジトリは、Qiitaに投稿した以下の記事のサンプルサイトです。<br>
[定番ツールを組み合わせて「そこそこの見栄えと機能のサイト」をお手軽に公開する](https://qiita.com/tomotlab/items/5f05b61dbed1f333bb47)

## Demo
[https://tomot.github.io/moderate-site/](https://tomot.github.io/moderate-site/)

## Installation

```shell
git clone https://github.com/tomot/moderate-site.git
cd moderate-site
bundle
```

## Usage

```shell
vi _layouts/default.html
   *** Google AnalyticsのコードとFont AwesomeのKit Codeを各自のものに変更する。***
vi _includes/header.html
   *** GitHubとTwitterのアカウントを各自のものに変更する。***
```

## Directory structure

```
.
├── Gemfile
├── Gemfile.lock
├── README.md
├── _config.yml
├── _data/
│   └── navi.yml
├── _includes/
│   ├── footer.html
│   └── header.html
├── _layouts/
│   └── default.html
├── _sass/
│   └── main.scss
├── _site/
├── assets/
│   └── css/
│       └── styles.scss
├── index.md
├── link.md
├── thema-a.md
└── thema-b.md
```

## License
This software is released under the MIT License.

## Author
- Github: [tomot](https://github.com/tomot)
- Twitter: [@tomotlab](https://twitter.com/tomotlab)
