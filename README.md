# GitHubTest
깃허브 연습, README 마크다운 문법

연습중

줄 바꿈은 개행두번이나 띄어쓰기 두번으로 구분  


한 줄 다 작성하고 다음줄로 개행하지 않으면 띄어쓰기 기준으로 마지막 단어 preview에 보이지 않음(한 줄 개행은 한 단락임을 의미하므로 목록이나 인용, 소스코드만 해당 하는듯)

---

### 제목
#개수로 제목 크기 결정, 한 줄 개행으로 제목아래부터 내용작성

---

### 줄 추가
--- or ***

---

목록: 순서있는 목록은 번호 붙여서 목록 만들고, 번호 순서안맞아도 순서대로 나타나게 해줌, 탭으로 들여쓰기 하면 항목 표시 알아서 구분해줌

순서 없는 목록은 - or * 붙여서 항목 표시

1. 첫 번째
2. 두 번쨰
3. 세 번째

- 첫 번째
- 두 번쨰
- 세 번쨰

---

### 텍스트 강조
굵게: 앞뒤로 **감싸기 **굵게**

기울임체: 앞뒤로 *감싸기 *기울임체*


굵은 기울임체: 앞뒤로 ***감싸기 ***굵은 기울임체***

취소선: 앞뒤로~~ 감싸기 ~~취소선~~

---

### 인용
인용문 삽입: 첫 번째 앞 줄에 > 추가, 인용문 안에 인용문은 >>추가, 인용문마무리는 두 줄 개행

>인용문
>>인용문

---

### 소스 코드
소스 코드: 대문자 활성화 시켜서 1왼편에 있는 그레이브 키 사용, ```로 소스 코드 감싸기(그레이브 뒤에 언어를 지정하면 해당 언어에 맞는 형태로 표시됨


```JAVA
class Test {
  pubic static void main(String[] args) {
    System.out.println("test");
    
    return;
  }
}
```

---

### 링크
- 링크 주소를 <>로 감싸면  화면에 주소가 그대로 나타나고 해당 주소로 이동

<https://www.naver.com/>
- 텍스트를 통해 이동하려면 []안에 원하는 텍스트 넣고()안에 링크 주소 삽입 []()형태

[네이버](https://www.naver.com/)

- 링크의 텍스트를 임의로 넣고 커서를 올렸을 때 부가설명을 넣으려면 [링크 텍스트](링크 주소, "부가 설명")형태로 입력

[네이버](https://www.naver.com/, "초록창")

---

### 이미지
- 웹 이미지 불러올 경우 ![대체 텍스트](이미지 주소) 

대체 텍스트는 이미지를 나타낼 수 없는 상황이나 화면 낭독기에서 이미지를 소리로 설명할 수 있도록 삽입하는 텍스트임

- 웹 이미지가 아니라면 깃허브 저장소에 직접 올린 다음 그 경로를 README파일에서 지정하면 됨 
 
![대체 텍스트](./깃허브 내에서 이미지들어있는 디렉토리/이미지명.확장자)

---

























