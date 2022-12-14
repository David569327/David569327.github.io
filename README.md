# 前端網頁設計 - 作品展 
## GitHub 專案儲存 David569327.github.io
### 連接主畫面的網址
https://david569327.github.io/index

<br> = = = = = = = = = = = = = = = = = = = = = = = = 
<br>    1. 重新練習 Visual Studio Code 系統與插件的安裝
<br>    2. 重新練習 Git and GitHub 安裝與設定
<br>    3. 重新練習 撰寫好的作葉上傳GitHub展示
<br>    4. 新增 Exercises 屬於自主練習的作品展示
<br> = = = = = = = = = = = = = = = = = = = = = = = = 

### 原 Build School 的作業依舊保留在 
https://github.com/DavidPeng1/FrontEnd/tree/main/HomeWork


## README.md 的編寫練習
==================================================
規範的README檔案開頭都寫上一個標題，這被稱為大標題。
在文字下面加上 等於號 = ，那麼上方的文字就變成了大標題。等於號的個數無限制，但一定要大於0個哦。。
比大標題低一級的是中標題，也就是顯示出來比大標題小點。


### README.md 的編寫方式說明
--------------------------------------------------
在文字下面加上 下劃線 - ，那麼上方的文字就變成了中標題，同樣的 下劃線個數無限制。

# h1 標題文字
## h2 標題文字
### h3 標題文字
#### h4 標題文字
##### h5 標題文字
###### h6 標題文字

關於標題還有等級表示法，分為六個等級，顯示的文字大小依次減小。不同等級之間是以井號  #  的個數來標識的。一級標題有一個 #，二級標題有兩個# ，以此類推。

如果有特殊符號, 使用Tab鍵上方的`符號可以標示

### 文字超連結
-----------------------------------------
在`[]`內寫入超連結要顯示的文字,超連結部分在`()`內寫入連結的地址
<br>
範例 : `[我在 GitHub 上的清單](https://DavidPeng1.github.io)`
<br>
顯示結果如下
<br>
[我在 GitHub 上的清單](https://DavidPeng1.github.io)
<br>
還可以在滑鼠停在超連結文字時, 出現提示文字, 例如要顯示作業的結果。
<br>
範例 : `[我在 GitHub 上的清單](https://DavidPeng1.github.io "Bulid School 作業清單")`
<br>
[我在 GitHub 上的清單](https://DavidPeng1.github.io "Bulid School 作業清單")


### 插入圖片
---------------------------------------------
驚嘆號! + 方括號[ ] + 括號(url) 
<br>
範例 : `![](https://www.google.com.tw/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)`
<br>
![](https://www.google.com.tw/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)
<br>
GitHub倉庫裡的圖片, 與上面的格式基本一致的，所不同的就是括號裡的URL該怎麼寫。
還可以在滑鼠停在超連結圖片時, 出現提示文字, 例如要顯示Bulid School Logo。
驚嘆號! + 方括號[ ] + 括號(url+提示文字 ) 
<br>
範例 : `https://raw.githubusercontent.com/DavidPeng1/DavidPeng1.github.io/main/Build%20School%20Logo.webp`
<br>
![](https://raw.githubusercontent.com/DavidPeng1/DavidPeng1.github.io/main/Build%20School%20Logo.webp "Bulid School Logo")
<br>

### 插入程式碼的方法
---------------------------------------------
在開頭處加入 3個 ` 符號後面加上語言別
    語言別如 html= 
        程式碼 ......................
    結尾處也需要加入 3個 ` 的符號

```html=
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- CSS Reset -->
    <link rel="stylesheet" href="./CSSreset.css">   
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" 
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <!-- Add Kit's Code to a Project -->
    <script src="https://kit.fontawesome.com/c8cecb51ea.js" crossorigin="anonymous"></script>
    <title>Hello, world!</title>
```


