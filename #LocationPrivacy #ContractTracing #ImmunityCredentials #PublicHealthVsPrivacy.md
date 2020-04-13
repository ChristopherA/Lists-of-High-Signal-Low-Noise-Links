---
created: 2020-04-11T08:43:06-07:00
modified: 2020-04-12T10:29:00-07:00
title: '#LocationPrivacy #ContractTracing #ImmunityCredentials #PublicHealthVsPrivacy'

---

# [#LocationPrivacy](https://twitter.com/hashtag/LocationPrivacy) [#ContactTracing](https://twitter.com/hashtag/ContactTracing)  [#ImmunityCredentials](https://twitter.com/hashtag/ImmunityCredentials) [#PublicHealthVsPrivacy](https://twitter.com/hashtag/PublicHealthVsPrivacy)

> This is one of my [series of lists](https://github.com/ChristopherA/High-Signal-Low-Noise-Link-Lists) of opinionated, high-signal but low-noise links on topics I care about.
>
> If you like my advocacy, my point-of-view, my writing, my travel, my talks, and my work with organizations such as [Blockchain Commons](https://www.BlockchainCommons.com), [Rebooting the Web of Trust](https://www.WebOfTrust.info) and the [W3C Credentials CG](https://w3c-ccg.github.io), I invite you to sponsor me by becoming a monthly patron on my [GitHub Sponsor Page](https://github.com/sponsors/ChristopherA) for as little as $5 a month, as they are matching the first $5,000!
>
> Alternatively can also support my efforts by sponsoring [Blockchain Commons](https://www.BlockchainCommons.com) and our vision of the open web via a monthly [GitHub Sponsorship](https://github.com/sponsors/BlockchainCommons) or with Bitcoin via our [Bitcoin](https://btcpay.blockchaincommons.com)contribution page.
>
> But please don’t think of this as a transaction. It’s an opportunity to advance the open web, digital civil liberties and human rights together. You get to plug into my various projects, and hopefully will find a way to actively contribute to the digital commons yourself. Let’s collaborate!
>
> -- Christopher Allen <ChristopherA@LifeWithAlacrity.com\>, Github: [@ChristopherA](https://github.com/ChristopherA), Twitter: [@ChristopherA](https://twitter.com/ChristopherA)

## Table of Contents

  * [Table of Contents](#table-of-contents)
  * [My Personal POV & High-Level Concerns](#my-personal-pov---high-level-concerns)
  * [General News & Opinion](#general-news---opinion)
    + [Contact Tracing News](#contact-tracing-news)
    + [Immunity Credential News](#immunity-credential-news)
  * [Law, Policy & Regulations](#law--policy---regulations)
  * [Implementations & Analysis](#implementations---analysis)
    + [Contact Tracing Technology](#contact-tracing-technology)
      - [Implementations of Contact Tracing](#implementations-of-contact-tracing)
        * [Analysis of Specific Contact Tracing Implemenations](#analysis-of-specific-contact-tracing-implemenations)
      - [General Contact Tracing Analysis and Technology](#general-contact-tracing-analysis-and-technology)
      - [General Criticism of Contact Tracing & Location Privacy Technology Solutions](#general-criticism-of-contact-tracing---location-privacy-technology-solutions)
  * [Immunity Credential Technology](#immunity-credential-technology)
    + [Implementations of Immunity Credentials](#implementations-of-immunity-credentials)
      - [W3C Verifiable Claims](#w3c-verifiable-claims)
    + [General Immunity Credentials Analysis & Technology](#general-immunity-credentials-analysis---technology)
  * [Other Related Privacy Technologies](#other-related-privacy-technologies)
    + [Psuedoanonymous Ephemeral Locality](#psuedoanonymous-ephemeral-locality)
  * [Related Events & Meetings](#related-events---meetings)
  * [New & Unsorted](#new---unsorted)

## My Personal POV & High-Level Concerns 

**This is my most recent presentation on the topic of why I'm involved in the Self-Sovereign Identity movement, as part of a [#Foremembrance](https://twitter.com/hashtag/Foremembrance) this March during an SSI Meetup virtual event. I talk about some important historical context from WWII in the Netherlands, and how it is relevant to the impact and risk of COVID-19 for privacy and identity systems:**

* Allen, Christopher (2020, 27 March). How to avoid another identity tragedy with SSI. [#SSI [#Foremembrance](https://twitter.com/hashtag/Foremembrance) #Opinion #Presentation, SSI Meetup].
  * Presentation retrieved from https://docs.google.com/presentation/d/1lO6vik7UkXQEhAWtVsaF3Bn_KUAUhZsTflTPjeF3aSw
  * Video retrieved from https://www.youtube.com/watch?v=isanNSDoSnE.
  > KEYQUOTE: Some of these things we've been fighting for a long time...in this crisis there is the opportunity to identify some best practices that are do-able now, and put some appropriate energy into better solutions that we can implement for maybe not this crisis, but for the next one.

## General News & Opinion
*(Most recent first)*

### Contact Tracing News

**Two of the biggest mobile app platfroms, Apple & Google, are partnering on contact-tracing technology. Early privacy analysis is positive, but it still has centralization issues (see [Implementations & Analysis](#implementations--analysis) section below for more details).**

* McSweeney, Michael (2020, April 10). Apple, Google partner on COVID-19 contact tracing tech initiative. [#News #Opinion, The Block].
  * Retrieved from https://www.theblockcrypto.com/linked/61556/apple-google-partner-on-covid-19-contact-tracing-tech-initiative.
  > KEYQUOTE: Technology giants Apple and Google are teaming up to develop a technology solution for contact tracing the spread of COVID-19 infections amid a growing global pandemic.

**Fantastic, public domain, comic explaining how privacy preserving Bluetooth alerts work:**

* Case, Nicky (2020, April 9). Twitter Thread, 12/12 [#Opinion, Twitter].
  * Retrieved from https://twitter.com/ncasenmare/status/1248271370368114688; https://ncase.me/contact-tracing/. 
  > KEYQUOTE via @mikarv: How exactly can #DP3T privacy-preserving Bluetooth COVID-19 alerts work if identifiable personal data never leaves your device? It's actually not so complicated, and even less so now @ncasenmare has made a fantastic, public domain, comic explaining it.

**A pretty good update on what is happening on the telcom side of [#LocationPrivacy](https://twitter.com/hashtag/LocationPrivacy). It does have me concerned that various efforts for privacy enhanced bluetooth [#ContactTracing](https://twitter.com/hashtag/ContactTracing) and other such approaches are a moot point given what the cell phone already allow to be correlated.**

* Espinoza, Javier and Fildes, Nic (2020, April 7). Tracking coronavirus: big data and the challenge to privacy. [#News #Opinion, Financial Times; Free to Read].
  * Retrieved from https://www.ft.com/content/7cfad020-78c4-11ea-9840-1b8019d9a987.
  > KEYQUOTE: Still, assurances from officials and industry executives have done little to appease anxiety that privacy rights could be brushed aside as governments seek to use tools of mass surveillance in their efforts to combat the virus. The concerns about political use of data have been aggravated by the fact that the European Commission wants the telecoms companies to provide the actual aggregated data, not just access to insights from that information.
  > Some researchers are not convinced by the claim that such data sets are completely anonymous. A 2019 study by researchers at Imperial College London and Belgium’s Catholic University of Louvain revealed there is a way to re-identify 99.98 per cent of individuals with just 15 demographic characteristics using location data. Other studies have come to similar conclusions that individuals can be identified based on aggregate data sets with relative ease.

* McDonald, Sean (2020, March 30). The Digital Response to the Outbreak of COVID-19 [#Opinion, Centre for International Governance Innovation].
  * Retrieved from https://www.cigionline.org/articles/digital-response-outbreak-covid-19
  > KEYQUOTE: Undeniably, we need to use technology as part of disaster response, but the regulatory immaturity of the industry makes technology companies risky allies, even in the best of circumstances
  > The way that we enable, administer and check the exceptional surveillance and social powers that each government exerts to contain COVID-19…will frame an important part of the future of state power in a world with increasing emergencies.
  >While the risks and harms associated with digital surveillance are often framed as related to privacy, there are significantly larger issues that apply during a pandemic, such as the escalation of government powers. "

* Thalen, Mikael (2020, March 27). Terrifying cellphone ‘heat map’ shows just how much people are still traveling [#News #Opinion, daily dot].
  * Retrieved from https://www.dailydot.com/debug/cellphone-heat-map-coronavirus/.
  > ABSTRACT/KEYQUOTE: X-Mode states that its “data is aggregated at the advertising ID level and associated to the device and not a physical person.” An advertising ID is assigned to devices and allows companies to tailor specific content to users based on their browsing history and activity...And while X-Mode and many other companies in the industry point to the fact their data is anonymized, researchers have found that such data can easily be linked to its owner’s identity.

* Unknown (2020, March 26). Countries are using apps and data networks to keep tabs on the pandemic. [#News #Opinion, The Economist].
  * Retrieved from https://www.economist.com/briefing/2020/03/26/countries-are-using-apps-and-data-networks-to-keep-tabs-on-the-pandemic.
  > ABSTRACT/KEYQUOTE: The use of data becomes most fraught when it moves beyond modelling and informing policy to the direct tracking of individuals in order to see from whom they got the disease. Such contact-tracing can be an important public-health tool. It also has a resemblance to modern counter-terrorism tactics.

**Privacy After Lockdown**

* Begley, Sharon (2020, March 25). When can we let up? Health experts craft strategies to safely relax coronavirus lockdowns. [#News #Opinion, Stat News].
  * Retrieved from https://www.statnews.com/2020/03/25/coronavirus-experts-craft-strategies-to-relax-lockdowns/.
  > KEYQUOTE: ...how to do it right, or at least better. There is reason to hope that will be possible. An emerging consensus points to aggressive tracing of contacts of sick people, much broader testing, targeted quarantines, and new online tracking technology as strategies that would facilitate the easing of social distancing measures.

* Harrison, Sara (2020, 24 March). When Is Anonymous Not Really Anonymous?. [#News #Opinion, Ask The Markup].
  * Retrieved from https://themarkup.org/ask-the-markup/2020/03/24/when-is-anonymous-not-really-anonymous.

  > KEYQUOTE: Differential privacy protects individuals in the data set by intentionally introducing mathematical randomness, also called noise, into the data set. The amount of noise can be shared publicly, just like an error rate, but no one can know which statistics are the noise and which are real people. This solution gives researchers access to the database, but it also protects the privacy of the individuals in the set.

* Swire, Peter (2020, March 24). Security, Privacy and the Coronavirus: Lessons From 9/11. [#Opinion, LawFare].
  * Retrieved from https://www.lawfareblog.com/security-privacy-and-coronavirus-lessons-911.

  > KEYQUOTE: ...it may become tempting for government agencies in the U.S. to seek access to location databases as a claimed way to battle the coronavirus. The usefulness of databases for tracking contacts, however, is open to serious doubt. The underlying data is often inexact. Even where two dots on the map appear close to each other, they may be on different floors of an apartment building or on opposite sides of a wall. In addition, there are innumerable other reasons why contagion may not occur between the owners of two phones in apparent proximity to each other. In short, absent an empirical showing of accuracy and actionability that does not exist to date, calls for such location tracking quite possibly are security theater rather than actual security.

* Marjan, Branka (2020, March 24). A delicate balance: Responding to a crisis with surveillance tech. [#News #Opinion, Project Ploughshares].
  * Retrieved from https://ploughshares.ca/2020/03/a-delicate-balance-responding-to-a-crisis-with-surveillance-tech/.

  > ABSTRACT/KEYQUOTE: Too often, history shows, temporary measures imposed by governments to meet a crisis have become permanent...Limits must be placed on what data is collected, how it is used, and how long it is kept. Focusing on voluntary participation and anonymizing data could address some privacy concerns. Requiring secure deletion of information after a certain period of time is also important.

* Scott, Mark; Cerulus, Laurens; Kayali, Laura (2020, March 23). Commission tells carriers to hand over mobile data in coronavirus fight [#News #Opinion, Politico].
  * Retrieved from https://www.politico.eu/article/european-commission-mobile-phone-data-thierry-breton-coronavirus-covid19/

  > ABSTRACT/KEYQUOTE: Researchers, academics and telecoms executives say that as the coronavirus crisis has spread so quickly, the usefulness of such anonymized mobile phone metadata is quickly coming to an end. As people enter lockdown, often not able to travel beyond their neighborhoods, such digital information does not offer much insight because it is not granular enough to track people's localized movements.

* Servick, Kelly (2020, March 22). Cellphone tracking could help stem the spread of coronavirus. Is privacy the price? [#News #Opinion, Science Magazine].
  * Retrieved from https://www.sciencemag.org/news/2020/03/cellphone-tracking-could-help-stem-spread-coronavirus-privacy-price#.

  > KEYQUOTE: Several emerging projects aim to set up voluntary, privacy-conscious phone tracking systems. This week, a team led by computer scientist Ramesh Raskar at the Massachusetts Institute of Technology released a prototype of an app called Private Kit: Safe Paths. The app stores up to 28 days of a user’s GPS location data, logged every 5 minutes. If the user tests positive for coronavirus, they can choose to share their recent data with health officials to identify and publicize the places where others may have been at risk of infection.

* Estrin, Daniel (2020, March 19). Israel Begins Tracking And Texting Those Possibly Exposed To The Coronavirus. [#News #Opinion, NPR].
  * Retrieved from https://www.npr.org/2020/03/19/818327945/israel-begins-tracking-and-texting-those-possibly-exposed-to-the-coronavirus.

  > KEYQUOTE: It's likely that Israelis who were not within 2 meters (6 feet) of distance from a virus carrier will still be identified for quarantine. Sharon Perry, a cellular tracing expert, said the GPS technology of civilian mobiles can pinpoint a person's location only within 5 to 6 meters' accuracy if the cellphone is outdoors, or 10 to 20 meters if the phone is indoors. But he argued the breach of privacy was justified.

* Williams, Jamie (2020, March 18). Unchecked Smart Cities are Surveillance Cities. What We Need are Smart Enough Cities. [#News #Opinion, Electronic Frontier Foundation].
  * Retrieved from https://www.eff.org/deeplinks/2020/03/unchecked-smart-cities-are-surveillance-cities-what-we-need-are-smart-enough.

  > ABSTRACT/KEYQUOTE: Local transportation planning agencies across the country are currently demanding that operators of shared mobility devices turn over individual trip data as a condition of getting a permit to operate within their jurisdictions.

* Byers, Dylan (2020, March 18). The U.S. wants smartphone location data to fight coronavirus. Privacy advocates are worried [#News #Opinion, NBC News].
  * Retrieved from https://www.nbcnews.com/tech/tech-news/u-s-wants-smartphone-location-data-fight-coronavirus-privacy-advocates-n1162821.

  > ABSTRACT/KEYQUOTE: Federal health officials say they could use anonymous, aggregated user data collected by the tech companies to map the spread of the virus — a practice known as ["syndromic surveillance"](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC353021/) — and prevent further infections. They could also use the data to see whether people were practicing "social distancing."

* Thompson, Stuart A.; Warzel, Charlie (2019, December 19). Twelve Million Phones, One Dataset, Zero Privacy [#News #Opinion, New York Times].
  * Retrieved from https://www.nytimes.com/interactive/2019/12/19/opinion/location-tracking-cell-phone.html. 

  > ABSTRACT/KEYQUOTE: The companies that collect all this information on your movements justify their business on the basis of three claims: People consent to be tracked, the data is anonymous and the data is secure. None of those claims hold up, based on the file we’ve obtained and our review of company practices. Yes, the location data contains billions of data points with no identifiable information like names or email addresses. But it’s child’s play to connect real names to the dots that appear on the maps.

### Immunity Credential News

* Wighton, Daniel and Chazan, David (2020, March 29). Germany will issue coronavirus antibody certificates to allow quarantined to re-enter society. [#News #Opinion, The Telegraph].
  * Retrieved from https://www.telegraph.co.uk/news/2020/03/29/germany-will-issue-coronavirus-antibody-certificates-allow-quarantined/. 
  > KEYQUOTE: German researchers plan to introduce coronavirus ‘immunity certificates’ to facilitate a proper transition into post-lockdown life, as Chancellor Angela Merkel’s handling of the crisis has led to a boost in the polls.


## Law, Policy & Regulations
*(Most recent first)*

** Given EU GDPR and California CPRA, it is very hard to meet those privacy laws and regulatory standards for #LocationPrivacy.**
* Gray, Stacey; et al (2020, March 25). A Closer Look at Location Data: Privacy and Pandemics. [#News #Opinion, Future of Privacy Forum].
  * Retrieved from https://fpf.org/2020/03/25/a-closer-look-at-location-data-privacy-and-pandemics/.
  > ABSTRACT/KEY QUOTE: Typically, we think of location data as having privacy implications when it is precise enough to single out an individual with reasonable specificity...Measuring precise location depends in part on context, such as population density...Recent legislative proposals have attempted to create strict cut-offs (such as an 1,640 foot radius under the U.S. House and Commerce Discussion Draft, or an 1,850 foot radius under the California Privacy Rights Act ballot initiative of 2020).
  
**Human Rights, Privacy Law & GPDR expert Elizabeth Renieres ([@hackylawyer](https://twitter.com/hackylawyer) always has great insights on the intersection of privacy technology, the law, and is always one of the first people I go to on these topics:**

* Renieris, Elizabeth M. (2020, March 23). When Privacy Meets a Pandemic. [#Opinion, Medium].
  * Retrieved from https://onezero.medium.com/when-privacy-meets-pandemic-fbf9154f80b3.
  > KEYQUOTE: So, where does this leave us as a privacy community and what is our role in the time of Corona? It means that before we debate the particulars of a specific technology or application, before we tweak certain features or functionality to better protect individual privacy, or before we impose certain transparency or accountability measures, we take a step back.
  > Before we concede that a measure is necessary and begin to assess its proportionality, we question that underlying assumption — especially when it’s coming from private companies who stand to gain from it or governments who fear being perceived as lacking control over the situation. We apply the age-old tests of legality, necessity, and proportionality — in that order. We require concrete evidence that a measure will further specific aims or achieve certain measurable outcomes.
  > If privacy advocates don’t step up and do this, who will?
  
* Scott, Mark; Cerulus, Laurens; Kayali, Laura (2020, March 23) Article: Commission tells carriers to hand over mobile data in coronavirus fight
  * Retrieved from https://www.politico.eu/article/european-commission-mobile-phone-data-thierry-breton-coronavirus-covid19/
  > KEYQUOTE: The European Commission on Monday urged Europe's telecoms giants including Deutsche Telekom and Orange to share reams of people's mobile data from across the region to help predict the spread of the coronavirus…called on the companies to hand over anonymized and aggregated data from people’s mobile phones to track how the virus was spreading…The draft plans would allow the Commission — and not the carriers — to manage how the data was used, and give EU officials control over so-called metadata on hundreds of millions of people’s mobile phones. That represents a significant step for Brussels as it would make the EU executive liable for any hefty fines if the digital information was hacked or misused.

* Unknown (2020, March 16). Statement by the EDPB Chair on the processing of personal data in the context of the COVID-19 outbreak [#Law #Regulatory, European Data Protection Board].
  * Retrieved from https://edpb.europa.eu/news/news/2020/statement-edpb-chair-processing-personal-data-context-covid-19-outbreak_en.
  > ABSTRACT/KEYQUOTE: The national laws implementing the ePrivacy Directive provide for the principle that the location data can only be used by the operator when they are made anonymous, or with the consent of the individuals...When it is not possible to only process anonymous data, Art. 15 of the ePrivacy Directive enables the member states to introduce legislative measures pursuing national security and public security.
  
* GMSA Public Policy: COVID-19 Privacy Guidelines April 2020 https://www.gsma.com/publicpolicy/resources/covid-19-privacy-guidelines
  > ABSTRACT: The mobile industry recognises the urgency with which governments must act to slow the spread of COVID-19 and the desire of some governments to seek help regarding those efforts. At the same time, the mobile industry recognises that the use of mobile network operator data by governments or agencies raises serious privacy concerns. These guidelines reflect recommendations on how the mobile industry may maintain trust while responding to those governments and public health agencies that have sought assistance in the fight against COVID-19.

* Johnston, Anna (2020, March 31). Privacy in a pandemic: Keep calm, and remember first principles [#News #Opinion, Salinger Privacy].
  * Retrieved from https://www.salingerprivacy.com.au/2020/03/31/privacy-in-a-pandemic/.
  > KEYQUOTE: Indeed a national committee of all the Australian privacy regulators has been formed to respond to COVID-related proposals with national implications (such as development of a contact tracing tool), and they have reiterated the value of conducting short-form Privacy Impact Assessments on proposed solutions to public health and economic problems, to make sure privacy is considered in the design process. 

* Hernandez, Lorena (2020, January 27). Report: Guidelines for public administrations on location privacy - Version 2 [#Law #Regulatory, European Location Interoperability Solutions for e-Government].
  * Retrieved from https://joinup.ec.europa.eu/collection/elise-european-location-interoperability-solutions-e-government/document/report-guidelines-public-administrations-location-privacy-version-2.

  > ABSTRACT/KEYQUOTE: The guidelines address the privacy implications of handling location data by public administrations and identify potential risks related to the processing of personal location data. 
 
## Implementations & Analysis

### Contact Tracing Technology

**[#ContactTracing](https://twitter.com/hashtag/ContactTracing) were among the first Covid-19 tech solutions proposed, basically informing people that they may have been in recent contact with someone with an active infection. There are huge privacy, concent and human rights risks in this area, as [#LocationPrivacy](https://twitter.com/hashtag/LocationPrivacy) is very difficult.**

**There are some emerging solutions that are better than other, however, I still am skeptical about both the efficacy of [#ContactTracing](https://twitter.com/hashtag/ContactTracing) (because in many case is probably too late, and it only works if there is large adoption) & and issues of [#PrivacyByDesign](https://twitter.com/hashtag/PrivacyByDesign) (many open issues on incentive design, consent & active adversary issues, and all proposed solutions are too centralized) of this first generation of [#ContactTracing](https://twitter.com/hashtag/ContactTracing) apps.**

**That being said, I beleive it is worth the effort to learn best practices of this generation of apps and make better choices for the next generation.**

#### Implementations of Contact Tracing
*(Those with most detail first, then by date order)*

**Some contact tracing implementations related, projects:**

* EU: PEPP-PT (Pan-European Privacy-Preserving Proximity Tracing):
  * Pan-European Privacy-Preserving Proximity Tracing
    * Retreived from https://www.pepp-pt.org
    > ABSTRACT: PEPP-PT was created to assist national initiatives by supplying ready-to-use, well-tested, and properly assessed mechanisms and standards, as well as support for interoperability, outreach, and operation when needed. The PEPP-PT mechanisms will have these core features:
  > Well-tested and established procedures for proximity measurement on popular mobile operating systems and devices. 
  > Enforcement of data protection, anonymization, GDPR compliance, and security.
  > International interoperability to support tracing local infection chains even if a chain spans multiple PEPP-PT participating countries.
  > Scalable backend architecture and technology that can be deployed with local IT infrastructure.
  > Certification service to test and ensure local implementations use the PEPP-PT mechanisms in a secure and interoperable manner.
  > Our reference implementation is available under the Mozilla License Agreement.
  * Stolton, Samuel (2020, April 6). EU data watchdog pitches pan-European COVID-19 app. [#News #Opinion, Euractiv].
    * Retrieved from https://www.euractiv.com/section/digital/news/eu-data-watchdog-pitches-pan-european-covid-19-app
    > KEYQUOTE: Apps taking advantage of ‘bluetooth handshakes’ registered between two smartphone users when coming into close proximity with one another have received publicity recently following the establishment of a European project dubbed Pan-European Privacy-Preserving Proximity Tracing (PEPP-PT)…The technology borrows from various initiatives worldwide, including Singapore’s TraceTogether application, which has influenced other national projects in the West seeking to clamp down on the spread of the virus.

* Singapore: 

  > TraceTogether is a mobile application developed to support existing nationwide efforts to combat COVID-19, by enabling community-driven contact tracing.
  * Retrieved from https://www.tracetogether.gov.sg/.

  > BlueTrace is a privacy-preserving protocol for community-driven contact tracing using Bluetooth devices, that allows for global inter-operability.
  * Retrieved from https://bluetrace.io/.

* MIT: SafePaths:

  > https://www.media.mit.edu/projects/safepaths/overview/ - Safe Paths is an MIT-led, free, open source technology that enables jurisdictions and individuals to maximize privacy, while also maximizing the effectiveness of contact tracing in the case of a positive diagnosis. The Safe Paths platform, currently in beta, comprises both a smartphone application, PrivateKit, and a web application, Safe Places.
  
* Israel: The Shield
  https://translate.google.com/translate?sl=auto&tl=en&u=https%3A%2F%2Fwww.haaretz.co.il%2Fcaptain%2Fsoftware%2F1.8700078

* Prague Smart Quarantine
  https://www.praguemorning.cz/czech-republic-smart-quarantine/

* Poland ProteGO
  https://github.com/ProteGO-app/specs/blob/master/ENGLISH.md

* Italy HITS by Cy4Gate
  https://twitter.com/elettronicagrp/status/1242462328362237959?s=21

* NextTrace
  https://nexttrace.org/about/

* Covid-Devender project overview (from Moses Ma's FutureLab):
  https://www.dropbox.com/s/lg05fp5f2d2qxry/COVID-defender%20OVERVIEW.pdf?dl=0

* Trustee Universal Healthcare Records
  https://docs.google.com/document/d/1LSWYNeHNYfU99UtUlvo-GXE6I6uTmzZjzaEtSRsecGM/edit?usp=sharing

* FOAM:
  https://blog.foam.space/introduction-to-proof-of-location-6b4c77928022

* GIDEON:
  https://www.gideononline.com/about/gideon/


**Papers on DP3T (refer to earlier comic):**

* Troncoso, Carmela; et al (2020, April 10). Decentralized Privacy-Preserving Proximity Tracing: Simplified Overview. [#Review #Implementation, GitHub Whitepaper].
  * Retrieved from https://github.com/DP-3T/documents/blob/master/DP3T%20White%20Paper.pdf.

  > ABSTRACT: This document proposes a system for secure and privacy-preserving proximity tracing (aka contact tracing) at large scale. This system provides a technological foundation to help slow the spread of SARS-CoV-2 virus by simplifying and accelerating the process of notifying people who have been in contact with an infected person. The system design aims to minimise privacy and security risks for individuals and communities and guarantee the highest level of data protection.

* Troncoso, Carmela (2020, April 3). Decentralized Privacy-Preserving Proximity Tracing: Simplified Overview. [#Review #Implementation, GitHub Whitepaper].
  * Retrieved from https://github.com/DP-3T/documents/blob/master/DP3T%20-%20Simplified%20Three%20Page%20Brief.pdf.

  > KEYQUOTE: Given the concerns about the effectiveness of legal safeguards, the impossibility of anonymization, and the intrinsic vulnerabilities of centralized data minimization models, we focus on decentralized designs for privacy preserving proximity tracing. 
  
##### Analysis of Specific Contact Tracing Implemenations

**Brief "first look" by Signal app's creator Moxie Marlinspike (Twitter: [@moxie](https://twitter.com/moxie)) on the Apple/Google #ContactPrivacy framework**
* Marlinspike, Moxie (2020, April 10). Twitter thread. [#Implementation #Analysis, Twitter]
  * Retreived from https://twitter.com/moxie/status/1248707315626201088
  KEYQUOTE: So first obvious caveat is that this is "private" (or at least not worse than BTLE), *until* the moment you test positive. At that point all of your BTLE mac addrs over the previous period become linkable… Second caveat is that it seems likely location data would have to be combined with what the device framework gives you.…Third caveat is that it seems likely some kind of PII would have to be combined with what the device framework gives you. Keys published by a device have to then be in turn "published" to *all* devices in the world. That's a major DoS vector!…All that aside, these APIs are novel in terms of what becomes possible from the app layer. I'm not super optimistic about opt-in contact tracing becoming a major factor, but I do kind of anticipate that someone will end up using this for some other interesting thing.

**Two early reivew of Singapore's Trace Together app and the BlueTrace protocol**
* L, Frank (2020, March 23). Trace Together Under the Hood [#Implementation #Analyisi, Medium].
  * Retrieved from https://medium.com/@frankvolkel/tracetogether-under-the-hood-7d5e509aeb5d. 
* Typic, Zero (2020, March 23). Reversing Trace Together.
  * Retrieved from https://medium.com/@zerotypic/reversing-tracetogether-initial-analysis-edc940e86aa8.
  
#### General Contact Tracing Analysis and Technology
(Most recent first)

**A good reply from W3C Credentials CG, where I am co-chair, to de Montjoye questionaire below:**

  * Booth, David (2020, April 02) W3C-CCG Mailing List: https://lists.w3.org/Archives/Public/public-credentials/2020Apr/0017.html
  > KEYQUOTE: That document raises excellent questions, but I think the range of protocols (designs) for consideration should be broadened even more. All three of the toy protocols that they discuss involved a central authority -- presumably a public health agency -- that would receive information about infected or exposed individuals.  I think it would be good to also consider (list follows

**Excellent questionnaire for people designing or evaluating should ask about #ContactTracing implementations**

* de Montjoye, Yves-Alexandre; Houssiau, Florimond; Gadotti, Andrea and Florent Guepin (2020, April 2). Evaluating COVID-19 contact tracing apps? Here are 8 privacy questions we think you should ask. [#Opinion #Implementation, Computational Privacy Group].
  * Retrieved from https://cpg.doc.ic.ac.uk/blog/evaluating-contact-tracing-apps-here-are-8-privacy-questions-we-think-you-should-ask/
  > KEYQUOTE: In-depth formal analysis of the protocol is necessary before deployment and should be published. Protecting privacy should rely on mathematical proofs of correctness, with mitigation strategies considered only when necessary. Our questions focus on privacy aspects, but ensuring security is similarly crucial. This means, for example, supervising the integrity and authenticity of the crowdsourced data, evaluating how mobile malware could affect the app’s behavior, or assessing the resilience of the authority’s servers against intrusions.
  > Building a contact tracing app that allows all of us to participate in the fight against COVID19 is possible, but it will require us to go beyond shallow reassurances that privacy is protected. 
  
**One technologist's first take on how to security approach #ContactPrivacy**
  
* Hoepman, Jaap-Henk (2020, March 25). Hansel and Gretel and the Virus: Privacy Conscious Contact Tracing. [#Opinion, XOT.nl].  
  * Retrieved from https://blog.xot.nl/2020/03/25/hansel-and-gretel-and-the-virus-privacy-conscious-contact-tracing/

  > KEYQUOTE: Inspired by Apple’s protocol, we could create a system where devices leave a trail of breadcrumbs (like Hansel and Gretel in their fairy tale) consisting of their location and identity. The system can be made privacy conscious by ensuring that this trail is not maintained in any central database (like the NHS proposal outlined above does), and making sure the breadcrumbs disappear after some time.
  
**W3C Credentials CG, where I am co-chair, regularly discusses identity & privacy, and recently #LocationPrivacy:**

* Andrieu, Joe; Hamilton Duffy, Kim; Allen; Christopher (2020, March 24). Credentials CG Telecon. [#Review #Meeting, W3C Credentials CG].
  * Retrieved from https://w3c-ccg.github.io/meetings/2020-03-24/. 

* Replies in the CCG worth reading:
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0094.html
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0108.html
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0112.html
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0113.html
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0120.html
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0124.html

#### General Criticism of Contact Tracing & Location Privacy Technology Solutions
*(Most recent first)*

**A real problems in the current crop of #ContactTracing approaches are not the precisely the technology, but social incentive design and adversarial resistance to attacks**
* Anderson, Ross (2020, April 12). "Contact Tracing in the Real World"
    * Retrieved from https://www.lightbluetouchpaper.org/2020/04/12/contact-tracing-in-the-real-world/
>ABSTRACT: “Here are some problems with private contact tracing. We should not give policymakers the false hope that they can avoid hard choices"
>KEYQUOTE: “The performance art people will tie a phone to a dog and let it run around the park; the Russians will use the app to run service-denial attacks and spread panic; & little Johnny will self-report symptoms to get the whole school sent home.”

**Former FDA Commissioner Dr. Scott Gotlieb ([@ScottGottliebMD](https://twitter.com/ScottGottliebMD)) calls for far greater public health surveillance to help stem COVID, but is skeptical of #ContactTracing apps.**
* McLellan, Mark; Gottlieb, Scott; Mostashari, Farzad; Rivers, Caitlin; Silvis, Lauren (2020, April 7) A National COVID-19 Survellance System: Achieving Containment [Duke-Margolis Center for Health Policy]
  * Retrieved from https://healthpolicy.duke.edu/sites/default/files/atoms/files/covid-19_surveillance_roadmap_final.pdf
  > KEYQUOTE: Cell phone-based apps recording proximity events between individuals are unlikely to have adequate discriminating ability or adoption to achieve public health utility, while introducing serious privacy, security, and logistical concerns. Instead, timely contact tracing can be achieved through strengthened public health case investigation augmented by technology and community-level collaborations.

**A key concern of #ContactTracing apps is the huge adoption required for them to be effecive. Other than coercive use in China, Singapore has the largest % acceptance of these apps (6% maybe), but many academics question the efficacy:**
* Ferritti, Luca, et al. (2020, March 31) Quantifying SARS-CoV-2 transmission suggests epidemic control with digital contact tracing [Science]
  * Retreived from: https://science.sciencemag.org/content/early/2020/04/09/science.abb6936
  > KEYQUOTE If this is an accurate picture of viral spread in Europe and not an artefact of early growth, epidemic control with only case isolation and quarantining of traced contacts appears implausible in this case, requiring near-universal App usage and near-perfect compliance. The App should be one tool among many general preventative population measures such as physical distancing, enhanced hand and respiratory hygiene, and regular decontamination.

**Criticism isn't always about the implementation of these technolgies, but also the concerns about the parties doing the implementations**
* Franceschi-Bicchierai, Lorenzo (2020, April 2). We Saw NSO's Covid-19 Software in Action, and Privacy Experts Are Worried. [#News #Opinion, Vice]. Retrieved from https://www.vice.com/en_us/article/epg9jm/nso-covid-19-surveillance-tech-software-tracking-infected-privacy-experts-worried
  > ABSTRACT: Every citizen of the world wants to go back to normal as soon as possible. The gold rush to surveillance technology could easily mean that there is a normal expectation of privacy that we will have a hard time going back to.
  > KEYQUOTE: In the spirit of never letting a good crisis go to waste, several companies around the world— some already notorious and some less public—are pitching and developing surveillance tools to help governments track citizens with the goal of stopping the spread of coronavirus. For critics, however, this is an unnecessary escalation justified by a tragic health crisis.

**Digital privacy expert, anonmyity researcher, and author of book "Queer Privacy" [@SarahJamieLewis](https://twitter.com/SarahJamieLewis)’s Twitter thread on the perils of #LocationPrivacy is a must read:**
* Jamie Lewis, Sarah (2020, March 23). Twitter Thread, 12/12 [#Opinion, Twitter].
  * Retrieved from https://twitter.com/sarahjamielewis/status/1242142313192644608?s=2.
  > KEYQUOTE: There is no such thing as a robust privacy preserving contact tracing tool because social graphs and location graphs are impossible to anonymity because anonymity is fundamentally about  removing social and location context - once you do that all that is left is the honour system.
  
**My Twitter RT about her thread**

* Allen, Christopher (2020, March 23). Twitter Thread, 12/12 [#Opinion, Twitter].
  * Retrieved from https://twitter.com/ChristopherA/status/1244346104054865920.
  > KEYQUOTE: Despite that I agree with those like @SarahJamieLewis that a key problem is that the task of #LocationPrivacy & real anonymity is extremely difficult, I do believe that in the short term we can be pragmatic & not suffer “the perfect is the enemy of the good… An effective Honor System is not the worst short-term outcome. We also need to set the stage to invest in the much more difficult problems of solving these problems long-term.

**Excerpt of one particular email from me to W3C-CCG list, about despite the challenge we must work this privacy tech:** 

* Allen, Christopher (2020, March 29). AGENDA W3C Credentials CG Call. [#Review, W3C].
  * Retrieved from https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0125.html
  > KEYQUOTE: Despite that I agree with those that a key of the problem is that the task of [#LocationPrivacy](https://twitter.com/hashtag/LocationPrivacy) and anonymity is extremely difficult, I do believe that in the short term we can be pragmatic & not suffer “the perfect is the enemy of the good”. We can share best practices, salute those doing the right thing, shame those who do not, and demonstrate our commitment to both the common good as well as to preventing individual harm. An effective Honor System is not the worst short-term outcome.
  > We also need to set the stage so that in the long term we can invest in the much more difficult problems of solving these problems more idealistically correctly. We need to fund things like deep requirements engineering, great user centric design including nudge/incentive/mechanism/ approaches, as well implementing the latest secure code practices, privacy protocols, zk-proofs and other modern cryptographic security approaches, etc.
  > For if we do not be somewhat pragmatic now, and set a stage to be able to invest in a more ideal future, we risk that everything we are currently doing on the privacy front now will fail because in the end, everyone will being tracked at another layer."
  
**Important academic paper on how easy it is to be able to de-anonymize supposedly anonomized location data.
  
* Luc Rocher, Julien M. Hendrickx & Yves-Alexandre de Montjoye (2019, Jul 23). Estimating the success of re-identifications in incomplete datasets using generative models. [#Opinion #Review, Nature Communications].
  * Retrieved from https://www.nature.com/articles/s41467-019-10933-3.
  > KEYQUOTE: Moving forward, they question whether current de-identification practices satisfy the anonymization standards of modern data protection laws such as GDPR and CCPA and emphasize the need to move, from a legal and regulatory perspective, beyond the de-identification release-and-forget model.
  
## Immunity Credential Technology
  
### Implementations of Immunity Credentials

** Most of the news has been about governments using cell phones & mobile apps to do #ContractTracing, but another important topic area is how we can create digital #ImmunityCertificates to allow people who have recovered from Covid-19 to leave quarantine, participate in the economic recovery, and to travel for work or family.**

#### W3C Verifiable Claims

**There has some some discussion & collaboration in the #W3C Credentials CG on what a #Covid19 Immunity Credential might look like using the #VerifiableCredentials standard.**
  * Example Immunity Passport Credential: https://github.com/w3c-ccg/vc-examples/tree/master/docs/covid-19
  * Thread (long) starts at: https://lists.w3.org/Archives/Public/public-credentials/2020Apr/0052.html
  * Thread (long) starts at: https://lists.w3.org/Archives/Public/public-credentials/2020Apr/0119.html

### General Immunity Credentials Analysis & Technology

**Important laypersons' introduction to Bayesian math and the massive difference between a 5% and a 3% margin of error for serological testing/passporting:**
* Chivers, Tom (2020, April 7). How far away are ‘immunity passports’? [#News #Opinion, Unherd].
  * Retrieved from https://unherd.com/2020/04/how-far-away-are-immunity-passports/.
  > KEYQUOTE: If you issue immunity passports on this basis, barely a third of the people you give them to will actually be immune. “There’s nothing peculiar about this statistically,” Kevin McConway, an emeritus professor of statistics at the Open University, told me. “It’s just Bayes’ theorem.” The likelihood of you having had Covid-19, if you’ve had a positive test, depends not just on the accuracy of the test but on the prevalence in the population you’re looking at.
  
**Beyond issues of immunology, Peter Story argues that we need to be design toward "co-immunology":**
* Story, Henry (2020, March 29) Co-Immunology and the Web For a Healthier World [#Opinion, #Society, #Immunology, Medium]
  * Retrieved from https://medium.com/@bblfish/co-immunology-and-the-web-43379b46688e
  > KEYQUOTE: We thus have three levels of immunities: biological, psychological and social. One should perhaps add hyper-social for the relations between states, that have over the last century put in place institutions to reduce the calamities of war. Each of these depends on the other. The body’s immunity is improved by individuals learning to adopt hygienic practices; those are helped by quarantining policies at the local and international level. At each level communication is restricted but cannot be stopped: trade, especially for medical goods and food, must continue, while new processes are put in place further to limit the spread of this microscopically small virus.

## Other Related Privacy Technologies

### Psuedoanonymous Ephemeral Locality

**I worked on some #LocationPrivacy approaches after year 1 of the iPhone. The target advocacy was not about health care but personal safety while travelling. Here they are for the record:**

* Allen, Christopher (circa 2008) Psuedoanonymous Ephemeral Locality Service API
  * Retreived from https://github.com/ChristopherA/Ephemeral-Locality-API

* Allen, Christopher (2020, 26 March) Hilbert Curves and utility for zk range proofs for privacy
  * https://twitter.com/ChristopherA/status/1243413128378892293

* Allen, Christopher (2007-2020) Various links on Hilbert Curves
  https://pinboard.in/search/u:ChristopherA?query=hilbert

  
## Related Events & Meetings

**Human Rights Foundation holds Oslo Freedom Forum, and this year is holding virtual event COVIDcon April 13-14th:**

* COVIDCON https://covidcon.org/

* > ABSTRACT: This two-day event, open to global audiences, will feature presentations and panels about the current pandemic and its relationship to state censorship, disinformation, surveillance, and civil liberties. COVIDCon sessions will showcase the difference in the responses of authoritarian regimes and democratic governments to the outbreak of the novel coronavirus.”

* Rebooting The Web of Trust https://www.WebOfTrust.info

**I have been hosting this twice a year design workshop that brings together experts in the decentralized digital identity and privacy community in a collaborative "design workshop" that has published 50+ collaborative white papers. It is where the W3C Decentralized Identifier specification was originally incubated, which is on its way to becoming an international standard.

**Unfortunately our last event in Buenos Aires where we planned to discussion #LocationPrivacy and other relatied Covid-19 privacy topics was cancelled. We are working now on plans for an event in the Fall in the EU, and expect many privacy tech, policy and regulatory experts coming specifially to work on the next generation of these technologies.**

* W3C Credentials Community Gruop https://w3c-ccg.github.io/

**I am co-chair of this World-Wide-Web Consortium (#W3C) community group, where a number of important credentials and identity specifications were nurtured to the point where they could be formalized into internation standards. Most notably, the Verifiable Credentials specification is now a full standard, and the Decentralized Identity specification is well on its way.**

**Both of these standards are key architectures toward privacy design, in particular in the short term for #ImmunityCertificates. We meet online weekly via voice and IRC on Tuesdays at 12noon ET, 9am PT, and 5pm CET. At several recent meetings we have had discussion on COVID-19 related privacy topics, and it looks like some standards around #ImmunityCredentials and #LocationPrivacy in particular will become official work items. Our meetings are open to the public, and are annonced on our public mailing list.

## New & Unsorted

**My Twitter list of technologists, advocates, policymakers, lawyers, regulators, etc. w/ a particular focus on privacy.**
* Allen, Christopher (2002-2020) Twitter "Privacy Tech & Advocacy" List [#SocialMedia #Influencers]
  * Retrieved from: https://twitter.com/i/lists/1068260260555579393

