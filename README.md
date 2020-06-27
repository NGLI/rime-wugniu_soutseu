# 蘇州吳語拼音輸入方案

配方：℞ **NGLI/rime-wugniu_soutseu**

基於 [Rime](https://rime.im/) 的蘇州吳語拼音輸入方案。

拼音方案爲 [吳語學堂式拼音](https://github.com/NGLI/rime-wugniu_soutseu#音系及拼音方案)，同時兼容 [吳語協會式拼音](http://wu-chinese.com/romanization/)。

## 音系及拼音方案

### 聲母

|          |  清不送氣音  |    清送氣音    |    濁音     |  鼻音/邊音  |   清擦音    |     濁擦音      |
| :------: | :----------: | :------------: | :---------: | :---------: | :---------: |   :---------:   |
| **脣音** |  p \[p\] 北  |  ph \[pʰ\] 潑  | b \[b\] 蔔  | m \[m\] 摸  | f \[f\] 夫  |   v \[v\] 舞    |
| **齒齦** |  t \[t\] 得  |  th \[tʰ\] 脫  | d \[d\] 奪  | n \[n\] 諾  |             |                 |
| **齒齦** |              |                |             | l \[l\] 勒  |             |                 |
| **齒齦** | ts \[ts\] 資 | tsh \[tsʰ\] 次 |             |             | s \[s\] 絲  |   z \[z\] 字    |
| **齦齶** | c \[tɕ\] 機  | ch \[tɕʰ\] 期  | j \[dʑ\] 其 | gn \[ȵ\] 擬 | sh \[ɕ\] 希 |                 |
| **軟齶** |  k \[k\] 葛  |  kh \[kʰ\] 克  | g \[ɡ\] 箇  | ng \[ŋ\] 魚 |             |                 |
| **聲門** |  / \[\] 阿   |                |             |             | h \[h\] 黑  | gh/y/w \[ɦ\] 合 |

### 韻母

|     開口      |      齊齒       |      合口       |       撮口       |
| :-----------: | :-------------: | :-------------: | :--------------: |
|  y \[ɿ\] 絲   |   i \[iⱼ\] 衣   |   u \[u\] 無    |   iu \[yⱼ\] 於   |
|  yu \[ɥ\] 除  |                 |                 |                  |
|  a \[a\] 哈   |  ia \[ia\] 亞   |  ua \[ua\] 娃   |                  |
|  o \[o\] 下   |  io \[io\] 靴   |                 |                  |
| ou \[əu\] 河  |                 |                 |                  |
|  e \[ᴇ\] 愛   |  ue \[uᴇ\] 筷   |                 |                  |
|  au \[æ\] 奧  |  iau \[iæ\] 要  |                 |                  |
| eu \[øʏ\] 歐  |  ieu \[y\] 優   |                 |                  |
|               |  ie \[i\] 煙    |                 |                  |
|  oe \[ø\] 安  |  ioe \[iø\] 淵  |  uoe \[uø\] 碗  |                  |
| en \[ən\] 恩  |  in \[in\] 因   | uen \[uən\] 溫  |  iun \[yn\] 雲   |
|  an \[ã\] 亨  |  ian \[iã\] 陽  |  uan \[uã\] 橫  |                  |
| aon \[ɑ̃\] 昂  | iaon \[iɑ̃\] 旺  | uaon \[uɑ̃\] 黃  |                  |
| on \[oŋ\] 翁  | ion \[ioŋ\] 雍  |                 |                  |
| aeq \[aʔ\] 鴨 | iaeq \[iaʔ\] 俠 | uaeq \[uaʔ\] 劃 | iuaeq \[yaʔ\] 曰 |
| aq \[ɑʔ\] 額  | iaq \[iɑʔ\] 藥  |                 |                  |
| oq \[oʔ\] 惡  | ioq \[ioʔ\] 樂  |                 |                  |
| eq \[əʔ\] 遏  |  iq \[iəʔ\] 一  | ueq \[uəʔ\] 活  |  iuq \[yəʔ\] 穴  |
| er \[əl\] 而  |                 |                 |                  |
|  m \[m\] 嘸   |                 |                 |                  |
|  n \[n\] 唔   |                 |                 |                  |
|  ng \[ŋ\] 魚  |                 |                 |                  |

### 單字調

| 拼音 | 調值 | 調類 |
| :--: | :--: | :--: |
|  1   |  44  | 陰平 |
|  2   | 223  | 陽平 |
|  3   |  51  | 陰上 |
|  4   | 231  | 陽上 |
|  5   | 523  | 陰去 |
|  7   |  43  | 陰入 |
|  8   |  23  | 陽入 |

聲母 \[ɦ\] 後面接韻母 i 或 i 介音時，拼作 yi 或 y- 。後面接韻母 iu 或 iu 介音時，拼作 yu-。後面接韻母 u 或 u 介音時，拼作 wu 或 w-。其餘情形拼寫爲 gh。

韻母 i 和韻母 ie 在資料中多記爲 \[i\] 和 \[iɪ\]。但在現存的口音中，i 韻有擦化而 ie 韻無，二者實際爲擦化與不擦化的對立。各類資料也對此有說明，故本處據實際口音記作 \[iⱼ\] 和 \[i\]。iu 韻和 ioe 韻同理記作 \[yⱼ\] 和 \[y\]。

## 安裝方法

- [Windows](https://ngli.github.io/安装方法/Windows.html)
- [macOS](https://ngli.github.io/安装方法/macOS.html)
- [Linux](https://ngli.github.io/安装方法/Linux.html)
- [Android](https://ngli.github.io/安装方法/Android.html)
- [iOS](https://ngli.github.io/安装方法/iOS.html)

## 使用

- [模糊音](https://ngli.github.io/使用/模糊音.html)
- [輸入提示](https://ngli.github.io/使用/输入提示.html)
- [反查](https://ngli.github.io/使用/反查.html)

## 拼音教程

https://www.bilibili.com/video/BV1gp411d7ct

https://www.bilibili.com/video/BV16x411B71T

## 參考資料

汪平：《标准苏州音手册》，齐鲁书社，2007

## 字詞查詢

https://www.wugniu.com/

## 鳴謝

- [Rime](https://rime.im/)
- [Trime](https://github.com/osfans/trime)
- [iRime](https://github.com/jimmy54/iRime)

## 聯繫

蘇白學堂：

- 微信公衆號：class_sz

[吳語學堂](https://www.wugniu.com/)：

- QQ羣：955201855
- 微信公衆號：wugniu_com
- 微博：[吴语学堂微博](https://weibo.com/u/6541762299)
