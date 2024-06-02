# LogicPro
## Logic Pro 11 の新機能 「Stem Splitter」と「Session Player」を使ってセッション曲のバッキングトラックを作る
  
### パターン１：音源を取り込み、「Stem Splitter」でドラムとベースを抽出する
1. 新規作成し、音源のファイルをリージョンとして取り込む。  
2. グローバルトラックを表示し、リージョンのテンポをプロジェクト全体に適用し、小節の区切りを音源に合わせる。
3. 音源の後ろに空白の小節があったら、ルーラーの右端をドラックして小節数を音源に合わせる。
4. 「Stem Splitter」でボーカル、ドラム、ベース、その他、の４つのトラックに分ける。
5. アレンジメントで曲の構成を入力する。
6. マーカーを入力して、繰り返しがわかるようにする
7. コードトラックにコードを入力する。繰り返し部分は、コピペする。小節途中のコードチェンジは、次の小節をドラッグして調節する。
8. 「Session Player」を挿入する。

### Session Player の設定項目
1. 「タイプ」：①Acoustic Drummer、②Electronic Drummer、③Percussionists、④Bass Player、⑤Keyboard Player
2. ①Acoustic Drummer の「スタイル」：Rock「Pop Rock、Retro Rock、Hard Rock、Punk Rock、Fnk Rock、Psychedelic Rock」、Songwriter「Funky Songwriter、Pop Songwriter、Experimental Songwriter、Roots Songwriter、60s Songwriter、Roots Brush、Pop Brush」、Alternative「Indie Pop、Indie Disco、Indie Rock、Garage Rock」、R&B「Modern R&B、Neo Soul、Modern Motown」
3. ②Electronic Drummer の「スタイル」：Electronic「Big Room EDM、Tech House、Bubstep、Electro Trap、Modern House」、Hip Hop「Trap、Modern Hip Hop、Boom Bap」、Alternative「Modern 80s、Synthpop」
4. ③Percussionists の「スタイル」：Parcussion「Latin、Pop、Songwriter」
5. ④Bass Player の「スタイル」：Rock「Pop Rock、Retro Rock」、Songwriter「Pop Songwriter、Roots Upright」、Alternative「Indie Disco、Disco Slap」、R&B「Modern R&B、Modern Motown」
6. ⑤Keyboard Player の「スタイル」：「Freely、Broken Chords、Block Chords、Arpegiated、Simple Pad」

### パターン２：「コードトラックを作成して、SessionPlayerを配置して作る」の大まかな流れ
1. 新規作成し、「グローバルトラック」で「マーカー」を作成し、「イントロ、Aパート、Bパート、ブリッジ」などの進行の大枠を作る。
2. 「グローバルトラック」で「コードトラック」を作成し、コード進行を入力する。
3. リージョン（トラック）を追加し、「SessionPlayer」のドラム、ベース、キーボードを配置する。
4. 曲調に合うように、楽器の「プリセット」、SessionPlayerの「タイプ、スタイル」を調整する。
5. さらに細かく調整することもできるが、なるべく少ない設定手順で仕上げることを目指す。


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