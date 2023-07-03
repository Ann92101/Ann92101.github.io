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

经济学家 **Herbert A. Simon** 在1955年首次提出了有限理性这个概念[^1]，作为决策制定的数学和新古典经济模型中的概念替代，以反驳经济效益等同于理性的普遍观念。在当时现有的经济理论中，理性意味着当一个人在面对选择不同行动方案时，他们能够做出最优选择，被称为 **rationality as optimization** ， 西蒙的提议在推翻这种模型上产生了巨大影响。

西蒙认为现有的经济理解并不足以代表人们做出的决策。他提出有限理性的概念，以考虑到"包括人在内的有机体所实际拥有的信息获取和计算能力，以及这些有机体存在的环境类型。"换句话说，他希望他的理论能够考虑到**人们在做决策时可接触到的信息**，**人类思考能力的限制**，以及**环境的限制**，如时间。

在有限理性这个术语被提出之前，相关领域的研究其实已经开始了。**Maurice Allais** 在1953年完成的一项研究开始产生决策制定的非理性观念，因为他发现在给定的偏好下，个体并不总是选择最理性的决策，因此在经济预测中，理性的概念并不总是可靠的。

> "Boundedly rational agents experience limits in formulating and solving complex problems and in processing (receiving, storing, retrieving, transmitting) information."  
> <cite> Herbert A. Simon </cite>

西蒙提出由于因为情况的复杂性，人们用 **heuristics** 而不是严格的优化规则做决策。比如，在比较简单的情况下（例如井字游戏）和困难情况（例如国际象棋）中决策者使用的认知策略通常是不同的。根据博弈论经济学的定义，这两种游戏都是具有完美信息的有限游戏，因此是等价的。然而，在国际象棋中，心理能力和能力是**约束条件**，因此不可能做出最优选择。

>在计算机中： heuristic is a problem-solving strategy or method that is not guaranteed to find the optimal solution, but is designed to find a satisfactory solution in a reasonable amount of time.

西蒙用剪刀比喻 **decision-making**，来解释为什么传统的经济理论不能充分解释决策问题。其中一片剪刀刀片代表人类的大脑能力，另一片则代表我们做决策时的环境。单看剪刀的任何一片刀片，我们都无法理解它是如何剪切的。因此我们有必要理解决策制定中的所有不同因素，或者换句话说，看看是什么因素使理性受到限制。

## 有限理性模型

在提出了有限理性的概念后，人们便开始尝试着在模型的制定中考虑有限理性。Huw Dixon 提出可能没有必要详细分析有限理性背后的推理过程。如果我们相信人们会选择一个让他们接近最优的行动，那么我们可以使用 **epsilon-optimization** 的概念，即使得我们的决策收益在最优解的**epsilon**范围内。定义最优解收益为 $U^*$，则被用来优化的选择 $S(\epsilon)$ 可以被定义为满足以下的选择 \\( 1/x^{2} \\)

$$ U(s) \ge U^* - \epsilon $$

严格理性是以上的一个特例即当 $\epsilon = 0$ 的情况。这种方法的优点在于，它避免了必须详细指定推理过程，而只是简单地假设，无论过程如何，它都足够好，能够接近最优解。

严格理性和有限理性可以被理解为 **algorithm** 和 **heuristic**。

## 例子
顾客在餐厅点餐时由于感到服务员在桌边等待，使得他们感到紧张，从而做出了不是最优的决定。另一个例子是，交易员由于时间压力和当时市场信息不完全，会做出次优且有风险的决定来交易他们的股票。





[^1]: Bounded Rationality [https://en.wikipedia.org/wiki/Bounded_rationality](https://en.wikipedia.org/wiki/Bounded_rationality)