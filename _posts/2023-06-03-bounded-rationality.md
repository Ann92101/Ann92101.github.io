---
layout: post
title: Bounded Rationality
date:   2023-06-03 09:01:00 -0700
image:  '/images/rational-post.jpg'
tags:   [Philosophy, Rationality, Bounded Rationality]
mathjax: true
---

# 有限理性

## 背景

经济学家 **Herbert A. Simon** 在1955年首次提出了有限理性这个概念[^fn1]，作为决策制定的数学和新古典经济模型中的概念替代，以反驳经济效益等同于理性的普遍观念。在当时现有的经济理论中，理性意味着当一个人在面对选择不同行动方案时，他们能够做出最优选择，被称为 **rationality as optimization** ， 西蒙的提议在推翻这种模型上产生了巨大影响。

西蒙认为现有的经济理解并不足以代表人们做出的决策。他提出有限理性的概念，以考虑到"包括人在内的有机体所实际拥有的信息获取和计算能力，以及这些有机体存在的环境类型。"换句话说，他希望他的理论能够考虑到**人们在做决策时可接触到的信息**，**人类思考能力的限制**，以及**环境的限制**，如时间。

在有限理性这个术语被提出之前，相关领域的研究其实已经开始了。**Maurice Allais** 在1953年完成的一项研究开始产生决策制定的非理性观念，因为他发现在给定的偏好下，个体并不总是选择最理性的决策，因此在经济预测中，理性的概念并不总是可靠的。

> "Boundedly rational agents experience limits in formulating and solving complex problems and in processing (receiving, storing, retrieving, transmitting) information."  
> <cite> Herbert A. Simon </cite>

西蒙提出由于因为情况的复杂性，人们用 **heuristics** 而不是严格的优化规则做决策。比如，在比较简单的情况下（例如井字游戏）和困难情况（例如国际象棋）中决策者使用的认知策略通常是不同的。根据博弈论经济学的定义，这两种游戏都是具有完美信息的有限游戏，因此是等价的。然而，在国际象棋中，心理能力和能力是**约束条件**，因此不可能做出最优选择。

>在计算机中： heuristic is a problem-solving strategy or method that is not guaranteed to find the optimal solution, but is designed to find a satisfactory solution in a reasonable amount of time.

西蒙用剪刀比喻 **decision-making**，来解释为什么传统的经济理论不能充分解释决策问题。其中一片剪刀刀片代表人类的大脑能力，另一片则代表我们做决策时的环境。单看剪刀的任何一片刀片，我们都无法理解它是如何剪切的。因此我们有必要理解决策制定中的所有不同因素，或者换句话说，看看是什么因素使理性受到限制。

## 有限理性模型

在提出了有限理性的概念后，人们便开始尝试着在模型的制定中考虑有限理性。Huw Dixon 提出可能没有必要详细分析有限理性背后的推理过程。如果我们相信人们会选择一个让他们接近最优的行动，那么我们可以使用 **epsilon-optimization** 的概念，即使得我们的决策收益在最优解的**epsilon**范围内。定义最优解收益为 \\(U^*\\)，则被用来优化的选择 \\(S(\epsilon)\\) 可以被定义为满足以下的选择 \\( s \\)

$$ U(s) \ge U^* - \epsilon $$

严格理性是以上的一个特例即当 \\(\epsilon = 0 \\)的情况。这种方法的优点在于，它避免了必须详细指定推理过程，而只是简单地假设，无论过程如何，它都足够好，能够接近最优解。

严格理性和有限理性可以被理解为 **algorithm** 和 **heuristic**。

## 例子

顾客在餐厅点餐时由于感到服务员在桌边等待，使得他们感到紧张，从而做出了不是最优的决定。另一个例子是，交易员由于时间压力和当时市场信息不完全，会做出次优且有风险的决定来交易他们的股票。

## 有限理性

有限理性是一种人类决策过程，其中我们试图寻求满意解，而不是最优解。换句话说，我们寻求的是一个足够好的决策，而不是最佳的决策。

***

# 理性本身的局限性

以上我们可以看出有限理性（bounded rationality）的限制来自于认知的局限性，人类的局限性。而理性本身呢？第一次看到这个问题的时候，我联想到的是Russell's Paradox[^fn2]。

## Naive Set Theory

Russell's Paradox 来自于 **Unrestricted Comprehension Principle**[^fn3]， 在naive set theory里，我们可以有 set of all sets that doesn't contains it self 即 \\(\\{x: x \text{ doesn't contains itself} \\}\\)。


>The unrestricted axiom of comprehension in set theory states that to every condition there corresponds a set of things meeting the condition


我们让 \\(R\\) 代表这个set，那 \\(R\\) 是否包含他自己呢？如果 \\(R\\) 包含他自己，那么 \\(R\\) 不包含他自己。如果 \\(R\\) 不包含他自己，则 \\(R\\) 满足不包含自己的条件，所以 \\(R\\) 应该包含他自己。

$$\text { Let } R=\{x \mid x \notin x\} \text {, then } R \in R \Longleftrightarrow R \notin R\\$$

由此我们得出了一个悖论

Ernst Zermelo 和 Abraham Fraenkel 创造了Zermelo–Fraenkel Set Theory 不允许 Unrestricted Comprehension Principle以及 set of set的存在，为了避免这样的悖论出现。

可在现实生活中这样的悖论无法被避免。

## 主语和谓语

苏格拉底是一个哲学家， 这句话中苏格拉底是subject即主语，是一个哲学家是predicate即谓语。我们可以说说predicate is true of subject，比如“是一个哲学家” is true of “苏格拉底”， “是一个人” is true of “我”， “是一只猫“ is not true of “我”（因为我不是一只猫）。

![pipe]({{site.baseurl}}/images/rational-post.jpg)
*图片有一个烟斗，有一个烟斗 is true of 图片*

语言没有限制，在语言中我们有Unrestricted Comprehension Principle，也可以说sentence of sentence，比如我们可以有 “‘你是一个画家’是一句话”，其中“你是一个画家”是subject，“是一句话” 是predicate。我们也可以有“‘是谓语’是谓语“，“‘是一只猫’ 是一只猫“，“‘是一个句子’是一个句子”，其中“是谓语”确实是谓语，而“是一只猫”不是一只猫，“是一个句子“确实是一个句子。是谓语 is true of 是谓语，所以是谓语 is true of itself，是一只猫is not true of itself，是一个句子 is true of is not true itself。

接下来考虑，“Is not true of itself“， 这是一个谓语 (predicate), 就像以上一样我们可以考虑他是不是 true of itself。 如果这个句子 is true of itself，即“Is not true of itself“ is true of itself，那么这句话Is not true of itself（是一个句子 is true of itself 指的是 是一个句子确实是是一个句子，“Is not true of itself“ is true of itself 指的是 “Is not true of itself“ 确实是“Is not true of itself“）

而如果这句子is not true of itself,即 “Is not true of itself“ is not true of itself， 这又能推出 这个句子 is true of itself。

有可能以上的例子比较绕，类似的可以考虑 “这句话是错的” 是不是对的，“我是一个给所有不给自己理头发的人理头发的剪发师“ 那我该不该给我自己理头发...

## 哥德尔不完备定理[^fn4]

**David Hilbert** 有一句名言 Wir müssen wissen, Wir werden wissen， 即 We must know and We shall know。**希尔伯特计划**[^fn5]是由德国数学家大卫‧希尔伯特在1920年代提出的一个数学计划。它是一个关于公理系统相容性的严谨证明的一项计划，而哥德尔不完备定理指出，希尔伯特计划里很多目标无法实现。

哥德尔不完备定理有两个定理

>**First Incompleteness Theorem**: "Any consistent formal system F within which a certain amount of elementary arithmetic can be carried out is incomplete; i.e., there are statements of the language of F which can neither be proved nor disproved in F."

>**Second Incompleteness Theorem**: "For any consistent system F within which a certain amount of elementary arithmetic can be carried out, the consistency of F cannot be proved in F itself."

哥德尔不完备定理构造也来自于self-reference，takeaway就是数学存在一个漏洞，意味着我们永远无法确定地知道一切，总会有无法证明的真命题。

> There is a hole at the bottom of math that means we will never know everything with certainty, there will always be true statement that cannot be proven.[^fn6]

***

# 总结

有限理性来源于人认知的局限性，环境的限制，信息的局限性。人类的有限性使我们的的认识是有缺陷的，这使得公众讨论是有意义的，获取知识是有益的，因为在过程中我们能够做出更加接近最优决策的选择。

理性本身的局限性，告诉我们悖论的存在，有很多事情我们不知道，而且可以被严谨的证明我们不能知道。但这不代表我们不应该去探索，去发现。事实上，即便在证明希尔伯特计划实现不了的过程中，Turing 提出了计算机的概念，使得今天的我们能有电子设备。

作为人类，我们具备非理性思考的能力，至少我们自己认为我们可以，我们可以感性，可以去爱，可以去用心感受，而这也使我们可以不单单依赖于理性的判断。

$$\text{And that's where beauty lies.}$$

***

[^fn1]: [Bounded Rationality](https://en.wikipedia.org/wiki/Bounded_rationality)
[^fn2]: [Russell's Paradox](https://en.wikipedia.org/wiki/Russell%27s_paradox)
[^fn3]: [Unrestricted Comprehension Principle](https://en.wikipedia.org/wiki/Axiom_schema_of_specification#Unrestricted_comprehension)
[^fn4]: [Godel Incompleteness Theorem](https://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems)
[^fn5]: [Hilbert Program](https://en.wikipedia.org/wiki/Hilbert%27s_program)
[^fn6]: [Godel Incomplete Video](https://www.youtube.com/watch?v=HeQX2HjkcNo)