This is just a demo of my new technique, using git makes me feel convenient in storaging my documents.
Commands for git utility
0. git init (bao gio tao ra mot thu muc dua no lam local repository thi phai dung lenh git init dau tien)
1. git status (always kiem tra trang thai cua working tree, xem la co file nao chua duoc source control untrack chua, hay co file nao duoc track roi)
2. git add file_and_directory_names, git add . (add them cac file, cach nhau boi space, . la add toan bo cac file trong working directory dua vao staging area)
3. git commit -m "message of commit" (sau khi dua cac file vao staging area, muon dua no vao git repository thi ta can phai commit)
4. git log (show ra nhung commit voi id cua no, thong tin nguoi thuc hien commit va thoi gian, ten cua file duoc add)
5. git show commit_id (show ra thong tin 1 commit khi dua vao argument la id cua commit do)
6. git diff (show ra nhung gi thay doi o working directory cua cac file tung duoc them vao git repository)
7. git configure --global user.name "user_name" && git configure --global user.email "user_email" (chi configure mot lan voi global)
8. git rm --cached file_name (xoa di file o staging area), ta co lenh git restore --staged <file> (untrack file o staging area, dua no ve working directory) or git reset ten_file
nhu vay co 3 lenh de untrack files 
9. git restore file_name (sau khi modify xong ma chua add vao staging area, file van o working directory, muon dua no ve trang thai truoc khi sua thi ta dung lenh git restore ten_file)
tuong tu ta co lenh git checkout --file_name
co 2 lenh de dua file ve trang thai ban dau 
10. git branch in ra branch hien tai dang tro toi commit gan nhat, mac dinh la branch master 
git branch <branch-name> de tao ra branch moi neu branch-name do chua exist
git branch -D <branch-name> de xoa di 1 branch khi dang o branch khac
11. git checkout -b branch-name cung de tao ra branch moi 
git checkout branch-name de chuyen sang branch co ten la branch-name
12. git merge other-branch-name de merge thay doi tu other-branch ve current branch
13. git reset --soft <commit-id> de tro HEAD ve commit-id do, sau do thay doi lai commit(thuong cho commit-id cua commit truoc commit ma ta muon thay doi), che do soft la dua no ve dang
chua commit, che do mixed dua no ve working directory, che do hard xoa luon commit do 
14. github la dich vu luu tru file truc tuyen, hoat dong voi su tro giup cua git, ta co the tao cac remote repository thuoc ve origin, sau do remote add origin nay ve local repository
de co the dong bo hoa local vs remote repository
git remote add origin <duong link repository.git> 
git add . 
git commit -m "message"
git push -u origin master (voi lan push dau tien)
git push voi cac lan push tiep theo
15. git credential voi ssh-key de do mat cong nhap mat khau nhieu lan

