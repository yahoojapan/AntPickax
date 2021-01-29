---
layout: default
language: ja
title: AntPickax
short_desc: AntPickax provides basic libraries, components and systems
lang_opp_file: index.html
lang_opp_word: To English
title_k2hdkc_dbaas: <a class="to_antpickax_banner" href="https://dbaas.k2hdkc.antpick.ax/indexja.html">k2hdkc dbaas</a>
title_k2hr3: <a class="to_antpickax_banner" href="https://k2hr3.antpick.ax/indexja.html">k2hr3</a>
title_k2hdkc: <a class="to_antpickax_banner" href="https://k2hdkc.antpick.ax/indexja.html">k2hdkc</a>
title_k2hdkc_nodejs: <a class="to_antpickax_banner" href="https://nodejs.k2hdkc.antpick.ax/indexja.html">k2hdkc nodejs addon</a>
title_k2hdkc_java: <a class="to_antpickax_banner" href="https://java.k2hdkc.antpick.ax/">java driver for k2hdkc</a>
title_k2hdkc_go: <a class="to_antpickax_banner" href="https://pkg.go.dev/github.com/yahoojapan/k2hdkc_go/k2hdkc">k2hdkc golang</a>
title_k2hftfuse: <a class="to_antpickax_banner" href="https://k2hftfuse.antpick.ax/indexja.html">k2hftfuse</a>
title_k2hash: <a class="to_antpickax_banner" href="https://k2hash.antpick.ax/indexja.html">k2hash</a>
title_k2hash_nodejs: <a class="to_antpickax_banner" href="https://nodejs.k2hash.antpick.ax/indexja.html">k2hash nodejs addon</a>
title_k2hash_go: <a class="to_antpickax_banner" href="https://pkg.go.dev/github.com/yahoojapan/k2hash_go/k2hash">k2hash golang</a>
title_chmpx: <a class="to_antpickax_banner" href="https://chmpx.antpick.ax/indexja.html">chmpx</a>
title_chmpx_nodejs: <a class="to_antpickax_banner" href="https://nodejs.chmpx.antpick.ax/indexja.html">chmpx nodejs addon</a>
title_k2htpdtor: <a class="to_antpickax_banner" href="https://k2htpdtor.antpick.ax/indexja.html">k2htp_dtor</a>
title_k2htpmdtor: <a class="to_antpickax_banner" href="https://k2htpmdtor.antpick.ax/indexja.html">k2htp_mdtor</a>
title_fullock: <a class="to_antpickax_banner" href="https://fullock.antpick.ax/indexja.html">fullock</a>
antpickax_icon: <span class="antpickax-icon-font-icon"></span>
github_icon: <span class="to_git_icon"></span>
---

# **AntPickax**
**AntPickax** は、Yahoo! JAPAN がオープンソースとして提供する基礎ライブラリ、コンポーネント、システムのプロダクト群です。  

### **背景**
Yahoo! JAPANでは、多くのオープンソースを利用し、また貢献していますが、次のような背景があり、**AntPickax** の制作を開始しました。
* 自分たちに必要と思われる基本機能が不足している。
* 新しいアーキテクチャーを採用し、運用コストを大幅に削減可能である。
* 性能（主に速度や拡張性）が不足している。
* ライセンス制限があり、自由に導入できない。

作成されたソフトウエアのうち、既存のOSSと比較しても遜色のない性能を持ち、かつ、既存のOSSにない便利な機能を持つソフトウエアを、**AntPickax** プロダクトとしてオープンソースとして公開しています。

### **AntPickax プロダクト一覧**

![AntPickax Products](images/top_antpickax.png)

**AntPickax**は、以下のプロダクトをオープンソースとして公開しています。

#### [**K2HDKC DBaaS**](https://dbaas.k2hdkc.antpick.ax/indexja.html)
[Trove(Trove is Database as a Service for OpenStack)](https://wiki.openstack.org/wiki/Trove) にDatabaseのひとつとして [K2HDKC](https://k2hdkc.antpick.ax/indexja.html) を利用できるようにした、**Database as a Service**です。  
#### [**K2HR3**](https://k2hr3.antpick.ax/indexja.html)
**IaaS**（Infrastructure as a Service）に対応した **RBAC** (**R**ole **B**ased **A**ccess **C**ontrol) を提供するシステムです。
#### [**K2HDKC**](https://k2hdkc.antpick.ax/indexja.html)
[**K2HASH**](https://k2hash.antpick.ax/indexja.html)と[**CHMPX**](https://chmpx.antpick.ax/indexja.html)をベースに作成された高速でオートスケール可能な分散KVSシステムです。
#### [**K2HFTFUSE**](https://k2hftfuse.antpick.ax/indexja.html)
高速にファイル、テキスト、ログを転送、中継転送、集約できるFUSEベースのコンポーネントです。
#### [**CHMPX**](https://chmpx.antpick.ax/indexja.html)  
クラスタ構築のできる高速な通信ミドルウエアです。
#### [**K2HASH**](https://k2hash.antpick.ax/indexja.html)  
高速、大容量で他にない多彩な機能を持つ Key Value Store（KVS）ライブラリです。
#### [**FULLOCK**](https://fullock.antpick.ax/indexja.html)  
[**K2HASH**](https://k2hash.antpick.ax/indexja.html), [**CHMPX**](https://chmpx.antpick.ax/indexja.html)で利用している高速な排他制御のライブラリです。

# **AntPickax プロダクト**

## {{ page.title_k2hdkc_dbaas }}

[**K2HDKC DBaaS** (Database as a Service for K2HDKC)](https://dbaas.k2hdkc.antpick.ax/indexja.html) は、[Trove(Trove is Database as a Service for OpenStack)](https://wiki.openstack.org/wiki/Trove) にDatabaseのひとつとして 分散KVSである [K2HDKC](https://k2hdkc.antpick.ax/indexja.html) を利用できるようにした、**Database as a Service**です。  
[**K2HDKC DBaaS**](https://dbaas.k2hdkc.antpick.ax/indexja.html) は、**Database as a Service**として、[K2HDKC](https://k2hdkc.antpick.ax/indexja.html)クラスターの構築およびスケール、データマージなどを自動化します。

[**K2HDKC DBaaS**](https://dbaas.k2hdkc.antpick.ax/indexja.html) は、[Trove](https://wiki.openstack.org/wiki/Trove)および、Yahoo! JAPANが公開している [**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)、[**k2hr3**](https://k2hr3.antpick.ax/indexja.html)、[**chmpx**](https://chmpx.antpick.ax/indexja.html) 等を使って構築されています。

詳しくは、以下の詳細を参照してください。  
- **k2hdkc dbaas全体** - {{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hdkc_dbaas)、{{ page.antpickax_icon }}[**ドキュメント**](https://dbaas.k2hdkc.antpick.ax/indexja.html)

- **環境** - {{ page.antpickax_icon }}[**環境構築**](https://dbaas.k2hdkc.antpick.ax/buildja.html)

- **操作方法** - {{ page.github_icon }}[**使い方**](https://dbaas.k2hdkc.antpick.ax/usageja.html)

- **ユーティリティ k2hdkc_dbaas_override_conf** - {{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf)

## {{ page.title_k2hr3 }}
[**k2hr3**](https://k2hr3.antpick.ax/indexja.html) (**K2H**dkc based **R**esource and **R**oles and policy **R**ules) は、Yahoo! JAPANオリジナルが公開する **RBAC** (**R**ole **B**ased **A**ccess **C**ontrol) システムのひとつです。  
[**k2hr3**](https://k2hr3.antpick.ax/indexja.html) は、**RBAC** としての機能を、**IaaS**（Infrastructure as a Service）である **OpenStack** と連携して動作し、また **RBAC** を利用する上で便利な **+SERVICE機能** を提供します。  

[**k2hr3**](https://k2hr3.antpick.ax/indexja.html) は、Yahoo! JAPANが公開している [**k2hash**](https://k2hash.antpick.ax/indexja.html)、[**k2htp_dtor**](https://k2htpdtor.antpick.ax/indexja.html)、[**chmpx**](https://chmpx.antpick.ax/indexja.html)、[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html) 等を使って構築されています。
[**k2hr3**](https://k2hr3.antpick.ax/indexja.html) は、以下のコンポネーントにより構成されています。  

詳しくは、以下の詳細を参照してください。  
- **k2hr3全体** - {{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hr3)、{{ page.antpickax_icon }}[**ドキュメント**](https://k2hr3.antpick.ax/indexja.html)

- **Web Application** - {{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hr3_app)、{{ page.antpickax_icon }}[**デモンストレーション**](https://demo.k2hr3.antpick.ax/indexja.html)

- **REST API** - {{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hr3_api)

- **OpenStack Notification Listener** - {{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hr3_osnl)

- **Utilities** - {{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hr3_utils)

- **Container Registration Sidecar** - {{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hr3_sidecar)

- **K2HR3 Get Resource** - {{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hr3_get_resource)

## {{ page.title_k2hdkc }}
[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)（**K2H**ash based **D**istributed **K**vs **C**luster）は、[**k2hash**](https://k2hash.antpick.ax/indexja.html), [**chmpx**](https://chmpx.antpick.ax/indexja.html)をベースとした高速で自動化された分散KVS（Distributed Key Value Store）です。  

[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)は、高可用性でスケーラブルな分散型KVSクラスタリングシステムであり、以下の機能・特徴を備えています。
- **自動マージ** （サーバーノード間の自動データ同期）  
クラスタ内のノード（サーバー）の障害・復旧に伴うデータの自動マージ機能を提供します。
- **自動スケーリング**  
クラスタへノード（サーバー）の追加・削除が可能であり、この際のデータの自動マージ機能も提供します。
- **ネストされたキー構造**  
[**k2hash**](https://k2hash.antpick.ax/indexja.html)の特徴であるキーとサブキーの関連付け機能を分散KVSとして提供します。
- **キュー（FIFO/LIFO）**  
[**k2hash**](https://k2hash.antpick.ax/indexja.html)の特徴であるキュー機能を分散KVSとして提供します。
- **トランザクション**  
[**k2hash**](https://k2hash.antpick.ax/indexja.html)の特徴であるデータ更新処理をトランザクションのトリガとして任意の処理ができる機能を提供します。
- **暗号化**  
[**k2hash**](https://k2hash.antpick.ax/indexja.html)の特徴である保持するデータの値をキー単位で暗号化機能を分散KVSとして提供します。
- **有効時間設定**  
[**k2hash**](https://k2hash.antpick.ax/indexja.html)の特徴であるキーの有効期限機能を分散KVSとして提供します。

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hdkc)、{{ page.antpickax_icon }}[**ドキュメント**](https://k2hdkc.antpick.ax/indexja.html) を参照してください。

## {{ page.title_k2hdkc_nodejs }}
[**k2hdkc nodejs addon**](https://nodejs.k2hdkc.antpick.ax/indexja.html)（**K2HDKC** nodejs addon - k2hash based distributed kvs cluster)は、[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)のNode.js addonライブラリです。  
このライブラリを利用して、[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)のスレーブ側クライアントアプリケーションを、Node.jsベースのJavaScriptで実装することができます。  
[**k2hdkc nodejs addon**](https://nodejs.k2hdkc.antpick.ax/indexja.html)は、[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)の分散KVSのスレーブ側クライアントに必要なすべての機能・特徴を提供します。  

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hdkc_nodejs)、{{ page.antpickax_icon }}[**ドキュメント**](https://nodejs.k2hdkc.antpick.ax/indexja.html) を参照してください。

## {{ page.title_k2hdkc_java }}
[**K2HDKC Java ドライバ**](https://java.k2hdkc.antpick.ax/index.html)（**K2HDKC** Java ドライバ)は、[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)のJavaクライアントライブラリです。  
このライブラリを利用して、[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)のスレーブ側クライアントアプリケーションを、Javaで実装することができます。  
[**k2hdkc Java ドライバ**](https://java.k2hdkc.antpick.ax/index.html)は、[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)の分散KVSのスレーブ側クライアントに必要なすべての機能・特徴を提供します。  

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hdkc_java)、{{ page.antpickax_icon }}[**プロジェクトのドキュメント**](https://java.k2hdkc.antpick.ax/index.html) を参照してください。

## {{ page.title_k2hdkc_go }}
[**k2hdkc golang**](https://pkg.go.dev/github.com/yahoojapan/k2hdkc_go/k2hdkc)（**K2HDKC** golang - k2hash based distributed kvs cluster)は、[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)のGo言語クライアントライブラリです。  
このライブラリを利用して、[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)のスレーブ側クライアントアプリケーションを、Go言語で実装できます。  
[**k2hdkc golang**](https://pkg.go.dev/github.com/yahoojapan/k2hdkc_go/k2hdkc)は、[**k2hdkc**](https://k2hdkc.antpick.ax/indexja.html)の分散KVSのスレーブ側クライアントに必要なすべての機能・特徴を提供します。  

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hdkc_go)、{{ page.antpickax_icon }}[**ドキュメント**](https://pkg.go.dev/github.com/yahoojapan/k2hdkc_go/k2hdkc) を参照してください。

## {{ page.title_k2hftfuse }}
[**k2hftfuse**](https://k2hftfuse.antpick.ax/indexja.html)（**k2h**ash **F**ile **T**ransaction by **FUSE** based file system）とは、[FUSE（Filesystem in Userspace）](https://github.com/libfuse/libfuse) によるユーザースペースでのマウント機能を利用したファイル/メッセージ転送システムです。  

[**k2hftfuse**](https://k2hftfuse.antpick.ax/indexja.html)は、 **確実** で **高速** なファイル/メッセージ転送を低コストで実現するために開発されたシステムです。
[**k2hftfuse**](https://k2hftfuse.antpick.ax/indexja.html)は、仮想ファイルシステムを提供し、マウントしたディレクトリにファイルを書き込むだけで利用でき、ログファイルやデータなどを集約できます。
既存プログラムの出力ファイルのディレクトリを[**k2hftfuse**](https://k2hftfuse.antpick.ax/indexja.html)でマウントするだけで、既存プログラムの変更なしにファイル/メッセージ転送ができます。

- **アプリケーションへの追加依存ライブラリはゼロ**  
新たにk2hftfuseを使う場合、アプリケーションへのライブラリの依存関係が増えることはありません。OSレベルでサポートされた標準ライブラリを使うためです。
- **高速で確実なデータ転送**  
[**k2hash**](https://k2hash.antpick.ax/indexja.html)と[**chmpx**](https://chmpx.antpick.ax/indexja.html)の機能を活用し、高速で確実なデータ転送が可能です。
- **多彩なデータフォーマットを転送可能**  
テキストだけではなく、バイナリデータ、メッセージ（1データを1メッセージとする）の転送が可能です。
- **フィルタリング**  
転送データに対して、任意の加工処理が可能です。
- **トリガー**  
転送データをトリガーにして、任意の処理を実行可能です。

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hftfuse)、{{ page.antpickax_icon }}[**ドキュメント**](https://k2hftfuse.antpick.ax/indexja.html) を参照してください。

## {{ page.title_chmpx }}
[**chmpx**](https://chmpx.antpick.ax/indexja.html)（**C**onsistent **H**ashing **M**q in**P**rocess data e**X**change）は、ネットワークをまたぐプロセス間におけるバイナリ通信を行うための通信ミドルウエアです。  

- **基本機能**  
[**chmpx**](https://chmpx.antpick.ax/indexja.html)は、サーバープログラムとクライアントプログラム間の通信を受け持ち、各プログラムからネットワーク通信接続を隠蔽（いんぺい）します。
- **クラスタ/多重化/オートスケール**  
[**chmpx**](https://chmpx.antpick.ax/indexja.html)は、クラスタ構成を作ることができ、多重化による障害発生時の耐性があり、オートスケール可能な通信ミドルウエアです。
- **通信データ**  
通信するデータ形式は自由であり、バイナリデータ、大容量の通信ができます。
- **通信暗号化**  
SSLでの通信をサポートしています。
- **通信多重化・同時並列処理**  
[**chmpx**](https://chmpx.antpick.ax/indexja.html)のサーバーとスレーブ間の通信は、全て多重化可能であり、並列通信が可能です。
- **通信データのキューイング**  
送受信データのキューイングがなされていますので、ある程度の送受信遅延、高負荷にも対応可能です。
- **マルチプロセス・マルチスレッド対応**  
マルチプロセス、マルチスレッドに完全対応できています。

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/chmpx)、{{ page.antpickax_icon }}[**ドキュメント**](https://chmpx.antpick.ax/indexja.html) を参照してください。

## {{ page.title_chmpx_nodejs }}
[**chmpx nodejs addon**](https://nodejs.chmpx.antpick.ax/indexja.html)（**CHMPX** nodejs addon - Consistent Hashing Mq inProcess data eXchange)は、[**chmpx**](https://chmpx.antpick.ax/indexja.html)のNode.js addonライブラリです。  
このライブラリを利用して、[**chmpx**](https://chmpx.antpick.ax/indexja.html)を使った通信プログラムのサーバ側、スレーブ側の両方をNode.jsベースのJavaScriptのプログラムで実装できます。  
[**chmpx nodejs addon**](https://nodejs.chmpx.antpick.ax/indexja.html)は、[**chmpx**](https://chmpx.antpick.ax/indexja.html)のすべての機能・特徴を提供します。  

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/chmpx_nodejs)、{{ page.antpickax_icon }}[**ドキュメント**](https://nodejs.chmpx.antpick.ax/indexja.html) を参照してください。

## {{ page.title_k2hash }}
[**k2hash**](https://k2hash.antpick.ax/indexja.html)は、NoSQL Key Value Store（KVS）libraryです。  
[**k2hash**](https://k2hash.antpick.ax/indexja.html)は、基本的なKVSの機能と、以下に示す独自の特徴を備えています。

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
[**k2hash**](https://k2hash.antpick.ax/indexja.html)は、オンメモリ（揮発性）、永続ファイル（一時ファイル含む）でデータを保管できます。  
永続ファイルの場合、ファイル全体（高速を維持して永続化したデータ）、インデックスのみ（大容量）のマッピング方法を提供します。
- **キーとサブキー**  
キーに対して値を保持するKVSの機能に、キーに対してサブキー（他のキー）をひも付けることができます。
- **トランザクション**  
データ更新処理をトランザクションのトリガとして、独自の処理を呼び出せます。
- **アーカイブ機能**  
データ更新処理を組み込みトランザクション処理として、アーカイブファイルとして出力できます。
- **キュー（FIFO/LIFO）**  
[**k2hash**](https://k2hash.antpick.ax/indexja.html)のデータとして、キュー（FIFO/LIFO）を構成でき、Push/Popができます。
- **属性**  
キーに対して属性（組み込み、カスタマイズ）を設定できます。
- **暗号化**  
保持するデータの値をキー単位で暗号化できます。
- **履歴機能**  
[**k2hash**](https://k2hash.antpick.ax/indexja.html)に保管するキーの更新ごとに、過去の値を履歴として残せます（バージョニング）。
- **有効時間設定**  
キーの有効期限を属性として設定できる機能です。

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hash)、{{ page.antpickax_icon }}[**ドキュメント**](https://k2hash.antpick.ax/indexja.html) を参照してください。

## {{ page.title_k2hash_nodejs }}
[**k2hash nodejs addon**](https://nodejs.k2hash.antpick.ax/indexja.html)（**K2HASH** nodejs addon - NoSQL Key Value Store(KVS) nodejs library)は、[**k2hash**](https://k2hash.antpick.ax/indexja.html)のNode.js addonライブラリです。  
このライブラリを利用して、[**k2hash**](https://k2hash.antpick.ax/indexja.html)をNode.jsベースのJavaScriptのプログラムから操作できます。  
[**k2hash nodejs addon**](https://nodejs.k2hash.antpick.ax/indexja.html)は、[**k2hash**](https://k2hash.antpick.ax/indexja.html)のすべての機能・特徴を提供します。  

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hash_nodejs)、{{ page.antpickax_icon }}[**ドキュメント**](https://nodejs.k2hash.antpick.ax/indexja.html) を参照してください。

## {{ page.title_k2hash_go }}
[**k2hash golang**](https://pkg.go.dev/github.com/yahoojapan/k2hash_go/k2hash)（**K2HASH** golang - NoSQL Key Value Store(KVS) nodejs library)は、[**k2hash**](https://k2hash.antpick.ax/indexja.html)のGo言語クライアントライブラリです。  
このライブラリを利用して、[**k2hash**](https://k2hash.antpick.ax/indexja.html)を操作するプログラムをGo言語で実装できます。  
[**k2hash golang**](https://pkg.go.dev/github.com/yahoojapan/k2hash_go/k2hash)は、[**k2hash**](https://k2hash.antpick.ax/indexja.html)のすべての機能・特徴を提供します。  

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2hash_go)、{{ page.antpickax_icon }}[**ドキュメント**](https://pkg.go.dev/github.com/yahoojapan/k2hash_go/k2hash) を参照してください。

## {{ page.title_k2htpdtor }}
[**k2htp_dtor**](https://k2htpdtor.antpick.ax/indexja.html)（**k2h**ash **T**ransaction **P**lugin **D**istributed **T**ransaction **O**f **R**epeater）は、[**k2hash**](https://k2hash.antpick.ax/indexja.html) のトランザクションデータを [**chmpx**](https://chmpx.antpick.ax/indexja.html) を利用して他ホストへ転送を行い、[**k2hash**](https://k2hash.antpick.ax/indexja.html)データの複製を容易に実現します。  
[**k2hash**](https://k2hash.antpick.ax/indexja.html)ライブラリに対応したYahoo! JAPANの提供する標準トランザクションプラグインであり、トランザクションをトリガとして独自処理のための一般的な手段を提供します。

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2htp_dtor)、{{ page.antpickax_icon }}[**ドキュメント**](https://k2htpdtor.antpick.ax/indexja.html) を参照してください。

## {{ page.title_k2htpmdtor }}
[**k2htp_mdtor**](https://k2htpmdtor.antpick.ax/indexja.html)（**k2h**ash **T**ransaction **P**lugin **M**ultiple **D**istributed **T**ransaction **O**f **R** epeater）は、[**chmpx**](https://chmpx.antpick.ax/indexja.html)を使用して[**k2hash**](https://k2hash.antpick.ax/indexja.html)のトランザクションデータを別のホストに転送することによって、[**k2hash**](https://k2hash.antpick.ax/indexja.html)データを簡単に複製します。

複数の[**k2hash**](https://k2hash.antpick.ax/indexja.html)トランザクションプラグインをロードするk2htp_mdtorの主な目的は、それらに定義されている任意の関数を呼び出すことです。 各関数を呼び出すとき、k2htp_mdtorは[**k2hash**](https://k2hash.antpick.ax/indexja.html)トランザクションログを関数のパラメータとして渡します。 一般的な[**k2hash**](https://k2hash.antpick.ax/indexja.html)トランザクションプラグインは他のものをロードしません。 複数の[**k2hash**](https://k2hash.antpick.ax/indexja.html)トランザクションプラグインを使用したい場合は、[**k2htp_mdtor**](https://k2htpmdtor.antpick.ax/indexja.html)を使用することをお勧めします。

詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/k2htp_mdtor)、{{ page.antpickax_icon }}[**ドキュメント**](https://k2htpmdtor.antpick.ax/indexja.html) を参照してください。

## {{ page.title_fullock }}
[**fullock**](https://fullock.antpick.ax/indexja.html)（**F**ast **U**ser **L**evel **LOCK** library）は、マルチプロセス、マルチスレッドから安全で、高速なロック機能を提供する低レベルのロックライブラリです。  
このライブラリは、[**k2hash**](https://k2hash.antpick.ax/indexja.html), [**chmpx**](https://chmpx.antpick.ax/indexja.html)など他の **AntPickax** プロダクトでも利用されています。


詳しくは、{{ page.github_icon }}[**ソースコード**](https://github.com/yahoojapan/fullock)、{{ page.antpickax_icon }}[**ドキュメント**](https://fullock.antpick.ax/indexja.html) を参照してください。
