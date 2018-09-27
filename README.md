# CSX0013 數位應用程式設計

網址： https://michael0703.github.io/django2018class/

## 課程協助者

Pecu Tsai
* 課程教授

廖威仲 (Michael Liao)
* 今年大三資工系的學生。

薛德明 (Domi)
* 資工博六（休學狀態）

---

## Week3


#### In Class
1. 投影片: [https://goo.gl/AmctUS](https://goo.gl/AmctUS)
1. 分區：按找你目前的狀態，請坐在最適合你自己的學習區域
1. Django的template和views的互動過程
1. 分享時間(上週的重點問題、成果分享)


#### Mission
1. 學會 Python 基礎
1. 學會 Django Template Language 基礎
1. 了解 views 如何和 template 進行互相控制，並且修改自己的網頁(具體目標待確認)
1. 確認：你可以用 `for` loop 來顯示一個圖片的清單 (修改 template 的 html，加入模板語言)
    * 例如 (圖片可以點放大)： (<img src="https://i.imgur.com/rzgNAlG.jpg"  width="400">)[https://i.imgur.com/rzgNAlG.jpg]
    * 強者，很鼓勵顯示一些更有創意的怪東西～ (例如： 可以參考 http://random.cat/ )
1. 把新的結果 push 到上週新開的 Github Repo + 把結果上傳至 Heroku，且確認 Heroku 上面的版本跟本機端的是一樣的
1. 共學的時候，跟更多同學互動，開始認識大家的名字
1. 花 10 分鐘反思你的學習過程，並且在 `README.md` 裡面做基本的學習紀錄一下
    * [其他課程同學 README 範例 #1](https://github.com/HowardChao/CSX_RProject_Spring_2018)
    * [其他課程同學 README 範例 #2](https://github.com/Dennishi0925/CSX_RProject_Spring_2018)
1. 了解本週的重點問題
   * 模板語言 
         * html中要怎麼使用一個變數？
         * 如果要在html中使用for、if 需要加上什麼符號？
         * 你還用到了什麼其他的模板語言(for、if之外的)
   * views和template的互動
         * template是如何知道模板中變數((ex: {{message}}))的值是多少?
         * render的第三個參數必須要是什麼樣的資料結構？
   * python基礎
         * python需不需要縮排？句尾要加分號嗎？
         * python字典(dictionary)要怎麼宣告？列表(list)要怎麼宣告？

#### 參考資料

1. 『全段著手開發的流程』教學影片 [https://goo.gl/fJNuYw](https://goo.gl/fJNuYw)
1. Week3 範例介紹:
   * [點這裡看線上結果](https://helloworldwei.herokuapp.com)
   * 提示: https://goo.gl/y4aMG3
1. [Datacamp: Python 基礎教學](https://campus.datacamp.com/courses/intro-to-python-for-data-science)
1. [Codecademy: Python 基礎教學](https://www.google.com.tw/search?q=codecademy+python)
1. Django模板教學
    * TODO
    * [Django 官方說明書：Django Template Language](https://docs.djangoproject.com/en/2.1/ref/templates/language/)






--- 

## Week2

#### In Class
1. 投影片: https://ppt.cc/fODSux
1. live demo last week's example
1. basic HTML/CSS

#### Mission

1. 確認你熟悉『全段著手開發的流程』（教學影片： https://goo.gl/fJNuYw )
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
