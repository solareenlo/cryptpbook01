# crypto-book-01
- 同人誌の雛形 ver1.0.0

## Overview
- Docker 内で RE:VIEW を動かして同人誌を書く．

## Requirement
- git
- Docker
- テキストエディタ

## Usage
```bash
git clone git@github.com:solareenlo/cryptpbook01.git
cd cryptobook01
sudo docker pull vvakame/review:4.0
sudo docker-compose run --rm review rake pdf
```

## RE:VIEW の書き方
- [RE:VIEW フォーマットガイド](https://github.com/kmuto/review/blob/master/doc/format.ja.md)
- [RE:VIEW の Wiki](https://github.com/kmuto/review/wiki)

## License
Main part of Re:VIEW is applied GNU Lesser General Public License (LGPL).
See [COPYING](https://github.com/kmuto/review/blob/master/COPYING) file.

Exception:

* doc/*: MIT License. See [LICENSE](https://github.com/kmuto/review/blob/master/doc/LICENSE) file.
* jumoline.sty, vendor/jumoline: The LaTeX Project Public License. See [LPPL](https://github.com/kmuto/review/blob/master/vendor/jumoline/lppl.txt) file.
* plistings.sty, vendor/plistings: MIT License. See [LICENSE](https://github.com/kmuto/review/blob/master/vendor/plistings/LICENSE) file.
* gentombow.sty, vendor/gentombow: BSD License. See [LICENSE](https://github.com/kmuto/review/blob/master/vendor/gentombow/LICENSE) file.
* jsbook.cls, vendor/jsclasses: BSD License. See [LICENSE](https://github.com/kmuto/review/blob/master/vendor/jsclasses/LICENSE) file.

## References
- [kmuto/review](https://github.com/kmuto/review)
- [vvakame/docker-review](https://github.com/vvakame/docker-review)
- [vvakame/docker-review/doc/windows-review.md](https://github.com/vvakame/docker-review/blob/master/doc/windows-review.md)
- [solareenlo/docker-review](https://github.com/solareenlo/docker-review)
