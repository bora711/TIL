# Branch

- `github.com` > `Repository name` 명 작성 > `Create repository`

![image-20201230132415817](201230_git_branch.assets/image-20201230132415817.png)

![image-20201230132507001](201230_git_branch.assets/image-20201230132507001.png)



![image-20201230133321459](201230_git_branch.assets/image-20201230133321459.png)

![image-20201230133408227](201230_git_branch.assets/image-20201230133408227.png)

![image-20201230133340800](201230_git_branch.assets/image-20201230133340800.png)

![image-20201230133506076](201230_git_branch.assets/image-20201230133506076.png)

![image-20201230133702056](201230_git_branch.assets/image-20201230133702056.png)

![image-20201230133912811](201230_git_branch.assets/image-20201230133912811.png)

![image-20201230134010418](201230_git_branch.assets/image-20201230134010418.png)

![image-20201230134047961](201230_git_branch.assets/image-20201230134047961.png)

![image-20201230134103888](201230_git_branch.assets/image-20201230134103888.png)



## bora라는 branch를 끌어오기

- ```shell
  $ git merge bora
  ```

  ![image-20201230134437621](201230_git_branch.assets/image-20201230134437621.png)

- master와 bora branch가 동일 선상에 있다는 것을 볼 수 있다.

  ```shell
  $ git log --oneline --graph
  ```

  

![image-20201230134509605](201230_git_branch.assets/image-20201230134509605.png)









## 다른 branch 삭제

- ```shell
  $ git branch -D bora
  $ git branch
  ```

![image-20201230134700222](201230_git_branch.assets/image-20201230134700222.png)



## 다른 branch와의 충돌로 인한 merge

![image-20201230134823367](201230_git_branch.assets/image-20201230134823367.png)

![image-20201230140528391](201230_git_branch.assets/image-20201230140528391.png)

![image-20201230140648430](201230_git_branch.assets/image-20201230140648430.png)





![image-20201230140742678](201230_git_branch.assets/image-20201230140742678.png)

![image-20201230140849425](201230_git_branch.assets/image-20201230140849425.png)

![image-20201230140933564](201230_git_branch.assets/image-20201230140933564.png)

- 아래와 같이 나오면 충돌 일어난 것이 아니다. 왜?
  - feature/login -> 맨 아랫줄 수정
  - master -> 맨 윗줄 수정
    - 그러므로 `git merge <feature/login>`을 하면 된다.

![image-20201230140958065](201230_git_branch.assets/image-20201230140958065.png)

- 저장하고 나가기

![image-20201230141513238](201230_git_branch.assets/image-20201230141513238.png)

![image-20201230141553102](201230_git_branch.assets/image-20201230141553102.png)

- 즉, 3 way merging이다

  ![image-20201230141615955](201230_git_branch.assets/image-20201230141615955.png)

  ![image-20201230141810039](201230_git_branch.assets/image-20201230141810039.png)



## branch 삭제

- branch 삭제

  ```shell
  $ git branch -D feature/login	
  ```

  

- branch 삭제 되었는지 확인

  ```shell
  $ git log --oneline --graph
  ```

  

  ![image-20201230142001126](201230_git_branch.assets/image-20201230142001126.png)







## 같은 줄에서 수정하여 충돌을 만들기

- 로그아웃 branch 만들어서 수정하기

![image-20201230142351681](201230_git_branch.assets/image-20201230142351681.png)

![image-20201230142527892](201230_git_branch.assets/image-20201230142527892.png)

![image-20201230142612253](201230_git_branch.assets/image-20201230142612253.png)

![image-20201230142745832](201230_git_branch.assets/image-20201230142745832.png)

![image-20201230142806610](201230_git_branch.assets/image-20201230142806610.png)

![image-20201230142950399](201230_git_branch.assets/image-20201230142950399.png)

![image-20201230143039049](201230_git_branch.assets/image-20201230143039049.png)

![image-20201230143134786](201230_git_branch.assets/image-20201230143134786.png)