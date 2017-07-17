# GIT指令介紹
GIT版本控制基本常用指令


查看檔案狀態  
`git status`

將檔案加入追蹤  
`git add --all`

將以經追蹤的檔案存檔並且寫上存檔訊息  
`git commit -m "123"`

將程式碼推上儲存庫  
`git push origin master`


切換分支  
`git checkout develop`  
> 你要先有 develop 這條分支


開一個新的分支並且直接切換過去  
`git checkout -b develop`  
> git checkout為切換分支 -b 為 branch (分支) 所以簡寫就是幫我開一個新的分支並且切換到那條分支上

將最新的 master 拉下來  
`git pull origin master`

# GIT操作順序
GIT基本使用步驟


先到專案答案夾右鍵(已有專案檔案夾)選  
`Git Bash Here`


進入Bash後先檢查狀態  
`git status`


沒問題就將最新的檔案拉下來  
`git pull "origin master"`  
(雙引號為可切換名稱不是指令 使用指令時不加雙引號)
>根據你要拉的檔案來切換master的名稱


檔案修正過後再次查看檔案狀態  
`git status`


再將檔案加入追蹤  
`git add .`


將以經追蹤的檔案存檔並且寫上存檔訊息  
`git commit -m "123"`


隨後將程式碼推上儲存庫  
 `git push origin master`


 最後在確認檔案狀態  
 `git status`


# GIT多重登入
GIT帳號經由不同電腦登入


首先開啟Git Bash 輸入指令做登入  
`git config --global user.name "MarsW"`  
`git config --global user.email "ymjh11436@gmail.com"`

接著輸入ssh生成指令  
`ssh-keygen -t rsa`  
>出現 Enter file in which to save the key 直接按三次enter跳過
會生成一個.ssh的資料夾 內有兩個檔案

id_rsa 跟 id_rsa(Microsoft Publisher) 即 私鑰跟公鑰

將id_rsa(Microsoft Publisher)用記事本開啟 內容全選 複製

到github的setttings  

選ssh 然後點 new ssh key  

將複製的內容貼到key那一欄
>title不用打  
點add ssh key 就可以了

接著clone專案到本機  
`git clone "git@github.com.......git"`  
>(雙引號為個人github上專案的clone碼 實際輸入指令時不需要加雙引號)


設置完成後將檔案克隆下來


接著對檔案夾右鍵選  
`Git Bash Here`開啟


不斷反覆練習 直到熟悉GITHUB  
不斷反思自己 是否適合做工程師

雖然學習的過程難免會遇到挫折  
不停地碰壁 不停地突破  
路有很多條 不是只有一條  
別被自己的困境侷限了自己  
放開眼界 放開父母的拘束  
keep bater
