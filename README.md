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


若master是用ssh加密需在個別的電腦做ssh加密
再將公鑰加入至GIT帳號就能使用別台電腦登入


設置完成後將檔案克隆下來


接著對檔案夾右鍵選  
`Git Bash`開啟
