<p align="center">
  <img src="images/secDevLabs-logo.png" allign="center" height=""/>
  <!-- logo font: Agency FB Bold Condensed -->
</p>

<p align="center">
安全なウェブ/モバイルアプリ開発を実践的に学ぶための実験室。
</p>

<p align="center">
<a href="https://github.com/globocom/secDevLabs/blob/master/docs/CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-Welcome-brightgreen"/></a>
<a href="https://gitter.im/secDevLabs/community"><img src="https://badges.gitter.im/secDevLabs/community.svg"/></a>
</p>

## あなたのラボをビルドする

docker-composeを用いてローカル環境をプロビジョニングして、Webアプリケーションの致命的セキュリティリスクがどのように悪用されるのか、そしてそれをどのように修正すればリスクを軽減できるのかを学びましょう。👩‍💻

## どうやって始めるの？

このリポジトリをフォークすると、Golang、Python、PHPなど様々な言語で作成された、現実の事件に基づいた複数の意図的な脆弱性をもつアプリが見つかります。最初は最も馴染みあるものをインストールしてみましょう。各アプリのページに手順が記載されています。💡

脆弱性にはそれぞれ攻撃者がどのように悪用してくるのかを解説する「攻撃の流れ」セクションが用意されています。コードを読む前に、攻撃そのものの理解を促すため読んでみることをおすすめします。💉

さあ、ついにアプリケーションを保護するターンです。これがあなたの管理するアプリケーションで、それの持つ欠陥を修正する必要があると思ってください！あなたのミッションは、その欠点を抑えるコードを書き、安全なアプリをデプロイするためPull Requestを送信することです！ 🔐

## 私のコードの安全性はどう？

脆弱性を軽減した後は、Pull Requestを送信してsecDevLabsのコミュニティに温和にレビューを依頼することができます。もし迷いがある場合は、 [軽減例](https://github.com/globocom/secDevLabs/pull/29)を見てみてください。何かの助けになるかもしれません。 🚀

## OWASP Top 10 (2021) アプリ: 💻

免責事項：あなたのマシンに大きな脆弱性を持つアプリをインストールしようとしています！ 🔥

| 脆弱性                                 | 言語       | アプリケーション                                                                     |
| --------------------------------------------- | -------------- | ------------------------------------------------------------------------------- |
| A1 - アクセスコントロールの不備                    | Golang         | [Vulnerable Ecommerce API](owasp-top10-2021-apps/a1/ecommerce-api)              |
| A1 - アクセスコントロールの不備                    | NodeJS         | [Tic-Tac-Toe](owasp-top10-2021-apps/a1/tictactoe)                               |
| A1 - アクセスコントロールの不備                    | Golang         | [Camplake-API](owasp-top10-2021-apps/a1/camplake-api)                           |
| A2 - 暗号化の失敗                   | Golang         | [SnakePro](owasp-top10-2021-apps/a2/snake-pro)                                  |
| A3 - インジェクション攻撃                                | Golang         | [CopyNPaste API](owasp-top10-2021-apps/a3/copy-n-paste)                         |
| A3 - インジェクション攻撃                                | NodeJS         | [Mongection](owasp-top10-2021-apps/a3/mongection)                               |
| A3 - インジェクション攻撃                                | Python         | [SSType](owasp-top10-2021-apps/a3/sstype)                                       |
| A3 - インジェクション攻撃（XSS）                          | Python         | [Gossip World](owasp-top10-2021-apps/a3/gossip-world)                           |
| A3 - インジェクション攻撃（XSS）                          | React          | [Comment Killer](owasp-top10-2021-apps/a3/comment-killer)                       |
| A3 - インジェクション攻撃（XSS）                          | Angular/Spring | [Streaming](owasp-top10-2021-apps/a3/streaming)                                 |
| A4 - 不安な設計                          | React/Go       | [Super Recovery Password App](owasp-top10-2021-apps/a4/super-recovery-password) |
| A5 - セキュリティの設定ミス（XXE）          | PHP            | [ViniJr Blog](owasp-top10-2021-apps/a5/vinijr-blog)                             |
| A5 - セキュリティの設定ミス                | PHP            | [Vulnerable Wordpress Misconfig](owasp-top10-2021-apps/a5/misconfig-wordpress)  |
| A5 - セキュリティの設定ミス                | NodeJS         | [Stegonography](owasp-top10-2021-apps/a5/stegonography)                         |
| A6 - 脆弱かつ旧式なコンポーネント      | PHP            | [Cimentech](owasp-top10-2021-apps/a6/cimentech)                                 |
| A6 - 脆弱かつ旧式なコンポーネン       | Python         | [Golden Hat Society](owasp-top10-2021-apps/a6/golden-hat)                       |
| A7 - アイデンティティと認証の失敗     | Python         | [Saidajaula Monster Fit](owasp-top10-2021-apps/a7/saidajaula-monster)           |
| A7 - アイデンティティと認証の失敗     | Golang         | [Insecure go project](owasp-top10-2021-apps/a7/insecure-go-project)             |
| A8 - Software and Data Integrity Failures     | Python         | [Amarelo Designs](owasp-top10-2021-apps/a8/amarelo-designs)                     |
| A9 - Security Logging and Monitoring Failures | Python         | [GamesIrados.com](owasp-top10-2021-apps/a9/games-irados)                        |

## OWASP Top 10 (2016) Mobile apps: 📲

免責事項：あなたのマシンに大きな脆弱性を持つモバイルアプリをインストールしようとしています！ 🔥

| Vulnerability                  | Language     | Application                                         |
| ------------------------------ | ------------ | --------------------------------------------------- |
| M2 - Insecure Data Storage     | Dart/Flutter | [Cool Games](owasp-top10-2016-mobile/m2/cool_games) |
| M4 - Insecure Authentication   | Dart/Flutter | [Note Box](owasp-top10-2016-mobile/m4/note-box)     |
| M5 - Insufficient Cryptography | Dart/Flutter | [Panda Zap](owasp-top10-2016-mobile/m5/panda_zap)   |

## Contributing

We encourage you to contribute to SecDevLabs! Please check out the [Contributing to SecDevLabs](/docs/CONTRIBUTING.md) section for guidelines on how to proceed! 🎉

## License

This project is licensed under the BSD 3-Clause "New" or "Revised" License - read [LICENSE.md](LICENSE.md) file for details. 📖
