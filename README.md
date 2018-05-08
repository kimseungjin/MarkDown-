# MarkDown
MarkDown에 대해서 알아 보자.

## MarkDown이란?

Markdown은 텍스트 기반의 마크업언어로 2004년 존그루버에 의해 만들어졌으며 쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능하다. 특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여 웹에서도 보다 빠르게 컨텐츠를 작성하고 보다 직관적으로 인식할 수 있다. 마크다운이 최근 각광받기 시작한 이유는 깃헙(https://github.com) 덕분이다. 깃헙의 저장소Repository에 관한 정보를 기록하는 README.md는 깃헙을 사용하는 사람이라면 누구나 가장 먼저 접하게 되는 마크다운 문서였다. 마크다운을 통해서 설치방법, 소스코드 설명, 이슈 등을 간단하게 기록하고 가독성을 높일 수 있다는 강점이 부각되면서 점점 여러 곳으로 퍼져가게 된다.


## MarkDown Syntax

### 제목(Header)
  * `<h1>` 부터 `<h6>` 까지 제목을 표현할 수 있다.

  #### <사용법>
  
  ```
  # 제목
  ## 제목
  ### 제목
  #### 제목
  ##### 제목
  ###### 제목
  ```

  #### <적용>
  
  # 제목
  ## 제목
  ### 제목
  #### 제목
  ##### 제목
  ###### 제목




### 강조(Emphasis)

#### <사용법>

```
이텔릭체는 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용하세요.
두껍게는 **별표(asterisks)** 혹은 __언더바(underscore)__를 사용하세요.
**_이텔릭체_와 두껍게**를 같이 사용할 수 있습니다.
취소선은 ~~물결표시(tilde)~~를 사용하세요.
<u>밑줄</u>은 `<u></u>`를 사용하세요.
```

#### <적용>

이텔릭체는 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용하세요.
두껍게는 **별표(asterisks)** 혹은 __언더바(underscore)__를 사용하세요.
**_이텔릭체_와 두껍게**를 같이 사용할 수 있습니다.
취소선은 ~~물결표시(tilde)~~를 사용하세요.
<u>밑줄</u>은 `<u></u>`를 사용하세요.




### 목록(List)
 * `<ol>`, `<ul>` 목록 태그로 변환됩니다.
 
 #### <사용법>
 ```
 1. 순서가 필요한 목록
 1. 순서가 필요한 목록
  - 순서가 필요하지 않은 목록(서브) 
  - 순서가 필요하지 않은 목록(서브) 
 1. 순서가 필요한 목록
  1. 순서가 필요한 목록(서브)
  1. 순서가 필요한 목록(서브)
 1. 순서가 필요한 목록

 - 순서가 필요하지 않은 목록에 사용 가능한 기호
  - 대쉬(hyphen)
  * 별표(asterisks)
  + 더하기(plus sign)
 ```

 #### <적용>
  1. 순서가 필요한 목록
  1. 순서가 필요한 목록
  - 순서가 필요하지 않은 목록(서브) 
  - 순서가 필요하지 않은 목록(서브) 
  1. 순서가 필요한 목록
  1. 순서가 필요한 목록(서브)
  1. 순서가 필요한 목록(서브)
  1. 순서가 필요한 목록

  - 순서가 필요하지 않은 목록에 사용 가능한 기호
  - 대쉬(hyphen)
  * 별표(asterisks)
  + 더하기(plus sign)
  
  
  
### 링크(Link)
 * `<a>`로 변환된다.

 #### <사용법>
 ```
 [GOOGLE](https://google.com)
 [NAVER](https://naver.com "링크 설명(title)을 작성하세요.")
 [상대적 참조](../users/login12)
 ```
 
  #### <적용>
 [GOOGLE](https://google.com)
 [NAVER](https://naver.com "링크 설명(title)을 작성하세요.")
 [상대적 참조](../users/login12)
 
 
 
 #### 이미지(Images)
 
 * `<img>`로 변환된다. 링크와 비슷하지만 `!`가 붙는다.
 
 
  #### <사용법>
 ```
 ![대체 텍스트(alternative text)를 입력하세요!](https://devimages-cdn.apple.com/assets/elements/icons/swift/swift-64x64_2x.png "링크 설명(title)을 작성하세요.")
 
 ```
 
  #### <적용>
  
  
  ![대체 텍스트(alternative text)를 입력하세요!](https://devimages-cdn.apple.com/assets/elements/icons/swift/swift-64x64_2x.png "링크설명(title)을 작성하세요.")




 #### 이미지에 링크
 
  #### <사용법>
 ```
 [!Swift](https://devimages-cdn.apple.com/assets/elements/icons/swift/swift-64x64_2x.png "링크 설명(title)을 작성하세요.")
 [![Vue](/images/vue.png)](https://kr.vuejs.org/)
 ```

[!Vue(/images/vue.png)](https://kr.vuejs.org/)

