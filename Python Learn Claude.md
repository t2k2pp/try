# はじめてのPython：つまずかないプログラミング入門

## まえがき

プログラミングの世界へようこそ！

この本を手に取られたあなたは、プログラミングという新しい扉を開こうとしているのかもしれません。初めての言語としてPythonを選ばれたのは、とても賢明な選択です。

プログラミング学習の旅は、時に困難を伴うこともあります。新しい概念を理解しようとして頭を抱えたり、エラーの意味が分からず立ち止まってしまったり...。そんな経験は、プログラミングを学ぶ誰もが通る道です。

この本は、そんなつまずきポイントをできるだけ減らし、スムーズにPythonの基礎を身につけられるよう設計されています。プログラミング未経験の方でも理解できるよう、専門用語は丁寧に解説し、具体例をたくさん用意しました。

大切なのは「なぜそうするのか」を理解すること。単にコードの書き方を覚えるだけでなく、その背景にある考え方を理解できれば、自分で問題を解決する力が育ちます。

この本があなたのプログラミング学習の良き伴走者となり、Pythonを通じてプログラミングの楽しさを発見するお手伝いができれば幸いです。

さあ、一緒にPythonの世界を探検しましょう！

---

## 目次

1. [プログラミングとPythonの世界：なぜPythonを学ぶのか](#第1章-プログラミングとpythonの世界なぜpythonを学ぶのか)
2. [開発環境の準備：初めてのPythonプログラム](#第2章-開発環境の準備初めてのpythonプログラム)
3. [変数とデータ型：Pythonのデータを扱う](#第3章-変数とデータ型pythonのデータを扱う)
4. [条件分岐と繰り返し：プログラムの流れをコントロールする](#第4章-条件分岐と繰り返しプログラムの流れをコントロールする)
5. [関数：コードを再利用可能にする](#第5章-関数コードを再利用可能にする)
6. [リストと辞書：データを収集して整理する](#第6章-リストと辞書データを収集して整理する)
7. [ファイル操作：データを保存して読み込む](#第7章-ファイル操作データを保存して読み込む)
8. [エラーとデバッグ：問題を見つけて解決する](#第8章-エラーとデバッグ問題を見つけて解決する)
9. [モジュールとライブラリ：Pythonの宝庫を活用する](#第9章-モジュールとライブラリpythonの宝庫を活用する)
10. [ミニプロジェクト①：簡易計算機を作ろう](#第10章-ミニプロジェクト簡易計算機を作ろう)
11. [ミニプロジェクト②：家計簿アプリを作ろう](#第11章-ミニプロジェクト家計簿アプリを作ろう)
12. [ミニプロジェクト③：データ分析の入門](#第12章-ミニプロジェクトデータ分析の入門)
13. [次のステップ：ここからの学習パス](#第13章-次のステップここからの学習パス)

---

# 第1章 プログラミングとPythonの世界：なぜPythonを学ぶのか

## この章で学ぶこと
- プログラミングとは何か
- Pythonの特徴と強み
- Pythonが活用されている分野
- プログラミング学習の効果的なアプローチ

## 必要な前提知識
- 特にありません。プログラミングの知識がゼロでも大丈夫です。

---

### 1.1 プログラミングとは何か

皆さんは、パソコンやスマートフォンを使っているとき、「このソフトウェアはどうやって動いているんだろう？」と考えたことはありませんか？LINE、Twitter、Excelなど、私たちが日常的に使うソフトウェアは、すべて「プログラム」によって動いています。

**プログラミングとは、コンピュータに指示を出すための命令を書くこと**です。人間同士なら「窓を開けて」と言えば伝わりますが、コンピュータは人間の言葉をそのまま理解できません。そこで、コンピュータが理解できる特別な言語（プログラミング言語）を使って指示を出す必要があります。

例えば、「1から10までの数字を足す」という計算をコンピュータにさせたいとき、次のような指示を出します：

1. 合計を記録する変数を用意し、初期値を0にする
2. 1から10までの数字を順番に取り出す
3. 取り出した数字を合計に加える
4. すべての数字を加え終わったら結果を表示する

このような手順をプログラミング言語で書いたものが「プログラム」です。プログラミングを学ぶということは、このようなコンピュータへの指示の出し方を学ぶことなのです。

### 1.2 なぜPythonなのか

プログラミング言語には、C、Java、JavaScript、Ruby、Python、Goなど、たくさんの種類があります。その中でもPythonは、特に初心者にオススメできる言語です。その理由を見ていきましょう。

#### 1.2.1 Pythonの特徴

1. **シンプルで読みやすい文法**

Pythonは「読みやすさ」を重視して設計された言語です。他の言語では必要な記号（セミコロンや中括弧など）が少なく、コードがすっきりしています。

例えば、「Hello, World!」と表示するプログラムを他の言語と比較してみましょう：

**Python**
```python
print("Hello, World!")
```

**Java**
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

どちらも同じことをするプログラムですが、Pythonはたった1行で済みます。

2. **豊富なライブラリ**

ライブラリとは、誰かが作った便利な機能をまとめたものです。Pythonには標準で多くの機能が備わっており、さらに外部ライブラリも充実しています。「車輪の再発明」をする必要がなく、既存の部品を組み合わせて効率的に開発できます。

3. **幅広い用途**

Pythonは汎用性が高く、様々な分野で活用されています：
- Webアプリケーション開発
- データ分析・機械学習
- 自動化スクリプト
- ゲーム開発
- 科学技術計算

4. **大きなコミュニティ**

世界中に多くのPythonユーザーがおり、困ったときに情報を見つけやすいという利点があります。質問サイトやフォーラム、チュートリアルなど、学習リソースが豊富です。

### 1.3 Pythonが活躍する分野

Pythonは様々な分野で利用されていますが、特に以下の分野で強みを発揮しています。

#### 1.3.1 データ分析・機械学習

Python最大の強みの一つが、データ分析や機械学習の分野です。NumPy、pandas、scikit-learnなどのライブラリを使うことで、複雑なデータ処理や機械学習アルゴリズムを簡単に扱えます。

例えば、以下のようなコードで簡単にグラフを描画できます：

```python
import matplotlib.pyplot as plt

# データを用意
x = [1, 2, 3, 4, 5]
y = [2, 4, 6, 8, 10]

# グラフ描画
plt.plot(x, y)
plt.title("グラフの例")
plt.xlabel("X軸")
plt.ylabel("Y軸")
plt.show()
```

このコードを実行すると、X軸とY軸の数値をもとにした直線グラフが表示されます。

#### 1.3.2 Webアプリケーション

DjangoやFlaskといったフレームワークを使うことで、Webアプリケーションを効率的に開発できます。Instagramなどの大規模サービスでもPythonが使われています。

#### 1.3.3 自動化

退屈な作業を自動化するのもPythonの得意分野です。たとえば、大量のファイルの名前を一括で変更したり、複数のExcelファイルからデータを抽出したりといった作業を自動化できます。

#### 1.3.4 AIと科学技術計算

人工知能の研究や科学技術計算の分野でもPythonは広く使われています。TensorFlowやPyTorchといった深層学習のフレームワークや、SciPyといった科学技術計算のライブラリが充実しています。

### 1.4 効果的なプログラミング学習法

プログラミングは、ただ本を読むだけでは身につきません。実際にコードを書いて、試行錯誤することが大切です。この本では、以下のようなアプローチで学んでいくことをおすすめします。

1. **例題を必ず手で入力して実行する**

コピー＆ペーストではなく、手で入力することで理解が深まります。また、入力ミスから「エラーメッセージの読み方」も学べます。

2. **概念を理解したら、応用問題に挑戦する**

各章の終わりにある「チャレンジ問題」に取り組んでみましょう。解答例も掲載していますが、まずは自分で考えてみることが重要です。

3. **小さなプロジェクトを作ってみる**

学んだことを総合的に活用するため、小さなプロジェクトに挑戦しましょう。本書の後半では、実用的なミニプロジェクトを一緒に作っていきます。

4. **エラーを恐れない**

プログラミングでは誰でもエラーを出します。エラーは失敗ではなく「学びの機会」と捉えましょう。エラーメッセージをよく読み、原因を探る習慣をつけると成長が早くなります。

### 1.5 まとめ

この章では、プログラミングとは何か、なぜPythonを学ぶべきか、Pythonの活用分野、効果的な学習法について学びました。Pythonはシンプルな文法、強力なライブラリ、幅広い用途など、初心者にとって学びやすく、また将来的にも様々な分野で活用できる言語です。

次の章では、実際にPythonを使うための環境構築に進んでいきます。いよいよPythonプログラミングの第一歩を踏み出しましょう！

### 理解度チェック

1. プログラミングとは何ですか？
2. Pythonが初心者に適している理由を3つ以上挙げてください。
3. Pythonが特に強みを発揮する分野は何ですか？
4. 効果的なプログラミング学習の方法には、どのようなものがありますか？

### チャレンジ問題

1. あなたの身の回りにあるソフトウェアやアプリを3つ挙げ、それらがどのような指示（プログラム）によって動いているか考えてみましょう。
2. Pythonで解決してみたい問題や作ってみたいプログラムについて考え、書き出してみましょう。

---

# 第2章 開発環境の準備：初めてのPythonプログラム

## この章で学ぶこと
- Pythonのインストール方法
- 統合開発環境（IDE）の選択とセットアップ
- 初めてのPythonプログラムの作成と実行
- Pythonの基本的な使い方

## 必要な前提知識
- パソコンの基本操作（ファイルやフォルダの作成、インターネットの閲覧など）

---

### 2.1 Pythonのインストール

プログラミングを始めるにあたり、まずはPythonを自分のパソコンにインストールしましょう。Pythonは無料で利用できるオープンソースソフトウェアです。

#### 2.1.1 Windowsへのインストール

1. Python公式サイト（https://www.python.org/downloads/）にアクセスします。
2. 「Download Python X.X.X」（Xはバージョンナンバー）のボタンをクリックします。
3. ダウンロードしたインストーラーを実行します。
4. インストール画面で「Add Python X.X to PATH」にチェックを入れてください。これは非常に重要です！
5. 「Install Now」をクリックして標準インストールを実行します。
6. インストールが完了したら「Close」をクリックします。

#### 2.1.2 macOSへのインストール

macOSには標準でPythonがインストールされていることがありますが、最新版を使うためにインストールすることをお勧めします。

1. Python公式サイト（https://www.python.org/downloads/）にアクセスします。
2. 「Download Python X.X.X」のボタンをクリックします。
3. ダウンロードしたパッケージをダブルクリックして開きます。
4. 画面の指示に従ってインストールを進めます。
5. インストールが完了したら「Close」をクリックします。

#### 2.1.3 インストールの確認

インストールがうまくいったか確認するために、コマンドプロンプト（Windows）またはターミナル（macOS）を開いて、次のコマンドを入力してみましょう：

```
python --version
```

または

```
python3 --version
```

すると、インストールされたPythonのバージョンが表示されるはずです：

```
Python 3.12.0
```

バージョン番号は異なる場合がありますが、Pythonのバージョンが表示されれば成功です。

### 2.2 統合開発環境（IDE）の選択

プログラムを書くためには、テキストエディタや統合開発環境（IDE）が必要です。IDEとは、コードの編集、実行、デバッグなどの機能が一体化されたソフトウェアです。初心者におすすめのIDEをいくつか紹介します。

#### 2.2.1 VS Code（Visual Studio Code）

MicrosoftのVS Codeは、軽量で拡張機能が豊富なエディタです。Python拡張機能をインストールすれば、強力なPython開発環境になります。

1. VS Code公式サイト（https://code.visualstudio.com/）からダウンロードします。
2. インストーラーを実行し、画面の指示に従います。
3. VS Codeを起動し、左側のExtensionsタブをクリックします。
4. 検索バーに「Python」と入力し、Microsoftの公式Python拡張機能をインストールします。

#### 2.2.2 PyCharm

JetBrains社のPyCharmは、Python専用のIDEです。無料のCommunity Editionと有料のProfessional Editionがあります。

1. PyCharm公式サイト（https://www.jetbrains.com/pycharm/download/）にアクセスします。
2. 「Community」版をダウンロードします。
3. インストーラーを実行し、画面の指示に従います。

#### 2.2.3 IDLE

IDLEはPythonに標準で付属しているシンプルなIDE（統合開発環境）です。特別なインストールは不要で、すぐに使い始められます。

1. Windowsの場合：スタートメニューからIDLEを検索して起動します。
2. macOSの場合：Applications/Python X.X/からIDLEを起動します。

初心者の方には、まずはIDLEから始めて、慣れてきたらVS CodeやPyCharmに移行することをお勧めします。

### 2.3 はじめてのPythonプログラム

環境が整ったところで、最初のプログラムを書いてみましょう。プログラミングの世界では、伝統的に最初に作るプログラムは「Hello, World!」と表示するものです。

#### 2.3.1 IDLEを使ったプログラミング

1. IDLEを起動します。
2. メニューから「File」→「New File」を選びます。
3. 開いたウィンドウに、次のコードを入力します：

```python
# 私の最初のPythonプログラム
print("Hello, World!")
```

4. メニューから「File」→「Save」を選び、適当な場所（デスクトップなど）に「hello.py」という名前で保存します。
5. メニューから「Run」→「Run Module」を選ぶか、F5キーを押します。
6. するとPythonインタープリタが起動し、結果が表示されます：

```
Hello, World!
```

おめでとうございます！これがあなたの最初のPythonプログラムです。

#### 2.3.2 コードの説明

たった2行のコードですが、一つずつ説明していきます：

1. `# 私の最初のPythonプログラム`

この行は「コメント」と呼ばれるもので、プログラムの動作には影響しません。`#`記号から行末までがコメントとして扱われます。コメントは人間が読むためのメモとして使われます。

2. `print("Hello, World!")`

この行が実際に実行される命令です。`print()`はPythonの「関数」の一つで、括弧内の内容を画面に表示します。`"Hello, World!"`は「文字列」と呼ばれるデータ型で、ダブルクォーテーション（"）で囲まれています。

### 2.4 対話モードを使ってみよう

Pythonには「対話モード」という機能があります。これは、コードを書いて保存・実行するという通常の流れではなく、一行ずつコードを入力してすぐに結果を確認できるモードです。

#### 2.4.1 対話モードの起動

1. IDLEを起動すると、デフォルトで対話モードのウィンドウが開きます。
2. また、コマンドプロンプト/ターミナルで`python`または`python3`と入力しても起動できます。
3. 対話モードが起動すると、以下のようなプロンプトが表示されます：

```
Python 3.12.0 (main, Aug 8 2023, 12:34:56) 
[GCC 9.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

`>>>`の後にコードを入力できます。

#### 2.4.2 対話モードでの操作

対話モードでは、一行ずつコードを入力し、Enterキーを押すとすぐに結果が表示されます：

```python
>>> 2 + 3
5
>>> print("こんにちは")
こんにちは
>>> "Py" + "thon"
'Python'
```

対話モードは簡単なコードを試したり、計算をしたりするのに便利です。

### 2.5 Pythonの実行の仕組み

ここで少し、Pythonプログラムがどのように実行されるのか、その仕組みについて説明します。

#### 2.5.1 インタープリタ言語としてのPython

プログラミング言語には大きく分けて「コンパイル言語」と「インタープリタ言語」があります。

- **コンパイル言語**（C、C++など）：プログラムを実行する前に、コードを機械語に翻訳（コンパイル）します。コンパイルには時間がかかりますが、実行は高速です。
- **インタープリタ言語**（Python、JavaScriptなど）：コードを一行ずつ解釈しながら実行します。実行前の準備は少なくて済みますが、実行速度はやや遅くなることがあります。

Pythonはインタープリタ言語です。`.py`ファイルを実行すると、Pythonインタープリタがコードを一行ずつ読み取って実行していきます。

![Python実行の流れ](https://example.com/python_execution_flow.png)
*図2.1: Pythonプログラムの実行フロー*

#### 2.5.2 Pythonプログラムの実行方法

Pythonプログラムの実行方法は複数あります：

1. **IDEから実行**：IDLEやVS Code、PyCharmなどのIDEの実行ボタンをクリックする
2. **コマンドラインから実行**：コマンドプロンプトやターミナルで次のコマンドを使う
   ```
   python ファイル名.py
   ```
   または
   ```
   python3 ファイル名.py
   ```
3. **対話モードで実行**：小さなコードスニペットをテストする場合

### 2.6 Pythonのインデント規則

Pythonには、他の多くのプログラミング言語とは異なる重要な特徴があります。それは「インデント」（行頭の空白）がコードの構造を決定するということです。

多くの言語では中括弧 `{` と `}` を使ってコードブロックを示しますが、Pythonでは行頭のスペースやタブによって、どの処理がどのブロックに属しているかを判断します。

例えば：

```python
if 天気 == "晴れ":
    print("外出しよう")
    print("帽子を忘れずに")
print("今日も一日頑張ろう")
```

この例では、最初の2つのprint文は「if」ブロックの中にあり、天気が晴れの場合のみ実行されます。最後のprint文はインデントがないため、if文の外にあり、天気に関係なく常に実行されます。

**インデントのルール**：
- インデントには通常、4つのスペースを使います（タブも可能ですが、混在させないよう注意）
- 同じブロック内のコードは同じレベルのインデントにします
- インデントのレベルが変わると、コードブロックも変わります

インデントは最初は少し戸惑うかもしれませんが、慣れるとコードが視覚的に整理され、読みやすくなるというメリットがあります。

### 2.7 まとめ

この章では、Pythonをインストールし、開発環境を整え、初めてのプログラムを作成・実行しました。また、対話モードの使い方や、Pythonプログラムの実行の仕組み、Pythonのインデント規則についても学びました。

これで基本的な開発環境が整いました。次の章からは、いよいよPythonの文法や機能について詳しく学んでいきます。

### 理解度チェック

1. Pythonをインストールする際、Windowsで特に注意すべき設定は何ですか？
2. 対話モードとは何ですか？どのように起動しますか？
3. Pythonはコンパイル言語ですか、それともインタープリタ言語ですか？その特徴は？
4. Pythonでコードブロックを表すために使われる方法は何ですか？

### チャレンジ問題

1. 自分の名前を表示するプログラムを作成してみましょう。
2. 対話モードを使って、好きな計算をいくつか行ってみましょう。
3. 以下のコードにインデントを追加して、正しく動作するようにしてみましょう。

```python
if 5 > 3:
print("5は3より大きい")
print("これは数学的真実です")
print("このメッセージはいつ表示される？")
```

---

# 第3章 変数とデータ型：Pythonのデータを扱う

## この章で学ぶこと
- 変数の概念と使い方
- Pythonの基本的なデータ型（数値、文字列、ブール値）
- データ型の変換方法
- 演算子の種類と使い方

## 必要な前提知識
- 第2章の内容（Pythonの実行環境、基本的な実行方法）

---

### 3.1 変数とは何か

プログラミングにおいて「変数」は、データを一時的に保存しておく「箱」のようなものです。この箱にはデータを入れたり、中身を取り出したり、変更したりすることができます。

#### 3.1.1 変数の基本

Pythonで変数を使う場合、まず「変数名 = 値」という形で変数を作成（これを「代入」と呼びます）します：

```python
# 変数xに数値10を代入
x = 10

# 変数nameに文字列"太郎"を代入
name = "太郎"

# 変数が持つ値を表示
print(x)
print(name)
```

実行結果：
```
10
太郎
```

変数の値は再代入することで変更できます：

```python
count = 1
print(count)  # 1と表示される

count = 2
print(count)  # 2と表示される

count = count + 1
print(count)  # 3と表示される
```

#### 3.1.2 変数名のルール

変数名は自由につけられますが、いくつかのルールがあります：

1. アルファベット、数字、アンダースコア（_）のみ使用可能
2. 数字から始めることはできない
3. 大文字と小文字は区別される（`name`と`Name`は異なる変数）
4. Pythonの予約語（`if`、`for`、`while`など）は使えない

良い変数名の例：
```python
user_name = "山田太郎"
age = 25
total_price = 1500
is_student = True
```

避けるべき変数名の例：
```python
# 数字から始まるのでエラー
1st_place = "金メダル"  # エラー

# スペースを含むのでエラー
user name = "山田太郎"  # エラー

# 予約語なのでエラー
if = 10  # エラー
```

#### 3.1.3 命名規約

読みやすいコードを書くためには、適切な変数名をつけることが重要です。Pythonでは以下のような命名規約があります：

- 変数名は基本的に小文字で書き、単語の区切りにはアンダースコアを使う（snake_case）
  ```python
  first_name = "太郎"
  last_login_date = "2023-04-01"
  ```

- わかりやすい名前をつける（変数の目的や内容を表す名前）
  ```python
  # 悪い例
  a = 10  # aが何を表すのかわからない
  
  # 良い例
  age = 10  # 年齢を表していることがわかりやすい
  ```

### 3.2 基本的なデータ型

Pythonでは様々な種類のデータを扱うことができますが、まずは基本的な3つのデータ型を学びましょう：数値型、文字列型、ブール型。

#### 3.2.1 数値型（Numeric Type）

数値型には主に以下の種類があります：

- **整数型（int）**：小数点のない整数
  ```python
  age = 25
  count = -10
  ```

- **浮動小数点型（float）**：小数点を含む数
  ```python
  height = 175.5
  temperature = -2.5
  ```

数値型では、以下のような演算が可能です：

```python
# 基本的な四則演算
a = 10
b = 3

print(a + b)   # 加算: 13
print(a - b)   # 減算: 7
print(a * b)   # 乗算: 30
print(a / b)   # 除算: 3.3333333333333335（浮動小数点数）
print(a // b)  # 整数除算: 3（小数点以下切り捨て）
print(a % b)   # 剰余（余り）: 1
print(a ** b)  # べき乗: 1000（10の3乗）
```

#### 3.2.2 文字列型（String Type）

文字列型は、テキストデータを表現するためのデータ型です。シングルクォート（'）またはダブルクォート（"）で囲みます：

```python
name = "山田太郎"
message = '今日は晴れです'
```

三重引用符（'''または"""）を使うと、複数行の文字列を作成できます：

```python
long_text = """これは
複数行にわたる
文字列です。"""

print(long_text)
```

実行結果：
```
これは
複数行にわたる
文字列です。
```

文字列には以下のような操作ができます：

```python
# 文字列の結合
first_name = "太郎"
last_name = "山田"
full_name = last_name + first_name
print(full_name)  # "山田太郎"

# 文字列の繰り返し
star_line = "*" * 10
print(star_line)  # "**********"

# 文字列の長さを取得
text = "こんにちは"
length = len(text)
print(length)  # 5

# 文字列の一部を取得（インデックス）
message = "Python"
print(message[0])   # "P"（最初の文字）
print(message[1])   # "y"（2番目の文字）
print(message[-1])  # "n"（最後の文字）

# 文字列のスライス
print(message[0:3])   # "Pyt"（0から2までの文字）
print(message[2:])    # "thon"（2から最後までの文字）
print(message[:4])    # "Pyth"（最初から3までの文字）
```

#### 3.2.3 ブール型（Boolean Type）

ブール型は`True`（真）または`False`（偽）の2つの値のみを持つデータ型です。条件判断などに使用されます：

```python
is_student = True
has_license = False

print(is_student)  # True
print(has_license)  # False
```

ブール型では、以下のような論理演算が可能です：

```python
a = True
b = False

print(a and b)  # 論理積（AND）: False
print(a or b)   # 論理和（OR）: True
print(not a)    # 論理否定（NOT）: False
```

#### 3.2.4 データ型の確認方法

変数のデータ型を確認するには、`type()`関数を使います：

```python
a = 10
b = 3.14
c = "Hello"
d = True

print(type(a))  # <class 'int'>
print(type(b))  # <class 'float'>
print(type(c))  # <class 'str'>
print(type(d))  # <class 'bool'>
```

### 3.3 データ型の変換

異なるデータ型の間で変換が必要な場合があります。例えば、ユーザーから入力された文字列を数値として扱いたい場合などです。

#### 3.3.1 型変換関数

Pythonには、データ型を変換するための関数が用意されています：

- `int()`：他の型から整数に変換
- `float()`：他の型から浮動小数点数に変換
- `str()`：他の型から文字列に変換
- `bool()`：他の型からブール値に変換

使用例：

```python
# 文字列から数値への変換
age_str = "25"
age_int = int(age_str)
print(age_int + 5)  # 30（数値として計算可能）

# 数値から文字列への変換
count = 100
count_str = str(count)
print("カウント: " + count_str)  # "カウント: 100"

# 整数から浮動小数点数への変換
x = 10
y = float(x)
print(y)  # 10.0

# 様々な値からブール値への変換
print(bool(1))       # True（0以外の数値はTrue）
print(bool(0))       # False（0はFalse）
print(bool(""))      # False（空文字列はFalse）
print(bool("Hello")) # True（空でない文字列はTrue）
```

#### 3.3.2 ユーザー入力の取得と変換

プログラムでユーザーからの入力を受け取るには、`input()`関数を使います。`input()`は常に文字列を返すため、数値として扱いたい場合は型変換が必要です：

```python
# ユーザーに名前を尋ねる
name = input("あなたの名前は？ ")
print("こんにちは、" + name + "さん！")

# ユーザーに年齢を尋ね、数値に変換
age_str = input("あなたの年齢は？ ")
age = int(age_str)
next_year_age = age + 1
print("来年は" + str(next_year_age) + "歳ですね。")
```

実行例：
```
あなたの名前は？ 太郎
こんにちは、太郎さん！
あなたの年齢は？ 25
来年は26歳ですね。
```

### 3.4 演算子

演算子は、データに対して操作を行うための記号です。既に数値型のところで一部の演算子を紹介しましたが、ここでもう少し詳しく見ていきます。

#### 3.4.1 算術演算子

数値に対して計算を行う演算子です：

| 演算子 | 説明 | 例 | 結果 |
|--------|------|-----|------|
| + | 加算 | 5 + 2 | 7 |
| - | 減算 | 5 - 2 | 3 |
| * | 乗算 | 5 * 2 | 10 |
| / | 除算 | 5 / 2 | 2.5 |
| // | 整数除算 | 5 // 2 | 2 |
| % | 剰余（余り） | 5 % 2 | 1 |
| ** | べき乗 | 5 ** 2 | 25 |

#### 3.4.2 比較演算子

2つの値を比較してブール値（TrueまたはFalse）を返す演算子です：

| 演算子 | 説明 | 例 | 結果 |
|--------|------|-----|------|
| == | 等しい | 5 == 5 | True |
| != | 等しくない | 5 != 2 | True |
| > | より大きい | 5 > 2 | True |
| < | より小さい | 5 < 2 | False |
| >= | 以上 | 5 >= 5 | True |
| <= | 以下 | 5 <= 4 | False |

使用例：

```python
a = 10
b = 5

print(a == b)  # False
print(a != b)  # True
print(a > b)   # True
print(a < b)   # False
print(a >= b)  # True
print(a <= b)  # False
```

#### 3.4.3 論理演算子

ブール値に対して論理演算を行う演算子です：

| 演算子 | 説明 | 例 | 結果 |
|--------|------|-----|------|
| and | 論理積（両方がTrueならTrue） | True and False | False |
| or | 論理和（どちらかがTrueならTrue） | True or False | True |
| not | 論理否定（TrueをFalseに、FalseをTrueに） | not True | False |

使用例：

```python
sunny = True
warm = False

# 晴れていて、暖かい
print(sunny and warm)  # False

# 晴れているか、暖かい
print(sunny or warm)   # True

# 晴れていない
print(not sunny)       # False
```

#### 3.4.4 代入演算子

変数に値を代入するための演算子です：

| 演算子 | 説明 | 例 | 同等の式 |
|--------|------|-----|----------|
| = | 代入 | x = 5 | x = 5 |
| += | 加算して代入 | x += 3 | x = x + 3 |
| -= | 減算して代入 | x -= 3 | x = x - 3 |
| *= | 乗算して代入 | x *= 3 | x = x * 3 |
| /= | 除算して代入 | x /= 3 | x = x / 3 |
| //= | 整数除算して代入 | x //= 3 | x = x // 3 |
| %= | 剰余して代入 | x %= 3 | x = x % 3 |
| **= | べき乗して代入 | x **= 3 | x = x ** 3 |

使用例：

```python
x = 10
print(x)  # 10

x += 5    # x = x + 5 と同じ
print(x)  # 15

x *= 2    # x = x * 2 と同じ
print(x)  # 30

x %= 7    # x = x % 7 と同じ
print(x)  # 2
```

### 3.5 文字列のフォーマット

文字列と変数を組み合わせて表示する方法をいくつか紹介します。

#### 3.5.1 文字列連結

最も基本的な方法は、`+`演算子を使って文字列を連結することです：

```python
name = "太郎"
age = 25

message = "私の名前は" + name + "で、年齢は" + str(age) + "歳です。"
print(message)  # "私の名前は太郎で、年齢は25歳です。"
```

数値型は文字列と直接連結できないため、`str()`で変換する必要があります。

#### 3.5.2 フォーマット文字列（f-string）

Python 3.6以降では、f-string（フォーマット文字列）という便利な機能が使えます。文字列の前に`f`をつけ、変数を`{}`で囲むだけです：

```python
name = "太郎"
age = 25

message = f"私の名前は{name}で、年齢は{age}歳です。"
print(message)  # "私の名前は太郎で、年齢は25歳です。"
```

f-stringでは、中括弧`{}`の中に式を書くこともできます：

```python
a = 5
b = 3
print(f"{a} + {b} = {a + b}")  # "5 + 3 = 8"
print(f"{a}の2乗は{a ** 2}です。")  # "5の2乗は25です。"
```

#### 3.5.3 format()メソッド

もう一つの方法は、文字列の`format()`メソッドを使う方法です：

```python
name = "太郎"
age = 25

message = "私の名前は{}で、年齢は{}歳です。".format(name, age)
print(message)  # "私の名前は太郎で、年齢は25歳です。"

# インデックスを指定することもできます
message2 = "私の名前は{0}で、年齢は{1}歳です。{0}と呼んでください。".format(name, age)
print(message2)  # "私の名前は太郎で、年齢は25歳です。太郎と呼んでください。"

# 名前付き引数も使えます
message3 = "私の名前は{name}で、年齢は{age}歳です。".format(name=name, age=age)
print(message3)  # "私の名前は太郎で、年齢は25歳です。"
```

### 3.6 まとめ

この章では、Pythonの基本的なデータ型（数値型、文字列型、ブール型）と変数の使い方を学びました。また、データ型の変換方法や、様々な演算子、文字列のフォーマット方法についても学びました。

データと変数はプログラミングの基礎中の基礎です。これらの概念をしっかり理解することで、より複雑なプログラムを書く基盤ができます。

次の章では、条件分岐や繰り返し処理など、プログラムの流れをコントロールする方法を学びます。

### 理解度チェック

1. 変数とは何ですか？どのように使いますか？
2. Pythonの基本的なデータ型を3つ挙げ、それぞれの特徴を説明してください。
3. 文字列型の変数に対して行える操作を3つ以上挙げてください。
4. ブール型の値は何と何ですか？どのような場面で使われますか？
5. 代入演算子 `+=` の意味を説明してください。

### チャレンジ問題

1. あなたの名前と年齢を変数に格納し、「私の名前は○○で、○○歳です。」と表示するプログラムを作成してください。
2. 円の半径を入力してもらい、その円の面積を計算して表示するプログラムを作成してください。（円の面積＝π×半径^2、πは3.14とします）
3. 摂氏温度を入力してもらい、華氏温度に変換するプログラムを作成してください。（変換式：華氏 = 摂氏 × 9/5 + 32）

---
