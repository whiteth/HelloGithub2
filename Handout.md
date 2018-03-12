### Course Outline : 

### 1. what is Git (a version control system) 

- 版本控制系統有很多不同的軟體，最紅的是git

- Git是分散式版本控制系統（Decentralized Version Control System）

- Github = Git + hub。Github.com提供Git的代管服務，允許使用者在網站上存取程式碼、專案和Git版本管理，也包含社交功能
 
### 2. Environment on Github ： `Fork`/`README` `code` `issue` `project` `Wiki` `settings`/`branch` 
 
 - `Fork` Let's fork this repo and [r4ds](https://github.com/hadley/r4ds)
 
 ![Fork的意義](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/Github_fork_animation.gif)
 
 - `README` `code` `issue` `project` `Wiki` `settings`
 > Let's look at `r4ds` and `E.Major-FB` repo
 
 - `branch` 
 > 現在創造一個叫做`Studying_0313_your english name`的分支
 
 ![如何開設分支](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/creat_a_branch.png)
 
 （截一張蔡植中的Network，要標出那個點的示意說明就是你的branch名稱） `
 
###  3. Environment on  Github desktop : `clone`/`commit`+`push`/`reverse`/`pull request`
 
 - `clone`
 > 把雲端抓到本機
 
![如何clone一個repo](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/clone_animation.png)
 
 > 檢查剛才開設的分支是否也存在GithubDesktop?
 
![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/branch_still_in_GithubDesktop.png)
 
 #### Now, stay at the branch in Github desktop and use your `Atom` software to open the `Lecturing_0313.md` file
 
 - `commit(提交新版本）`+`push`
 
 > 一開始的檔案內容
 
![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/atom1.png)

 > 新增一句話  
 
![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/atom2.png)

 > GithubDesktop會偵測到檔案變化 
 
![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/Githubdstop1.png)

 > 同步到雲端  
 
![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/Githubsync1.png)
 
 - `reverse`
 
>如何進行版本回溯  

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/reverse1.png)

>版本回溯示意圖

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/reverse2.png)

>變回原始檔案內容並再次`push`
 
![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/atom3.png)
 
>版本回溯也同步到雲端

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/Githubsync2.png)
 
 - `pull request in Github`
 
> 如何將分支中的檔案`Lecturing_0313.md`更動，併入到主幹道。
 
> 再次新增檔案內容

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/atom4.png)
 
> GithubDesktop偵測到改變

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/Githubdesktop2.png)

> 如何送出pull request

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/pullrequest1.png)

> 留意檔案內更動內容

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/pullrequest2.png)

> 說明本次欲併入的意義與具體修改內容

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/pullrequest3.png)

> Github會偵測是否與主幹道產生衝突

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/pullrequest4.png)

> 主幹道更新成功，離專案完成更近一步！

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/pullrequest5.png)

 > what happen at `Network` in `Insights`?
 
 （截一張蔡植中箭頭指回主幹道的示意圖）

 
#### 3-1. Let's try on your own 
 
 - 新增一個issue在這個`PoMingChen/HelloGithub2`repo當作發問，或者純粹留言
 
 - 主要重點：
 
   + `Fork`/`README` `code` `issue` `project` `Wiki` `settings`/`branch`
   + `clone`/`commit`+`push`/`reverse`/`pull request`
 
 - add something new in the `Lecturing_0313.md` and then `commit`+`push`+`pull request` again
 
 ---
 
 (19:50 10min break)
 
 - 請兩兩一組，並且由其中一位把另一位加到目前所在的 `YourUserName/HelloGithub2` repo，也就是你一開始從我這邊fork回去的
 
 --- 
 
###  4. Let's work in a pair to resemble as team project 
 
 - `pull request`
 
 (一張植中開設他的分支的圖）
 
 (一張植中新增內容，並同步到雲端的圖）
 
 (一張植中送出pull request的base 和 compare)
 
 (一張允許同意合併的圖）
 
 
### 5. To know what to do when it's a conflict in pull request
 
 (一張由主幹道併入到我的分支的示意圖）
 
（我修改的內容）

（植中修改的內容）
 
 （由我送出合併請求給主幹道的畫面）
 
 （一張植中送出給給主幹道的合併請求，失敗的畫面）
 
 （最終由組長決定保留的畫面）
 
 
 
### 6. A quick course survey
 
 ---
 
### HW
 
 - `Add local repository + publish`
 
 > 從Github到Github Desktop是從雲端到本機的過程，那如何從本機到雲端呢？（Add local Repository)（請不要使用中文路徑）

 > 有意願選修【經濟時事與多媒體出版】學分的同學，請將作業完成後的repo網址，貼到`PoMingChen/HelloGithub2`的issue裡面，就算完成。
 
 ---
 
 Bonus:
 
> [Gitter, where developers come to talk](https://gitter.im/apps)

> [interesting article about Github](https://www.ithome.com.tw/news/95284)

> [Github Help](https://help.github.com)



