<p align="center"><a href = "https://www.acmicpc.net"><img src="https://upload.acmicpc.net/23278560-e2ca-4e90-a663-9386e5049860/boj.png" width="500"></a></p>

## 2018-07-25

* Java에서 런타임 에러와 메모리 초과를 조금 더 정확하게 구분함.
  * 기존 채점: `int[] a = new int[100000000];` (런타임 에러)
  * 바뀐 채점: `int[] a = new int[100000000];` (메모리 초과)

## 2018-07-24

* 맞은 사람 페이지의 속도를 실수로 조금 개선함. 의도 하지 않았지만, 아래 업데이트를 구현하다가 구현해버림.
* 전체 채점 문제의 맞은 사람 페이지에서 0개 이상의 데이터를 맞은 제출을 보여주게 업데이트 함. (숏코딩 탭 포함)
   * [15624번](https://beta2.acmicpc.net/problem/15624)의 경우 문제 페이지 하단 채점 탭에 201개 이상의 데이터를 맞춰야 "맞았습니다!!"를 받는다고 되어있음
   * 기존 방식: 201개 이상 맞은 사람만 맞은 사람/숏코딩 탭에 보여줬음
   * 바뀐 방식: 0개 초과 맞은 사람을 모두 [맞은 사람](https://www.acmicpc.net/problem/status/15624)/[숏코딩](https://www.acmicpc.net/short/status/15624) 탭에 보여줌
  

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
