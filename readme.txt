labdcs is a DCS platform which integrates state-in-art open source software to provide the function of measuring and control. It is low-cost solutions for many applications because its control part can be coded by Modelica which can be compiled to executable program with free compiler,e,g, OpenModelica. It used the server and client structure, and real time data exchange is through memory database redis and the mechinics of publish and subscibe of message provided by redis is utilized to prevent the latency of data exchange.  GUI of configuration and running management,hmi and the function of history storage is provided. 
Nowadays there are various solutions like this.  ..... But what is special for labdcs is:
1 systematic definition of basic concept
2 value quality and timestamp with the point information, complete information is important for control algorithms  which may depend on the data quality
3 module structure , can be easily extended
4 memory database gives good performance
5 easily configuration of industrial bus ,current it gives the implementation example of Modbus TCP
6.  Modeling code is supported, can use abundant of modeling library for control,e,g blocks and state graph, and device libs for real time implementation. Then it can be easily used in fo control prototype construction and laboratory control system or eduction of control practice.
7 history function is given using postgresql database.
Now education users can obtain free use of labdcs.


软件下载地址：
链接：https://pan.baidu.com/s/169hfxP07st2dO7AAlA8K7w?pwd=8888 
提取码：8888 


交流QQ群：1012390630
教学视频： https://www.youku.com/profile/index/?spm=a2h0c.8166622.PhoneSokuUgc_1.1&uid=UNDM0MDYwNTk2NA==
或 进入优酷，搜索和关注labdcs

若使用labdcs软件发表论文，请引用该论文
[1]殷亮,蒋军成.基于代理的分布式过程控制Labdcs平台的开发[J].实验室研究与探索,2023,42(03):53-58+97.
