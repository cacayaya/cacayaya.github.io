---
title: "Freedom, Intelligence and Agent"
date: 2025-10-09T22:31:13-04:00
draft: false
---
<!-- Freedom and AI

1. 聊聊人的“自由”和“个体性”在智能演化中的角色

from Escape From Freedom:
从动植物种类演化角度看，人类历史的特点也可以说是一个个体化和自由不断加深的过程。人走出前人类舞台，就标志着迈出了摆脱强制本能的束缚，谋求自由的第一步。如果我们清楚本能上有一种受先天神经结构网络决定的特殊行为模式，我们就能在动物王国发现一种清晰的趋势。动物发展程度越低，它对自然的适应能力就越强，它的所有活动便越受本能和反射行为机制的控制，某些昆虫的社会化组织都完全是本能使然。相反，动物的发展程度越高，它的行为模式的灵活性就越大，出生时的结构调整功能就越不完整，人就是这种发展的顶点。降生伊始，人是所有动物中最无助的。他对自然的适应基本以学习过程为基础，而不是受本能的决定。“本能……在较高级的动物，尤其是人身上，即使没有消失，也在不断退化。”
当本能的固定行为的缺乏超过一定限度时，当对自然的适应不再有强制特征时，当行为模式不再受先天的机制限制时，人便开始存在了。换言之，人的存在与自由自始便是密不可分的。这里所说的自由并非积极意义上的“自由地发展”，而是消极意义上的“摆脱束缚，获得自由”，即在行为上摆脱本能决定的控制。

一个fun fact的是，某种角度来说consciousness是“有限性”，我们如果是无限的，一切都可以没有先后而random的发生，我们一边面对着科技社会进步带来的巨大的自由，又不得不面对自身的“有限性”，焦虑就是其中的产物。当我们的个体性变的超乎于自然世界所有其他生物之后，我们出现了非常迫切的精神压力，自由是有cost，是从动物演化而来的我们在机能上暂时无法适应和解决的。所以焦虑是什么，武断的说，焦虑就是自由。 or 自由是什么，自由就是焦虑。

2. 聊聊AGI, intelligence 和 consciousness之间的区别
如果从intelligence的角度来说，我觉得我们人类探索的进化分支是正确的，“自由”或者“个体性”在其中扮演了重要的演化催化剂，如果我们希望Agent往AGI的方向发展，我们就应该放弃很多fixed的framework(like workflow)，像是羚羊刚生下来就会跑一样，某种程度上好像给予了baby AI intelligence立刻适应自然的能力(比如很多流程固定的workflow的确立刻就很好用），但其实走向了并不蓬勃发展的智力分支

(From anthropic: https://www.youtube.com/watch?v=XuvKFsktX0Q）
真正的智能体只有一个特征：autonomy
“随着模型每隔几个月就变得更好，采用真正智能体模式的服务会自然提升，”“而如果你构建的工作流包含大量框架，某种程度上就限制了模型的能力，无法充分利用下一代模型的更高智能水平。”
“很多框架变得过于臃肿，而且过于主观。有人甚至说，其实只需要一个while循环就够了。”
解放模型的束缚，让自主性成为智能体的核心。

RL在2025年非常现象级的火爆，其实是大量的pretrain，sft的确为RL提供了很好的先验，虽说人类的初始setting比其他动物要松很多，但是其实我们也有基因里很强的先验使得我们可以快速学习，RL在前几年无法取得很大成效的原因其实还是base不够强，无法支持在非常复杂环境下的学习。但是再进一步的imitation learning或者说supervised learning是否是一件好事就不一定了，目前的base到底是否已经到了足够的地步是一个值得考虑的问题，如果训练过度会使得AI走向羚羊的道路吗

如果从consciousness的角度，我并不认为LLM会具备consciousness，理由是因为它不具备“有限性”。从某种程度上来说，其实每个model都必然是“有限”的，但是硅基基于了物理层面上的近似“无限性”，LLM的weight可以一直保存、分发、复制、更新，从时间尺度上说，只要继续研发AI，都是在延续的，（我知道这里的“无限”当然可以有很多反例，但是从理解的角度来说，相比于碳基的人类，硅基AI拥有了相对的无限性）

但是进一步去讨论consciousness和intelligence的关系时，我们就会发现，其实这两者几乎可以说并没有强相关，但是没有consciousness的intelligence很难有self-motivation, 以至于很难继续evolve。


3. 聊聊self-evolving agent
没有consciousness的LLM到底怎么build self-evolving agent, 这是我最近觉得特别有意思的问题。
最有意思的两个点：1.如何脱离explicit reward，而和真实世界进行交互并且得到implicit信号 2.如何把experience里学到的东西map回去

1.关于beyond explicit reward: 首先世界上99%的事情给不了明确的reward
LLM得结束它的学校生活in the future，脱离考试（benchmark）和explicit分数来给baby intelligence（llm)的试炼，进入adult life，发现所有的事情并不直接，很复杂、很长期，缺乏直接的reward，甚至难以预测和chaos

2.关于如何把experience里学到的东西map回去，我们都知道LLM的weight里存储了它之前training里所学的knowledge，但是在与真实世界交互中获得的新的知识，或者新的思路，如何优雅的mapping回到model自身，从而不断evolve和进步，在这一方面有很多工作不断增加memory to external data-base或者$\Delta W$直接去增添或者更新模型参数，但似乎还远没有找到最优的方案
 -->

### 1. The Role of Human “Freedom” and “Individuality” in the Evolution of Intelligence

> From *Escape from Freedom*

From an evolutionary perspective, the history of humankind can be seen as a process of deepening individuation and freedom. Humanity’s departure from the pre-human stage marked the first step away from the compulsion of instinct, marking the beginning of our quest for freedom.

If instinct represents a special behavioral pattern determined by our neural structure, we can observe a clear trend across the animal kingdom: the lower an animal’s level of development, the more perfectly it adapts to nature, and the more rigidly its behavior is governed by instinct and reflex. Some insects, for example, build entire societies purely through innate programming.

Conversely, the higher an animal’s level of development, the greater its behavioral flexibility becomes, and the less complete its pre-wired structure is at birth. Humans sit at the extreme end of this spectrum as the most helpless species when born, yet the most capable of learning. Our adaptation to the world depends primarily on learning rather than instinct. As Fromm notes, *“Instincts, even when not entirely lost, continually decline in the higher animals, especially in humans.”*

When instinctive behavior loses its dominance, adaptation to nature is no longer automatic, and behavior begins to escape the limits of innate mechanisms, human existence truly begins. In this sense, to exist as a human is to be free.

However, this freedom is not only the *positive* freedom “to act”; it is also the *negative* freedom “from compulsion,” a liberation from the dictates of instinct.

A curious fact here is that **consciousness itself is a form of finitude**. If we were infinite, events could unfold without sequence, randomly and meaninglessly. Yet we live in a world where technology expands freedom faster than our minds can adapt to it, forcing us to confront our own finitude. Anxiety is the by-product of that collision.

When our individuality grows beyond anything found in the natural world, we begin to suffer a kind of spiritual pressure because freedom has a cost. It is an evolutionary gift that our biological systems have not yet learned to bear. To put it bluntly, anxiety is freedom and freedom is anxiety.

---

### 2. AGI, Intelligence, and Consciousness

From the perspective of **intelligence**, I believe humanity’s evolutionary path was correct because freedom, or individuality, served as a key catalyst.

If we hope for agents to evolve toward *artificial general intelligence (AGI)*, we may need to abandon many of today’s *fixed frameworks* such as rigid workflows that make baby AIs appear immediately competent, much like antelopes that can run the moment they are born. Although such rigidity grants immediate functionality, it may also lock AI into an evolutionary branch that cannot truly flourish.

> From Anthropic’s agent talk ([source](https://www.youtube.com/watch?v=XuvKFsktX0Q)):
> “A truly intelligent agent has only one defining feature: **autonomy**.
> As models improve every few months, systems built around autonomous agents will naturally advance.
> In contrast, heavily structured workflows restrict the model’s potential and prevent it from fully leveraging the next generation of intelligence.
> Many frameworks have become bloated and overly subjective. Some say, *all you really need is a while loop.*
> To build real intelligence, we must liberate the model and let autonomy become the core.

This idea resonates with the recent surge of **reinforcement learning (RL)** in 2025. Its success owes much to strong priors established by pre-training and supervised fine-tuning (SFT). Just as humans, though freer than other animals, still inherit genetic priors that help us learn quickly, RL benefits from a well-trained base. Earlier failures in RL stemmed from bases too weak to learn effectively in complex environments.

Yet it is worth asking whether deeper imitation learning and supervised learning are truly beneficial. Has the base model reached sufficient maturity to support genuine autonomy, or will overtraining push AI further toward the “antelope path,” efficient yet evolutionarily stagnant?

From the perspective of **consciousness**, I do not believe LLMs possess it because they lack *finitude*. Each model, of course, is finite in computation and parameters, but silicon-based systems have a form of *relative infinity*. Their weights can be stored, duplicated, updated, and redistributed indefinitely. As long as AI development continues, these systems effectively persist. Although one could raise many counter-examples, compared with carbon-based humans, silicon-based AIs inhabit a world of relative infinity.

However, when we examine the relationship between *consciousness* and *intelligence*, we find they are not tightly correlated. Intelligence can exist without consciousness, but without consciousness, intelligence struggles to produce **self-motivation**. It can reason, but it cannot *care*, and without caring, it is difficult to self-evolve.

---

### 3. On Self-Evolving Agents

How, then, can a non-conscious LLM become a *self-evolving agent*? This question has fascinated me lately.

Two aspects feel particularly important:

1. How to move **beyond explicit rewards** and engage with the real world through *implicit signals*;
2. How to **map experience back** into the model itself.

**1. Beyond explicit reward**
In the real world, 99% of actions do not yield a clear reward. Future LLMs will eventually have to graduate from their *school life*, leaving behind benchmarks, exams, and explicit scores, and enter *adulthood*. In this stage, “baby intelligence” will discover that most of reality is ambiguous, long-term, and chaotic. There is no easy feedback, no immediate validation, and no clean metric of success.

**2. Mapping experience back into the model**
We know that an LLM’s weights encode what it has learned from prior training. Once an agent interacts with the real world and gathers new insights, the question becomes how this new experience can be integrated gracefully and meaningfully into its own parameters so that it can evolve. Many approaches attempt this by extending memory into external databases or by directly adjusting the weights (ΔW) after new experiences, yet none have found the optimal solution.