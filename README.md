# LogicPro
## Logic Pro 11 の新機能 「Stem Splitter」と「Session Player」を使ってセッション曲のバッキングトラックを作る
  
### パターン１：音源を取り込み、「Stem Splitter」でドラムとベースを抽出し、「Keyboard Player」を追加する
1. 新規作成し、音源のファイルをリージョンとして取り込む。  
2. グローバルトラックを表示し、リージョンのテンポをプロジェクト全体に適用し、小節の区切りを音源に合わせる。
3. 音源の後ろに空白の小節があったら、ルーラーの右端をドラックして小節数を音源に合わせる。
4. 「Stem Splitter」でボーカル、ドラム、ベース、その他、の４つのトラックに分ける。
5. アレンジメントで曲の構成を入力する。
6. マーカーを入力して、繰り返しがわかるようにする
7. コードトラックにコードを入力する。繰り返し部分は、コピペする。小節途中のコードチェンジは、次の小節の小節線を左へドラッグして調節する。
8. 「Session Player」を挿入する。曲調に合うように、SessionPlayerの「スタイル」を選ぶ。生成されたフレーズが気に入らない場合は、「再度実行」（回転矢印マークのボタン）をクリックしてみる。それでもなじまない場合は、さらに「プリセット」で調整する。

### Session Player の設定項目
1. 設定項目としては、「タイプ」「スタイル」「プリセット」がある。
2. まず「タイプ」で、ドラムかベースかキーボードかを選ぶ。
3. 「スタイル」で音楽的ジャンルを選ぶ。
4. 「プリセット」で細かなニュアンスを調整する。
5. 「タイプ」：①Acoustic Drummer、②Electronic Drummer、③Percussionists、④Bass Player、⑤Keyboard Player
6. ①Acoustic Drummer の「スタイル」：Rock「Pop Rock、Retro Rock、Hard Rock、Punk Rock、Fnk Rock、Psychedelic Rock」、Songwriter「Funky Songwriter、Pop Songwriter、Experimental Songwriter、Roots Songwriter、60s Songwriter、Roots Brush、Pop Brush」、Alternative「Indie Pop、Indie Disco、Indie Rock、Garage Rock」、R&B「Modern R&B、Neo Soul、Modern Motown」
7. ②Electronic Drummer の「スタイル」：Electronic「Big Room EDM、Tech House、Bubstep、Electro Trap、Modern House」、Hip Hop「Trap、Modern Hip Hop、Boom Bap」、Alternative「Modern 80s、Synthpop」
8. ③Percussionists の「スタイル」：Parcussion「Latin、Pop、Songwriter」
9. ④Bass Player の「スタイル」：Rock「Pop Rock、Retro Rock」、Songwriter「Pop Songwriter、Roots Upright」、Alternative「Indie Disco、Disco Slap」、R&B「Modern R&B、Modern Motown」
10. ⑤Keyboard Player の「スタイル」：「Freely、Broken Chords、Block Chords、Arpegiated、Simple Pad」
11. 「プリセット」

### パターン２：コードトラックを作成して、「SessionPlayer」のみ配置して作る
1. 新規作成し、「グローバルトラック」で「マーカー」を作成し、「イントロ、Aパート、Bパート、ブリッジ」などの進行の大枠を作る。
2. 「グローバルトラック」で「コードトラック」を作成し、コード進行を入力する。繰り返し部分は、コピペする。小節途中のコードチェンジは、次の小節の小節線を左へドラッグして調節する。
3. 「SessionPlayer」のドラム、ベース、キーボードを挿入する。
4. 曲調に合うように、SessionPlayerの「スタイル」を選び、「プリセット」で調整する。
5. 手動でさらに細かく調整することもできるが、なるべく少ない設定手順で仕上げることを目指す。


### パターン３：「音源を取り込み、そのリズムやコードに合わせて作る」の大まかな流れ
1. 音源を用意し、リージョンに取り込む。
2. 「スマートテンポ」でテンポを検出し、プロジェクトに適用する。
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

  
### メモ
1. 「Stem Splitter」：曲の音源トラックを、①ボーカル②ドラム③ベース④その他、の４トラックに分割できる。
2. 「Session Player」：ドラム・ベース・キーボードのフレーズをAIが生成してくれる。「タイプ→スタイル→プリセット」の３段階で曲調を設定できる。再生成ボタンを押すと、パターンを変えて生成しなおしてくれる。
3. 「Varispeed」：テンポを半分～倍のあいだに変えて再生。「コントロールバーをカスタマイズ」でチェックを入れてLCDに表示させて使う。「速度のみ」と「速度とピッチ」の切り替えが可能。「速度のみ」ではピッチを変えずにテンポだけ遅くできるので、練習や耳コピにピッタリ。
4. 「グローバルトラック」：アレンジメント、マーカー、テンポ、コードなどを管理できる。特に「マーカー」で「イントロ」「Aメロ」「Bメロ」「アウトロ」などと印をつけると、曲の構成の把握や繰り返し部分が俯瞰でき、現在位置をロストしにくくなる。「コード」を指定しておくと、「Session Player」の生成精度が上がる。
5. 「ループレコーディング」：「サイクル」をオンにして、範囲を指定して録音すると、ループ録音できる。ベストテイクを残したり、複数テイクをつぎはぎしたりできる。
6. 「スマートテンポ」：生演奏データを取り込んだ場合、テンポにゆらぎがあると小節区切りがずれて困りますが、テンポを検出してプロジェクト全体に適用すると、小節区切りがピッタリ合います。