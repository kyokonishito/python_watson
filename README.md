# python_watson
pythonからWatson APIを呼び出すサンプルです。

## ハンズオンの前提条件
ハンズオン資料の以下が完了している必要があります：　
- Watson Studioのセットアップ
- Watson Studioの起動
- Projectの作成

## ハンズオンの流れ(全Lab共通)
1. IBM Cloud: サービスの作成
2. IBM Cloud: 作成したサービスの資格情報取得<br/>
　     - API KEY(API鍵)とURL

3. Watson Studio: githubのファイルからnotebookの作成
4. Watson Studio: notebookの指示にしたがってAPIを実行する<br/>
　      - 2で取得したAPI KEYとURLを使用

## ハンズオン
Watson StudioでProjectの画面を表示してください。
Lab１からLab4まで順に実施してください（4でLab情報を指定します）。

### 1. 上のメニューから`Add to project`をクリック
します。<br/>
<img src="images/add_to_project.png" width="90%">


### 2.  表示された`Choose asset type`から`Notebook`をクリックします。<br/>
<img src="images/choose_asset_type.png" width="90%">

### 3.  表示された`New notebook`から`From URL`をクリックします。<br/>
<img src="images/from_url.png" width="90%">

### 4. `Name` と `Notebook URL`にそれぞれ以下の値をハンズオンするLabに応じてコピペします。<br/>

#### Lab1: Language Translator 翻訳
Name: `Lab1` <br/>
Notebook URL: `https://raw.githubusercontent.com/kyokonishito/python_watson/master/notebooks/Lab1.ipynb`


#### Lab2: Natural Language Understanding 自然言語解析
Name: `Lab2`<br/>
Notebook URL: `https://raw.githubusercontent.com/kyokonishito/python_watson/master/notebooks/Lab2.ipynb`

#### Lab3: isual Recognition 画像認識
Name: `Lab3`<br/>
Notebook URL: `https://raw.githubusercontent.com/kyokonishito/python_watson/master/notebooks/Lab3.ipynb`


#### Lab4: Personality Insights テキストから筆者の性格を推定する
Name: `Lab4`<br/>
Notebook URL: `https://raw.githubusercontent.com/kyokonishito/python_watson/master/notebooks/Lab4.ipynb`

### 5. `Select runtime`に`python3.5`が入っているものを選択して(通常はデフォルト値のままでよい)、`Create Notebook`をクリック<br/>
<img src="images/select_runtime.png" width="90%">

### 6. Notebookが開きますので、ロードされたNotebookの指示にしたがってハンズオンを進めてください。

### 7. 全て終わったら、右上のSaveアイコンをクリックし、次に右上に表示されている現在のプロジェクトの名の文字をクリックしてプロジェクトの画面に戻ってください。<br/>
<img src="images/comp_lab.png" width="90%">

### 8. 次のLabがあれば1に戻って再度Notebookを作成します。

>### Hint: 保存したNotebookを呼び出すには?
>Projectの画面で`Assets`タブをクリックして表示されたページの、`Notebook`の見出しの下にこれまで作成したNotebooｋのリストが表示されています。呼び出したいNotebooｋの名前をクリックするとそのNotebooｋが開きます。<br/>
実行や編集したい場合は、Notebookが開いた後、上部にある鉛筆アイコンをクリックして、`Edit Mode`にしてください。あるいは`Notebook`のList上で鉛筆アイコンを直接クリックしてください。<br/>
<img src="images/edit1.png" width="90%">
<img src="images/edit2.png" width="90%">


## オプションハンズオン
Watson APIではありませんが余力があればWatson Machine Learningにも触れてみましょう。2019年6月5日に開催したDeveloper Dojo Shibuyaでのハンズオン資料です：
### [Watson Studioで機械学習ハンズオン](https://speakerdeck.com/kyokonishito/ml-handson-with-watson-studio)

