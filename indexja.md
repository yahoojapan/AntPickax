---
layout: default
language: ja
title: AntPickax
short_desc: AntPickax provides basic libraries, components and systems
lang_opp_file: index.html
lang_opp_word: To English
title_k2hdkc: <a class="to_git_banner" href="https://github.com/yahoojapan/k2hdkc">k2hdkc</a>
title_k2hftfuse: <a class="to_git_banner" href="https://github.com/yahoojapan/k2hftfuse">k2hftfuse</a>
title_k2hash: <a class="to_git_banner" href="https://github.com/yahoojapan/k2hash">k2hash</a>
title_chmpx: <a class="to_git_banner" href="https://github.com/yahoojapan/chmpx">chmpx</a>
title_k2htpdtor: <a class="to_git_banner" href="https://github.com/yahoojapan/k2htp_dtor">k2htp_dtor</a>
title_fullock: <a class="to_git_banner" href="https://github.com/yahoojapan/fullock">fullock</a>
---

# **AntPickax**
`AntPickax`は、Yahoo! JAPAN がオープンソースとして提供する基礎ライブラリ、コンポーネント、システムのプロダクト群です。  

### **背景**
Yahoo! JAPANでは、多くのオープンソースを利用し、また貢献していますが、次のような背景があり、`AntPickax`の制作を開始しました。
* 自分たちに必要と思われる基本機能が不足している。
* 新しいアーキテクチャーを採用し、運用コストを大幅に削減可能である。
* 性能（主に速度や拡張性）が不足している。
* ライセンス制限があり、自由に導入できない。

作成されたソフトウエアのうち、既存のOSSと比較しても遜色のない性能を持ち、かつ、既存のOSSにない便利な機能を持つソフトウエアを、`AntPickax`プロダクトとしてオープンソースとして公開しています。

### **AntPickax　プロダクト一覧**
`AntPickax`プロダクトの公開しているオープンソースには、以下のものがあります。

- [`k2hdkc`](https://github.com/yahoojapan/k2hdkc/wiki)  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)と[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)をベースに作成された高速でオートスケール可能な分散KVSシステムです。
- [`k2hftfuse`](https://github.com/yahoojapan/k2hftfuse/wiki)  
高速にファイル、テキスト、ログを転送、中継転送、集約できるFUSEベースのコンポーネントです。
- [`k2hash`](https://github.com/yahoojapan/k2hash/wiki)  
高速、大容量で他にない多彩な機能を持つ Key Value Store（KVS）ライブラリです。
- [`chmpx`](https://github.com/yahoojapan/chmpx/wiki)  
クラスタ構築のできる高速な通信ミドルウエアです。
- [`k2htpdtor`](https://github.com/yahoojapan/k2htp_dtor/wiki)  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)ライブラリに組み込むことができるトランザクション処理のプラグインライブラリです。
- [`fullock`](https://github.com/yahoojapan/fullock/wiki)
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki), [`chmpx`](https://github.com/yahoojapan/chmpx/wiki)で利用している高速な排他制御のライブラリです。

# **AntPickax プロダクト**

## {{ page.title_k2hdkc }}
[`k2hdkc`](https://github.com/yahoojapan/k2hdkc/wiki)（**K2H**ash based **D**istributed **K**vs **C**luster）は、**[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)**, **[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)**をベースとした高速で自動化された分散KVS（Distributed Key Value Store）です。  

[`k2hdkc`](https://github.com/yahoojapan/k2hdkc/wiki)は、高可用性でスケーラブルな分散型KVSクラスタリングシステムであり、以下の機能・特徴を備えています。
- **自動マージ**（サーバーノード間の自動データ同期）  
クラスタ内のノード（サーバー）の障害・復旧に伴うデータの自動マージ機能を提供します。
- **自動スケーリング**  
クラスタへノード（サーバー）の追加・削除が可能であり、この際のデータの自動マージ機能も提供します。
- **ネストされたキー構造**  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)の特徴であるキーとサブキーの関連付け機能を分散KVSとして提供します。
- **キュー（FIFO/LIFO）**  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)の特徴であるキュー機能を分散KVSとして提供します。
- **トランザクション**  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)の特徴であるデータ更新処理をトランザクションのトリガとして任意の処理ができる機能を提供します。
- **暗号化**  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)の特徴である保持するデータの値をキー単位で暗号化機能を分散KVSとして提供します。
- **有効時間設定**  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)の特徴であるキーの有効期限機能を分散KVSとして提供します。

詳しくは、[ソースコード](https://github.com/yahoojapan/k2hdkc)、[ドキュメント](https://github.com/yahoojapan/k2hdkc/wiki/Home_jpn) を参照してください。

## {{ page.title_k2hftfuse }}
[`k2hftfuse`](https://github.com/yahoojapan/k2hftfuse/wiki)（**k2h**ash **F**ile **T**ransaction by **FUSE** based file system）とは、[FUSE（Filesystem in Userspace）](https://github.com/libfuse/libfuse) によるユーザースペースでのマウント機能を利用したファイル/メッセージ転送システムです。  

[`k2hftfuse`](https://github.com/yahoojapan/k2hftfuse/wiki)は、**確実**で**高速**なファイル/メッセージ転送を低コストで実現するために開発されたシステムです。
[`k2hftfuse`](https://github.com/yahoojapan/k2hftfuse/wiki)は、仮想ファイルシステムを提供し、マウントしたディレクトリにファイルを書き込むだけで利用でき、ログファイルやデータなどを集約できます。
既存プログラムの出力ファイルのディレクトリを[`k2hftfuse`](https://github.com/yahoojapan/k2hftfuse/wiki)でマウントするだけで、既存プログラムの変更なしにファイル/メッセージ転送ができます。

- **アプリケーションへの追加依存ライブラリはゼロ**
新たにk2hftfuseを使う場合、アプリケーションへのライブラリの依存関係が増えることはありません。OSレベルでサポートされた標準ライブラリを使うためです。
- **高速で確実なデータ転送**
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)と[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)の機能を活用し、高速で確実なデータ転送が可能です。
- **多彩なデータフォーマットを転送可能**
テキストだけではなく、バイナリデータ、メッセージ（1データを1メッセージとする）の転送が可能です。
- **フィルタリング**
転送データに対して、任意の加工処理が可能です。
- **トリガー**
転送データをトリガーにして、任意の処理を実行可能です。

詳しくは、[ソースコード](https://github.com/yahoojapan/k2hftfuse)、[ドキュメント](https://github.com/yahoojapan/k2hftfuse/wiki/Home_jpn) を参照してください。

## {{ page.title_k2hash }}
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)は、NoSQL Key Value Store（KVS）libraryです。  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)は、基本的なKVSの機能と、以下に示す独自の特徴を備えています。

- **高速**  
データへのアクセス（リード、ライト）が高速です。
- **マルチスレッド/マルチプロセス対応**  
マルチプロセス、マルチスレッドに完全対応できています。
- **バイナリデータ**  
キー（Key）、値（Value）は、バイナリ（任意の値）を取り扱いでき、可変長のデータとして取り扱いことができます。
- **自動サイズ拡張/低フラグメント**  
ページングを利用してフラグメントを最低限にします。  
動的にデータ領域（データ、Hashテーブル）の拡張をします。
- **データ保管/マッピングタイプ**  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)は、オンメモリ（揮発性）、永続ファイル（一時ファイル含む）でデータを保管できます。  
永続ファイルの場合、ファイル全体（高速を維持して永続化したデータ）、インデックスのみ（大容量）のマッピング方法を提供します。
- **キーとサブキー**  
キーに対して値を保持するKVSの機能に、キーに対してサブキー（他のキー）をひも付けることができます。
- **トランザクション**  
データ更新処理をトランザクションのトリガとして、独自の処理を呼び出せます。
- **アーカイブ機能**  
データ更新処理を組み込みトランザクション処理として、アーカイブファイルとして出力できます。
- **キュー（FIFO/LIFO）**  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)のデータとして、キュー（FIFO/LIFO）を構成でき、Push/Popができます。
- **属性**  
キーに対して属性（組み込み、カスタマイズ）を設定できます。
- **暗号化**  
保持するデータの値をキー単位で暗号化できます。
- **履歴機能**  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)に保管するキーの更新ごとに、過去の値を履歴として残せます（バージョニング）。
- **有効時間設定**  
キーの有効期限を属性として設定できる機能です。

詳しくは、[ソースコード](https://github.com/yahoojapan/k2hash)、[ドキュメント](https://github.com/yahoojapan/k2hash/wiki/Home_jpn) を参照してください。

## {{ page.title_chmpx }}
[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)（**C**onsistent **H**ashing **M**q in**P**rocess data e**X**change）は、ネットワークをまたぐプロセス間におけるバイナリ通信を行うための通信ミドルウエアです。  

- **基本機能**  
[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)は、サーバープログラムとクライアントプログラム間の通信を受け持ち、各プログラムからネットワーク通信接続を隠蔽（いんぺい）します。
- **クラスタ/多重化/オートスケール**  
[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)は、クラスタ構成を作ることができ、多重化による障害発生時の耐性があり、オートスケール可能な通信ミドルウエアです。
- **通信データ**  
通信するデータ形式は自由であり、バイナリデータ、大容量の通信ができます。
- **通信暗号化**  
SSLでの通信をサポートしています。
- **通信多重化・同時並列処理**  
[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)のサーバーとスレーブ間の通信は、全て多重化可能であり、並列通信が可能です。
- **通信データのキューイング**  
送受信データのキューイングがなされていますので、ある程度の送受信遅延、高負荷にも対応可能です。
- **マルチプロセス・マルチスレッド対応**  
マルチプロセス、マルチスレッドに完全対応できています。

詳しくは、[ソースコード](https://github.com/yahoojapan/chmpx)、[ドキュメント](https://github.com/yahoojapan/chmpx/wiki/Home_jpn) を参照してください。

## {{ page.title_k2htpdtor }}
[`k2htp_dtor`](https://github.com/yahoojapan/k2htp_dtor/wiki)（**k2h**ash **T**ransaction **P**lugin **D**istributed **T**ransaction **O**f **R**epeater）は、**[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)** のトランザクションデータを **[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)** を利用して他ホストへ転送を行い、[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)データの複製を容易に実現します。  
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)ライブラリに対応したYahoo! JAPANの提供する標準トランザクションプラグインであり、トランザクションをトリガとして独自処理のための一般的な手段を提供します。

- **複数プラグイン**
[`k2htpdtor`](https://github.com/yahoojapan/k2htp_dtor/wiki) は、複数のプラグインを連結して使うことができます。あるプラグインが処理した結果を、さらに別にプラグインで処理できます。

詳しくは、[ソースコード](https://github.com/yahoojapan/k2htp_dtor)、[ドキュメント](https://github.com/yahoojapan/k2htp_dtor/wiki/Home_jpn) を参照してください。

## {{ page.title_fullock }}
[`fullock`](https://github.com/yahoojapan/fullock/wiki)（**F**ast **U**ser **L**evel **LOCK** library）は、マルチプロセス、マルチスレッドから安全で、高速なロック機能を提供する低レベルのロックライブラリです。  
このライブラリは、**[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)**, **[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)**など他の`AntPickax`プロダクトでも利用されています。


詳しくは、[ソースコード](https://github.com/yahoojapan/fullock)、[ドキュメント](https://github.com/yahoojapan/fullock/wiki/Home_jpn) を参照してください。
