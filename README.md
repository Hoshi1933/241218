# 現在地の気温、湿度、風速からの体感温度
## 概要
急に暑くなったり、急に寒くなったりと毎日の服装選びが難しくなっています。普段期
にしている気温だけでなく、風速や湿度も服装選びというところでは大事になってく
る気象要素です。この気温、湿度、風速などの気象データから体感温度を計算し、ユー
ザーが適切な行動や服装選びの参考にできるようにすることで、快適な生活をサポー
トします。また、過度な暑さや寒さによる健康リスクを減らします。

## 利用するオープンデータ
- 気象データ：気温、湿度、風速のリアルタイム気象データ（気象庁や Open Weather 
Map など）
- 地理情報データ：GPS 情報を基にしたユーザーの現在地データ
- 健康リスク情報：環境省や厚生労働省から提供される暑さ指数(WBGT)や熱中症・
低体温症などのリスク情報

## 機能概要
### 1. 現在地の気象データ取得機能
GPS を利用してユーザーの現在地を取得し、気温、湿度、風速などの気象データ
をリアルタイムで取得。
### 2. 体感温度計算機能
気温、湿度、風速をもとに、独自の計算式や既存の体感温度計算式（ミスナール法やリンケ法など）を用いて体感温度を算出。算出された体感温度を「暑い」、「快適」、「寒い」などのカテゴリーに分類し、ユーザーにわかりやすく表示。
### 3. 服装・行動アドバイザー機能
体感温度に基づき、推奨される服装や注意点を表示。熱中症や低体温症のリスクが高い場合に警告を表示し、予防のための行動を提案。
### 4. 過去の体感温度履歴
過去の気象データと体感温度を記録し、ユーザーが同時期の気象傾向を確認できる。
### 5. 通知機能
特定の気温・湿度条件での体感温度や健康リスクが高い場合、ユーザーにプッシュ通知で警告を送信。

## ユーザーにとっての利便性
- 快適な服装選び：体感温度を基に、その日の最適な服装や持ち物を選びやすく、外出時の快適さを高められる。
- 健康リスクの低減：体感温度が極端な場合に通知がくることで、熱中症や低体温症などの予防につながる。
- データの可視化：過去の体感温度や傾向を確認できるため、自分の体調管理にも役立てられる。

## デモリンク
[GitHub Pages](https://<username>.github.io/<project-name>/)

## 将来の展望（オプション）
- AI による学習：これまでのユーザーの体感温度データを基に AI が学習し、個別の体感温度範囲を設定することができるようにする。
- アレルギーや健康に関する情報連携：花粉情報や風邪予防など、季節性の健康情報を追加し、包括的な健康管理支援を目指す。
- 複数地点の気象比較：複数の地点を選択し、それぞれの体感温度を比較できるようにして、旅行や引っ越し先の環境を考慮する際の参考情報として利用できるようにする。
