# GIT指令介紹
GIT版本控制基本常用指令


查看檔案狀態  
`git sttus`

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
