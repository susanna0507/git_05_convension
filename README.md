# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

1. 순서가 있는 목록
2. 순서가 있는 목록
   1. 순서가 있는 목록
   2. 순서가 있는 목록

- 순서가 없는 목록
  - 대쉬 (hyphen)
  + 더하기 (plus sign)
  * 별표 (asterisk)

### 링크 (Links)

[구글](https://www.google.com)  
[네이버](https://www.naver.com)  
[구글홈페이지]<https://www.google.com>  
[네이버홈페이지]<https://www.naver.com>

### 이미지 (Images)

![한소희](https://search.pstatic.net/common?type=b&size=216&expire=1&refresh=true&quality=100&direct=true&src=http%3A%2F%2Fsstatic.naver.net%2Fpeople%2Fportrait%2F202001%2F20200113143850805.jpg)

[![구글](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](https://www.google.com)

![조토리](./asset/dog.jpg)


### 인라인 (Inline) 코드 강조
`백틱 1개`는 '인라인 코드 강조'를 의미한다.

```java
   public class Exam(
      public static void main(String[] args){
         System.out.println("exam");
      }
   }
```


### 표 (Table)
|이름|성별|주소|
|---|---|---:|
|홍길동|남|경기도 화성시|
|한소희|여|서울|

: 붙이는 방향으로 정렬, 양쪽이면 가운데 정렬임


### 인용문(BlockQuote)
> 타인의 말이나 문장을 직접 또는 간접으로 가져온다.
>> 인용문1
>>> 인용문2


### 수평선 (Morizental Rule)
각 기호를 3개 이상 입력하면 된다
---
(hyphen)
***
(asterisk)
___
(Underscores)


### 줄바꿈 (line breaks)
바다<br>
하늘   <!--띄어쓰기 2번 이상> <!--주석처리기능-->   
구름


----
# TIL

## 리눅스 명령어

1. ls

   > list(목록)

2. cd
   change directory (작업 경로 변경)

3. rm
   remove (파일 삭제)

4. mkdir  
   make directory(작업목록 생성)

5. rmdir  
   remove directory(작업목록 삭제)

6. touch  
   파일생성

7. cat
   파일의 내용 출력

## Git

1. init  
   git 생성
2. add <파일명>  
   staging area로 이동
3. commit -m <메세지>  
   Repository로 이동
4. push <원격저장소><브랜치>  
   원격(GitHub)으로 이동
5. pull <원격저장소><브랜치>  
   원격에서 로컬로 복사
6. clone <원격저장소><브랜치>  
   원격에서 로컬로 복제
7. status  
   Staging Area의 상태
8. log  
   repository의 상태
