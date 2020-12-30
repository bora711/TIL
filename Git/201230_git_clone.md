# Clone 하기

- `multicampus` 폴더 만들기

![image-20201230093254238](201230_git_clone.assets/image-20201230093254238.png)

- `github.com` >`repository 선택` > `code` > `https clone`

  ![image-20201230093436077](201230_git_clone.assets/image-20201230093436077.png)

- `multicampus 폴더` -> 우클릭 -> `Git Bash Here`

- ```shell
  $ git clone https://github.com/bora711/TIL.git
  $ ls
  ```

  ![image-20201230093549691](201230_git_clone.assets/image-20201230093549691.png)

- `바탕화면\multicampus\TIL` 폴더 생성되었는지 확인

  ![image-20201230093651567](201230_git_clone.assets/image-20201230093651567.png)









## 다른 컴퓨터에서 clone 할 때의 구조

![image-20201230093751769](201230_git_clone.assets/image-20201230093751769.png)







## Clone 후 수정할때

- `바탕화면\multicampus\TIL\README` 파일 수정

  ![image-20201230094015657](201230_git_clone.assets/image-20201230094015657.png)

  

  

  ![image-20201230094123838](201230_git_clone.assets/image-20201230094123838.png)



- clone하여 remote 주소를 이미 알고 있기 때문에 push를 해도 `바탕화면\til`에도 업데이트가 된다.

  ![image-20201230094430451](201230_git_clone.assets/image-20201230094430451.png)

  

- `github.com` > `repository` > `TIL` > `README.md` 확인

![image-20201230094512471](201230_git_clone.assets/image-20201230094512471.png)



## 당겨오기 

- ```shell
  $ git pull origin master
  ```

  ![image-20201230094853516](201230_git_clone.assets/image-20201230094853516.png)

- `바탕화면` -> `til` -> `README` -> 업데이트된 파일과 내용 확인

  ![image-20201230094928929](201230_git_clone.assets/image-20201230094928929.png)



