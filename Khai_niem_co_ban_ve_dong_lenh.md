# Khái niệm cơ bản về dòng lệnh

### Thảo luận về phân phối
Sử dụng các bản phân phối(distro). Một bản phân phối nên sử dụng khi follow cuốn sách này như: Centos7, Ubuntu 18.04 LTS.
### Tiếp cận một Shell
Để truy cập vào **Shell**, có thể ssh vào máy hoặc trên Ubuntu Desktop nhấn `Ctrl + Alt + T`
### Khám phá các tùy chọn Linux Shell của bạn
Một số bản phân phối Sell:
1. Bash
1. Dash
1. KornShell
1. tcsh
1. Z shell
Listin 1.1: Hiển thị Centos thuộc shell nào
```
[root@laiduy ~]# readlink /bin/sh
bash
```
Listin 1.2: Echo phiên bản shell
```
[root@laiduy ~]# echo $BASH_VERTION
4.2.46(2)-release
```
Listin 1.3: Hiển thị bản phân phối Linux.
```
[root@laiduy ~]# uname -a
Linux laiduy 3.10.0-1160.e17.x86_64 #1 SMP Mon Oct  19 16:18:59 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux.
```
### Điều hướng cấu trúc thư mục
Sử dụng lênh `cd` để di chuyển giữa các thư mục và lệnh `pwd` để xem vị trí thư mục hiện tại.

### Tìm sự giúp đỡ
- Sử dụng lệnh `history` để xem lại các lệnh thực hiện gần đây.
```
cat /var/laiduy
cd laiduy
head -n6 /etc/passwd
ls -l
cd ~
blkid
readlink /bin/sh
cd ubuntu
echo $BASH_VERSION
uname -a
Hell.s
Hello.sh
/root/laikhandhuy/Hello.sh
man
history
```
- Để quay lại 1 lệnh đã sử dụng trước đó dùng lệnh `!65`
```
pwd
/root
```
- Hiển thị tên tệp lịch sử `echo $HISTFILE`
```
/root/.bash_history
```

