###### tags: `laradock`

# Laradock阿度版

## 安裝步驟
```
0. 安裝docker
1. clone本專案
2. 安裝vscode套件docker
3. 輸入指令啟動docker
```

### 0.安裝docker
> window跟linux版本安裝方式不同，請先自行安裝並確認可運行
### 1.clone本專案
> 使用sourceTree之類的 or 其他
### 2.安裝vscode套件docker
>推薦[docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
>
>方便查看容器狀況(非必要)
### 3.輸入指令啟動docker
>開啟vscode->開啟laradock資料夾
>
>開啟終端機 ctrl + ~ 
>
>輸入docker-compose up -d nginx mariadb phpmyadmin

## 大功告成


### 1.開啟瀏覽器輸入 [http://localhost:8080](http://localhost:8080)

> 可看到phpmyadmin登入畫面
> 
> 伺服器: mariadb
> 
> 帳號/密碼:root/root 

### 2.開啟瀏覽器輸入 [http://localhost](http://localhost)
>沒有東西是很正常的
>
>先建立web資料夾，與laradock同一層
>
>web底下建立public資料夾
>
>在public資料夾底下建立index.html
>
>重新整理就可以看到index.html的內容了