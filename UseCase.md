1. Lỡ commit dư 1 file, muốn loại bỏ file đó ra khỏi commit mà vẫn giữ nguyên message commit
    `git reset HEAD^ -- path/to/file`
    `git commit --amend --no-edit`

2. Đặt lại author là tên mình khi làm việc trên máy người khác
        `git commit --author="Name <email>" -m "commit message"`

    Nếu đã nhỡ commit rồi muốn sửa lại thi ta có thể sử dụng
        `git commit --amend --author="Name <email>" -m "commit message"`

3. Sau khi merge mà không tự tin lắm muốn trở lại trước lúc merge
        `git reset --hard ORIG_HEAD`

        Cách trên cũng áp dụng được với rebase , 
        hoặc không thì ta có lại sử dụng đến git reflog sau đó git reset --head <commit_hash> để tìm lại commit cuối cùng của branch trước khi merge hoặc rebase

4. Nhỡ pull về mà conflic nhiều quá, fix không nổi nản quá muốn trở lại
        `git merge --abort`
        or
        `git reset --hard ORIG_HEAD` 
