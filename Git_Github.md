# **GIT** / **GITHUB**
**:warning:**`rm -fr .git` :Xóa git khỏi directory **:warning:**
###### [*‘Docs…*](Content/Git_Github)
> :book: `<...>` :Gợi ý nội dung cần điền vào.

<!-- ============================================================ -->
<details>
<!-- Head -->
   <summary><b>Menu</b></summary>

- [1. git remote](#1-git-remote)‘,
- [2. git push](#2-git-push)
- [3. git pull](#3-git-pull)
- [4. git clone](#4-git-clone)
- [5. Basic](#5-basic)
- [6. git branch](#6-git-branch)
- [7. Ignore](#7-ignore)
- [8. Fix error](#8-fix-error)
- [9. For Linux](#9-for-linux)


</details>

---

<!-- ============================================================ -->

## Start new project
   **:exclamation:**`git init` :Bắt đầu project.
#### 1. **git remote**
   + `git remote add origin <link repository>` :Liên kết git với github qua link.
   + `git remote add origin new-url <link repository>` :Liên kết thêm với repository khác.
   + `git remote rm origin` :Xóa all liên kết.
   + `git remote -v` :Hiển thị thông tin liên kết.

#### 2. **git push**
   + `git push -u origin <branch name> ` :Lần đầu tiên push.
   >:book: 
   >* *Password* là token,
   >* **cách truy cập your token**: *open* `Github` *on web* -> `Settings` -> `Developer settings` -> `Personal access tokens` -> `Tokens (classic)` -> `Generate new token` -> `Select scopes` -> :white_check_mark: repo -> `Generate token`.
   
   + `git push` :Đẩy code lên github, dùng khi có 1 nhánh.
   + `git push origin <branch_Name> ` :Dùng khi có nhiều nhánh.

#### 3. **git pull**
   + `git pull` :Kéo new commit từ github về, dùng khi có 1 nhánh.
   + `git pull origin <branch_Name> ` :Dùng khi có nhiều nhánh.
#### 4. **git clone**   
   + `git clone <link repository> ` :Sao chép repository từ github về nơi bạn đang ở.
   + `git fetch origin <branch_Name> ` :review branch, khác với pull.

#### 5. **Basic**
+ `git status` :Xem trạng thái của repository **(có folder .git)**.
   
<!-- ============================================================ -->
<details>
<!-- Head -->
<summary><b>Menu</b></summary>

<!-- Body -->
  - <a href="#git-add">**git add**</a>
  - <a href="#git-commit">**git commit**</a>
  - <a href="#git-log">**git log**</a>
  - <a href="#git-show">**git show**</a>
  - <a href="#git-diff">**git diff**</a>
  - <a href="#restore">**Undo (restore)**</a>
  - <a href="#reset">**Undo (reset)**</a>
  - <a href="#git-revert">**git revert**</a>
   </details>
<!-- ============================================================ -->

---
   
   + <h4 id="git-add">git add</h4>  
      
      + `git add` :Add new file vào git.
      + `git add .` :Add tất cả.

   + <h4 id="git-commit">git commit</h4>
      
      + `git commit` :Dùng sau **git add**, nôm na là đóng gói lại và không có nhãn.
      + `git commit -m <label>` :Commit có nhãn.
      + `git commit -am <label>` :Commit không cần dùng **git add**, sử dụng đối với các file đã từng **git add** lần đầu.
       

   + <h4 id="git-log">git log</h4>
      
      + `git log` :Show history commit.
      + `git log --reverse` :Hiển thị tương tự git log, nhưng thứ tự sắp xếp commit ngược lại.
      + `git log --oneline` : Mỗi commit chỉ hiển thị một dòng, bao gồm ID commit và dòng đầu tiên của messages (cách này có vẻ dễ nhìn nhất).
      + `git log -p` :Hiển thị chi tiết thông tin commit, bao gồm cả nội dung thay đổi (thêm/xóa dòng code nào).


   + <h4 id="git-show">git show</h4>
   
      >:book:
      >**ID-commit** lấy từ **git log**.
      >
      >> **\<ID-commit> :** ***(9d7dbd0580d2ece5f822440766707468d08ae09e)***
      + `git show <ID-commit>` :Show chi tiết thay đổi của 1 commit.

   + <h4 id="git-diff">git diff</h4>
   
      + `git diff` :Xem sự khác nhau giữa file đã thay đổi *(hiển thị trong git status là modified)* với file ban đầu.

   + <h4 id="restore">Undo (restore)</h4>
   
      + `git restore <filename> ` :Quay lại trước khi thay đổi nội dung trong \<filename>.:+1:
      + `git checkout --<filename> ` :Tương tự.:-1:
   
   + <h4 id="reset">Undo (reset)</h4>
   
      + `git reset HEAD <filename> ` :Undo về trước khi đã dùng **git add** với \<filename>.:+1:
      + `git restore --staged <filename> ` :Tương tự.:-1:
      
      ---

      + `git reset --mixed <ID-commit> ` :Gỡ commit trước \<ID-commit> và Undo về trước khi **git add**.
      + `git reset --soft <ID-commit> ` :Gỡ commit trước \<ID-commit>:warning:
      + `git reset --hard <ID-commit> ` :Xóa commit trước \<ID-commit>:warning:

   + <h4 id ="git-revert">git revert</h4>
   
      + `git revert <ID-commit> ` :Xóa tất cả những thay đổi tại \<ID-commit>:warning:

#### 6. **git branch**
   + `git branch` :List các nhánh **(\* là nhánh đang ở)**.
   + `git branch -D <branch-name> ` :Xóa nhánh **\<branch-name>**.
   
   + `git checkout -b <branch-name> ` :Tạo 1 nhánh mới.
   + `git checkout <branch-name>` :Di chuyển về nhánh **\<branch-name>**.
   
   + `git merge <branch-name> ` :Kéo các commit từ branch \<branch-name> về branch đang ở.

#### 7. **Ignore**
   >**.gitignore** là file chứa các file or folder không cần **commit** bằng cách ghi tên vào file **.gitignore**.

#### 8. **Fix error**
   >Xử lí ***Conflicting file*** (2 người cùng sửa 1 file trên 2 nhánh khác nhau).
   + **step 1** :`git pull`.
   + **step 2** :Di chuyển tới nhánh cần xử lí (`git checkout` \<branch_Name> ).
   + **step 3** :Kéo nhánh master(main) về nhánh cần xử lí (`git merge` master(main) ).
   + **step 4** :Sửa file hiển thị lỗi sau khi merge (file 2 người cùng sửa).
   + **step 5** :**Add,commit** file rồi **push branch** lên github.
   + **step 6** :**Đã merge, pull** request bình thường, lỗi ***Conflicting file*** đã được fix.

#### 9. **For Linux**
         git config --global credential.helper "cache --timeout=90000"
    
   >Duy trì thời gian đăng nhập, sau 90000s phải nhập lại mật khẩu và chạy lại lệnh để tiếp tục duy trì đăng nhập.

[ end ]: end