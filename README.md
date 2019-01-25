# [CAD and SoC Design Lab Tutorial](http://soc.postech.ac.kr)
신입생/인턴들을 위한 자료 모음
## Git 
깃은 버전 관리, 코드 관리를 위해 필수 불가결한 도구로 사용되고 있습니다. 
다루는 코드가 많고, 방대해지면 자신을 믿을 수 없게 됩니다... 협업에도 중요한 역할을 합니다. 


처음 시작하는 단계에서는 계속 읽으면서 개념을 습득하는 게 중요합니다. [1: Git 개요](https://postechackr-my.sharepoint.com/:b:/g/personal/sunghoon1kim_postech_ac_kr/EaQqzn0Tk5xKiwJKjwRR5N4B1kQPZwFNs9WK-x8rM1sGMA?e=VewVHr), 
[2: Summary 자료](https://github.com/KennethanCeyer/tutorial-git), [3: Curtis Kim, Git Introduction](https://postechackr-my.sharepoint.com/:b:/g/personal/sunghoon1kim_postech_ac_kr/EZu9KhChZRFAgZg_R4r_YuwBh5DAXweMnoomIinHuKB15Q?e=jTvfCl)를 추천합니다. 대략적인 설명이 잘 되어있습니다.

이후 inflearn 강좌를 이용해 실습해보시면 됩니다. 
Vivado를 이용할 때 GUI 때문에 Window에서 작업할 일이 많은데, 이때 Souretree를 이용하면 편리합니다. 
서버에서는 Git CLI 명령어를 숙지하시면 됩니다. 

* [Sourcetree 및 Git 기초](https://www.inflearn.com/course/git-and-github/)  
* [지옥에서 돌아온 Git](https://www.inflearn.com/course/%EC%A7%80%EC%98%A5%EC%97%90%EC%84%9C-%EC%98%A8-git/)
* [버전관리시스템 Git](https://www.inflearn.com/course/git-2/)

## X-Shell을 통해 서버 접속하기
서버에 접속하기 위해 터미널(X-Shell, Putty 등)을 이용합니다. 
* [X-shell v6](https://www.netsarang.co.kr/news/ver6_release.html) 학교, 가정용으로 다운
* [서버접속하기/ ftp 이용하기](https://postechackr-my.sharepoint.com/:b:/g/personal/sunghoon1kim_postech_ac_kr/EUCD4Nt_0w5OkyiSGQQpOy4B5DX_FqI5xWOn9UAo4AFw1w?e=XuxaiO)

## Vim
서버에서 텍스트 편집기 Vim을 주로 사용합니다. 
* [Simple Vim Guide](https://github.com/johngrib/simple_vim_guide/blob/master/README.md) 
* [밤앙개 Vim](https://m.blog.naver.com/PostList.nhn?blogId=nfwscho&categoryNo=45&logCode=0) 

## C언어
* [코딩도장 C](https://dojang.io/course/view.php?id=2)
* [Embedded C](http://www.seoulworkshop.org/tag/Embedded_C?fbclid=IwAR1w9VR1a3uBb8Y7vSM6ystwe_4gjCK9XstcvDjiMZcDpaKnFJrsYni87-o) 
* [임베디드 프로그래밍 C 코드 최적화 eBook](http://book.interpark.com/product/BookDisplay.do?_method=detail&sc.shopNo=0001100000&sc.prdNo=250377090&sc.saNo=007&bnid1=book_2015&bnid2=bottom&bnid3=Author&bnid4=relate_book)
* [디버깅: GDB 사용하기](http://blog.naver.com/PostView.nhn?blogId=shumin&logNo=220769056921&parentCategoryNo=&categoryNo=40&viewDate=&isShowPopularPosts=true&from=search)
* [GCC 사용법](http://seolin.tistory.com/73)
* [Makefile 만들기](http://bowbowbow.tistory.com/12)

## Python / Deep Learning 
머신러닝 붐과 함께 핫하게 떠오르고 있는 언어입니다. 코드를 짜기 편리하고, Tensorflow, Pytorch 등 머신러닝 라이브러리 사용 및 하드웨어에 적합한 C언어로 변환하기 위해서 배워둘 필요가 있습니다. 
* [K-Mooc: 데이터 과학을 위한 파이썬 입문](https://github.com/TeamLab/Gachon_CS50_Python_KMOOC)
* [머신러닝과 딥러닝 BASIC](https://www.edwith.org/others26)
* [논문으로 짚어보는 딥러닝의 맥](https://www.edwith.org/deeplearningchoi) 
* [Stanford cs231n_17_KOR_SUB](https://github.com/insurgent92/CS231N_17_KOR_SUB?fbclid=IwAR1vbL12UiUKEcKlQgJafIHh5qwr8NfaOIGfDa11vJm8ACZmWpm8greFqG8)

## 하드웨어란?
범용적으로 사용할 수 있는 소프트웨어와 달리 하드웨어는 특수한 목적으로 동작하는 장치입니다. 만드는데 오랜 시간과 많은 비용이 소모되지만 저전력으로 높은 성능을 얻을 수 있어 하드웨어를 사용합니다. 하드웨어는 개발 단계가 진행될 수록 버그를 찾기 힘들며, 수정하기 어렵고, 수정 비용이 크게 증가합니다. 따라서 각각의 개발 프로세스를 이해하고 준수하는 일이 무엇보다 중요합니다. 하드웨어를 설계하는 과정은 크게 Front-end와 Back-end 두 가지로 구분할 수 있습니다. Front-end는 하드웨어의 스펙과 동작을 정의해서 논리 회로로 구성된 netlist를 만들어내는 과정이며, Back-end는 설계된 로직을 실제 Die로 배치하는 등의 물리적인일을 담당합니다. 빌딩을 짓는 과정으로 예를 들면 건물의 크기 등의 스펙을 결정한 후 캐드등의 툴을 사용해서 도면을 그려보는 과정이 front-end 입니다. 설계 의도에 따라 아파트가 될 수 도있고 주상복합이 될 수있는 것처럼 어떤 하드웨어를 만들 것인지 명확한 정의가 필요한 과정입니다. 이어서 도면과 설계도를 기반으로 건물을 완성하는 과정이 back-end 입니다. 일을 하는 순서, 혹은 재료를 공급하는 시기 적절함에 따라 작업의 효율성이 달라질 수 있으며, 마감 처리등에 따라 완성도 (성능)가 달라질 수 있습니다. back-end는 설계 의도를 반영해서 물리적인 하드웨어 chip을 만드는 과정입니다.
[Ref](http://sharebook.kr/pages/viewpage.action?pageId=9437607)

### [Intro. to EDA Tools from IDEC](https://postechackr-my.sharepoint.com/:b:/g/personal/sunghoon1kim_postech_ac_kr/ESZoiswddKFNnuuUAbuFEkABf2FO0CURwxHzSgMV8ZHdEA?e=cETyeJ)
### HDL (Verilog Coding)
* [문법 모음 사이트](http://verilog.renerta.com/source/vrg00038.htm) 
* [연습 문제들 모음](https://hdlbits.01xz.net/wiki/Main_Page)
* [IDEC 2018 자료들](https://postechackr-my.sharepoint.com/:f:/g/personal/sunghoon1kim_postech_ac_kr/EhxHE6dNYbBKkWHsAkr--AsBts9atLa5oYiKB8LzfZ1nBg?e=jNRFGP)

#### Design of Digital Circuits & Computer Architecture 
  * [Deep Learning & HW Accelerators](https://github.com/fengbintu/Neural-Networks-on-Silicon)
  * [PYNQ Work Shop](https://github.com/Xilinx/PYNQ_Workshop) 
  * [UsefulSite1: ETH Zurich](http://www.syssec.ethz.ch/education/Digitaltechnik_17.html) & [UsefulSite2: Cornell ECE4750](https://www.csl.cornell.edu/courses/ece4750/readings.html) & [UsefulSite3: Cornell ECE5745](https://www.csl.cornell.edu/courses/ece5745/handouts.html)

#### Xilinx 
 * [Xilinx Design Hub](https://www.xilinx.com/support/documentation-navigation/design-hubs.html)
 * [Xilinx Lab & Design Ref. Guide Download](https://www.xilinx.com/training/downloads.html)

### Back-end를 잘 하기 위해선? 프로그래밍을 잘해야 합니다. 
* [free programming books](https://github.com/EbookFoundation/free-programming-books/blob/master/free-programming-books.md?fbclid=IwAR1eEcSeLhYSkTps68RE3bjvGEuCGBU5QjpSIEEVIOJ_yCqoijc8wSKDXQs#vim) 
* [알고리즘 Deep Into Algorithm from MIT](https://www.edwith.org/introalgorithm)
* [자료구조]


## Linux
* [Linux 자료](https://postechackr-my.sharepoint.com/:f:/g/personal/sunghoon1kim_postech_ac_kr/Es4a1QxvLkBHqBsVsO5zuYgBDhTDqjGPtcnxS7Y2dpENxg?e=1LCcQW) 
* [이것이 우분투 리눅스다](https://www.inflearn.com/course/%EC%9D%B4%EA%B2%83%EC%9D%B4-%EC%9A%B0%EB%B6%84%ED%88%AC-%EB%A6%AC%EB%88%85%EC%8A%A4%EB%8B%A4/)
* [이것이 리눅스다](https://www.inflearn.com/course/%EC%9D%B4%EA%B2%83%EC%9D%B4-%EB%A6%AC%EB%88%85%EC%8A%A4%EB%8B%A4/)
## Shell 명령어 
### Tcl & Using Tool without GUI
[Tcl(Tool Command Language)](https://ko.wikipedia.org/wiki/Tcl)은 Front-end, Back-end 등에서 사용할 툴들을 조작하는데 주로 사용됩니다. 
* [Tcl Summary](https://www.dropbox.com/sh/ej208jcrqd6o3xz/AAC1udUUn12vucdSTrymvER-a?dl=0) 
* [How to Start Using Tools Efficiently: EDA tool without GUI](https://www.dropbox.com/s/wrlj8w3vyp06vm2/HowToStartUsingToolsEfficiently-v2.pdf?dl=0)

### Screen 
Screen은 리눅스에서 코드를 장시간 안정적으로 돌리기 위해 사용합니다. 스크린을 사용하지 않을 경우 터미널을 끄거나 인터넷연결이 끊어지면, 다시 코드를 돌려야하는 불편이 생깁니다.
* [Screen Summary](https://wikidocs.net/13887)
* [Screen Appendix1 Screen Copy mode](http://michael.thegrebs.com/2008/07/10/screen-copy-mode-can-copy/) 스크린 재 접속 후 얼마나 돌았나 확인하기 


## Overleaf / Power Point / Excel
글과 발표자료를 예쁘고 간결하게 만들며 데이터 정리를 잘 하는 것도 직장인/대학원생이 갖춰야할 능력 중 하나 입니다.
* [Overleaf Main](https://www.overleaf.com/) & [Tutorial1](https://ko.overleaf.com/learn/latex/Main_Page) &[Tutorial2](https://www.dropbox.com/sh/x6bc2yik5x7w81u/AABG3tBJTkVss9hlpYjwm2MJa?dl=0)
* [PowerPoint](https://www.inflearn.com/course/%ED%8C%8C%EC%9B%8C%ED%8F%AC%EC%9D%B8%ED%8A%B8-%EA%B0%95%EC%A2%8C-quick-start/)
* [Excel](https://www.inflearn.com/course/%EC%97%91%EC%85%80-%EA%B0%95%EC%A2%8C/)

