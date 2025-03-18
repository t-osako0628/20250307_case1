---
output:
  word_document:
    # reference_blue.docx の配置パスに変更
    reference_doc: C:\\path\\to\\reference_blue.docx
title: 性能調査報告書
subtitle: 
author: 株式会社スマートスタイル
date: 2025/03/03
abstract:
puppeteer:
  # 横長のPDFの場合はtrueに設定 ※style-landscape.lessをimportするように変更すること
  landscape: false
  margin:
    top: 60px
    bottom: 38px
    left: 20px
    right: 20px
  displayHeaderFooter: true
  headerTemplate: "<div style=\"margin: 0; text-align: left;\"> <img alt=\"header logo\" width=\"87\" height=\"21\" src=\"data:image/png;base64,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\" /> </div>"
  footerTemplate: "<div style=\"font-size: 9px; margin: 0 auto;\"> <span class='pageNumber'></span> / <span class='totalPages'></span></div>"
---

大日本印刷株式会社蕨工場様<br> BCP環境PoC評価報告書
======

<!-- landscape: trueの場合は style-landscape.lessを使用 -->
<!-- style.lessは本ファイルからの相対パスで指定 -->

@import "../../style.less"

<div class="author-info">
  <div>
    <div> Author: </div>
    <div> 株式会社スマートスタイル</div>
  </div>
  <div>
    <div> Mail: </div>
    <div> sales@s-style.co.jp </div>
  </div>
  <div>
    <div> Date: </div>
    <div> 2025-03-07 </div>
  </div>
</div>

<!-- omit in toc -->
## 目次  {ignore=true}

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=4 orderedList=true} -->

<!-- code_chunk_output -->

1. [はじめに](#はじめに)
2. [PoC 環境と評価対象](#poc-環境と評価対象)
3. [ベンチマーク使用データ](#ベンチマーク使用データ)
4. [PoC 評価](#poc-評価)
    1. [分析概要](#分析概要)
        1. [2025/02/03 午前中ワークロード](#20250203-午前中ワークロード)
        2. [2025/02/03 14:00 ～ 14:30 wdc_user 大量データ登録処理ワークロード](#20250203-1400---1430-wdc_user-大量データ登録処理ワークロード)
        3. [ディスクI/O性能](#ディスクio性能)
        4. [データベース接続数の状況](#データベース接続数の状況)
5. [MySQL収集ログ情報の詳細](#mysql収集ログ情報の詳細)
    1. [システムリソース使用状況](#システムリソース使用状況)
        1. [全体の負荷状況](#全体の負荷状況)
        2. [CPU](#cpu)
        3. [CPU (コア毎)](#cpu-コア毎)
        4. [ディスク使用状況](#ディスク使用状況)
        5. [メモリ使用状況](#メモリ使用状況)
        6. [ネットワーク使用状況](#ネットワーク使用状況)
    2. [MySQLの内部ステータス状況](#mysqlの内部ステータス状況)
        1. [接続状況](#接続状況)
        2. [クエリ実行状況](#クエリ実行状況)
        3. [内部処理待ち発生状況](#内部処理待ち発生状況)
        4. [バッファ・キャッシュ使用状況](#バッファキャッシュ使用状況)
        5. [インデックス使用状況](#インデックス使用状況)
        6. [一時テーブル作成状況](#一時テーブル作成状況)
    3. [MySQL関連ログ](#mysql関連ログ)
        1. [スロークエリログ](#スロークエリログ)
        2. [エラーログ](#エラーログ)
6. [Appendix A 用語集](#appendix-a-用語集)

<!-- /code_chunk_output -->


## はじめに

本報告書は、大日本印刷株式会社蕨工場様 BCP環境 PoC プロジェクトにおける、ベンチマーク結果のパフォーマンス分析と評価、および改善施策について報告するものです。

## PoC 環境と評価対象

| ホスト名     | qmsLibraPoC-MySQLReplica01     | qmsLibraPoC-MySQLReadReplica01 | qmsLibraPoC-MySQLRouter01                                                        | qmsLibraPoC-Benchmark01                          |
|----------|--------------------------------|--------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------|
| 役割       | レプリケーションソースDB                  | レプリカDB                         | DBプロキシ                                                                           | ベンチマーク実行クライアント                                   |
| vCPU     | 10                             | 8                              | 6                                                                                | 8                                                |
| Memory   | 60                             | 60                             | 6                                                                                | 23                                               |
| Disk     | HDD 1.5T                       | HDD 1.5T                       | 30G                                                                              | 100G                                             |
| S/W Ver. | MySQL Enterprise Server 8.0.27 | MySQL Enterprise Server 8.0.27 | MySQL Router 8.4.3 Commercial Edition (ベンチマーク1回目)<br/>ProxySQL 2.7.2 (ベンチマーク2回目) | sql-replay  v0.3.4<br/>(更に一部不具合を修正した独自コンパイル版を使用) |


![](images/env.png)


## ベンチマーク使用データ

2025/02/03 AM 8:30 に本番環境 InnoDB レプリカ(`qmsLibra-MySQLBACK01`) から取得したデータを使用しました。


| スキーマ            | サイズ(MB)  |
|-----------------|----------|
| qms             | 410097.1 |
| diins           | 2305.5   |
| matching2       | 2744.4   |
| mez             | 66.9     |
| usermaintenance | 0.4      |

**合計: 405.5 GB**


## PoC 評価

今回の PoC において、BCP 環境に求める性能指標は、**「本番環境と同等」** です。

これに対して、ベンチマーク実行した結果から判断できる性能評価としては、**「本番環境と同等の性能に達していない」** と結論付けます。

現状、本番環境と同等のワークロードを PoC 環境で実行すると「全体的なトランザクションレスポンスの遅延」を感じることになる可能性が高いです。
最大でおよそ本番環境の1/2程度のスループット低下に陥っているように見受けられます。

PoC 環境が本番 NDB Cluster と決定的に異なる(パフォーマンス影響のある)のは、データアクセス、特に書込み処理の速度の違いです。

NDB Cluster はそのシステムアーキテクチャ上、DB内のデータ変更の際はメモリアクセスが主体となります。

一方 InnoDB (ストレージエンジン)では、バッファープール(メモリ)に対するデータ変更は高速ですが、バッファプールにキャッシュされていないデータへのアクセスや、バッファプール内の変更データ(ダーティページ)をディスクへ同期(フラッシュ)する際に、必ずディスクアクセスが生じます。

今回の PoC 環境で InnoDB ReplicaSet の MySQL 用(データディレクトリ、各種ログ)ディスクは **HDD** を使用しています。

データベースへのデータアクセスは、ランダムアクセスとなります。
HDDへのランダムアクセスはシーク待ち時間や回転待ち時間のコストが極めて高く、1回あたり1～5ms級の時間を要すため、HDD1本あたりのランダムIOPSは数百程度にしかなりません。

メモリとHDDでは、100倍くらいの差は簡単に発生してしまいます。

お客様のシステムでは、瞬間的な同時書込みの処理速度が現行本番環境 NDB Cluster では高パフォーマンスを出しており、InnoDB + HDD でそれ同等に実現するには、以下のような施策が必要となってきます。

- データベースの全データをキャッシュすることが可能なメモリをDBサーバに搭載する。
- 高速な SSD を使用する。かつ、データベースファイルとログ(REDO,バイナリログ)の配置を分散し、I/O 競合を減らす。

※MySQL InnoDB の幾つかのパラメータでI/Oの最適化を行うことも可能ですが、今回は事前にある程度想定されるチューニングは行っているため、あまり変更の余地はなく、また(そこをチューニングしたとしても)過度の期待は難しいのではと考えます。

!!!note
    なお、今回は ディスク I/O がボトルネックでサーバリソースが飽和状態になっているということではありません。

<div style="page-break-before:always"></div>

### 分析概要

#### 2025/02/03 午前中ワークロード

**データベーストランザクション処理状況(TPS)比較**

![](images/diff-tps_0203-0225.png)

#### 2025/02/03 14:00 ～ 14:30 wdc_user 大量データ登録処理ワークロード

**データベーストランザクション処理状況(TPS)比較**

本番 NDB Cluster では 18分で完了するデータ登録処理が、InnoDB では 倍以上の 39分を要していることが分かります。

![](images/diff-tps-wdc_user-data-import_0203-0225.png)

#### ディスクI/O性能

特に書込みの await(デバイスへのI/Oリクエストの平均待ち時間) に着目すると、平均して1ミリ秒程度掛かっています。
最近の SSD の例では 0.02ミリ秒程度が妥当な速度ですので、根本的なディスク自体の性能差が顕著となります。

[qmsLibraPoC-MySQLReplica01: Read IOPS および await]
![](images/replicaset-io-read.png)

[qmsLibraPoC-MySQLReplica01: Write IOPS および await]
![](images/replicaset-io-write.png)


#### データベース接続数の状況

**現行 HAProxy～NDB Cluster SQL ノード**

現行環境では HAProxy 3台分合計のクライアント接続数がそのままデータベース接続数になります。
(HAProxyは 複数台の SQL ノードに分散接続を行っていますが、コネクションプーリングは使用していません)

![](images/2025-02-03-現行-HAProxyクライアント接続数.jpg)
![](images/2025-02-03-現行-DB接続数.jpg)

**PoC環境 ProxySQL～InnoDB ReplicaSet**

下グラフから、ProxySQL はクライアント接続(薄緑線)に対して少ないバックエンドDB接続(黄色線)でプロキシしていることが分かります。
ProxySQL がクライアントとの接続を多重化し、コネクションプールを使用することで、少ないバックエンドDBへの接続数で処理をさばくことができています。

![](images/2025-02-25-ベンチマークテスト-2回目-DB接続数.jpg)


!!!note
    なお、今回のベンチマーク実行において、DBプロキシ用のサーバリソースはCPU・メモリともに使用率には余裕がありました。
    データベース側の性能が向上する(高速にレスポンスされる)ようになると、もう少しDBプロキシ側のリソースも使われるようになることが想定されるため、再度キャパシティ面で確認する必要はあります。

## MySQL収集ログ情報の詳細

60秒間隔で取得した以下の情報を可視化しています。

1. OSのリソース使用状況
   1. 全体の負荷状況  
       `/proc/loadavg`から取得
   2. CPU使用状況  
       コマンド`mpstat`で取得
   3. ディスク使用状況  
       コマンド`iostat`で取得
   4. メモリ使用状況  
       コマンド`vmstat`で取得
   5. ネットワーク使用状況  
       コマンド`netstat`で取得

2. MySQLの内部状況
   1. 接続状況
   2. クエリ実行状況
   3. 内部処理待ち発生状況
   4. バッファ・キャッシュ使用状況
   5. インデックス使用状況
   6. 一時テーブル作成状況
   7. InnoDB内部処理状況

  - ※以下の各コマンドで取得
    - `SHOW GLOBAL STATUS`
    - `SHOW ENGINE INNODB STATUS`
    - `SHOW SLAVE STATUS`

3. MySQL関連ログ
   1. スロークエリログ
   2. エラーログ


<div style="page-break-before:always"></div>

### システムリソース使用状況

ここではRDSインスタンスのシステムリソース(CPU、メモリ、ディスク、ネットワーク)について解析結果、およびその結果から判断できる内容について説明します。

#### 全体の負荷状況
**・ロードアベレージ**


* qmsLibraPoC-MySQLReplica01
![](images/log-scripts/Replica01/graph/loadavg.png)

* qmsLibraPoC-MySQLReadReplica01
![](images/log-scripts/ReadReplica01/graph/loadavg.png)


!!!note
    1分間のロードアベレージをグラフ化したものです。  
    ロードアベレージとは特定の条件を満たすプロセス数を表し、サーバの負荷状況を把握する指標として用います。特定の条件を満たすプロセスとは、実行可能でCPU割当てやディスクI/Oの待機が発生しているプロセスです。処理するプロセスが多すぎる、ディスクI/O待ちが大量に発生しているなど複数の要因によって値が変動します。  
    ロードアベレージではCPU数は考慮されていません。ディスクI/O待ちがなく複数のCPUがほぼ均等に利用されている環境では、CPU数で割った値が1前後であれば、待機しているプロセスは殆どないと判断できます。

#### CPU

**・CPU使用状況**

**・CPU使用状況 (全体)**

* qmsLibraPoC-MySQLReplica01
![](images/log-scripts/Replica01/graph/cpu_all.png)

* qmsLibraPoC-MySQLReadReplica01
![](images/log-scripts/ReadReplica01/graph/cpu_all.png)

!!!note
    全てのCPUを100とした場合の使用率をグラフにしたものです。  
    userはMySQLなど一般的なアプリケーションが使用したCPUの割合、sysはLinuxカーネルがプロセスのスケジューリング、メモリ管理などに使用したCPUの割合、iowaitはディスクI/O待ちとなっていたCPUの割合を示しています。

#### CPU (コア毎)
**・CPU使用状況(コア毎)**

* qmsLibraPoC-MySQLReplica01
![](images/log-scripts/Replica01/graph/cpu_core.png)

* qmsLibraPoC-MySQLReadReplica01
![](images/log-scripts/ReadReplica01/graph/cpu_core.png)

!!!note
    CPUの各コア毎の使用率をグラフにしたものです。各コアが偏りなく動作していれば、負荷分散が健全に行われていると判断できます。

<div style="page-break-before:always"></div>

#### ディスク使用状況

**・ディスク(dm-0)使用状況(busy_rate)**

MySQLのデータディレクトリとしては、`/dev/dm-0(/var/lib/mysql)`が対象となります。


* qmsLibraPoC-MySQLReplica01
![Disk Busy(dm-0)](images/log-scripts/Replica01/graph/disk_busy_dm_0.png)

* qmsLibraPoC-MySQLReadReplica01
![Disk Busy(dm-0)](images/log-scripts/ReadReplica01/graph/disk_busy_dm_0.png)


**・ディスク(/dev/dm-0)使用状況(iops)**

* qmsLibraPoC-MySQLReplica01
![Disk IOPS(dm-0)](images/log-scripts/Replica01/graph/disk_iops_dm_0.png)

* qmsLibraPoC-MySQLReadReplica01
![Disk IOPS(dm-0)](images/log-scripts/ReadReplica01/graph/disk_iops_dm_0.png)


!!!note
    ディスクの使用状況を表しています。   
    utilはディスクが転送要求の処理に費やした時間の割合です。100%に近いほどディスクがビジーであることを示します。
    また、r/sはディスクからの読み込み回数、w/sはディスクへの書き込み回数です。ただしこれらにはファイルキャッシュの読み書き回数は含まれていません。

<div style="page-break-before:always"></div>

**・ディスク(/dev/dm-0)使用状況(amount)**

* qmsLibraPoC-MySQLReplica01
![Disk IO amount(dm-0)](images/log-scripts/Replica01/graph/disk_io_amount_dm_0.png)

* qmsLibraPoC-MySQLReadReplica01
![Disk IO amount(dm-0)](images/log-scripts/ReadReplica01/graph/disk_io_amount_dm_0.png)


!!!note
    単位時間中の読み込み、書き込みのデータ量（単位はKB）を表しており、rkB/sはディスクからの読み込みデータ量、wkB/s はディスクへの書き込みデータ量です。ただしこれらにはファイルキャッシュの読み書き量は含まれていません。

<div style="page-break-before:always"></div>

#### メモリ使用状況

**・メモリ使用状況**

* qmsLibraPoC-MySQLReplica01
![Amount of memory usage](images/log-scripts/Replica01/graph/memory_util.png)

* qmsLibraPoC-MySQLReadReplica01
![Amount of memory usage](images/log-scripts/ReadReplica01/graph/memory_util.png)

<div style="page-break-before:always"></div>

!!!note
    OSが使用している全体的なメモリの使用状況を表しています。
    freeは空きメモリ容量、buffはバッファ・キャッシュ（ディスクブロックのメタデータであるiノードやディレクトリエントリなどをキャッシュするために使用しているメモリ容量）、cacheはページキャッシュ（ファイルシステム上のファイルをキャッシュするために使用しているメモリ容量）です。  
    Linuxでは空きメモリを積極的にページキャッシュとして利用するため、読み書きするデータ量が多い場合は、空きメモリが少なくなります。しかしメモリが必要となった場合には、利用頻度の低いバッファ・キャッシュやページキャッシュを破棄して、メモリを確保するため、空きメモリが少なくてもあまり問題ありません。
    総メモリ量からfree + buff + cacheを引いたものが、OSと各プロセスが実際に利用しているメモリ量です。


    なお、MySQLが使用するメモリの最大サイズは、以下の計算式からおおよその目安を割り出すことができます。

    ```
    【グローバルバッファ】
    key_buffer_size (16MB) + innodb_buffer_pool_size (185GB) + innodb_log_buffer_size (8MB) + temptable_max_ram (1GB) ≒ 186GB

    【スレッドバッファ】
    sort_buffer_size (1MB) + read_buffer_size (256KB) + read_rnd_buffer_size (512KB) + join_buffer_size (256KB) ≒ 2.5MB

    【MySQLの使用するメモリ量】
    グローバルバッファ(186GB) + (スレッドバッファ(2.5MB) * 同時接続数(max_connections 16,000) ≒ 39GB)】 ≒ 225 GB
    ```

    実際にMySQLで使用されているメモリは以下の通りでした。
    - qmsLibraPoC-MySQLReplica01で約7GB
    - qmsLibraPoC-MySQLReadReplica01では約5.5GB程度


**・スワップ使用状況**

* qmsLibraPoC-MySQLReplica01
![Amount of swap usage](images/log-scripts/Replica01/graph/swap.png)

* qmsLibraPoC-MySQLReadReplica01
![Amount of swap usage](images/log-scripts/ReadReplica01/graph/swap.png)


!!!note
    OSが使用しているスワップの使用状況を表しています。
    OSは実メモリ容量が不足してくると、メモリの内容の一部をスワップ領域へ移動させることで空きメモリを確保しようとします。
    siは1秒間にスワップイン（スワップアウトされたデータを必要に応じてメモリ上へ戻す処理）されたメモリ容量、
    soは1秒間にスワップアウト（実メモリ内の利用頻度が低いデータをディスク上へ一時的に退避させる処理）されたメモリ容量を表しています。
    スワップイン、スワップアウトが頻繁に行われると大量のディスクI/Oが発生するため、システムの性能が大幅に低下します。

<div style="page-break-before:always"></div>

#### ネットワーク使用状況


**・送受信量(サービス系NW)**

* qmsLibraPoC-MySQLReplica01
![Amount of NW transfer data](images/log-scripts/Replica01/graph/net_data_amount_ens192.png)

* qmsLibraPoC-MySQLReadReplica01
![Amount of NW transfer data](images/log-scripts/ReadReplica01/graph/net_data_amount_ens192.png)

**・送受信量(レプリケーション用NW)**

* qmsLibraPoC-MySQLReplica01
![Amount of NW transfer data](images/log-scripts/Replica01/graph/net_data_amount_ens224.png)

* qmsLibraPoC-MySQLReadReplica01
![Amount of NW transfer data](images/log-scripts/ReadReplica01/graph/net_data_amount_ens224.png)


!!!note
    各ネットワークインターフェースで送受信されたデータ量を示しており、RX_bytesが受信データ量、TX_bytesが送信データ量です。

<div style="page-break-before:always"></div>

**・送受信パケット数(サービス系NW)**

* qmsLibraPoC-MySQLReplica01
![Amount of NW transfer packets](images/log-scripts/Replica01/graph/net_packets_ens192.png)

* qmsLibraPoC-MySQLReadReplica01
![Amount of NW transfer packets](images/log-scripts/ReadReplica01/graph/net_packets_ens192.png)

**・送受信パケット数(レプリケーション用NW)**

* qmsLibraPoC-MySQLReplica01
![Amount of NW transfer packets](images/log-scripts/Replica01/graph/net_packets_ens224.png)

* qmsLibraPoC-MySQLReadReplica01
![Amount of NW transfer packets](images/log-scripts/ReadReplica01/graph/net_packets_ens224.png)

!!!note
    各ネットワークインターフェースで送受信されたパケット数を示していてRX_packetsが受信パケット数、TX_packetsが送信パケット数です。データベースではサイズが小さなパケットの送受信が多くなるため、帯域を使い切る前に処理可能なパケット数の上限を超えてしまいます。このため、送受信パケット数も合わせて確認する必要があります。

<div style="page-break-before:always"></div>

**・MySQL ネットワークトラフィック使用量**

* qmsLibraPoC-MySQLReplica01
![Amount of NW transfer packets](images/log-scripts/Replica01/graph/mysql_net_traffic.png)

* qmsLibraPoC-MySQLReadReplica01
![Amount of NW transfer packets](images/log-scripts/ReadReplica01/graph/mysql_net_traffic.png)

!!! note
    Bytes_receivedはすべてのクライアントから受信したバイト数、
    Bytes_sentはすべてのクライアントに送信されたバイト数です。

<div style="page-break-before:always"></div>

### MySQLの内部ステータス状況


#### 接続状況
**・接続数**

* qmsLibraPoC-MySQLReplica01
![Connections](images/log-scripts/Replica01/graph/connections.png)

* qmsLibraPoC-MySQLReadReplica01
![Connections](images/log-scripts/ReadReplica01/graph/connections.png)

!!! note
    Connectionsは単位時間内でのMySQLへの接続回数の増加差分、
    Threads_connectedはその時点でMySQLへ接続している接続数、
    Threads_runningはクエリ実行中の接続数(ステータスがSleepでないもの)を示しています。
    Threads_runningが多い場合はMySQLの負荷が高くなっていると判断できます。



**・スレッドキャッシュ使用状況**

* qmsLibraPoC-MySQLReplica01
![](images/log-scripts/Replica01/graph/thread_cache_hit_ratio.png)

* qmsLibraPoC-MySQLReadReplica01
![](images/log-scripts/ReadReplica01/graph/thread_cache_hit_ratio.png)

!!! note
    Thread_cache_hit_ratio はスレッドキャッシュのヒット率を示しています。`(100 - (Threads_created/Connections) * 100)`
    MySQL は、接続スレッドを thread_cache_size で設定したサイズ分メモリにキャッシュします。
    クライアントからの接続要求や接続の終了発生したとき、スレッドキャッシュを再利用することで、スレッドの新規作成と破棄のオーバーヘッドを削減してパフォーマンスを向上させます。
    新規スレッド生成が増加し、キャッシュヒット率が低下している場合は thread_cache_size の値を大きくすることを検討します。

!!! info
    今回の PoC では MySQL Enterprise スレッドプールを使用しているため、上記スレッドキャッシュは利用されません。


<!--

**・スレッドプール**

-->


**・接続エラー数**

* qmsLibraPoC-MySQLReplica01
![Connect Errors](images/log-scripts/Replica01/graph/connect_error.png)

* qmsLibraPoC-MySQLReadReplica01
![Connect Errors](images/log-scripts/ReadReplica01/graph/connect_error.png)

!!! note
    Aborted_connectsは認証エラーや不正なパケットなどによりMySQLサーバへ接続できなかった接続数です。
    Aborted_clientsはタイムアウトやクライアントが接続を適切にクローズしなかったために切断された接続数を示しています。

<div style="page-break-before:always"></div>

#### クエリ実行状況
**・クエリ(SELECT/UPDATE/DELETE)及びスロークエリ発生状況**

* qmsLibraPoC-MySQLReplica01
![Com Queries](images/log-scripts/Replica01/graph/com_queries.png)
![Slow Query Log](images/log-scripts/Replica01/graph/slow_query_log.png)

* qmsLibraPoC-MySQLReadReplica01
![Com Queries](images/log-scripts/ReadReplica01/graph/com_queries.png)
![Slow Query Log](images/log-scripts/ReadReplica01/graph/slow_query_log.png)

!!! note
    Com_selectはselectの実行回数、
    Com_insertはinsertの実行回数、
    Com_updateはupdateの実行回数、
    Com_deleteはdeleteの実行回数です。
    Slow_queriesは実行時間がlong_query_timeパラメータで指定した時間を越えるクエリの発生回数です。
    ただしlog-queries-not-using-indexesが有効な場合は、インデックスを利用しなかったクエリが実行された場合もSlow_queriesがカウントアップされます。

**・InnoDB内部処理状況**

* qmsLibraPoC-MySQLReplica01
![innodb_row_op](images/log-scripts/Replica01/graph/innodb_row_op.png)

* qmsLibraPoC-MySQLReadReplica01
![innodb_row_op](images/log-scripts/ReadReplica01/graph/innodb_row_op.png)

!!! note
    Innodb_rows_readは、InnoDBテーブルから読み取られた行数、
    Innodb_rows_insertedは、InnoDBテーブルに挿入された行数、
    Innodb_rows_updatedは、InnoDBテーブルで更新された行数、
    Innodb_rows_deletedは、InnoDBテーブルから削除された行数です。
    単位時間内の行数を示しています。


#### 内部処理待ち発生状況
**・InnoDB処理待ち状況**

* qmsLibraPoC-MySQLReplica01
![innodb_buffer_free_waits](images/log-scripts/Replica01/graph/innodb_buffer_free_waits.png)

* qmsLibraPoC-MySQLReadReplica01
![innodb_buffer_free_waits](images/log-scripts/ReadReplica01/graph/innodb_buffer_free_waits.png)

!!! note
    Innodb_buffer_pool_wait_freeはバッファプールに空きがないためダーティページをディスクへフラッシュする処理待ちが発生した回数、Innodb_log_waitsはログバッファに収まりきらず、トランザクションログファイルにフラッシュする処理待ちが発生した回数です。

**・InnoDB行ロック発生状況**

* qmsLibraPoC-MySQLReplica01
![InnoDB row locks](images/log-scripts/Replica01/graph/innodb_row_lock.png)

* qmsLibraPoC-MySQLReadReplica01
![InnoDB row locks](images/log-scripts/ReadReplica01/graph/innodb_row_lock.png)


!!! note
    Innodb_row_lock_timeは行ロック待ちの時間（単位はミリ秒）、
    Innodb_row_lock_waitsは行ロック待ちが発生した回数です。


**・InnoDB 非同期 I/O 処理待ち発生状況**

* qmsLibraPoC-MySQLReplica01
![InnoDB row locks](images/log-scripts/Replica01/graph/innodb_aio_wait.png)

* qmsLibraPoC-MySQLReadReplica01
![InnoDB row locks](images/log-scripts/ReadReplica01/graph/innodb_aio_wait.png)

!!! note
    Pending_AIO_Readsは、非同期 I/O 読取り処理の単位時間当たりの保留回数、
    Pending_AIO_Writesは、非同期 I/O 書込み処理の単位時間当たりの保留回数です。
    InnoDB は、Linux で非同期 I/O サブシステム (ネイティブ AIO) を使用して、データファイルページの先読みおよび書込みリクエストを実行します。
    I/O リクエストを処理する InnoDB バックグラウンドスレッド数は innodb_read_io_threads および innodb_write_io_threads で定義します。

<div style="page-break-before:always"></div>

#### バッファ・キャッシュ使用状況

<!--
注意!!!
InnoDBでrow_formant=compressedを使用しているテーブルが存在する場合、
show statusで確認するinnodb_buffer_pool_pages_xxxx系の値は不正となる**仕様**であるため、
本グラフは使う事はできません。

https://bugs.mysql.com/bug.php?id=59550

innodb_buffer_pool_pages_dataの量の正常性は、innodb_buffer_pool_hit_ratioのヒット率を見て判断してください。
innodb_buffer_pool_pages_(no)dirty、innodb_buffer_pool_pages_miscについては代替はありません。

不正な値となった場合は、以下の文言を付与してください。

:::WARNING
IMPORTANT: 本項目は、show global statusの結果より出力しておりますが、link:https://bugs.mysql
.com/bug.php?id=59550[Bug#59550]の**仕様**により、本環境では不正な値となります。 +
そのため、解析対象から除外しております。
:::

なお、後述のヒット率はこれらの値を使用していないため正確です。
-->

<説明>

**・InnoDBバッファプール使用状況**

* qmsLibraPoC-MySQLReplica01
![innodb_buffer_pool_pages_data](images/log-scripts/Replica01/graph/innodb_buffer_pool_pages_data.png)

* qmsLibraPoC-MySQLReadReplica01
![innodb_buffer_pool_pages_data](images/log-scripts/ReadReplica01/graph/innodb_buffer_pool_pages_data.png)

!!! note
    Innodb_buffer_pool_pages_data (no dirty)はクリーンな（ディスク上のデータと同期している）データが格納されているバッファプールのページ数、
    Innodb_buffer_pool_pages_dirtyはダーティな（ディスクにフラッシュしていない）データが格納されているバッファプールのページ数、
    Innodb_buffer_pool_pages_miscは行ロックやアダプティブハッシュインデックスなどに割り当てられているバッファプールのページ数、
    Innodb_buffer_pool_pages_freeは空き状態のバッファプールのページ数です。


**・InnoDBバッファヒット率**

* qmsLibraPoC-MySQLReplica01
![innodb_buffer_pool_hit_ratio](images/log-scripts/Replica01/graph/innodb_buffer_pool_hit_ratio.png)

* qmsLibraPoC-MySQLReadReplica01
![innodb_buffer_pool_hit_ratio](images/log-scripts/ReadReplica01/graph/innodb_buffer_pool_hit_ratio.png)

!!! note
    buffer pool hit rateはInnoDBが必要なデータをバッファプール内から探し出した割合です。


**・InnoDBバッファヒット回数/ミス回数**

* qmsLibraPoC-MySQLReplica01
![innodb_buffer_pool_hit_and_miss_count](images/log-scripts/Replica01/graph/innodb_buffer_pool_hit_and_miss_count.png)

* qmsLibraPoC-MySQLReadReplica01
![innodb_buffer_pool_hit_and_miss_count](images/log-scripts/ReadReplica01/graph/innodb_buffer_pool_hit_and_miss_count.png)

!!! note
    innodb_buffer_pool_read_requestは要求されたデータがバッファプール内にキャッシュされていた回数、
    innodb_buffer_pool_readsはバッファプール内にデータが存在せず、ディスクから読み込んだ回数です。

<div style="page-break-before:always"></div>

#### インデックス使用状況
**・インデックス使用状況**

* qmsLibraPoC-MySQLReplica01
![index scaning](images/log-scripts/Replica01/graph/scaning.png)

* qmsLibraPoC-MySQLReadReplica01
![index scaning](images/log-scripts/ReadReplica01/graph/scaning.png)

!!! note
    Select_full_joinはテーブル結合にインデックスを使用しない検索の回数、
    Select_scanはテーブルスキャンをした検索の回数、
    Sort_scanはテーブルスキャンを使用して実行したソートの回数です。


<説明>
試験中、Select_full_joinの平均回数が5回となっています。
実行クエリのアクセスするテーブル行数にも拠りますが、大量行数の結合・走査が必要なクエリについてはインデックスを使用することによって、処理速度の向上やDB全体の負荷軽減にもつながりますので、適宜見直しすることをお勧めいたします。


**・ソート処理状況**

* qmsLibraPoC-MySQLReplica01
![Sort merge](images/log-scripts/Replica01/graph/sort_merge.png)

* qmsLibraPoC-MySQLReadReplica01
![Sort merge](images/log-scripts/ReadReplica01/graph/sort_merge.png)

!!! note
    Sort_merge_passesはインデックスを利用できないソート処理においてsort_buffer_sizeで割り当てられたバッファ内だけでは処理できず、ディスクに一時ファイルを書き出した回数です。
    ソートマージ発生件数は0件が望ましいです。

#### 一時テーブル作成状況
**・一時テーブル作成状況**

* qmsLibraPoC-MySQLReplica01
![temp_table](images/log-scripts/Replica01/graph/temp_table.png)

* qmsLibraPoC-MySQLReadReplica01
![temp_table](images/log-scripts/ReadReplica01/graph/temp_table.png)

!!! note
    Created_tmp_tablesはSQL実行中にメモリ上に作成された一時テーブルの数です。
    これに対してCreated_tmp_disk_tablesはディスク上に作成された一時テーブルの数です。
    一時テーブルがディスク上に作成される原因としては、tmp_table_sizeかmax_heap_table_sizeを上回るサイズの一時テーブルの作成、BLOB型やTEXT型のカラムの処理、集計処理(group by)、サブクエリなどが考えられます。

    なお、以下のケースではメモリ上のテーブルが使用できず、強制的にディスク上にテーブルが作成されてしまうのでご注意ください。

    1. テーブル内の BLOB または TEXT カラムの存在
    2. GROUP BY または DISTINCT 句内の、バイナリ文字列の場合に512 バイトまたは非バイナリ文字列の場合に 512 文字より大きい文字列カラムの存在
    3. UNION または UNION ALL が使用された場合に、SELECT リスト内の 512 (バイナリ文字列の場合はバイト数、非バイナリ文字列の場合は文字数) より大きい最大長を持つ文字列カラムの存在

### MySQL関連ログ

#### スロークエリログ

qmsLibraPoC-MySQLReadReplica01 にて以下2種類のスロークエリ発生を確認しました。

```
# Profile
# Rank Query ID                            Response time   Calls R/Call   
# ==== =================================== =============== ===== ======== 
#    1 0x3CB21BE47FB2C6ECB62AD0343F7AE06C  1471.4418 40.7%    90  16.3494  8.10 SELECT sheet_match_job_rec_?
#    2 0x4541A9B9C1E0C6DA9FB3465E0ACC0AA3  1265.9588 35.0%    83  15.2525  6.97 SELECT window_rec_?
```

以下、スロークエリの原因分析と改善案について記載します。

<div style="page-break-before:always"></div>

##### Rank 1

* プロファイル

```
# Query 1: 0.00 QPS, 0.00x concurrency, ID 0x3CB21BE47FB2C6ECB62AD0343F7AE06C at byte 60183
# Scores: V/M = 8.10
# Time range: 2025-02-14T15:45:13 to 2025-02-25T17:09:30
# Attribute    pct   total     min     max     avg     95%  stddev  median
# ============ === ======= ======= ======= ======= ======= ======= =======
# Count         48      90
# Exec time     40   1471s     11s     56s     16s     47s     12s     12s
# Lock time     48    22ms    62us   492us   241us   403us    93us   236us
# Rows sent      0       0       0       0       0       0       0       0
# Rows examine  53   1.68G  17.65M  20.57M  19.17M  20.30M 993.20k  19.33M
# Bytes sent    56 153.72k   1.71k   1.71k   1.71k   1.71k       0   1.71k
# Query size    51  15.60k     177     178  177.51  174.84       0  174.84
# Bytes receiv   0       0       0       0       0       0       0       0
# Created tmp    0       0       0       0       0       0       0       0
# Created tmp    0       0       0       0       0       0       0       0
# Errno          0       0       0       0       0       0       0       0
# Read first     0       0       0       0       0       0       0       0
# Read key       3     280       1      20    3.11   19.46    5.80    0.99
# Read last      0       0       0       0       0       0       0       0
# Read next     53   1.68G  17.65M  20.57M  19.17M  20.30M 993.20k  19.33M
# Read prev      0       0       0       0       0       0       0       0
# Read rnd       0       0       0       0       0       0       0       0
# Read rnd nex   0       0       0       0       0       0       0       0
# Sort merge p   0       0       0       0       0       0       0       0
# Sort range c   0       0       0       0       0       0       0       0
# Sort rows      0       0       0       0       0       0       0       0
# Sort scan co   0       0       0       0       0       0       0       0
# String:
# Databases    qms
# Users        qms_user
```

* 対象クエリ(ワーストサンプル)

```sql
select
  *
from
  sheet_match_job_rec_01
where
  work_no > 0
  and menu_id = '161'
  and input_type <> 2
  and check_date >= '2025-02-03 11:00:03.1247'
  and check_date < '2025/02/03 11:15:03';
```

* 実行計画(`EXPLAIN ANALYZE`結果)

```sql
EXPLAIN: -> Filter: ((sheet_match_job_rec_01.WORK_NO > 0) and (sheet_match_job_rec_01.MENU_ID = 161) and (sheet_match_job_rec_01.INPUT_TYPE <> 2) and (sheet_match_job_rec_01.CHECK_DATE >= TIMESTAMP'2025-02-03 11:00:03.1247') and (sheet_match_job_rec_01.CHECK_DATE < TIMESTAMP'2025-02-03 11:15:03'))  (cost=1844707.00 rows=91920) (actual time=11923.036..11923.036 rows=0 loops=1)
    -> Index range scan on sheet_match_job_rec_01 using PRIMARY  (cost=1844707.00 rows=9193797) (actual time=0.070..9176.385 rows=18512284 loops=1)
```

複合主キーのうちの `WORK_NO` のみを使って範囲スキャンしていることがコストになっています。

* テーブル定義

```sql
mysql> show create table sheet_match_job_rec_01\G
*************************** 1. row ***************************
       Table: sheet_match_job_rec_01
Create Table: CREATE TABLE `sheet_match_job_rec_01` (
  `WORK_NO` bigint NOT NULL,
  `SEQ` decimal(7,0) NOT NULL,
  `DUMMY` decimal(1,0) NOT NULL DEFAULT '0',
  `MENU_ID` decimal(5,0) NOT NULL,
  `TRIAL_NO` decimal(5,0) NOT NULL DEFAULT '1',
  `JOB_NO` decimal(11,0) NOT NULL DEFAULT '0',
  `CHECK_MODE` decimal(1,0) NOT NULL DEFAULT '0',
  `CHECK_TYPE` decimal(1,0) NOT NULL DEFAULT '0',
  `INPUT_TYPE` decimal(1,0) NOT NULL DEFAULT '0',
  `CHECK_RESULT` decimal(1,0) NOT NULL DEFAULT '0',
  `FIXED_CONTENTS_CHECK` decimal(1,0) NOT NULL DEFAULT '0',
  `USER_NO` decimal(6,0) NOT NULL DEFAULT '0',
  `PC_ID` varchar(50) NOT NULL,
  `PC_ADDRESS` varchar(255) NOT NULL,
  `OPTION_GROUP_ID` decimal(8,0) NOT NULL DEFAULT '0',
  `DISABLED` decimal(1,0) NOT NULL DEFAULT '0',
  `CHECK_DATE` datetime NOT NULL DEFAULT CURRENT_TIMESTAMP,
  `REC_CREATE` datetime NOT NULL DEFAULT CURRENT_TIMESTAMP,
  `REC_UPDATE` datetime NOT NULL DEFAULT CURRENT_TIMESTAMP,
  PRIMARY KEY (`WORK_NO`,`SEQ`,`DUMMY`,`MENU_ID`,`TRIAL_NO`),
  KEY `IDX_SHEET_MATCH_JOB_REC_01` (`WORK_NO`,`MENU_ID`,`DISABLED`,`CHECK_RESULT`),
  KEY `IDX_SHEET_MATCH_JOB_REC_01_02` (`WORK_NO`,`JOB_NO`,`DISABLED`),
  KEY `IDX_SHEET_MATCH_JOB_REC_01_03` (`WORK_NO`,`SEQ`,`DUMMY`,`MENU_ID`,`DISABLED`),
  KEY `IDX_ITEM_MASTER_Rank3_1` (`MENU_ID`,`CHECK_DATE`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb3
1 row in set (0.00 sec)
```

* 改善案

実データを確認したところ、`WORK_NO` ではなく、`MENU_ID` と `input_type` の組み合わせの絞り込み結果のほうがカーディナリティが高いことが確認できました。

よって、以下のように `MENU_ID` と `input_type` の複合セカンダリインデックスを追加し、使用させることで実行速度の向上が見込めます。

```
ALTER TABLE qms.sheet_match_job_rec_01 ADD INDEX IDX_SHEET_MATCH_JOB_REC_01_Rank3_1 (`MENU_ID`,`CHECK_DATE`);
```

!!!info
    `sheet_match_job_rec_01～12` まであり、いずれも同じテーブル構造のため、上記インデックスを12テーブル全てに作成します。

<div style="page-break-before:always"></div>

##### Rank 2

* プロファイル

```
# Query 2: 0.00 QPS, 0.00x concurrency, ID 0x4541A9B9C1E0C6DA9FB3465E0ACC0AA3 at byte 8499
# Scores: V/M = 6.97
# Time range: 2025-02-14T15:50:06 to 2025-02-25T17:11:24
# Attribute    pct   total     min     max     avg     95%  stddev  median
# ============ === ======= ======= ======= ======= ======= ======= =======
# Count         44      83
# Exec time     35   1266s     10s     50s     15s     40s     10s     11s
# Lock time     44    20ms    58us   521us   237us   366us    92us   224us
# Rows sent      0       0       0       0       0       0       0       0
# Rows examine  44   1.39G  15.68M  18.96M  17.15M  18.41M   1.14M  16.70M
# Bytes sent    42 115.34k   1.39k   1.39k   1.39k   1.39k       0   1.39k
# Query size    44  13.66k     168     169  168.49  166.51       0  166.51
# Bytes receiv   0       0       0       0       0       0       0       0
# Created tmp    0       0       0       0       0       0       0       0
# Created tmp    0       0       0       0       0       0       0       0
# Errno          0       0       0       0       0       0       0       0
# Read first     0       0       0       0       0       0       0       0
# Read key       3     273       1      20    3.29   19.46    6.01    0.99
# Read last      0       0       0       0       0       0       0       0
# Read next     44   1.39G  15.68M  18.96M  17.15M  18.41M   1.14M  16.70M
# Read prev      0       0       0       0       0       0       0       0
# Read rnd       0       0       0       0       0       0       0       0
# Read rnd nex   0       0       0       0       0       0       0       0
# Sort merge p   0       0       0       0       0       0       0       0
# Sort range c   0       0       0       0       0       0       0       0
# Sort rows      0       0       0       0       0       0       0       0
# Sort scan co   0       0       0       0       0       0       0       0
# String:
# Databases    qms
# Users        qms_user
```

* 対象クエリ(ワーストサンプル)

```sql
select
  *
from
  window_rec_11
where
  work_no > 0
  and menu_id = '162'
  and input_type <> 2
  and check_date >= '2025-02-03 08:45:07.1482'
  and check_date < '2025/02/03 9:00:06';
```

* 実行計画(`EXPLAIN ANALYZE`結果)

```sql
EXPLAIN: -> Filter: ((window_rec_11.WORK_NO > 0) and (window_rec_11.MENU_ID = 162) and (window_rec_11.INPUT_TYPE <> 2) and (window_rec_11.CHECK_DATE >= TIMESTAMP'2025-02-03 08:45:07.1482') and (window_rec_11.CHECK_DATE < TIMESTAMP'2025-02-03 09:00:06'))  (cost=2005979.71 rows=99951) (actual time=13183.620..13183.620 rows=0 loops=1)
    -> Index range scan on window_rec_11 using PRIMARY  (cost=2005979.71 rows=9997125) (actual time=0.160..10189.588 rows=19880078 loops=1)
```

複合主キーのうちの `WORK_NO` のみを使って範囲スキャンしていることがコストになっている。

* 改善案

Rank 1と同様に、以下のように `MENU_ID` と `CHECK_DATE` の複合セカンダリインデックスを追加し、使用させることで実行速度の向上が見込めます。

```
ALTER TABLE window_rec_01 ADD INDEX IDX_WINDOW_REC_11_Rank29_1 (MENU_ID,CHECK_DATE);
```

!!!info
    `window_rec_01～12` まであり、いずれも同じテーブル構造のため、上記インデックスを12テーブル全てに作成します。


#### エラーログ

今回エラーログには特に異常を示すメッセージ出力はありませんでした。

<!--

## 改善提案

解析の結果を踏まえ、下記に改善提案を致します。

### 提案

提案内容について以下に記載いたします。
なお、初めに重要度(※1)を記載しており、その後詳細について説明をおこなっております。

※1.

  - 大 : 変更することで性能の改善が期待できます
  - 中 : 今は問題ありませんが、変更しておくことで将来的に有用となる可能性があります
  - 小 : 変更することで運用上のメリットや障害調査の一助に繋がる可能性があります

---

- 大 : SSDの使用、および MySQL のI/O 分割

  試験中、実行されるクエリテーブル結合でインデックスが使用できていないような傾向が見られました。そのため、実行されているクエリが適切にインデックスが使用されているかをご確認下さい。

- 大 : クエリチューニング

  前述のスロークエリログの章で記載しているインデックス追加の対応によりスロークエリ発生を減少させることが可能と考えます。


- 中 : パラメータチューニング

  その他、いくつかのパラメータについては変更することでリソースの効率化やオーバーヘッドの削減が期待できますので、こちらもご検討ください。


## 推奨される MySQL パラメータの設定

下記のパラメータの変更を提案いたします。

|重要度| パラメータ  | 現在の設定 | 推奨値 | 説明        |
|--|--------|-------|-----|-----------|
|中| thread_cache_size | 100 | 1000 | キャッシュする接続スレッドの上限を制御します。スレッドをキャッシュしておくことで新規接続時にスレッド生成処理をスキップする事ができ、多数の接続が見込まれるシステムではパフォーマンス低下の軽減につながります。メモリ余力もあるため、余裕をもって1000に設定します。 |
|中| tmp_table_size | 16MB | 256MB | 接続スレッドごとの個別の一時テーブルの上限サイズです。内部インメモリ一時テーブルがこのサイズを超えると、自動的にディスク上の内部一時テーブルに変換されます。本パラメータのサイズを引き上げることでクエリパフォーマンスの向上が見込めます。設定サイズはクエリの処理内容に依存しますが、一旦妥当値として設定し、 Created_tmp_disk_tables の減少やメモリ使用状況を見つつ調整を行ってください。|
|中| table_open_cache | 4000 | ※ | すべてのスレッドが開くテーブルをキャッシュするサイズです。試験中の Open_tablesメトリクス(現在開いているテーブルオープン数)が 4000 に到達して以降も、新規テーブルオープンが継続して発生している状況がみられるので、本キャッシュサイズの引き上げることでパフォーマンス向上が見込めます。推奨値については、パーティション数も含めたテーブル総数*平均同時接続数 を設定すると概ねカバーすることができます。本試験では通常稼働中の処理は含まれていないためシステムの平均同時接続数が不明ですので、お客様にて適宜ご確認いただいて設定願います。|
|中| innodb_open_files | 4000 | ※ | MySQL が一度に開くことができる InnoDB テーブルスペースファイル数の最大数です。変更した table_open_cache と同値にしておくことを推奨いたします。 |
|中| max_connections | 16000 | ※ | クライアントからの最大同時接続数を設定します。システム要件に応じて余裕をもった値を設定することが推奨されますが、許可する同時接続数が大きすぎると、想定外の接続とそれによって実行される処理内容によっては接続スレッドバッファを消費し、メモリ枯渇に至る可能性が高まります。 実際の接続数の上限＋余力程度に見直すことことを推奨いたします。|

-->


## Appendix A 用語集

本報告書で使用した主な専門用語についての解説です

| 語句        | 解説                                                                                                  |
|-----------|-----------------------------------------------------------------------------------------------------|
| ロードアベレージ  | サーバの負荷状況を表す指標で、単位時間内で実行中、もしくは実行待ちになっているプロセス数                                                        |
| システムコール   | カーネルの機能を呼び出すために使用される機構。ファイルの作成、読み書き、プロセスの生成などの際に用いられます                                              |
| ファイルキャッシュ | OSがディスクの内容をメモリにコピーし、それに対して読み書きすることで、低速なディスクへのアクセスを減らそうとする機能のことを指します                                 |
| バッファキャッシュ | ディスクブロックのメタデータのiノードやディレクトリエントリなどをキャッシュするために使用されるメモリ容量                                               |
| ページキャッシュ  | ファイルシステム上のファイルなどをキャッシュするために使用されるメモリ容量                                                               |
| スワップアウト   | メモリ内の利用頻度が低いデータをディスク上へ一時的に退避する処理                                                                    |
| スワップイン    | スワップアウトされたデータを必要に応じてメモリ上へ戻す処理                                                                       |
| スレッドキャッシュ | クライアントとMySQLとの接続で使用したスレッドを接続後も内部で保持し、再接続時のオーバーヘッドを軽減させる機能                                           |
| クエリキャッシュ  | 実行したSQLの実行結果をメモリ内に保存しておき、同じSQLが実行された際にはその実行結果をクライアントへ返すことで処理の高速化を図る機能                               |
| バッファプール   | InnoDBがディスクへのアクセスを減らすためにテーブルのデータやインデックスをキャッシュしておくためのメモリ領域                                           |
| フラッシュ     | バッファ（メモリ）内のデータをディスクに書き出す処理のこと。バッファ内のデータはMySQLやOSの異常終了や停電などにより消えてしまうが、ディスクに書き出せばそれらによってデータが失われることはない |
| テーブルキャッシュ | テーブルへのアクセスに必要なテーブルディスクリプタをキャッシュする機能。キャッシュすることでディスクリプタの初期化が不要となり、処理が高速化できる                           |
| テーブルスキャン  | テーブルのデータを先頭から最後まですべて順番に読込む処理                                                                        |
| ログバッファ    | InnoDBでは更新内容をトランザクションログファイルに記録するが、1つのトランザクション内での更新内容はコミットが行われるまでバッファ内に保持されます。このために用意されたバッファがログバッファ  |
| キーバッファ    | MyISAMがディスクへのアクセスを減らすためにインデックスをキャッシュしておくためのメモリ領域                                                    |
