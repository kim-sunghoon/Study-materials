# Study materials 
@ [CAD and SoC Design Lab in POSTECH](http://csdl.postech.ac.kr)

# 📖 1. Tools 
## Git 
깃은 코드 관리, 버전 관리를 위해 필수 불가결한 도구로 사용되고 있습니다. 다루는 코드가 많고, 방대해지면 자신을 믿을 수 없게 됩니다.
협업에서도 중요한 역할을 합니다. [Summary-1](https://github.com/KennethanCeyer/tutorial-git) & [Summary-2 | 웹말고 다운 받아 보세요](https://www.slideshare.net/IldooKim/170209-github-introduction-korean-version)

아래의 강좌를 추천합니다. GUI 때문에 Window에선 Souretree를 이용하면 편리하고, 서버에서는 Git CLI 명령어를 숙지하시면 됩니다. 
 
* [Sourcetree 및 Git 기초](https://www.inflearn.com/course/git-and-github/)  
* [지옥에서 돌아온 Git](https://www.inflearn.com/course/%EC%A7%80%EC%98%A5%EC%97%90%EC%84%9C-%EC%98%A8-git/)
* [버전관리시스템 Git](https://www.inflearn.com/course/git-2/)
* [GitHub Cheat Sheet](https://github.com/yunho0130/github-cheat-sheet/blob/master/README.ko.md) 
* https://learngitbranching.js.org/?locale=ko 

## X-Shell을 통해 서버 접속하기
서버에 접속하기 위해 터미널(X-Shell, Putty 등)을 이용합니다. 
* [X-shell v6](https://www.netsarang.co.kr/news/ver6_release.html) 학교, 가정용으로 다운
* [서버접속하기/ ftp 이용하기](https://postechackr-my.sharepoint.com/:b:/g/personal/sunghoon1kim_postech_ac_kr/EUCD4Nt_0w5OkyiSGQQpOy4B5DX_FqI5xWOn9UAo4AFw1w?e=XuxaiO)

## VNC를 통해 서버 접속하기
응답속도가 빠른 GUI가 필요한 경우 VNC를 이용해 서버에 접속합니다. 
* [VNC Connection](https://www.dropbox.com/s/ulszhciudwi1f67/VNC_connection.pptx?dl=0) 

## Vim
서버에서 텍스트 편집기 Vim을 주로 사용합니다. 
* [Simple Vim Guide](https://github.com/johngrib/simple_vim_guide/blob/master/README.md) 
* [밤앙개 Vim](https://m.blog.naver.com/PostList.nhn?blogId=nfwscho&categoryNo=45&logCode=0) 
* [Vim 에디터 다양한 기능 설명 및 C++/Python 개발 환경설정 · Edward Im](https://edward0im.github.io/technology/2020/09/17/vim/)
* [Dotfiles/Plugin Auto install](https://github.com/kim-sunghoon/dotfiles)
  - works @ EDA, HDL, CPU, GPU and CNN servers (Except RTL - cetos 6) 

## Visual Studio Code 
* [1편: VSCode 설치와 유용한 extension 설치 및 사용법, 단축키](https://youtu.be/Xs5aM9FYuic)
* [2편: VSCode와 Window ubuntu 연결, ubuntu에 Python 설치](https://youtu.be/1Zhb-QEKIEY)
* [3편: VSCode와 git 연동](https://youtu.be/hKhX87L2ydQ)
* [알아두면 쓸데있는 VSCode 노하우](https://youtu.be/_QCNqV_EfzE)

## Linux
* [**Linux Command Line tool 인프런**](https://www.inflearn.com/course/command-line/#) 
* [**이것이 우분투 리눅스다**](https://www.inflearn.com/course/%EC%9D%B4%EA%B2%83%EC%9D%B4-%EC%9A%B0%EB%B6%84%ED%88%AC-%EB%A6%AC%EB%88%85%EC%8A%A4%EB%8B%A4/)
* :star2: [**modern-unix tool**](https://github.com/ibraheemdev/modern-unix) 
  * [git-fuzzy](https://github.com/bigH/git-fuzzy)
* [이것이 리눅스다](https://www.inflearn.com/course/%EC%9D%B4%EA%B2%83%EC%9D%B4-%EB%A6%AC%EB%88%85%EC%8A%A4%EB%8B%A4/)
* [Linux Bible 자료](https://postechackr-my.sharepoint.com/:f:/g/personal/sunghoon1kim_postech_ac_kr/Es4a1QxvLkBHqBsVsO5zuYgBDhTDqjGPtcnxS7Y2dpENxg?e=1LCcQW) 
* [Virtual Box1](https://m.blog.naver.com/wideeyed/220960764870) & [Virtual Box2](https://technote.kr/178)

### Tcl & Using Tool without GUI
[Tcl (Tool Command Language)](https://ko.wikipedia.org/wiki/Tcl)은 Front-end, Back-end 등에서 사용할 툴들을 조작하는데 사용됩니다. 
* [Tcl Summary](https://www.dropbox.com/sh/ej208jcrqd6o3xz/AAC1udUUn12vucdSTrymvER-a?dl=0) 
* [How to Start Using Tools Efficiently: EDA tool without GUI](https://www.dropbox.com/s/wrlj8w3vyp06vm2/HowToStartUsingToolsEfficiently-v2.pdf?dl=0)

### Screen 
Screen은 리눅스에서 코드를 장시간 안정적으로 돌리기 위해 사용합니다. 스크린을 사용하지 않을 경우 사용 중인 터미널(X-Shell etc)을 끄거나 인터넷연결이 끊어지면 다시 코드를 돌려야합니다. 
* [Screen Summary](https://wikidocs.net/13887)
* Screen Copy mode, 스크린 재 접속 후 위에 어떤 작업이 진행됬는지 확인하기 
  * Entering Copy Mode and Scrolling 
    - By default, enter copy mode with *CRTL+a* then *ESC*. You can use vi like commands to navigate through the scollback buffer. The *arrows* and *PAGE UP/DOWN* should works as well. 

### Link File 생성 [[1]](https://webdir.tistory.com/148), [[2]](https://zetawiki.com/wiki/%EB%A6%AC%EB%88%85%EC%8A%A4_%EC%8B%AC%EB%B3%BC%EB%A6%AD%EB%A7%81%ED%81%AC_%EC%83%9D%EC%84%B1_%EC%8B%A4%EC%8A%B5), [[3]](https://zetawiki.com/wiki/%EB%A6%AC%EB%88%85%EC%8A%A4_%EC%8B%AC%EB%B3%BC%EB%A6%AD%EB%A7%81%ED%81%AC_%EC%82%AD%EC%A0%9C)
윈도우의 바로가기와 비슷한 개념입니다. 크게 Hard Link, Softlink (symbolic link) 두 가지 링크 파일이 존재합니다.
* 링크 생성하기 
```shell
사용법: $ ln [옵션] 원본 링크
하드링크 $ ln 원본 링크 
소프트링크 $ ln -s 원본 링크 
``` 
* 소프트링크 삭제하기
  * **rm -f 로 삭제**
  * **마지막에 /를 붙이면 안됨**
  - :star2: **원본 폴더를 삭제하지 않도록 주의해야함 아래 명령어 수행시 원본파일 삭제됨** 
  
    ```$ rm -rf myfolderlink/  --> Bad End```
---   

# ♦️ 2. How to make a chip? | Front-end and Back-end of hardware design
* 하드웨어란?
> 범용적으로 사용할 수 있는 소프트웨어와 달리 하드웨어는 특수한 목적으로 동작하는 장치입니다. 만드는데 오랜 시간과 많은 비용이 소모되지만 저전력으로 높은 성능을 얻을 수 있어 하드웨어를 사용합니다. 하드웨어는 개발 단계가 진행될 수록 버그를 찾기 힘들며, 수정하기 어렵고, 수정 비용이 크게 증가합니다. 따라서 각각의 개발 프로세스를 이해하고 준수하는 일이 무엇보다 중요합니다. 하드웨어를 설계하는 과정은 크게 Front-end와 Back-end 두 가지로 구분할 수 있습니다. Front-end는 하드웨어의 스펙과 동작을 정의해서 논리 회로로 구성된 netlist를 만들어내는 과정이며, Back-end는 설계된 로직을 실제 Die로 배치하는 등의 물리적인일을 담당합니다. 빌딩을 짓는 과정으로 예를 들면 건물의 크기 등의 스펙을 결정한 후 캐드등의 툴을 사용해서 도면을 그려보는 과정이 front-end 입니다. 설계 의도에 따라 아파트가 될 수 도있고 주상복합이 될 수있는 것처럼 어떤 하드웨어를 만들 것인지 명확한 정의가 필요한 과정입니다. 이어서 도면과 설계도를 기반으로 건물을 완성하는 과정이 back-end 입니다. 일을 하는 순서, 혹은 재료를 공급하는 시기 적절함에 따라 작업의 효율성이 달라질 수 있으며, 마감 처리등에 따라 완성도 (성능)가 달라질 수 있습니다. back-end는 설계 의도를 반영해서 물리적인 하드웨어 chip을 만드는 과정입니다.
[Ref](http://sharebook.kr/pages/viewpage.action?pageId=9437607)

## [Intro. to EDA Tools from IDEC](https://postechackr-my.sharepoint.com/:b:/g/personal/sunghoon1kim_postech_ac_kr/ESZoiswddKFNnuuUAbuFEkABf2FO0CURwxHzSgMV8ZHdEA?e=cETyeJ)

## Front-end - HDL (Verilog Coding)
* [문법 모음 사이트](http://verilog.renerta.com/source/vrg00038.htm) 
* [**연습 문제 사이트 hdlbits!**](https://hdlbits.01xz.net/wiki/Main_Page)
* [IDEC 2018 자료들](https://postechackr-my.sharepoint.com/:f:/g/personal/sunghoon1kim_postech_ac_kr/EhxHE6dNYbBKkWHsAkr--AsBts9atLa5oYiKB8LzfZ1nBg?e=jNRFGP)
* [Facebook HDL Korea (SV/Verilog/VHDL)](https://www.facebook.com/groups/2442026209451002/)
* Design of Digital Circuits & Computer Architecture 
  - [**MIT Tutorial**](http://eyeriss.mit.edu/tutorial.html)
  - [**Stanford CS217 - Hardware Accelerators for Machine Learning**](https://cs217.stanford.edu/)
  - [**Papers: Deep Learning & HW Accelerators**](https://github.com/fengbintu/Neural-Networks-on-Silicon)
  - [**Collection of recent methods on DNN compression and acceleration**](https://github.com/MingSun-Tse/EfficientDNNs)
  - [Neural Network Acceleration Study](https://github.com/ConstantPark/Nerual-Network-Acceleration)
  - [Neural Network Accelerator Inference](https://nicsefc.ee.tsinghua.edu.cn/projects/neural-network-accelerator/)
  - [Embedded and mobile deep learning research resources(EMDL)](https://github.com/EMDL/awesome-emdl)
  - [UsefulSite1: ETH Zurich](https://www.youtube.com/watch?v=g3yH68hAaSk&list=PL5Q2soXY2Zi9JXe3ywQMhylk_d5dI-TM7) & [UsefulSite2: Cornell ECE4750](https://www.csl.cornell.edu/courses/ece4750/readings.html) & [UsefulSite3: Cornell ECE5745](https://www.csl.cornell.edu/courses/ece5745/handouts.html)
  - MIPS Instruction Set Architecture [1](https://www.youtube.com/watch?v=PlavjNH_RRU&list=PLylNWPMX1lPlmEeeMdbEFQo20eHAJL8hx) & [2](https://www.youtube.com/watch?v=qzSdglU0SBc&list=PLylNWPMX1lPnipZzKdCWRj2-un5xvLLdK)
  - [Neural Network Dataflow Scheduling](https://github.com/stanford-mast/nn_dataflow)

  
* **Xilinx Vivado**
  - [**Xilinx University Program**](https://www.xilinx.com/support/university/vivado/vivado-workshops.html)
  - [**Recipe for FPGA cooking**](https://github.com/lastweek/FPGA)
  - [ug939-Vivado Design Suite Tutorial: Designing with IP](https://www.xilinx.com/support/documentation/sw_manuals/xilinx2018_2/ug939-vivado-designing-with-ip-tutorial.pdf) 
  - [ug1119-Vivado Design Suite Tutorial: Creating and Packaging Custom IP](https://www.xilinx.com/support/documentation/sw_manuals/xilinx2018_2/ug1119-vivado-creating-packaging-ip-tutorial.pdf) 
  - [ug940-Embedded Processor HW Design](https://www.xilinx.com/support/documentation/sw_manuals/xilinx2018_2/ug940-vivado-tutorial-embedded-design.pdf#%5B%7B%22num%22%3A113%2C%22gen%22%3A0%7D%2C%7B%22name%22%3A%22XYZ%22%7D%2C51%2C720%2C0%5D)
  - [Xilinx Video Series](https://forums.xilinx.com/t5/Video/Xilinx-Video-Series/td-p/849583) 
  - [Vivado HW Server Connection](https://www.dropbox.com/s/gv19bvl962f51th/Vivado_Hardware_Server.pptx?dl=0)
  
* **Xilinx High Level Synthesis** 
  - [Parallel Programming for FPGAs: An open-source high-level synthesis book](https://github.com/KastnerRG/pp4fpgas)
  - [Cornell Z. Zhang 2018](https://postechackr-my.sharepoint.com/:f:/g/personal/sunghoon1kim_postech_ac_kr/EqACs4rcczpIvayXAZpnoqMBgzRmGcsJuFoyGh9P3IXpVA?e=JJ9uH0)
  - [CMU J.C. Hoe 2017](https://postechackr-my.sharepoint.com/:f:/g/personal/sunghoon1kim_postech_ac_kr/EsAQpr6_4qJIvpPa4_PHcx8BJe2K9FyGJYkNPZsHFmND0Q?e=V3UTh3) 
  - [ug871-xilinx HLS tutorial](https://www.xilinx.com/support/documentation/sw_manuals/xilinx2018_2/ug871-vivado-high-level-synthesis-tutorial.pdf)
  
* **Open Source**
   - **DAC SDC** [Overview](http://www.cse.cuhk.edu.hk/~byu/2019-DAC-SDC/index.html), [Winners](https://github.com/xyzxinyizhang/2019-DAC-System-Design-Contest), [Webniar](https://drive.google.com/file/d/1ZFFSMyLNH88ClTnxbovtd7MEx2Ce5dOb/view) 
      - [DAC SDC 2020 Page](https://dac-sdc-2020.groups.et.byu.net/doku.php)
      - [DAC SDC 2019 FPGA 1st: SkyNet](https://github.com/TomG008/SkyNet) 
      - [DAC SDC 2019 FPGA 2nd: XJTU-Tripler](https://github.com/venturezhao/XJTU-Tripler)
      - [DAC SDC 2019 FPGA 3rd: spooNN](https://github.com/fpgasystems/spooNN/tree/DAC2019)
      - [DAC SDC 2018 FPGA 1st: TGIIF](https://github.com/hirayaku/DAC2018-TGIIF)
      - [DAC SDC 2018 FPGA 2nd: spooNN](https://github.com/fpgasystems/spooNN)
      - [DAC SDC 2018 FPGA 3rd: iSmart2](https://github.com/onioncc/iSmartDNN)
      - [PYNQ WorkShop](https://github.com/Xilinx/PYNQ_Workshop) 
   - [Yolo_v2 on PYNQ](https://github.com/dhm2013724/yolov2_xilinx_fpga)
   - [ZynqNet](https://github.com/dgschwend/zynqnet)
   - [Xilinx/CHaiDNN-HLS based Deep Neural Network Accelerator Library for Xilinx Ultrascale+ MPSoCs](https://github.com/Xilinx/CHaiDNN)
   - [HLS4ML](https://github.com/hls-fpga-machine-learning/hls4ml)
   - [DNN Weaver](http://dnnweaver.org/)
   - [Scalable systolic array-based matrix-matrix multiplication implemented in Vivado HLS for Xilinx FPGAs](https://github.com/spcl/gemm_hls)
   - **Z. Zhang Group, Cornell**
      - [BNN on FPGA, FPGA 2017](https://github.com/cornell-zhang/bnn-fpga) 
      - [Accelerating Face Detection on FPGA, FPGA 2017](https://github.com/cornell-zhang/facedetect-fpga)
      - [Rosetta: A Realistic High-level Synthesis Benchmark Suite for Software Programmable FPGAs, FPGA 2018](https://github.com/cornell-zhang/rosetta)
   

 --- 
 ## Back-end 
 * VLSI Physical Design: From Graph Partitioning to Timing Closure: https://link.springer.com/book/10.1007/978-90-481-9591-6
 * https://github.com/The-OpenROAD-Project/OpenROAD 
 * https://github.com/siliconcompiler/siliconcompiler 
 * [Nature 2021, Google] A graph placement methodology for fast chip design. 
     - code: https://github.com/google-research/circuit_training 
---  
# 📢 3 Common skills 
## Algorithm + Computer Science Basics 
 * [Free programming books](https://github.com/EbookFoundation/free-programming-books/blob/master/free-programming-books.md?fbclid=IwAR1eEcSeLhYSkTps68RE3bjvGEuCGBU5QjpSIEEVIOJ_yCqoijc8wSKDXQs#vim) 
 * [Deep Into Algorithm from MIT](https://www.edwith.org/introalgorithm)
 * [The Algorithms: Open Source Resource for Newbies to Learn Algorithms and Implement them in any Programming Language](https://github.com/TheAlgorithms)
 * [Google Coding Style Guides](https://google.github.io/styleguide/)
 * [Programmers Coding Test](https://programmers.co.kr/learn/challenges) 
 * [**gyoogle / tech-interview-for-developer**](https://github.com/gyoogle/tech-interview-for-developer)
 * 🥇 [**신입 개발자 면접을 위한 지식 총 정리**](https://rokrokss.com/post/2019/04/06/%EB%A9%B4%EC%A0%91-%EC%A4%80%EB%B9%84-%EC%A0%84%EC%82%B0-%EC%88%98%EC%97%85-%EC%B4%9D%EC%A0%95%EB%A6%AC.html#network)
 * 🌠 [**boostcamp ai-tech-interview**](https://github.com/boostcamp-ai-tech-4/ai-tech-interview) 
 * [**brave-people brave-tech-interview**](https://github.com/brave-people/brave-tech-interview) 
 * [**brave-people Awesome-Dev-Contents**](https://github.com/brave-people/Awesome-Dev-Contents)
 * [Deep Learning Interviews book](https://github.com/BoltzmannEntropy/interviews.ai)
 * [awesome dev blog](https://disquiet.io/product/%EC%96%B4%EC%8D%B8%EB%8D%B0%EB%B8%8C%EB%B8%94%EB%A1%9C%EA%B7%B8)

## C언어
* [코딩도장 C](https://dojang.io/course/view.php?id=2)
* [Embedded C](http://www.seoulworkshop.org/tag/Embedded_C?fbclid=IwAR1w9VR1a3uBb8Y7vSM6ystwe_4gjCK9XstcvDjiMZcDpaKnFJrsYni87-o) 
* [임베디드 프로그래밍 C 코드 최적화 eBook](http://book.interpark.com/product/BookDisplay.do?_method=detail&sc.shopNo=0001100000&sc.prdNo=250377090&sc.saNo=007&bnid1=book_2015&bnid2=bottom&bnid3=Author&bnid4=relate_book)
* [GCC 사용법](http://seolin.tistory.com/73)
* [Makefile 만들기](http://bowbowbow.tistory.com/12)
* [디버깅: GDB 사용하기](http://blog.naver.com/PostView.nhn?blogId=shumin&logNo=220769056921&parentCategoryNo=&categoryNo=40&viewDate=&isShowPopularPosts=true&from=search)
* [생활코딩](https://opentutorials.org/course/1) 
* [OpenCV](https://www.youtube.com/playlist?list=PLvX6vpRszMkye9Zj16aG9J063A9rBfBj2) 
* [Darknet: Open Source Neural Networks in C](https://pjreddie.com/darknet/)
* [C++ Programming Curriculum for undergraduates](https://github.com/jeonhyun97/cpp_4_undergraduates)
* [cplusplus.com](http://www.cplusplus.com/)
* [Modern C++ Tutorial: C++11/14/17/20 On the Fly](https://github.com/changkun/modern-cpp-tutorial)
* [awesome-hpp: A curated list of awesome header-only C++ libraries](https://github.com/p-ranav/awesome-hpp)
--- 
## Embedded boards 
  - [GPU System Stack](https://github.com/zhangruiskyline/DeepLearning/blob/master/doc/system.md)
  - [IT기술노트](https://wikidocs.net/book/2184) 
  - [이니프로 카페](https://cafe.naver.com/plduser/14517)  
  - [ICBanQ](https://www.icbanq.com/A05_templete/templeteList.do?t_idx=203&catg_code=101144129)
* Nvidia Jetson 
  - [Jetson User Group for Korean](https://github.com/jetsonworld?tab=repositories) 
  - [인공지능 하드웨어 개발을 위한 Nvidia Jetson Nano 기초과정](https://www.g.camp/1216) 
  - [Jetson hacks1](https://github.com/jetsonhacks) | [Jetson hacks2](https://www.jetsonhacks.com/) 
  - [Jetson Fan Ctrl](https://github.com/Pyrestone/jetson-fan-ctl)
  - [Systemmd1](https://am003507.tistory.com/302) | [Systemmd2](https://www.elex.pe.kr/entry/%EC%9A%B0%EB%B6%84%ED%88%AC-systemd%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%B4%EC%84%9C-%EB%B0%B1%EA%B7%B8%EB%9D%BC%EC%9A%B4%EB%93%9C-%EC%84%9C%EB%B9%84%EC%8A%A4-%EB%93%B1%EB%A1%9D)
  - [라즈베리파이 문서](https://wikidocs.net/book/483)
  - [Interactive map of Linux kernel](https://makelinux.github.io/kernel/map/?fbclid=IwAR0xk6mNTxGM_jvOzfYlNlSKaqCRCSNNBz39kdPn6Wli6WpvBSaqyaXe9KE)
  - [임베디드 엔지니어 ](https://jpub.tistory.com/m/1064)
--- 

## Python
* [Python 대학 강의 모음 + Tips](https://github.com/yunho0130/Python_Lectures) 
* [K-Mooc: 데이터 과학을 위한 파이썬 입문](https://github.com/TeamLab/Gachon_CS50_Python_KMOOC)
* [pyCheckiO - python quiz](https://py.checkio.org/)
* [Anaconda 유용한 사용법](https://provia.tistory.com/55) 
* [파이썬 클린코드](http://www.yes24.com/Product/goods/69064790) - [git](https://github.com/PacktPublishing/Clean-Code-in-Python)
* [Google Python Style](https://google.github.io/styleguide/pyguide.html)
* [클래스 및 모듈 정리](https://seongjaemoon.github.io/python/2018/04/06/python-course3.html)
* [30-helpful-python-snippets](https://towardsdatascience.com/30-helpful-python-snippets-that-you-can-learn-in-30-seconds-or-less-69bb49204172)
* [Awesome Python: frameworks, libraries, software and resources](https://github.com/vinta/awesome-python)
* [Python Cheatsheet](https://github.com/gto76/python-cheatsheet)
* [Matplotlib](https://jehyunlee.github.io/2020/04/21/Python-DS-10-matplotlib_Tools/)
* [python process time measure](https://stackoverflow.com/questions/52222002/what-is-the-difference-between-time-perf-counter-and-time-process-time/52228375#52228375) 
* [python profiling](https://wikidocs.net/3692)
* [자주쓰는 명령어로 배우는 Pandas #1 : Pandas와 데이터 살펴보기](https://sjquant.tistory.com/54)
* [PyQt5 Tutorial - 파이썬으로 만드는 나만의 GUI 프로그램](https://wikidocs.net/book/2165)
* [python GUI Programming](https://www.youtube.com/watch?v=bKPIcoou9N8&t=1733s) 
* [파이썬 라이브러리, 점프투파이선 저자 박응용님](https://wikidocs.net/book/5445)
* [파이썬 알고리즘 인터뷰](https://github.com/onlybooks/algorithm-interview) 
---

# 4. Application: Deep Learning 
## Basics + Seminar 
* Probability Distribution: https://distribution-explorer.github.io/
* [머신러닝과 딥러닝 BASIC](https://www.edwith.org/others26)
* [GIST yongyi lee 머신러닝 BASIC] - [Slide](https://drive.google.com/file/d/1dLypFb0WS25_y1wL4uyzlhjByB7qCe4W/view?fbclid=IwAR1dJJI2O2YsX7js-ZRwRXsULxHOxHx_Q-6ur0DCCCV8ULMixFqhwB_PJvU), [Youtube](https://www.youtube.com/watch?v=hJH4w6mXIoE&feature=youtu.be&fbclid=IwAR0ln4NDNyfRSx8lae-nOObs2crAPXcbTA0D0_NHWuwo1nA61Hoxk2hEhk4)
* [역전파 알고리즘 완전정복](https://nbviewer.jupyter.org/github/metamath1/ml-simple-works/blob/master/BP/bp.ipynb?fbclid=IwAR1KMcFHPJs5St-RMKDHODe7L4bWhVM27j_lDCRmGCBK4tb2lbsWs8E3ocY) 
* [논문으로 짚어보는 딥러닝의 맥](https://www.edwith.org/deeplearningchoi) 
* [Stanford cs231n_17_KOR_SUB](https://github.com/insurgent92/CS231N_17_KOR_SUB?fbclid=IwAR1vbL12UiUKEcKlQgJafIHh5qwr8NfaOIGfDa11vJm8ACZmWpm8greFqG8)
* [Stanford cs230 -Deep Learning](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-convolutional-neural-networks?fbclid=IwAR0nVQBbsFR271fNtsiewA9x1jnP0Hp0j0nkx47kWKkNA7turD-ksT0nyQY)
* [이상화교수님 - 확률 및 통계](https://www.youtube.com/playlist?list=PLSN_PltQeOyjmRIsC7VNirXOBqWoypd4V)
* [State of AI Report 2019.06.28](https://www.slideshare.net/StateofAIReport/state-of-ai-report-2019-151804430?utm_campaign=nathan.ai+newsletter&utm_medium=email&utm_source=Revue+newsletter&fbclid=IwAR0jZ2j9B_bvukhtyz9UixUa1rWzE4zChSvyqIK0uA-XtleeC5WOII1DC3I)
* [LeaderBoard: StateOfTheArt.ai](https://www.stateoftheart.ai/) 
* [Paperwithcode](https://paperswithcode.com/)
* [Benchmarks.AI](https://benchmarks.ai/)
* 🌠 [DAVIAN Lab. Seminar List](https://github.com/awesome-davian/Paper-study)
* 🌸 https://github.com/jungwoo-ha/WeeklyArxivTalk
* https://github.com/sangyun884/Diffusion-Models-Seminar
* https://github.com/labmlai/annotated_deep_learning_paper_implementations
* Pyon 2021 머신러닝 엔지니어 커리어 로드맵: https://youtu.be/XM4hBpSylpM

## [PyTorch](pytorch.org)
* [KAIST 딥러닝 홀로서기 세미나 2019 Pytorch](https://github.com/heartcored98/Standalone-DeepLearning)
* [convNet.pytorch - training example ](https://github.com/eladhoffer/convNet.pytorch)
* [Pytorch로 시작하는 딥러닝](http://taewan.kim/tutorial_manual/dl_pytorch/)
* [PyTorch Deep Learning by Yan Lecun & Alfredo Canziani]
    - 강의 슬라이드: https://github.com/Atcold/pytorch-Deep-Learning/tree/master/slides
    - 동영상: https://www.youtube.com/playlist?list=PLLHTzKZzVU9eaEyErdV26ikyolxOsz6mq
    - GitHub(Jupyter Notebook): https://github.com/Atcold/pytorch-Deep-Learning
* [Everything You Need To Know About Saving Weights In PyTorch](https://medium.com/@animesh7pointer/everything-you-need-to-know-about-saving-weights-in-pytorch-572651f3f8de)
* [pytorch-how-and-when-to-use-module-sequential-modulelist-and-moduledict](https://towardsdatascience.com/pytorch-how-and-when-to-use-module-sequential-modulelist-and-moduledict-7a54597b5f17)
* [pytorch Autograd](https://teamdable.github.io/techblog/PyTorch-Autograd?fbclid=IwAR0aqsFKGV-fXIUyZdD7nwr2QI9GUDeX_kiW9xqLyaup2E5EU4-FCbPP1q8)
* [Reproducible PyTorch를 위한 randomness 올바르게 제어하기!](https://hoya012.github.io/blog/reproducible_pytorch/?fbclid=IwAR0MCyMMw-Q1gcrE8HIoVSk842ict52DhoswoWBqzjd1tdG0lq4BXzwk_IE)
* [PyTorch Multi-GPU 제대로 학습하기](https://medium.com/daangn/pytorch-multi-gpu-%ED%95%99%EC%8A%B5-%EC%A0%9C%EB%8C%80%EB%A1%9C-%ED%95%98%EA%B8%B0-27270617936b)
* [albumentations - fast image augmentation library 소개 및 사용법 Tutorial](https://hoya012.github.io/blog/albumentation_tutorial/)
* [2022_the_annotated_transformer](https://github.com/serotoninpm/2022_the_annotated_transformer)

---
## AutoML
* 🥇 [**pycaret**](https://pycaret.org/)
* [**Awesome-NAS**](https://github.com/D-X-Y/Awesome-NAS)
* [**Awesome-AutoML-Papers**](https://github.com/hibayesian/awesome-automl-papers)
* [awesome-AutoML-and-Lightweight-Models](https://github.com/guan-yuan/awesome-AutoML-and-Lightweight-Models)
* [Literature on Neural Architecture Search](https://www.automl.org/automl/literature-on-neural-architecture-search/)
* [An Overview of Google's Work and AutoML and Future Directions / ICML 2019](https://slideslive.com/38917182/an-overview-of-googles-work-on-automl-and-future-directions) 
* [Using Optuna to Optimize PyTorch Ignite Hyperparameters](https://medium.com/pytorch/using-optuna-to-optimize-pytorch-ignite-hyperparameters-626ffe6d4783)
* [Catalyst 101 — Accelerated PyTorch](https://medium.com/pytorch/catalyst-101-accelerated-pytorch-bd766a556d92)
* [NeurIPS 2021, Amazon Benchmarking Multimodal AutoML for Tabular Data with Text Fields](https://arxiv.org/abs/2111.02705)


## GNN
* [dgl](https://github.com/dmlc/dgl)
* [CS224W: Machine Learning with Graphs Stanford / Winter 2021](http://web.stanford.edu/class/cs224w/)
  * https://youtube.com/playlist?list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn 
* [Deep-GCNS](https://sites.google.com/view/deep-gcns/home)
* Intro to graph neural networks: https://youtu.be/8owQBFAHw7E

## XAI, SHAP
* https://aims.cs.washington.edu/research 
* [Explainable AI for Trees_ From Local Explanations to Global Understanding, Scott M. Lundberg et al., 2019](https://arxiv.org/abs/1905.04610) 
* DBSM XAI Seminar 
  1. https://www.youtube.com/watch?v=Grc7egfZP84
  2. NIPS2020 ON CONCEPT-BASED EXPLANATIONS IN DEEP NEURAL NETWORKS https://www.youtube.com/watch?v=-l8vqkCu91M 
## MLOps
* https://github.com/graviraja/MLOps-Basics 


---

# 5. Tools: LaTeX / Power Point / Excel / etc. 
## LaTeX  
* [Overleaf Main](https://www.overleaf.com/) & [Tutorial1](https://ko.overleaf.com/learn/latex/Main_Page) &[Tutorial2](https://www.dropbox.com/sh/x6bc2yik5x7w81u/AABG3tBJTkVss9hlpYjwm2MJa?dl=0) & [Tips1](https://github.com/Wookai/paper-tips-and-tricks)  & [LaTeX using vim](https://castel.dev/post/lecture-notes-1/)
* [LaTeX Table Generator](https://www.tablesgenerator.com/#)
``` 
% Rotaing Table: use `sidewaystable` from the `rotating` package
\usepackage{rotating}

\begin{sidewaystable}
    \centering
    \caption{Your caption here}
   \begin{tabular}{ll}
    First First & First Second\\
    Second First & Second Second
    \end{tabular}
\end{sidewaystable}
```

* [LaTeX Color](http://latexcolor.com/)

```
% Definition on the main file
\definecolor{applegreen}{rgb}{0.55, 0.71, 0.0}
\definecolor{azure(colorwheel)}{rgb}{0.0, 0.5, 1.0}

\newcommand{\rone}[1]{\textcolor{applegreen}{#1}}
\newcommand{\sh}[1]{\textcolor{azure(colorwheel)}{[SH: #1]}}
\newcommand{\shrev}[2]{\textcolor{azure(colorwheel)}{\sout{#1}[SH: #2]}}

% How to use it 
\rone{Test} 
\shk{the}
\shkrev{conformable}{their respective} output
```
* [LaTeX Link Color](https://tex.stackexchange.com/questions/525261/better-default-colors-for-hyperref-links)
```
\usepackage{hyperref} 
\hypersetup{ colorlinks=false, linkcolor=red, filecolor=magenta, urlcolor=cyan, citecolor=green }
```
* [LaTeX Symbols1](https://oeis.org/wiki/List_of_LaTeX_mathematical_symbols) & [LaTex Symbols2](https://jjycjnmath.tistory.com/117)
* In a math environment, LaTeX ignores the spaces you type and puts in the spacing that it thinks is best. LaTeX formats mathematics the way it's done in mathematics texts. If you want different spacing, LaTeX provides the following four commands for use in math mode:
```
\; - a thick space
\: - a medium space
\, - a thin space
\! - a negative thin space
```
---
## Other Tools
* [arxive - Chrome 웹 스토어 (google.com) arxive 논문 저장용이](https://chrome.google.com/webstore/detail/arxive/hkoblclipggkhhbllgefhnbjdcajmelh) 
* [PowerPoint](https://www.inflearn.com/course/%ED%8C%8C%EC%9B%8C%ED%8F%AC%EC%9D%B8%ED%8A%B8-%EA%B0%95%EC%A2%8C-quick-start/)
* [PPT 만들기: 생각부터 PPT 문서까지 전부 보여드립니다!](https://youtu.be/TCNioTWZWCQ) 
* [Excel](https://www.inflearn.com/course/%EC%97%91%EC%85%80-%EA%B0%95%EC%A2%8C/) & [엑셀 대시보드 만들기](https://www.youtube.com/watch?v=bDOG_uzn0_g)
* [WaveDrom: Digital Timing Diagram](https://wavedrom.com/) & [관련](https://dreamsailor.tistory.com/5)
* [Draw.io: visio 대안 무료 Drawing Program](https://www.draw.io/)  &  [관련](https://blog.naver.com/PostView.nhn?blogId=julian_dev&logNo=221461148445&parentCategoryNo=&categoryNo=7&viewDate=&isShowPopularPosts=true&from=search)
* [Markdown문법1](https://heropy.blog/2017/09/30/markdown/) & [Markdown문법2](https://blog.kalkin7.com/2014/02/05/wordpress-markdown-quick-reference-for-koreans/) & [Markdown문법3](http://taewan.kim/post/markdown/#comment) & [Markdown TongDal](https://github.com/zeuseyera/Markdown_TongDal-kr)
* [ReadMe MD Generator](https://github.com/kefranabg/readme-md-generator)
* [MkDocs: Project documentation with Markdown](https://blog.naver.com/doksg/221986849004)
* [Github Extensions](https://www.secmem.org/blog/2019/10/20/useful-chrome-extensions-for-github/)
* [CV Template](https://github.com/kim-sunghoon/online-cv/tree/master) & [개인 홈페이지 만들기](https://kinetic.codes/2020/03/06/build-blog-with-hexo-github/)
* [Pronunciation - Sounds American Channel](https://www.youtube.com/channel/UC-MSYk9R94F3TMuKAnQ7dDg/playlists)
* [브릿센트 x 영국영어](https://www.youtube.com/channel/UCq0pVPNYdDWQk1iTS4jTk2w)
* [Learn English with Emma](https://www.youtube.com/user/EnglishTeacherEmma)
* [Brave browser](https://brave.com/ko/)
--- 
## ETC. 
* [대학원생 때 알았더라면 좋았을 것들](http://gradschoolstory.net/)
* [일 잘하는 사람의 보고서 작성법 | 까이기 딱 좋은 보고서 피하기](https://www.youtube.com/watch?v=iFyxYmUHolY) 
* [How to write a good review: CVPR 2020 Tutorial](https://www.youtube.com/watch?v=W1zPtTt43LI&feature=youtu.be&fbclid=IwAR2PLlRaxAAsLXfbRqsSY8pw6kHY5UEjWj27sySMeLsVQ93Tq9otQQ0ZyjA)
* [how-machine-learning-teams-share-and-reuse-features](https://www.tecton.ai/blog/how-machine-learning-teams-share-and-reuse-features/)
* [인재가 떠나는 조직의 공통점 9가지](https://www.ciokorea.com/news/138296)





<!--
* [웃는 얼굴에 속지 마라! 내 커리어에 치명적인 ‘독버섯 상사’ 감별 법](https://media.fastcampus.co.kr/insight/toxanium_boss/)
* [퇴사 결정을 내려야할 때는?](https://www.youtube.com/watch?v=vqwY2SwkQ2Q) | [퇴사 제대로 하는 법](https://youtu.be/tKmmJEb-QFg)
* [거절 잘하는 법](https://youtu.be/rzRGGh9rcCQ)
* [잠이 안 깨고 항상 피곤할때 해결법](https://www.youtube.com/watch?v=30OadDaCbrA)
-->
