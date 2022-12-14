# 網頁設計 - 自我學習的練習作品展 
## GitHub 專案儲存 https://david569327.github.io/Exercises

<br> = = = = = = = = = = = = = = = = = = = = = = = =  
#### CoreSolution 目錄簡易說明-使用指令創建方案與專案
<br> = = = = = = = = = = = = = = = = = = = = = = = = 
<br> 透過 CLI 指令 [ 建立方案 ]
<br>    1. md CoreSolution
<br>       執行後會建立CoreSolution目錄夾
<br>    2. cd CoreSolution
<br>       執行後會切換到CoreSolution目錄夾
<br>    3. dotnet new sln
<br>       執行後會建立方案, type CoreSolution.sln , 會顯示方案的內容
<br> 透過 CLI 指令 [ 建立 MVC 專案 ]
<br>    1. dotnet new mvc -o MvcTest
<br>       執行後會建立MvcTest目錄夾
<br>    2. dotnet sln add MvcTest
<br>       執行後會將MvcTest專案加入CoreSolution解決方案的資料夾中, type CoreSolution.sln , 會顯示方案的內容
<br> 透過 CLI 指令 [ 建立 Web API 專案 ]
<br>    1. dotnet new webapi -o WebApiTest
<br>       執行後會建立WebApiTest目錄夾
<br>    2. dotnet sln add WebApiTest
<br>       執行後會將WebApiTest專案加入CoreSolution解決方案的資料夾中, type CoreSolution.sln , 會顯示方案的內容  
<br>   
<br> 使用Visual Studio Code 選擇啟動專案執行   
<br>    1. code . -r
<br>        執行後會開啟 VS Code, 且 VS Code 的檔案總管會在CoreSolutions中
<br>    2. 右下角會出現C#的通知, 選取Yes 並在上方命令提示選擇MvcTest 或 WebApiTest
<br>        執行後會在CoreSolutions中產生.vscode目錄與launch.json ; tasks.json 兩個檔案
<br>    3. 執行與偵錯, 就會出現所選擇的啟動專案
<br>
<br> -----------------------------------------------
<br> 備註
<br> -----------------------------------------------
<br> 如果需要移除某個專案, 透過 CLI 指令
<br>    1. dotnet sln remove WebApiTest 
<br>        執行後會將 WebApiTest 從方案中移除
<br> 其他可參考書本 第 3 章
<br> = = = = = = = = = = = = = = = = = = = = = = = = 
