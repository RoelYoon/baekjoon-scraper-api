# baekjoon-api
## solved.ac & acmicpc.net api
  
### installing requirements
```
pip install baekjoon
```
  
  How to use [boj]
  ```Python
  from baekjoon import boj
  
  user = "smartwe"
  
  boj.get_status_message(user) #사용자 이름
  
  boj.get_rank(user) #백준 랭크(순위)
  
  boj.get_correct_qs(user) #맞은 문제들
  
  boj.get_correct_q(user) #맞은 문제의 개수
  
  boj.get_unsolved_qs(user) #시도했지만 맞지 못한 문제들
  
  boj.get_unsolved_q(user) #시도했지만 맞지 못한 문제의 개수
  
  boj.get_submit_time(user) #제출 개수
  ```
  
  How to use [solved.ac]
  ```Python
  from baekjoon import solvedac
  
  user = "smartwe"
  
  solvedac.get_tier(user) #티어
  
  solvedac.get_ac_rating(user) #AC RATING
  
  solvedac.get_exp(user) #EXP
  
  solvedac.get_rank(user) #solved.ac 기준 랭크
  ```
