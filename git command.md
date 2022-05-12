# GIT

https://www.youtube.com/watch?v=fJImlz2N8vc&list=PLwJr0JSP7i8D041yrTcWB_qEdzijIUX-q&index=2

## Git 02
1. `git status`
2. `git branch` : kiem tra branch hien tai
3. `git branch -m newName` : doi ten branch dang dung
4. `git branch -m oldName newName` : doi ten branch, neu dang dung o branch khac
5. `git add .` : them tat ca thay doi vao git quan ly
6. <img width="547" alt="image" src="https://user-images.githubusercontent.com/96764572/165423810-aee628cf-7b35-4ce9-8df0-1f6bc824d571.png">
7. `git commit -m "content"`
8. `git commit --amend -m "content"`
9. `git log`
10. git log --oneline
11. git log --oneline --graph
12. git log --oneline tenRemote/tenNhanh
13. git restore abcFile
14. git restore -- .
15. git diff
16. git diff --staged (so sanh voi commit cuoi)
17. git diff dsrb23 23kbsdf
18. git diff asf4 4dsaf --stat
19. git checkout 324dsfgd (//id cua commit) -- abcFile
20. git checkout 53sfas -- .
21. .gitignore

## Git 03
20. git reset --soft HEAD~1
21. git reset --hard
22. git reset -- abcFile
23. git branch
24. git branch tenNhanhCanTao
25. git merge tenNhanhConCanGop (dang hieu la o local)
26. git merge tenRemoteCanGop/tenNhanhCangop
27. git merge --abort (huy gop nhanh)
28. git branch -d tenNhanhCanXoa
29. git checkout 322sadf

## Git 05
29. git rebase tenNhanhMuonGop
30. git rebase --continue


## Git 06 : Lam viec voi remote repository
31. ssh
32. `git remote` : kiem tra local dang ket noi toi remote nao
33. `git remote add tenRemote diaChiRemote` (co the dung ssh) : tao 1 remote moi
34. `git remote -v` : xem dia chi cua remote
35. `git remote rm tenRemote` : xoa 1 remote
36. `git push tenRemote` : up toan bo du lieu, cac nhanh len remote
37. `git push tenRemote tenNhanh` : push nhanh tenNhanh tren remote 
38. `git push --all tenRemote`
39. `git push -u tenNhanh tenRemote` : push va tao upstream  de lan sau chi viec chay git push
40. `git push --delete tenRemote tenNhanhRemote` : xoa nhanh tenNhanhRemote tren remote tenRemote
41. `git clone diaChiLuTruGit` : tai ve source code tu remote repository
42. `git fetch` : cap nhat thong tin moi tu remote,  nhung chua ap dung vao local
43. `git fetch tenRemote`
44. `git pull tenRemote tenNhanhMuonCapNhatOLocal` : cap nhat nhanh tenNhanhMuonCapNhatOLocal tu remote tenRemote ve local
45. git log --oneline tenRemote/tenNhanh
46. copy file tu branch nay sang branch khac : 1-> dung o branch muon copy, 2->git checkout tenbranchChuafiile duongDanFile

## Git 09 : Fork va Pull request tren github

47. fork : dung de tham gia cung phat trien voi tac gia cua git repository tren git hub
48. pull request : len git repository tao 1 pull request, dien title, noi dung cua pull request gui cho owner.
   - 1. nhan vao pull request













