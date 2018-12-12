# Cad and SoC Design Lab Tutorial
신입생/인턴들을 위한 자료 모음
## Git 
깃은 버전관리, 코드관리를 위해 필수 불가결한 도구로 사용되고 있습니다. 

다루는 코드가 많고, 코드가 방대해지면 자신을 믿을 수 없게 됩니다. 협업에도 중요한 역할을 합니다. 

학교 계정을 통해 가입하면, 무료 private 저장소를 일정기간동안 줍니다. 졸업년도를 잘 입력합시다!

처음 시작하는 단계에서는 계속 읽으면서 개념을 습득하는게 중요합니다. [1: Git 개요](https://postechackr-my.sharepoint.com/:b:/g/personal/sunghoon1kim_postech_ac_kr/EaQqzn0Tk5xKiwJKjwRR5N4B1kQPZwFNs9WK-x8rM1sGMA?e=VewVHr), 
[2: Summary 자료](https://github.com/KennethanCeyer/tutorial-git), [3: Curtis Kim, Git Introduction](https://postechackr-my.sharepoint.com/:b:/g/personal/sunghoon1kim_postech_ac_kr/EZu9KhChZRFAgZg_R4r_YuwBh5DAXweMnoomIinHuKB15Q?e=jTvfCl)를 추천합니다. 대략적인 깃에관한 설명이 잘 되어있습니다.

이후 inflearn 강좌를 이용해 실습해보시면 됩니다. 
Vivado를 이용할때 GUI때문에 Window에서 작업할 일이 많은데, 이때 Souretree를 이용하면 편리합니다. 
서버에서는 GIT의 명령어들을 숙지하시면 됩니다. 

* [윈도우 Sourcetree 이용](https://www.inflearn.com/course/git-and-github/)  
* [지옥에서 돌아온 Git](https://www.inflearn.com/course/%EC%A7%80%EC%98%A5%EC%97%90%EC%84%9C-%EC%98%A8-git/)
* [버전관리시스템 Git](https://www.inflearn.com/course/git-2/)

## X-Shell을 통해 서버 접속하기
서버에 접속하기 위해 터미널(X-Shell, Putty)등 터미널을 이용합니다. 
* [X-shell v6](https://www.netsarang.co.kr/news/ver6_release.html) 학교, 가정용으로 다운
* [서버접속하기]
* [ftp 이용하기]
* [scp 이용하기]

## Vim
Linux서버를 이용해 코드작업하는 일이 많습니다. 간단한 vim 가이드를 소개합니다.
* [Simple Vim Guide](https://github.com/johngrib/simple_vim_guide/blob/master/README.md) 


## C언어
* [코딩도장 C](https://dojang.io/course/view.php?id=2)
* [열혈 C]

## Python / Deep Learning 
머신러닝 붐과 함께 핫하게 떠오르고 있는 언어입니다. 코드를 짜기 편리하고, Tensorflow, Pytorch 등을 사용, C언어로 변환하기 위해서 배워둘 필요가 있습니다. 
* [K-Mooc: 데이터 과학을 위한 파이썬 입문](https://github.com/TeamLab/Gachon_CS50_Python_KMOOC)
* [머신러닝과 딥러닝 BASIC](https://www.edwith.org/others26)
* [논문으로 짚어보는 딥러닝의 맥](https://www.edwith.org/deeplearningchoi) 


## 하드웨어란?
하드웨어는
범용적으로 사용할 수 있는 소프트웨어와 달리 하드웨어는 특수한 목적으로 동작하는 장치입니다. 만드는데 오랜 시간과 많은 비용이 소모되지만 저전력으로 높은 성능을 얻을 수 있어 하드웨어를 사용합니다. 하드웨어는 개발 단계가 진행될 수록 버그를 찾기 힘들며, 수정하기 어렵고, 수정 비용이 크게 증가합니다. 따라서 각각의 개발 프로세스를 이해하고 준수하는 일이 무엇보다 중요합니다. 하드웨어를 설계하는 과정은 크게 Front-end와 Back-end 두 가지로 구분할 수 있습니다. Front-end는 하드웨어의 스펙과 동작을 정의해서 논리 회로로 구성된 netlist를 만들어내는 과정이며, Back-end는 설계된 로직을 실제 Die로 배치하는 등의 물리적인일을 담당합니다. 빌딩을 짓는 과정으로 예를 들면 건물의 크기 등의 스펙을 결정한 후 캐드등의 툴을 사용해서 도면을 그려보는 과정이 front-end 입니다. 설계 의도에 따라 아파트가 될 수 도있고 주상복합이 될 수있는 것처럼 어떤 하드웨어를 만들 것인지 명확한 정의가 필요한 과정입니다. 이어서 도면과 설계도를 기반으로 건물을 완성하는 과정이 back-end 입니다. 일을 하는 순서, 혹은 재료를 공급하는 시기 적절함에 따라 작업의 효율성이 달라질 수 있으며, 마감 처리등에 따라 완성도 (성능)가 달라질 수 있습니다. back-end는 설계 의도를 반영해서 물리적인 하드웨어 chip을 만드는 과정입니다.

### Front-end를 위해선 HDL(Verilog Coding)이 필요합니다.
* [문법 모음 사이트](http://verilog.renerta.com/source/vrg00038.htm) 
* [연습 문제들 모음](https://hdlbits.01xz.net/wiki/Main_Page)
* [IDEC 2018 자료들](https://postechackr-my.sharepoint.com/:f:/g/personal/sunghoon1kim_postech_ac_kr/EhxHE6dNYbBKkWHsAkr--AsBts9atLa5oYiKB8LzfZ1nBg?e=jNRFGP)

### Back-end를 잘 하기 위해선? 프로그래밍을 잘해야 합니다. 
* [알고리즘]
* [자료구조]

## Overleaf / Power Point / Excel
글과 발표자료를 예쁘고 간결하게 만들며 데이터 정리를 잘 하는 것도 직장인/대학원생이 갖춰야할 능력 중 하나 입니다.
* [Overleaf Main](https://www.overleaf.com/) & [Tutorial1](https://ko.overleaf.com/learn/latex/Main_Page) &[Tutorial2](https://www.dropbox.com/sh/x6bc2yik5x7w81u/AABG3tBJTkVss9hlpYjwm2MJa?dl=0)
* [PowerPoint](https://www.inflearn.com/course/%ED%8C%8C%EC%9B%8C%ED%8F%AC%EC%9D%B8%ED%8A%B8-%EA%B0%95%EC%A2%8C-quick-start/)
* [Excel](https://www.inflearn.com/course/%EC%97%91%EC%85%80-%EA%B0%95%EC%A2%8C/)


## Linux
* [Linux 자료](https://postechackr-my.sharepoint.com/:f:/g/personal/sunghoon1kim_postech_ac_kr/Es4a1QxvLkBHqBsVsO5zuYgBDhTDqjGPtcnxS7Y2dpENxg?e=1LCcQW) 

## Shell 명령어 
### TCL 
TCL은 Front-end, Back-end 등에서 사용할 툴들을 조작하는데 주로 사용됩니다. 
* [TCL1](https://www.dropbox.com/sh/ej208jcrqd6o3xz/AAC1udUUn12vucdSTrymvER-a?dl=0) 

## Etc.

