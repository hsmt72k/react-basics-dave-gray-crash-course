# Dave Gray's React Hands On Crash Course

React を学ぶことは、Web 開発者としてのキャリアを広げるための最良の方法の1つです。
このチュートリアルシリーズは、React を紹介し、ステップバイステップで学習することができます。

> 動画リンクはクリックしても別タブで開きません。
> 別タブで開きたい場合は、Ctrl（Command）キーを押しながらリンクをクリックしてください


この動画シリーズで React の基礎を学んだら、大規模アプリで状態管理を行うのに必要になる
Redux Toolkit の使い方を以下の動画シリーズで学びましょう。

React Redux Toolkit Tutorials:  
https://github.com/hsmt72k/redux-toolkit-dave-gray-crash-course

## CHAPTERS: React Tutorials

React tutorial series playlist:  
https://www.youtube.com/playlist?list=PL0Zuz27SZ-6PrE9srvEn8nbhOOyxnWXfp

CHAPTER 01. 
<a href="#start_here">
    <strong>Start Here</strong>
<a>

CHAPTER 02. 
<a href="#app_component_and_jsx">
    <strong>App Component & JSX</strong>
<a>

CHAPTER 03. 
<a href="#functional_components">
    <strong>Functional Components</strong>
<a>

CHAPTER 04. 
<a href="#css_styles">
    <strong>CSS Styles in React</strong>
<a>

CHAPTER 05. 
<a href="#click_events">
    <strong>Click Events</strong>
<a>

CHAPTER 06. 
<a href="#usestate_hook">
    <strong>useState Hook</strong>
<a>

CHAPTER 07. 
<a href="#lists_and_keys">
    <strong>Lists & Keys</strong>
<a>

CHAPTER 08. 
<a href="#props_and_prop_drilling">
    <strong>Props and Prop Drilling</strong>
<a>

CHAPTER 09. 
<a href="#controlled_form_inputs">
    <strong>Controlled Form Inputs</strong>
<a>

CHAPTER 10. 
<a href="#project_challenge">
    <strong>腕試し Project Challenge</strong>
<a>

CHAPTER 11. 
<a href="#useeffect_hook">
    <strong>useEffect Hook</strong>
<a>

CHAPTER 12. 
<a href="#json_server">
    <strong>JSON Server</strong>
<a>

CHAPTER 13. 
<a href="#fetching_api_data">
    <strong>Fetching API Data</strong>
<a>

CHAPTER 14. 
<a href="#crud_operations">
    <strong>CRUD Operations</strong>
<a>

CHAPTER 15. 
<a href="#fetch_data_challenge">
    <strong>Fetch Data Challenge</strong>
<a>

CHAPTER 16. 
<a href="#router">
    <strong>React Router</strong>
<a>

CHAPTER 17. 
<a href="#router_hooks_and_links">
    <strong>Router Hooks & Links</strong>
<a>

CHAPTER 18. 
<a href="#flexbox_components">
    <strong>Flexbox Components</strong>
<a>

CHAPTER 19. 
<a href="#axios_api_requests">
    <strong>Axios API Requests</strong>
<a>

CHAPTER 20. 
<a href="#custom_hooks">
    <strong>Custom Hooks</strong>
<a>

CHAPTER 21. 
<a href="#context_api">
    <strong>Context API useContext</strong>
<a>

CHAPTER 22. 
<a href="#deploy_to_github_pages_and_netlify">
    <strong>Deploy a React App to GitHub Pages and Netlify</strong>
<a>

<h2 id="start_here">CHAPTER 01. Start Here</h2>

<a href="https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=5">
    <img src="./images/thumbnail_01.start_here.jpg" width="240px">
</a>

[https://youtu.be/TeeAp5zkYnI](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=5)

この動画では、React を始めるために必要なセットアップ、開発環境、学習リソースについて説明します。
最初の React アプリを作成し、JSX とコンポーネントについてより深く学んでいく第一歩を始めましょう。

[[00:05](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=5)] React とは何か  
[[00:50](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=50)] React エンジニアの求人状況  
[[01:28](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=88)] Node.js と React Dev Tools のインストール  
[[02:18](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=138)] create-react-app   
[[04:03](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=243)] VSCode の拡張機能と設定  
[[05:38](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=338)] VSCode で React プロジェクトを開く  
[[06:27](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=387)] React プロジェクトファイルを見る  
[[11:12](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=672)] サンプルの React プロジェクトを実行する

### Topics

- Node.js をインストール
- ブラウザに React DevTools 拡張をインストール
- create-react-app で React プロジェクト作成
- VSCode に dsznajder.es7-react-js-snippets 拡張機能をインストール
- preferences で emmet を検索して、User の settings.json 、 "emmet.includeLanguages": に "javascript": "javascriptreact" を追加
- `code .` コマンドで新しい VSCode インスタンスを開く
- create-react-app で作られる各ディレクトリ、ファイルの説明
- App.test.js, reportWebVitals.js, setupTests.js, logo.svg の削除
- 削除したファイルを使用している箇所のソースコードを修正
- 編集したファイルのファイル名は VSCode で濃いクリーム色になり、Git の検知で Modified(変更)の略として「M」が表示される
- getElementById('root') の説明
- npm start で開発サーバ起動
- ホットリロードの動作確認
- Ctrl + C キーで開発サーバの起動停止

<h2 id="app_component_and_jsx">CHAPTER 02. App Component & JSX</h2>

<a href="https://www.youtube.com/embed/jzd70d0yc7E?autoplay=1&start=5">
    <img src="./images/thumbnail_02.app_component_and JSX.jpg" width="240px">
</a>

[https://youtu.be/jzd70d0yc7E](https://www.youtube.com/embed/jzd70d0yc7E?autoplay=1&start=5)

この動画では、React App コンポーネントと JSX について説明します。
App コンポーネントは、デフォルトで create-react-app で作成されます。
JSX は、Javascript と XML の略です。JSX はコンポーネントのテンプレートとして機能し、
Javascript の式を挿入することができます。

[[00:05](https://www.youtube.com/embed/jzd70d0yc7E?autoplay=1&start=5)] すべての始まり  
[[00:50](https://www.youtube.com/embed/jzd70d0yc7E?autoplay=1&start=46)] React の App コンポーネント  
[[01:28](https://www.youtube.com/embed/jzd70d0yc7E?autoplay=1&start=186)] JSX  
[[02:18](https://www.youtube.com/embed/jzd70d0yc7E?autoplay=1&start=263)] データをテキストとしてレンダリングする  
[[04:03](https://www.youtube.com/embed/jzd70d0yc7E?autoplay=1&start=452)] JSX にコメントを追加するには  
[[05:38](https://www.youtube.com/embed/jzd70d0yc7E?autoplay=1&start=503)] JSX に Javascript の式を記述する

<h2 id="functional_components">CHAPTER 03. Functional Components</h2>

<a href="https://www.youtube.com/embed/NJ_qbsLf52w?autoplay=1&start=5">
    <img src="./images/thumbnail_03.functional_components.jpg" width="240px">
</a>

[https://youtu.be/NJ_qbsLf52w](https://www.youtube.com/embed/NJ_qbsLf52w?autoplay=1&start=5)

この動画では、React の関数コンポーネントを作成する方法を学習します。
コンポーネントツリーで機能コンポーネントを構築していきます。

[[00:05](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=5)] はじめに  
[[00:53](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=50)] VSCode の ES7 React JS Snippets 拡張機能  
[[01:14](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=88)] コンポーネントのインポート  
[[01:40](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=138)] Header コンポーネントの作成    
[[04:51](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=243)] Content コンポーネントの作成  
[[06:50](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=338)] Footer コンポーネントの作成  
[[08:34](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=387)] コンポーネントはロジックをカプセル化する  
[[09:11](https://www.youtube.com/embed/TeeAp5zkYnI?autoplay=1&start=672)] React Dev Tools を使用してコンポーネントツリーを 確認 する

<h2 id="css_styles">CHAPTER 04. CSS Styles in React</h2>

<a href="https://www.youtube.com/embed/RYDXbp7vmjc?autoplay=1?autoplay=1&start=5">
    <img src="./images/thumbnail_04.CSS_styles.jpg" width="240px">
</a>

[https://youtu.be/RYDXbp7vmjc](https://www.youtube.com/embed/RYDXbp7vmjc?autoplay=1&start=5)

この動画では、React で CSS スタイルを適用する方法について学習します。
CSSの適用方法には、いくつかのアプローチがあります。ここでは、React で CSS を適用する際の代表的なアプローチの例を見ていきます。

[[00:05](https://www.youtube.com/embed/RYDXbp7vmjc?autoplay=1&start=5)] React で CSS スタイルを追加する様々な方法
[[01:36](https://www.youtube.com/embed/RYDXbp7vmjc?autoplay=1&start=96)] JSX に挿入するインラインスタイルの例  
[[04:19](https://www.youtube.com/embed/RYDXbp7vmjc?autoplay=1&start=259)] プロジェクトのクリーンアップ  
[[05:05](https://www.youtube.com/embed/RYDXbp7vmjc?autoplay=1&start=305)] React プロジェクトに CSS スタイルを適用する   
[[06:37](https://www.youtube.com/embed/RYDXbp7vmjc?autoplay=1&start=397)] CSS をインポートする  

<h2 id="click_events">CHAPTER 05. Click Events</h2>

<a href="https://www.youtube.com/embed/s4dCiHvU-Pw?autoplay=1&start=5">
    <img src="./images/thumbnail_05.click_events.jpg" width="240px">
</a>

[https://youtu.be/s4dCiHvU-Pw](https://www.youtube.com/embed/s4dCiHvU-Pw?autoplay=1&start=5)

Click イベントは、React アプリで最も一般的なイベントかもしれません。
この動画では、React アプリをクリックイベントに反応させる方法と、その様々な適用方法について学びます。

[[00:05](https://www.youtube.com/embed/s4dCiHvU-Pw?autoplay=1&start=5)] React の onClick イベント  
[[00:50](https://www.youtube.com/embed/s4dCiHvU-Pw?autoplay=1&start=157)] クリックイベントでパラメータを渡す   
[[01:28](https://www.youtube.com/embed/s4dCiHvU-Pw?autoplay=1&start=298)] クリックを待つか、すぐに関数を呼び出すか  
[[02:18](https://www.youtube.com/embed/s4dCiHvU-Pw?autoplay=1&start=336)] クリックイベント関数でイベントオブジェクトを使用する  
[[04:03](https://www.youtube.com/embed/s4dCiHvU-Pw?autoplay=1&start=449)] React の onDoubleClick イベント  
[[05:38](https://www.youtube.com/embed/s4dCiHvU-Pw?autoplay=1&start=498)] 次の useState のチュートリアルが必要になる理由  

<h2 id="usestate_hook">CHAPTER 06. useState Hook</h2>

<a href="https://www.youtube.com/embed/P9ELDeqNToo?autoplay=1&start=5">
    <img src="./images/thumbnail_06.useState_hook.jpg" width="240px">
</a>

[https://youtu.be/P9ELDeqNToo](https://www.youtube.com/embed/P9ELDeqNToo?autoplay=1&start=5)

React の useState フックは、React のフックの中で最も一般的なものです。
なぜなら、React は状態の変化に反応することが重要だからです。
React のアプリでは、useState フックを使って状態の変化にともなう制御を行うことができます。

[[00:05](https://www.youtube.com/embed/P9ELDeqNToo?autoplay=1&start=5)] 前回のおさらい  
[[01:34](https://www.youtube.com/embed/P9ELDeqNToo?autoplay=1&start=35)] コンポーネントの状態変化に適応する   
[[02:07](https://www.youtube.com/embed/P9ELDeqNToo?autoplay=1&start=94)] useState フックのインポート  
[[03:23](https://www.youtube.com/embed/P9ELDeqNToo?autoplay=1&start=127)] コンポーネントのデフォルト状態を設定する   
[[05:06](https://www.youtube.com/embed/P9ELDeqNToo?autoplay=1&start=203)] 新しい状態の値を設定する  
[[05:46](https://www.youtube.com/embed/P9ELDeqNToo?autoplay=1&start=306)] useState の2つ目の例  
[[05:46](https://www.youtube.com/embed/P9ELDeqNToo?autoplay=1&start=346)] useState で失敗しないために 
[[10:31](https://www.youtube.com/embed/P9ELDeqNToo?autoplay=1&start=631)] まとめ  

<h2 id="lists_and_keys">CHAPTER 07. Lists & Keys</h2>

<a href="https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=5">
    <img src="./images/thumbnail_07.lists_and_keys.jpg" width="240px">
</a>

[https://youtu.be/Fcj6DQT3nVA](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=5)

この動画では、React のリストとキーについて学びます。
React のリスト内のすべての要素には、キーが必要であることが分かります。
また、React の JSX 内で要素の動的なリストを生成する方法についても学びます。

[[00:05](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=5)] チュートリアルの設定  
[[01:30](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=90)] デフォルトの状態を変更する  
[[03:02](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=182)] React Dev Toolsで新しい状態を表示する  
[[03:57](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=237)] map() でリストアイテムを表示する  
[[06:23](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=383)] 要素のリストにはキーが必要  
[[07:17](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=437)] React のリスト表示を確認する  
[[07:35](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=455)] react-icons パッケージを追加する  
[[12:39](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=759)] Reac のリストに CSS を適用する  
[[15:20](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=920)] クリックしてもチェックマークが表示されない理由  
[[15:52](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=952)] onChange リスナーを追加する  
[[18:24](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=1104)] handleCheck 関数  
[[22:05](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=1325)] React Dev Tools で新しいコンポーネントの状態を表示する  
[[23:19](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=1399)] 状態を localStorage に保存する  
[[24:08](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=1448)] onDoubleClick リスナーを追加する  
[[25:12](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=1512)] 条件付き CSS スタイリングを追加する  
[[26:07](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=1567)] onClick リスナーを追加する  
[[27:40](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=1660)] handleDelete 関数  
[[29:32](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=1772)] 空リストメッセージを追加する  
[[32:07](https://www.youtube.com/embed/Fcj6DQT3nVA?autoplay=1&start=1927)] いつ localStorage から状態を読み込むか？  

<h2 id="props_and_prop_drilling">CHAPTER 08. Props and Prop Drilling</h2>

<a href="https://www.youtube.com/embed/XyIXMQ9SZmI?autoplay=1&start=5">
    <img src="./images/thumbnail_08.props_and_prop_drilling.jpg" width="240px">
</a>

[https://youtu.be/XyIXMQ9SZmI](https://www.youtube.com/embed/XyIXMQ9SZmI?autoplay=1&start=5)

React の props と prop のバケツリレー（Prop Drilling）は、React の学習に興味がある人なら必ず学ぶべき概念です。
React のコンポーネントは、しばしば props として渡されるデータを共有する必要があります。
Prop Drilling は、親コンポーネントから子コンポーネントに props を渡します。

[[00:05](https://www.youtube.com/embed/XyIXMQ9SZmI?autoplay=1&start=5)] props とは？  
[[01:28](https://www.youtube.com/embed/XyIXMQ9SZmI?autoplay=1&start=88)] コンポーネントへの prop の受け渡し  
[[02:47](https://www.youtube.com/embed/XyIXMQ9SZmI?autoplay=1&start=167)] prop の再構築   
[[03:43](https://www.youtube.com/embed/XyIXMQ9SZmI?autoplay=1&start=223)] デフォルトの props  
[[04:51](https://www.youtube.com/embed/XyIXMQ9SZmI?autoplay=1&start=291)] 親コンポーネントへの状態遷移   
[[10:17](https://www.youtube.com/embed/XyIXMQ9SZmI?autoplay=1&start=617)] Footer コンポーネントへの prop の受け渡し  
[[12:44](https://www.youtube.com/embed/XyIXMQ9SZmI?autoplay=1&start=764)] ItemList コンポーネントへの Prop Drilling  
[[19:18](https://www.youtube.com/embed/XyIXMQ9SZmI?autoplay=1&start=1158)] 再利用可能な LineItemコンポーネントへの Prop Drilling  

<h2 id="controlled_form_inputs">CHAPTER 09. Controlled Form Inputs</h2>

<a href="https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=5">
    <img src="./images/thumbnail_09.controlled_form_inputs.jpg" width="240px">
</a>

[https://youtu.be/r5ombQn3fHY](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=5)

React Forms は、React の状態にリンクされた制御された入力を利用します。
これは、HTML や Javascript で学ぶのとは異なるアプローチです。
React に制御されたフォーム入力を React の状態にリンクさせることで、
制御されたコンポーネントの信頼できる単一の情報源が作成されます。

[[00:05](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=5)] セットアップとクリーンアップ  
[[03:06](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=186)] Form コンポーネントを作成する  
[[07:44](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=464)] フォームに CSS を追加する  
[[09:24](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=564)] Form コンポーネントへの props の受け渡し  
[[11:47](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=707)] 制御された Input コンポーネントを作成する  
[[13:58](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=838)] handleSubmit 関数  
[[17:52](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=1072)] addItem 関数  
[[21:04](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=1264)] setAndSaveItems 関数 - D.R.Y. (don't repeat yourself)  
[[22:15](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=1335)] 新しい項目を追加する  
[[23:17](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=1397)] localStorage から状態を読み込む  
[[24:58](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=1498)] 検索機能  
[[25:40](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=1540)] 検索入力コンポーネントの作成  
[[27:50](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=1670)] 検索入力コンポーネントの小道具  
[[29:03](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=1743)] 制御された検索入力コンポーネントを完成させる  
[[31:34](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=1894)] filter() による検索機能の追加  
[[33:58](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=2038)] FormInput コンポーネントの表示確認  
[[34:32](https://www.youtube.com/embed/r5ombQn3fHY?autoplay=1&start=2072)] useRef フック   

<h2 id="project_challenge">CHAPTER 10. Controlled Form Inputs</h2>

<a href="https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=5">
    <img src="./images/thumbnail_10.project_challenge.jpg" width="240px">
</a>

[https://youtu.be/oWIqiVAK1Wo](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=5)

この React コードチャレンジでは、この動画シリーズの前のレッスンで学んだことができるか腕試しをします。
課題は、React を使用してシンプルなカラーチェンジャーアプリを構築することです。

[[00:05](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=5)] コードチャレンジ：初めてのプロジェクト   
[[01:29](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=89)] 解答例の開始: create-react-app とセットアップ   
[[04:35](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=275)] アプリのコンポーネントの概要   
[[06:41](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=401)] 四角いコンポーネント   
[[09:02](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=542)] フォーム入力コンポーネント   
[[11:19](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=679)] useState フックと props の受け渡し   
[[12:56](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=776)] CSS スタイルの追加   
[[14:51](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=891)] チャレンジ完了 どうだった？  
[[15:28](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=928)] 追加機能: 色名から16進数値へ   
[[20:12](https://www.youtube.com/embed/oWIqiVAK1Wo?autoplay=1&start=1212)] 追加機能: 文字色の切り替え    

<h2 id="useeffect_hook">CHAPTER 11. useEffect Hook</h2>

<a href="https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=5">
    <img src="./images/thumbnail_11.useEffect_hook.jpg" width="240px">
</a>

[https://youtu.be/j3vk0FW71DM](https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=5)

この useEffect フックチュートリアルでは、React で useEffect フックが呼び出されて実行されるタイミングについて学習します。
また、useEffect フックを使用してデータをロードおよび保存する方法と、useEffect フックの最大の間違いを回避する方法についても学びます。

[[00:05](https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=5)] セットアップ   
[[00:53](https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=53)] 依存関係のない useEffect フック  
[[01:46](https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=106)] アプリのロード時に useEffect フックを使用する  
[[02:51](https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=171)] 依存関係が変更されたときだけ useEffect フックを使用する  
[[03:55](https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=235)] useEffect は同期型ではない  
[[05:32](https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=332)] useEffect でデータをロードする  
[[06:40](https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=400)] useEffect で大きな間違いをしないために  
[[07:10](https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=430)] useState を使った読み込みエラーの回避   
[[08:55](https://www.youtube.com/embed/j3vk0FW71DM?autoplay=1&start=535)] useEffect を使ったデータの保存    

<h2 id="json_server">CHAPTER 12. JSON Server</h2>

<a href="https://www.youtube.com/embed/_Fx6GDuIo1A?autoplay=1&start=5">
    <img src="./images/thumbnail_12.json_server.jpg" width="240px">
</a>

[https://youtu.be/_Fx6GDuIo1A](https://www.youtube.com/embed/_Fx6GDuIo1A?autoplay=1&start=5)

この動画では、React アプリのモック開発サーバとして機能する JSON Server Rest API をセットアップします。
この React アプリは、JSON サーバーにリクエストを送信して、JSON データを取得、投稿、更新、削除できるようになります。

[[00:05](https://www.youtube.com/embed/_Fx6GDuIo1A?autoplay=1&start=5)] JSON Server とは？  
[[00:32](https://www.youtube.com/embed/_Fx6GDuIo1A?autoplay=1&start=32)] NPM の代わりに NPX を使う  
[[00:54](https://www.youtube.com/embed/_Fx6GDuIo1A?autoplay=1&start=54)] JSON データの作成   
[[02:45](https://www.youtube.com/embed/_Fx6GDuIo1A?autoplay=1&start=165)] JSON Server の起動  
[[03:57](https://www.youtube.com/embed/_Fx6GDuIo1A?autoplay=1&start=237)] GET リクエストの送信   
[[05:10](https://www.youtube.com/embed/_Fx6GDuIo1A?autoplay=1&start=310)] JSON Server のエンドポイントとリクエストタイプ   

<h2 id="fetching_api_data">CHAPTER 13. Fetching API Data</h2>

<a href="https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=5">
    <img src="./images/thumbnail_13.fetching_api_data.jpg" width="240px">
</a>

[https://youtu.be/9vvtO0S1KlY](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=5)

この動画では、React で API からデータをフェッチする方法を学びます。
useEffect フック内で async と await を使用し、Rest API から取得したデータを画面上に表示する方法を学びます。

[[00:05](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=5)] セットアップ  
[[01:57](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=117)] localStorage から REST API への切り替え  
[[04:48](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=288)] useEffect フックで Async Await を利用する  
[[05:45](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=345)] fetch 関数の作成  
[[09:31](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=571)] すべての fetch エラーが catch ブロックに行くわけではない  
[[10:59](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=659)] fetch エラーのレスポンスをキャッチする  
[[14:10](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=850)] JSX でエラーを表示する  
[[18:47](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=1127)] REST API の遅いレスポンスをシミュレートする  
[[20:04](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=1204)] ロード状態を追跡する  
[[21:15](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=1275)] JSX での読み込みメッセージの表示  
[[22:52](https://www.youtube.com/embed/9vvtO0S1KlY?autoplay=1&start=1372)] useEffect 内の完全なフェッチ関数   

<h2 id="crud_operations">CHAPTER 14. CRUD Operations</h2>

<a href="https://www.youtube.com/embed/XYrNkTkx8Uc?autoplay=1&start=5">
    <img src="./images/thumbnail_14.CRUD_operations.jpg" width="240px">
</a>

[https://youtu.be/XYrNkTkx8Uc](https://www.youtube.com/embed/XYrNkTkx8Uc?autoplay=1&start=5)

この動画では、非同期フェッチ関数を抽象化し、options オブジェクトのパラメータ内で操作を定義することによって、
React で CRUD 操作を完了する方法を学びます。
CRUD 操作は、REST API サーバとやり取りして、データの作成、読み取り、更新、および削除を行います。

[[00:05](https://www.youtube.com/embed/XYrNkTkx8Uc?autoplay=1&start=5)] プロジェクトについて  
[[01:39](https://www.youtube.com/embed/XYrNkTkx8Uc?autoplay=1&start=99)] 非同期 API リクエスト関数を作成する   
[[06:48](https://www.youtube.com/embed/XYrNkTkx8Uc?autoplay=1&start=408)] POST API リクエストで新規レコードを作成する   
[[10:10](https://www.youtube.com/embed/XYrNkTkx8Uc?autoplay=1&start=610)] JSON サーバ API リクエストの受信を確認する   
[[11:48](https://www.youtube.com/embed/XYrNkTkx8Uc?autoplay=1&start=708)] PUT APIリクエストで既存のレコードを更新する   
[[17:08](https://www.youtube.com/embed/XYrNkTkx8Uc?autoplay=1&start=1028)] DELETE APIリクエストで既存のレコードを削除する   

<h2 id="fetch_data_challenge">CHAPTER 15. Fetch Data Challenge</h2>

<a href="https://www.youtube.com/embed/lf_uNOKVSnM?autoplay=1&start=5">
    <img src="./images/thumbnail_15.fetch_data_challenge.jpg" width="240px">
</a>

[https://youtu.be/lf_uNOKVSnM](https://www.youtube.com/embed/lf_uNOKVSnM?autoplay=1&start=5)

この2部構成の Reactビギナーズチャレンジでは、ダミーの REST API を使って、useEffect フックで API データを取得します。
しかし、ちょっと待ってください! React の状態を管理し、クリックイベントを適用し、機能的なコンポーネントを構築する必要があるのです。

[[00:05](https://www.youtube.com/embed/lf_uNOKVSnM?autoplay=1&start=5)] ようこそ   
[[00:14](https://www.youtube.com/embed/lf_uNOKVSnM?autoplay=1&start=14)] React ビギナーズチャレンジ - パート A  
[[02:27](https://www.youtube.com/embed/lf_uNOKVSnM?autoplay=1&start=147)] Part A のヒント  
[[03:42](https://www.youtube.com/embed/lf_uNOKVSnM?autoplay=1&start=222)] 解答のセットアップ  
[[05:58](https://www.youtube.com/embed/lf_uNOKVSnM?autoplay=1&start=358)] パートAの解答例  
[[25:53](https://www.youtube.com/embed/lf_uNOKVSnM?autoplay=1&start=1553)] Reactビギナーズチャレンジ パートB  
[[27:07](https://www.youtube.com/embed/lf_uNOKVSnM?autoplay=1&start=1627)] パートBのヒント  
[[28:51](https://www.youtube.com/embed/lf_uNOKVSnM?autoplay=1&start=1731)] パートBの解答例  

<h2 id="router">CHAPTER 16. React Router</h2>

<a href="https://www.youtube.com/embed/Cv_JhlKUpto?autoplay=1&start=5">
    <img src="./images/thumbnail_16.router.jpg" width="240px">
</a>

[https://youtu.be/Cv_JhlKUpto](https://www.youtube.com/embed/Cv_JhlKUpto?autoplay=1&start=5)

この動画では、初心者向けのプロジェクトで React Router を学びます。
React を使えばシングルページアプリケーション（SPA）を作ることができますが、
React Router を使えば、React は完全なウェブサイトを構築することができます！
React Router の使用方法について説明します。

[[00:05](https://www.youtube.com/embed/Cv_JhlKUpto?autoplay=1&start=5)] ようこそ   
[[00:14](https://www.youtube.com/embed/Cv_JhlKUpto?autoplay=1&start=14)] プロジェクトの概略  
[[01:18](https://www.youtube.com/embed/Cv_JhlKUpto?autoplay=1&start=78)] クイックセットアップガイド   
[[03:13](https://www.youtube.com/embed/Cv_JhlKUpto?autoplay=1&start=193)] React Router で App コンポーネントをラッピングする   
[[04:42](https://www.youtube.com/embed/Cv_JhlKUpto?autoplay=1&start=282)] すべてのコンポーネントを識別する   
[[08:04](https://www.youtube.com/embed/Cv_JhlKUpto?autoplay=1&start=484)] 関数コンポーネントを作成する   
[[12:36](https://www.youtube.com/embed/Cv_JhlKUpto?autoplay=1&start=756)] コンポーネントを JSX に配置する   
[[13:49](https://www.youtube.com/embed/Cv_JhlKUpto?autoplay=1&start=829)] コンポーネントのルートを追加する   

<h2 id="router_hooks_and_links">CHAPTER 17. Router Hooks & Links</h2>

<a href="https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=5">
    <img src="./images/thumbnail_17.router_hooks_and_links.jpg" width="240px">
</a>

[https://youtu.be/eHnqS9kMH-s](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=5)

この動画では、1つ前の動画の React Router チュートリアルで作った React プロジェクトを完成させながら、
React Router のフックとリンクを追加していきます。

[[00:05](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=5)] ようこそ   
[[00:15](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=15)] このチャプターの目標  
[[00:58](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=58)] CSSをプロジェクトに適用する  
[[01:58](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=118)] ヘッダーコンポーネント   
[[02:46](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=166)] Nav コンポーネントと React Router リンク  
[[07:13](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=433)] 検索状態の追加  
[[07:54](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=474)] 投稿ステートと初期投稿データの追加   
[[08:48](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=528)] 検索結果ステートの追加   
[[09:13](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=553)] Nav コンポーネントへの props の受け渡し   
[[09:36](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=576)] Home コンポーネント   
[[12:41](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=761)] Feed コンポーネント   
[[13:50](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=830)] Post コンポーネント   
[[17:54](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=1074)] PostPage コンポーネントと useParams フック   
[[25:00](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=1500)] handleDelete 関数と useHistory フック   
[[27:10](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=1630)] NewPost コンポーネント   
[[33:50](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=2030)] handleSubmit 関数と date-fns パッケージ  
[[39:16](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=2356)] useEffect と filter による検索機能の追加  
[[43:52](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=2632)] handleSubmit 関数のエラー修正   
[[44:56](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=2696)] 404 Not Found 用ページのコンポーネント  
[[46:42](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=2802)] Footer コンポーネント   
[[47:46](https://www.youtube.com/embed/eHnqS9kMH-s?autoplay=1&start=2866)] コンポーネントについて  

<h2 id="flexbox_components">CHAPTER 18. Flexbox Components</h2>

<a href="https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=5">
    <img src="./images/thumbnail_18.flexbox_components.jpg" width="240px">
</a>

[https://youtu.be/oHUNLuEtqQ0](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=5)

React アプリをフルスクリーンサイズに設定する方法を紹介します。
この動画では、React アプリの CSS の幅と高さの設定について確認します。
Flexbox を活用し、React アプリの画面サイズを設定する方法を学びます。

[[00:05](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=5)] ようこそ   
[[00:33](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=33)] アプリの幅の問題   
[[01:12](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=72)] なぜ幅が変わるのか？  
[[01:56](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=116)] 問題の特定   
[[02:46](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=166)] アプリの幅を一定にする   
[[05:13](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=313)] 余白と全ページ幅のどちらを取るか   
[[05:53](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=353)] flex-grow 設定の重要性   
[[06:28](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=388)] アプリの高さについて   
[[07:15](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=435)] App コンポーネントの flexbox 設定   
[[07:40](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=460)] body 要素の min-height 設定   
[[08:22](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=502)] App コンポーネントの高さ設定   
[[09:06](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=546)] メインコンテンツコンポーネントの flex-grow  
[[09:57](https://www.youtube.com/embed/oHUNLuEtqQ0?autoplay=1&start=597)] 要素を中央に配置する別の方法  

<h2 id="axios_api_requests">CHAPTER 19. Axios API Requests</h2>

<a href="https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=5">
    <img src="./images/thumbnail_19.axios_api_requests.jpg" width="240px">
</a>

[https://youtu.be/ZEKBDXGnD4s](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=5)

この動画では、React Axios API Requests を学びます。
ここまで進めてきた React ブログプロジェクトの作成をさらに進め、Axios を実装していきます。
Axiosは、Javascript で Fetch API を使用するよりも簡単に API リクエストを行うことができます。

[[00:05](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=5)] チュートリアルの概要   
[[00:26](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=26)] JSON サーバのセットアップ  
[[02:06](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=126)] Axios のインストール  
[[03:29](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=209)] Axios の baseURL を設定する  
[[04:44](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=284)] JSON サーバの起動  
[[05:21](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=321)] React アプリの起動  
[[06:27](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=387)] Axios の API をインポートする  
[[07:08](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=428)] Axios でデータを取得する   
[[13:35](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=815)] Axios でデータを投稿する  
[[17:05](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=1025)] Axios でデータを削除する   
[[18:23](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=1103)] handleEdit 更新関数の構築  
[[23:08](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=1388)] EditPost コンポーネントを作成する  
[[30:24](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=1824)] EditPost コンポーネントの Route を追加する  
[[31:52](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=1912)] EditPost コンポーネントをもう1つ追加する  
[[32:56](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=1976)] PostPage コンポーネントに EditPost ボタンを追加する  
[[33:59](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=2039)] EditPost のインポートと機能テスト   
[[35:54](https://www.youtube.com/embed/ZEKBDXGnD4s?autoplay=1&start=2154)] 小さな CSS の変更  

<h2 id="custom_hooks">CHAPTER 20. Custom Hooks</h2>

<a href="https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=5">
    <img src="./images/thumbnail_20.custom_hooks.jpg" width="240px">
</a>

[https://youtu.be/tBuceoEGFhI](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=5)

この動画では、Axios を使用して React のカスタムフックを構築します。
Fetch API の代わりに Axios を適用する独自の useFetch フックを作成します。
また、useWindowSize というシンプルなカスタムフックも作ってみます。

[[00:05](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=5)] ようこそ   
[[00:19](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=19)] クイックセットアップ  
[[00:43](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=43)] フックのルール  
[[01:45](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=105)] React のカスタムフックはレシピのようなもの  
[[02:41](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=161)] カスタムフック useWindowSize を作成する  
[[08:46](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=526)] カスタムフック useWindowSize を動作確認する  
[[09:25](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=565)] React アプリに useWindowSize を適用する  
[[15:01](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=901)] useEffect のクリーンアップ関数を覚えておく  
[[17:20](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=1040)] useAxiosFetch カスタムフックを作成する  
[[25:34](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=1534)] カスタムフック useAxiosFetch のおさらい  
[[27:16](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=1636)] useAxiosFetch を適用する  
[[35:19](https://www.youtube.com/embed/tBuceoEGFhI?autoplay=1&start=2119)] 最終的なクリーンアップ  

<h2 id="context_api">CHAPTER 21. Context API useContext</h2>

<a href="https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=5">
    <img src="./images/thumbnail_21.context_api_useContext.jpg" width="240px">
</a>

[https://youtu.be/ngVvDegsAW8](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=5)

この動画では Context API の useContext フックを使って、React の状態管理を学びます。
React では、コンポーネントを通じて prop を渡すことができますが、
Context API と useContext フックを使用すると、prop のバケツリレー（Prop Drilling）を回避することができます。

[[00:05](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=5)] ようこそ   
[[00:13](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=13)] 概要  
[[01:05](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=65)] コンテキストの作成  
[[03:54](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=234)] DataProvider の追加  
[[05:03](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=303)] コンテキストへのステートとロジックの移動  
[[07:21](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=441)] useContext を使った Header のリファクタリング  
[[10:21](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=621)] useContext を用いた Nav のリファクタリング  
[[11:53](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=713)] useContext を用いた Home のリファクタリング  
[[14:42](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=882)] useContext を用いた NewPost のリファクタリング  
[[17:21](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=1041)] useContext を使った EditPost のリファクタリング  
[[19:30](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=1170)] useContext を用いた PostPage のリファクタリング  
[[22:00](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=1320)] アプリコンポーネントのクリーンアップ  
[[23:04](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=1384)] すべてコンテキストにする必要があるのか？  
[[24:37](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=1477)] コンポーネントの状態 vs コンテキストによる共有の状態  
[[26:17](https://www.youtube.com/embed/ngVvDegsAW8?autoplay=1&start=1577)] 共有状態をコンテキストで維持したままコンポーネントの状態をリファクタリング  

<h2 id="deploy_to_github_pages_and_netlify">CHAPTER 22. Deploy a React App to GitHub Pages and Netlify</h2>

<a href="https://www.youtube.com/embed/AOqY6disSVI?autoplay=1&start=5">
    <img src="./images/thumbnail_22.deploy_to_github_pages_and_netlify.jpg" width="240px">
</a>

[https://youtu.be/AOqY6disSVI](https://www.youtube.com/embed/AOqY6disSVI?autoplay=1&start=5)

React アプリを Github Pages と Netlify にデプロイする方法を学びます。
この動画では、Github リポジトリから React アプリをビルドして Github Pages か Netlify のどちらか、
または両方にデプロイする方法を学びます。

[[00:05](https://www.youtube.com/embed/AOqY6disSVI?autoplay=1&start=5)] ようこそ  
[[00:20](https://www.youtube.com/embed/AOqY6disSVI?autoplay=1&start=20)] 概要  
[[00:31](https://www.youtube.com/embed/AOqY6disSVI?autoplay=1&start=31)] Netlify に React アプリをデプロイする方法  
[[07:35](https://www.youtube.com/embed/AOqY6disSVI?autoplay=1&start=455)] GitHub Pages にReactアプリをデプロイする方法  
[[14:13](https://www.youtube.com/embed/AOqY6disSVI?autoplay=1&start=853)] Netlify と GitHub Pages のどちらがいいの？  
