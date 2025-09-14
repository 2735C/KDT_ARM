
![PPT_1](https://github.com/2735C/KDT_ARM/blob/main/History/Img/ppt_1.png?raw=true)|
--|

### [Personal Project]
### 🖊️Role

- 게임 스토리 기획
- Embedded C 코딩

### 프로젝트 요약


![PPT_2](https://github.com/2735C/KDT_ARM/blob/main/History/Img/img0.png?raw=true)|
--|


|<img src="/History/Img/img0.png" width=1000>|
|--|

> ### 개발 환경


- 오브젝트: 빨간모자, 과일, 늑대 
- 장비: stm32f10x(CORTEX-M3), LCD board

> ### 개발 일정

| 날짜       | 4/26 (토) | 4/27 (일) | 5/1 (목) | 5/2 (금) | 5/3 (토) | 5/4 (일) | 5/5 (월) | 5/6 (화) |
|------------|------------|------------|-----------|-----------|-----------|-----------|-----------|-----------|
| 목표       |     예제 <br>코드<br> 분석       |    과일 및 고정<br> object 구현   |    늑대 <br>object <br>구현   |    결과 <br>보고서<br> 제작  |           |           |           |           |
| 달성       |  예제<br> 코드<br> 분석   |            |           | 과일<br> object <br>제작   |           | 과일<br> object <br>오류 해결 |  늑대 <br>object<br> 제작   |   오류 해결<br> 및 결과 보고서 <br>제작  |


![PPT_3](https://github.com/2735C/KDT_ARM/blob/main/History/Img/ppt_3.png?raw=true)|
--|

![PPT_4](https://github.com/2735C/KDT_ARM/blob/main/History/Img/ppt_4.png?raw=true)|
--|

> ### Game Rule

1. 정은지_실핼파일1.bin 파일을 TERA TERM에 다운로드한다.
2. 게임 제한 시간은 50초이며 LCD 화면에 감소 시간이 나타난다. 
3. 빨간모자는 키조작으로 움직일 수 있다. (KEY0, KEY1을 활용해도 좌우로 움직일 수 있다.)
4. 과일은 3초마다 등장하며 과일을 쪼개면 할머니의 치료약(GHP)을 만들 수 있다.
5. GHP =과일*3/5, GHP 개수에 따라 엔딩이 달라진다. 
> (즉, 과일: 1개 -> GHP: 0, 과일: 2개 -> GHP: 1, 과일: 5개 -> GHP: 3)

![Demo GIF1](https://github.com/2735C/KDT_ARM/blob/main/History/Gif/Level_1.gif?raw=true)

6. 늑대는 게임 시작 10초 후부터 등장하며 자유이동한다. 충돌 시 빨간모자는 사망한다.

![Demo GIF2](https://github.com/2735C/KDT_ARM/blob/main/History/Gif/Level_2.gif?raw=true)


7. game over 시 LCD에 “GAME OVER” 출력된다.

![Demo GIF3](https://github.com/2735C/KDT_ARM/blob/main/History/Gif/Level_3.gif?raw=true)

8. Reset 옆 2번 핀을 내리고 Reset을 눌러 다시 시작한다. 
