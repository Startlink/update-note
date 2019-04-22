<p align="center"><a href = "https://www.acmicpc.net"><img src="https://upload.acmicpc.net/23278560-e2ca-4e90-a663-9386e5049860/boj.png" width="500"></a></p>

## 2019-04-23

* [링크 설정](https://www.acmicpc.net/setting/connect)이 추가됨
* [테마 설정](https://www.acmicpc.net/setting/theme)에서 solarized dark와 solarized light를 선택했을 때, 올바르게 적용되지 않던 버그 수정
* 그룹 이름 및 설명에서 `&`와 같은 글자가 자꾸 `&amp;`로 escape되는 버그 수정
* 소스 코드 줄 바꿈을 `\r\n`에서 `\n`으로 변경

## 2018-11-26

* 새로운 언어 Kotlin (Native), Java 11 추가 ([공지](https://www.acmicpc.net/board/view/31120))

## 2018-11-20

* 문제집 북마크 추가

## 2018-11-19

* 비공개 문제집
* 문제집 추가 UI 변경

## 2018-11-06

* 문제집 구분 세분화 (인증/공개/비공개)

## 2018-10-23

* 예제의 공백을 하이라이트 할 수 있음 ([공지](https://www.acmicpc.net/board/view/30297))

## 2018-09-17

* 소스 코드를 공유할 수 있음 ([공지](https://www.acmicpc.net/board/view/29058))

## 2018-09-15

* 맞은 사람/숏코딩 페이지 업데이트
  * 언어를 선택하면, 좌측에 언어에 해당하는 통계를 보여줌 (기존: 언어 선택과 무관하게 전체 통계를 보여줌)
  * 맞은 사람 페이지에 **시도**를 추가 (시도: 첫 번째 맞았습니다!!를 받기 전까지 제출한 횟수 + 1)

## 2018-09-14

* 일정 시간 동안 제출을 너무 많이 하면, 제출할 때 reCAPTCHA 검사를 수행함

## 2018-08-17

* 채점 결과 맞춤법 수정
  * 채점 준비중 &rarr; 채점 준비 중
  * 채점중 &rarr; 채점 중

## 2018-08-10

* [최근 제출된 문제](https://www.acmicpc.net/problem/recent/submit), [최근 풀린 문제](https://www.acmicpc.net/problem/recent/accepted)가 새로 생김

## 2018-07-31

* [Spotboard](https://github.com/spotboard/spotboard)를 네이티브(?)로 지원함. 기존에는 https://\*.acmicpc.net 으로 지원했었음.
  * 예전 주소: https://ucpc2018.acmicpc.net
  * 바뀐 주소: https://www.acmicpc.net/contest/spotboard/314
  * 주소가 길어졌기 때문에, http://boj.kr/c/ucpc2018, http://boj.kr/c/ucpc2018-open 과 같은 짧은 주소도 제공

## 2018-07-25

* Java에서 런타임 에러와 메모리 초과를 조금 더 정확하게 구분함.
  * 기존 채점: `int[] a = new int[100000000];` (런타임 에러)
  * 바뀐 채점: `int[] a = new int[100000000];` (메모리 초과)
* 유저 정보 페이지에서 [vs 기능](https://www.acmicpc.net/vs/baekjoon/koosaga)이 올바르게 동작하지 않던 버그를 수정

## 2018-07-24

* 맞은 사람 페이지의 속도를 실수로 조금 개선함. 의도 하지 않았지만, 아래 업데이트를 구현하다가 구현해버림.
* 전체 채점 문제의 맞은 사람 페이지에서 0개 이상의 데이터를 맞은 제출을 보여주게 업데이트 함. (숏코딩 탭 포함)
   * [15624번](https://beta2.acmicpc.net/problem/15624)의 경우 문제 페이지 하단 채점 탭에 201개 이상의 데이터를 맞춰야 "맞았습니다!!"를 받는다고 되어있음
   * 기존 방식: 201개 이상 맞은 사람만 맞은 사람/숏코딩 탭에 보여줬음
   * 바뀐 방식: 0개 초과 맞은 사람을 모두 [맞은 사람](https://www.acmicpc.net/problem/status/15624)/[숏코딩](https://www.acmicpc.net/short/status/15624) 탭에 보여줌
* 주소의 맨 뒤에 `/`가 오지 못하게 수정
  

## 2018-07-23

* [문제집 문제보는 페이지](https://www.acmicpc.net/workbook/view/1152)에서 맞은 사람 링크가 올바르지 않던 버그 수정
* 예제에 대한 설명을 힌트에 몰아서 보여주지 않고, 예제별 설명을 지원함. [예전 방식](https://www.acmicpc.net/problem/12872), [새로운 방식 1](https://www.acmicpc.net/problem/15928), [새로운 방식 2](https://beta2.acmicpc.net/problem/15929)
* [서버 상태](http://status.acmicpc.net/) 페이지를 더 이상 사용하지 않음. 다른 방식을 사용할 예정.
* 문제집 클리어를 삭제. 다시 새로운 방식으로 업데이트 할 예정.

## 2018-07-22

* 시간 표시를 MS에서 ms로 올바르게 수정함 (520 MS -> 520 ms)

## 2018-07-21

* [Pusher](https://pusher.com/) 연결을 http에서 https로 변경

## 2018-07-20

* [기본 언어 설정](https://www.acmicpc.net/setting/language) 페이지를 라디오 버튼에서 Select box로 변경
* 사이트 하단에 [업데이트 노트](https://github.com/Startlink/update-note/blob/master/boj.md) 링크 추가


## 이전 내용

2018-03-19까지 내용은 [BOJ 뉴스](https://www.acmicpc.net/news), 그 이후 2018-07-20까지 기록은 [BOJ 업데이트 게시판](https://www.acmicpc.net/board/list/update) 에서 확인할 수 있음
