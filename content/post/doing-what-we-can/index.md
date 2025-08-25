+++
author = "Tyler McDonald"
title = "Doing What We Can, Not What We Should - My Take on AI as a Researcher"
date = "2025-05-24"
description = "As AI sweeps through our world, I finally decided to make my stance on modern AI known."
tags = [
    "artificial intelligence",
    "research"
]
categories = [
    "opinions",
]
image = "doingwhatwecan.png"
+++
It's hard to be a stranger to the ongoing debate about recent AI technologies. These tools have flooded across the internet, and are starting to bleed into a little bit of everything we do. It's a little unfortunate to see, especially as an AI researcher - a label I affix to myself that actually does me more harm than good, it seems. I'm actually fairly accepting of the debate my field of study causes, and I hope that this article of sorts finally solidifies my stance on the matter for the first time outside of a classroom or casual discussion.

Calling myself an AI researcher or someone interested in the field of AI typically provokes one of three reactions:

- Those who place quite the hype on the work I do, assuming my work is creating the technology they know and love.
- Those who dislike the field (perhaps correctly so), assuming my work is done with the intent to actively inflict harm on society.
- Those who have no clue what AI does, assuming I must be the next ChatGPT architect - this is arguably the scariest group.

I usually receive and process these opinions at face value, and I place great care on hearing debates and opinions from all sides - our field is quite detached from any idea of perfection, and I strongly believe we hype up a lot of dangerous work. I initially decided to write this to formalize everything I've learned from these discussions, but also to clear the air a bit about what we, as researchers, are *actively* trying to create.

The more I thought about that simple question, the more I realized it was far from simple. However, my stance on AI research remains clear: **we are in a field where researchers often have & equally entertain unchecked ambition.** I try my best to be cognizant of this fact, bouncing my ideas off of many people before I firmly land on something, which, frankly speaking, I wish was more of a common trend.

For those of you who want the digestible intro to what I'm going to talk about, my key anecdotes are threefold:

1. Just because we *can* make something doesn't come anywhere near implying that we *should* do something, which seems to be the source of much concern as of late.
2. The AI systems we see circulated regularly, with their litany of ethical issues, are not inherently evil - rather, they are a projection of the ethical oversights of their creators.
3. In my (likely polarized) opinion, AI is not ready for society, and society is not ready for AI - further obfuscated by the fact that we often have no clue how to solve either of those problems.

---

## AI research is more than creating LLMs!

With all due respect to the community, I hate how often I have to say this. **An AI researcher does not equal someone working on "modern" AI** [i]. Rather, AI researchers span a nauseatingly large number of subdisciplines - rule-based systems, classical approaches like pathfinding algorithms or simple classification techniques, natural language, data science, the mathematics of data inference, among *so* many others.

Granted, you must be thinking that this is a scorching hot take from a self-proclaimed natural language processing researcher who is actively concerned with LLMs [ii]. I'll hand you that one, but I'll clarify by saying that, no matter the discipline, there's *further* subdisciplines:

- Those who **create** the technology we use daily.
- Those who **evaluate** the technology we use daily.
- Those who **criticize** the technology we use daily.
- Those who **iterate over** the technology we use daily.

As you can likely gather, these subdisciplines have - rightfully so - quite a large overlap with one another. In fact, I am of the opinion that a well-rounded AI researcher is cognizant of ensuring their work falls in all four subdisciplines. Unfortunately, we're seeing less of this overlap with every new paper I read.

Because of these wide-spanning subdisciplines, AI has proven quite useful for the field of science: computer scientists should be forced to critically evaluate the implications of what they create, and the pace of play keeps us on our toes while forcing us to find new ways to accomplish that evaluation. Our field moves at a staggering rate - conferences see submission counts in the tens of thousands, and the general consensus is that we often can't know our specific niches in their entirety thanks to this pace. It's a blessing and a curse, almost perfectly reflecting the work we do in that funny little way.

Another key point to mention is that an AI researcher isn't necessarily developing something evil in their work, and that it is entirely logical to conclude that you regret creating something in the first place. Computer science has seen quite a few examples of this - Tony Hoare regretting the creation of the `null` reference, Joseph Weizenbaum being openly critical about the Eliza chatbot - and this is a trend that extends well beyond our field. For those who think I'm hyperfocusing on AI with this argument, I point you to Alfred Nobel regretting the creation of dynamite [1,2,3]!

My point here is crucial, and I'll refer back to one of those anecdotes above: **the implementation of a system is directly proportional to the ethical considerations of the creator.** McCullough and Pitts didn't create the neural network to inflict harm on society, but a basement developer designing their newest open-source image generation engine trained on scraped artwork might have ignored their willingness to do so.

The reality of AI research is that there is a loud majority of us who are committed not to the creation of these systems, but rather the exposal of the flaws that lie within these systems. I won't herald us as perfect, but we often spend our time writing and experimenting to expose those flaws as readily as our systems are being developed under our feet. I also won't play a victim card here, but I will note that it is at least a *tad* unfair to lump AI research into a collective bucket of harm-inducing papers that seek only to further egg on the devastation that these tools can inflict; in many cases, we're seeking out the exact opposite, and our goals are aligned with yours.

---

## Is AI ready for us, and are we ready for AI?

My short answer: **no.** My slightly longer answer: **no, and frankly, I have no clue how and when we'll ever be ready.**

The unfortunate reality is a product of a fortunate trend: AI research has accelerated at a mind-numbing pace. With advancements in AI over the past 50 years, we've been able to iterate over a computational model of cognition endless times, and I would argue we've better understood ourselves as a byproduct of this innovation. We created networks that modeled human neurons at scale, then imbued computers with the ability to classify text into parts of speech, *then* gave them the power to model that language into something coherent - and this is all said while fully ignoring the advancements in vision, speech synthesis, and so on.

The aforementioned unfortunate reality lies in one keyword: *power.* We've given each other and, as a result, computers the unchecked power to attempt to emulate humans. This unchecked power is what proves problematic, especially so given the fact that we can do very little to enforce responsibility on developers. Unfortunately, this issue has *layers*, and there's likely no immediate solution to ensuring that responsibility.

Some may argue that AI governance is the way forward, and while I agree in principle, putting it into practice is something I believe to be far more difficult than we make it seem. In my eyes, I look to the edge cases, of which I believe there to be two:

1. An overly enthusiastic figurehead imposes governance policies which **accelerate the development of AI** strictly for the localized benefits - automation in the workplace, user experience through AI-augmented daily tasks, et cetera [iii]. In this case, those who are overly enthusiastic tend to **overlook the myriad issues with the systems being developed *ad nauseam***, favoring rapid innovation to guardrailing.
2. A traditional figurehead from a non-STEM background imposes governance policies which **halt the development of AI** because of the harm it brings. In this case, ethically developed artificial intelligence systems are being looped unfairly into a blanket classification, which halts our progress as a field, and classical techniques that are, by definition, artificial intelligence get shoehorned into a classification of **dangerous, irresponsible, and a blight on society.**

Will there be AI policies put in place by those who are aware enough to know that power needs to come with responsibility? *Absolutely*, but I currently fear that those policies will end up being the minority. Even worse, what happens when the enthusiast, the traditionalist, and the realist butt heads and overwrite each other's policies? We end up in a governance deadlock that can't be resolved without some dustpan-line ruling from someone further up the chain, looking to impart their own mark on history.

Speaking further on dustpan lines, some argue that guardrail systems and post-deployment verifiers are the way forward - in essence, deploying a sidecar technology that verifies that outputs are debiased and safe for ordinary consumption. This is the most promising and, in my experience, active area of development, but to me it comes with a major flaw: the very nature of the field, the rapid development and race to the top, means we will see systems that are compromised by implicit biases [iv].

Allow me to provide a contextual example - a sidecar system in the Global East may potentially be more rooted in ensuring outputs respect the elderly, reflecting the Confucianist perspective of filial piety that is often culturally rooted in these regions [5]. Should this system speak for *all* countries, especially those where traditions vary? Perhaps it should - after all, respect for your elders feels more like common courtesy - but when we hit the point where a potentially conflicting tradition prevails - e.g., "No, you should not place your grandfather in a retirement home" - is this system truly free of implicit bias?

This provokes *yet another* issue - these traditions are often rooted in the data that models collect, and this data can be unfairly gathered as we are well-aware of by now. The "solution" to this is the creation of *synthetic data*, or data that models can generate and use in their own training. This solution is the least promising, yet seems fairly widely propagated.

How about *model collapse*, or the degradation of models that train on their own outputs? We can argue about the merits of AI all we'd like, but we can likely collectively agree that AI that spouts nonsense is a waste of resources, so why risk it? Additionally, we seem to often ignore that synthetic data requires **human data in the first place**, which leads us right back to square one. The reality is that we'll always need human data at some point in the process, but we often wrongfully conflate the need for human data with unethical data collection - a problem I agree is overwhelmingly prevalent.

My point in this whole rebuttal to my own thoughts is to say that we are at a crossroads where every path seems deceptive to me. We have to be very cautious about our way forward over the next few years, as it's going to be increasingly easy to trust and not verify - the very thing that got us into this mess to begin with. I don't entirely know when we'll every be fully prepared and equipped to handle unethical AI, and I can't promise a timeline for when I'd like to see that preparation as I feel wholly unqualified.

---

## Responsible AI in the real world

It is entirely plausible to create AI systems that are ethical in nature and in practice - unfortunately, developers often ignore these cases because it's far easier to pump out a system when you don't have checks and balances beyond performance considerations. Personally, I've seen some incredibly motivating examples of where to use AI, and I think they serve as a nice palate cleanser against the slop we see across the internet today.

A great example? Geolabe’s effort to use foundational AI models for climate event detection [4,v]! The creation and use of datasets to detect environmental abnormalities through niche patterns is something incredibly exciting to me; detecting methane emissions by using AI to deconvolve emission patterns has proven immensely powerful, especially as doing this by hand is a futile search.

Of course, some will argue that the environmental impact of training these models could potentially negate their use in detecting the abnormalities they may have had a hand in creating. To this point, I cautiously agree - yes, we require a fair bit of energy to develop these foundational models, but if they're being put to use in ethical and productive settings, I'd argue that the benefit is at least equal to the cost. We appreciate and take for granted plenty of creature comforts that mandate insane levels of resource consumption - hell, you're reading this on a device that takes rare minerals and a very involved R&D process that, all said and done, can take up to a gigajoule of energy (73 yearly charges of said phone [6]!) to create - but as long as the productivity of these technologies is there, I'd say we're headed in the right direction.

Another amazing use case: the discovery of drugs and malignant tumors! Drug discovery through classical AI is an area of interest for me, albeit one that's not necessarily congruent to my research, and AI has enabled us to investigate the drug creation process in ways that would take us a near-infinite amount of time and bodily energy to replicate as humans [vi]. Similarly, though more warily, the use of AI to augment the cancer discovery process is something I feel to be a step in the right direction; AI augmentation for good, not just to *vibe code* your SaaS startup, is something I will cherish as a healthy innovation in the field, but not without some reservations [vii].

---

## How do we equip ourselves for success?

These reservations take me to my final set of points: how do we continue to develop ethical systems for social good? Of course, this area has been explored and addressed too many times, so my thoughts on the matter are likely a reflection of many of my past experiences:

- We need to **obtain data legally and through fair compensation schemes.** Pay artists for their artwork, and don't train on their work to establish some perverted stylistic mimicry [viii]. Sample data with consent from those who can be linked to that data - when designing a system to predict cancer, inform patients of their right to withhold their medical imaging - and do everything in our power to remove the links between person and data. In all, ensure that the data we gather is representative of the whole and fair to all parties.
- When creating user-centric models, **make every reasonable effort to conduct a diverse bias recognition and mitigation process.** Bias mitigation can't be performed by a single demographic - instead, we need to loop in those from different lived experiences and social domains to know how bias presents in different ways. For those who will take issue with my use of "reasonable effort", believe me when I say that we have a *lot* of reasonable efforts at our disposal, and this is the most critical one. Most importantly, don't rush your technologies off the production line and cross your fingers that users won't see that bias can propagate in a million different forms.
- By far the opinion that I'm most polarized about, **stop making things just to say you made something!** Innovation can wait, because polished, safe, and equitable innovation trumps all other innovation. Researchers in our field often chase papers like there's no tomorrow, and this is a trend I desperately want to see mitigated. We need to stop developing problematic systems just to say we beat a benchmark, and we need to stop training our existing models on anything and everything just to beat the same benchmarks. **Equitable iteration over technology is possible**, it's often just conveniently ignored.

Naturally, there are far more moving parts to this than I can cover reasonably in an opinion piece, so I urge you - especially if you are someone less familiar with the moving parts behind the AI systems we interact with daily - to read papers, opinion pieces, and surveys on the development being done in our field. Not only will this demystify what we do as researchers, but it'll show you the many ways lots of us are fighting back against the status quo of doing what we want just because we can.

My hope is that AI will develop to a point where people will be empowered and encouraged to develop safe and fair systems, but unfortunately, that seems to be an illusion I craft to comfort myself at night. I appreciate those who take the time to make their opinions known, as it helps us as a field more than you know - your opinions provide the fuel to the work we do to expose systems that are harming users actively.

---

## Shameless plug: what do I work on?

To provide some context for my arguments, I'll clarify my own interests as a researcher.

Presently, I am a Master of Science candidate at Brock University, having completed my Honours Bachelor of Science in Computer Science in April of 2025. My thesis primarily focuses on the differences between LLMs developed in various global regions, the locally projected biases these models may exhibit, and how model merging techniques may help us mitigate this bias while providing stronger multilingual models. My hope is that this research motivates the development of a truly global LLM, or at least one that is multinational, as this saves us from redundant innovation at the expense of natural resources.

Priorly, my work has fallen in the realms of commonsense reasoning, detection and mitigation of implicit and explicit bias, and the evaluation of inference costs inflicted by recent prompt engineering techniques. My goal is to reveal where LLMs suffer in terms of performance and equity, and to use my findings to motivate the creation of LLMs that are appropriate for consumption while being suited for various tasks. My work has been published in various natural language processing conferences such as ACL, EMNLP, and COLING.

Outside of the scope of my thesis, I’m also incredibly interested in cognitive social science and how it interfaces with modern AI - things like parasocial human-AI relationships, the effects of early childhood AI usage on brain development, and the emotional toll AI can inflict on users. As a whole, I am interested in fair and robust AI systems, while understanding the aftershocks caused by a lack of consideration for either of these qualifiers.

I understand that I'm not perfect - a focus on commonsense reasoning benchmarks, for a long time, left me clinging to the *opposite* point of view compared to what I proposed in this opinion. I'll be the first to admit that I was a benchmark chaser for a long time - which is precisely why I dedicated my MSc. to "break it" research as opposed to "make it" research.

If you're at all interested in my work, or wish to discuss anything further (in respectful conversations), you can contact me via email at tmcdonald3 with the suffix [brocku.ca](http://brocku.ca/).

---

## Endnotes

i - By “modern” AI, I am primarily referring to the influx of language, vision, and speech synthesis models - particularly, those designed for consumption through a user-centric interface, like ChatGPT. These are traditionally systems that rely on natural language processing, or the enabling of AI systems to process and understand natural languages (languages that develop naturally through use).

ii - LLMs is a common shorthand for Large Language Models.

iii - I use the term “AI augmentation” a few times in this article. I define this term as the use of AI in tandem with human effort - this contrasts AI reliance, creation, etc. which implies the use of AI predominantly to achieve a task. Vibe coding falls… in a strange place on this spectrum.

iv - I define implicit bias as a subconscious bias that may impact someone’s thoughts or actions, often without their direct oversight, and explicit bias as a conscious and expressed bias.

v - I define a foundational model as a pretrained model on a set of data that is not yet finetuned, or tailored, to act on a specific task. It’s not a perfect definition here, but I digress.

vi - My definition of “classical” AI is meant to serve in opposition to “modern” AI - tried and true techniques that do not involve large language/vision/speech models.

vii - “Vibe coding” is the practice where a software engineer develops code with the primary assistance of an artificially intelligent system. See: GitHub Copilot or Cursor.

viii - “Stylistic mimicry” is the act of training on artist works to allow users to request a piece of AI-generated art in that artist’s style.

1 - To learn more about Hoare’s gripe with his own invention, I point you to this amazing lecture: https://www.youtube.com/watch?v=ybrQvs4x0Ps

2 - An absolutely stunning take on Weizenbaum’s issues with Eliza can be found here: https://www.theguardian.com/technology/2023/jul/25/joseph-weizenbaum-inventor-eliza-chatbot-turned-against-artificial-intelligence-ai. Particularly of interest if you’re interested in parasocial relationships with AI, as I am.

3 - Similarly, a spectacular article from McGill re: Nobel’s “merchant of death” stance on his creation of dynamite: https://www.mcgill.ca/oss/article/history/how-dynamite-spawned-nobel-prizes

4 - Geolabe competed in a NASA entrepreneurship competition, developing the system I described. Read about it here: https://www.mcgill.ca/oss/article/history/how-dynamite-spawned-nobel-prizes

5 - I am cognizant of the fact that I may retain some bias when drawing this conclusion; however, I point to sources such as https://theamericanscholar.org/confucianism-in-china-today/ for inspiration. Specifically, through the interactions I’ve had with various peers, filial piety is a value that I pay particular interest to. I mean no harm by drawing this conclusion, and use it purely as a demonstration of traditional values.

6 - Obtained from a cool read: https://www.theatlantic.com/technology/archive/2014/10/the-energy-in-things/381557/