# MinecractServer
## 概要
自宅PCを利用してUbuntu上にゲームサーバーを構築し、MariaDBでプレイヤーデータを管理した。
また、AWS EC2上にも同様の環境を構築し、オンプレミスとクラウド双方での運用を経験した。

## 構成
- OS: Ubuntu
- DB: MariaDB
- DB管理: phpMyAdmin
- Minecraftサーバーソフトウェア: paper (https://github.com/papermc/paper)
- proxyサーバーソフトウェア: bungeecord (https://github.com/SpigotMC/BungeeCord)
- クラウド: AWS EC2
- 停電対策: UPS
- 用途: ゲームサーバー運用、プレイヤーデータ管理

## 工夫した点
- 余剰PC部品と中古部品を利用して低コストで構築
- MariaDBでプレイヤーデータを管理
- phpMyAdminでデータ確認・管理
- UPS導入により突然の電源断によるデータ破損リスクを軽減
- AWS EC2上にも同様の環境を構築し、クラウド運用を経験
- 短期間、友人から月額料金を受け取って運営

## 学んだこと
- Linuxサーバー構築
- DB設計・運用
- バックアップの重要性
- オンプレミスとクラウドの違い
- ポートフォワードの設定
- DNSの設定
- 利用条件、料金、税金など技術外の責任
