---
description: Leetcode刷题整理
---

# Practice Order
https://www.cspiration.com/#/leetcodeClassification
 
[http://www.1point3acres.com/bbs/thread-224104-1-1.html](http://www.1point3acres.com/bbs/thread-224104-1-1.html)

## 刷题之道：

刷题  
链接：https://www.zhihu.com/question/31092580/answer/453117660  
来源：知乎  
  
第一遍刷题吃力非常正常。

当年自己第一遍刷的时候，特别痛苦。一天就3道题，持续了两个月吧。后来刷的多了，一天5道，再往后，一天10道，15道。刷了两遍后，一天可以30道也不累。以现在的水平，可以一天100道。毕竟很多题刷的太熟了，就是在打字。

简单说一下我认为的刷题几个阶段，这是上课时和学生说的：

* 1，第一遍：知道。直接看答案，不要自己想，了解所有最优解，方法技巧第一。做题套路，以印象为主。
* 2，第二遍：熟悉。过easy题，记住；做medium，重点题背，反复背。最简单会，大多不会。记住做题套路，以记住为主。
* 3，第三遍：做题。做easy题；做部分medium题，hard题有思路。夯实medium基础。熟练运用做题套路，以做题为主。
* 4，面经：做面经，开阔思路，了解出题形式。基础决定上层建筑，基础牢轻松，不牢就痛苦
* 5，第四遍以上：刷题。

其实我感觉，在前4个阶段，都不叫“刷题”，那是做题，在学习，只有在第四遍，才叫刷题。没有人一遍就会，大多数人都向快。直接做题，不管不顾基础知识。很多人连Segment Tree，BIT，Trie，Union Find这种数据结构都不懂，遇见就刷，自己想，怎么可能想的出来？

所以刷题最重要的，第一步，就是了解所有的数据结构，做题方法，基础算法。从基础数据结构HashMap，HashSet，到TreeSet，TreeMap，Deque，LinkedHashMap；到各种对刷题来说的基础算法，各种排序算法，DFS，BFS，Sliding Window，sweep line，等等。99%的人这些都没有学过，就直接做题，做两道就想类似的题自己能做出来。

如果刷题这么容易，那人人都能进Facebook，Google了。

不可能的。我告诉我学生的方法，第一遍就是看答案。在第一遍刷题的时候，很多题其实是一类方法，但自己做的时候并不知道，然后自己做不出来就感觉挫败，其实是方法不对。所以在第一遍的时候，就是在看答案，最优解，去知道什么是刷题，理解所有的算法，原理，套路。建立一个较为完整的刷题思维体系。这样才能在遇见不会的题，想法思路才能正，才能有感觉最优解的方向，否则想一上来做几个题自己就知道最优解了，不可能的。

这里多说两句。很多人反对第一遍刷题看答案，认为就是自己做。当年我第一遍刷题的时候，举几个例子。

LC 76 怎么想都想不到，看答案感觉这解法真厉害，做多了才发现，有一种方法叫Sliding Window。

LC 56，看了答案才知道，还有个扫描线算法。之前想了那么多，都是错误的方向。

LC 200，看似简单的dfs，bfs，最后才知道flood fill。。。

LC 215，quick select

这种情况我相信每个人都遇见过，还有数据结构不好时，TreeMap都不知道是啥，PriorityQueue也不知道怎么用，LinkedHashMap，没听过。

所以现在回想起来当年第一遍刷，感觉费了那么多时间想这些，真的是浪费时间，因为想题想思路是重要的，但不应该把时间花在想的是这些已有的固定方法数据结构上，如果做这道题之前就知道了数据结构，知道了算法，那么我至少应该有个想的方向。即使想错了，也能说，啊，这个问题应该用sliding window啊，而不是发现，哎，还有个这样的方法！还有这种数据结构叫TreeMap！

就像学数学，知道1，2，3，不知道4，5，6，那怎么能算出2+5呢？

**至少也应该把10个数认全再算加减乘除吧！**

所以我认为浪费时间在这个补基础的点，不值。

与其这样，还不如第一遍就看答案，以题带练，带补，**学习人家的最优解，建立思维体系，补数据结构，补算法知识**。而第二遍时，才是真正自己想。这样做，一点不耽误锻炼思维过程，锻炼逻辑基础。这是我刷了这么多题感悟到能最快刷题的方法，现阶段我认为没有之一。

而第二遍就是要自己想了，第一遍已经有了思维，现在就是要培养自己的做题能力了。很多题第二遍看感觉自己以前没做过，正常，没人能一遍记住。但这遍就需要自己先写答案，因为你很多已经有了大体的方向感和目标，自己多多少少能写出来一些。然后这边尝试自己写，加深印象。

第三遍就是再过一下，再熟练所有套路，就需要牢牢记住。第四遍我认为需要脱离lc，需要做面经了，看看公司面试是怎么出题的。如果你的目标是北美找工作的话。

另外不建议刷800，主刷前400，就够用了，毕竟，前400能刷完的，理解的了的，10中2-3个人而已。

其实这些东西说起来容易，做起来很难。 每一遍其实都挺痛苦的，需要一个循序渐进的过程。我不是什么天才，我到现在的水平，基本上全职刷题，上课只是副业，8-9个月的时间。以数量来看，留学两年多，刷题过3000。不重复的题，就做过过千了。后来我把lc前400题所有题解法录成视频，录了近半年。所以不是看到一个人刷题厉害怎么聪明，而是踏踏实实的努力。

**毕竟最快的捷径，就是没有捷径。**

当然也不是每个人需要做到这种程度。公司面试题，很多题难度不是那么高，很多人2，300最后运气好也进去了。但如果想看到一道题就有思路，就能写出来，想有这种硬实力，我认为，最少需要4，5个月的时间。

我也见过那种，天赋异禀的，有那种只刷了100多的，聊天发现想法特别正，我感觉自己两遍才能有那些总结过的想法。还有那种，交流能力极强的，60多，各种店面过，各种要hint去交流暴力解过的。但自己也说这样onsite肯定不行，也就是店面而已。

