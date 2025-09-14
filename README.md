## :wolf: (총을 쏘고 싶었던) 빨간 모자와 늑대 게임


### 🖊️Role

- 게임 스토리 기획
- Embedded C 코딩

### 프로젝트 요약

<img src="History/img/ppt_1.png" width="1000">|
--|

<img src="History/img/ppt_2.png" width="1000">
--|

|<img src="/History/img/ppt_3.png" width=1000>|
--|


|<img src="/History/img/ppt_4.png" width=1000>|
--|

> ### Game Rule

1. 정은지_실핼파일1.bin 파일을 TERA TERM에 다운로드한다.
2. 게임 제한 시간은 50초이며 LCD 화면에 감소 시간이 나타난다. 
3. 빨간모자는 키조작으로 움직일 수 있다. (KEY0, KEY1을 활용해도 좌우로 움직일 수 있다.)
4. 과일은 3초마다 등장하며 과일을 쪼개면 할머니의 치료약(GHP)을 만들 수 있다.
5. GHP =과일*3/5, GHP 개수에 따라 엔딩이 달라진다. 
> (즉, 과일: 1개 -> GHP: 0, 과일: 2개 -> GHP: 1, 과일: 5개 -> GHP: 3)

![Demo GIF](https://github.com/2735C/KDT_ARM/blob/main/History/Gif/Level_1.gif?raw=true)

6. 늑대는 게임 시작 10초 후부터 등장하며 자유이동한다. 충돌 시 빨간모자는 사망한다.
7. game over 시 LCD에 “GAME OVER” 출력된다.
8. Reset 옆 2번 핀을 내리고 Reset을 눌러 다시 시작한다. 
