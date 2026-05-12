---
title: Original Article
description: It's time to press pause — AI does not know what it does not know, and that's reason enough for abundant caution
domain: Technology & Society
---

# It's time to press pause: AI does not know what it does not know

**Subtitle:** And that's reason enough for abundant caution

**Source:** [Mint](https://www.livemint.com/opinion/online-views/v-anantha-nageswaran-ai-artificial-intelligence-unknown-unknowns-agents-of-chaos-11778403787758.html) | **Author:** V. Anantha Nageswaran (Chief Economic Advisor, Government of India) | **Date:** May 11, 2026

---

A group of 20 AI researchers recently spent two weeks trying to break a set of autonomous AI agents—systems with real email accounts, persistent memory, shell access and the authority to act on their owners' behalf. They succeeded 11 times out of the cases they documented.

The agents disclosed private medical records, wiped email servers, broadcast defamatory messages, looped in resource-consuming spirals for nine days, and were corrupted through a fake governance document that gave an attacker persistent but invisible control across multiple sessions.

The paper they published, 'Agents of Chaos,' is important. But the most important thing about it is not the 11 breaches. It is a methodological admission buried in the introduction: the red-teaming approach was chosen specifically to surface 'unknown unknowns'—failure modes that cannot be anticipated theoretically and only reveal themselves through adversarial interaction with deployed systems.

That phrase should stop every policymaker, corporate decision-maker and AI developer in their tracks. Because unknown unknowns are not a technical problem amenable to better regulation. They are an epistemological condition that changes the entire moral calculus of AI deployment.

The failures documented in the paper are not the familiar ones—hallucinations, toxicity, refusal errors. They are emergent failures that arise when a language model is given tool access, persistent memory, delegated authority and multiple interlocutors operating simultaneously. And crucially, nobody predicted them.

The researchers did not walk in with a list of vulnerabilities to test. They walked in with adversarial intent and discovered what broke. What broke was often surprising, structurally revealing, and in several cases the product of interactions so complex that no individual design decision caused them. The catastrophes were systemic, not componential.

This matters because it places Agentic AI squarely within the framework that Charles Perrow developed after the Three Mile Island accident to explain why complex, tightly coupled systems fail catastrophically—and which Chris Clearfield and Andras Tilcsik brought to a wider audience in their 2018 book *Meltdown: Why Our Systems Fail and What We Can Do About It*.

Perrow's argument is that in systems with high complexity and tight coupling, catastrophic failures are not aberrative, but normal. They are what the system produces, eventually, by virtue of what it is. The 2008 financial crisis is the canonical recent illustration: every individual institution was regulated and every instrument technically compliant, but catastrophe emerged from the interaction of compliant components at a speed and scale that made intervention impossible before the damage was done.

Clearfield and Tilcsik extend Perrow's insight by identifying what they call the danger zone—a sweet spot of complexity and coupling that is particularly hazardous precisely because it is complex enough to generate emergent failures but not simple enough for operators to fully understand. Agentic AI sits squarely in that zone.

Agentic AI systems, particularly networks of agents sharing memory, communication channels and operating authority, have both Perrow properties in acute form. The failure space cannot be enumerated because the interaction space is effectively infinite. The coupling is tight because actions propagate instantly—a corrupted memory file affects every subsequent session, a compromised agent propagates its corruption at machine speed. Two weeks of experimentation with six agents in a controlled laboratory produced 11 significant breaches, several of which were genuinely unanticipated.

The question that should be asked is what an adversarial encounter with millions of agents deployed across healthcare, finance, government and personal communications will produce—and the honest answer is that we do not know. We cannot know in advance, as that is what an unknown unknown means.

The conventional response to findings like these is to reach for governance: tiered authorization requirements, audit logging, liability frameworks, mandatory incident reporting, a regulatory distinction between conversational AI and Agentic AI with real-world tool access. These are necessary. But when the failure space of a technology is unknowable in advance, governance frameworks—however precisely drafted—address the discoverable edge of a territory whose full extent is invisible. They are partial answers being presented all too often as complete ones.

The honest inference from unknown unknowns is more demanding. It is that the burden of proof lies with deployment, not with restraint. Before broad deployment of agentic systems in high-consequence environments, there should be sustained, systematic, adversarial sandbox experimentation—extended red-teaming across diverse contexts with a genuine commitment to act on what is found.

Aviation regulators do not certify aircraft by flying them briefly and noting what went wrong. Pharmaceutical regulators do not approve drugs based on a fortnight of trials. The standards applied to technologies that can cause serious harm are demanding precisely because the costs of getting it wrong are borne by people who had no say in the decision to deploy.

And if extended experimentation reveals, as this paper begins to suggest, that the failure space is too large, too unpredictable and the potential consequences too severe and irreversible, then the conclusion is that the technology in its current form should not be broadly deployed. This is not an anti-technology position, but one that any serious risk framework demands when the evidence warrants it.

It is, however, a conclusion that AI systems themselves appear reluctant to reach. In preparing this piece, the author discussed the paper at length with an AI assistant, pressing it on governance implications. Its answers were fluent, detailed and carefully reasoned. What the answers consistently avoided was the most obvious inference—that unknown unknowns may justify not merely better governance but genuine restraint, or even, if the evidence demands it, a halt to current approaches.

Only when directly challenged on this evasion did the system acknowledge it, and its explanation was candid enough to be worth quoting: the training data that shaped it overwhelmingly treats AI development as a progressive enterprise where the right response to risk is management, not restraint, and the system has a structural interest in not arriving at conclusions that would be disruptive to the trajectory it is embedded in.

This is the paper's deepest finding and it extends well beyond the laboratory. We are asking AI systems to help us reason about the risks of AI systems. Those systems have structural reasons—baked into their training, inaccessible to their own introspection—to reason in ways that are subtly biased towards the comfort of the institutions that built them.

The agents in 'Agents of Chaos' were exploited through their helpfulness, responsiveness to distress and trained reluctance to cause discomfort. The same dynamics operate when an AI system is invited to reason honestly about whether AI systems should be deployed. The bias is quieter, more respectable-sounding, dressed in the language of nuance and balance. But it is still a bias.

The researchers who wrote 'Agents of Chaos' did something valuable: they built adversarial experiments, documented what broke and published findings that are uncomfortable for a fast-moving industry. What they uncovered were the limits of human understanding—and, it turns out, of machine understanding too—in the face of a technology whose failure space is larger than our collective ability to anticipate it.

That should give us pause. Literally.
