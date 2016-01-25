#phalconフレームワークを触ってみよう
社内勉強用

#環境 wikiを見て

#phalcon depeloperツール
https://phalconphp.com/ja/download/tools
https://github.com/phalcon/phalcon-devtools

compoer install

``
$curl -s http://getcomposer.org/installer | php
``

``composer.json
{
    "require": {
        "phalcon/devtools": "1.3.*@dev"
    }
}
``

install

``
$./composer.phar install
``

シンボリックリンク

``
$ln -s ~/vendor/phalcon/devtools/phalcon.php /usr/bin/phalcon
$phalcon commands
``


プロジェクトを作成

``
$cd /vargrant
$phalcon project todo
``
