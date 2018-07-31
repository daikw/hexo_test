---
title: 難しいことを簡単に説明する指針。"Lie(s)-to-children"
date: 2018-08-01 00:20:15
tags: Qiita 原子構造
---

# 原子の構造を、子供に説明できますか？
僕は、だらだらと長い説明を聞いていることができません。飽きてしまうからです。

でも自分がいざ説明するとなると、途端に難しいですよね。

特に、複雑に入り混じった情報を何の知識もない子供に説明するときには、非常に難しさを感じます。


# 出会い

　PiCamera(RaspberryPiの純正カメラ）のAPIのドキュメントを読んでいるときに、次のような文章を見かけました。

> Many questions I receive regarding picamera are based on misunderstandings of how the camera works. This chapter attempts to correct those misunderstandings and gives the reader a basic description of the operation of the camera. The chapter deliberately follows a **lie-to-children** model, presenting first a technically inaccurate but useful model of the camera’s operation, then refining it closer to the truth later on.
>> 私が受け取った質問の多くは、カメラの動作の勘違いから生じたものでした。このチャプターでは、こういった勘違いを直すため、カメラの操作に関する初歩的な説明を試みます。このチャプターは非常に慎重に**lie-to-children**モデルに従って記述されます。つまり、技術的には間違っていても、カメラの操作については有用なモデルを初めに示した上で、後で正確な表現により近づけます。

[6. Camera Hardware — Picamera 1.13 Documentation](http://picamera.readthedocs.io/en/latest/fov.html)

どうやらこのドキュメントは、非常に厳密にある指針に基づいて構成されているようです。しかし、Lie-to-childrenモデルとはどのようなモデルなのでしょう？


# Lie-to-children  ー子供につく嘘ー
　とはいっても、モデルの中身はすでに上述の訳文に全て書かれています。つまり、lie-to-childrenとは、次のようなプロセスで行われる知識の伝達を意味します。

1. 間違ってはいる（嘘である）が、非常に分かりやすい仕方の説明を試みる。
2. その後、より正確な表現に近づける。

"Lie-to-children"についての初めての議論は、Jack Cohen と Ian Stewartの共著「The Collapse of Chaos」にて行われました。後に、その定義が、「The Science of Discworld (同共著：Terry Pratchett)」の中に見られます。

> A lie-to-children is a statement that is false, but which nevertheless leads the child’s mind towards a more accurate explanation, one that the child will only be able to appreciate if it has been primed with the lie.
>> lie-to-childrenは、間違ってはいるけれども、子供の心をより正確な表現に導いてくれるような
、そのlieをあらかじめ知ることによってようやく正しく理解できるようになるような、そんな表現です。



# Lie-to-childrenの好例： 原子核内の、電子-陽子系の説明

　化学・物理では、原子について習います。中学生程度では、まず次の図のようなボーアモデルを学びます。
![558px-Electron_shell_005_Boron.svg_-279x300.png](https://qiita-image-store.s3.amazonaws.com/0/119807/c50dca78-171d-ddbf-9a3d-b679c366e338.png "Electron shells around a Boron atom. Image licensed under creative commons via Wikimedia Commons")

ボーアモデルでは、電子は原子核の周りを回っていると説明します。これはまるで、火星や地球が太陽の周りを回っている様子に似ています。それぞれの惑星（電子）は、太陽（原子核）からの距離が異なる軌道に乗って動いています。

このモデルを学んだ後で、シュレディンガー方程式についての理解を深めることができたら、電子は惑星のように実体として存在しているという嘘や、電子が同じ軌道に８つまでという嘘に気づくことになるでしょう。
その後に、より正確なモデルとして、電子雲の形状がどのようになっているのかや、電子軌道を定めるパウリの排他原理を学ぶことになるでしょう。

![800px-Single_electron_orbitals-300x176.jpg](https://qiita-image-store.s3.amazonaws.com/0/119807/edf58343-12e1-d888-2e2a-505b8272d8af.jpeg "Single electron orbitals. Image licensed under creative commons via Wikimedia Commons")



# Lie-to-childrenの抱える問題

　どのようなモデルにも、問題があります。

先ほどのJack Cohen と Ian Stewartはのちの書籍(Evolving the Alien: The Science of Extraterrestrial Life)において、Lie-to-childrenを教育のために用いる場合には副作用があると言っているようです。

>Within the work, the authors were critical of use of lie-to-children as an educational methodology which had an unfortunate side-effect of reducing complex science concepts to overly simplified explanations.

（原著を読んでいないので、wikipediaの文章を引用しています)


僕個人的にも、このモデルを採用する際には、「これから話すことは、非常に簡略化したもので、正確ではない」ことを強く言う必要があるだろうと感じています。とはいえ、最も強力な情報伝達の手段の一つであることは揺るぎないのではないでしょうか。


# 参考文献
[Lie-to-children - Wikipedia](https://en.wikipedia.org/wiki/Lie-to-children)

[Scientific Scribbles >> Lies to children](https://web.archive.org/web/20150712155148/https://blogs.unimelb.edu.au/sciencecommunication/2012/08/17/lies-to-children/)

[6. Camera Hardware — Picamera 1.13 Documentation](http://picamera.readthedocs.io/en/latest/fov.html)

# 最後に

調べていて、この記事を思い出しました。

[頭がいい人は「分かりやすい説明」をする時、何を考えているのか](http://blog.tinect.jp/?p=35489)
