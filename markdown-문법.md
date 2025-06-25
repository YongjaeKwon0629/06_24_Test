## Markdown 문법

Markdown은 README, 문서화, 블로그 등에서 널리 사용되는 경량 마크업 언어입니다. GitHub에서는 Markdown을 사용해 가독성 좋고 구조화된 문서를 작성할 수 있습니다.

---

### 1. 제목 (Headings)
```
markdown
# H1 제목
## H2 제목
### H3 제목
#### H4 제목
##### H5 제목
###### H6 제목
```

- # 개수가 많을수록 제목 수준이 낮아짐 (H1~H6).

- H1은 일반적으로 문서의 제목으로, README에서는 보통 프로젝트 이름.
  
---

### 2. 문단과 줄바꿈
- 문단 사이에는 한 줄을 비워야 새로운 문단으로 인식됩니다.

- 줄바꿈은 문장 끝에 스페이스 2개 + 엔터 필요.

```markdown
이것은 첫 번째 문장입니다.  
이것은 같은 문단에서 줄바꿈된 문장입니다.

이것은 새로운 문단입니다.
```

---

### 3. 강조 (Bold / Italic / 취소선)
```markdown
**굵게** 또는 __굵게__
*기울임* 또는 _기울임_
~~취소선~~
예시: 강조, 기울임, 삭제된 텍스트
```

---

### 4. 목록 (Lists)
- 순서 없는 목록
 
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

---

### 5. 링크와 이미지
- 링크
```markdown
[텍스트](https://example.com)
```
- 이미지
  
```markdown
![대체 텍스트](https://example.com/image.png)
```
💡 GitHub 내 이미지 경로: ./이미지폴더/파일명.png

---

### 6. 코드 및 코드블록
인라인 코드

```markdown
`코드`
```
예시: ```console.log("Hello World")```

코드 블록 (언어 지정 가능)
<pre> ```python def hello(): print("Hello Markdown") ``` </pre>

---

### 7. 인용문 (Blockquote)

```markdown

> 이것은 인용문입니다.
>> 중첩된 인용문도 가능합니다.
```

---

### 8. 수평선 (구분선)

```markdown
---
***
___
```

---

### 9. 체크리스트 (To-do list)

```markdown
- [x] 완료된 작업
- [ ] 미완료 작업
```

![image](https://github.com/user-attachments/assets/a73e6196-3b06-4e6f-b6b4-287dfc83b521)

---

### 10. 표 (Table)

```markdown

| 이름  | 역할     | 비고       |
|-------|----------|------------|
| 홍길동 | 개발자   | 프론트엔드 |
| 김철수 | 디자이너 | UI/UX      |
```
- 예시:

![image](https://github.com/user-attachments/assets/635e6e54-181b-40f0-aa79-ed07f910129e)
