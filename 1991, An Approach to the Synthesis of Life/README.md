# An Approach to the Synthesis of Life
Thomas S. Ray,

Artificial Life II, 1991
<!-- Author, year and journal infomations. -->

<!-- Link to the paper -->

http://tomray.me/pubs/alife2/Ray1991AnApproachToTheSynthesisOfLife.pdf

## Motivation
<!-- What issues or problems did they try to solve? -->
<!-- What was lacking in existing research? -->

現在の生物の研究は、"地球上の生物"というn=1のサンプルに依存し、その環境制約を受けている。
生命をコンピュータ上で生成することが出来れば、それは生命の理解に大いに役立つ。

既存の進化シミュレーションは、open-endな仕組みを採用していないものが多い。
また生命の生成を目指す既存の研究は、"生命の起源"の再現を目指したものがほとんどである。

本研究では、"生命の起源"ではなく"カンブリア爆発"に見られるような多様性の獲得を目指す。

## Method
<!-- ![fig1](img/fig1.png) -->
<!-- What system did they create? Why did they think that the system design was well jusified? -->
<!-- What algorithm did they create? Why did they consider that the algorithm design was good enough? -->
<!-- What kind of surveys did they do? How did they justify their study design? -->
<!-- What experiments did they conduct? How did they justify their experimenal design? -->

Tierra Simulatorを作成した。
CPUをエネルギーに、メモリを空間に見立ててデジタル生物を進化させた。

仮想マシン上で実行させることで、デジタル生物がウイルス化しても問題ないようにした。
DNA, RNA, タンパク質の仕組み(命令語の少なさ、アドレッシング機構)を取り入れた言語Tierranを開発した。
Tierraの実行を担うTierran OSを開発した(細胞としてのメモリ割り当て/CPU時間の割り当て:Slicer/死の実装:Reaper/突然変異の実装)。

## Insight
<!-- What results did they obtain? Under what conditions did it work, and under what conditions did it not work? -->
<!-- What are the new findings? What are the findings that could be used in other applications or systems? -->

進化の結果、下記の特徴を持つデジタル生物が生まれた。

- パラサイト
- パラサイトへの免疫
- パラサイトへの免疫回避
- ハイパーパラサイト(パラサイトへの便乗)
- 社会性ハイパーパラサイト
- チーター(社会性ハイパーパラサイトを出し抜く)

## Unknown
<!-- What is still unknown or unresolved? -->

- "molecular, "cellular", "ecological"という階層を反映させた進化モデル。
- Reaperではなく"捕食"による淘汰。

## Reference
<!-- Which of the papers listed in the related studies are close and which you have not read? -->
<!-- Which of the related papers should I read next? -->

<!-- This template format refenrece: -->
<!-- https://iis-lab.org/misc/paperreading/ -->

- Evolutionary learning in the 2D artificial life system ‘Avida’  
Chris Adami, C Titus Brown, Artificial Life IV, 1994  
https://arxiv.org/pdf/adap-org/9405003.pdf
