## 第1章 プログラミングとPythonの世界：なぜPythonを学ぶのか

**この章で学ぶこと**

- プログラミングが私たちの身の回りでどのように使われているか
- Pythonというプログラミング言語がなぜ初心者におすすめなのか
- Pythonを使ってどんなことができるようになるのか
- この本でどのように学習を進めていくか

**必要な前提知識**

- 特にありません！ パソコンの基本的な操作（マウス操作、キーボードでの文字入力、ファイルの保存など）ができれば大丈夫です。リラックスして読み進めてくださいね。

### はじめに：プログラミングってなんだろう？

こんにちは！ この本を手に取っていただき、ありがとうございます。

「プログラミング」と聞くと、なんだか難しそうなイメージがあるかもしれません。黒い画面に謎の英語がズラッと並んでいる…そんな光景を思い浮かべる方もいるでしょうか？

でも、実はプログラミングは、私たちのとても身近なところにたくさん隠れているんです。

例えば、あなたが毎日使っているスマートフォン。アプリをタップすると、天気予報が表示されたり、友達とメッセージを交換できたりしますよね。これも、プログラマーが書いた「指示書」＝「プログラム」に従って、スマートフォンが動いている結果なのです。

他にも、

- 駅の自動改札機：切符やICカードの情報を読み取って、通って良いか判断し、ゲートを開け閉めする。
- インターネットの検索エンジン：検索したい言葉を入力すると、関連するWebサイトを世界中から探し出して表示する。
- お掃除ロボット：部屋の形を認識して、効率的なルートで掃除を進め、充電が少なくなったら自分で充電ステーションに戻る。

これら全て、人間がコンピューターに対して「こういうときは、こう動いてね」と細かく指示を書いたプログラムによって動いています。

つまり、**プログラミングとは、「コンピューターにやってほしいことを、コンピューターが理解できる言葉で、順番に伝えること」** なのです。まるで、外国の人に言葉で指示を出すのに似ていますね。コンピューターが理解できる特別な言葉、それが「プログラミング言語」です。

[プログラマー用語集]

- **プログラム:** コンピューターに対する指示を順番に書いたもの。レシピや設計図のようなイメージ。
- **プログラミング:** プログラムを作成すること。
- **プログラミング言語:** 人間がコンピューターに指示を伝えるために使う、特別な言葉。英語に似たものが多いですが、文法ルールが厳密に決まっています。
- **ソースコード:** プログラミング言語で書かれたプログラムのテキストそのもの。
- **実行:** コンピューターがソースコードを読み取って、書かれた指示通りに動作すること。

### なぜ今Python（パイソン）なの？

世の中にはたくさんのプログラミング言語があります。C言語、Java、JavaScript、PHP、Ruby…それぞれに特徴があり、得意な分野も異なります。

その中でも、この本で皆さんと一緒に学んでいくのが **Python（パイソン）** という言語です。なぜ、数ある言語の中から、最初のプログラミング学習にPythonが選ばれることが多いのでしょうか？ それには、いくつか理由があります。

1. **シンプルで読みやすい文法:** Pythonの最大の特徴は、その文法が比較的シンプルで、人間が読んで理解しやすいように設計されていることです。他の言語と比べて覚えるルールが少なく、英語の文章を読むような感覚でコードを理解しやすい場面も多いでしょう。これは、初めてプログラミングに触れる方にとって、とても大きなメリットです。「おまじない」のような複雑な記述が少なく、自分が「何をしているか」を把握しやすいのです。
    
2. **豊富な「道具箱（ライブラリ）」:** Pythonには、「ライブラリ」と呼ばれる便利な機能（プログラムの部品）がたくさん用意されています。これは、先人たちが作ってくれた便利な道具箱のようなもので、複雑な処理も、このライブラリを組み合わせることで、比較的簡単に実現できてしまいます。例えば、Webサイトを作るためのライブラリ、データ分析をするためのライブラリ、AI（人工知能）を作るためのライブラリなど、ありとあらゆる分野のライブラリが存在します。自分で一からすべてを作る必要がないので、効率的に開発を進められます。
    
3. **世界中で人気があり、応用範囲が広い:** Pythonは、Google、Instagram、YouTubeといった世界的なサービスでも使われています。また、最近注目されているAI（人工知能）や機械学習、データサイエンスといった分野では、事実上の標準言語として広く使われています。その他にも、Webアプリケーション開発、ゲーム開発、科学技術計算、日常業務の自動化など、本当に幅広い分野で活躍しています。つまり、Pythonを学ぶことで、あなたの興味がある分野で役立つスキルを身につけられる可能性が高いのです。
    

これらの理由から、Pythonは「学びやすく、かつ、実用的」な言語として、プログラミング初心者からプロの開発者まで、世界中の多くの人に支持されています。

### Pythonでできること色々

Pythonを学ぶと、具体的にどんなことができるようになるのでしょうか？ もちろん、すぐにプロのエンジニアと同じようなものが作れるわけではありませんが、基礎を身につけるだけでも、あなたのアイデアを形にするための第一歩を踏み出すことができます。

[図表：Pythonの主な応用分野を示したイラストマップ] （ここに、Web開発、データ分析、AI・機械学習、業務自動化、ゲーム開発などの分野を示すイラストが入るイメージ）

- **Webアプリケーション開発:** ブログシステムやSNSのようなWebサイトの裏側（サーバーサイド）を作ることができます。（例: Django, Flask というライブラリ）
- **データ分析・機械学習・AI:** 大量のデータから意味のある情報を見つけ出したり、将来の予測をしたり、画像や音声を認識したりするプログラムを作ることができます。（例: NumPy, Pandas, Scikit-learn, TensorFlow, PyTorch というライブラリ）
- **業務の自動化:** ファイルの整理、Excelの操作、メールの自動送信、Webサイトからの情報収集（スクレイピング）など、パソコンで行う定型的な作業を自動化するプログラムを作ることができます。
- **その他:** 簡単なゲームを作ったり、科学技術計算をしたり、IoTデバイス（インターネットにつながる機器）を制御したりと、アイデア次第で様々なことに挑戦できます。

この本では、まずPythonの基本的なルールを学び、最終的には簡単な計算機や家計簿アプリ、そしてデータ分析の初歩に触れるミニプロジェクトに挑戦します。これらの経験を通して、Pythonを使って「自分で何かを作り出す楽しさ」を感じてもらえたら嬉しいです。

### この本の進め方と学習の心構え

この本は、プログラミングが全く初めての方でも、つまずかずに最後まで進められるように、以下の点を工夫しています。

- **ステップ・バイ・ステップ:** 基礎から順番に、少しずつ難易度を上げていきます。前の章で学んだことが、次の章の土台となるように構成されています。
- **豊富な図解と具体例:** 抽象的な説明だけでなく、図や具体的なコード例、そしてその実行結果を必ず示すことで、直感的に理解できるように工夫します。
- **「なぜ？」を大切に:** 単にコードの書き方を覚えるだけでなく、「なぜそう書くのか」「どういう仕組みで動いているのか」という理由も、できるだけ丁寧に説明します。
- **「よくある間違い」コーナー:** 初心者が陥りやすい間違いやエラーについて、その原因と対策を具体的に解説します。転ばぬ先の杖として役立ててください。
- **手を動かすことを重視:** プログラミングは、本を読むだけではなかなか身につきません。各章で紹介するコードは、ぜひ実際にあなたのパソコンで入力し、実行してみてください。そして、章末の「理解度チェック」や「チャレンジ問題」にも挑戦してみましょう。

**学習を進める上での心構えとして、いくつかお伝えしたいことがあります。**

1. **焦らないこと:** プログラミングの学習には時間がかかります。すぐに理解できなくても、落ち込む必要はありません。何度も読み返したり、コードを書き直したりするうちに、だんだんと分かってくるものです。自分のペースで進めましょう。
2. **エラーを恐れないこと:** プログラムを書いていると、必ずと言っていいほどエラー（間違い）が出ます。これは、プロのエンジニアでも同じです。エラーメッセージは、プログラムが「ここが間違っているよ！」と教えてくれているヒントです。エラーを解決する過程で、理解が深まります。
3. **楽しむこと！:** これが一番大切かもしれません。「分からないこと」が「分かる」に変わる瞬間、自分の書いたコードが思った通りに動いた瞬間の喜びは、プログラミングの大きな魅力です。ぜひ、楽しみながら学習を進めてください。

さあ、準備はいいですか？ 次の章から、いよいよPythonの世界への冒険を始めましょう！

---

## 第2章 開発環境の準備：初めてのPythonプログラム

**この章で学ぶこと**

- Pythonを自分のパソコンで動かせるようにする方法（インストール）
- Pythonのコードを書くための便利なツール（テキストエディタ/IDE）
- 初めてのPythonプログラムを作成し、実行する手順
- コードの基本的な書き方と保存方法

**必要な前提知識**

- 第1章の内容
- パソコンの基本的な操作（ファイルのダウンロード、ソフトウェアのインストール、フォルダの作成など）

さあ、いよいよPythonに触れていきましょう！ この章では、あなたのパソコンでPythonプログラムを動かすための準備を行います。料理で言えば、キッチンに必要な調理器具を揃えるようなステップです。少しだけ作業が必要ですが、ここを乗り越えれば、すぐにプログラミングを始められますよ！

### Pythonをインストールしよう：冒険の始まり！

まず、Pythonという言語をコンピューターに理解してもらうための「翻訳機」のようなソフトウェア（Pythonインタープリタ）を、あなたのパソコンにインストールする必要があります。

Pythonは無料で利用でき、公式サイトからダウンロードできます。

**1. Python公式サイトへアクセス** Webブラウザを開き、「Python 公式サイト」などで検索するか、以下のURLにアクセスしてください。 `https://www.python.org/`

**2. ダウンロードページへ移動** サイト上部にある「Downloads」メニューにマウスカーソルを合わせると、お使いのOS（Windows, macOSなど）向けの最新版ダウンロードボタンが表示されるはずです。基本的には、そのボタンをクリックしてインストーラーをダウンロードしましょう。 （もし特定のバージョンが必要な場合や、OSが自動で判別されない場合は、「Downloads」メニューからお使いのOSを選択して、安定版（Stable Releases）の中から最新のものを選ぶのがおすすめです。）

**3. インストーラーを実行** ダウンロードしたインストーラーファイルを実行し、画面の指示に従ってインストールを進めます。

**【Windowsでの注意点】** インストールの最初の画面で、**「Add Python X.X to PATH」**（X.Xはバージョン番号）というチェックボックスが**必ず表示されているはずです。ここに必ずチェックを入れてください！** これを忘れると、後で少し面倒な設定が必要になる場合があります。（もしチェックを入れ忘れてインストールしてしまった場合の対処法は、本書のサポートサイト[架空]やWeb検索で確認できます）

[図表：Windowsインストーラーでの「Add Python X.X to PATH」チェックボックスのキャプチャ画像]

**【macOSでの注意点】** macOSには、最初からPython（Python 2系という古いバージョン）が入っている場合がありますが、現在主流のPython 3系を別途インストールするのが一般的です。公式サイトからダウンロードしたインストーラーを使えば問題ありません。インストール後、ターミナルで `python3 --version` と入力してバージョンが表示されればOKです。

**4. インストール確認** 無事にインストールが完了したら、確認してみましょう。

- **Windows:** コマンドプロンプトを開き、`python --version` と入力してエンターキーを押します。インストールしたPythonのバージョン番号が表示されれば成功です。
- **macOS:** ターミナルを開き、`python3 --version` と入力してエンターキーを押します。バージョン番号が表示されれば成功です。

もし「コマンドが見つかりません」のようなエラーが出る場合は、PATHの設定（特にWindowsでチェックを入れ忘れた場合）やインストール自体がうまくいっていない可能性があります。落ち着いてインストールの手順を見直したり、Webでエラーメッセージを検索したりしてみてください。

[プログラマー用語集]

- **インストール:** ソフトウェアをコンピューターで使えるように準備すること。
- **インストーラー:** ソフトウェアのインストール作業を自動で行ってくれるプログラム。
- **公式サイト:** そのソフトウェアを開発・配布している公式のWebサイト。信頼できる情報を得る基本。
- **バージョン:** ソフトウェアの世代や改訂を示す番号。新しいほど機能が追加されたり、問題が修正されたりしていることが多い。
- **PATH（パス）を通す:** コマンドプロンプトやターミナルが、どこにあるプログラムでも名前だけで実行できるように、プログラムの場所をOSに登録すること。（Windowsの「Add Python to PATH」はこれを行ってくれる）
- **コマンドプロンプト (Windows) / ターミナル (macOS, Linux):** キーボードで命令（コマンド）を入力してコンピューターを操作する画面。

### コードを書く道具を選ぼう：快適な作業環境を

Pythonのコード（プログラム）は、極端な話、Windowsの「メモ帳」やmacOSの「テキストエディット」のようなシンプルなテキストエディタでも書くことができます。しかし、プログラミングを快適に進めるためには、もう少し高機能な「コードエディタ」や「統合開発環境（IDE）」を使うのが断然おすすめです。

これらのツールは、

- コードの色分け（シンタックスハイライト）：コードが見やすくなる
- 入力補完：コードの候補を表示してくれて入力が楽になる
- エラーチェック：間違いを早い段階で教えてくれる
- プログラムの実行機能：エディタ内から簡単にプログラムを実行できる

など、便利な機能がたくさん搭載されています。

この本では、現在非常に人気があり、無料で使える高機能なコードエディタである **Visual Studio Code (VS Code)** を使うことを推奨します。

**1. VS Codeのダウンロードとインストール** 公式サイト `https://code.visualstudio.com/` から、お使いのOS用のインストーラーをダウンロードしてインストールしてください。インストールは特に難しい点はないはずです。

**2. Python拡張機能のインストール** VS Codeを起動したら、Pythonのプログラミングをサポートしてくれる「拡張機能」をインストールしましょう。 左側のメニューにある四角いアイコン（拡張機能ビュー）をクリックし、検索ボックスに `Python` と入力します。Microsoftが提供している「Python」拡張機能（通常、一番上に出てきます）を選び、「Install」ボタンをクリックします。

[図表：VS Codeの画面構成とPython拡張機能のインストール画面キャプチャ]

これで、VS CodeでPythonコードを快適に書く準備が整いました！ 他にも様々なエディタやIDE（PyCharmなど）がありますが、まずはVS Codeから始めてみるのが良いでしょう。

[プログラマー用語集]

- **テキストエディタ:** テキストファイルを作成・編集するためのソフトウェア。メモ帳もその一種。
- **コードエディタ:** プログラミングに特化したテキストエディタ。色分けや入力補完などの機能を持つ。
- **IDE (統合開発環境):** コードエディタに加え、プログラムの実行、デバッグ（エラー修正）など、開発に必要な様々な機能を一つにまとめたソフトウェア。VS Codeも高機能なのでIDEに近い存在。
- **拡張機能 (プラグイン):** ソフトウェアに後から追加して、特定の機能（例: Pythonサポート）を強化するもの。

### 最初のプログラム："Hello, World!" を表示させてみよう

さあ、いよいよ最初のPythonプログラムを作成し、実行してみましょう！プログラミングの世界では、最初に画面に「Hello, World!」という文字を表示させるのが、昔からの習わしのようなものになっています。

**1. 作業フォルダの作成** まず、これから作るプログラムファイルを保存しておくためのフォルダを、パソコンの分かりやすい場所（デスクトップやドキュメントフォルダなど）に作成しましょう。フォルダ名は `python_practice` など、自分で分かりやすい名前を付けてください。

**2. VS Codeでフォルダを開く** VS Codeを起動し、「ファイル(File)」メニューから「フォルダを開く(Open Folder...)」を選び、先ほど作成した `python_practice` フォルダを選択します。

**3. 新しいファイルの作成** VS Codeの左側にあるエクスプローラービュー（フォルダのアイコン）で、`python_practice` フォルダ名の上あたりにマウスカーソルを持っていくと表示される「新しいファイル」アイコンをクリックします。ファイル名を `hello.py` と入力してエンターキーを押します。（`.py` というのがPythonファイルの目印（拡張子）です）

[図表：VS Codeでフォルダを開き、新しいファイルを作成する手順のキャプチャ]

**4. コードの入力** `hello.py` が開かれるので、以下の1行を**半角英数で**正確に入力してください。大文字・小文字も区別されます。括弧 `()` や引用符 `""` も重要です。

Python

```
print("Hello, World!")
```

**5. ファイルの保存** コードを入力したら、必ずファイルを保存します。「ファイル(File)」メニューから「保存(Save)」を選ぶか、キーボードショートカット（Windowsなら `Ctrl+S`、macOSなら `Command+S`）を使います。

**6. プログラムの実行** いよいよ実行です！実行方法はいくつかあります。

- **VS Codeのターミナルを使う方法（おすすめ）:**
    
    1. VS Codeの上部メニュー「ターミナル(Terminal)」から「新しいターミナル(New Terminal)」を選びます。画面下部にターミナルが開きます。
    2. ターミナルに `python hello.py` (macOSの場合は `python3 hello.py`) と入力し、エンターキーを押します。
- **OS標準のターミナル/コマンドプロンプトを使う方法:**
    
    1. Windowsならコマンドプロンプト、macOSならターミナルを起動します。
    2. `cd` コマンドを使って、`hello.py` を保存した `python_practice` フォルダまで移動します。（例: `cd Desktop/python_practice` のように）
    3. `python hello.py` (macOSの場合は `python3 hello.py`) と入力し、エンターキーを押します。

**7. 実行結果の確認** ターミナルに、次のように表示されれば成功です！

```
Hello, World!
```

[図表：VS Codeのターミナルで `python hello.py` を実行し、結果が表示された画面キャプチャ]

おめでとうございます！ これがあなたの最初のPythonプログラムです！ たった1行ですが、コンピューターに指示を出して、文字を表示させることができました。

**コードの簡単な解説:**

- `print()`: これはPythonに組み込まれている「関数」の一つで、括弧 `()` の中に入れたものを画面（ターミナル）に表示する役割を持っています。
- `"Hello, World!"`: これは「文字列」と呼ばれるデータの種類で、表示したい文字を `"` (ダブルクォーテーション) または `'` (シングルクォーテーション) で囲んで表現します。

今はまだ「そういうものなんだな」という理解で大丈夫です。これから少しずつ詳しく見ていきましょう。

### よくある間違い：最初のつまづきポイント

初めてプログラムを実行するときは、ちょっとしたことでエラーが出ることがあります。でも心配しないでください。よくある原因を知っておけば、すぐに対処できます。

- **タイプミス (`SyntaxError`, `NameError`):**
    - `print` を `pront` と打ち間違えたり、括弧 `()` や引用符 `""` を全角で入力してしまったり。コードは**必ず半角英数**で、一字一句正確に入力する必要があります。エラーメッセージをよく見て、どこが違うか確認しましょう。
- **ファイルの保存忘れ:** コードを編集した後、保存せずに実行しようとすると、古いコードが実行されてしまいます。実行前には必ず保存する癖をつけましょう (VS Codeなら自動保存の設定もできます)。
- **ファイル名や場所の間違い (`FileNotFoundError`):**
    - ターミナルで実行する際に、ファイル名 `hello.py` を間違えて入力したり、`hello.py` が保存されているフォルダとは違う場所で実行しようとしたりすると、「そんなファイルは見つからないよ」というエラーが出ます。`cd` コマンドで正しいフォルダにいるか確認しましょう。
- **Pythonコマンドが認識されない (WindowsでPATH設定忘れ):**
    - `python` (または `python3`) と入力しても「コマンドが見つかりません」と言われる場合は、インストール時に「Add Python to PATH」にチェックを入れ忘れた可能性が高いです。再度インストーラーを実行して修正するか、環境変数の設定を手動で行う必要があります（方法はWebで検索してみてください）。

エラーが出ても焦らず、まずはエラーメッセージを読むことから始めてみましょう。

---

## 第3章 変数とデータ型：Pythonのデータを扱う

**この章で学ぶこと**

- プログラムの中でデータを一時的に保存しておく「変数」の使い方
- Pythonが扱うデータの種類（数値、文字列、ブール値など）である「データ型」
- データの型を確認したり、別の型に変換したりする方法

**必要な前提知識**

- 第2章の内容（Pythonの実行環境、`print()` 関数の基本的な使い方、コードの書き方と実行）

前の章では、`print("Hello, World!")` というコードを実行して、コンピューターに文字を表示させることに成功しましたね。今回は、プログラムの中でもっと柔軟にデータ、つまり情報（文字や数字など）を扱うための基本を学びます。その鍵となるのが「変数」と「データ型」です。

### 変数って何？：データを入れておく魔法の箱

プログラムを書いていると、計算の途中結果を覚えておいたり、ユーザーが入力した名前を後で使ったりと、様々なデータを一時的に保存しておきたい場面がたくさん出てきます。そんな時に使うのが **変数 (variable)** です。

変数は、**データを入れておくための「名前付きの箱」** だとイメージしてください。箱に好きな名前をつけて、その中にデータ（数字や文字など）を入れておくことができます。そして、後でその名前を呼べば、中に入っているデータを取り出して使うことができるのです。

[図表：変数を「名前付きの箱」で表現したイメージ図。例: `name` という箱に `"田中"` という文字データが入っている]

**変数を使うメリット:**

- **データを再利用できる:** 同じデータを何度も使いたいときに便利です。
- **データに意味のある名前を付けられる:** 例えば `x = 100` よりも `price = 100` の方が、そのデータが何を表しているか分かりやすいですよね。
- **データの変更がしやすい:** 箱の中身を入れ替えれば、プログラムの他の部分でその名前を使っている箇所全てに、変更後のデータが反映されます。

### 変数を使ってみよう：箱に名前をつけてデータを入れる

Pythonで変数を使うのはとても簡単です。

Python

```
変数名 = データ
```

このように、`=`（イコール）を使って、左側に「変数名」、右側に「入れたいデータ」を書きます。これを **代入 (assignment)** と呼びます。 `=` は数学の「等しい」とは少し意味が違い、プログラミングでは「右のデータを左の変数名の箱に入れる」という操作を表します。

**例を見てみましょう:**

Python

```
# name という名前の変数に、文字列 "田中" を代入する
name = "田中"

# age という名前の変数に、数値 25 を代入する
age = 25

# print() を使って変数の中身を表示する
print(name)
print(age)
```

これを `variable_example.py` のような名前で保存して実行すると、次のように表示されます。

```
田中
25
```

`print(name)` と書くと、`name` という変数の中に入っている `"田中"` が表示され、`print(age)` で `age` の中身である `25` が表示されているのが分かりますね。

**変数名の付け方のルール:**

変数名は何でも好きな名前を付けられるわけではなく、いくつかのルールがあります。

- **使える文字:** 半角のアルファベット (a〜z, A〜Z)、数字 (0〜9)、アンダースコア `_` を組み合わせることができます。
- **最初の文字:** 変数名の最初の文字に数字は使えません。(`1st_name` はNG、`name1` はOK)
- **予約語は使えない:** Pythonであらかじめ特別な意味を持つ単語（`if`, `for`, `while`, `print`, `True`, `False` など）は変数名として使えません。VS Codeなどのエディタを使っていると、予約語は色が変わることが多いので気づきやすいでしょう。
- **大文字と小文字は区別される:** `name` と `Name` と `NAME` は、それぞれ別の変数として扱われます。
- **分かりやすい名前を心がける:** `a` や `x` のような短い名前も使えますが、後でコードを見返したときに何のための変数か分かるように、意味のある名前（例: `user_name`, `total_price`, `is_active` など）を付けるのがおすすめです。一般的には、英単語をアンダースコア `_` でつなぐ「スネークケース」という形式がよく使われます（例: `user_name`）。

[プログラマー用語集]

- **変数 (variable):** データを一時的に保存しておくための名前付きの領域（箱）。
- **代入 (assignment):** 変数にデータを格納する操作 (`=`)。
- **変数名 (variable name):** 変数を識別するための名前。
- **予約語 (reserved word / keyword):** プログラミング言語で特別な意味を持つため、変数名などとして使えない単語。

### Pythonが扱うデータの種類（データ型）：箱に入れるものにも種類がある

変数という箱には、様々な種類のデータを入れることができます。Pythonでは、データの種類を **データ型 (data type)** と呼びます。主なデータ型を見ていきましょう。

[図表：データ型の一覧と比較表（整数、浮動小数点数、文字列、ブール値）]

1. **整数 (`int`)**:
    
    - `0`, `10`, `-5` のような、小数点のない数値です。
    
    Python
    
    ```
    count = 10
    year = 2025
    minus_value = -50
    print(count)
    print(year)
    print(minus_value)
    ```
    
2. **浮動小数点数 (`float`)**:
    
    - `3.14`, `0.5`, `-2.7` のような、小数点のある数値です。
    
    Python
    
    ```
    pi = 3.14
    ratio = 0.5
    temperature = -2.7
    print(pi)
    print(ratio)
    print(temperature)
    ```
    
    - **注意:** 整数と浮動小数点数は、計算（足し算 `+`、引き算 `-`、掛け算 `*`、割り算 `/`）ができます。
    
    Python
    
    ```
    price = 100
    tax_rate = 0.1
    tax = price * tax_rate  # 掛け算
    total_price = price + tax # 足し算
    print(total_price) # 結果は 110.0 (float型になります)
    ```
    
3. **文字列 (`str`)**:
    
    - `"こんにちは"`, `'Python'`, `"123"` のように、文字の並びです。**必ず `"` (ダブルクォーテーション) または `'` (シングルクォーテーション) で囲みます。**
    - 数字の `123` と文字列の `"123"` は、コンピューターにとっては全く違うものとして扱われるので注意が必要です。文字列は基本的に計算には使えません（`+` を使うと文字同士を連結できます）。
    
    Python
    
    ```
    greeting = "こんにちは"
    language = 'Python'
    number_string = "123"
    print(greeting)
    print(language)
    print(number_string)
    
    # 文字列の連結
    full_greeting = greeting + "、" + language + "の世界へようこそ！"
    print(full_greeting)
    ```
    
4. **ブール値 (`bool`)**:
    
    - `True` (真、正しい) と `False` (偽、間違い) のどちらか2つの値だけを持つ、特殊なデータ型です。主に、条件が満たされているかどうかを表すのに使われます（第4章で詳しく学びます）。
    - **注意:** `True` と `False` は最初の文字が大文字です。
    
    Python
    
    ```
    is_active = True
    is_greater = 10 > 5 # 10は5より大きいので True になる
    is_equal = 10 == 5 # 10と5は等しくないので False になる
    print(is_active)
    print(is_greater)
    print(is_equal)
    ```
    

### 自分のデータ型は？ 型の確認と変換

変数にどんな型のデータが入っているかを確認したいときは、`type()` という組み込み関数を使います。

Python

```
name = "田中"
age = 25
height = 175.5
is_student = False

print(type(name))   # <class 'str'> と表示される (文字列型)
print(type(age))    # <class 'int'> と表示される (整数型)
print(type(height)) # <class 'float'> と表示される (浮動小数点数型)
print(type(is_student)) # <class 'bool'> と表示される (ブール値型)
```

また、あるデータ型を別のデータ型に変換したい場合もあります。例えば、ユーザーに年齢を入力してもらった場合、それは文字列として扱われるため、そのまま計算に使うことができません。こういう時に **型変換 (type casting)** を行います。

- `int(データ)`: データを整数型に変換します。
- `float(データ)`: データを浮動小数点数型に変換します。
- `str(データ)`: データを文字列型に変換します。

**例：ユーザーに入力してもらった年齢で計算する**

`input()` 関数を使うと、ユーザーがキーボードから入力した内容をプログラムで受け取ることができます。**ただし、`input()` が受け取るデータは、たとえ数字を入力した場合でも、必ず文字列型 (`str`) になります。**

Python

```
# input() で年齢を入力してもらう (この時点では文字列)
input_age_str = input("あなたの年齢を入力してください: ")

# 型を確認してみる
print("入力されたデータの型:", type(input_age_str)) # <class 'str'> と表示される

# このままでは計算できない！ (TypeErrorが発生する)
# print(input_age_str + 1) # これはエラーになる！

# int() を使って文字列を整数に変換する
age_int = int(input_age_str)

# 型を確認してみる
print("変換後のデータの型:", type(age_int)) # <class 'int'> と表示される

# 整数に変換したので、計算ができる
next_year_age = age_int + 1
print("来年のあなたは", next_year_age, "歳ですね！")
```

このように、必要に応じて型を変換することで、様々な計算や処理が可能になります。ただし、何でも変換できるわけではありません（例えば、文字列 `"こんにちは"` を `int()` で整数にしようとするとエラーになります）。

[プログラマー用語集]

- **データ型 (data type):** データの種類（整数、文字列など）。
- **整数 (`int`):** 小数点のない数値。
- **浮動小数点数 (`float`):** 小数点のある数値。
- **文字列 (`str`):** 文字の並び。`"` または `'` で囲む。
- **ブール値 (`bool`):** `True` または `False` のどちらかの値。
- **`type()`:** データ型を調べるための組み込み関数。
- **型変換 (type casting):** あるデータ型を別のデータ型に変換すること (`int()`, `float()`, `str()`)。
- **`input()`:** ユーザーからのキーボード入力を受け取るための組み込み関数（結果は常に文字列）。

### よくある間違い：型に関する落とし穴

変数やデータ型を扱う上で、初心者がよく間違えるポイントを見ておきましょう。

- **変数名のタイプミス (`NameError`):**
    - 定義した変数名と、後で使おうとした変数名が微妙に違う（例: `user_name` を `username` と書いた）。「そんな名前の変数は定義されていませんよ」というエラーが出ます。スペルをよく確認しましょう。
- **文字列と数値の連結/計算エラー (`TypeError`):**
    - `"年齢は" + 25` のように、文字列と数値を `+` で直接つなげようとするとエラーになります。数値を文字列に変換 (`str(25)`) してから連結するか、`print()` のカンマ区切りを使います (`print("年齢は", 25)`)。
    - 逆に、文字列同士を `*` や `/` で計算しようとしてもエラーになります。
- **`input()` の結果は文字列:**
    - `input()` で数字を入力してもらっても、それは文字列型です。計算に使いたい場合は、必ず `int()` や `float()` で数値型に変換するのを忘れないようにしましょう。
- **クォーテーションの付け忘れ/不一致 (`SyntaxError`):**
    - 文字列を `"` や `'` で囲み忘れるとエラーになります。また、開始が `"` で終わりが `'` のように、種類が混在していてもエラーです。

エラーが出たら、メッセージをよく読んで、どの行でどんな種類のエラー（`NameError`, `TypeError`, `SyntaxError` など）が起きているかを確認するのが解決の第一歩です。

---

第3章はここまでです。変数というデータの入れ物と、その中身の種類であるデータ型について学びました。これで、プログラムの中で様々な情報を扱えるようになりましたね！ 型の確認 `type()` や型変換 `int()`, `str()` も、これからよく使うことになるでしょう。

特に `input()` の結果が文字列になる点と、計算のための型変換は重要なポイントでした。

次は、いよいよプログラムの流れをコントロールする方法、「**第4章 条件分岐と繰り返し**」に進みます。もし〜ならこうする、〜の間はこれを繰り返す、といった、プログラムをより賢く動かすための仕組みを学びます。
