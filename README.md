# 簡單的短連結

> 這是一個非常簡單的短連結 , 在[Issues](https://github.com/Tira-tw/Url/issues)創建[New issue](https://github.com/Tira-tw/Url/issues/new/choose) , 標題打上網址上傳就可以了!
<br>
> 請依照問題編碼使用!<br>
> 比如說 : #1問題編碼 >> "http://url.thisalesa.eu.org/1" , 這樣就可以了! <br>

# 想架設 , 要如何設定?

> 需要先[fork](https://github.com/Tira-tw/Url/fork) , 然後到CNAME檔案更改你要用的網域 , 然後到404.html檔案第12行更改以下 : <br>
```
 var GITHUB_ISSUES_LINK =
        "https://api.github.com/repos/Tira-tw/Url/issues/";
      var PATH_SEGMENTS_TO_SKIP = 0;
```
請自行修改: 
```
https://api.github.com/repos/Github用戶名稱/Repository名稱/issues/ 
```
> 更改完之後到Settings > Pages > Custom domain驗證 , 跳出有關DNS需要去[cloudflare.com](https://www.cloudflare.com/)設定DNS! <br>
```
 選擇 : 類型CNAME
 名稱 : @[都可以 , 只是網域前面需要加名稱! , ex : 名稱.yourdomain.com]
 內容 : Github用戶名稱.github.io [ ex : tira-tw.github.io ]
 ```
 <br>儲存 , 這樣就完成了owob <br>
> 最後回到Custom domain驗證 , 重新驗證就完成了! <br>
> 可以測試一下在Issues添加網址看看 , 如果成功恭喜你! , ~~[不妨訂閱一下?](https://www.youtube.com/c/Tiratw/)~~ , 如果失敗請聯絡我! <br>
# 聯絡
> Discord : ๛M͜͡r幻月シ#1853 <br>
> Discord Group : https://discord.gg/D9hWKmest8
