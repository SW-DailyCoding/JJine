![image](https://user-images.githubusercontent.com/51090557/98557783-f8175300-22e7-11eb-92fc-72ba51b6b8d7.png)

## 문서 객체 모델(DOM : Document Object Model)

- **DOM**
- 웹 문서의 모든 요소를 자바스크립트를 이용하여 조작할 수 있도록 객체를 사용해 문서를 해석하는 방법
- 동일한 문서를 표현하고, 저장하고, 조작하는 방법을 제공
- 웹 페이지의 객체 지향 표현이며, 자바스크립트와 같은 스크립팅 언어를 이용해 DOM 을 수정 가능
- **DOM**의 트리
- DOM은 웹 문서의 요소를 부모 요소와 자식 요소를 구분
- 웹 문서에 있는 요소나 속성을 나타내는 노드(Node), 노드와 노드 사이 연결 관계를 나타내는 가지로 표현
- 웹 문서 요소를 다음과 같이 표현

    웹 문서의 태그는 **요소(Element)** 노드 표현
    - 태그가 품고 있는 텍스트는 해당 요소 노드(태그)의 자식 노드인 텍스트(Text) 노드로 표현
    - 태그의 속성은 모두 해당 요소 노드(태그)의 자식 노드인 속성(Attribute) 노드로 표현
    - 주석은 주석(Comment) 노드로 표현

## DOM 요소에 접근하기

- 자바스크립트로 DOM 요소에 접근할 수 있도록 주로 선택자(Selector)를 사용
![image](https://user-images.githubusercontent.com/51090557/98557630-cb633b80-22e7-11eb-9a62-cf0914945a6d.png)

## 웹 요소의 태그 속성 가져와서 수정하기
- HTML 태그 속성을 가져오거나 수정하기
![image](https://user-images.githubusercontent.com/51090557/98557703-e03fcf00-22e7-11eb-87e7-53df06731d66.png)

