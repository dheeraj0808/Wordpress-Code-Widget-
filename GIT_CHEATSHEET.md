# Git Command Practice Cheatsheet 🚀

Aap is file ka use Git commands ki practice karne ke liye kar sakte hain.

## 1. Basics (Basic Commands)
- `git init`: Naya repository banane ke liye.
- `git status`: File changes check karne ke liye.
- `git add <filename>`: File ko staging area me add karne ke liye (use `git add .` for all files).
- `git commit -m "Your Message"`: Changes ko save (record) karne ke liye.

## 2. Remote Operations
- `git clone <url>`: Kisi existing repository ko copy karne ke liye.
- `git remote add origin <url>`: Remote repository se connect karne ke liye.
- `git push -u origin main`: Changes ko internet (GitHub/GitLab) par bhejne ke liye.
- `git pull`: Remote se latest changes lene aur current files update karne ke liye.

## 3. Branching & Merging
- `git branch`: Branches ki list dekhne ke liye.
- `git checkout -b <branchname>`: Nayi branch banane aur usme switch karne ke liye.
- `git checkout <branchname>`: Branch badalne ke liye.
- `git merge <branchname>`: Kissi branch ke changes ko current branch me milane (merge) ke liye.

## 4. Stashing (Drafting)
- `git stash`: Adhe-adhura kaam (temporary changes) ko save karke side me rakhne ke liye.
- `git stash list`: Saare stash ki list dekhne ke liye.
- `git stash pop`: Saved changes ko wapas laane aur stash se remove karne ke liye.
- `git stash apply`: Changes wapas laaye bina stash se remove kiye.

## 5. Advanced Commands
- `git rebase main`: Apni branch ko main branch ke top par move karne ke liye (Clean history ke liye use hota hai).
- `git log`: Commit history dekhne ke liye.
- `git diff`: Files me kya changes huye hain, wo dekhne ke liye.
- `git reset <file>`: File ko staging area se hatane ke liye.
- `git revert <commit-id>`: Purane commit ke changes ko undo karne ke liye ek naya commit banake.

---

### Practice Steps (Kaise Practice Karein):
1. Pehle `git init` karein agar nahi kiya hai.
2. `practice_code.js` me kuch badlav karein.
3. `git add practice_code.js` karein.
4. `git commit -m "Updated practice code"` karein.
5. Ek nayi branch banayein: `git checkout -b feature-test`.
6. Kuch aur changes karein aur `git stash` try karein.
7. Wapas lane ke liye `git stash pop` karein.
