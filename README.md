# system-design-interview-book-study
`가상 면접 사례로 배우는 대규모 시스템 설계 기초` 책 스터디를 위한 레포지토리입니다.

## 발표 자료
| 진행일자 | 챕터                                                                                 | 이슈 링크                                                                       |
|---|------------------------------------------------------------------------------------|:----------------------------------------------------------------------------|
|25/05/17,19| [1장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/01장). 사용자 수에 따른 규모 확장성        | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/3) |
|25/05/19| [2장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/02장). 개략적인 규모 추정              | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/4) |
|25/05/22| [3장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/03장). 시스템 설계 면접 공략법           | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/5) |
|25/05/26| [4장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/04장). 처리율 제한 장치의 설계           | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/6) |
|25/05/29| [5장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/05장). 안정 해시 설계                | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/7) |
|25/06/02| [6장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/06장). 키-값 저장소 설계              | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/8) |
|25/06/07| [7장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/07장). 분산 시스템을 위한 유일 ID 생성기 설계 | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/9) |
|25/06/07| [8장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/08장). URL 단축기 설계              | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/10) |
|25/06/09| [9장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/09장). 웹 크롤러 설계                | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/11) |
|25/06/12| [10장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/10장). 알림 시스템 설계              | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/12) |
|25/06/17| [11장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/11장). 뉴스 피드 시스템 설계           | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/13) |
|25/06/19| [12장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/12장). 채팅 시스템 설계              | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/14) |
|25/06/23| [13장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/13장). 검색어 자동완성 시스템           | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/15) |
|25/06/26,30| [14장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/14장). 유튜브 설계                 | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/16) |
|25/07/03| [15장](https://github.com/HI-dle/system-design-interview-book-study/tree/main/15장). 구글 드라이브 설계             | [링크](https://github.com/HI-dle/system-design-interview-book-study/issues/17) |

## 📜 진행방식
- [책 링크](http://www.yes24.com/Product/Goods/102819435)
  - [참고: 부록 링크](https://github.com/alex-xu-system/bytebytego/blob/main/system_design_links.md) 
- 일정 : 2025. 05. 14(수) ~ 2025.07.03(목) 
  - 매주 월/목(첫 주만 수/토 로 진행합니다.) 오후 2시, 총 8주(16회)
- 인원: 5명
- 16장 (마지막 장)은 제외합니다.

### 읽기
- 월/목 오후 2시 함께 정해진 분량을 읽습니다.
- 읽은 내용 중 질문 혹은 중요하다고 생각되는 부분을 해당하는 장의 Issue 에 Comment 를 바로 남겨주세요.

### 발표
- 월/목 읽기 시간이 끝난 후 발표를 진행합니다.
- 발표 내용: 지난 타임에서 읽은 부분으로 진행합니다.
- 발표 담당자 지정: 지난 타임에서 읽은 부분을 적절히 나누어 사다리 타기로 진행합니다.
- 발표자는 본인 파트에 해당하는 Issue 에 달린 Comment 관련 내용도 함께 준비합니다.

## 📚 Github Convention

#### 발표 자료 
  - 파일명(파일 위치 포함)은 아래와 같이 해주세요.
    ```
    0X장/[0X장]_{제목}{(부가옵션)_0X-0X_소제목자유}_{이름}.md
    ```

#### issue 
  - 아래와 같이 제목을 작성해주세요.
    ```
    [0X장]_{제목}
    ```
  - Issue Comment 는 제일 첫 줄에 관련 페이지 위치를 작성해주세요.
    ```
    p.123 n문단
    ~문장이 이해가 안 됩니다.
    ```
    
#### commit message 
  - 아래와 같이 작성해주세요.
    ```
    [#이슈번호]{파일이름(.md 제외)}
    ```

## 👨‍👩‍👧‍👦 회고

- 1주일 동안 책을 읽으면서 느낀점, 발표를 보고 느낀점 들을 자유롭게 이야기 해주시면 됩니다.
- 자유롭게 각자 하고 싶은 말을 하면 되니 부담 가지실 필요는 없습니다.

### 팀원 정보
<table>
    <tr>
        <td align="center">
            <a href="https://github.com/hyezuu"><img  width="100px" src="https://avatars.githubusercontent.com/u/147456219?v=4" /></a>
        </td>
        <td align="center">
            <a href="https://github.com/je-pa"><img  width="100px" src="https://avatars.githubusercontent.com/u/76720692?v=4" /></a>
        </td>
        <td align="center">
            <a href="https://github.com/cchoijjinyoung"><img  width="100px" src="https://avatars.githubusercontent.com/u/68311264?v=4" /></a>
        </td>
        <td align="center">
            <a href="https://github.com/hanjihoon03"><img  width="100px" src="https://avatars.githubusercontent.com/u/163777923?v=4" /></a>
        </td>
        <td align="center">
            <a href="https://github.com/HanaHww2"><img  width="100px" src="https://avatars.githubusercontent.com/u/62924471?v=4" /></a>
        </td>
    </tr>
    <tr>
        <td align="center">강혜주</td>
        <td align="center">박지은</td>
        <td align="center">최진영</td>
        <td align="center">한지훈</td>
        <td align="center">황하온</td>
    </tr>
</table>
