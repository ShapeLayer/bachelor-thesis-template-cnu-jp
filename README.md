# 전남대학교 인문대학 일어일문학과 학사학위논문 Typst 템플릿

전남대학교 인문대학 일어일문학과의 학사학위논문 서식 Typst 템플릿입니다.

## Getting Started

### 기본 설정

`main.typ` 파일에서 다음 정보를 수정하세요:

```typst

#show: bachelor-thesis-style.with(
  title: "논문 제목",
  subtitle: none,
  author: "학생 이름",
  supervisor: "지도교수 이름",
  pubdate: (
    year: [2026],
    month: [12]
  ),
  coach-date: (
    first: (year: [2026], month: [9], day: [15]),
    second: (year: [2026], month: [10], day: [20]),
    third: (year: [2026], month: [11], day: [25]),
  )
)
```

### 논문 작성

기본 설정 이후 `lorem()` 부분을 실제 논문 내용으로 대체하세요:

```typst
= 첫 번째 장

논문 내용을 작성합니다.

== 첫 번째 절

더 자세한 내용을 작성할 수 있습니다.
```

## 폰트 설정

> [!NOTE]
> 서식에서 권장하는 신명조와 견고딕은 한컴오피스 제품군에서만 사용할 수 있도록 라이선스되어있습니다. 
> 따라서 이 템플릿에서는 Noto Serif CJK KR과 Noto Sans CJK KR을 사용하도록 설정되어있습니다.

## 참고문헌

`refs.bib` 파일에 BibTeX 형식으로 참고문헌을 추가하세요.
