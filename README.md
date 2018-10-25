# CSX0013 數位應用程式設計

### [網站如果顯示有問題，請點我看 Github 中的版本](https://github.com/michael0703/django2018class)

## 課程協助者

Pecu Tsai
* 課程教授

廖威仲 (Michael Liao)
* 今年大三資工系的學生。

薛德明 (Domi)
* 資工博六（休學狀態）

---

## Week7 

#### In Class

[投影片](todo)

#### Mission

1. 這次要學習的概念：ORM資料庫如何使用CRUD,ER-model(規劃資料庫)
1. 新增資料庫的CRUD功能
   *  可以新增資料(應該是前幾週功能)
   *  可以刪除資料
   *  可以查詢資料
   *  可以修改資料(並非新增一筆、刪除舊的)
   *  以上功能加入網頁中(可以讓使用者自己操作、注意權限問題)
1. 實作資料庫的join
   *  了解什麼是table join、foreign key
   *  建立兩個或以上的表、建立彼此之間的FK
1. 了解本週重點問題
   *  
   *  


#### 參考資料
1. 助教範例
   - [網站](https://weidbtest.herokuapp.com/)
1. [Django資料庫操作](https://code.ziqiangxuetang.com/django/django-queryset-api.html)
1. [ER圖介紹](http://cc.cust.edu.tw/~ccchen/doc/db_03.pdf)
1. [資料庫資料太多、不想全部顯示在同一頁？可以使用Django的分頁套件](https://mozillazg.com/2013/01/django-pagination-by-use-paginator.html)

---

## Week6 

#### In Class

[投影片](https://docs.google.com/presentation/d/1PpyPXNEAqfNk-_Xq7w7QpWu7MT1_cuUXQHJc46pkyuI/edit?usp=sharing)

#### Mission

1. 這次要學習的概念：網頁的cookie、seesion是什麼？
1. 瞭解說登入系統的基本概念？
1. 實作一個登入系統
   *  有基本的登入、註冊、登出頁面
   *  讓使用者可以清楚地知道自己是否登入、註冊成功(or失敗)
   *  各個頁面是否可以正確跳轉？
   *  Bonus:你是否可以驗證使用者是否輸入合法資料註冊？如果有兩個人輸入同樣的帳號註冊你能處理嗎？
1. 了解本週重點問題
   *  使用者資料(名稱帳號密碼..)是如何儲存？是存在資料庫或是哪裡？
   *  Django的預設使用者欄位有哪些？(除了基本的使用者帳號、密碼)
   *  為什麼切換到網站的不同頁面伺服器還是可以知道是哪個使用者登入？
   * Heroku
     - 在本機端註冊一個使用者，可以在heroku端的網頁登入嗎？
     - 承上題，為什麼？


#### 參考資料
1. 助教範例
   - [網站](https://weidbtest.herokuapp.com/)
   - [投影片](https://docs.google.com/presentation/d/1UQlAwJVzFDsj4MykWKyblr72n4k7VcUDHZJDZ7ttz3s/edit#slide=id.g4479fdd358_0_268)
   - [repo](https://github.com/michael0703/DjangoWeek6LoginSystem)
1. [簡易教學](http://pythoncat.blogspot.com/2014/11/django11.html)
1. [redirect函式使用](https://www.jianshu.com/p/921f4cfc798a)
1. [django預設後台管理](https://developer.mozilla.org/zh-TW/docs/Learn/Server-side/Django/Admin_site)


---

## Week5

#### In Class

[投影片](https://docs.google.com/presentation/d/e/2PACX-1vSaq8sqFrbTRuhqdvg9FBbb_k9mgtdjtY_6LH7XrXDy42-LBmcVQ9YAnFbegiX8ZpvVWJzYovQvd07s/pub?start=false&loop=false&delayms=3000&slide=id.p)

#### Mission

1. 這次要新學習的概念： Django 裡面的 Form, Request, URL, GET + POST
1. 瞭解：如何從 view 裡面呼叫 Model 來更改資料庫裡面的資料？
1. 在網站中增加 Form 來得到使用者的輸入
1. Form 裡面的資料送出去後可以存到資料庫
1. 資料庫內容更改後，網頁上面可以看到新的資料
1. 確保利用 Postgre 的網站在本機端 還有 Heroku 上面都跑得動
1. 了解本週重點問題：
   * 表單 (Form)
      - 如何創建表單？
      - 如何在後端處理表單？
      - 你是使用POST還是GET處理表單？
   * 資料庫
      - 你是怎麼把本地端資料庫和heroku上面的同步？（方法不只一種）


#### 參考資料

* [NetNinja: Django的教學影片](https://www.youtube.com/watch?v=n-FTlQ7Djqc&list=PL4cUxeGkcC9ib4HsrXEYpQnTOTZE1x0uc)
* [如何增加不一樣的 URL + 頁面？](http://dokelung-blog.logdown.com/posts/220283-django-note-2-views-and-urls)
* [MDN: Django Forms](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms)
* [使用者互動與表單 (Forms)](http://dokelung-blog.logdown.com/posts/220833-django-notes-7-forms)
* 助教提供：
   * [範例網址](https://weidbtest.herokuapp.com/)
   * [設定psql、推上heroku教學(適用mac、linux)]（https://docs.google.com/presentation/d/1na4G7xXNmReeTuwU35q-jt4LeOwF_jfP7KaN-hsIVHY/edit)

---

## Week4

#### In Class

[投影片](https://docs.google.com/presentation/d/1cMKatsT5Cp580ghxtYdTWKE03nbcHdVwKVk3Miyl2YI/edit?usp=sharing)

#### Mission
1. 共學的時候，儘量認識三個陌生同學，問他們一兩個問題，看看能不能聊得來（也不一定需要聊得來啦～）
1. 確認你會打開本機端的伺服器且在本機端開發： `python manage.py runserver`
1. 設定資料庫（我們推薦： PostgreSQL）
1. 設定你第一個 `model`
1. 用 `django migrate` 的指令來建立資料庫中新的 `Schema`
    * （`Schema` 是指：一堆資料表的架構，也就是你的 app 在資料庫中存起來資料的『資料架構』）
1. 學會如何用 `django` 的指令來控制資料庫的內容（尤其是：確認說你會加資料進去）
1. 複習 Python 基礎：搞定 `list`, `dictionary` and `class` 三個概念，因為。。。
    * 資料庫最喜歡吐出來的資料主要是 `list` + `dictionary`
    * 那些 `list` + `dictionary` 裡面的東西就是 model `class` 所定義的物件
1. 確保說：在頁面上可以看到資料庫中的資料
1. 稍微視覺化資料；不只要單純看到一些數字文字，反而要顯示一個簡單的應用（例如： guest book, 『我瘋狂的興趣』的網站, 我奇怪的 TODO list 等等～）
1. [多餘給強者的部分] 自學會 `Week5` 的內容重點：透過 `form`, `url`, `request handler` + `router` 讓使用者輸入新的資料或更改已有的資料
1. [推薦] 花 1-60 分鐘（自己決定啦～）面對本週重點問題：
    * 你今天認識了幾個新的同學？
    * 資料庫 (Database)
        - 資料庫和資料表的差別？
        - row + column 之間的差別是什麼？Row 是什麼？ Column 是什麼？
        - PostgreSQL 跟 SQL 之間的差別是什麼？兩個概念之中，哪一個比較大比較抽象？
        - PostgreSQL 裡面怎麼加資料表 (Table)？
        - [多餘給強者的問題] PostgreSQL 裡面怎麼進行 Insert, Delete, Update, Select 個別四種 operation？每個 operation 的 SQL 語法是什麼？
    * Django Model
        - 如何在 Django 裡面初始化資料庫？（提示： `migrate` ）
        - 如何加新的資料 (row) 到資料表 (Table) 裡面了？
        - 如何從資料庫中取得現有資料？
        - 如何修改資料庫中已經存起來的資料(請試著google看看)？
        - 改資料庫之中的資料表 (Table) 之後還要改什麼才能讓使用者看到新的資料？怎麼改？
1. 花 10 分鐘反思你的學習過程，並且在 `README.md` 裡面做基本的學習紀錄一下
    * [其他課程同學 README 範例 #1](https://github.com/HowardChao/CSX_RProject_Spring_2018)
    * [其他課程同學 README 範例 #2](https://github.com/Dennishi0925/CSX_RProject_Spring_2018)

#### 參考資料

1. 確認[『全段著手開發的流程』10個步驟](https://docs.google.com/presentation/d/1-iTMn9BbuanJqMERGoObx1JYhKFTNINt5_ifrDXURao/edit#slide=id.g42c94c5ac4_0_8) 是完全 ok 的，有記住的了啦～
1. 助教幫忙準備
   1. [本週任務提示](https://goo.gl/c5v9cG)
   1. [範例網址](https://weidbtest.herokuapp.com/)
   1. [Django Models介紹](https://goo.gl/aSJoKd)
   1. [Django 操作資料庫教學](https://djangogirlstaipei.gitbooks.io/django-girls-taipei-tutorial/django/orm.html)
1. [Django 教材： 資料模型與資料庫](http://yltang.net/tutorial/django/7/) [全中文！！！]
1. [Net Ninja - Django models](https://www.youtube.com/watch?v=5zNR3E6WRLE)
1. [Django Migration到底在做什麼？](https://realpython.com/django-migrations-a-primer/)
1. 更多 Python 基礎
   * [Codecademy: Python - Lists and Dictionaries](https://www.codecademy.com/courses/learn-python/lessons/python-lists-and-dictionaries/exercises/introduction-to-lists?action=resume_content_item)
   * [Udacity: Python - Writing your own Classes](https://classroom.udacity.com/courses/ud036/lessons/997889780/concepts/10136290570923) 如何用 Python 來定義 `class`？ [有中文字幕！！！]

---

## Week3


#### In Class
1. 投影片: [https://goo.gl/AmctUS](https://goo.gl/AmctUS)


#### Mission
1. 共學的時候，跟更多同學互動，開始認識大家，記住一些人的名字
1. 學會 Python 基礎
1. 學會 Django Template Language 基礎
1. 了解 views 如何和 template 進行互相控制，並且修改自己的網頁(具體目標待確認)
1. 確認：你可以用 Python 的 `for` loop 來顯示東西 (修改 template 的 html，加入模板語言)
    - 例如顯示出一堆隨機抓過來的圖 (圖片可以點放大)： <a href="https://i.imgur.com/rzgNAlG.jpg"><img src="https://i.imgur.com/rzgNAlG.jpg"  width="400"></a>
    - 強者，很鼓勵顯示一些更有創意的怪東西～ (例如：透過 [`request`](https://stackoverflow.com/questions/42737733/send-http-request-using-django-and-get-results) 下載線上的東西，然後用 Django Template Language 重新整理顯示出來)
1. 把新的結果 push 到上週新開的 Github Repo + 把結果上傳至 Heroku，且確認 Heroku 上面的版本跟本機端的是一樣的
1. 反省一下 － 你到底有沒有學習的成就感？（提出幾個重點問題給你參考）
   - 模板語言 
     - html中要怎麼使用一個變數？
     - 如果要在html中使用for、if 需要加上什麼符號？
     - 你還用到了什麼其他的模板語言(for、if之外的)
   - views和template的互動
     - template是如何知道模板中變數((ex: {{message}}))的值是多少?
     - render的第三個參數必須要是什麼樣的資料結構？
   - python基礎
     - python需不需要縮排？句尾要加分號嗎？
     - python字典(dictionary)要怎麼宣告？列表(list)要怎麼宣告？
1. 花 10 分鐘反思你的學習過程，並且在 `README.md` 裡面做基本的學習紀錄一下
    - [其他課程同學 README 範例 #1](https://github.com/HowardChao/CSX_RProject_Spring_2018)
    - [其他課程同學 README 範例 #2](https://github.com/Dennishi0925/CSX_RProject_Spring_2018)

#### 參考資料

1. 搞定[『全段著手開發的流程』10個步驟](https://docs.google.com/presentation/d/1-iTMn9BbuanJqMERGoObx1JYhKFTNINt5_ifrDXURao/edit#slide=id.g42c94c5ac4_0_8)
1. Week3 範例介紹:
    - [點這裡看線上結果](https://helloworldwei.herokuapp.com)
    - 提示: [https://goo.gl/y4aMG3](https://goo.gl/y4aMG3)
1. Python 基礎教學
   - [Udacity: Introduction to Python Programming](https://www.udacity.com/course/introduction-to-python--ud1110) (有中文字幕)
   - [Datacamp: Python 基礎教學](https://campus.datacamp.com/courses/intro-to-python-for-data-science)
   - [Codecademy: Python 基礎教學](https://www.google.com.tw/search?q=codecademy+python)
1. Django Template 教學
    - [Django 的 Template 怎麼開始下手？](https://www.youtube.com/watch?v=Iy4niMCsbEE&feature=youtu.be)
    - [影片：Django 中的 for loop](https://www.youtube.com/watch?v=uB5cL0Hghgw) （英文）
    - [基礎模板教學](http://tw-hkt.blogspot.com/2017/02/django_42.html)
    - [Django 官方說明書：Django Template Language](https://docs.djangoproject.com/en/2.1/ref/templates/language/)
1. 前端排版搞定 (How to do proper layouting in HTML?)
    - 答案 #1： Flexbox!!!
    - [中文的影片: CSS3 Flexbox 完整教學](https://www.youtube.com/watch?v=e6rZDyURgTY)
    - [Flexbox Cheatsheet](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) <img src="https://i.imgur.com/nPMnnYt.png" height="100px">
    - [中文版 Flexbox Cheatsheet](https://www.oxxostudio.tw/articles/201501/css-flexbox.html)






--- 

## Week2

#### In Class
1. 投影片: https://ppt.cc/fODSux
1. live demo last week's example
1. basic HTML/CSS

#### Mission
1. 搞定[『全段著手開發的流程』10個步驟](https://docs.google.com/presentation/d/1-iTMn9BbuanJqMERGoObx1JYhKFTNINt5_ifrDXURao/edit#slide=id.g42c94c5ac4_0_8)
    * 教學影片： https://goo.gl/fJNuYw
1. 學會 HTML + CSS 基礎
1. 在本機端開發，將 view.py 修改後透過 Django 產生靜態頁面，且自己打開 localhost (本機端) 的網址做確認內容是正確的
1. 把新的結果 push 到上週新開的 Github Repo
1. 把結果上傳至 Heroku，且確認 Heroku 上面的版本跟本機端的是一樣的
1. 花 10 分鐘反思你的學習過程，並且在 `README.md` 裡面做基本的學習紀錄一下
    * [其他課程同學 README 範例 #1](https://github.com/HowardChao/CSX_RProject_Spring_2018)
    * [其他課程同學 README 範例 #2](https://github.com/Dennishi0925/CSX_RProject_Spring_2018)
1. 了解本週的重點問題

* 著手開發的步驟是？
* 怎麼用 HTML + CSS 來拼出一個簡單的網頁？ 例如。。。。
    * 怎麼在html插入圖片？
    * 怎麼在html插入影片？
    * 怎麼在html加入unordered list?
    * &lt;ol> 和 &lt;ul>的差別是？
    * 如何用 CSS 改 某幾個字的顏色、大小、字體。。。？
    * 請你（儘量）思考更多 HTML 需要幫你做的事情（就算你不知道怎麼做，範例：『怎麼（大概）模仿 YouTube 的 HTML 架構？』）
* 怎麼控制一個最簡單的 Django 網站？例如。。。
    * 如何建立一個新的html檔案(需要什麼打什麼在檔案的ㄧ開頭)
    * 如何讓Django顯示你寫好的html檔案(也就是我的投影片寫的內容)
    * 如何讓Django裡面的 HTML 檔案引用到另一個css檔案？
* 怎麼保證『遠端』跟『本機端』是一樣的？


#### 參考資料

* 注意： 我們推薦用 [Codecademy](https://www.codecademy.com/) 等等網站來訓練程式基礎～

1. 『全段著手開發的流程』教學影片 https://goo.gl/fJNuYw
1. HTML basics
    * HTML 基礎訓練： https://www.codecademy.com/courses/learn-html/lessons/intro-to-html/exercises/intro
    * HTML 的檔案架構與連結訓練： https://www.codecademy.com/courses/learn-html/lessons/common-html-elements/exercises/prepare-html
    * https://www.codecademy.com/catalog/language/html-css
    * 註： 至少看完以下的一些基本課程：
1. CSS basics
    * CSS 基礎訓練： https://www.codecademy.com/catalog/language/html-css
    * CSS 中文簡介網站： https://www.1keydata.com/css-tutorial/tw/syntax.php
1. Week2 Django 範例介紹： https://goo.gl/ePSmdr
    * [點這裡看線上結果](https://helloworldwei.herokuapp.com)
    * Week2 example repository: https://github.com/michael0703/DjangoWeek2HTMLCSS
1. 有些同學可能會不知道怎麼把第一週clone下來的我的repo成功的丟上自己的github.或是怎麼樣把github上面的檔案同步下來本機端
    * 如何push上github https://goo.gl/BGAa5m
    * 如何從github上pull下來本地端 https://goo.gl/PjDkhu

--- 
    
## Week1


#### In class
1. 投影片: https://ppt.cc/fPu5Qx
1. register Heroku, Github 
1. install Django
1. learn heroku and git



#### Mission

1. 學會 Command-line 操作基礎
1. 裝好 Heroku + 跑讓本幾段跑出來
1. 把結果 push 到 Github
1. finish the class assignment


#### 參考資料

* Install Heroku CLI: https://devcenter.heroku.com/articles/getting-started-with-python#set-up
    * MAC: use [Homebrew](https://brew.sh/index_zh-tw) to install
    * Windows: use [Chocolatey](https://chocolatey.org/) to install
* Follow the instruction video: https://goo.gl/eirmji
* Week1 example repository https://github.com/michael0703/DjangoWeek1HelloWorld
    * [點這裡看線上結果](https://helloworldwei.herokuapp.com)
* Git 的教學
    * https://git-scm.com/book/zh-tw/v2/開始-Git-安裝教學
    * https://blog.gogojimmy.net/2012/01/17/how-to-use-git-1-git-basic/
