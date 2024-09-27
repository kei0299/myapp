# myapp
## サービス概要
このアプリは、失業者やフリーターが日々の生活費を効率的に管理し、今後の生活資金を簡単に予測できるツールです。  
現在の貯金額と月々の支出を入力するだけで、どれくらいの期間今の生活を維持できるかをすぐに把握できます。  
また、バイト先を複数登録することができ、時給や深夜手当などの設定を行ったうえで、シフトを入力すると自動的に収入が反映されます。  
これにより、収入と支出を総合的に管理し、将来の資金状況をリアルタイムで予測できるようになります。  
生活の不安を軽減し、計画的な家計管理をサポートするアプリです。  

## このサービスへの思い・作りたい理由  
私は今回、学校に通うために一時的に仕事を退職しましたが、その際に最も不安に感じたのが「生活費をどうやって管理するか」でした。  
一般的な家計簿アプリは多く存在しますが、単に支出を記録するだけでは、実際に今の貯金でどれくらい生活できるのかを判断することが難しいと感じました。  

同じように、体調の問題でやむを得ず仕事を辞めた方や、夢や目標を持ってフリーターとして働いている方々も、将来の生活資金に不安を感じることが多いのではないでしょうか。  
そんな方々に少しでも安心を届け、計画的に生活をサポートできるツールを作りたいと思い、このアプリを考案しました。  
生活の不安を少しでも軽減し、前向きに未来を見据えられるようなサポートを目指しています。  

## ユーザー層について
失業者やフリーターで今後の生活が金銭面的に不安な人。   

## サービスの利用イメージ
1. 新規登録 or ログイン  
  ユーザーはまず、アカウント登録を行います。ログインには、Googleアカウントが使用可能です。    

2. 貯金と支出の設定  
  貯金額を入力します。この情報に基づいて、現在の生活資金でどれくらい生活できるかを予測します。  
  月々の固定支出を設定します。  
  貯金が設定した閾値（例：貯金の20％）を下回ると、アラートが自動的に表示されます。この閾値はユーザーが自由に設定できます。  

3. アルバイト先の登録  
  ユーザーは、複数のバイト先を登録できます。  
  各バイト先ごとに、以下の情報を入力します。
  時給：通常時給および深夜割増（例えば、22時以降は25％増など）  
  シフト時間：週の勤務時間を入力。日付と時間を設定すると、自動的に収入が算出されます。  
  深夜帯の勤務時間や、残業が発生する場合には、加算された金額が反映されます。  

4. 日々の収支管理  
  ユーザーは、日々の収支を簡単に入力できます。食費や交通費、娯楽費などのカテゴリを選んで入力します。  
  入力された支出は、Googleカレンダーへ自動で反映されます。これにより、カレンダー上で収支の変動が確認でき、予定と一緒に管理できます。  

5. 貯金残高と支出の分析  
  ホーム画面では、現在の貯金と支出の推移をグラフで確認できます。  
  シフトや収入が反映され、将来の収支予測も見ることができます。これにより、貯金がどれくらいの期間で尽きるかや、収入によってどれくらい延命できるかがわかります。   

## ユーザーの獲得について
どの年代の人でも直感的に使えるように、シンプルなUI/UXにする。  
レスポンシブに対応し、PC、モバイルともに使いやすくする。  
(ゲストモードを作成し、手軽に使い勝手を試せるようにする。)  

## サービスの差別化ポイント・推しポイント
従来の家計簿アプリでは、収支の記録はできても現在の貯金でどれだけの期間生活できるかを把握するのは難しいです。  
そのため、ユーザーが別途計算して生活計画を立てる手間がかかります。  
本サービスは、貯金や支出をもとに生活可能期間を簡単に計算し、すぐに結果を提供します。  
さらに、アルバイトを行うユーザー向けにバイト先や時給やシフトを登録するだけで今後の収入を自動的に反映させます。  

## 機能候補
### MVPリリース
- 作成ページ
  - ログイン画面
  - ホーム画面
  - 収支入力画面
  - グラフ比較画面
  - 予算管理画面
  - バイト先登録画面
  - 目標設定画面
  - サポートページ（必要？）

Googleログイン機能  
Googleカレンダーへの出力  
収支入力  
バイト先登録機能  
シフト入力  
カテゴリ分類  
収支をカテゴリごとに円グラフで表示  
予算比をプログレスバーで表示  
通知機能  
  - 予算が超えそうな時  
  - 予算が超えた時  

### 将来的に
テーマカラー変更  
節約アドバイス機能追加  
予定された収支のリマインダー  
LINEチャットbotへの相談機能  
失業手当がもらえるかどうかの診断機能  
失業手当の目安金額診断  
定年退職者にも対応
（年金、退職金、将来の医療費、介護費用などを追加）
学生や主婦/主夫モードの追加  
目安となる保険料や住民税が自動的に算出され、月々の支出に追加される機能  
  - 年齢：将来の税金や保険料算出に必要。  
  - 扶養人数：世帯の人数に基づいて、国民健康保険や住民税などの目安を計算する。  
  - 前年度の収入：住民税、国民健康保険の金額を正確に算出するために使用。  

## 収益化について
節約アドバイス機能を課金にする  
転職関連会社との連携  
保険関連会社との連携  
資産運用会社との連携  

| 使用技術  |   |
| ------------- | ------------- |
| バックエンド   | Ruby on Rails（APIモード） |
| フロントエンド   |  React,Node.js |
| CSS  | TailwindCSS |
| データベース  | PostgreSQL |
| インフラ  | Render.com |
| API  | Google Calendar API |


