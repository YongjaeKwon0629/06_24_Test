# 📘 AI 학습 정리

## 1. ABout Github, Markdown, Colab
- [GitHub 사용법](#github-사용법)
- [Markdown 문법](#markdown-문법)  
- [Colab 기초](#colab-기초)

  ## GitHub 사용법

### ✅ GitHub 계정 만드는 순서 (2025년 기준)

1. **웹 브라우저 열기**
   크롬(Chrome), 엣지(Edge), 사파리(Safari) 중 편한 걸 사용하세요.

2. **GitHub 웹사이트 접속**
   주소창에 아래 주소를 입력하고 Enter 누르세요: https://github.com

3. **회원가입 시작하기**
   화면 오른쪽 위 또는 중간에 있는 Sign up 버튼 클릭

4. **이메일 주소 입력**
   평소 자주 사용하는 이메일을 입력

5. **비밀번호 만들기**
   영어 대문자, 소문자, 숫자, 특수문자를 섞어 안전하게!
   예시: Git1234!hub

6. **사용자 이름(Username) 정하기**
   나만의 고유한 이름을 지어요 (다른 사람이 쓰고 있으면 불가)
   - 예시: jetsunmom, sungsookjang66 등
   - 영어, 숫자, 하이픈(-) 가능 (띄어쓰기 ❌)

### ✅ Repository 만들기 순서

1. **GitHub에 로그인 후 New Repository 클릭**
2. ![new](https://github.com/user-attachments/assets/3481a680-f677-403b-be8c-1fe59d5aa7cb)

3. **Repository 이름 입력**
4. **Public/Private 선택**
5. **README.md 파일 생성 체크**
6. **Create repository 버튼 클릭**
   
![create_repository](https://github.com/user-attachments/assets/8c2eb16b-8dfc-465a-88cd-d35770d12df0)

## Markdown 문법

Markdown은 README, 문서화, 블로그 등에서 널리 사용되는 경량 마크업 언어입니다. GitHub에서는 Markdown을 사용해 가독성 좋고 구조화된 문서를 작성할 수 있습니다.

### 1. 제목 (Headings)
markdown
복사
편집
# H1 제목
## H2 제목
### H3 제목
#### H4 제목
##### H5 제목
###### H6 제목
# 개수가 많을수록 제목 수준이 낮아짐 (H1~H6).

H1은 일반적으로 문서의 제목으로, README에서는 보통 프로젝트 이름.

### 2. 문단과 줄바꿈
- 문단 사이에는 한 줄을 비워야 새로운 문단으로 인식됩니다.

- 줄바꿈은 문장 끝에 스페이스 2개 + 엔터 필요.

```markdown
이것은 첫 번째 문장입니다.  
이것은 같은 문단에서 줄바꿈된 문장입니다.

이것은 새로운 문단입니다.
```
### 3. 강조 (Bold / Italic / 취소선)
```markdown
**굵게** 또는 __굵게__
*기울임* 또는 _기울임_
~~취소선~~
예시: 강조, 기울임, 삭제된 텍스트
```

### 4. 목록 (Lists)
- 순서 없는 목록
- 
```markdown
- 항목 1
- 항목 2
  - 하위 항목
    - 더 하위 항목
* 별표도 사용 가능
```

- 순서 있는 목록

```markdown

1. 첫 번째
2. 두 번째
3. 세 번째
```

### 5. 링크와 이미지
- 링크
```markdown
[텍스트](https://example.com)
```
- 이미지
  
```markdown
복사
편집
![대체 텍스트](https://example.com/image.png)
```
💡 GitHub 내 이미지 경로: ./이미지폴더/파일명.png

### 6. 코드 및 코드블록
인라인 코드

```markdown
`코드`
```
예시: ```console.log("Hello World")```

코드 블록 (언어 지정 가능)
<pre> ```python def hello(): print("Hello Markdown") ``` </pre>

### 7. 인용문 (Blockquote)

```markdown

> 이것은 인용문입니다.
>> 중첩된 인용문도 가능합니다.
```

### 8. 수평선 (구분선)

```markdown
---
***
___
```

### 9. 체크리스트 (To-do list)

```markdown
- [x] 완료된 작업
- [ ] 미완료 작업
```

![image](https://github.com/user-attachments/assets/a73e6196-3b06-4e6f-b6b4-287dfc83b521)


### 10. 표 (Table)

```markdown

| 이름  | 역할     | 비고       |
|-------|----------|------------|
| 홍길동 | 개발자   | 프론트엔드 |
| 김철수 | 디자이너 | UI/UX      |
```
- 예시:

![image](https://github.com/user-attachments/assets/635e6e54-181b-40f0-aa79-ed07f910129e)

✅ 기타 팁
- README.md는 프로젝트 소개, 설치 방법, 사용법, 기여 방법 등을 작성하는 문서입니다.

- GitHub에서는 .md 확장자를 가진 파일을 자동으로 렌더링합니다.

- 직접 확인은 Markdown Live Preview 또는 GitHub에서 브랜치 푸시 후 확인 가능.

## Colab 기초  
(여기에 Colab 내용 작성)

![Colab_06_24_1](https://github.com/user-attachments/assets/2868e474-e7a2-4dcc-b839-62e9e54fe597)

![Colab_06_24_2](https://github.com/user-attachments/assets/6cb994b1-89fc-47ec-a850-b9c93ecf6cf0)

![Colab_06_24_3](https://github.com/user-attachments/assets/05981dbb-0329-4e78-856f-ab14b5ad654b)

![Colab_06_24_4](https://github.com/user-attachments/assets/7dc8a851-b51b-41e4-9413-94aaba4f33f0)
