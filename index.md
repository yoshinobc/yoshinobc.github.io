---
layout: home
title: Takumi Tanabe
description: 田邊拓実
---

## Personal Information

* Name : Takumi Tanabe(田邊拓実)
* DOB : 1998/05/27

## Education

* 2017.04 : 筑波大学 情報学群 情報科学類 入学
* 2021.03 : 筑波大学 情報学群 情報科学類 卒業
* 2021.04 : 筑波大学院 情報理工学位プログラム 入学
* 2023.03 : 筑波大学院 情報理工学位プログラム 修了

## Publications

* Neurips 2022, Takumi Tanabe, Rei Sato, Kazuto Fukuchi, Jun Sakuma, Youhei Akimoto Max-Min Off-Policy Actor-Critic Method Focusing on Worst-Case Robustness to Model Misspecification [[link]](https://nips.cc/Conferences/2022/Schedule?showEvent=53532)
* 2022年度人工知能学会, 田邊 拓実, 佐藤 怜, 福地 一斗, 佐久間 淳, 秋本 洋平 モデル化誤差に頑健な Max-Min Off-Policy Actor-Critic [[link]](https://www.jstage.jst.go.jp/article/pjsai/JSAI2022/0/JSAI2022_2C5GS203/_article/-char/ja/)
* GECCO 2021 full paper, Takumi Tanabe, Kazuto Fukuchi, Jun Sakuma, Youhei Akimoto Level Generation for Angry Birds with Sequential VAE and Latent Variable Evolution [[link]](https://dl.acm.org/doi/10.1145/3449639.3459290)
* 2021年度人工知能学会,　田邊 拓実, 福地 一斗, 佐久間 淳, 秋本 洋平 Sequential Variational Autoencoderを用いたAngry Birdsのステージ生成 [[link]](https://www.jstage.jst.go.jp/article/pjsai/JSAI2021/0/JSAI2021_3G4GS2i04/_article/-char/ja/)

## Research Contents

### Procedural Contents Generation [[link]](https://arxiv.org/abs/2104.06106)

-----------------------------------------------------------------------------

ビデオゲームコンテンツの設計には，ゲームに関する多くの知識や経験が必要であるため，手作業でコンテンツを設計することはコストのかかる作業である． Procedural
Contents Generation (PCG)とは，プログラムを使用してゲームのコンテンツを自動生成する技術であり，上記のコストを最小限に抑えることができる． ここでは，ゲームのステージをビデオゲームコンテンツの一例とする．一般的なPCG手法では，生成されるステージが(1)プレイ可能であるか，(2)美的センスがあるか，などの暗黙の制約を満たす必要があり，この制約を満たすステージを生成するプログラムを開発することにもゲームに関する知識や経験が必要になる．そこで，既存のコンテンツをデータセットとし，機械学習モデルを用いてステージを生成することで，そのゲームに関する知識や経験がなくても誰でもステージを生成できる手法(PCGML)が注目されている．しかし，ビデオゲーム分野では，データセットとして使用できるデータ自体が少ないこともあり，プレイ可能なステージを生成することは困難である． 本研究では，特にプレイ可能なステージを生成するのが困難な「Angry Birds」というゲームを対象とし、時系列ベースのエンコーディング手法を提案し、Sequential VAEを用いることでジェネレータの学習を行った。そして、ジェネレータの入力空間である潜在空間をCMAESを用いて最適化することで、「プレイ可能である」という制約を常に満たしながら望ましい構造を持つステージの探索に成功した。

### Robust Reinforcement Learning [[link]](https://arxiv.org/abs/2211.03413)

-----------------------------------------------------------------------------

現実世界で強化学習を用いて方策を学習することは高コストかつ高リスクであるため，シミュレーション環境で学習した方策を現実世界に転移させるという試みがしばしば行われている．しかしながら，シミュレーション環境は現実世界を完全に模倣できるわけではなく，現実世界とシミュレーション環境の間にはモデル化誤差が生じる．このモデル化誤差が原因で，シミュレーション環境で高性能な方策を獲得したとしても，現実世界では方策の性能が著しく劣化するという問題が複数報告されている．本研究では，不確実性パラメータによってモデル化誤差が生じるシミュレーション環境と現実世界の不確実性パラメータが存在する空間が既知であるという設定に着目する．現実世界が不確実性パラメータ空間に含まれている場合に現実世界での方策の性能の下界を保証するために，不確実性パラメータ空間に対する最悪ケース性能の最適化を目指す．最悪ケース性能に対して最適化された方策を獲得するために，強化学習の枠組みの中で同時勾配降下法を用いてmax-min最適化を行うMax-Min Twin Delayed Deep Deterministic Policy Gradient Algorithm（M2TD3）を提案する．Multi-Joint dynamics with Contact (MuJoCo)を用いた実験により，M2TD3は多くのシナリオでベースライン手法よりも優れた最悪ケース性能を示す方策の獲得に成功することを示した．

## Awards

* 2020.03 : 筑波大学 情報特別演習 優秀賞
* 2021.03 : 茗溪会賞 [[link]](https://www.coins.tsukuba.ac.jp/award/)
* 2021.07 : 2021年度 人工知能学会学生奨励賞 [[link]](https://www.ai-gakkai.or.jp/about/award/jsai_award-conf-s/)
* 2021.07 : Genetic and Evolutionary Computation Conference 2021 Real World Application Track Best Paper
            Nomination [[link]](https://gecco-2021.sigevo.org/Best-Paper-Nominations)
* 2022.01 : 2021年度 enPiT 筑波大学 成果発表会 優秀賞 [[Code]](https://github.com/enpitut2021/chimimoryo_autumn) [[Slide]](https://docs.google.com/presentation/d/19LOgfusJPz2zKUi5XlY2GovOB502de7kg8dkmTaCPzs/edit#slide=id.g119750c39e8_0_29)
* 2022.03 : 2021年度　情報理工学位PL特別表彰
* 2023.03 : 2022年度　情報理工学位PL表彰

## Part-time job and Internship

* 2018~2019 : 株式会社SPJ
* 2019 : 筑波大学 研究補助
* 2019 : 株式会社Gunosy
* 2019 : 株式会社サイバーエージェント
* 2019~2021 : フューチャーアーキテクト株式会社
* 2021 : 株式会社Preferred Networks
* 2021 : 株式会社DeNA
* 2021 : 株式会社サイバーエージェント
* 2022 : 株式会社博報堂

## Projects

### Chrome Extension [[link]](https://chrome.google.com/webstore/detail/pdf-translator/dnkjinhmoohpidjdgehjbglmgbngnknl)

このChrome拡張はPDF上でDeepLの翻訳結果を表示するChrome拡張である．毎週1万人弱のアクティブユーザーがいる．

### AIwolf Agent [[link]](https://github.com/yoshinobc/wolf-strategy)

これは，プログラムによって自動で人狼ゲームをプレイするエージェントである． ルールベースによって複数の性格のエージェントが実装されてる．

## Others

* 2020 : セキュリティキャンプ全国大会2020 エクスプロイト自動化ゼミ 修了
* 2021 : Kaggle RANZCR Clip - Catheter and Line Position Challenge (solo, silver, 65 / 1547 th)
* 2022 : Kaggle U.S. Patent Phrase to Phrase Matching (solo, silver, 49/1889 th)
* Atcoder Rating 816(緑)
