## git-demo2
- 測試 git 指令

> 建立時間
- 2022/05/21
- 作者:
    - mingqing Chen (陳明卿)


> git reset    將當前 HEAD 重置為指定狀態   (如移動HEADmaster的位置)
                  #git reset 命令用于回退版本，可以指定退回某一次提交的版本
=========================================
- git reset --hard <commit-object>    #  <commit-object> :  sha1 - 7碼(前2碼資料夾名稱)
    - 名義上後面新增/修改的檔案都會被刪除

- git reset --mixed <commit-object>
    -  A --> U

- git reset --soft <commit-object>
    - 恢復在暫存區

- git reflog
    - git reset (checkout) <commit-object>

> 表格

| 專案        | 價格   |  數量  |
| --------   | -----:  | :----:  |
| 計算機      | $1600   |   5     |
| 手機        |   $12   |   12   |
| 管線        |    $1    |  234  |

> github  
https://www.mdeditor.tw/  

echo "# git_demo2" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin https://github.com/mingqingc13/git_demo2.git  
git push -u origin main