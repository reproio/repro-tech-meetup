# Hands-on organize workflow

本templateを元に実施のissueを作成し、進捗を管理する。

# Template

## Prepare contents

- [ ] hands-on themeの決定
- [ ] hands-on案(`hands-on/<num>/connpass.md`) を作成し、詳細を詰める
    - Reproの会場の場合募集は最大で30名程度
    - 10名に一人のメンターがつけるのが理想
    - 集まりを鑑み、connpassの開始時間はスタートより15min程度早めにしておく
    - 対象者のレベル感を明確にするとともに、必要であれば募集枠も分ける
      - e.g.
        - 関連する技術に類する技術を触ったことがある人
        - 関連する技術に類する業務やその周辺技術を触ったことがない人
- [ ] hands-on案をもとに1名以上のメンター依頼を実施
- [ ] メンターを[Slack](https://repro-tech.slack.com/)(join from [here](https://join.slack.com/t/repro-tech/shared_invite/enQtNDc3MTAyMjk2NDE4LTYxMjRhMmUyNjA0YTllNGE4ZWNkNzExZmM0N2RiN2U5YTZiZjc1NGI3Y2ZjN2QyMmVmODdjYzlhMjA4OTYyZDE))へ招待
- [ ] Mentorの都合と時間に合わせ、土日(可能であれば日曜)で開催日の決定

## Publish Event

最低でも開催2W前に公開すること

- [ ] メンターより自己紹介文(twitterのbio程度の長さ)とプロフィール画像(github, twitter画像の参照でも可能)を回収
- [ ] connpassへ公開準備を行い、memterに最終チェックを依頼。期間は1日程度設ける。
- [ ] メンターとmeetingを行い、hands-onプログラムの方向性を決定する
- [ ] [Repro Tech connpass](https://repro-tech.connpass.com/)の公開

## Promotion

- [ ] announce.md, meetup.md, wantedly.mdなどのプロモーション資料の準備
- [ ] [Repro meetup group event](https://www.meetup.com/reproio/)
- [ ] [Repro wantedly feed](https://www.wantedly.com/companies/repro/feed)
- [ ] [Repro linkedin](https://www.linkedin.com/company/repro-inc-/)
- [ ] [Repro facebook group event](https://www.facebook.com/pg/reproio/events/)
- [ ] [Repro connpass group message](https://repro.connpass.com/)
- [ ] PR担当にtrelloより依頼 / [Repro facebook group](https://www.facebook.com/reproio/), Repro slack, [reproio twitter](https://twitter.com/reproio?lang=en)
- [ ] Mentorにtwitter, facebookなどのSNSでの拡散

## 1 week before

- [ ] 必要に応じて増枠し、再告知する
- [ ] Hands-on プログラムの詳細が決まっていない場合は、Menter含め最終調整
- [ ] 前回のKPTも活かしたintrocution資料の準備

## 2 day before

- [ ] 金曜日にconnpassより以下メッセージを送る
- 在庫状況に応じて以下を実施
    - [ ] 必要なお酒ケース数 = `開催1日前の申込者数 * 当日キャンセルしない率 0.9 * 実参加率 0.7 * 懇親会残留率 0.8 * 一人あたりの平均消費缶 1.8 / 24`
    - [ ] 乾き物の発注
      - 柿ピー2種, おつまみ 2種, パイの実, カントリーマーム

```txt
subject: Repro Tech Hands-on #<num> <theme>
To: Event Admins, Presenter, Attendees, Waitlist
Body:
この度は明日開催のRepro Tech Hands-onへご応募頂きまして、誠にありがとうございます。
明日の開場は12時30分です。

## 開場・開始

開場: 12:30
スタート: 13:00

## 場所

東京都渋谷区代々木1丁目36-4 全理連ビル 6階
google map: https://goo.gl/maps/t7NtRv4rUv92

それではイベントでお会い出来ることを楽しみにしています✨
```

## イベント当日の作業

- 開場30min前に会場設営
    - 机の配置はカテゴリーや参加者のスキルを考慮しグループ化する
    - 人数が少ないときは複数のデスクをくっつけ、多きグループを作るとコミュニケーションが活発になる
    - カテゴリごとにgrouping(iOS, Androidなど)する場合は、ホワイトボードに各グループの座席配置を書いておくと案内に迷わなくて良い
- Introduction
    - ReproよりRepro Tech Hands-onの概要説明
    - 自己紹介の時間を以下のように取る
        - 20名以下ときは、全体で実施
        - 20名超過のときは、机やgroupごとに実施
- hands-on
  - Mentorより自己紹介やhands-onの流れを説明
- 懇親会
  - `#reprotech` にて感想tweet・感想を言える時間を作る
  - 立食形式、テーブル２つ程度に軽食を展開

## イベント終了後

- [ ] 振り返りの実施し、次回の改善点を決定する

# イベント中止

- [ ] 中止が決定したあと速やかに、connpassより以下メッセージを送る
- [ ] Mentorにtwitter, facebookなどのSNSでの拡散を依頼
- [ ] connpassにイベントを中止する
- [ ] 公開ページ全てに中止の旨を記載
    - Facebook
    - Wantedly
    - Meetup
- [ ] イベント開催予定の前日に同じメッセージ送る

```
subject: Repro Tech Hands-on #<num> <theme>は中止します。
To: Event Admins, Presenter, Attendees, Waitlist
Body:
この度はReproTech Hands-onにご応募頂きまして誠にありがとうございます。

大変心苦しいのですが、運営サイドの都合により開催日を変更することとなりました。
こちら、改めてconnpassのイベントをご応募頂いた方にはメールにてご連絡させて頂きます。

引き続きReproTech Hands-onをよろしくお願い申し上げます。
```
