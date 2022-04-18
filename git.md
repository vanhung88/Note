# git flow :
- working directory -> staging area -> local repository -> remote repository
- git push -u origin <branch name> : push lần đầu lên server , tạo ra một upstream lk giữa local và remote , lần push sau chỉ cần git push

# git commit
- log history
* git log --oneline : show history gon hon
* git log reflog : show history all action

* git commit -a : lấy những file chưa add
* git commit --amend : đè lên commit gần nhất , không tạo ra commit mới

# git reset
