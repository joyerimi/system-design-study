# 대규모 시스템 설계 기초 스터디

<div align="center">

[가상 면접 사례로 배우는 대규모 시스템 설계 기초](http://www.yes24.com/Product/Goods/102819435)
 
<img src="https://github.com/user-attachments/assets/2fbaf0bb-45de-46c0-baa7-038eec3497f5" height=600, width=450>
</div>

<div align="center">

## 스터디원 소개 💁🏻‍♂️
 
| **조예림** | **이권민** | **김용범** | **소태호** |
| :------: |  :------: | :------: | :------: |
| [<img src="https://avatars.githubusercontent.com/u/96174711?v=4" height=150 width=150> <br/> @joyerimi](https://github.com/joyerimi) | [<img src="https://avatars.githubusercontent.com/u/101376985?v=4" height=150 width=150> <br/> @dradra0905](https://github.com/dradra0905) | [<img src="https://avatars.githubusercontent.com/u/88239689?v=4" height=150 width=150> <br/> @Bumnote](https://github.com/Bumnote) | [<img src="https://avatars.githubusercontent.com/u/91146046?v=4" height=150 width=150> <br/> @SoTaeHo](https://github.com/SoTaeHo) |
---

</div>

* 기간: 2025.06.11(수) \~ 
* 시간 및 장소: 매주 수요일 오후 6시, 오프라인 (역삼역 인근)

## 목적

1. 단순 요약이 아니라 **왜 이 기술이 필요한가?** 를 중심으로 이해
2. **요구사항·제약·병목**에 따라 설계하고 설명하는 역량 강화
3. 내가 만드는 서비스(예: 찍을지도)에 적용해보며 **체화**

---

## 진행 방식

* 매주 한 챕터씩
* 각자 작성 내용:

  * 핵심 개념 요약
  * 예상 면접 질문 + 답변 (선택)
  * 실제 서비스에 적용해보는 설계 예시 (선택)
* 발표자는 매주 당일 랜덤 지정
* 발표자는 발표 후 공통 정리(`README.md`) 작성
* PR로 개인 정리 제출, 상호 리뷰
* 질문·토론은 GitHub Issue 활용

---

## 주간 스터디 사이클

* **발표 전**: 해당 장에 대한 개인 정리 PR 제출
* **수요일**: 발표 진행(발표자는 직전 사다리 타기로 랜덤 선정)
* **목요일\~금요일**: 다른 스터디원의 PR 읽고 코멘트 남기기
* **토요일\~화요일**: 받은 코멘트에 답변하며 토론 진행
* **다음 발표 준비**: 동시에 각자 다음 장 학습 및 정리하여 PR 작성

---

## 디렉토리 구조

```
SYSTEM-DESIGN-STUDY/
├── chap01/
│   └── members/
│       ├── 김용범.md
│       ├── 소태호.md
│       ├── 이권민.md
│       └── 조예림.md
├── chap02/
│   └── ...
└── README.md
```

* 각자 한 파일 안에 개념 정리, 면접 질문, 서비스 적용 정리를 모두 작성

---

## 학습 내용 정리

| 주차      | Chapter                      | 발표자                                     | 발표 자료                                                               |
| ------- | ---------------------------- | --------------------------------------- | ------------------------------------------------------------------- |
| 1주차     | 01장. 사용자 수에 따른 규모 확장성        | [joyerimi](https://github.com/joyerimi) | [자료](https://github.com/joyerimi/system-design-study/pull/4)        |
| 2주차     | 02장. 개략적인 규모 추정              | [SoTaeHo](https://github.com/SoTaeHo)   | [자료](https://github.com/joyerimi/system-design-study/pull/9)        |
| 2주차(추가) | **캐시**                       | [Bumnote](https://github.com/Bumnote)   | [자료](https://github.com/joyerimi/system-design-study/pull/8)        |
| 3주차     | 03장. 시스템 설계 면접 공략법           | [joyerimi](https://github.com/joyerimi) | [자료](https://github.com/joyerimi/system-design-study/pull/13)       |
| 3주차(추가) | **인덱스**                      | [joyerimi](https://github.com/joyerimi) | [자료](https://github.com/joyerimi/system-design-study/pull/13)       |
| 4주차     | 04장. 처리율 제한 장치의 설계           | [SoTaeHo](https://github.com/SoTaeHo)   | [자료](https://github.com/joyerimi/system-design-study/pull/20)       |
| 5주차     | 05장. 안정 해시 설계                | [Bumnote](https://github.com/Bumnote)   | [자료](https://github.com/joyerimi/system-design-study/pull/23/files) |
| 6주차     | 06장. 키-값 저장소 설계              | [SoTaeHo](https://github.com/SoTaeHo)   | [자료](https://github.com/joyerimi/system-design-study/pull/27)       |
| 7주차     | 07장. 분산 시스템을 위한 유일 ID 생성기 설계 | [SoTaeHo](https://github.com/SoTaeHo)   | [자료](https://github.com/joyerimi/system-design-study/pull/27)       |
| 8주차     | 08장. URL 단축기 설계              | [발표자]()                                 | [자료]()                                                              |
| 9주차     | 09장. 웹 크롤러 설계                | [발표자]()                                 | [자료]()                                                              |
| 10주차    | 10장. 알림 시스템 설계               | [발표자]()                                 | [자료]()                                                              |
| 11주차    | 11장. 뉴스 피드 시스템 설계            | [발표자]()                                 | [자료]()                                                              |
| 12주차    | 12장. 채팅 시스템 설계               | [발표자]()                                 | [자료]()                                                              |
| 13주차    | 13장. 검색어 자동완성 설계             | [발표자]()                                 | [자료]()                                                              |
| 14주차    | 14장. 유튜브 설계                  | [발표자]()                                 | [자료]()                                                              |
| 15주차    | 15장. 구글 드라이브 설계              | [발표자]()                                 | [자료]()                                                              |
| 16주차    | 16장. 배움은 계속된다                | [발표자]()                                 | [자료]()                                                              |

