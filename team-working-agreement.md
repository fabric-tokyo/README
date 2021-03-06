# ワーキングアグリーメント

## 概要

ワーキングアグリーメントの目的はチームがどのように連携して機能するかについての期待を定義する責任を共有し、自己組織化プロセスを強化することです。

## 振る舞いについて

- 開発者はデイリースクラムに必ず参加する（参加できない場合はSlackにて報告する
- DMを使わずにチームメンションに質問する
- PRは `@fabric-tokyo/{team}`, `@fabric-tokyo/server` などを使いレビューを依頼する
- PRの確認項目にチケットの受入要件の項目を満たしている状態でPOレビューを行う
- 営業日の14時から16時までの期間、予定が埋まっていない場合は [#bu_ec](https://lsd-dev.slack.com/archives/C12ETE7DX)🔒でHuddleに参加する

- 関連部署からの依頼について
    - 障害は発見者から [#system_oncall](https://lsd-dev.slack.com/archives/C2YRK6ADC)🔒で報告される
    - OnCallの対応はプロダクト部のエンジニアが一週間ごとに交代制で担当する
- リリースについて
    - リリースは基本、月〜木で実施する。
    - 祝休前日および、祝休前前日の深夜にリリースはしない。

---

## 以下 Scrum Event に関する項目

### デイリースクラム

- 毎日 11:30 - 12:00 （スプリントプランニングを行う日は除く
- 12時を超えないようにする。超える場合に個人間でのやりとりであれば別で行う
- ふりかえりの際に議論したい内容がないかを確認し、あれば翌週の振り返りに利用するMiroに追加する
- 出席者
    - 必須
        - 開発者（エンジニア・デザイナー）
    - 任意
        - PdM
- ファシリテーターは開発者で持ち回り
- 出席できない場合は事前にSlackにて以下を報告

```
## 昨日やったこと

## 今日やること

## 困っていること
```

### スプリントプランニング

- 月曜日 14:00 - 17:00 (祝日の場合は次の営業日)
- 出席者
    - 必須
        - PdM・開発者
- ファシリテーターはPdM

### スプリントレトロスペクティブ

- 月曜日 12:30 - 14:00　(祝日の場合は次の営業日)
- 出席者
    - 必須
        - PdM・開発者
- ファシリテーターはスクラムマスター
- 不在の場合はPdM
