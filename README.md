# talk-about
这里是头脑风暴

## milestone
nothing

## mud 2021-10-13
1. 今天看了一些关于文字游戏的文章，感觉在原始的原宇宙时期，可以使用这种落后的形势来进行交互，一是成本简单，二是怀旧
2. 相对于图片的nft形式，mud的文字更贴近于nft的数据本质
3. 参考[batmud](https://www.bat.org/play/creation)
4. 还有像roguelike一样的，死了重来的hardcore版本。当然hardcore版本的奖励会更加丰富。
5. 组团交互等需要考虑实现方式
6. [论坛](https://trow.cc/board/index.php?showforum=122)
7. [知乎上的图文结合](https://trow.cc/board/index.php?showforum=122)
8. 关于客户端，好像有文字和带图的两种形式
9. 鉴于区块链的机制，所以还是回合制的形式
10. Graphical泥巴 相当于添加了图片的mud，比如可以将带有图片的nft作为图中的元素
11. [资料](https://zhuanlan.zhihu.com/p/22094547)
12. [一个财博朋克类型的](https://en.wikipedia.org/wiki/Habitat_(video_game))

### 地图
[https://store.steampowered.com/app/616920/BatMUD/](https://store.steampowered.com/app/616920/BatMUD/)
地图可以参考上面链接里的，采用大+小的形式来展示，大地图用ascii码，小地图用图片

## 关于世界和机制的一些想法
1. 由于区块链的共识性质，所以无法实时游戏，可以类似5s刷新一次世界动态的形式展示当前世界状态或者范围内用户的位置等。类似雷达图，每隔5s（出块时间）刷新下最新状态
2. 关于token和消耗机制：比如每天（24h）可以获取一定数量的token来执行行为（类似消耗gas，也类似现在手游中的行动点），当行为点（免费token）消耗完之后，只能通过重新充值token来增加行动点，但是增加的比例会越来越少（或者不变，可以作为一种机制）
3. 存在死亡的账户，死亡后会有一些惩罚或者保护机制

## startup-2021-09-10
1. 今天无意想到辐射4的后现代生存游戏，觉得和nft这种游戏比较契合，然后搜索了一下[wiki](https://zh.wikipedia.org/wiki/%E7%95%B0%E5%A1%B5%E9%A4%98%E7%94%9F%E7%B3%BB%E5%88%97), 从它的属性设计上感觉还是比较符合nft的设计的，于是想了一款可以用于交互的nft的废土风格游戏
2. 同时在搜索时获取了[地下城与勇士](https://zh.wikipedia.org/wiki/%E9%BE%99%E4%B8%8E%E5%9C%B0%E4%B8%8B%E5%9F%8E#%E5%8A%9B%E9%87%8F%EF%BC%88Strength%EF%BC%8CSTR%EF%BC%89)的灵感，也是比较契合的
3. 既然是废土，又是多交互，可以参考`这是我的战争`这个游戏，比如世界资源是有限的，有的人占领了一些资源，其他的人可以选择各自的行为与方式
