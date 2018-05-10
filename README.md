# parse_kaken_master

### 1. 設定ファイル作成
- config.ipynb

### 2. bitbucketのKAKENマスタをパースしてローカルのMariaDBに保存するプログラム
- category_master.ipynb　…　研究種目マスタ
- institution_master.ipynb　…　研究機関マスタ
- section_master.ipynb　…　配分区分マスタ

### 3-1. KAKENデータベースからXMLファイルをダウンロードするプログラム
- kaken_zenkadai_download.ipynb

### 3-2. KAKENからダウンロードしたXMLファイルをパースしてローカルのMariaDBに保存するプログラム
- parse_grantaward_main.ipynb
- parse_grantaward_institution_from_grantlist.ipynb
- parse_grantaward_member_from_summary.ipynb
- parse_grantaward_integration.ipynb

1の設定ファイルさえ作れば、2と3は順不同です。
