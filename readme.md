chatbot 만들기 
==============
0. 목적 정하기
@
-------------
1. github : 코드관리
--------------------
2. 챗봇 환경 구축
--------------------
2-1. 패키지 구축
2-1-1. numpy
2-1-2. nltk
2-1-3. tensorflow
2-1-4. tflearn


git 사용방법 / 오류 정리
======================

초기설정
--------
* git할 폴더 생성   
* git bash here 지정   
* git init   
* git remote add origin https:// ~ 
   
   * git add ~   
   * git commit -m "~"   
   * git push origin master 

일단 안되면 
----------

* git pull origin master
* git push origin master

* maerg 오류는
-> git pull origin master --allow-unrelated-histories

신규 저장소 생성 시 순서
----------------------
* echo "# -" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/kirokrobot/-.git
* git push -u origin main

* git remote add origin https://github.com/kirokrobot/-.git
* git branch -M main
* git push -u origin main