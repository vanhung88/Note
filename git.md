# git flow :
- working directory -> staging area -> local repository -> remote repository
- git push -u origin <branch name> : push lần đầu lên server , tạo ra một upstream lk giữa local và remote , lần push sau chỉ cần git push

# git commit
- log history
* git log --oneline : show history gon hon
* git log reflog : show history all action

* git commit -a : lấy những thay đổi chưa đc add
* git commit --amend : đè lên commit gần nhất , không tạo ra commit mới

# git reset
- git reset --soft id : trở về commit(id) -> đưa các commit trước đó về staging
- git reset --mixed id : trở về commit(id) -> đưa các commit trước đó về working directory
- git reset --hard id : xóa bỏ các commit và thay đổi nó đi qua

# git revert
- git revert id : loại bỏ 1 commit đó , loại bỏ thay đổi -> không nên dùng nhiều
 
 # branch
 . git branch -a : xem all branch local va remote
 git fetch origin : fetch all from origin
 git fetch origin branch : featch one branch
  
# rebase 
- fix conflix
git rebase <branch>
git add .
git rebase --continue
 
