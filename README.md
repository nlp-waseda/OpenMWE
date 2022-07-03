# OpenMWE Corpus


## Corpus Specification

The corpus is designed for the idiom token identification task. That is, each example sentence in the corpus is annotated with a label that indicates whether the corresponding phrase in an example is used as an idiom or a literal phrase. We call the former the positive example and the latter the negative example. More specifically, the corpus consists of lines that each represent one example. A line consists of the following information.

- Label: indicates whether the example is positive or negative. The label I is for positive ones and L is for negative ones.
- ID: indicates which idiom is included in the example. In this study, each idiom has a unique number.
- Lemma: also shows the idiom in the example. We gave each idiom its canonical form.
- Example: is the example itself. Idiom constituents are marked with "<" and ">".

As for the corpus size, we basically annotated examples until they amount to 1,000 for each idiom, regardless of the proportion of idioms and literal phrases. (For some idioms, we annotated more than 1,000 examples.) In the case of the shortage of original data, we annotated examples as many as possible.

The original data came from the Web corpus of Japanese.

Characters are euc-jp encoded.


## Corpus Summary

The corpus consists of 102,334 examples. Below is a summry that shows the number of examples, ID, and lemma for each idiom.

- Class C

```
   3034 3018 右から左
   2357 3047 水を差す
   1884 3037 水と油
    834 0262 一から十まで
    341 1379 事によると
    129 2700 火が消えたよう
    121 0381 芋を洗うよう
     49 2521 歯が抜けたよう
     35 3265 目と鼻の間
     29 2248 とらの子
      2 0416 牛の歩み
```

- Class D

```
    1320 2677 腹を割る
    1309 2584 鼻が高い
    1279 3191 胸を痛める
    1218 0161 網を張る
    1200 0150 脂が乗る
    1155 3471 弓を引く
    1096 3170 胸が詰まる
    1016 2461 熱しやすく冷めやすい
     988 2459 熱が冷める
     982 0390 色を失う
     970 2463 熱を上げる
     965 2770 人を食う
     961 3039 水に流す
     960 0648 尾を引く
     959 2473 根を下ろす
     958 2967 幕が開く
     958 0106 頭を痛める
     957 0738 型にはまる
     954 2075 手に乗る
     952 2785 火花を散らす
     950 0114 頭をもたげる
     949 2166 峠を越す
     945 2621 鼻を鳴らす
     942 0756 肩を並べる
     940 1153 首をひねる
     940 0198 息が詰まる
     939 2475 根を張る
     936 0101 頭が下がる
     935 2974 幕を開ける
     933 3468 指をくわえる
     931 3164 胸が痛む
     931 2976 幕を閉じる
     929 0035 あぐらをかく
     923 1141 首が回らない
     921 3132 実を結ぶ
     919 1864 棚に上げる
     918 2937 骨が折れる
     913 2033 手がない
     912 2947 骨を埋める
     910 0080 足を洗う
     907 2341 波に乗る
     906 0060 足が速い
     904 1947 宙に浮く
     904 0107 頭を抱える
     897 0088 足を伸ばす
     894 2125 手を延ばす
     890 2949 骨を折る
     888 3236 目がない
     888 0689 顔を出す
     884 1738 背を向ける
     880 2018 手が上がる
     873 0090 足を引っ張る
     866 3231 芽が出る
     862 2555 バスに乗り遅れる
     861 3193 胸を打つ
     844 2464 熱を入れる
     839 0436 腕が上がる
     837 0057 足が出る
     836 1897 血が通う
     831 3256 メスを入れる
     826 1146 首を切る
     826 1100 唇をかむ
     821 3318 目を覆う
     821 3078 耳が痛い
     821 2128 手を広げる
     818 2100 手を合わせる
     812 1909 力を入れる
     803 2108 手を切る
     798 3628 輪を掛ける
     797 2121 手を取る
     793 3069 身に付ける
     789 2105 手を掛ける
     785 3085 耳にする
     777 3087 耳につく
     767 1120 口をとがらせる
     763 2037 手が離れる
     758 3337 目を付ける
     753 3338 目をつぶる
     752 2122 手を握る
     742 2620 鼻を突く
     741 2119 手を付ける
     738 3173 胸が膨らむ
     736 2102 手を打つ
     729 2264 泥を塗る
     728 2130 手を回す
     726 0079 足元を見る
     721 2580 バトンを渡す
     719 3279 目に入る
     699 3327 目を覚ます
     665 3598 訳は無い
     665 3084 耳に入れる
     656 0056 足が付く
     644 0773 角が取れる
     628 3225 目が覚める
     599 2101 手を入れる
     584 0151 油を売る
     582 3091 耳に入る
     580 2032 手が届く
     558 2604 鼻に付く
     531 2581 鼻息が荒い
     493 2623 花を持たせる
     462 2030 手が出ない
     430 1107 口を切る
     422 0342 一杯食う
     374 0098 頭が痛い
     362 0174 泡を食う
     343 0681 顔に泥を塗る
     332 0016 青筋を立てる
     328 2878 船をこぐ
     291 2684 歯を食い縛る
     280 2860 筆を入れる
     256 1988 土が付く
     246 3350 目を細くする
     208 0152 油を絞る
     175 1417 ごまをする
     157 2615 鼻を折る
     133 3143 虫がいい
     128 1687 図に当たる
     124 1526 しっぽをつかむ
     112 2265 泥を吐く
     111 2863 筆を加える
      99 1524 しっぽを出す
      92 0046 あごを出す
      65 1963 ちょうちんを持つ
      63 1194 けたが違う
      59 1096 くちばしを入れる
      42 1095 くちばしが黄色い
      37 0659 飼い犬に手をかまれる
      37 0414 動きが取れない
      34 2646 腹が太い
      33 3053 みそを付ける
      20 3533 らっぱを吹く
       8 3106 脈が有る
       8 1058 くさびを打ちこむ
       6 0072 足元に火が付く
```


## Licence

```
Copyright 2008, OpenMWE Developers
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

    * Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above
      copyright notice, this list of conditions and the following
      disclaimer in the documentation and/or other materials provided
      with the distribution.
    * Neither the name of OpenMWE Developers nor the names of its
      contributors may be used to endorse or promote products derived
      from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```


## Notice

Since we use the Web texts as source data, someone might request us to remove some examples from the corpus. In that case, we will ask the users of OpenMWE Corpus to do so.


## Developers

- Chikara Hashimoto
- Daisuke Kawahara


## Publications

* Compilation of an Idiom Example Database for Supervised Idiom Identification. Chikara Hashimoto and Daisuke Kawahara. Language Resources and Evaluation, Volume 43, Number 4, pp.355-384, 2009.

* Construction of an Idiom Corpus and its Application to Idiom Identification based on WSD incorporating Idiom-Specific Features. Chikara Hashimoto and Daisuke Kawahara. EMNLP 2008, Regular paper, Oral, pp.991-1000. 2008.

* Detecting Japanese Idioms with a Linguistically Rich Dictionary. Chikara Hashimoto, Satoshi Sato, and Takehito Utsuro. Language Resources and Evaluation: Special Issue on Asian Language Technology, Volume 40, Number 3-4, pp.243-252. 2006.

* Japanese Idiom Recognition: Drawing a Line between Literal and idiomatic Meanings. Chikara Hashimoto, Satoshi Sato, and Takehito Utsuro. COLING/ACL 2006 Poster, pp.353-360. 2006.


## Acknowledgments

This work was conducted as a part of the collaborative research project of Kyoto University and NTT Communication Science Laboratories.

The work was supported from NTT Communication Science Laboratories and JSPS Grants-in-Aid for Young Scientists (B) 19700141.

We would like to thank the members of the collaborative research group of Kyoto University and NTT Communication Science Laboratories and Francis Bond for their stimulating discussion. Our thanks go as well to Prof. Sato Satoshi, who kindly gave us the list of basic idioms of Japanese.


## ChangeLog

- v0.01 --> v0.02
  - The label changed from i/l to I/L.
  - Idiom constituents were marked with '<' and '>'.
  - Pornographic examples were removed automatically.
