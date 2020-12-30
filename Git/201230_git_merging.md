# 원하지 않은 파일 빼고 올리기

![image-20201230102340306](C:\Users\bora\AppData\Roaming\Typora\typora-user-images\image-20201230102340306.png)

![image-20201230102541083](C:\Users\bora\AppData\Roaming\Typora\typora-user-images\image-20201230102541083.png)

![image-20201230102606742](C:\Users\bora\AppData\Roaming\Typora\typora-user-images\image-20201230102606742.png)

![image-20201230102634233](C:\Users\bora\AppData\Roaming\Typora\typora-user-images\image-20201230102634233.png)



![image-20201230103304210](201230_git_except.assets/image-20201230103304210.png)

![image-20201230103317913](201230_git_except.assets/image-20201230103317913.png)

![image-20201230103357807](201230_git_except.assets/image-20201230103357807.png)

![image-20201230103448792](201230_git_except.assets/image-20201230103448792.png)

![image-20201230103513772](201230_git_except.assets/image-20201230103513772.png)

![image-20201230103528987](201230_git_except.assets/image-20201230103528987.png)



`.gitignore`는 최상단에 둬야 한다. 예를 들어 `db.sqlite`가 `.gitignore`랑 같이 있다면 `db.sqlite` 를 제외 시켜주지 않기 때문에 유저 정보 (아이디, 이름, 비밀번호 등)가 남아있다.







## 둘의 싱크가 안맞아서 생기는 오류

![image-20201230104516028](201230_git_except.assets/image-20201230104516028.png)

![image-20201230104556926](201230_git_except.assets/image-20201230104556926.png)

- 데이터를 올리는 과정에서 오류 남

![image-20201230104638899](201230_git_except.assets/image-20201230104638899.png)

![image-20201230104717261](201230_git_except.assets/image-20201230104717261.png)

![image-20201230104828917](201230_git_except.assets/image-20201230104828917.png)









- ```shell
  git pull origin master
  ```

![image-20201230105012083](201230_git_except.assets/image-20201230105012083.png)



- ```shell
  $ git add .
  $ git commit -m "머징완료"
  $ git push origin master
  ```

  ![image-20201230111154591](201230_git_except.assets/image-20201230111154591.png)

  ![image-20201230111211038](201230_git_except.assets/image-20201230111211038.png)



- ㅇ

  ```shell
  $ git log --oneline
  $ git pull origin master
  ```

  

  ![image-20201230111348189](201230_git_except.assets/image-20201230111348189.png)







## 이런 경우는 오류 안 남

![image-20201230111742288](201230_git_except.assets/image-20201230111742288.png)















## 끝말잇기

![image-20201230112545753](201230_git_except.assets/image-20201230112545753.png)

![image-20201230112751428](201230_git_except.assets/image-20201230112751428.png)

![image-20201230112908890](201230_git_except.assets/image-20201230112908890.png)

![image-20201230112940409](201230_git_except.assets/image-20201230112940409.png)



![image-20201230113500920](201230_git_except.assets/image-20201230113500920.png)

![image-20201230113047849](201230_git_except.assets/image-20201230113047849.png)

![image-20201230113120046](201230_git_except.assets/image-20201230113120046.png)

![image-20201230113147424](201230_git_except.assets/image-20201230113147424.png)

![image-20201230113303284](201230_git_except.assets/image-20201230113303284.png)





### git 클론 받기

- `바탕화면\Git Bash Here`

![image-20201230113652619](201230_git_except.assets/image-20201230113652619.png)

```
$ git pull origin master
```



![image-20201230114041585](201230_git_except.assets/image-20201230114041585.png)

![image-20201230114239574](201230_git_except.assets/image-20201230114239574.png)

![image-20201230114317345](201230_git_except.assets/image-20201230114317345.png)

![image-20201230114408201](201230_git_except.assets/image-20201230114408201.png)

![image-20201230114623072](201230_git_except.assets/image-20201230114623072.png)





![image-20201230114759541](201230_git_except.assets/image-20201230114759541.png)

![image-20201230115010114](201230_git_except.assets/image-20201230115010114.png)

![image-20201230115026933](201230_git_except.assets/image-20201230115026933.png)











![image-20201230131913244](201230_git_except.assets/image-20201230131913244.png)

![image-20201230132020576](201230_git_except.assets/image-20201230132020576.png)

![image-20201230132037313](201230_git_except.assets/image-20201230132037313.png)