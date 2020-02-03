### Pycharm을 이용해 README를 작성해보자
* * *
 ### __파일설치__

   - Git 설치하기: <https://git-scm.com/>
       
     ![git](https://github.com/wotjd0715/markdown/blob/master/git1.png)
      
   - pycharm 설치하기: 
     <https://www.jetbrains.com/pycharm/download/#section=windows/>
        
     ![pycharm](https://github.com/wotjd0715/markdown/blob/master/pycharm1.png)
___
  ### __Github 로그인후 Resistory 생성__
   ![git](https://github.com/wotjd0715/markdown/blob/master/github1.png)
   
   ![git](https://github.com/wotjd0715/markdown/blob/master/github2.png) 
   
   ![git](https://github.com/wotjd0715/markdown/blob/master/github3.png)
   
 ___
  ### Pycharm에서 README작성
  - new project 생성후 아래쪽 Terminal에   입력해줍니다
  ```python
  git clone 아까 복사해둔 주소 붙여넣기 
  ```
 - README 꾸미기
 
   ![git](https://github.com/wotjd0715/markdown/blob/master/p2.png)
  
  README는 일반 문서와 달리 Markdown으로 쓰입니다
  
  잠고: <https://gist.github.com/ihoneymon/652be052a0727ad59601>

---
### Github에 업로드 하기

 - README파일이 있는 폴더로 이동하기
 ```python
 cd README.md가 있는 파일명(ex. cd markdown)
 ```
 - Github에 업로드 하기 
 ```python
 git add .
 git commit -m "README"
 git push origin master
 ```
 git push origin master에서 오류가 생길시 
 ```python
git push origin +master 
```
를 통해 강제 업로드가 가능하지만    
기존의 파일을 잃어버릴수 있습니다.
 - Github으로 돌아가 새로고침을 통해 확인하기
 
    