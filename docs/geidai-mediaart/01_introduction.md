# TouchDesigner 初めの一歩 - インストールと操作の基本

![](https://lh3.googleusercontent.com/pw/AP1GczMDtZp2IQdMwkwQu4VGm6OSxWe1OjlKD4X90FOuBLZQfS_ozciaP_rlCI_T51VQ0cckdRrg2cDJfnM5cHX-iIUcyqJ2cgXWDVkERvrTu2zI1MRKcDeksPbjqT6GfE4fVnrs4FXwF_JmecxeE2nVIPYjXw=w1486-h989-s-no-gm?authuser=0)

今回は、最初の講義ですので、最初にこの講義の概要とスケジュールについて説明します。

後半は、この講義の演習パートで主に使用するTouchDesigerの紹介と、インストール方法、操作の基本について解説していきます。

## 「メディアアート・プログラミング I」について

### 講義概要

 メディアアートのためのプログラミングの技術を駆使して、実践的な作品制作のための技術とコンセプトメイキングについて学ぶ。個人制作をベースにしながら、立案した作品テーマやコンセプトを掘り下げて作品として制作し展示する。具体的には現在多くのアーティスト達や制作現場で実際に使用されている制作環境であるTouchDesignerをメインの開発環境として、制作環境の基本操作から始めて最終的に自身の作品を制作できる技術の習得を目指す。

- [シラバス (藝大学事システムにログインが必要)](https://cplan-web.off.geidai.ac.jp/public/web/Syllabus/WebSyllabusSansho/UI/WSL_SyllabusSansho.aspx?P1=AAM200501&P2=2024&P3=20240401)
  - 開講責任部署: 美術学部　対象学生：美術（学部・修士・博士）、音楽（学部・修士）、国際（修士）
  - 講義開講時期: 前期
  - 講義区分: 芸術情報センター（AMC）
  - 基準単位数: 3
  - 開講日: 金曜日 3限、4限
  - 校地: 上野(AMC)
  - 授業を行う教員: 田所淳、森山朋絵

※ 履修制限 (定員の設定) は行いません <br/>※ AMCのPCの台数には制限がありますので、ノートPCを持参しての受講 (BYOD) をお薦めします

### この講義のざっくりとした内容

- 演習 (田所担当) : TouchDesignerを用いたリアルタイム3DCGによる表現を中心にしたメディアート制作のための技術を学ぶ
- 講義 (森山先生担当): 美術館での経験をもとに、現場での実践的なメディアアートの展示や企画について学ぶ
- 学期末にはAMCのギャラリーでの作品展示を目指します

## TouchDesignerについて

![](https://i.ytimg.com/vi/wmM1lCWtn6o/maxresdefault.jpg)

- TouchDesigner
  - [https://derivative.ca/](https://derivative.ca/)
  - カナダのDerivative社が開発したビジュアルプログラミング環境
  - インスタレーションアートやプロジェクションマッピング、メディアアートなど、さまざまな映像や音楽、デジタルアートに関するシステムを簡単に構築可能
  - 詳細: [https://derivative.ca/feature/application-building](https://derivative.ca/feature/application-building)

### TouchDesignerを使用した作品例

![](https://derivative.ca/sites/default/files/styles/content_colorbox/public/field/body-images/Astro02.1_sm.jpeg)[Astro Immersive AV Performance - Weidi Zhang](https://www.zhangweidi.com/astro)



![](https://derivative.ca/sites/default/files/field/body-images/BABYMETL_METALIZM_sm_0.jpg)[Interactive live visual system with venue simulator and chart output for BABYMETAL "METALIZM" - Kezzardrix](https://youtu.be/NzWxAE7C2Os?feature=shared&t=94)

 	

![](https://i.ytimg.com/vi/7RsZL-6UCgM/maxresdefault.jpg)[WE ARE NONOTAK 2K19](https://youtu.be/7RsZL-6UCgM?feature=shared)

その他沢山の作品が Derivative社の[Showcase](https://derivative.ca/showcase)で逐次公開されています。参考にしてみてください。

## TouchDesignerのインストールとキー登録

### TouchDesignerのライセンス

TouchDesignerはProcessingやopenFrameworksのようなオープンソースの開発環境ではなく、Derivative社が販売している製品 (プロプライエタリソフトウェア) です。しかし、非商用の利用の場合には無料で使用可能です。

ライセンスの詳細は以下を参照。

![](https://yoppa.org/wp-content/uploads/2024/04/Screenshot-2024-04-02-172445.png)

この演習では、NON-COMMERCIAL版を使用します。以下のような制限があります。

- 解像度は1280x1280 Pixelまでに制限
- 個人使用または学習用の用途に限り使用可能
- すべてのアカウントは10個の非商用キーを付与
- 有料プロジェクトでは使用不可

最初はNON-COMMERCIAL版で使用して、もしより本格的に使用したいと思った場合はEDUCATIONAL版を購入すると良いでしょう。

### インストールとキー登録の手順

TouchDesignerはアプリケーションをインストールした後に、アカウントに付与されたキーを登録する必要があります。以下の手順で行いましょう。

**ユーザー登録: Derivativeのサイトからユーザー登録**

- Derivative Webサイトのページの「[SIGN UP FOR AN ACCOUNT](https://derivative.ca/user/register)」より
- 必要事項を記入して送信
- 登録したemailアドレスにメールが返信されるのでリンクをクリックして登録完了

**TouchDesignerをダウンロード**

- 使用しているOSにあわせて[ダウンロードページ](https://derivative.ca/download)からインストーラーをダウンロード
- インストーラーを起動してインストール (特に設定の変更の必要は無し)

**TouchDesignerを起動してキー登録**

- インストールしたTouchDesignerを起動
- 上部メニューから「Dialogs > Key Mangager」を選択
- 以下の画面が出力されるので登録した情報でログイン<br/>![](https://yoppa.org/wp-content/uploads/2024/04/Screenshot-2024-04-02-174203.png)
- キーを選択して有効化する<br/>![](https://docs.derivative.ca/images/4/4f/KeyManagerCreate.png)

**アプリケーションの再起動**

- アプリケーションを起動し直すとNON-COMMERCIAL版が起動するはず

### AMCのMacにインストールされているTouchDesigner使用の注意

AMCの実習室の全てのiMacにもTouchDesignerがインストールされています。しかしながら、AMCのMacのファイルは起動する度に保存したファイルは消去されて元の状態にリセットされるため、使用する際には以下の手順で毎回キーの登録と削除を行う必要があります。

**ユーザーアカウントの作成**

- キーは各自のDerivativeアカウントに付与された個人のものを使用します
- あらかじめ「[SIGN UP FOR AN ACCOUNT](https://derivative.ca/user/register)」よりユーザー登録しましょう

**起動とキーの有効化**

- コンピューターを起動し、TouchDesignerのアプリケーションを起動
- 上部メニューから「Dialogs > Key Mangager」を選択
- 以下の画面が出力されるので登録した情報でログイン<br/>![](https://yoppa.org/wp-content/uploads/2024/04/Screenshot-2024-04-02-174203.png)
- キーを選択して有効化する<br/>![](https://docs.derivative.ca/images/4/4f/KeyManagerCreate.png)

**TouchDesignerのアプリケーションを使用**

- 個人のノートPCで使用している人と同じようにTouchDesignerが使用可能となります

**キーの削除と終了**

- アプリケーションを終了する前に必ずキーをアプリから削除します
- 上部メニューから「Dialogs > Key Mangager」を選択
- Disableのタブを選択し、Disable Keyボタンを押す<br/>![](https://yoppa.org/wp-content/uploads/2024/04/Screenshot-2024-04-03-054538.jpg)

**システム終了**

- アプリケーションを終了し、システム終了

※この操作を行わないと毎回使用できるキーが減っていってしまうので注意してください!

## TouchDesignerはじめの一歩

   ![](https://learn.derivative.ca/wp-content/uploads/2021/10/101_00-cover.png)

これから先の数回は、Derivative社が提供しているオンライン教材「[The 100 Series: TouchDesigner Fundamentals (TouchDesigner入門)](https://learn.derivative.ca/courses/100-fundamentals/)」を使用して入門から基礎的な内容を学んでいきます。熱意のある受講生の方は先取りしてどんどん予習していってください。

本日は、[101 – Navigating the Environment (制作環境のナビゲーション)](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/)  の前半部分をやっていきましょう!

### 101 – Navigating the Environment (制作環境のナビゲーション)

**タッチデザイナーの文法**

新しいツールや開発環境の学習の大半は、すべてのノブやボタンがどこにあるかを把握することから始まります。この最初のレッスンでは、TouchDesignerを使いこなすことに焦点を当て、必要不可欠なインターフェース要素とコントロール、そして各オペレーターファミリーの基本原則を学びます。

#### 101-1. The User Interface (ユーザーインターフェイス)

- [教材ページ](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/user-interface/)
- [チュートリアル映像 (YouTube)](https://youtu.be/d5n4QbJ2N_Q?feature=shared)
- [サンプルファイルのダウンロード](https://github.com/TouchDesigner/CurriculumExamples/raw/main/toxExamples/TouchDesignerFundamentals/100/101/TDFundamentals-101-userInterface.tox)

#### 101-2. Using the OP Create Dialog (OP作成ダイアログを使う)

- [教材ページ](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/using-the-op-create-dialog/)
- [チュートリアル映像](https://youtu.be/5AaXWvdQrbI?feature=shared)
- [サンプルファイルのダウンロード](https://github.com/TouchDesigner/CurriculumExamples/raw/main/toxExamples/TouchDesignerFundamentals/100/101/TDFundamentals-101-OPCreateDialog.tox)

#### 101-3. Reading Network Anatomy (ネットワークの解剖)

- [教材ページ](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/reading-network-anatomy/)
- [チュートリアル映像](https://youtu.be/0h01Nwj-lAg?feature=shared)
- [サンプルファイルのダウンロード](https://github.com/TouchDesigner/CurriculumExamples/raw/main/toxExamples/TouchDesignerFundamentals/100/101/TDFundamentals-101-networkAnatomy.tox)

#### 101-4. Reading Operator Anatomy (オペレーターの解剖)

- [教材ページ](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/reading-operator-anatomy/)
- [チュートリアル映像](https://youtu.be/wKBtfHTjsNM?feature=shared)
- [サンプルファイルのダウンロード](https://github.com/TouchDesigner/CurriculumExamples/raw/main/toxExamples/TouchDesignerFundamentals/100/101/TDFundamentals-101-operatorAnatomy.tox)

#### 101.5. Operator Wires, References & Links (オペレータの接続、参照、リンク)

- [教材ページ](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/manipulating-operator-wires/)
- [チュートリアル映像](https://youtu.be/wb51mj-HNiQ?feature=shared)
- [サンプルファイルのダウンロード](https://github.com/TouchDesigner/CurriculumExamples/raw/main/toxExamples/TouchDesignerFundamentals/100/101/TDFundamentals-101-opWiresReferencesAndLinks.tox)

## 本日の課題

### 課題: ノイズで遊ぼう!

![](https://yoppa.org/wp-content/uploads/2024/04/Screenshot-2024-04-04-103723.png)

簡単に二次元から四次元のノイズを生成することのできるNoise TOPを使用して、試行錯誤しながら自分なりの「作品」をつくってみる。プログラムの原型は以下からダウンロードしてください。

- [ノイズのサンプル](https://drive.google.com/file/d/1U75L2JLDiDQ1_ghAkZRlp46l6MuPC3OW/view?usp=sharing)

まだ操作の基本を習得した段階ですが、まずはいろいろ試行錯誤しながら操作の基本感覚を身に付けていきましょう。その上で以下のような工夫をしてみてください。

**参考資料**

- [パーリンノイズ (wikipedia)](https://ja.wikipedia.org/wiki/%E3%83%91%E3%83%BC%E3%83%AA%E3%83%B3%E3%83%8E%E3%82%A4%E3%82%BA)
- [The Book of Shaders by Patricio Gonzalez Vivo & Jen Lowe](https://thebookofshaders.com/11/)

#### 基本: 使用されているオペレータのパラメーターを変化させてみる

- [Noise TOP](https://docs.derivative.ca/index.php?title=Noise_TOP) (noise1)
  - ノイズの細かさ
  - ノイズの複雑さ
  - ノイズの種類
  - ...など
- [LFO CHOP](https://docs.derivative.ca/index.php?title=LFO_CHOP) (lfo1)
  - 変化速度
  - 変化する波形の種類
  - ...など
- [HSV Adjust TOP](https://docs.derivative.ca/index.php?title=HSV_Adjust_TOP) (hsvadj1)
  - 色相を変えてみる (hue)
  - 再度を変えてみる (saturation)
  - 明るさを変えてみる (brightness)
  - ...など

#### 応用: オペレーターを追加してみる

- Noise TOPにNoise TOPを接続するとどうなるか?
- HSV Adjust TOPの前後に別のTOPを追加してみる
- LFO CHOPを追加して他のパラメータに参照させてみる
- ...など