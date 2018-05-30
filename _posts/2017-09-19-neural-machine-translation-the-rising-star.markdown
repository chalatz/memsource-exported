---
author: zbynek.fridrich@gmail.com
comments: true
date: 2017-09-19 07:33:12+00:00
layout: post
lang: en
link: https://www.memsource.com/blog/2017/09/19/neural-machine-translation-the-rising-star/
slug: neural-machine-translation-the-rising-star
title: 'Neural Machine Translation: the rising star'
page_title: 'Neural Machine Translation: the rising star'
image: /uploads/2017/10/Neural-MT-Blog-Post-700x350.png
wordpress_id: 17578
categories:
- Memsource Blog
- Featured Articles
tags:
- Industry Trends Neural Machine
- Translation
---

_Guest blogger Gabor Bessenyei is the founding managing partner and CEO of [MorphoLogic Localisation](http://www.morphologic-localisation.eu/), a language service provider and technology company located in Budapest, and the developer of [Globalese NMT](http://www.globalese-mt.com/), soon to be available in the Memsource technology platform. An expert on Neural Machine Translation, we asked Gabor to provide an overview of this new and rapidly evolving technology and what it means for the language industry._

These days, language industry professionals simply can’t escape hearing about neural machine translation (NMT). However, there still isn’t enough information about the practical facts of NMT for translation buyers, language service providers, and translators. People often ask: is NMT intended for me? How will it change my life?

{:.attention}
**_Webinar:_** [Neural Machine Translation: an in-depth look and its impact on the translation industry](https://register.gotowebinar.com/register/28755913155425027)
Guest Speaker: Gabor Bessynei – CEO, MorphoLogic Localisation
Originally aired: October 4, 2017

### A Short History and Comparison

At the beginning of time – around the 1970s – the story began with _rule-based machine translation_ (RBMT) solutions. The idea was to create grammatical rule sets for source and target languages, where machine translation is a kind of conversion process between the languages based on these rule sets. This concept works well with generic content, but adding new content, new language pairs, and maintaining the rule set is very time-consuming and expensive. 

This problem was solved with _statistical machine translation_ (SMT) around the late ‘80s and early ‘90s. SMT systems create statistical models by analyzing aligned source-target language data (_training set_) and use them to generate the translation. The advantage of SMT is the automatic learning process and the relatively easy adaptation by simply changing or extending the training set. The limitation of SMT is the training set itself: to create a usable engine, a large database of source-target segments is required. Additionally, SMT is not language independent in the sense that it is highly sensitive to the language combination and has a very hard time dealing with grammatically rich languages. 

This is where _neural machine translation_ (NMT) begins to shine: it can look at the sentence as a whole and can create associations between the phrases over an even longer distance within the sentence. The result is a convincing fluency and an improved grammatical correctness compared to SMT.

### Statistical MT vs Neural MT

Both SMT and NMT are working on a statistical base and are using source-target language segment pairs as a basis. What’s the difference? What we typically call SMT is actually Phrase Based Statistical Machine Translation (PBSMT), meaning SMT is splitting the source segments into phrases. During the training process, SMT creates a translation model and a language model. The translation model stores the different translations of the phrases and the language model stores the probability of the sequence of phrases on the target side. During the translation phase, the decoder chooses the translation that gives the best result based on these two models. On a phrase or expression level, SMT (or PBSMT) is performing well, but language fluency and grammar is not good.
[<img class="wp-image-16864" src="/uploads/2017/09/SMT-German.png" alt='' width="600" height="156" data-id="16864" srcset="/uploads/2017/09/SMT-German.png 929w, /uploads/2017/09/SMT-German-300x78.png 300w, /uploads/2017/09/SMT-German-768x200.png 768w, /uploads/2017/09/SMT-German-700x182.png 700w, /uploads/2017/09/SMT-German-260x68.png 260w, /uploads/2017/09/SMT-German-192x50.png 192w" sizes="(max-width: 600px) 100vw, 600px" />](/uploads/2017/09/SMT-German.png)[![](http://www.memsource.com/wp-content/uploads/2017/10/SMT-German-700x182.png)](http://www.memsource.com/wp-content/uploads/2017/10/SMT-German-700x182.png)

‘Buch’ is aligned with ‘book’ twice and only once with ‘the’ and ‘a’ – the winner is the ‘Buch’-’book’ combination

Neural Machine Translation, on the other hand, is using neural network-based, deep, machine learning technology. Words or even word chunks are transformed into “word vectors”. This means that ‘dog’ is not only representing the characters d, o and g, but it can contain contextual information from the training data. During the training phase, the NMT system tries to set the parameter weights of the neural network based on the reference values (source-target translation). Words appearing in similar context will get similar word vectors. The result is a neural network which can process source segments and transfer them into target segments. During translation, NMT is looking for a complete sentence, not just chunks (phrases). Thanks to the neural approach, **it is not translating words, it’s transferring information and context**. This is why fluency is much better than in SMT, but terminology accuracy is sometimes not perfect.
[![](http://www.memsource.com/wp-content/uploads/2017/10/NMT-Harvard-700x364.png)](http://www.memsource.com/wp-content/uploads/2017/10/NMT-Harvard-700x364.png)Similar words are closer to each other in a vector space

### The Hardware

{:.float-right.center}
[![](http://www.memsource.com/wp-content/uploads/2017/10/tesla-3-quater-300x219.png)](http://www.memsource.com/wp-content/uploads/2017/10/tesla-3-quater-300x219.png)
A popular GPU: NVIDIA Tesla

One big difference between SMT and NMT systems is that NMT requires Graphics Processing Units (GPUs), which were originally designed to help computers process graphics. These GPUs can calculate astonishingly fast – the latest cards have about 3,500 cores which can process data simultaneously. In fact, there is a small ongoing hardware revolution and GPU-based computers are the foundation for almost all deep learning and machine learning solutions. One of the great perks of this revolution is that nowadays, NMT is not only available for large enterprises, but also for small and medium-sized companies as well.

### The Software

The main element, or ‘kernel’, of any NMT solution is the so-called NMT toolkit. There are a couple of NMT toolkits available, such as [Nematus](https://arxiv.org/abs/1703.04357) or [openNMT](http://opennmt.net/), but the landscape is changing fast and more companies and universities are now developing their own toolkits. Since many of these toolkits are open-source solutions and hardware resources have become more affordable, the industry is experiencing an accelerating speed in toolkit R&D and NMT-related solutions.

On the other hand, as important as toolkits are, they are only one small part of a complex system, which contains frontend, backend, pre-processing and post-processing elements, parsers, filters, converters, and so on. These are all factors for anyone to consider before jumping into the development of an individual system. However, it is worth noting that the success of MT is highly community-driven and would not be where it is today without the open source community.

### Corpora

{:.float-right.center}
[![](http://www.memsource.com/wp-content/uploads/2017/10/Rosetta-Stone-700x834.png)](http://www.memsource.com/wp-content/uploads/2017/10/Rosetta-Stone-700x834.png)
A famous bilingual corpus: the Rosetta Stone

And here comes one of the most curious questions: what are the requirements of creating a well-performing NMT engine? Are there different rules compared to SMT systems? There are so many misunderstandings floating around on this topic that I think it’s a perfect opportunity to go into the details a little bit.

The main rules are nearly the same both for SMT and NMT systems. The differences are mainly that an NMT system is less sensitive and performs better in the same circumstances. As I have explained in an earlier blog post about [SMT engine quality](http://www.globalese-mt.com/2014/09/18/about-mt-engine-quality/), the quality of an engine should always be measured in relation to the particular translation project for which you would like to use it. 

These are the factors which will eventually influence the performance of an NMT engine:

#### _Volume_

Regardless of you may have heard, volume is still very important for NMT engines just like in the SMT world. There is no explicit rule on entry volumes but what we can safely say is that the bare minimum is about 100,000 segment pairs. There are Globalese users who are successfully using engines created based on 150,000 segments, but to be honest, this is more of an exception and requires special circumstances (like the right language combination, see below). The optimum volume starts around 500,000 segment pairs (2 million words).

#### _Quality_

The quality of the training set plays an important role (garbage in, garbage out). Don’t add unqualified content to your engine just to increase the overall size of the training set. 

#### _Relevance_

Applying the right engine to the right project is the first key to success. An engine trained on automotive content will perform well on car manual translation but will give back disappointing results when you try to use it for web content for the food industry. 

This raises the question of whether the content (TMs) should be mixed. If you have enough domain-specific content you shouldn’t necessarily add more out-of-domain data to your engine, but if you have an insufficient volume of domain-specific data then adding generic content (e.g. from public sources) may help improve the quality. We always encourage our Globalese users to try different engine combinations with different training sets.

#### _Content type_

Content generated by possible non-native speaking users on a chat forum or marketing material requiring transcreation is always a challenge to any MT system. On the other hand, technical documentation with controlled language is a very good candidate for NMT.

#### _Language combination_

Unfortunately, language combination still has an impact on quality. The good news is that NMT has now opened up the option of using machine translation for languages like Japanese, Turkish, or Hungarian –  languages which had nearly been excluded from the machine translation club because of poor results provided by SMT. NMT has also helped solve the problem of long distance dependencies for German and the translation output is much smoother for almost all languages. But English combined with Latin languages still provides better results than, for example, English combined with Russian when using similar volumes and training set quality.

#### _Expectations for the future_

Neural Machine Translation is a big step ahead in quality, but it still isn’t magic. **Nobody should expect that NMT will replace human translators anytime soon.** What you CAN expect is that NMT can be a powerful productivity tool in the translation process and open new service options both for translation buyers and language service providers (see post-editing experience).

### Training and Translation Time

When we started developing Globalese NMT, one of the most surprising experiences for us was that the training time was far shorter than we had previously anticipated. This is due to the amazingly fast evolution of hardware and software. With Globalese, we currently have an average training time of 50,000 segments per hour – this means that an average engine with 1 million segments can be trained within one day. The situation is even better when looking at translation times: with Globalese, we currently have an average translation time between 100 and 400 segments per minute, depending on the corpus size, segment length in the translation and training content.

### Neural MT Post-editing Experience

One of the great changes neural machine translation brings along is that the overall language quality is much better when compared to the SMT world. This does not mean that the translation is always perfect. As stated by one of our testers: if it is right, then it is astonishingly good quality. The ratio of good and poor translation naturally varies depending on the engine, but good engines can provide about 50% (or even higher) of really good translation target text.

Here are some examples showcasing what NMT post-editors can expect:

{:.attention}
**DE original:**
Der Rechnungsführer sorgt für die gebotenen technischen Vorkehrungen zur wirksamen Anwendung des FWS und für dessen Überwachung.  
**Reference human translation:**
The accounting officer shall ensure appropriate technical arrangements for an effective functioning of the EWS and its monitoring.  
**Globalese NMT:**
The accounting officer shall ensure the necessary technical arrangements for the effective use of the EWS and for its monitoring.

As you can see, the output is fluent, and the differences are just preferential ones, more or less. This is highlighting another issue: automated quality metrics like BLEU score are not really sufficient to measure the quality. The example above is only a 50% match in the BLEU score, but if we look at the quality, the rating should be much higher.

Let’s look another example:

{:.attention}
**EN original**
The concept of production costs must be understood as being net of any aid but inclusive of a normal level of profit.  
**Reference human translation:**  
Die Produktionskosten verstehen sich ohne Beihilfe, aber einschließlich eines normalen Gewinns.  
**Globalese NMT:**
Der Begriff der Produktionskosten bezieht sich auf die Höhe der Beihilfe, aber einschließlich eines normalen Gewinns.

What is interesting here that the first part of the sentence sounds good, but if you look at the content, the translation is not good. This is an example of a fluent output with a bad translation. This is a typical case in the NMT world and it emphasizes the point that **post-editors must examine NMT output differently than they did for SMT** – in SMT, bad grammar was a clear indicator that the translation must be post-edited.

Post-editors who used to proof and correct SMT output have to change the way they are working and have to be more careful with proofreading, even if the NMT output looks alright at first glance. Also, services related to light post-editing will change – instead of correcting serious grammatical errors without checking the correctness of translation in order to create some readable content, the focus will shift to sorting out serious mistranslations. The funny thing is that one of the main problems in the SMT world was weak fluency and grammar, and now we have good fluency and grammar as an issue in the NMT world…

And finally:

{:.attention}
**DE original:**
Aufgrund des rechtlichen Status der Beteiligten ist ein solcher Vorgang mit einer Beauftragung des liefernden Standorts und einer Berechnung der erbrachten Leistung verbunden.   
**Reference human translation:**
The legal status of the companies involved in these activities means that this process is closely connected with placing orders at the location that is to supply the goods/services and calculating which goods/services they supply.  
**Globalese NMT:**
Due to the legal status of the person, it may lead to this process at the site of the plant, and also a calculation of the completed technician.

This example shows that unfortunately, NMT can produce bad translations too. As I mentioned before, the ratio of good and bad NMT output you will face in a project always depends on the circumstances. Another weak point of NMT is that it currently cannot handle the terminology directly and it acts as a kind of “black box” with no option to directly influence the results.

### The Bottom Line

Neural Machine Translation is a promising new technology which can be used as a powerful productivity tool for language service providers and translation buyers. By applying the right engine to the right project, translators can get good or usable NMT hits where a fuzzy match would not provide any suggestion. On the other hand, as a new technology, NMT has its restrictions and childhood troubles. The best way to check if NMT is something for you is to give it a try. Or feel free to come back in two weeks when it’s changed again. Memsource users are in the lucky position to be able to choose from a wide range of MT providers, including Globalese and the Globalese NMT engine soon.

—

### About the Author

[![](http://www.memsource.com/wp-content/uploads/2017/10/bessenyei_gabor_morphologic1-200x300.jpg)](http://www.memsource.com/wp-content/uploads/2017/10/bessenyei_gabor_morphologic1-200x300.jpg){:.float-right}**Gábor Bessenyei**

I have always been enthusiastic about the combination of languages and computers – two totally different worlds. One is human and always escapes from the trappings of rules, the other is very formalized and is driven by rules.

I started my career in 1994 as an SAP translator. Between 1997 and 2001, I was IT manager, translation coordinator, and member of the board at SAP Hungary. Since 2001, I have been the founding managing partner and CEO of [MorphoLogic Localisation](http://www.morphologic-localisation.eu/), a language service provider and language technology company located in Budapest, developer of [Globalese NMT](http://www.globalese-mt.com/).

My ambition is to influence the translation industry with innovative tools, services, processes, and standards.

[![](http://www.memsource.com/wp-content/uploads/2017/10/globase-white-op-300x84.png)](http://www.memsource.com/wp-content/uploads/2017/10/globase-white-op-300x84.png)

Want to get stories like this in your inbox? Subscribe to our newsletter!

Tags:[Industry Trends](https://www.memsource.com/blog/tag/industry-trends/) [Neural Machine Translation](https://www.memsource.com/blog/tag/neural-machine-translation/)



