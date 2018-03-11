# HelloGithub2


### this is the repo for Github minicourse in E.Major 

#### GTD

1. 要求下載atom



what are the good plug-in on Github （not included in class)?

Is there any time to get more understanding on bookdown(the `pandoc` package)

Finally, I will need three outline file Outline (in detail) (in further detailed)




---

### Course Outline : 

#### 1. what is Git (a version control system) (介紹觀念，很重要）
 
#### 2. Environment on Github 
 
 - `Fork` Let's fork this repo and [r4ds](https://github.com/hadley/r4ds)
 
 ![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/Github_fork_animation.gif)
 
 - `code` `issue` `project` `Wiki` `settings`
 > Let's look at `r4ds` and `E.Major-FB` repo
 
 - `branch` 
 > Let's create a branch called `Studying_0313_your english name` on Github
 
 ![如何開設分支](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/creat_a_branch.png)
 
 （截一張蔡植中的Network，要標出那個點的示意說明就是你的branch名稱） `
 
 3. Environment on  Github desktop 
 
 - `clone`
 
![如何clone一個repo](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/clone_animation.png)
 
 > Is there still your branch `Studying_0313_your english name` in Github desktop environment?
 
![已經開設的分支也會存在](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/branch_still_in_GithubDesktop.png)
 
 #### Now, stay at the branch in Github desktop and use your `Atom` software to open the `Lecturing_0313.md` file
 
 - `commit`+`push`
 
![一開始的檔案內容](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/atom1.png)
 
![新增一句話](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/atom2.png)
 
![GithubDesktop會偵測到檔案變化](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/Githubdstop1.png)

![同步到雲端](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/Githubsync1.png)
 
 - `reverse`
 
![如何進行版本回溯](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/reverse1.png)
 
![版本回溯示意圖](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/reverse2.png)

 > Let's go back to see your `Atom`, the change should be reverted!
 
![變回原始檔案內容](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/atom3.png)
 
 - `push` again
 
 > the local is changed and we need to sync the cloud, namely Github!

![版本回溯也同步到雲端](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/Githubsync2.png)
 
 - `pull request in Github`
 
 > Add the new content in `Lecturing_0313.md` from the `Studying_0313_your english name` branch to `master` branch
 
![再次新增檔案內容](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/atom4.png)
 
![GithubDesktop偵測到改變](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/Githubdesktop2.png)
 
![如何送出pull request](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/pullrequest1.png)

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/pullrequest2.png)

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/pullrequest3.png)

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/pullrequest4.png)

![](https://github.com/PoMingChen/HelloGithub2/blob/master/images/0313_Github_minicourse/pullrequest5.png)

 > what happen at `Network` in `Insights`?
 
 （截一張蔡植中箭頭指回主幹道的示意圖）

 
 3. Let's try on your own 
 
 - create a issue on this `PoMingChen/HelloGithub2` repo
 
 - add something new in the `Lecturing_0313.md` and then `commit`+`push`+`pull request` again
 
 ---
 
 (19:50 10min break)
 
 - add the classmates beside you as your collaborator in `YourUserName/HelloGithub2` repo which was forked from me
 
 --- 
 
 4. Let's work in a pair to resemble as team project 
 
 - `pull request`
 
 請被加入的那位組員新開一個branch（名稱與`Studying_0313_your english name`相同）並在自己的分支的`Lecturing_0313.md`檔案新增一些文字敘述，並且執行`commit`+`push`+`pull request`
 
 這時候因為repo擁有者是組長，必須由他來審核這個pull request是否是適合併入到`master`主幹道裡面。
 
 因為只要組員針對該檔案進行更動，因此理論上會是：able to merge
 
 5. To know what to do when it's a conflict
 
 進行完上個部分的merge後，`master`主幹道就會擁有最新的專案進度，並同步到Github desktop
 
 這時兩人皆進到自己的分支，去針對同一行（自己選）去修改成不同內容
 
 修改好之後，由組長先在自己的分支`commit`+`push`+`pull request`欲進到主幹道，並merge完畢。
 
 再由組員重複一次先在自己的分支`commit`+`push`+`pull request`欲進到主幹道，此時會產生conflict
 
 由組長決定要將哪一段保留，並刪去哪些部分，最終形成新的主幹道。
 
 若是組長與組員同時接續要求pull request，因為Github是與原版本相比，兩者皆會able，但是唯有併入一個之後，衝突就會產生。
 
 
 6. A quick course survey
 
 ---
 
 #### HW
 
 - `Add local repository + publish`
 
 > this the opposite direction from `Github, the cloud` to `GithubDesktop, the local`

 > open an issue in this `HelloGithub2` repo and paste the URL of your repo, therefore, the credit to get the 【經濟時事與多媒體出版】is completed.
 
 (找一個參考示範的連結或解說給他們參考）
 
 ---
 
 Bonus:
 
> [Gitter, where developers come to talk](https://gitter.im/apps)

> [interesting article about Github](https://www.ithome.com.tw/news/95284)

> [Github Help](https://help.github.com)



