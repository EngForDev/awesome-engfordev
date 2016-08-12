# 버그 리포팅

## 목차
- [리포팅할때](https://github.com/LucyJeong/awesome-engfordev/blob/master/bugReporting/README.md#리포팅-할-때)
- [리포팅에 대한 답변을 할 때](https://github.com/LucyJeong/awesome-engfordev/blob/master/bugReporting/README.md#리포팅에-대한-답변을-할-때)


## 리포팅 할 때

- ### 이 부분을 좀 살펴봐줄래?
  - **Could you take a look at ~**
  - ~을 살펴봐줄 수 있어? (살펴봐줄래?)
    - (쉬운 예) **Could you take a look at my computer?**
    - 내 컴퓨터 한번 **살펴봐주래?**
    - **Could you take a look at** this please?
    - 이 부분 좀 살펴봐줄 수 있니?

- ### ~을 사용하다가 이런 문제가 생겼다.
  - **I faced ... using ~**
  - 나는 ~을 사용하다가 ...에 직면했다. (어떤 문제 등이 생겼다.)
    - (쉬운 예) **I faced** a problem **using** the computer.
    - 컴퓨터를 **사용하는 중에** 문제가 **나타났어.**
    - **I faced** a strange behavior **using** the max_pool op.
    - max_pool op를 **사용하다가** 이상한 부분을 발견했어.
    - faced, using 설명
      - face는 얼굴이란 뜻도 있지만, 'faced a problem'에서 face가 동사로써, '무언가에 직면하다'는 의미를 지니고 있다.
      - use: 사용하다라는 의미인데, 'I faced a problem using (A)'는 (A)를 사용하다가, 사용하는 중에' 라는 의미로, 이때 use + ing -> using을 현재분사라고 함.


- ### 난 ~에 대해서 문제가(어려움이) 있었다.
  - **I had problems with ~**
  - 나는 ~에 대해서 문제가 있었어.
    - (쉬운 예) **I have problem with** this app.
    - 나는 이 앱과 관련한 문제가 많아.
    - **I had problems with** NaNs in my pipeline.
    - 나는 내 파이프라인에 있는 NaNs에 대해 문제가 있어.
      - problem with: ~와 관련해서 문제가 있다.


- ### Server를 위해 서류를 검토하는 도중에
  - **look through ~**
  - ~를 검토하다
    - (쉬운 예) Please **look through** the report.
    - 레포트를 **검토해줘**
    - **Looking through** the documentation for Server.
    - Sever를 위해 문서를 검토하는 도중에

- ### 난 64비트 Linux를 컴퓨터로 실행시키고 있다.
  - **run ~ with**
  - ~을 ~로 실행시키다
    - (쉬운 예) I am **running** this program with my laptop.
    - 나는 이 프로그램을 내 노트북으로 실행 시키고 있다.
    - I am **running** a 64-bit Linux (CentOS) **with** a computer.
    - 나는 64비트 리눅스(CentOS)를 컴퓨터로 실행시키고 있다.

- ### 나는 이 문제도 가지고 있다.
  - I'm having this **issue as well**.
  - issue: 문제, 사안 / as well: ~도, ~또한 (동의어:too)
    - (비슷한 에) This **issue** came up **as well**.
    - 이 문제도 나타났다.

  - ###Contribution 할 때

      - 텐서플로우에 ~을 설치해줄 수 있어?
        - **Could you please?**
        - ~해줄 수 있어?
          - (쉬운 예)**Could you please** open the window?
          - 창문을 열어줄 수 있어?
          - **Could you please** implement 2D/3D dilated convolution and 2D/3D dilated pooling in TensorFlow?
          - 2D/3D dilated convolution와 2D/3D dilated pooling을 TensorFlow에 설치해줄 수 있어?


- ### ~하는 방법이 있어?
  - **Is there any way ~**
  - ~을 하는 방법이 있니?
    - (쉬운 예) **Is there any way** that I can contact her?
    - 내가 그녀에 연락할 방법이 있어?
    - **Is there any way** to do a partial assign?
    - 부분 배정을 하는 방법이 있어?

## 리포팅에 대한 답변을 할 때

- ### ~점에 주의해
  - **Note that ~**
  - ~에 주목하다 / 주의하다
    - (쉬운 예) **Note that** this is poisonous.
    - 이것이 독성이 있다는 **점에 주목해.**
    - **Note that** this is without any specific inputs.
    - 이것이 특정 인풋이 전혀 없어도 그렇다는 **점에 주의해.**
    - **Note that** TensorShape has been heavily optimized to avoid memory allocations.
    - TensorShape가 메모리 할당을 피하기 위해 최적화 되어 있다는 **점에 주의해.**
    - **Note that** another user is connected to both GPUs through Torch7, and is actively using gpu0.
    - 다른 사용자가 Torch7을 통해 두개의 GPUs에 모두 연결되어 있고, gpu0를 사용하고 있다는 **점을 유의해.**

- ### 내생각에는 이 부분도 언급해야 할 것 같다.
    - **I guess (that)~**
    - 내 생각에는 ~인 것 같다.
      - (쉬운 예) **I guess** you are right.
      - 너의 말이 맞는 것 같아.
      - **I guess** this behavior should be mentioned within the documentation.
      - **내 생각에** 문서에 이 행동이 명시되어야 **한다고 생각해.**

- ### 넌 몇군데 바꿔야 할 수도 있다.
  - **It is possible (that)~**
  - ~할 가능성이 있다. ~이 가능하다.
    - (쉬운 예) **It is possible** to have a meeting at 10.
    - 10시에 미팅을 할 가능성이 있다. 10시에 미팅이 가능하다.
    - **It is possible that** you need to change several places to make this work.
    - 너가 이것이 작동되게 하기 위해 몇몇 부분을 바꿔야 할 수도 있다.

- ### 내가 서류를 이해한 바로는
  - **As I understand ~**
  - 내가 ~을 이해한 바로는,
    - (쉬운 예) **As I understand** your opinion, you do not agree with me, right?
    - 내가 네 의견을 이해한 바로는, 넌 나에게 동의하지 않아. 맞지?
    - **As I understand** from the documentation,
    - 제가 서류를 이해한 바로는,
    - As는 ~하는 동안에/~한 대로/~때문에/~이긴 하지만 등 다양하게 해석된다. 문맥에 맞게 적절한 의미를 부여하면 된다. (근데 그게 어렵지!)
    
- ### ~을 지원하는거 같은데.
  - **It look like~**
  - ~ 하는 것 같다.
    - (쉬운 예) **It looks like** it's going to rain.
    - 비가 올 **것 같다.**
    - **It looks like** TensorFlow already supports 2D dilated convolution.
    - TensorFlow가 이미 2D dilated convolution을 **지원하는 것 같다.**
