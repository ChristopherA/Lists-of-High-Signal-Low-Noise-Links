# [#LocationPrivacy](https://twitter.com/hashtag/LocationPrivacy) [#ContactTracing](https://twitter.com/hashtag/ContactTracing)  [#PublicHealthVsPrivacy](https://twitter.com/hashtag/PublicHealthVsPrivacy) [#COVID19](https://twitter.com/hashtag/COVID19)

> This is one of my [series of lists](https://github.com/ChristopherA/High-Signal-Low-Noise-Link-Lists) of opinionated, high-signal but low-noise links on topics I care about.
>
> If you like my advocacy, my point-of-view, and my writing, as well as my travel to support local communities, my talks for those communities, and my work with organizations such as [Blockchain Commons](https://www.BlockchainCommons.com), [Rebooting the Web of Trust](https://www.WebOfTrust.info), and the [W3C Credentials CG](https://w3c-ccg.github.io), I invite you to sponsor me.
>
> Plus, it's a way to plug into an advocacy network that's not focused on the "big guys". Most of the large corporations have full-time people representing their desires in the various standards orgs, making it hard for small companies and lone developers to fully participate. I work to represent smaller developers in a vendor-neutral, platform-neutral way, helping us all to work together.
>
> You can become a monthly patron on my [GitHub Sponsor Page](https://github.com/sponsors/ChristopherA) for as little as $5 a month; and your contributions will be multipled, as GitHub is matching the first $5,000! Alternatively, you can support my efforts by sponsoring [Blockchain Commons](https://www.BlockchainCommons.com) and our vision of the open web via a monthly [GitHub Sponsorship](https://github.com/sponsors/BlockchainCommons) or with Bitcoin via our BTCPay contribution page, [Bitcoin contribution](https://btcpay.blockchaincommons.com).
>
> But please don’t think of this as a transaction. It’s an opportunity to advance the open web, digital civil liberties, and human rights together. You get to plug into my various projects, and hopefully will find a way to actively contribute to the digital commons yourself. Let’s collaborate!
>
> -- Christopher Allen <ChristopherA@LifeWithAlacrity.com\>, Github: [@ChristopherA](https://github.com/ChristopherA), Twitter: [@ChristopherA](https://twitter.com/ChristopherA)

# Table of Contents

- [Status & Copyright](#status---copyright)
- [Related Lists](#related-lists)
- [My Personal POV](#my-personal-pov)
- [Contact Tracing Primer](#contact-tracing-primer)
  * [Background: Contact Tracing](#background--contact-tracing)
  * [Introduction to Contact Tracing Technology (CTT)](#introduction-to-contact-tracing-technology--ctt-)
  * [General criticisms of CTT](#general-criticisms-of-ctt)
    + [Criticism 1: Effectiveness](#criticism-1--effectiveness)
    + [Criticism 2: Potential for Exploitation](#criticism-2--potential-for-exploitation)
    + [Criticism 3: Privacy Erosion (Location, Other)](#criticism-3--privacy-erosion--location--other-)
- [Current Implementations of CTT](#current-implementations-of-ctt)
  * [Overview of CTT projects](#overview-of-ctt-projects)
  * [Commentary on specific CTT projects](#commentary-on-specific-ctt-projects)
  * [Unsorted list of specific CTT projects](#unsorted-list-of-specific-ctt-projects)
- [CTT Recommendations](#ctt-recommendations)
  * [Guidelines for Technologists](#guidelines-for-technologists)
  * [Policy Considerations for Governments](#policy-considerations-for-governments)
- [Recent CTT News](#recent-ctt-news)
- [Unsorted CTT Links](#unsorted-ctt-links)
- [Related Materials](#related-materials)
  * [Twitter Lists](#twitter-lists)
  * [Notable Tweets](#notable-tweets)
  * [Other Privacy Technologies](#other-privacy-technologies)
    + [Pseudoanonymous Ephemeral Locality](#pseudoanonymous-ephemeral-locality)
  * [Events & Meetings](#events---meetings)
    + [ImPACT 2020 (2020, April 16. Recording available)](#impact-2020--2020--april-16-recording-available-)
    + [W3C CCG](#w3c-ccg)
    + [Rebooting the Web of Trust](#rebooting-the-web-of-trust)
  * [Sponsorship](#sponsorship)

# Status & Copyright

- Version 0.2.0 (2020, April 18) New structure, courtesy Vinay Taylor ([Github:@VinayTaylor](https://github.com/vinaytaylor) [Twitter:@VinayTaylor](https://twitter.co/VinayTaylor))
- Version 0.1.0 (2020, April 14) First relatively complete release. Had to move [#VerifiableClaims #ImmunityCredentials #COVID19](./ImmunityCredentials-VerifiableClaims-COVID19.md) to another list.

For information on this versioning scheme, see [Status & Versioning](./README.md#status--versioning).

Copyright ©2020 by Christopher Allen, and is shared under CC-BY-SA open-source license. See this repo's [README.md](./README.md#copyright--license) for more details.

# Related Lists

- [#VerifiableClaims #ImmunityCredentials #COVID19](./ImmunityCredentials-VerifiableClaims-COVID19.md)

# My Personal POV

**This is my most recent presentation explaining why I'm involved in the Self-Sovereign Identity movement, as part of a [#Foremembrance](https://twitter.com/hashtag/Foremembrance) this March during an SSI Meetup virtual event. I talk about some important historical context from WWII in the Netherlands and how it is relevant to the impact and risk of COVID-19 for privacy and identity systems:**

* Allen, Christopher (2020, 27 March). How to avoid another identity tragedy with SSI. [#SSI [#Foremembrance](https://twitter.com/hashtag/Foremembrance) #Opinion #Presentation, SSI Meetup].
  * Presentation retrieved from https://docs.google.com/presentation/d/1lO6vik7UkXQEhAWtVsaF3Bn_KUAUhZsTflTPjeF3aSw
  * Video retrieved from https://www.youtube.com/watch?v=isanNSDoSnE.
  > KEYQUOTE: Some of these things we've been fighting for a long time...in this crisis there is the opportunity to identify some best practices that are do-able now, and put some appropriate energy into better solutions that we can implement for maybe not this crisis, but for the next one.

**I am co-chair of this World-Wide-Web Consortium (#W3C) community group, where a number of important credentials and identity specifications were nurtured to the point where they could be formalized into international standards. Most notably, the Verifiable Credentials specification is now a full standard, and the Decentralized Identity specification is well on its way.** 
**We meet online weekly via voice and IRC on Tuesdays at 12noon ET, 9am PT, and 5pm CET. At several recent meetings we have had discussion on #COVID19 related privacy topics, and it looks like some standards around #ImmunityCredentials in particular will become official work items. Our meetings are open to the public and are announced on our public mailing list.**

**Both of these standards are key architectures toward privacy design, in particular in the short term for #ImmunityCertificates (see my other High Signal Low Noise list on [#VerifiableClaims #ImmunityCredentials](https://github.com/ChristopherA/Lists-of-High-Signal-Low-Noise-Links/blob/master/ImmunityCredentials-VerifiableClaims-COVID19.md).**

* W3C Credentials Community Group https://w3c-ccg.github.io/

**Excerpt of one particular email from me to W3C-CCG list, about why we must work on this privacy tech despite the challenges:** 

* Allen, Christopher (2020, March 29). AGENDA W3C Credentials CG Call. [#Review, W3C].
  * Retrieved from https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0125.html
  > KEYQUOTE: Despite that I agree with those that a key of the problem is that the task of [#LocationPrivacy](https://twitter.com/hashtag/LocationPrivacy) and anonymity is extremely difficult, I do believe that in the short term we can be pragmatic & not suffer “the perfect is the enemy of the good”. We can share best practices, salute those doing the right thing, shame those who do not, and demonstrate our commitment to both the common good as well as to preventing individual harm. An effective Honor System is not the worst short-term outcome.
  > We also need to set the stage so that in the long term we can invest in the much more difficult problems of solving these problems more idealistically correctly. We need to fund things like deep requirements engineering, great user centric design including nudge/incentive/mechanism/ approaches, as well implementing the latest secure code practices, privacy protocols, zk-proofs and other modern cryptographic security approaches, etc.
  > For if we do not be somewhat pragmatic now, and set a stage to be able to invest in a more ideal future, we risk that everything we are currently doing on the privacy front now will fail because in the end, everyone will being tracked at another layer."

**Harvard white-paper supporting this thinking on April 3**

* Vi, Hart; et al (2020, April 3). Outpacing the Virus: Digital Response to Containing the Spread of COVID-19 while Mitigating Privacy Risks [#Opinion, #Paper, Edmond J. Safra Center for Ethics - Harvard].
    * Retrieved from https://ethics.harvard.edu/outpacing-virus
    > ABSTRACT: There is a growing consensus that we must use a combined strategy of medical and technological tools to provide us with response at a scale that can outpace the speed and proliferation of the SARS-CoV-2 virus. A process of identifying exposed individuals who have come into contact with diagnosed individuals, called “contact tracing,” has been shown to effectively enable suppression of new cases of SARS-CoV-2 (COVID-19). Important concerns around protecting patient’s confidentiality and civil liberties, and lack of familiarity with available privacy-protecting technologies, have both led to suboptimal privacy implementations and hindered adoption. This paper reviews the trade-offs of these methods, their techniques, the necessary rate of adoption, and critical security and privacy controls and concerns for an information system that can accelerate medical response. Proactive use of intentionally designed technology can support voluntary participation from the public toward the goals of smart testing, effective resource allocation, and relaxing some of physical distancing measures, but only when it guarantees and assures an individual’s complete control over disclosure, and use of data in the way that protects individual rights.

# Contact Tracing Primer
## Background: Contact Tracing

**Contact tracing is one the main methods being proposed to curb the spread of the virus. These are good explainers:**

* Rapaport, Lisa (2020, April 14). Explainer: What is contact tracing and how can it help fight the new coronavirus? [#News #Opinion, Reuters].
  * Retrieved from https://www.reuters.com/article/us-health-coronavirus-tracing-explainer/explainer-what-is-contact-tracing-and-how-can-it-help-fight-the-new-coronavirus-idUSKCN21W2N3.
  > KEYQUOTE: Contact tracing has been used for decades to control the spread of infectious diseases. The basic idea is simple: track down infected people, then find everyone who has been near them and encourage those people to stay home until it is clear they are not sick.

* Simmons-Duffin, Selena (2020, April 14). How Contact Tracing Works And How It Can Help Reopen The Country [#News, #Opinion, NPR].
  * Retrieved from https://www.npr.org/sections/health-shots/2020/04/14/833726999/how-contact-tracing-can-help-fight-coronavirus
  >KEYQUOTE: ...public health leaders are calling for communities around the country to ramp up capacity and get ready for a massive contact tracing effort to control the coronavirus.

**One of the best things I've read recently on the topic of #COVID19 #ContactTracing is this article that argues that we should call it "Exposure Alerting" and that many of our design problems come from naming it incorrectly.**

* Karlton, Phil (2020, April 22). Digital Contact Tracing and Alerting vs Exposure Alerting [#Opinion, Blog by Harper Reed]
  * Retrieved from https://harper.blog/2020/04/22/digital-contact-tracing-and-alerting-vs-exposure-alerting/.
  > KEY QUOTE: Digital contact tracing should be called Exposure Alerting. That is what it does. It doesn’t “trace contacts” from an epidemiological perspective. Exposure Alerting could tie in with contact tracing, but we should not conflate these separate technologies. Manual Contact Tracing is essential and is very different than Exposure Alerting Exposure Alerting should be decentralized. Manual contact tracing is centralized. Exposure Alerting has very specific privacy concerns that are very different than Manual Contact Tracing.

## Introduction to Contact Tracing Technology (CTT)

**Contact tracing apps are touted as a way out of lockdown:**

* Harkness, Timandra (2020, April 14). Can your smartphone crack Covid? [#News #Opinion, Unherd].
  * Retrieved from https://unherd.com/2020/04/can-your-smartphone-crack-covid/.
  > KEYQUOTE: Contact-tracing is also used in sexually transmitted infections, where previous partners may be contacted with advice to get themselves a test. But whereas we tend to remember our sexual partners, we tend not to remember everyone who shared our train carriage or served us in a shop several days before we had symptoms. That’s where technology could help.

* Unknown (2020, March 26). Countries are using apps and data networks to keep tabs on the pandemic. [#News #Opinion, The Economist].
  * Retrieved from https://www.economist.com/briefing/2020/03/26/countries-are-using-apps-and-data-networks-to-keep-tabs-on-the-pandemic.
  > ABSTRACT/KEYQUOTE: The use of data becomes most fraught when it moves beyond modelling and informing policy to the direct tracking of individuals in order to see from whom they got the disease. Such contact-tracing can be an important public-health tool. It also has a resemblance to modern counter-terrorism tactics.

* Singer, Natasha; Sang-Hun, Choe (2020, March 23). As Coronavirus Surveillance Escalates, Personal Privacy Plummets [#News #Opinion, New York Times].
  * Retrieved from https://www.nytimes.com/2020/03/23/technology/coronavirus-surveillance-tracking-privacy.html.
  > KEYQUOTE: As countries around the world race to contain the pandemic, many are deploying digital surveillance tools as a means to exert social control, even turning security agency technologies on their own civilians. Health and law enforcement authorities are understandably eager to employ every tool at their disposal to try to hinder the virus — even as the surveillance efforts threaten to alter the precarious balance between public safety and personal privacy on a global scale.

**When we talk about contact tracing technology, there are actually 3 approaches/designs. This is a good summary of each: Bluetooth Contact Tracing, Redacted Location Tracing, and Hashing Servers and Mix Nets**

* Greenberg, Andy (2020, April 8). Clever Cryptography Could Protect Privacy in Covid-19 Contact-Tracing Apps [#News #Opinion, Wired].
  * Retrieved from https://www.wired.com/story/covid-19-contact-tracing-apps-cryptography/.
  > KEYQUOTE: Users may appreciate privacy, but health care workers and governments don't necessarily want to build a system that prevents them from, say, proactively notifying users who have been potentially exposed to Covid-19, or even actively tracking the location of infected or potentially exposed people.  

**This is a simple way to understand bluetooth contact tracing, via a comic!**

* Case, Nicky (2020, April 9). Twitter Thread, 12/12 [#Opinion, Twitter].
  * Retrieved from https://twitter.com/ncasenmare/status/1248271370368114688; https://ncase.me/contact-tracing/. 
  > KEYQUOTE via @mikarv: How exactly can #DP3T privacy-preserving Bluetooth COVID-19 alerts work if identifiable personal data never leaves your device? It's actually not so complicated, and even less so now @ncasenmare has made a fantastic, public domain, comic explaining it.

## General criticisms of CTT

**I’m pleased that the Netherlands government had their attorney general take a serious look at several contact tracing proposals.**

* Cluskey, Peter (2020, April 23). Netherlands abandons initial plan to develop Covid-19 tracing app [#News, The Irish Times].
  * Retrieved from https://www.irishtimes.com/news/world/europe/netherlands-abandons-initial-plan-to-develop-covid-19-tracing-app-1.4236355
  > KEY QUOTE: The government’s problems became even more acute last weekend when attorney general Reimer Veldhuis was asked to assess the final seven contenders for compliance with privacy laws – and found all seven lacking.

**This explains some of the technical flaws with respect to privacy**

* Buchanan OBE, Prof Bill (2020, April 14). The Flawed World of Contact Tracing: Where's Carol The Tester? [#Opinion, Medium].
  * Retrieved from https://medium.com/asecuritysite-when-bob-met-alice/the-flawed-world-of-contact-tracing-wheres-carol-the-tester-3939ac92488a.
  > KEYQUOTE: The whole discussion on user and contact tracing opens up a whole lot of questions, and the most fundamental of these is that we don’t actually have any real infrastructure to implement privacy-preserving methods. It is likely that a COVID-19 app would be a pin-point app, and where the data gathered for location and contact tracking could be easily abused, and would have limited scope outside a country’s borders. Our core problem is that we have built data infrastructures that mirror those from the 1980s, and where we care little about the core rights of the data we gather. Once captured, the owner becomes the entity who captured the data, and without the trustworthiness of the transactions involved, we leave it open to abuse for malicious activities.

**A real problem in the current crop of #ContactTracing approaches is not precisely the technology, but instead social incentive design and adversarial resistance to attacks**
* Anderson, Ross (2020, April 12). Contact Tracing in the Real World [#Opinion #Analysis, Security Research at the University of Cambridge]
    * Retrieved from https://www.lightbluetouchpaper.org/2020/04/12/contact-tracing-in-the-real-world/.
>ABSTRACT: Here are some problems with private contact tracing. We should not give policymakers the false hope that they can avoid hard choices
>KEYQUOTE: The performance art people will tie a phone to a dog and let it run around the park; the Russians will use the app to run service-denial attacks and spread panic; & little Johnny will self-report symptoms to get the whole school sent home.

**Former FDA Commissioner Dr. Scott Gotlieb ([@ScottGottliebMD](https://twitter.com/ScottGottliebMD)) calls for far greater public health surveillance to help stem COVID, but is skeptical of #ContactTracing apps.**
* McLellan, Mark; Gottlieb, Scott; Mostashari, Farzad; Rivers, Caitlin; Silvis, Lauren (2020, April 7) A National COVID-19 Surveillance System: Achieving Containment [#Opinion #Implementation, Duke-Margolis Center for Health Policy]
  * Retrieved from https://healthpolicy.duke.edu/sites/default/files/atoms/files/covid-19_surveillance_roadmap_final.pdf.
  > KEYQUOTE: Cell phone-based apps recording proximity events between individuals are unlikely to have adequate discriminating ability or adoption to achieve public health utility, while introducing serious privacy, security, and logistical concerns. Instead, timely contact tracing can be achieved through strengthened public health case investigation augmented by technology and community-level collaborations.

### Criticism 1: Effectiveness

**A key concern of #ContactTracing apps is the huge adoption required for them to be effective. Other than coercive use in China, Singapore has the largest % acceptance of these apps (6% maybe), but many academics question the efficacy:**
* Ferritti, Luca, et al. (2020, March 31) Quantifying SARS-CoV-2 transmission suggests epidemic control with digital contact tracing [#News #Opinion, Science Magazine].
  * Retrieved from https://science.sciencemag.org/content/early/2020/04/09/science.abb6936
  > KEYQUOTE: If this is an accurate picture of viral spread in Europe and not an artefact of early growth, epidemic control with only case isolation and quarantining of traced contacts appears implausible in this case, requiring near-universal App usage and near-perfect compliance. The App should be one tool among many general preventative population measures such as physical distancing, enhanced hand and respiratory hygiene, and regular decontamination.

**Even if there's high adoption, questions remain about whether tech-only solutions even work:**

* Ng, Alfred (2020, April 13). Tech isn't solution to COVID-19, says Singapore director of contact tracing app [#News #Opinion, Cnet].
  * Retrieved from https://www.cnet.com/news/director-behind-singapores-contact-tracing-app-says-tech-isnt-the-solution-to-covid-19/
  > KEY QUOTE In the weeks since Singapore released its contact tracing app, the government has seen technology's shortcomings for tracking COVID-19. Despite the government's public campaign to the country to download the app, only about one in six people in Singapore have actually done it, Singapore's national development minister Lawrence Wong said on April 1.
 
  > Bay also noted several issues with an overreliance on mobile contact tracing, pointing out that the apps would not have flagged cases where the coronavirus spread, including an incident in Washington where 45 members of a choir were diagnosed with COVID-19. 

  > "If you ask me whether any Bluetooth contact tracing system deployed or under development, anywhere in the world, is ready to replace manual contact tracing, I will say without qualification that the answer is, no," Bay said in the post.

* Doffman, Zak (2020, April 12). Forget Apple And Google—Here’s The Real Challenge For COVID-19 Contact-Tracing [#News #Opinion, Forbes].
  * Retrieved from https://www.forbes.com/sites/zakdoffman/2020/04/12/forget-apple-and-google-heres-the-real-challenge-for-covid-19-contact-tracing/#5d66bf7f2709
  > KEYQUOTE: Unless and until governments can either develop or mandate a system that deploys this across the majority of its population, and then backs it up with the rigorous testing regime that is stitched into the core concept of operation, such apps will be helpful but not game-changing. 

* Bay, Jason (2020, April 10). Automated contact tracing is not a coronavirus panacea [#Opinion #News #Google #Apple, Medium].
  * Retrieved from https://blog.gds-gov.tech/automated-contact-tracing-is-not-a-coronavirus-panacea-57fb3ce61d98. 
  > KEYQUOTE: An automated algorithm will necessarily generate both false negatives and false positives. A human contact tracer will similarly make mistakes. However, because a human contact tracer would seek to incorporate information beyond just physical proximity, he/she can correct for systematic biases introduced by automated notification system.
 
  > Encounters between individuals can be classified into close, casual and transient contacts for epidemiological purposes, based on proximity and duration of contact. However, these classifications depend on factors such as location/environment. For example, short-duration encounters in enclosed spaces without fresh ventilation often constitute close contact, even if encounter proximity and duration do not meet algorithmic thresholds.

  > Since Bluetooth-based contact tracing solutions do not, by themselves, record location/environment data, this information needs to be obtained through other means — a human-led contact tracing interview.

**There are also fundamental questions about the specificity of the tech**

* Estrin, Daniel (2020, March 19). Israel Begins Tracking And Texting Those Possibly Exposed To The Coronavirus. [#News #Opinion, NPR].
  * Retrieved from https://www.npr.org/2020/03/19/818327945/israel-begins-tracking-and-texting-those-possibly-exposed-to-the-coronavirus.
  > KEYQUOTE: It's likely that Israelis who were not within 2 meters (6 feet) of distance from a virus carrier will still be identified for quarantine. Sharon Perry, a cellular tracing expert, said the GPS technology of civilian mobiles can pinpoint a person's location only within 5 to 6 meters' accuracy if the cellphone is outdoors, or 10 to 20 meters if the phone is indoors. But he argued the breach of privacy was justified.

### Criticism 2: Potential for Exploitation

**Criticism isn't always about the implementation of these technologies, but also the concerns about the parties doing the implementations**
* Franceschi-Bicchierai, Lorenzo (2020, April 2). We Saw NSO's Covid-19 Software in Action, and Privacy Experts Are Worried. [#News #Opinion, Vice]. 
  * Retrieved from https://www.vice.com/en_us/article/epg9jm/nso-covid-19-surveillance-tech-software-tracking-infected-privacy-experts-worried.
  > ABSTRACT: Every citizen of the world wants to go back to normal as soon as possible. The gold rush to surveillance technology could easily mean that there is a normal expectation of privacy that we will have a hard time going back to.
  > KEYQUOTE: In the spirit of never letting a good crisis go to waste, several companies around the world— some already notorious and some less public—are pitching and developing surveillance tools to help governments track citizens with the goal of stopping the spread of coronavirus. For critics, however, this is an unnecessary escalation justified by a tragic health crisis.

**Some governments will misuse new surveillance technology; my concerns about this continue to be justified:**

* Mackinnon, Mark; Venderklippe, Nathan. (2020, April 6). How the coronavirus pandemic is making strongmen stronger, from Hungary to Serbia to the Philippines [# News #Opinion, The Globe and Mail].
  * Retrieved from https://www.theglobeandmail.com/world/article-how-the-coronavirus-pandemic-is-making-strongmen-stronger-from/.
  > KEYQUOTE: With governments around the world adopting extraordinary measures amid the pandemic, ostensibly to protect their citizens – but often in directions that have little or nothing to do with public health – one of the most potent legacies of this era may prove to be a global erosion of democratic freedoms. The power grabs have been dubbed “coronavirus coups” in some countries, and three months into the crisis, with no end in sight, there are concerns that leaders such as Hungary’s Viktor Orban are capitalizing on COVID-19 to seize powers they may never relinquish.

### Criticism 3: Privacy Erosion (Location, Other)

**Even before the pandemic, concerns about #LocationPrivacy were being raised.**

* Thompson, Stuart A.; Warzel, Charlie (2019, December 19). Twelve Million Phones, One Dataset, Zero Privacy [#News #Opinion, New York Times].
  * Retrieved from https://www.nytimes.com/interactive/2019/12/19/opinion/location-tracking-cell-phone.html. 
  > ABSTRACT/KEYQUOTE: The companies that collect all this information on your movements justify their business on the basis of three claims: People consent to be tracked, the data is anonymous and the data is secure. None of those claims hold up, based on the file we’ve obtained and our review of company practices. Yes, the location data contains billions of data points with no identifiable information like names or email addresses. But it’s child’s play to connect real names to the dots that appear on the maps.

**Important academic paper on how easy it is to be able to de-anonymize supposedly anonymized location data.**
  
* Luc Rocher, Julien M. Hendrickx & Yves-Alexandre de Montjoye (2019, Jul 23). Estimating the success of re-identifications in incomplete datasets using generative models [#Opinion #Review, Nature Communications].
  * Retrieved from https://www.nature.com/articles/s41467-019-10933-3.
  > KEYQUOTE: Moving forward, they question whether current de-identification practices satisfy the anonymization standards of modern data protection laws such as GDPR and CCPA and emphasize the need to move, from a legal and regulatory perspective, beyond the de-identification release-and-forget model.

**More recently, concerns have been raised again on the telecom side of [#LocationPrivacy](https://twitter.com/hashtag/LocationPrivacy). It does have me concerned that work on privacy enhanced bluetooth [#ContactTracing](https://twitter.com/hashtag/ContactTracing) (and other such approaches) is moot given what information a cell phone already allows to be correlated.**

* Espinoza, Javier and Fildes, Nic (2020, April 7). Tracking coronavirus: big data and the challenge to privacy. [#News #Opinion, Financial Times; Free to Read].
  * Retrieved from https://www.ft.com/content/7cfad020-78c4-11ea-9840-1b8019d9a987.
  > KEYQUOTE: Still, assurances from officials and industry executives have done little to appease anxiety that privacy rights could be brushed aside as governments seek to use tools of mass surveillance in their efforts to combat the virus. The concerns about political use of data have been aggravated by the fact that the European Commission wants the telecoms companies to provide the actual aggregated data, not just access to insights from that information.
  > Some researchers are not convinced by the claim that such data sets are completely anonymous. A 2019 study by researchers at Imperial College London and Belgium’s Catholic University of Louvain revealed there is a way to re-identify 99.98 per cent of individuals with just 15 demographic characteristics using location data. Other studies have come to similar conclusions that individuals can be identified based on aggregate data sets with relative ease.

**Digital privacy expert, anonmyity researcher, and author of book "Queer Privacy" [@SarahJamieLewis](https://twitter.com/SarahJamieLewis)’s Twitter thread on the perils of #LocationPrivacy is a must read:**
* Jamie Lewis, Sarah (2020, March 23). Twitter Thread, 12/12 [#Opinion, Twitter].
  * Retrieved from https://twitter.com/sarahjamielewis/status/1242142313192644608?s=2.
  > KEYQUOTE: There is no such thing as a robust privacy preserving contact tracing tool because social graphs and location graphs are impossible to anonymity because anonymity is fundamentally about  removing social and location context - once you do that all that is left is the honour system.
  
**My Twitter RT about her thread**

* Allen, Christopher (2020, March 23). Twitter Thread, 12/12 [#Opinion, Twitter].
  * Retrieved from https://twitter.com/ChristopherA/status/1244346104054865920.
  > KEYQUOTE: Despite that I agree with those like @SarahJamieLewis that a key problem is that the task of #LocationPrivacy & real anonymity is extremely difficult, I do believe that in the short term we can be pragmatic & not suffer “the perfect is the enemy of the good… An effective Honor System is not the worst short-term outcome. We also need to set the stage to invest in the much more difficult problems of solving these problems long-term.

**Despite good practices by others, governments (in this case France, and maybe the UK's NHS) will demand more than what is safe, to meet their own political desires or for efficiency of connection to their existing legacy systems. This means often they don’t look at the big picture. France/UK should be moving slower, not faster, especially given questions about efficacy of current approaches.**

* Fouquet, Helene (2020, April 21). France Says Apple Bluetooth Policy Is Blocking Virus Tracker [#News, Bloomberg].
  * Retrieved from https://www.bloomberg.com/news/articles/2020-04-20/france-says-apple-s-bluetooth-policy-is-blocking-virus-tracker 
  > KEY QUOTE: The Google-Apple system relies on smartphones’ Bluetooth connections and will allow users to keep their data on their handsets. However, France and the European Union want to feed the data to a central server, managed by state health services, which would alert users if they come into contact with a person infected by Covid-19. Any system that sends data to a centralized location is inherently less secure and is vulnerable to “mission creep,” enabling a form of surveillance on users, according to a letter on Monday from 300 academics in more than two dozen countries, which endorsed Google and Apple’s approach.

* Hern, Alex (2020, April 16). NHS in standoff with Apple and Google over coronavirus tracing [#News, The Guardian]
  * Retrieved from https://www.theguardian.com/technology/2020/apr/16/nhs-in-standoff-with-apple-and-google-over-coronavirus-tracing
  > KEY QUOTE: Apple and Google are encouraging health services worldwide to build contact-tracing apps that operate in a decentralised way, allowing individuals to know when they’ve been in contact with an infected person but preventing governments from using that data to build a picture of population movements in aggregate. But the policies, unveiled last week, apply only to apps that don’t result in the creation of a centralised database of contacts. That means that if the NHS goes ahead with its original plans, its app would face severe limitations on its operation.

# Current Implementations of CTT

**Despite these reservations, governments and private sector players across the world have started developing or deploying a dizzying array of contact tracing apps; with limited/no interoperability.**

**For example, it looks like there are twelve regional pandemic-tracking apps in China and one national one. Interestingly, the patchwork of tracking apps across China seems to show that there is actually very little coordination between localities and the central government.**

* Yang, Yuan; Liu, Nian; Wong, Sue-Lin and Liu, Qianer (2020, April 1). China, coronavirus and surveillance: the messy reality of personal data [#News #Opinion, Financial Times; Paywall].
  * Retrieved from https://www.ft.com/content/760142e6-740e-11ea-95fe-fcd274e920ca
  > KEYQUOTE: Pandemic-tracking apps are now proliferating as local governments have started trying to gain access to phone GPS location data through the apps, which are more accurate than carrier location data. The test version of the national government’s online services platform links to at least 12 provincial- or major city-level governments’ own health code apps, as well as providing a national-level app.
  
  > As is often the case when multiple bureaucracies collide, the health apps have overlapping coverage. On arriving back in Beijing from a trip out of the city, one FT reporter was told by their district authority to ignore the Beijing municipal government’s app and register on another health app used by the district. “One person, six codes”, ran the headline of a local media feature lamenting the multiplication of district- and municipal-level apps.

**The EU is striving for a more coordinated response:**

* Weber, Manfred; Pons, Esteban Gonzalez; Pérez, Iratxe García; Cioloş, Dacian; Lamberts, Philippe (2020, April 15). European Parliament resolution on EU coordinated action to combat the COVID-19 pandemic and its consequences [#News #Policy, European Parliament].
    * Retrieved from https://www.europarl.europa.eu/doceo/document/RC-9-2020-0143_EN.html
  > KEY QUOTE: Takes note of the emergence of contact-tracing applications on mobile devices in order to warn people if they were close to an infected person, and the Commission’s recommendation to develop a common EU approach for the use of such applications; points out that any use of applications developed by national and EU authorities may not be obligatory and that the generated data are not to be stored in centralised databases, which are prone to potential risk of abuse and loss of trust and may endanger uptake throughout the Union; demands that all storage of data be decentralised, full transparency be given on (non-EU) commercial interests of developers of these applications, and that clear projections be demonstrated as regards how the use of contact tracing apps by a part of the population, in combination with specific other measures, will lead to a significantly lower number of infected people; demands that the Commission and Member States are fully transparent on the functioning of contact-tracing apps, so that people can verify both the underlying protocol for security and privacy, and check the code itself to see whether the application functions as the authorities are claiming; recommends that sunset clauses are set and the principles of data protection by design and data minimisation are fully observed.

* Stolton, Samuel (2020, April 6). EU data watchdog pitches pan-European COVID-19 app. [#News #Opinion, Euractiv].
   * Retrieved from https://www.euractiv.com/section/digital/news/eu-data-watchdog-pitches-pan-european-covid-19-app
   > KEYQUOTE: Apps taking advantage of ‘bluetooth handshakes’ registered between two smartphone users when coming into close proximity with one another have received publicity recently following the establishment of a European project dubbed Pan-European Privacy-Preserving Proximity Tracing (PEPP-PT)…The technology borrows from various initiatives worldwide, including Singapore’s TraceTogether application, which has influenced other national projects in the West seeking to clamp down on the spread of the virus.

**Two of the biggest mobile app platforms, Apple and Google, are partnering on contact-tracing technology.**

* Greenberg, Andy (2020, April 10). How Apple and Google Are Enabling Covid-19 Contact-Tracing [#News, #Opinion, Wired].
  * Retrieved from https://www.wired.com/story/apple-google-bluetooth-contact-tracing-covid-19/
  > KEYQUOTE: In mid-May, they plan to release an application programming interface that apps from public health organizations can tap into. The API will let those apps use a phone's Bluetooth radios—which have a range of about 30 feet—to keep track of whether a smartphone's owner has come into contact with someone who later turns out to have been infected with Covid-19. Once alerted, that user can then self-isolate or get tested themselves.

## Overview of CTT projects

**This is a high-level review of CTT implementations by country**

* Gershgorn, Dave (2020, April 8). We Mapped How the Coronavirus Is Driving New Surveillance Programs Around the World [#News #Opinion, Medium].
  * Retrieved from https://onezero.medium.com/the-pandemic-is-a-trojan-horse-for-surveillance-programs-around-the-world-887fa6f12ec9
  > KEYQUOTE: In an attempt to stem the tide of the coronavirus pandemic, at least 30 governments around the world have instituted temporary or indefinite efforts to single out infected individuals or maintain quarantines. Many of these efforts, in turn, undermine personal privacy.

**Here is another by Linklaters, the law firm:**

* Cisse, Sonia (2020, April 16) 28 countries race to launch official Covid-19 tracking apps to reduce the spread of the virus 
  * Retrieved from https://www.linklaters.com/en/about-us/news-and-deals/deals/2020/april/28-countries-race-to-launch-official-covid-19-tracking-apps-to-reduce-the-spread-of-the-virus
  > KEY QUOTE: In a bid to harness technology to limit the spread of coronavirus, 28 countries have launched official nationwide contact-tracing apps, according to new analysis by global law firm Linklaters. A further 11 countries are known to be developing apps to trace positive cases of the virus, using either GPS or Bluetooth data, with some expected to launch in a matter of days. However, this new class of apps means that governments are facing significant data protection obstacles.

**This is a comprehensive summary of CTT implementations in the US and in 40+ countries around the world, from USC:**

* Tanaka, Nina (Last Updated: 2020, April 11). Background Research on mobile applications focused on COVID-19  [#Implementation #Review, USC Viterbi School of Engineering].
  * Retrieved from https://docs.google.com/document/d/1bgsNjPcvoz8fpOutEYiqCJpu2PWYHnGqPI3pcK9mUio/edit.
  > KEYQUOTE: Based on news stories and other online sources, with a focus on February 2020 to present.

**This is another comprehensive crowdsourced list of projects related to COVID-19 contact tracing**

* Shankari (Ongoing). Covid 19 Tracing Projects [#Implementation, GitHub].
  * Retrieved from https://github.com/shankari/covid-19-tracing-projects. 
  > KEYQUOTE: This site is a crowdsourced list of projects related to COVID-19 contact tracing using smartphones. The goal of contact tracing is to identify the contacts of people who have tested positive for COVID-19 and to advise them to self-quarantine. Large scale, highly accurate contact tracing could control the spread of epidemics and reduce the need for societal lockdowns.

## Commentary on specific CTT projects

**Early privacy analysis is positive, but it still has centralization issues (see [Implementations & Analysis](#implementations--analysis) section below for more details).**

* Benson, Jeff (2020, April 14). Privacy Safeguards in Apple-Google Platform Could Be Abused, Experts Say [#Review #Opinion #News #Google #Apple, Digital Privacy News].
  * Retrieved from https://digitalprivacy.news/2020/04/14/privacy-safeguards-in-apple-google-platform-could-be-abused-experts-say/. 
  > KEYQUOTE: ...the design is ethical so long as it’s based on “consensual interaction.” In other words, “the app only works if you agree to use it,” they said. But they’re concerned that growing acceptance of surveillance tools — “especially the privacy-by-design ones” — will normalize surveillance.

  > “Once people swallow this one, it’s easier for governments to give us other, far more dangerous pills,” they said. “What if the next one lacks a privacy-centric design?”

* Whittaker, Zack; Etherington, Darrell (2020, April 13). Q&A: Apple and Google discuss their coronavirus tracing efforts [#Review #Opinion #News #Google #Apple, TechCrunch].
  * Retrieved from https://techcrunch.com/2020/04/13/apple-google-coronavirus-tracing/. 
  > KEYQUOTE: ...use of the API will be restricted only to authorized public health organizations as identified by whatever government is responsible for designating such entities for a given country or region. There could be conflict about what constitutes a legitimate public health agency in some cases, and even disagreements between national and state authorities, conceivably, so this sounds like it could be a place where friction might occur, with Apple and Google on tricky footing as platform operators.

**Brief "first look" by Signal app's creator Moxie Marlinspike (Twitter: [@moxie](https://twitter.com/moxie)) at the Apple/Google #ContactPrivacy framework**
* Marlinspike, Moxie (2020, April 10). Twitter thread. [#Implementation #Analysis, Twitter].
  * Retrieved from https://twitter.com/moxie/status/1248707315626201088
  KEYQUOTE: So first obvious caveat is that this is "private" (or at least not worse than BTLE), *until* the moment you test positive. At that point all of your BTLE mac addrs over the previous period become linkable… Second caveat is that it seems likely location data would have to be combined with what the device framework gives you.…Third caveat is that it seems likely some kind of PII would have to be combined with what the device framework gives you. Keys published by a device have to then be in turn "published" to *all* devices in the world. That's a major DoS vector!…All that aside, these APIs are novel in terms of what becomes possible from the app layer. I'm not super optimistic about opt-in contact tracing becoming a major factor, but I do kind of anticipate that someone will end up using this for some other interesting thing.
  
**Another "first look" at Apple/Google #ContactPrivacy, this one by Zcash cryptography researcher Henry de Valence [@hdevalence](https://twitter.com/hdevalence):**
* de Valence, Henry (2020, April 10) Twitter thread [#Implementation #Analysis, Twitter].
  * Retrieved from https://twitter.com/hdevalence/status/1248661056622186496
  > KEYQUOTE: Revealing a daily tracing key reveals all of the RPIs derived from that daily tracing key, meaning that a passive adversary can correlate past RPI broadcasts from a user who reports infection.  This is a tradeoff between reporter privacy and bandwidth, also made by TCN and DP-3T. But in the Apple/Google protocol, the tradeoff isn't an adjustable knob, it's hardcoded into the protocol, so there's only one choice. And this choice might not be the optimal one. For instance, if an entire day's RPIs are revealed in one block, they may end up being linkable *across* days, because people have regular patterns of life, and a passive adversary can e.g., notice that two reports appeared at the same place each day. Figuring out the optimal tradeoff here is challenging, but if it's hardcoded into the protocol, it's not possible to change it at all.
  > …it's not totally clear to me that this actually ensures unlinkability of RPIs and MAC addresses, because the RPIs are dependent only on the time interval (also hardcoded into the protocol), rather than having a "next RPI" ratchet (as in the TCN design).
  > The other big problem with the protocol is that because there's no information attached to reports, just an implicit "tested positive" bit, the protocol assumes the existence of a single, centralized entity who can determine whether a COVID19 test happened. But this isn't the way that testing actually works! It's a huge patchwork of different agencies doing different tests, and it's already even a challenge just to collect statistics, let alone authenticate tests.

**First look at Australia's approach**

* Teague, Vanessa (2020, April 21). Tweet Thread [#Review, Twitter].
  * Retrieved from https://twitter.com/VTeagueAus/status/1252768937357438977
  > KEY QUOTE: The answer to, "Does the commonwealth government learn your contacts when you test positive?" would be, "it depends whether Google decides to tell them."

**Two early reviews of Singapore's Trace Together app and the BlueTrace protocol**
* L, Frank (2020, March 23). Trace Together Under the Hood [#Implementation #Analysis, Medium].
  * Retrieved from https://medium.com/@frankvolkel/tracetogether-under-the-hood-7d5e509aeb5d. 
* Typic, Zero (2020, March 23). Reversing Trace Together.
  * Retrieved from https://medium.com/@zerotypic/reversing-tracetogether-initial-analysis-edc940e86aa8.

## Unsorted list of specific CTT projects

**This solution proposed in New Zealand feels quite implausible to me. I’ve looked at credit card sized Bluetooth before, and the battery tech isn’t quite there for always on devices.**

* Daalder, Marc (2020, April 17). NZ considering $100m contact tracing ‘CovidCard’ [#News, Newsroom NZ].
  * Retrieved from https://www.newsroom.co.nz/2020/04/17/1132682/nz-considering-100m-contact-tracing-covidcard
  > KEY QUOTE: For those who do own a smartphone and do download apps, there will be "too much friction" preventing people from doing so. Users may be afraid of Google having their data, of the Government knowing what they are up to. They may forget their password or turn off the app because it interferes with their Bluetooth headphones. With some back-of-the-napkin math, the presentation estimates just 20 percent uptake in New Zealand - meaning just 4 percent of contacts would be traced. That's where CovidCard comes in. Built using the same underlying technology as Tile Bluetooth trackers, the tool would be the size of a credit card and distributed to every New Zealander.

**Here are some additional notable projects or specific links, not yet in the USC list (listed in alphabetical order):**

* Apple/Google Privacy Contact Tracing (2020, April 10)
  * Bluetooth Specification (2020, April 10)
    * Link https://covid19-static.cdn-apple.com/applications/covid19/current/static/contact-tracing/pdf/ContactTracing-BluetoothSpecificationv1.1.pdf
  * Cryptography Specification (2020, April 10)
    * Link https://covid19-static.cdn-apple.com/applications/covid19/current/static/contact-tracing/pdf/ContactTracing-CryptographySpecification.pdf
  * Framework API (2020, April 10)
    * Link https://covid19-static.cdn-apple.com/applications/covid19/current/static/contact-tracing/pdf/ContactTracing-FrameworkDocumentation.pdf

* Bluetrace (underlying tech used by Singapore):
  * BlueTrace is designed for decentralised proximity logging and supplements centralised contact tracing by public health authorities. Proximity logging using Bluetooth addresses a key limitation of manual contact tracing: that it is dependent on a person’s memory and is therefore limited to contacts that a person is acquainted with and remembers having met. BlueTrace therefore enables contact tracing to be more scalable and less resource-intensive.
    * Link https://bluetrace.io/
     
* Coalition
  * Coalition is a free, privacy-first contact tracing app to help stop the spread of COVID-19. Download the app to help your friends and your family stay safe.
    * Link https://www.coalitionnetwork.org/. 
          
* COVID-Defender:
  * Intelligent contact tracing using a deployment model better suited to the US market proposed by Moses Ma's FutureLab.
    * Link https://www.dropbox.com/s/lg05fp5f2d2qxry/COVID-defender%20OVERVIEW.pdf?dl=0

* EU PEPP-PT (Pan-European Privacy-Preserving Proximity Tracing):
  * PEPP-PT was created to assist national initiatives by supplying ready-to-use, well-tested, and properly assessed mechanisms and standards, as well as support for interoperability, outreach, and operation when needed.
    * Link https://www.pepp-pt.org

* FOAM project:
  * FOAM is a spatial protocol for the Ethereum blockchain that provides secure Proof of Location services.
    * Link https://blog.foam.space/introduction-to-proof-of-location-6b4c77928022

* GIDEON project:
  * GIDEON (Global Infectious Diseases and Epidemiology Online Network) is the world’s premier Global Infectious Disease knowledge management tool. 
    * Link https://www.gideononline.com/about/gideon/
    
* HITS project:
  * Human Interaction Tracking System proposed by Cy4Gate, a cyber defence and intelligence solutions provider in Italy.
    * Link to Tweet https://twitter.com/elettronicagrp/status/1242462328362237959?s=21  

* Smart Quarantine:
  * The Czech Republic will start testing the new “smart quarantine system” to track the movements of infected citizens in South Moravia (Prague region).
    * Link https://www.praguemorning.cz/czech-republic-smart-quarantine/

 * Antidote
   * Antidote uses anonymous proximity information to help curb the spread of infectious diseases. Antidote was built by Asgard Analytics, Inc. pro-bono.
     * Link https://asgardanalytics.com/antidote/

 * Nexttrace
   * Nexttrace is a system for survey-based contact tracing at scale that can be deployed by public health officials around the United States. The approach does not require advanced location-based tracking, though could incorporate data from such systems as they become available.
     * https://nexttrace.org/  

# CTT Recommendations
## Guidelines for Technologists

**This states a few compelling pros and cons to consider when balancing privacy and public health**

* Newman, Daniel (2020, April 22). Privacy Pros And Cons As Apple And Google Look Into Using Data To Trace COVID-19 [#News #Opinion, Forbes]
  * Retrieved from https://www.forbes.com/sites/danielnewman/2020/04/22/privacy-pros-and-cons-as-apple-and-google-look-into-using-data-to-trace-covid-19/#35bd94b51fa7
  > KEY QUOTE: ...the ultimate decision to track and unleash information regarding COVID-19 will not be made by us, the people. It will be made by government authorities who may or may not understand the full implications of the precedent they are setting in using surveillance in the name of public health. In this case, the cat is already out of the bag. But that happened long before any global health crisis began. The priority now should be for us as a society to understand what data is being captured, how it is being used and what, if anything will change when the health crisis is over.

**A good reply from W3C Credentials CG (where I am co-chair) to the de Montjoye questionnaire below:**

  * Booth, David (2020, April 02) W3C-CCG Mailing List [#Implementation #Analysis, W3C CCG].
    * Retrieved from https://lists.w3.org/Archives/Public/public-credentials/2020Apr/0017.html
    > KEYQUOTE: That document raises excellent questions, but I think the range of protocols (designs) for consideration should be broadened even more. All three of the toy protocols that they discuss involved a central authority -- presumably a public health agency -- that would receive information about infected or exposed individuals.  I think it would be good to also consider (list follows

**Excellent questionnaire for people designing or evaluating #ContactTracing implementations**

* de Montjoye, Yves-Alexandre; Houssiau, Florimond; Gadotti, Andrea and Florent Guepin (2020, April 2). Evaluating COVID-19 contact tracing apps? Here are 8 privacy questions we think you should ask. [#Opinion #Implementation, Computational Privacy Group].
  * Retrieved from https://cpg.doc.ic.ac.uk/blog/evaluating-contact-tracing-apps-here-are-8-privacy-questions-we-think-you-should-ask/
  > KEYQUOTE: In-depth formal analysis of the protocol is necessary before deployment and should be published. Protecting privacy should rely on mathematical proofs of correctness, with mitigation strategies considered only when necessary. Our questions focus on privacy aspects, but ensuring security is similarly crucial. This means, for example, supervising the integrity and authenticity of the crowdsourced data, evaluating how mobile malware could affect the app’s behavior, or assessing the resilience of the authority’s servers against intrusions.
  > Building a contact tracing app that allows all of us to participate in the fight against COVID19 is possible, but it will require us to go beyond shallow reassurances that privacy is protected.

**Guidelines from the Electronic Frontier Foundation**

* Crocker, Andrew; Hoffman-Andrews, Jacob (2020, April 6). How to Protect Privacy When Aggregating Location Data to Fight COVID-19 [#Opinion, Electronic Frontier Foundation].
  * Retrieved from https://www.eff.org/deeplinks/2020/04/how-protect-privacy-when-aggregating-location-data-fight-covid-19
  > KEY QUOTE: In general, our advice to organizations that consider sharing aggregate location data: Get consent from the users who supply the data. Be cautious about the details. Aggregate on the highest level of generality that will be useful. Share your plans with the public before you release the data. And avoid sharing “deidentified” or “anonymized” location data that is not aggregated—it doesn’t work.

**Two technologist's first take on how to securely approach #ContactPrivacy**
  
* Hoepman, Jaap-Henk (2020, March 25). Hansel and Gretel and the Virus: Privacy Conscious Contact Tracing. [#Opinion, XOT.nl].  
  * Retrieved from https://blog.xot.nl/2020/03/25/hansel-and-gretel-and-the-virus-privacy-conscious-contact-tracing/

  > KEYQUOTE: Inspired by Apple’s protocol, we could create a system where devices leave a trail of breadcrumbs (like Hansel and Gretel in their fairy tale) consisting of their location and identity. The system can be made privacy conscious by ensuring that this trail is not maintained in any central database (like the NHS proposal outlined above does), and making sure the breadcrumbs disappear after some time.

* Harrison, Sara (2020, 24 March). When Is Anonymous Not Really Anonymous?. [#News #Opinion, Ask The Markup].
  * Retrieved from https://themarkup.org/ask-the-markup/2020/03/24/when-is-anonymous-not-really-anonymous.
  > KEYQUOTE: Differential privacy protects individuals in the data set by intentionally introducing mathematical randomness, also called noise, into the data set. The amount of noise can be shared publicly, just like an error rate, but no one can know which statistics are the noise and which are real people. This solution gives researchers access to the database, but it also protects the privacy of the individuals in the set.

**Human Rights, Privacy Law, and GDPR expert Elizabeth Renieres ([@hackylawyer](https://twitter.com/hackylawyer) regularly has great insights on the intersection of privacy technology and the law, and is always one of the first people I go to on these topics:**
* Renieris, Elizabeth M. (2020, March 23). When Privacy Meets a Pandemic. [#Opinion, Medium].
  * Retrieved from https://onezero.medium.com/when-privacy-meets-pandemic-fbf9154f80b3.
  > KEYQUOTE: So, where does this leave us as a privacy community and what is our role in the time of Corona? It means that before we debate the particulars of a specific technology or application, before we tweak certain features or functionality to better protect individual privacy, or before we impose certain transparency or accountability measures, we take a step back.
  > Before we concede that a measure is necessary and begin to assess its proportionality, we question that underlying assumption — especially when it’s coming from private companies who stand to gain from it or governments who fear being perceived as lacking control over the situation. We apply the age-old tests of legality, necessity, and proportionality — in that order. We require concrete evidence that a measure will further specific aims or achieve certain measurable outcomes.
  > If privacy advocates don’t step up and do this, who will?

**Papers on DP3T (refer to earlier comic):**

* Troncoso, Carmela; et al (2020, April 10). Decentralized Privacy-Preserving Proximity Tracing: Simplified Overview. [#Review #Implementation, GitHub Whitepaper].
  * Retrieved from https://github.com/DP-3T/documents/blob/master/DP3T%20White%20Paper.pdf
  > ABSTRACT: This document proposes a system for secure and privacy-preserving proximity tracing (aka contact tracing) at large scale. This system provides a technological foundation to help slow the spread of SARS-CoV-2 virus by simplifying and accelerating the process of notifying people who have been in contact with an infected person. The system design aims to minimise privacy and security risks for individuals and communities and guarantee the highest level of data protection.

* Troncoso, Carmela (2020, April 3). Decentralized Privacy-Preserving Proximity Tracing: Simplified Overview. [#Review #Implementation, GitHub Whitepaper].
  * Retrieved from https://github.com/DP-3T/documents/blob/master/DP3T%20-%20Simplified%20Three%20Page%20Brief.pdf.
  > KEYQUOTE: Given the concerns about the effectiveness of legal safeguards, the impossibility of anonymization, and the intrinsic vulnerabilities of centralized data minimization models, we focus on decentralized designs for privacy preserving proximity tracing. 

## Policy Considerations for Governments

**Governments today are taking legitimate emergency measures to track and manage public health, in particular in the #COVID19 crisis. We need to balance this public good vs. risks of loss of human rights in the future. We can do this!**

**This is one of the best explainers on the legal considerations around contact tracing apps in the US:**

* Chesney, Robert (2020, April 14). COVID-19 Contact Tracing We Can Live With: A Roadmap and Recommendations [#News #Opinion, LawFare].
  * Retrieved from https://www.lawfareblog.com/covid-19-contact-tracing-we-can-live-roadmap-and-recommendations
  > KEY QUOTE Notably, it is not clear that such legislation could be enacted at the federal level, as a constitutional matter. It likely would generate a Sebelius-style challenge, with litigants contending that it amounts to the mandatory use of a product akin to the mandatory purchase of health insurance under the Affordable Care Act. The Supreme Court held in Sebelius that Congress cannot rely on its Interstate Commerce authority to command individuals to engage in a commercial purchase when they would otherwise do no such thing, and even rejected the idea that such an authority can be derived from the Necessary and Proper Clause due to the critical role such purchases played in support of the larger, otherwise-constitutional insurance rules established by the statute. Might the same be true here? True, the requirement to download and use an app for public-health data-collection purposes is not in itself necessarily best viewed as a commercial activity. But then again neither was the must-eat-broccoli hypothetical that Chief Justice John Roberts used to illustrate the dangers of empowering Congress to make us take affirmative actions. Sebelius might best be read as a broad rule against federal legislative authority to compel affirmative activity, not just one barring statutory obligations to buy things.

**Specific Senate Committee hearing on big data and COVID-19** 

* Calo, Prof Ryan (2020, April 9). Enlisting Big Data in the Fight Against Coronavirus [#Opinion, Senate	Committee on Commerce, Science, and Transportation].
    * Retrieved from https://www.commerce.senate.gov/services/files/D069F0C0-2B67-4999-AC75-5BC41D14D00C
    > ABSTRACT: The appeal of contact tracing apps is intuitive. Many Americans today face a Hobson's cjhoice: remain at hjome in isolation, leaving social relations (and the economy) in tatters; or venture out into the world and potentially contract and spread COVID-19. The developers of contact tracing apps hope to offer a third way: safe mobility even in the absence of herd or vaccine immunity by crowd-sourcing the detetion and avoidance. Laudable as this goal may be, the technique is unproven and the drawbacks potentially significant.

**Given EU GDPR and California CPRA, it is very hard to meet those privacy laws and regulatory standards for #LocationPrivacy.**
* Gray, Stacey; et al (2020, March 25). A Closer Look at Location Data: Privacy and Pandemics [#News #Opinion, Future of Privacy Forum].
  * Retrieved from https://fpf.org/2020/03/25/a-closer-look-at-location-data-privacy-and-pandemics/.
  > ABSTRACT/KEY QUOTE: Typically, we think of location data as having privacy implications when it is precise enough to single out an individual with reasonable specificity...Measuring precise location depends in part on context, such as population density...Recent legislative proposals have attempted to create strict cut-offs (such as an 1,640 foot radius under the U.S. House and Commerce Discussion Draft, or an 1,850 foot radius under the California Privacy Rights Act ballot initiative of 2020).

* Hernandez, Lorena (2020, January 27). Report: Guidelines for public administrations on location privacy - Version 2 [#Law #Regulatory, European Location Interoperability Solutions for e-Government].
  * Retrieved from https://joinup.ec.europa.eu/collection/elise-european-location-interoperability-solutions-e-government/document/report-guidelines-public-administrations-location-privacy-version-2.

  > ABSTRACT/KEYQUOTE: The guidelines address the privacy implications of handling location data by public administrations and identify potential risks related to the processing of personal location data.

**Some thoughts on Privacy Impact Assessments and other methods to ensure checks on exceptional surveillance**

* McDonald, Sean (2020, March 30). The Digital Response to the Outbreak of COVID-19 [#Opinion, Centre for International Governance Innovation].
  * Retrieved from https://www.cigionline.org/articles/digital-response-outbreak-covid-19.
  > KEYQUOTE: Undeniably, we need to use technology as part of disaster response, but the regulatory immaturity of the industry makes technology companies risky allies, even in the best of circumstances
  > The way that we enable, administer and check the exceptional surveillance and social powers that each government exerts to contain COVID-19…will frame an important part of the future of state power in a world with increasing emergencies.
  >While the risks and harms associated with digital surveillance are often framed as related to privacy, there are significantly larger issues that apply during a pandemic, such as the escalation of government powers. "

* Johnston, Anna (2020, March 31). Privacy in a pandemic: Keep calm, and remember first principles [#News #Opinion, Salinger Privacy].
  * Retrieved from https://www.salingerprivacy.com.au/2020/03/31/privacy-in-a-pandemic/.
  > KEYQUOTE: Indeed a national committee of all the Australian privacy regulators has been formed to respond to COVID-related proposals with national implications (such as development of a contact tracing tool), and they have reiterated the value of conducting short-form Privacy Impact Assessments on proposed solutions to public health and economic problems, to make sure privacy is considered in the design process.  

**And pandemic responses for the Western world may not be suitable for developing nations, here are some useful general guidelines for policymakers with a focus on India as an example:**

* Rajagopalan, Shruti; Tabarrok, Alexander (April 9, 2020). Pandemic Policy in Developing Countries: Recommendations for India [#Opinion, #Policy]
  * Retrieved from https://www.mercatus.org/publications/covid-19-policy-brief-series/pandemic-policy-developing-countries-recommendations-india
   > KEY QUOTE: India needs to find local solutions suited to its unique context to effectively deal with the pandemic. We have collated 10 recommendations for the Indian context, many of which will also apply to other developing countries.

# Recent CTT News
*(Most recent first)*

**In this section, I try to highlight some key articles I found interesting on the topics of #LocationPrivacy #ContactTracing #PublicHealthvsPrivacy #COVID19. There's a lot of material published daily, so on a rolling basis I will limit this list to 20-25 relevant articles:**

* Stiffler, Lisa (2020, April 22). UW and Microsoft release contact-tracing app, aiming to battle COVID-19 while preserving privacy [#News, Geekwire]
  * Retrieved from https://www.geekwire.com/2020/uw-microsoft-release-contact-tracing-app-aiming-battle-covid-19-preserving-privacy/amp/
  KEY QUOTE: CovidSafe, released today as a “demonstration app,” is designed to help with both manual tracing, where a public health official interviews someone who has coronavirus to determine with whom they’ve been in contact; and automated tracking, which uses devices like smartphones to follow who’s been in close proximity with whom, and notify people of an exposure. When a person tests positive for coronavirus, health officials will ask them to recall where they’ve been and whom they’ve been near over the previous two weeks. But it can be difficult to remember that information, particularly given how days blur in the absence of normal routines for work and school. The app will help users access the GPS-based location data that our phones are already gathering, and share that with health workers.

* Giglio, Mike (2020, April 22). Would You Sacrifice Your Privacy to Get Out of Quarantine? [#Opinion, The Atlantic].
  * Retrieved from https://www.theatlantic.com/politics/archive/2020/04/coronavirus-pandemic-privacy-civil-liberties-911/609172/
  > KEY QUOTE: Since 9/11, for example, information acquired via surveillance on national-security grounds has been used to prosecute drug crimes, food-stamp and mortgage fraud, and lying on bank statements. Conversations recorded by an Amazon Echo and heart-rate data tracked by a Fitbit have been used in criminal investigations. “There really is such a thing as surveillance creep, and surveillance programs do tend to increase beyond their initial scope,” Rozenshtein said. “Pandemics, like other emergencies, have often been these catalyst moments for the permanent expansion of the government. And the government does not tend to shrink after the moment has passed.”

* Campbell, Kwan (2020, April 21). COVID-19 contact tracing: The tricky balance between privacy and relief efforts [#Opinon, Tech Republic].
  * Retrieved from https://www.techrepublic.com/article/covid-19-contact-tracing-the-tricky-balance-between-privacy-and-relief-efforts/#ftag=RSS56d97e7
  KEY QUOTE: Australia's upcoming contact tracing app would put data into an encrypted national store that is only accessible by the states and territories' "health detectives. The Commonwealth can't access the data. No government agency at the Commonwealth level, not the tax office, not government services, not Centrelink, not Home Affairs, not Department of Education, not childcare -- the Commonwealth will have no access to that data," Morrison said.

* Mehta, Ivan (2020, April 21). India wants to build an ultra-intrusive ‘wristband’ to track coronavirus patients’ every move [#News #Opinion, The Next Web]
  * Retrieved from https://thenextweb.com/in/2020/04/22/india-wants-to-build-an-ultra-intrusive-wristband-to-track-coronavirus-patients-every-move/.
  > KEY QUOTE A technical document by the Broadcast Engineering Consultant India Limited (BECIL) described the band as an “Intelligence investigation platform & tactical tool to detect, prevent and investigate threats to national security using CDR, IPDR, Tower, Mobile Phone Forensics Data.” The idea is to pair this hardware solution with the Aarogya Setu app, and get information about patients and people under quarantine including their location data and people they’re in contact with.

* Warrell, Helen (2020, April 17). Majority in UK support use of mobile phones for coronavirus contact tracing [#News #Opinion, Financial Times, Paywall].
  * Retrieved from https://www.ft.com/content/1752affb-24dc-4ad9-8503-78f9ce1adca9
  > KEY QUOTE: The survey, commissioned by the Financial Times, suggests that concern over public health is trumping privacy worries as ministers look to technology as a way of managing the outbreak and easing lockdown restrictions. When asked, 65 per cent of people said they agreed with using smartphones to identify people who had been diagnosed with the virus and establish who they had come into close contact with. Support for the idea rose to 73 per cent among 55 to 75-year-olds and fell to 59 per cent in those aged 18 to 34.

* Urerti, David (2020, April 17). Coronavirus Surveillance Highlights Need for Federal Privacy Law [#News #Opinion, Wall Street Journal].
  * Retrieved from https://www.wsj.com/articles/coronavirus-surveillance-highlights-need-for-federal-privacy-law-11587115801
  > KEY QUOTE: New federal protections could also improve public trust in apps and devices that require users to opt in to share data with health authorities, said Graham Dufault, senior director for public policy at ACT | The App Association, a trade group. “The absence of a federal privacy framework has left us less prepared to respond to the crisis with a coordinated, data-driven, and trusted effort,” Mr. Dufault wrote.

* Smith-Spark, Laura (2020, April 16). These countries are reopening after coronavirus -- here's how they're doing it [#News #Opinion, CNN Health].
  * Retrieved from https://edition.cnn.com/2020/04/11/health/european-countries-reopening-coronavirus-intl/index.html
  > KEY QUOTE the countries preparing to ease restrictions had something in common: they were among the first in Europe to implement lockdowns or severe social distancing measures and had rapidly scaled up coronavirus testing. "They had these things in place and as a result they are already past the peak of infections there," he said. The numbers of coronavirus-related deaths in these nations are in the tens or hundreds, rather than the thousands, he said, and "they are in a much better place because of proactive action."

* Selinger, Evan (2020, April 15). The Lasting Privacy and Civil Liberties Impacts of Responses to COVID-19 [#Opinion, OECD Forum]. 
  * Retrieved from https://www.oecd-forum.org/users/386048-evan-selinger/posts/65529-the-lasting-privacy-and-civil-liberties-impacts-of-responses-to-covid-19
  > KEY QUOTE: By emphasising efficacy as a first-order concern for determining whether to run a new surveillance programme or use new surveillance features during the crisis, we’re making the case that evidence-based considerations are fundamental. These considerations include the fact that transaction costs and opportunity costs matter: the easier it is to surveil, the more tempting it becomes; and, investing resources in expanding and accessing surveillance infrastructure weakens the prospects for dismantling it. Also, surveillance and mission creep go hand-in-hand: over time, the mandate for using data or a data-collecting instrument for a specific purpose can change and become more expansive. And the more accustomed people become to using a technology, the harder it can be to break them of the habit.

**San Francisco is implementing contact tracing, with a focus on technology, but a reliance on actual contact tracing workers:**

* Unknown (2020, April 15). San Francisco Launches Innovative Contact Tracing Program to Strengthen Coronavirus Response [#News, Office of the Mayor - San Francisco].
  * Retrieved from https://sfmayor.org/article/san-francisco-launches-innovative-contact-tracing-program-strengthen-coronavirus-response
  > KEY QUOTE: San Francisco’s new program will engage with individuals who test positive for COVID-19 to identify whom they have had contact with in recent days. Specially trained outreach workers will then follow up remotely with any individuals who may have been in contact with the COVID-positive patient. These conversations will be voluntary, confidential, and culturally and linguistically appropriate. Immigration status will have no bearing on these conversations.

  > Case contacts will be able to receive daily text messages or phone calls checking in on their health and symptoms throughout the 14-day monitoring period. They can self-report symptoms via text, immediately alerting public health officials that follow up or testing may be required.

  > The new program will amass an unprecedented number of personnel to respond immediately by phone and text across the city, and potentially the region, whenever there is a newly confirmed case, in order to take immediate action to prevent the spread among contacts as much as possible. This capability will enable the City to move forward after the shelter in place order is lifted.

* Kemp, Katharine (2020, April 15). Privacy and health: COVID-19 tracking apps [#News #Opinion, University of New South Wales].
  * Retrieved from https://newsroom.unsw.edu.au/news/business-law/privacy-and-health-covid-19-tracking-apps
  > KEY QUOTE: The app would be offered on an ‘opt in’ basis, so that only Australians who choose to download the app would be part of the scheme. To be effective, at least 40 per cent of Australians would need to download the app. It is therefore critical the app does all that is reasonable to protect our privacy.

* Unknown (2020, April 15). WHO’s polio surveillance team, other field staff join COVID19 fight [#News, World Health Organization].
  * Retrieved from https://www.who.int/southeastasia/news/detail/15-04-2020-who-s-polio-surveillance-team-other-field-staff-join-covid19-fight
  > KEY QUOTE: India’s WHO National Surveillance Project, renamed as National Public Health Surveillance Project post-polio elimination, has supported a number of public health emergency responses, including Ebola, with 50 of its surveillance medical officers deployed to Africa.

* Nardelli, Alberto (2020, April 15). The New NHS Coronavirus App Won’t Work Without A Huge Increase In Testing And People To Do Contact Tracing [#News #Opinion, BuzzFeed News].
  * Retrieved from https://www.buzzfeed.com/albertonardelli/nhs-coronavirus-tracing-app-hancock
  > KEY QUOTE: Hancock confirmed plans on Sunday for an app that will warn users if they have been in close proximity to someone who has reported coronavirus symptoms — but officials in nations such as Singapore have warned that such apps only work as a complement to mass testing and human-led contact tracing, not a replacement. The UK has fallen well short in these areas in recent weeks. 

* Lin, Liza; Martin, Timothy W (2020, April 15). How Coronavirus Is Eroding Privacy [#News #Opinion, Wall Street Journal].
  * Retrieved from https://www.wsj.com/articles/coronavirus-paves-way-for-new-age-of-digital-surveillance-11586963028?mod=article_inline
  > KEY QUOTE: The Covid-19 pandemic is ushering in a new era of digital surveillance and rewiring the world’s sensibilities about data privacy. Governments are imposing new digital surveillance tools to track and monitor individuals. Many citizens have welcomed tracking technology intended to bolster defenses against the novel coronavirus. Yet some privacy advocates are wary, concerned that governments might not be inclined to unwind such practices after the health emergency has passed.

* Sharma, Sanchita (2020, April 15). Aarogya Setu has 50 million users in 13 days, beats ‘Pokémon GO’ record [#News, Hindustan Times]. 
  * Retrieved from https://www.hindustantimes.com/india-news/aarogya-setu-has-50-million-users-in-13-days-beats-pokemon-go-record/story-4Q25vLRuezSuzPA8jboLEL.html
  > KEY QUOTE India’s coronavirus disease (Covid-19) contact-tracing app Aarogya Setu (health bridge) became the world’s fastest growing mobile app on Tuesday night with 50 million users in 13 days. Of these, 11 million were in a single day after Prime Minister Narendra Modi urged people to download the application in his third televised address to the nation, according to the Niti Aayog team lead.

* Cox, Joseph (2020, April 14). How Google Plans to Push Its Coronavirus Tracing Feature to Android Phones [#News #Opinion, Vice].
  * Retrieved from https://www.vice.com/en_us/article/dygbmj/how-google-coronavirus-contact-tracing-feature-update
  > KEY QUOTE On a call with reporters Monday, Google said it was using the Play Services mechanism to update phones with the contact-tracing system. Not to be confused with the Play Store, Play Services is used to push new features to apps such as Google Maps or install new APIs without requiring a full update of the Android operating system itself. Google told Motherboard that Play Services is updated automatically, and that it can use Play Services to push the contact-tracting update to phones as far back as devices running Android 6. 

* Faleiro, Sonia (2020, April 13). What the world can learn from Kerala about how to fight covid-19 [#News #Opinion, MIT Technology Review].
  * Retrieved from https://www.technologyreview.com/2020/04/13/999313/kerala-fight-covid-19-india-coronavirus/
  > KEY QUOTE While the rest of India, along with countries such as the UK and the US, wouldn’t take stringent steps to limit movement for another two months, Shailaja had ordered Kerala’s four international airports to start screening passengers in January. All those with symptoms were taken to a government facility, where they were tested and isolated; their samples were flown to the National Institute of Virology 700 miles away. By February, she had a 24-member state response team coordinating with the police and public officials across Kerala.

* Ng, Alfred (2020, April 14). Apple, Google to terminate COVID-19 tracking tools once pandemic ends [#News #Opinion, Cnet].
  * Retrieved from
  > KEY QUOTE: ...it essentially keeps a temporary log of devices you've been nearby for at least two weeks, even if the IDs are anonymized. Google said it would only be used by public health officials for managing the COVID-19 pandemic, and that it will be turned off once the health crisis ends. It's still unclear when that would be.

* Roy, Avik (2020, April 14). A New Strategy for Bringing People Back to Work During COVID-19 [#Opinion, FreOpp/Medium].
  * Retrieved from https://freopp.org/a-new-strategy-for-bringing-people-back-to-work-during-covid-19-a912247f1ab5
  > KEY QUOTE Much of the traditional paradigm for managing pandemics comes from our historical experiences, especially the 1918 Spanish flu pandemic. But COVID-19 is not the flu, and those whose policy recommendations are primarily based on the 1918 experience will ignore important options for reopening the economy.
  
  > SARS-CoV-2 may not as easily lend itself to vaccine production as influenza does. And the flu affects all age groups, whereas the COVID-19 disease far more heavily impacts the elderly and those with chronic diseases.
  
  > In other words, while we must learn from our history, we must not be wedded to it. Instead, we must focus on the specific biology of the virus at hand, and the specific evidence of the disease at hand. If we do these things, we will find that we have better options to improve public health and reopen the economy than many have believed.

* Hoepman, Jaap-Henk (2020, April 11). Stop the Apple and Google contact tracing platform. (Or be ready to ditch your smartphone.) [#Opinion, XOT.nl].
  * Retrieved from https://blog.xot.nl/2020/04/11/stop-the-apple-and-google-contact-tracing-platform-or-be-ready-to-ditch-your-smartphone/. 
  > KEYQUOTE: However any decentralised scheme can be turned into a centralised scheme by forcing the phone to report to the authorities that it was at some point in time close to the phone of an infected person. In other words, certain governments or companies — using the decentralised framework developed by Apple and Google — can create an app that (without users being able to prevent this) report the fact that they have been close to a person of interest in the last few weeks. The platform itself may be decentralised. But the app developed on top of it breaks this protective shield and collects the contact information centrally regardless. This effectively turns our smartphones into a global mass surveillance tool.

* Thalen, Mikael (2020, March 27). Terrifying cellphone ‘heat map’ shows just how much people are still traveling [#News #Opinion, daily dot].
  * Retrieved from https://www.dailydot.com/debug/cellphone-heat-map-coronavirus/.
  > ABSTRACT/KEYQUOTE: X-Mode states that its “data is aggregated at the advertising ID level and associated to the device and not a physical person.” An advertising ID is assigned to devices and allows companies to tailor specific content to users based on their browsing history and activity...And while X-Mode and many other companies in the industry point to the fact their data is anonymized, researchers have found that such data can easily be linked to its owner’s identity.

* Swire, Peter (2020, March 24). Security, Privacy and the Coronavirus: Lessons From 9/11. [#Opinion, LawFare].
  * Retrieved from https://www.lawfareblog.com/security-privacy-and-coronavirus-lessons-911.

  > KEYQUOTE: ...it may become tempting for government agencies in the U.S. to seek access to location databases as a claimed way to battle the coronavirus. The usefulness of databases for tracking contacts, however, is open to serious doubt. The underlying data is often inexact. Even where two dots on the map appear close to each other, they may be on different floors of an apartment building or on opposite sides of a wall. In addition, there are innumerable other reasons why contagion may not occur between the owners of two phones in apparent proximity to each other. In short, absent an empirical showing of accuracy and actionability that does not exist to date, calls for such location tracking quite possibly are security theater rather than actual security.

* Scott, Mark; Cerulus, Laurens; Kayali, Laura (2020, March 23). Commission tells carriers to hand over mobile data in coronavirus fight [#News #Opinion, Politico EU].
  * Retrieved from https://www.politico.eu/article/european-commission-mobile-phone-data-thierry-breton-coronavirus-covid19/.
  > KEYQUOTE: The European Commission on Monday urged Europe's telecoms giants including Deutsche Telekom and Orange to share reams of people's mobile data from across the region to help predict the spread of the coronavirus…called on the companies to hand over anonymized and aggregated data from people’s mobile phones to track how the virus was spreading…The draft plans would allow the Commission — and not the carriers — to manage how the data was used, and give EU officials control over so-called metadata on hundreds of millions of people’s mobile phones. That represents a significant step for Brussels as it would make the EU executive liable for any hefty fines if the digital information was hacked or misused.
  > Researchers, academics and telecoms executives say that as the coronavirus crisis has spread so quickly, the usefulness of such anonymized mobile phone metadata is quickly coming to an end. As people enter lockdown, often not able to travel beyond their neighborhoods, such digital information does not offer much insight because it is not granular enough to track people's localized movements.

* Byers, Dylan (2020, March 18). The U.S. wants smartphone location data to fight coronavirus. Privacy advocates are worried [#News #Opinion, NBC News].
  * Retrieved from https://www.nbcnews.com/tech/tech-news/u-s-wants-smartphone-location-data-fight-coronavirus-privacy-advocates-n1162821.
  > ABSTRACT/KEYQUOTE: Federal health officials say they could use anonymous, aggregated user data collected by the tech companies to map the spread of the virus — a practice known as ["syndromic surveillance"](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC353021/) — and prevent further infections. They could also use the data to see whether people were practicing "social distancing."

# Unsorted CTT Links

- [Covid score proposal](https://gist.github.com/18dew/b6d45de8f30dc70e3d8d69e522a37b40)
- [Coronavirus: An EU approach for efficient contact tracing apps to support gradual lifting of confinement measures](https://ec.europa.eu/commission/presscorner/detail/en/IP_20_670)
- [Coronavirus lockdowns could end in months if Australians are willing to have their movements monitored - Politics - ABC News (Australian Broadcasting Corporation)](https://www.abc.net.au/news/2020-04-14/coronavirus-app-government-wants-australians-to-download/12148210)
- [Guarantee Limits and Protections on Covid App or it will Fail - Digital Rights Watch](https://digitalrightswatch.org.au/2020/04/15/guarantee-limits-protections-covid-app-or-will-fail/)
- [Big Tech surveillance and our privacy – Daily News](https://www.dailynews.com/2020/04/08/big-tech-surveillance-and-our-privacy/)
- [The Lasting Privacy and Civil Liberties Impacts of Responses to COVID-19 | The OECD Forum Network](https://www.oecd-forum.org/users/386048-evan-selinger/posts/65529-the-lasting-privacy-and-civil-liberties-impacts-of-responses-to-covid-19)
- [Houseparty Could Be a Digital Privacy Nightmare: Experts | Digital Trends](https://www.digitaltrends.com/news/houseparty-privacy-tracking-security/)
- [Would you give up health or location data to return to work?](https://apnews.com/7f420983dfca013baf0914714c95272a)
- [Commission COVID-19 data sharing aims to be operational ‘as soon as possible’  – EURACTIV.com](https://www.euractiv.com/section/digital/news/commission-covid-19-data-sharing-aims-to-be-operational-as-soon-as-possible/)
- [Location data brokers say they can help contain COVID-19. Here's why that's a problem - CNET](https://www.cnet.com/news/location-data-brokers-say-they-can-help-contain-covid-19-heres-why-thats-a-problem/)
- [This is not the time for #technology optimism or pessimism. It’s the time for technology realism, with the full understanding that technology’s promise is as only good as those who control it](https://washingtonpost.com/opinions/2020/04/16/be-very-wary-trumps-health-surveillance-plans/)
- [Worried about location tracking apps "after" the pandemic? Or the normalisation of public surveillance? What will civil liberties look like later, based on the choices we're making today?](https://www.oecd-forum.org/users/386048-evan-selinger/posts/65529-the-lasting-privacy-and-civil-liberties-impacts-of-responses-to-covid-19)

# Related Materials

## Twitter Lists

**My Twitter list of technologists, advocates, policymakers, lawyers, regulators, etc. w/ a particular focus on privacy.**
* Allen, Christopher (2002-2020) Twitter "Privacy Tech & Advocacy" List [#SocialMedia #Influencers]
  * Retrieved from: https://twitter.com/i/lists/1068260260555579393

## Notable Tweets

- [Rep Andy Biggs on Twitter: "Contact tracing? Immunity cards? This type of centralization of spying on the American people isn’t freedom. It’s enslavement. It’s totalitarianism. https://t.co/fkxkhdf8Wr" / Twitter](https://twitter.com/repandybiggsaz/status/1250575130507522053?s=21)
- [Automated contact tracing is not a coronavirus panacea](https://blog.gds-gov.tech/automated-contact-tracing-is-not-a-coronavirus-panacea-57fb3ce61d98)
- [(1) John Scott-Railton on Twitter: "Lots of contact tracing apps make assertions of unique, private identifiers. This doesn't mean that they are resistant to linkage attacks that leverage beacons to de-anonymize users. Here's a theoretical attack example from @ashk4n... https://t.co/WflNB0C3nv" / Twitter](https://twitter.com/jsrailton/status/1250088001042034689)
- [(1) ashkan soltani on Twitter: "Here's an example linkage attack you could deploy to identify people that report positive for #COVID19 via apps that rely on @Apple / @Google’s "Privacy-Preserving Contact Tracing" API (applies to any contact tracing app that utilize publicly broadcast identifiers) #THREAD:" / Twitter](https://twitter.com/ashk4n/status/1250071326372638736)
- [(1) Sourav Chakrabarty on Twitter: "A 66 Year old male of Sanatrilochanpur Village in Jajpur Block tested positive for COVID-19. We have deduced the travel history and Contact Tracing is going on. Containment Zone is identified and movement is strictly restricted. #OdishaFightsCorona https://t.co/ki8aekGiVL" / Twitter](https://twitter.com/chakraview_/status/1250075086612135936)
- [Izwe Lethu on Twitter: "Health Min Dr Mkhize: Tracers are 13 488. We're heeding Cyril/Cabinet/NCC's call We'd like everyone to cooperate with screening. If they don't we'll use enforcement measures It's our strongest weapon, Contact Tracing, Community Screening, refer people with symptoms for testing https://t.co/aL5GTsWoaW" / Twitter](https://twitter.com/landnoli/status/1250291633733513218?s=21)
- [Andrew Exum on Twitter: "Interesting note from @TexasStandard today: Contact tracing is harder when people don’t answer their phones, and people don’t answer their phones because spammers have conditioned them to not do so when they don’t have the number saved in their contacts." / Twitter](https://twitter.com/exumam/status/1250476647138177027?s=21)
- [Sophie in 't Veld on Twitter: "Tomorrow @Europarl_EN will call for privacy proof use of contact tracing apps: - not obligatory - no central storage, but only decentral on the device - full transparency on the functioning of these apps (open source) - full transparency on commercial interests ⬇️ #DP3T https://t.co/JZbZwyt771" / Twitter](https://twitter.com/sophieintveld/status/1250437299491360768?s=21)
- [Christopher Allen on Twitter: "I do believe that this is a great start for a proscriptive list for the EU to avoid some of the risks to human rights privacy of #ContactTracing. But I believe there should be more. For instance, will compliance by authorities to these standards be auditable? There is much more. https://t.co/HE1ZqVtbmi" / Twitter](https://twitter.com/christophera/status/1250687727139303424?s=21)
- [Russ on Twitter: "Day 86 26 Mar When asked why government has eased up on contact tracing and quarantining, Deputy Chief Medical Officer tells reporters “There comes a point in a pandemic where that is not an appropriate intervention"" / Twitter](https://twitter.com/russincheshire/status/1249984411971596291?s=21)
- [(1) Gavin Newsom on Twitter: "1) Ability to monitor and protect our communities through testing, contact tracing, isolating, and supporting those who are positive or exposed 2) Ability to prevent infection in people who are at high risk 3) Ability of hospitals and health systems to handle surges" / Twitter](https://twitter.com/gavinnewsom/status/1250144572480487424?s=21)
- [(1) The New York Times on Twitter: "Gov. Gavin Newsom of California on Tuesday said the state would be moving from its broad shelter-in-place order to an approach focused on individuals, including contact tracing and isolating patients. He didn’t immediately give a time frame for the shift. https://t.co/VWH9r8fOr5 https://t.co/rT37MAaNiO" / Twitter](https://twitter.com/nytimes/status/1250162049449185282?s=21)
- [(1) Alex Gladstein on Twitter: "Thread on the folly of fighting COVID-19 w/ surveillance: 1/ Is there an independent study showing that digital contact tracing has, all things equal, been a big help? As opposed to masks, hand washing, testing, social distancing, public education, healthcare per capita, etc?" / Twitter](https://twitter.com/gladstein/status/1250296349997690883)
- [(1) steve hilton on Twitter: ""those wishing to engage in air/Amtrak travel must participate in a certified contact tracing app, demonstrate at check-in they have tested negative" no travel unless you get a cellphone + let Big Tech track you stop these Big Government "re-open" plans! https://t.co/91rQSJXKlr" / Twitter](https://twitter.com/stevehiltonx/status/1250167489754886145)
- [(1) Andy Slavitt @ 🏡 on Twitter: "I tried a little exercise in contact tracing today by lightly interviewing someone who was positive for a week before he knew it. He came into contact with dozens of people. I know one of the people he had breakfast with. He went into a conference room w 24 ppl. Post-bkfst. 4/" / Twitter](https://twitter.com/aslavitt/status/1250590141997027331)
- [(1) Adam Harvey on Twitter: "Cyber-physical cross modal biometric leakage: Wi-Fi and Bluetooth MAC addresses can be used to harvest "multiple biometric clusters with ~94% purity" https://t.co/hx3TeFWSCQ In other words: always fully disable (not disconnect) Wi-Fi and Bluetooth when not in use https://t.co/BgXjCkAVdX" / Twitter](https://twitter.com/adamhrv/status/1220630888918196225)
- [(1) Richard Blumenthal on Twitter: "The plan to re-open America hinges on massive testing—along with contact tracing &amp; effective treatment. The Trump Admin has failed on testing since day one. The message remains clear: Make the tests. https://t.co/rP4KWy5bst" / Twitter](https://twitter.com/senblumenthal/status/1250459791543209989)
- [(1) Dr Bruce Baer Arnold on Twitter: "so, the people who gave us RoboDebt, CensusFail, MyHRfail &amp; IdentityhubFail are now wanting voluntary mobile contact tracing from sea to sea. Irrespective of a truckload of privacy concerns, the program is a matter of health security theatre ... won't work but reassures voters" / Twitter](https://twitter.com/brucearnoldlaw/status/1250270053158629376)
- [(1) Governor Phil Murphy on Twitter: "Productive call just now with renowned epidemiologist @DrEricDing, who led the team that developed the first mobile app for contact tracing. Eric’s guidance will help us utilize technology to #FlattenTheCurve and responsibly reopen New Jersey, driven by public health and science." / Twitter](https://twitter.com/govmurphy/status/1250189543569068032)
- [(1) LongSats on Twitter: "I will be fighting #ContactTracing. I'm going to be leaving my phone at home like a landline until #OpenSource #privacy phones become common place. Not opting into the big hand of govt monitoring me. Back to life in the 90's like Seinfeld. https://t.co/l4SIpsQOne" / Twitter](https://twitter.com/longsats/status/1250287962295635970)
- [(1) Freedomfighter on Twitter: "Smart phones are the new ankle monitoring bracelets, except WE didn’t break any laws! This is straight government over reach and against the constitution #MurphyThestalker" / Twitter](https://twitter.com/no_phux/status/1250212934032273408)
- Health data is so sensitive. Privacy breaches can lead to higher insurance premiums and firings. It can lead to targeted deportations. It can provoke hate and abuse against Patient Zeros. (https://twitter.com/i/status/1251127895889571840)

## Other Privacy Technologies

### Pseudoanonymous Ephemeral Locality

**I worked on some #LocationPrivacy approaches after year one of the iPhone. The target advocacy was not about health care, but personal safety while travelling. Here they are for the record:**

* Allen, Christopher (circa 2008) Pseudoanonymous Ephemeral Locality Service API
  * Retrieved from https://github.com/ChristopherA/Ephemeral-Locality-API

* Allen, Christopher (2020, 26 March) Hilbert Curves and utility for zk range proofs for privacy
  * https://twitter.com/ChristopherA/status/1243413128378892293

* Allen, Christopher (2007-2020) Various links on Hilbert Curves
  https://pinboard.in/search/u:ChristopherA?query=hilbert


## Events & Meetings

### ImPACT 2020 (2020, April 16. Recording available)

**Three-hour mini-conference (the first in a series of mini-conferences to foster a public dialogue on private automated contact tracing technology) to provide technologists, privacy experts, and public health officials with a forum to discuss how contact tracing can be used to slow the spread of COVID-19, and how privacy-preserving automated contact tracing can augment manual contact tracing.**

  * Retrieved from https://pact.mit.edu/impact-2020/

### W3C CCG

**W3C Credentials CG (where I am co-chair) regularly discusses identity & privacy, and more recently #LocationPrivacy:**

* Andrieu, Joe; Hamilton Duffy, Kim; Allen; Christopher (2020, March 24). Credentials CG Telecon. [#Review #Meeting, W3C Credentials CG].
  * Retrieved from https://w3c-ccg.github.io/meetings/2020-03-24/. 

* Replies in the CCG worth reading:
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0094.html
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0108.html
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0112.html
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0113.html
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0120.html
  https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0124.html

### Rebooting the Web of Trust

**I have been hosting Rebooting the Web of Trust, a twice-a-year design workshop that brings together experts in the decentralized digital identity and privacy community in a collaborative "design workshop" that has published 50+ collaborative white papers. It is where the W3C Decentralized Identifier specification, which is on its way to becoming an international standard, was originally incubated.**

**Unfortunately our last event in Buenos Aires where we planned to discussion #LocationPrivacy and other related Covid-19 privacy topics was cancelled. We are working now on plans for an event in the Fall in the EU, and expect many privacy tech, policy, and regulatory experts coming specifically to work on the next generation of these technologies.**

* Rebooting The Web of Trust https://www.WebOfTrust.info

## Sponsorship

> Reminder: You can become a monthly patron on my [GitHub Sponsor Page](https://github.com/sponsors/ChristopherA) for as little as $5 a month; and your contributions will be multipled, as GitHub is matching the first $5,000! Alternatively, you can support my efforts by sponsoring [Blockchain Commons](https://www.BlockchainCommons.com) and our vision of the open web via a monthly [GitHub Sponsorship](https://github.com/sponsors/BlockchainCommons) or with Bitcoin via our BTCPay contribution page, [Bitcoin contribution](https://btcpay.blockchaincommons.com).
>
> -- Christopher Allen <ChristopherA@LifeWithAlacrity.com\>, Github: [@ChristopherA](https://github.com/ChristopherA), Twitter: [@ChristopherA](https://twitter.com/ChristopherA)