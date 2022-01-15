# git

공유 문서

* [git 간편 안내서](http://rogerdudler.github.io/git-guide/index.ko.html)
* [카카오 택시 데이터(2018)](https://brunch.co.kr/@kakao-it/38)
* [백엔드 개발자 되기](https://d2.naver.com/news/3435170)
* [github 홈페이지 안내서](https://guides.github.com/activities/hello-world/)
* [git 책](https://git-scm.com/book/ko/v2)
* [git 정리](https://backlog.com/git-tutorial/kr/stepup/stepup1_1.html)

# git 특강 마지막 정리

Q1. 비어있는 파일을 만들기 위한 bash 명령어는 ? 

​	A : touch

Q2.  Git 원격저장소의 url이 [https://google.com](https://www.google.com/url?q=https://google.com&sa=D&source=editors&ust=1625587304898000&usg=AFQjCNECXyuWYpmtNRec3JmrhQdZpFTKlQ) 일때 원격저장소로 설정하기 위한 명령어는?

​	A : remote

Q3. 다음의 오류 메시지의 발생 원인은?

![image-20210707000502083](C:/Users/dbswj/AppData/Roaming/Typora/typora-user-images/image-20210707000502083.png)

​	A : git init을 안했기 때문

Q4. 다음중 커밋을 할 시점으로 적절하지 않을 것을 모두 고르시오.

- [ ] 모든 기능 개발이 완성되었을 때
- [ ] 모든 기능 중 일부 기능만 완성하였을 때
- [x] 작업을 하던 중 식사하러 갈 때
- [x] 작업을 하던 중 기능 개발은 완성 안되었지만 긴급하게 작업해야할 때

Q5. git 저장소 내에서 특정 파일/폴더 등을 git으로 관리하고 싶지 않을 때 사용하는 파일은?

​	A : .gitignore

Q6. push를 했을 때 원격저장소에 반영되는 것은?

​	A : updates, 새로 추가되거나 수정된 것

Q7. 다음 오류 메시지가 발생했을 때 해결하기 위한 명령어들을 순서대로 작성하시오

<img src="C:/Users/dbswj/AppData/Roaming/Typora/typora-user-images/image-20210707000916808.png" alt="image-20210707000916808" style="zoom: 67%;" />

​	A :

Q7-1. 위의 상황의 이유를 알기 위해 로컬에서 작성해야 하는 명령어를 쓰시오.

​	A : git status

Q8. clone과 pull 명령어의 차이점을 쓰시오.

​	A : clone은 local에 아무것도 없는 상태에서 원격저장소의 데이터를 가져오는 것.

​		  pull은 local에 이미 있고, 원격저장소의 수정상태를 반영하기 위해 하는 것

Q9. 로컬에서 브랜치를 merge하면서 충돌(conflict)가 발생하였을 때 충돌난 파일 목록을 확인하기 위해 작성해야 하는 명령어를 쓰시오

​	A : git merge

Q10. 다음의 메시지가 발생하는 이유는 ?

![image-20210707002223188](C:/Users/dbswj/AppData/Roaming/Typora/typora-user-images/image-20210707002223188.png)

​	A : 커밋할 것이 없다.

Q10-1. 상황을 보기 위해 어떤 명령어를 입력해야 하는지 쓰시오.

 	A : git status

Q11. 다음의 메시지가 발생하는 이유는?

![image-20210707002347511](C:/Users/dbswj/AppData/Roaming/Typora/typora-user-images/image-20210707002347511.png)

​	A : 수정된 사항이 없음

Q11-1. 상황을 보기 위해 어떤 명령어를 입력해야 하는지 쓰시오.

​	A : git log

Q12. Github flow 에서 Shared Repository와 Fork 모델의 가장 큰 차이점은 ?

​	A : 권한의 유무