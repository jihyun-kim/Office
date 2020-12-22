Office
======

### About

This is your project's README.md file. It helps users understand what your
project does, how to use it and anything else they may need to know.

=======

Deploy message

2020. 3. 26. 오후 3:19:25node: 8eafa98e.7fec18
msg : string[16]
"pyfile not exist"

=======
Python Shell 설정방법
=========
컨테이넌에 접근
$ docker exec -it mynodered bash
$pwd
/usr/src/node-red
$ls
....

현재 위치에서 sftp로 자료 가져온다
$ sftp stvin@10.70.17.51
sftp> pwd
sftp> cd workspace/node-red/pythonshell
....
> get subprogram.py
> get formated.py
....

다른 접근법
$ docker run -i -t --name myvolume -v myvolume:/root/  ubuntu:14.04 
다른 프로그램으로 로컬 볼륨을 접근한다


