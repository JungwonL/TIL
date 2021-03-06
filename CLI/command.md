# Command

command line interface 명령어를 정리합니다.



### pwd

현재 위치한 폴더를 출력하는 명령어입니다.

```shell
pwd
```



### ls

list의 약자로 현재폴더에 있는 파일과 폴더를 출력하는 명령어입니다.

```shell
ls # 숨김폴더는 출력 안함
ls -a # 숨김폴더, 파일까지 모두 출력
```



### cd

change directory의 약자로 폴더를 이동하는 명령어입니다.

```shell
cd <PATH>  # 이동하고 싶은 폴더를 PATH에 입력
```



### 생성

- `touch`: 파일 생성

  ```shell
  touch <a.txt>
  ```

- `mkdir`: 폴더 생성

  ```shell
  mkdir <dir name>
  ```

  

### vim

vim 에디터를 사용하여 편집

연습할 수 있는 사이트: [빔어드벤처](https://vim-adventures.com/) 

- `vi`: 읽기

  ```shell
  vi <a.txt>
  ```

- `i`: 수정(insert)

  ```sh
  i # 누른 후 내용 편집
  ```

- `Esc`: 편집 종료

- `:w`: 저장

- `:q`: 종료

  ```shell
  :wq # 저장 후 vi종료
  ```

  



> 인용구도 작성이 가능



