# DataTSVCommon
共通のデータを置いたリポジトリ。
誰でもMIT LICENSEでつかっていいです。

## prefectures.tsv

```sql
CREATE TABLE prefectures(
  id INTEGER PRIMARY KEY,
  name VARCHAR(16) NOT NULL,
  name_kana VARCHAR(16) NOT NULL,
  name_short VARCHAR(16) NOT NULL,
  name_kana_short VARCHAR(16) NOT NULL,
);
```
