# LogicPro
## Logic Pro 11 の新機能 Session Player を使ってセッション曲のバッキングトラックを作る

### パターン１：「コードトラックを作成して、SessionPlayerを配置して作る」の大まかな流れ
1. 新規作成し、「グローバルトラック」で「マーカー」を作成し、「イントロ、Aパート、Bパート、ブリッジ」などの進行の大枠を作る。
2. 「グローバルトラック」で「コードトラック」を作成し、コード進行を入力する。
3. リージョン（トラック）を追加し、「SessionPlayer」のドラム、ベース、キーボードを配置する。
4. 曲調に合うように、楽器の「プリセット」、SessionPlayerの「タイプ、スタイル」を調整する。
5. さらに細かく調整することもできるが、なるべく少ない設定手順で仕上げることを目指す。


### パターン２：「音源を取り込み、そのリズムやコードに合わせて作る」の大まかな流れ
1. 音源を用意し、リージョンに取り込む。
2. テンポを検出し、プロジェクトに適用する。
3. コードを検出し、プロジェクトに適用する。（できるか要検証）
4. リージョン（トラック）を追加し、「SessionPlayer」のドラム、ベース、キーボードを配置する。
5. 「SessionPlayer」が音源トラックのリズムやコードに合わせるように調整する。

SessionPlayerエディタ
・スタイルを変更
・プリセットを選択
・定義済みのリズムパターンを選択
・独自のパターンをゼロから作成
・さまざまな設定を使って演奏を微調整

### 公式のマニュアル

1. ★Mac用Logic Proのコードの概要  
https://support.apple.com/ja-jp/guide/logicpro/lgcp2633963f/11.0/mac/13.5

2. ★Mac用Logic ProのSession Playerのタイプとスタイルを変更する  
https://support.apple.com/ja-jp/guide/logicpro/lgcp9cf380ab/11.0/mac/13.5

3. ★Mac用Logic ProでSession Playerプリセットを選択する  
https://support.apple.com/ja-jp/guide/logicpro/lgcp286ad2de/11.0/mac/13.5

4. ★定義済みのリズムパターンを選択  
https://support.apple.com/ja-jp/guide/logicpro/lgcp74b34026/11.0/mac/13.5#lgcpc3a7172b

5. ★Mac用Logic ProでカスタムのSession Playerパターンを作成する  
https://support.apple.com/ja-jp/guide/logicpro/lgcp53c6779f/11.0/mac/13.5

6. ★Mac用Logic ProでSession Playerの演奏を編集する  
https://support.apple.com/ja-jp/guide/logicpro/lgcp74b34026/11.0/mac/13.5