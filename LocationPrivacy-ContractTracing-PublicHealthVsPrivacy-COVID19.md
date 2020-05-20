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
  * [Examples of Government Pushback Against Contact Tracing](#examples-of-government-pushback-against-contact-tracing)
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

- Version 0.3.0 (2020, April 30) Updated content, courtesy Vinay Taylor ([Github:@VinayTaylor](https://github.com/vinaytaylor) [Twitter:@VinayTaylor](https://twitter.co/VinayTaylor))
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

**I share my concerns specifically with respect to COVID-19 response technology, and digital identity here:**

* Amery, Paul (2020, May 7). Coronavirus jumpstarts race for digital ID [#SSI, New Money Review].
  * Retrieved from https://newmoneyreview.com/index.php/2020/05/07/coronavirus-jumpstarts-race-for-digital-id/ 
  >KEY QUOTE: ...well-intentioned national identity system can be abused if the political winds shift

**I am co-chair of this World-Wide-Web Consortium (#W3C) community group, where a number of important credentials and identity specifications were nurtured to the point where they could be formalized into international standards. Most notably, the Verifiable Credentials specification is now a full standard, and the Decentralized Identity specification is well on its way.**

**We meet online weekly via voice and IRC on Tuesdays at 12noon ET, 9am PT, and 5pm CET. At several recent meetings we have had discussion on #COVID19 related privacy topics, and it looks like some standards around #ImmunityCredentials in particular will become official work items. Our meetings are open to the public and are announced on our public mailing list.**

**Both of these standards are key architectures toward privacy design, in particular in the short term for #ImmunityCertificates (see my other High Signal Low Noise list on [#VerifiableClaims #ImmunityCredentials](https://github.com/ChristopherA/Lists-of-High-Signal-Low-Noise-Links/blob/master/ImmunityCredentials-VerifiableClaims-COVID19.md).**

* W3C Credentials Community Group https://w3c-ccg.github.io/

**Excerpt of one particular email from me to W3C-CCG list, about why we must work on this privacy tech despite the challenges on March 29th 2020:** 

* Allen, Christopher (2020, March 29). AGENDA W3C Credentials CG Call. [#Review, W3C].
  * Retrieved from https://lists.w3.org/Archives/Public/public-credentials/2020Mar/0125.html
  > KEYQUOTE: Despite that I agree with those that a key of the problem is that the task of [#LocationPrivacy](https://twitter.com/hashtag/LocationPrivacy) and anonymity is extremely difficult, I do believe that in the short term we can be pragmatic & not suffer “the perfect is the enemy of the good”. We can share best practices, salute those doing the right thing, shame those who do not, and demonstrate our commitment to both the common good as well as to preventing individual harm. An effective Honor System is not the worst short-term outcome.

  > We also need to set the stage so that in the long term we can invest in the much more difficult problems of solving these problems more idealistically correctly. We need to fund things like deep requirements engineering, great user centric design including nudge/incentive/mechanism/ approaches, as well implementing the latest secure code practices, privacy protocols, zk-proofs and other modern cryptographic security approaches, etc.

  > For if we do not be somewhat pragmatic now, and set a stage to be able to invest in a more ideal future, we risk that everything we are currently doing on the privacy front now will fail because in the end, everyone will being tracked at another layer."

**This Harvard white-paper also expands on these concerns about #PublicHealthVsPrivacy on April 3rd 2020:**

* Vi, Hart; et al (2020, April 3). Outpacing the Virus: Digital Response to Containing the Spread of COVID-19 while Mitigating Privacy Risks [#Opinion, #Paper, Edmond J. Safra Center for Ethics - Harvard].
    * Retrieved from https://ethics.harvard.edu/outpacing-virus
    > ABSTRACT: There is a growing consensus that we must use a combined strategy of medical and technological tools to provide us with response at a scale that can outpace the speed and proliferation of the SARS-CoV-2 virus. A process of identifying exposed individuals who have come into contact with diagnosed individuals, called “contact tracing,” has been shown to effectively enable suppression of new cases of SARS-CoV-2 (COVID-19). Important concerns around protecting patient’s confidentiality and civil liberties, and lack of familiarity with available privacy-protecting technologies, have both led to suboptimal privacy implementations and hindered adoption. This paper reviews the trade-offs of these methods, their techniques, the necessary rate of adoption, and critical security and privacy controls and concerns for an information system that can accelerate medical response. Proactive use of intentionally designed technology can support voluntary participation from the public toward the goals of smart testing, effective resource allocation, and relaxing some of physical distancing measures, but only when it guarantees and assures an individual’s complete control over disclosure, and use of data in the way that protects individual rights.

**The NYT Editorial Board makes a key argument that any technology measures implemented today need to end once the threat passes:**

* Editorial Board (2020, May 1). We the People, in Order to Defeat the Coronavirus [#Opinion, New York Times].
  * Retrieved from https://www.nytimes.com/2020/05/01/opinion/coronavirus-civil-liberties.html
  > KEY QUOTE: In a large self-governing society, civil liberties exist as part of a delicate balance. That balance is being sorely tested right now, and there is often no good solution that does not infringe on at least some liberty. At the same time, the coronavirus provides Americans with an opportunity to reimagine the scope and nature of our civil liberties and our social contract. Yes, Americans are entitled to freedom from government intrusion. But they also have an obligation not to unnecessarily expose their fellow citizens to a deadly pathogen. Protecting Americans from the pandemic while also preserving our economy and our civil liberties is not easy. But it’s essential.

**Some interesting risk modeling approaches to COVID-19 response technology, specifically apps:**

* Ernst, Johannes (2020, May 7). Trust through Transparency for Apps [#Opinion #Risk].
    * Retrieved from https://reb00ted.org/tech/20200507-trust-through-transparency-for-apps/
    > KEY QUOTE: What do you need to know so you can confidently trust a piece of technology, such as an app supposedly helping fight COVID-19?
    > That question is at the heart of Project App Assay. It applies to all technology, but is particularly important for the COVID-19 apps, because many of them collect so much information about our health, our friends, our locations and activities around the clock.

# Contact Tracing Primer
## Background: Contact Tracing

**Contact tracing is one the main methods being proposed to curb the spread of the virus. This is a good explainer:**

* Rapaport, Lisa (2020, April 14). Explainer: What is contact tracing and how can it help fight the new coronavirus? [#News #Opinion, Reuters].
  * Retrieved from https://www.reuters.com/article/us-health-coronavirus-tracing-explainer/explainer-what-is-contact-tracing-and-how-can-it-help-fight-the-new-coronavirus-idUSKCN21W2N3.
  > KEYQUOTE: Contact tracing has been used for decades to control the spread of infectious diseases. The basic idea is simple: track down infected people, then find everyone who has been near them and encourage those people to stay home until it is clear they are not sick.

## Introduction to Contact Tracing Technology (CTT)

**Contact Tracing Technology aims to accelerate the manual, laborious process of Contact Tracing. One of the best things I've read recently on the topic is this article that argues that we should call it "Exposure Alerting" and that many of our design problems come from naming it incorrectly:**

* Karlton, Phil (2020, April 22). Digital Contact Tracing and Alerting vs Exposure Alerting [#Opinion, Blog by Harper Reed]
  * Retrieved from https://harper.blog/2020/04/22/digital-contact-tracing-and-alerting-vs-exposure-alerting/.
  > KEY QUOTE: Digital contact tracing should be called Exposure Alerting. That is what it does. It doesn’t “trace contacts” from an epidemiological perspective. Exposure Alerting could tie in with contact tracing, but we should not conflate these separate technologies. Manual Contact Tracing is essential and is very different than Exposure Alerting Exposure Alerting should be decentralized. Manual contact tracing is centralized. Exposure Alerting has very specific privacy concerns that are very different than Manual Contact Tracing.

**When we talk about CTT, there are actually 3 approaches/designs. This is a good summary of each: Bluetooth Contact Tracing, Redacted Location Tracing, and Hashing Servers and Mix Nets:**

* Greenberg, Andy (2020, April 8). Clever Cryptography Could Protect Privacy in Covid-19 Contact-Tracing Apps [#News #Opinion, Wired].
  * Retrieved from https://www.wired.com/story/covid-19-contact-tracing-apps-cryptography/.
  > KEYQUOTE: Users may appreciate privacy, but health care workers and governments don't necessarily want to build a system that prevents them from, say, proactively notifying users who have been potentially exposed to Covid-19, or even actively tracking the location of infected or potentially exposed people.

**This is a simple way to understand bluetooth contact tracing, via a comic!**

* Case, Nicky (2020, April 9). Twitter Thread, 12/12 [#Opinion, Twitter].
  * Retrieved from https://twitter.com/ncasenmare/status/1248271370368114688; https://ncase.me/contact-tracing/. 
  > KEYQUOTE via @mikarv: How exactly can #DP3T privacy-preserving Bluetooth COVID-19 alerts work if identifiable personal data never leaves your device? It's actually not so complicated, and even less so now @ncasenmare has made a fantastic, public domain, comic explaining it.

## General criticisms of CTT

**This explains some of the technical flaws with respect to CTT privacy:**

* Buchanan OBE, Prof Bill (2020, April 14). The Flawed World of Contact Tracing: Where's Carol The Tester? [#Opinion, Medium].
  * Retrieved from https://medium.com/asecuritysite-when-bob-met-alice/the-flawed-world-of-contact-tracing-wheres-carol-the-tester-3939ac92488a.
  > KEYQUOTE: The whole discussion on user and contact tracing opens up a whole lot of questions, and the most fundamental of these is that we don’t actually have any real infrastructure to implement privacy-preserving methods. It is likely that a COVID-19 app would be a pin-point app, and where the data gathered for location and contact tracking could be easily abused, and would have limited scope outside a country’s borders. Our core problem is that we have built data infrastructures that mirror those from the 1980s, and where we care little about the core rights of the data we gather. Once captured, the owner becomes the entity who captured the data, and without the trustworthiness of the transactions involved, we leave it open to abuse for malicious activities.

**A real problem in the current crop of #ContactTracing approaches is not precisely the technology, but instead social incentive design and adversarial resistance to attacks:**
* Anderson, Ross (2020, April 12). Contact Tracing in the Real World [#Opinion #Analysis, Security Research at the University of Cambridge]
    * Retrieved from https://www.lightbluetouchpaper.org/2020/04/12/contact-tracing-in-the-real-world/.
    > ABSTRACT: Here are some problems with private contact tracing. We should not give policymakers the false hope that they can avoid hard choices
    > > KEYQUOTE: The performance art people will tie a phone to a dog and let it run around the park; the Russians will use the app to run service-denial attacks and spread panic; & little Johnny will self-report symptoms to get the whole school sent home.

**More on adversaries here:**
* Soltani, Ashkan et al (2020, April 27). Contact-tracing apps are not a solution to the COVID-19 crisis [#Opinion, Brookings].
  * Retrieved from https://www.brookings.edu/techstream/inaccurate-and-insecure-why-contact-tracing-apps-could-be-a-disaster/
  > KEY QUOTE: And finally, the issue of malicious use is paramount—particularly given this current climate of disinformation, astroturfing, and political manipulation. Imagine an unscrupulous political operative who wanted to dampen voting participation in a given district, or a desperate business owner who wanted to stifle competition. Either could falsely report incidences of coronavirus without much fear of repercussion. Trolls could sow chaos for the malicious pleasure of it. Protesters could trigger panic as a form of civil disobedience. A foreign intelligence operation could shut down an entire city by falsely reporting COVID-19 infections in every neighborhood. There are a great many vulnerabilities underlying this platform that have still yet to be explored.

### Criticism 1: Effectiveness

**A key concern of #ContactTracing apps is the huge adoption required for them to be effective. Other than coercive use in China, Singapore has the largest % acceptance of these apps (16-17% maybe), but many question the efficacy:**

* Ng, Alfred (2020, April 13). Tech isn't solution to COVID-19, says Singapore director of contact tracing app [#News #Opinion, Cnet].
  * Retrieved from https://www.cnet.com/news/director-behind-singapores-contact-tracing-app-says-tech-isnt-the-solution-to-covid-19/
  > KEY QUOTE In the weeks since Singapore released its contact tracing app, the government has seen technology's shortcomings for tracking COVID-19. Despite the government's public campaign to the country to download the app, only about one in six people in Singapore have actually done it, Singapore's national development minister Lawrence Wong said on April 1.
 
  > Bay also noted several issues with an overreliance on mobile contact tracing, pointing out that the apps would not have flagged cases where the coronavirus spread, including an incident in Washington where 45 members of a choir were diagnosed with COVID-19. 

  > "If you ask me whether any Bluetooth contact tracing system deployed or under development, anywhere in the world, is ready to replace manual contact tracing, I will say without qualification that the answer is, no," Bay said in the post.

**Former FDA Commissioner Dr. Scott Gotlieb ([@ScottGottliebMD](https://twitter.com/ScottGottliebMD)) calls for far greater public health surveillance to help stem COVID, but is skeptical of #ContactTracing apps:**
* McLellan, Mark; Gottlieb, Scott; Mostashari, Farzad; Rivers, Caitlin; Silvis, Lauren (2020, April 7) A National COVID-19 Surveillance System: Achieving Containment [#Opinion #Implementation, Duke-Margolis Center for Health Policy]
  * Retrieved from https://healthpolicy.duke.edu/sites/default/files/atoms/files/covid-19_surveillance_roadmap_final.pdf.
  > KEYQUOTE: Cell phone-based apps recording proximity events between individuals are unlikely to have adequate discriminating ability or adoption to achieve public health utility, while introducing serious privacy, security, and logistical concerns. Instead, timely contact tracing can be achieved through strengthened public health case investigation augmented by technology and community-level collaborations.

### Criticism 2: Potential for Exploitation

**Criticism isn't always about the implementation of these technologies, but also the concerns about the parties doing the implementations:**

* Funakoshi, Minami et al (2020, April 28). Tracing COVID-19 [#News, Reuters]
  * Retrieved from https://graphics.reuters.com/HEALTH-CORONAVIRUS/SPY/qzjvqkkxovx/index.html
  > KEY QUOTE: Surveillance companies, better known for providing spyware to governments, argue they are better placed to track and check the spread of the coronavirus. Using the same technology they already use to monitor dissidents and terrorists, governments can track the entire population.

    > But privacy issues loom. Civil liberties advocates fear that anti-virus tracking efforts could open the door to the kind of ubiquitous government surveillance efforts they have fought for decades. Some are especially alarmed by the potential role of spyware firms, arguing that their involvement could undermine the public trust governments need to restrain the spread of the virus. 

**Some governments will misuse new surveillance technology; my concerns about this continue to be justified:**

* Rachman, Gideon (2020, April 20). How strongman leaders will exploit the coronavirus crisis [#Opinion, Financial Times, Paywall].
  * Retrieved from https://www.ft.com/content/4cb87988-82df-11ea-b555-37a289098206.
  > KEYQUOTE: But, as events wear on, strongman leaders might find that the new environment is even more hospitable to their style of politics. Economic despair and desperation are often the enemies of calm debate and a friend to the conspiracy theories that help populism to flourish. An expansion of state-surveillance, once rolled out, could be hard to reverse and will be a potent tool for would-be dictators.

### Criticism 3: Privacy Erosion (Location, Other)

**Digital privacy expert, anonmyity researcher, and author of book "Queer Privacy" [@SarahJamieLewis](https://twitter.com/SarahJamieLewis)’s Twitter thread on the perils of #LocationPrivacy is a must read:**

* Jamie Lewis, Sarah (2020, March 23). Twitter Thread, 12/12 [#Opinion, Twitter].
  * Retrieved from https://twitter.com/sarahjamielewis/status/1242142313192644608?s=2.
  > KEYQUOTE: There is no such thing as a robust privacy preserving contact tracing tool because social graphs and location graphs are impossible to anonymity because anonymity is fundamentally about removing social and location context - once you do that all that is left is the honour system.
  
**My Twitter RT about her thread:**

* Allen, Christopher (2020, March 23). Twitter Thread, 12/12 [#Opinion, Twitter].
  * Retrieved from https://twitter.com/ChristopherA/status/1244346104054865920.
  > KEYQUOTE: Despite that I agree with those like @SarahJamieLewis that a key problem is that the task of #LocationPrivacy & real anonymity is extremely difficult, I do believe that in the short term we can be pragmatic & not suffer “the perfect is the enemy of the good… An effective Honor System is not the worst short-term outcome. We also need to set the stage to invest in the much more difficult problems of solving these problems long-term.

**Important academic paper on how easy it is to be able to de-anonymize supposedly anonymized location data:**
  
* Luc Rocher, Julien M. Hendrickx & Yves-Alexandre de Montjoye (2019, Jul 23). Estimating the success of re-identifications in incomplete datasets using generative models [#Opinion #Review, Nature Communications].
  * Retrieved from https://www.nature.com/articles/s41467-019-10933-3.
  > KEYQUOTE: Moving forward, they question whether current de-identification practices satisfy the anonymization standards of modern data protection laws such as GDPR and CCPA and emphasize the need to move, from a legal and regulatory perspective, beyond the de-identification release-and-forget model.

**Even before the pandemic, concerns were raised on the telecom side of [#LocationPrivacy](https://twitter.com/hashtag/LocationPrivacy). It does have me concerned that work on privacy enhanced bluetooth [#ContactTracing](https://twitter.com/hashtag/ContactTracing) (and other such approaches) is moot given what information a cell phone already allows to be correlated:**

* Thompson, Stuart A.; Warzel, Charlie (2019, December 19). Twelve Million Phones, One Dataset, Zero Privacy [#News #Opinion, New York Times].
  * Retrieved from https://www.nytimes.com/interactive/2019/12/19/opinion/location-tracking-cell-phone.html. 
  > ABSTRACT/KEYQUOTE: The companies that collect all this information on your movements justify their business on the basis of three claims: People consent to be tracked, the data is anonymous and the data is secure. None of those claims hold up, based on the file we’ve obtained and our review of company practices. Yes, the location data contains billions of data points with no identifiable information like names or email addresses. But it’s child’s play to connect real names to the dots that appear on the maps.

# Current Implementations of CTT

**Despite these reservations, governments and private sector players across the world have started developing or deploying a dizzying array of contact tracing apps; with limited/no interoperability:**

* Singer, Natasha et al (2020, April 29). A Scramble for Virus Apps That Do No Harm [#Opinion, New York Times].
  * Retrieved from https://www.nytimes.com/2020/04/29/business/coronavirus-cellphone-apps-contact-tracing.html
  > KEY QUOTE: The proliferation of coronavirus apps has trailed the spread of the pandemic around the globe. Often, the differences among apps are technical ones but can create vast differences in their security, privacy and effectiveness.

**For example, it looks like there are twelve regional pandemic-tracking apps in China and one national one. Interestingly, the patchwork of tracking apps across China seems to show that there is actually very little coordination between localities and the central government.**

* Yang, Yuan; Liu, Nian; Wong, Sue-Lin and Liu, Qianer (2020, April 1). China, coronavirus and surveillance: the messy reality of personal data [#News #Opinion, Financial Times; Paywall].
  * Retrieved from https://www.ft.com/content/760142e6-740e-11ea-95fe-fcd274e920ca
  > KEYQUOTE: Pandemic-tracking apps are now proliferating as local governments have started trying to gain access to phone GPS location data through the apps, which are more accurate than carrier location data. The test version of the national government’s online services platform links to at least 12 provincial- or major city-level governments’ own health code apps, as well as providing a national-level app.
  
  > As is often the case when multiple bureaucracies collide, the health apps have overlapping coverage. On arriving back in Beijing from a trip out of the city, one FT reporter was told by their district authority to ignore the Beijing municipal government’s app and register on another health app used by the district. “One person, six codes”, ran the headline of a local media feature lamenting the multiplication of district- and municipal-level apps.

## Overview of CTT projects

**This is a high-level review of CTT implementations by country:**

* Gershgorn, Dave (2020, April 8). We Mapped How the Coronavirus Is Driving New Surveillance Programs Around the World [#News #Opinion, Medium].
  * Retrieved from https://onezero.medium.com/the-pandemic-is-a-trojan-horse-for-surveillance-programs-around-the-world-887fa6f12ec9
  > KEYQUOTE: In an attempt to stem the tide of the coronavirus pandemic, at least 30 governments around the world have instituted temporary or indefinite efforts to single out infected individuals or maintain quarantines. Many of these efforts, in turn, undermine personal privacy.

**This is a comprehensive summary of CTT implementations in the US and in 40+ countries around the world, from USC:**

* Tanaka, Nina (Last Updated: 2020, April 11). Background Research on mobile applications focused on COVID-19  [#Implementation #Review, USC Viterbi School of Engineering].
  * Retrieved from https://docs.google.com/document/d/1bgsNjPcvoz8fpOutEYiqCJpu2PWYHnGqPI3pcK9mUio/edit.
  > KEYQUOTE: Based on news stories and other online sources, with a focus on February 2020 to present.

**This is another comprehensive crowdsourced list of projects related to COVID-19 contact tracing:**

* Shankari (Ongoing). Covid 19 Tracing Projects [#Implementation, GitHub].
  * Retrieved from https://github.com/shankari/covid-19-tracing-projects. 
  > KEYQUOTE: This site is a crowdsourced list of projects related to COVID-19 contact tracing using smartphones. The goal of contact tracing is to identify the contacts of people who have tested positive for COVID-19 and to advise them to self-quarantine. Large scale, highly accurate contact tracing could control the spread of epidemics and reduce the need for societal lockdowns.

**Europe's data watchdog also pitched a pan-Europe app, but many European countries are all pursuing their own projects or relying on Apple-Google technology (see below).**

## Commentary on specific CTT projects

**This is the best technical overview of the Apple/Google protocol:**

* Fleishman, Glenn (2020, April 10). Apple and Google Partner for Privacy-Preserving COVID-19 Contact Tracing and Notification [#Opinion]
    * Retrieved from https://tidbits.com/2020/04/10/apple-and-google-partner-for-privacy-preserving-covid-19-contact-tracing-and-notification/
    > KEY QUOTE: In the first stage, Apple and Google will make private APIs (application programming interfaces) available in mid-May 2020 strictly limited to health agencies. These APIs will work identically across both iOS and Android and let public-health authorities modify existing apps or build new ones that leverage the tracing features. The companies will also build simple model apps that governments could either put their own logos on or substantially modify. 
    > A second stage will appear “in the coming months,” and will build the tracing approach into Android and iOS at the operating system level. Enabling tracing and receiving a basic notification can happen without even installing an app, company representatives said in the briefing. An app will be required for someone to register a diagnosis of COVID-19.

**Early privacy analysis of Apple and Google's partnership is positive, but it still has potential centralization issues (see [Implementations & Analysis](#implementations--analysis) section below for more details).**

* Hoepman, Jaap-Henk (2020, April 11). Stop the Apple and Google contact tracing platform. (Or be ready to ditch your smartphone.) [#Opinion, XOT.nl].
  * Retrieved from https://blog.xot.nl/2020/04/11/stop-the-apple-and-google-contact-tracing-platform-or-be-ready-to-ditch-your-smartphone/. 
  > KEYQUOTE: However any decentralised scheme can be turned into a centralised scheme by forcing the phone to report to the authorities that it was at some point in time close to the phone of an infected person. In other words, certain governments or companies — using the decentralised framework developed by Apple and Google — can create an app that (without users being able to prevent this) report the fact that they have been close to a person of interest in the last few weeks. The platform itself may be decentralised. But the app developed on top of it breaks this protective shield and collects the contact information centrally regardless. This effectively turns our smartphones into a global mass surveillance tool.
  
**Despite good practices by others, governments (in this case France, and the UK's NHS) will demand more than what is safe, to meet their own political desires or for efficiency of connection to their existing legacy systems. This means often they don’t look at the big picture. France/UK should be moving slower, not faster, especially given questions about efficacy of current approaches.**

*  Daphne, Leprince-Ringuet (2020, April 28). Contact-tracing apps: Why the NHS said no to Apple and Google's plan [#Opinion, ZDNET] 
   * Retrieved from https://www.zdnet.com/article/contact-tracing-apps-why-the-nhs-said-no-to-apple-and-googles-plan/
   > KEY QUOTE: The UK government's homegrown app is also likely to come under public scrutiny as a result of privacy concerns. The new tool follows a centralized model, which means that when a user reports symptoms of the coronavirus, the warning is sent to a central computer server, which then works out who to send an alert to among the contacts that the infected person's phone has registered.

* Fouquet, Helene (2020, April 21). France Says Apple Bluetooth Policy Is Blocking Virus Tracker [#News, Bloomberg].
  * Retrieved from https://www.bloomberg.com/news/articles/2020-04-20/france-says-apple-s-bluetooth-policy-is-blocking-virus-tracker 
  > KEY QUOTE: The Google-Apple system relies on smartphones’ Bluetooth connections and will allow users to keep their data on their handsets. However, France and the European Union want to feed the data to a central server, managed by state health services, which would alert users if they come into contact with a person infected by Covid-19. Any system that sends data to a centralized location is inherently less secure and is vulnerable to “mission creep,” enabling a form of surveillance on users, according to a letter on Monday from 300 academics in more than two dozen countries, which endorsed Google and Apple’s approach.

**Germany has thankfully u-turned and are adopting the Google-Apple model without centralization:**

* Busvine, Douglas (2020, April 26). Germany flips to Apple-Google approach on smartphone contact tracing [#News, Reuters].
  * Retrieved from https://www.reuters.com/article/us-health-coronavirus-europe-tech-idUSKCN22807J
  > KEY QUOTE: Germany as recently as Friday backed a centralised standard called Pan-European Privacy-Preserving Proximity Tracing (PEPP-PT), which would have needed Apple in particular to change the settings on its iPhones. When Apple refused to budge there was no alternative but to change course, said a senior government source. In their joint statement, Braun and Spahn said Germany would now adopt a “strongly decentralised” approach.

**Elsewhere in the world, this solution proposed in New Zealand feels quite implausible to me. I’ve looked at credit card sized Bluetooth before, and the battery tech isn’t quite there for always on devices.**

* Daalder, Marc (2020, April 17). NZ considering $100m contact tracing ‘CovidCard’ [#News, Newsroom NZ].
  * Retrieved from https://www.newsroom.co.nz/2020/04/17/1132682/nz-considering-100m-contact-tracing-covidcard
  > KEY QUOTE: For those who do own a smartphone and do download apps, there will be "too much friction" preventing people from doing so. Users may be afraid of Google having their data, of the Government knowing what they are up to. They may forget their password or turn off the app because it interferes with their Bluetooth headphones. With some back-of-the-napkin math, the presentation estimates just 20 percent uptake in New Zealand - meaning just 4 percent of contacts would be traced. That's where CovidCard comes in. Built using the same underlying technology as Tile Bluetooth trackers, the tool would be the size of a credit card and distributed to every New Zealander.

**Some commentary on Australia, again with centralization but with very specific protections:**

* Whitley, Angus; Withers, Tracy (2020, April 26). Two Million Australians Download Coronavirus Contact-Tracing App [#News, Bloomberg].
  * Retrieved from https://www.bloomberg.com/news/articles/2020-04-27/australia-launches-contact-tracing-app-as-states-ease-lockdown
  > KEY QUOTE: The COVIDSafe app records digital handshakes between smartphones via Bluetooth, and if someone catches the virus, health authorities can track who has been within 1.5 meters of the person for 15 minutes or more.

* Campbell, Kwan (2020, April 21). COVID-19 contact tracing: The tricky balance between privacy and relief efforts [#Opinon, Tech Republic].
  * Retrieved from https://www.techrepublic.com/article/covid-19-contact-tracing-the-tricky-balance-between-privacy-and-relief-efforts/#ftag=RSS56d97e7
  > KEY QUOTE: Australia's upcoming contact tracing app would put data into an encrypted national store that is only accessible by the states and territories' "health detectives. The Commonwealth can't access the data. No government agency at the Commonwealth level, not the tax office, not government services, not Centrelink, not Home Affairs, not Department of Education, not childcare -- the Commonwealth will have no access to that data," Morrison said.

**Two early reviews of Singapore's Trace Together app and the BlueTrace protocol:**

* L, Frank (2020, March 23). Trace Together Under the Hood [#Implementation #Analysis, Medium].
  * Retrieved from https://medium.com/@frankvolkel/tracetogether-under-the-hood-7d5e509aeb5d. 
* Typic, Zero (2020, March 23). Reversing Trace Together.
  * Retrieved from https://medium.com/@zerotypic/reversing-tracetogether-initial-analysis-edc940e86aa8.

**It's not just national or regional governments, but also the private sector that is exploring contact tracing for their own internal purposes:**

* Murph, Hannah; McGee, Patrick (2020, April 26). Private sector races to build virus apps to track employees [#News, Financial Times, Paywall]  
  * Retrieved from https://www.ft.com/content/caeb250b-8d8b-4eaa-969c-62a8b58464aa
  > KEY QUOTE: Companies including PwC, the global consultancy, are racing to build surveillance tools that will monitor the spread of coronavirus inside offices and workplaces...While governments and tech companies are working on voluntary tools that send similar alerts, these may not be widely adopted. By contrast, PwC said companies could make its tool mandatory. 

## Examples of Government Pushback Against Contact Tracing

**I’m pleased that the Netherlands government had their attorney general take a serious look at several contact tracing proposals, given these concerns:**

* Cluskey, Peter (2020, April 23). Netherlands abandons initial plan to develop Covid-19 tracing app [#News, The Irish Times].
  * Retrieved from https://www.irishtimes.com/news/world/europe/netherlands-abandons-initial-plan-to-develop-covid-19-tracing-app-1.4236355
  > KEY QUOTE: The government’s problems became even more acute last weekend when attorney general Reimer Veldhuis was asked to assess the final seven contenders for compliance with privacy laws – and found all seven lacking.

**Also Israel's Supreme Court banned the current invasive methods of contact tracing:**

* Fingas, John (2020, April 26). Israel barred from COVID-19 phone tracking without new legislation [#News, EnGadget]
  * Retrieved from https://www.engadget.com/israel-court-orders-law-for-covid-19-phone-tracking-225848133.html
  > KEY QUOTE: The country’s Supreme Court has ruled that the government can’t keep tracking residents’ phones unless it drafts legislation covering the practice. It has to start work on the new law by April 30th and complete it within a few weeks. Officials raised “great difficulties” by using a “preventative security service” for tracking peaceful people without their permission, the court said, and journalists were within their rights to get injunctions to protect their sources.

## Unsorted list of specific CTT projects

# CTT Recommendations
## Guidelines for Technologists

**Human Rights, Privacy Law, and GDPR expert Elizabeth Renieres (Twitter @hackylawyer) regularly has great insights on the intersection of privacy technology and the law, they stated:**

* Renieris, Elizabeth M. (2020, March 23). When Privacy Meets a Pandemic. [#Opinion, Medium].
  * Retrieved from https://onezero.medium.com/when-privacy-meets-pandemic-fbf9154f80b3.
  > KEYQUOTE: So, where does this leave us as a privacy community and what is our role in the time of Corona? It means that before we debate the particulars of a specific technology or application, before we tweak certain features or functionality to better protect individual privacy, or before we impose certain transparency or accountability measures, we take a step back.

  > Before we concede that a measure is necessary and begin to assess its proportionality, we question that underlying assumption — especially when it’s coming from private companies who stand to gain from it or governments who fear being perceived as lacking control over the situation. We apply the age-old tests of legality, necessity, and proportionality — in that order. We require concrete evidence that a measure will further specific aims or achieve certain measurable outcomes.
  > If privacy advocates don’t step up and do this, who will?

* Renieres, Elizabeth (2020, April 26). Tweet [#Opinion, Twitter].
    * Retrieved from https://twitter.com/hackylawyER/status/1254432590578225152
    > KEY QUOTE: The pandemic is driving home the vast & dangerous divide between technologists who view "privacy" as a technical exercise in approaching anonymity vs. law & policy folks who understand "privacy" as a broad concept necessary to protect the rights & interests of people in practice.

**This states a few compelling pros and cons to consider when balancing privacy and public health**

* Newman, Daniel (2020, April 22). Privacy Pros And Cons As Apple And Google Look Into Using Data To Trace COVID-19 [#News #Opinion, Forbes]
  * Retrieved from https://www.forbes.com/sites/danielnewman/2020/04/22/privacy-pros-and-cons-as-apple-and-google-look-into-using-data-to-trace-covid-19/#35bd94b51fa7
  > KEY QUOTE: ...the ultimate decision to track and unleash information regarding COVID-19 will not be made by us, the people. It will be made by government authorities who may or may not understand the full implications of the precedent they are setting in using surveillance in the name of public health. In this case, the cat is already out of the bag. But that happened long before any global health crisis began. The priority now should be for us as a society to understand what data is being captured, how it is being used and what, if anything will change when the health crisis is over.

**EFF provides a helpful list of safeguards for technologists to consider when building CTT solutions:**

* Crocker, Andrew et al (2020, April 10). The Challenge of Proximity Apps For COVID-19 Contact Tracing [#Recommendations].
  * Retrieved from https://www.eff.org/deeplinks/2020/04/challenge-proximity-apps-covid-19-contact-tracing
  > KEY QUOTE: We urge app developers to provide, and users to require, the following necessary safeguards: Consent, Minimization, Information Security, Transparency, Addressing Bias and Expiration.

* Crocker, Andrew; Hoffman-Andrews, Jacob (2020, April 6). How to Protect Privacy When Aggregating Location Data to Fight COVID-19 [#Recommendations, Electronic Frontier Foundation].
  * Retrieved from https://www.eff.org/deeplinks/2020/04/how-protect-privacy-when-aggregating-location-data-fight-covid-19
  > KEY QUOTE: In general, our advice to organizations that consider sharing aggregate location data: Get consent from the users who supply the data. Be cautious about the details. Aggregate on the highest level of generality that will be useful. Share your plans with the public before you release the data. And avoid sharing “deidentified” or “anonymized” location data that is not aggregated—it doesn’t work.

**A good reply from W3C Credentials CG (where I am co-chair) to the de Montjoye questionnaire below:**

  * Booth, David (2020, April 02) W3C-CCG Mailing List [#Implementation #Analysis, W3C CCG].
    * Retrieved from https://lists.w3.org/Archives/Public/public-credentials/2020Apr/0017.html
    > KEYQUOTE: That document raises excellent questions, but I think the range of protocols (designs) for consideration should be broadened even more. All three of the toy protocols that they discuss involved a central authority -- presumably a public health agency -- that would receive information about infected or exposed individuals.  I think it would be good to also consider (list follows

**Excellent questionnaire for people designing or evaluating #ContactTracing implementations**

* de Montjoye, Yves-Alexandre; Houssiau, Florimond; Gadotti, Andrea and Florent Guepin (2020, April 2). Evaluating COVID-19 contact tracing apps? Here are 8 privacy questions we think you should ask. [#Opinion #Implementation, Computational Privacy Group].
  * Retrieved from https://cpg.doc.ic.ac.uk/blog/evaluating-contact-tracing-apps-here-are-8-privacy-questions-we-think-you-should-ask/
  > KEYQUOTE: In-depth formal analysis of the protocol is necessary before deployment and should be published. Protecting privacy should rely on mathematical proofs of correctness, with mitigation strategies considered only when necessary. Our questions focus on privacy aspects, but ensuring security is similarly crucial. This means, for example, supervising the integrity and authenticity of the crowdsourced data, evaluating how mobile malware could affect the app’s behavior, or assessing the resilience of the authority’s servers against intrusions.
  > Building a contact tracing app that allows all of us to participate in the fight against COVID19 is possible, but it will require us to go beyond shallow reassurances that privacy is protected.

**This highlights the importance of community support for any technological response to COVID-19:**

* Gropper, Adrian (2020, April 30). Reducing Privacy Impacts of Surveillance During COVID-19 [#Recommendations].
  * Retrieved from https://thedeductible.com/2020/04/30/reducing-the-privacy-impacts-of-surveillance-during-covid-19/
  > KEY QUOTE: There are hundreds of groups around the world developing contact tracing, symptom reporting and immunity status apps. They range from state actors to hobbyists to private finance. Many of them introduce new privacy technology based on cryptography, blockchain-based decentralized identifiers, and digital credentials. Apple and Google are planning to update their mobile phone operating systems to launch a decentralized contact tracing platform, an attempt to improve privacy that all the while gives them surveillance power that will impact society long after the pandemic is over. A shift in power from the state to private multinational corporations in the name of privacy seems unwarranted. Can we do better?

**Specific to Decentralised Privacy-Preserving Proximity Tracing (DP-3T), with a helpful focus on risks and mitigations:**

* Bugnion, Prof. Edouard (2020, May 1). DATA PROTECTION IMPACT ASSESSMENT REPORT [#Recommendations].
  * Retrieved from https://github.com/DP-3T/documents/blob/master/data_protection/DP-3T%20Model%20DPIA.pdf
  > KEY QUOTE: The DP-3T system is designed for national (or regional) deployments, but its protocol is scalable internationally. The requirement for a data protection impact assessment (“DPIA”) will therefore have to be analysed on a country-by-country (or regional) basis. DP^3T is currently intended to be deployed in Switzerland. Pursuant to the Swiss Federal Data Protection Act (“FDPA”)33, there is no mandatory obligation to carry out a DPIA. This DPIA is therefore carried out on a voluntary basis, following best practices. In case of deployment in countries that are subject to the GDPR, the need of a DPIA must be assessed in accordance with Articles 35 and 36 GDPR, which require that a DPIA be carried out before the implementation in case the processing is likely to result in a high risk to the rights and freedoms of natural persons. 

## Policy Considerations for Governments

**Governments today are taking legitimate emergency measures to track and manage public health, in particular in the #COVID19 crisis. We need to balance this public good vs. risks of loss of human rights in the future. We can do this!**

**This is one of the best explainers on the legal considerations around contact tracing apps in the US:**

* Chesney, Robert (2020, April 14). COVID-19 Contact Tracing We Can Live With: A Roadmap and Recommendations [#News #Opinion, LawFare].
  * Retrieved from https://www.lawfareblog.com/covid-19-contact-tracing-we-can-live-roadmap-and-recommendations
  > KEY QUOTE Notably, it is not clear that such legislation could be enacted at the federal level, as a constitutional matter. It likely would generate a Sebelius-style challenge, with litigants contending that it amounts to the mandatory use of a product akin to the mandatory purchase of health insurance under the Affordable Care Act. The Supreme Court held in Sebelius that Congress cannot rely on its Interstate Commerce authority to command individuals to engage in a commercial purchase when they would otherwise do no such thing, and even rejected the idea that such an authority can be derived from the Necessary and Proper Clause due to the critical role such purchases played in support of the larger, otherwise-constitutional insurance rules established by the statute. Might the same be true here? True, the requirement to download and use an app for public-health data-collection purposes is not in itself necessarily best viewed as a commercial activity. But then again neither was the must-eat-broccoli hypothetical that Chief Justice John Roberts used to illustrate the dangers of empowering Congress to make us take affirmative actions. Sebelius might best be read as a broad rule against federal legislative authority to compel affirmative activity, not just one barring statutory obligations to buy things.

**Recommendations for US states from CAP:**

* Simpson, Erin; Conner, Adam (2020, April 22). Digital Contact Tracing To Contain the Coronavirus [#Recommendations, Center for American Progress]
  * Retrieved from https://www.americanprogress.org/issues/technology-policy/news/2020/04/22/483521/digital-contact-tracing-contain-coronavirus/
  > KEY QUOTE: Digital contact tracing recommendations for state leaders: In coordination with mass testing, manual contact tracing, significant investments in public health and health care infrastructure, and sufficient social and financial support for all Americans, voluntary and privacy-protected digital contact tracing may play a role in helping state authorities prevent new outbreaks and more safely reopen society. [1] Embrace distributed technology by default. [2] Voluntary systems are more ethical, useful, and likely to be downloaded. [3] Minimize data for secure and trustworthy systems. [4] Build trust by limiting scope creep. [5] Lead and partner with transparency. [6] Design with public health workers and residents to provide clear benefits for both. [7] States should appoint an independent privacy and civil rights advisory board. [8] Governors must be at the helm. [9] Pursue regional collaboration and national standards.

**Again US-centric, the need for a Federal Privacy Law, some senators have started with a proposal:**

* Urerti, David (2020, April 17). Coronavirus Surveillance Highlights Need for Federal Privacy Law [#News #Opinion, Wall Street Journal].
  * Retrieved from https://www.wsj.com/articles/coronavirus-surveillance-highlights-need-for-federal-privacy-law-11587115801
  > KEY QUOTE: New federal protections could also improve public trust in apps and devices that require users to opt in to share data with health authorities, said Graham Dufault, senior director for public policy at ACT | The App Association, a trade group. “The absence of a federal privacy framework has left us less prepared to respond to the crisis with a coordinated, data-driven, and trusted effort,” Mr. Dufault wrote.

* Unknown (2020, April 30). Wicker, Thune, Moran, Blackburn Announce Plans to Introduce Data Privacy Bill [#Legislation].
  * Retrieved from https://www.commerce.senate.gov/2020/4/wicker-thune-moran-blackburn-announce-plans-to-introduce-data-privacy-bill
  > KEY QUOTE: U.S. Sens. Roger Wicker, R-Miss., chairman of the Senate Committee on Commerce, Science, and Transportation, John Thune, R-S.D, chairman of the Subcommittee on Communications, Technology, Innovation, and the Internet, Jerry Moran, R-Kan., chairman of the Subcommittee on Consumer Protection, Product Safety, Insurance and Data Security, and Marsha Blackburn, R-Tenn., today announced plans to introduce the COVID-19 Consumer Data Protection Act. The legislation would provide all Americans with more transparency, choice, and control over the collection and use of their personal health, geolocation, and proximity data. The bill would also hold businesses accountable to consumers if they use personal data to fight the COVID-19 pandemic.

**Canada's Privacy Impact Assessment recommendations are a helpful framework for governments:**

* Unknown (2020, April). A Framework for the Government of Canada to Assess Privacy-Impactful Initiatives in Response to COVID-19 [#Recommendations, Office of The Privacy Commissioner of Canada].
  * Retrieved from https://www.priv.gc.ca/en/privacy-topics/health-genetic-and-other-body-information/health-emergencies/fw_covid/
  > KEY QUOTE: Privacy protection isn’t just a set of technical rules and regulations, but rather represents a continuing imperative to preserve fundamental human rights and democratic values, even in exceptional circumstances...Government institutions should still apply the principles of necessity and proportionality, whether in applying existing measures or in deciding on new actions to address the current crisis.

**And pandemic responses for the Western world may not be suitable for developing nations, here are some useful general guidelines for policymakers with a focus on India as an example:**

* Rajagopalan, Shruti; Tabarrok, Alexander (April 9, 2020). Pandemic Policy in Developing Countries: Recommendations for India [#Opinion, #Policy]
  * Retrieved from https://www.mercatus.org/publications/covid-19-policy-brief-series/pandemic-policy-developing-countries-recommendations-india
   > KEY QUOTE: India needs to find local solutions suited to its unique context to effectively deal with the pandemic. We have collated 10 recommendations for the Indian context, many of which will also apply to other developing countries.

# Recent CTT News
*(Most recent first)*

**In this section, I try to highlight some key articles I found interesting on the topics of #LocationPrivacy #ContactTracing #PublicHealthvsPrivacy #COVID19. There's a lot of material published daily, so on a rolling basis this will update:**

* McCarthy, Kieran (2020, May 5). UK finds itself almost alone with centralized virus contact-tracing app that probably won't work well, asks for your location, may be illegal [#Opinion #News].
    * Retrieved from https://www.theregister.co.uk/2020/05/05/uk_coronavirus_app/
    > KEY QUOTE: A de-centralised smartphone contact tracing system – the type contemplated ... by governments across Europe and also Apple and Google – would be likely to comply with both human rights and data protection laws. In contrast, a centralised smartphone system – which is the current UK Government proposal – is a greater interference with fundamental rights and would require significantly greater justification to be lawful. That justification has not yet been forthcoming.

* Oswald, Marion (2020, May 4). Towards a Trustworthy Coronavirus Contact Tracing App [#Opinion].
    * Retrieved from https://rusi.org/commentary/towards-trustworthy-coronavirus-contact-tracing-app
    > KEY QUOTE: The use of a coronavirus contact tracing app has not yet been demonstrated to be trustworthy, in terms of its purpose, reliability, effectiveness or potential harmfulness. Furthermore, the binary nature of its output must be addressed if trustworthiness is to be achieved.

* Banerjee, Prasid (2020, April 29). Govt's Aarogya Setu app to be installed on smartphones by default soon [#News, LiveMint].
  * Retrieved from https://www.livemint.com/technology/apps/govt-s-aarogya-setu-app-to-be-installed-on-smartphones-by-default-soon-11588170539557.html
  > KEY QUOTE: The Indian government’s covid-19 tracking app may soon be installed on smartphones by default, two sources from the smartphone industry — one a smartphone maker and the other from the Manufacturers Association for Information Technology (MAIT) — confirmed.

* Timberg, Craig (2020, April 29). Most Americans are not willing or able to use an app tracking coronavirus infections. That’s a problem for Big Tech’s plan to slow the pandemic [#News, Washington Post].
  * Retrieved from https://www.washingtonpost.com/technology/2020/04/29/most-americans-are-not-willing-or-able-use-an-app-tracking-coronavirus-infections-thats-problem-big-techs-plan-slow-pandemic/
  > KEY QUOTE: Nearly 3 in 5 Americans say they are either unable or unwilling to use the infection-alert system under development by Google and Apple, suggesting that it will be difficult to persuade enough people to use the app to make it effective against the coronavirus pandemic, a Washington Post-University of Maryland poll finds. 

* Farr, Christina (2020, April 28). How a handful of Apple and Google employees came together to help health officials trace coronavirus [#News, CNBC].
  * Retrieved from https://www.cnbc.com/2020/04/28/apple-iphone-contact-tracing-how-it-came-together.html
  > KEY QUOTE: The project, known by the codename “Bubble” at Apple, was pushed forward by a handful of employees in the space of a month...The two companies couldn’t formally announce plans to work together until they got a green-light from their CEOs. So Apple CEO Tim Cook and Alphabet CEO Sundar Pichai hashed it out on a virtual meeting several days ahead of the official announcement on April 10th.

**The editors of @TheEconomist have clearly not learned the #Foremembrance story of how 75% of Dutch Jews lost their lives in the Holocaust nor connect it to the rise of the right today. This is why Northern Europe has a privacy “religion”. After 75 years is becoming forgotten:**

* Unknown (2020, April 23). Privacy in a pandemic [#Opinion, The Economist].
  * Retrieved from https://www.economist.com/europe/2020/04/23/privacy-in-a-pandemic
  > KEY QUOTE: If the eu had an official religion, it would be privacy. A devout priesthood of eu officials and politicians preach that only their privacy laws can lead to salvation. Holy texts, such as the General Data Protection Regulation or the ePrivacy Directive, are held up as wisdom the whole world would be better off following.

* Giglio, Mike (2020, April 22). Would You Sacrifice Your Privacy to Get Out of Quarantine? [#Opinion, The Atlantic].
  * Retrieved from https://www.theatlantic.com/politics/archive/2020/04/coronavirus-pandemic-privacy-civil-liberties-911/609172/
  > KEY QUOTE: Since 9/11, for example, information acquired via surveillance on national-security grounds has been used to prosecute drug crimes, food-stamp and mortgage fraud, and lying on bank statements. Conversations recorded by an Amazon Echo and heart-rate data tracked by a Fitbit have been used in criminal investigations. “There really is such a thing as surveillance creep, and surveillance programs do tend to increase beyond their initial scope,” Rozenshtein said. “Pandemics, like other emergencies, have often been these catalyst moments for the permanent expansion of the government. And the government does not tend to shrink after the moment has passed.”

* Turner-Lee, Nicole (2020, April 21). Managing health privacy and bias in COVID-19 public surveillance [#Opinion, Brookings]. 
  * Retrieved from https://www.brookings.edu/blog/techtank/2020/04/21/managing-health-privacy-and-bias-in-covid-19-public-surveillance/
  > KEY QUOTE: Any such use of digital tools should continue to raise legal and ethical questions around privacy to avoid unintended consequences for the people being helped. The conversation about the privacy risks should lend itself to a broader conversation on inequality, especially racial and ethnic profiling and the digital divide.

* Mehta, Ivan (2020, April 21). India wants to build an ultra-intrusive ‘wristband’ to track coronavirus patients’ every move [#News #Opinion, The Next Web]
  * Retrieved from https://thenextweb.com/in/2020/04/22/india-wants-to-build-an-ultra-intrusive-wristband-to-track-coronavirus-patients-every-move/.
  > KEY QUOTE A technical document by the Broadcast Engineering Consultant India Limited (BECIL) described the band as an “Intelligence investigation platform & tactical tool to detect, prevent and investigate threats to national security using CDR, IPDR, Tower, Mobile Phone Forensics Data.” The idea is to pair this hardware solution with the Aarogya Setu app, and get information about patients and people under quarantine including their location data and people they’re in contact with.

* Warrell, Helen (2020, April 17). Majority in UK support use of mobile phones for coronavirus contact tracing [#News #Opinion, Financial Times, Paywall].
  * Retrieved from https://www.ft.com/content/1752affb-24dc-4ad9-8503-78f9ce1adca9
  > KEY QUOTE: The survey, commissioned by the Financial Times, suggests that concern over public health is trumping privacy worries as ministers look to technology as a way of managing the outbreak and easing lockdown restrictions. When asked, 65 per cent of people said they agreed with using smartphones to identify people who had been diagnosed with the virus and establish who they had come into close contact with. Support for the idea rose to 73 per cent among 55 to 75-year-olds and fell to 59 per cent in those aged 18 to 34.

* Faleiro, Sonia (2020, April 13). What the world can learn from Kerala about how to fight covid-19 [#News #Opinion, MIT Technology Review].
  * Retrieved from https://www.technologyreview.com/2020/04/13/999313/kerala-fight-covid-19-india-coronavirus/
  > KEY QUOTE While the rest of India, along with countries such as the UK and the US, wouldn’t take stringent steps to limit movement for another two months, Shailaja had ordered Kerala’s four international airports to start screening passengers in January. All those with symptoms were taken to a government facility, where they were tested and isolated; their samples were flown to the National Institute of Virology 700 miles away. By February, she had a 24-member state response team coordinating with the police and public officials across Kerala.

# Unsorted CTT Links

* Schneier, Bruce (2020, May 1). Me on COVID-19 Contact Tracing Apps [#Opinion, Schneier on Security Blog].
  * Retrieved from https://www.schneier.com/blog/archives/2020/05/me_on_covad-19_.html
  > KEY QUOTE: The idea that contact tracing can be done with an app, and not human health professionals, is just plain dumb.

* Landau, Susan et al (2020, May 1). The Importance of Equity in Contact Tracing [#Opinion, Law Fare Blog].
  * Retrieved from https://www.lawfareblog.com/importance-equity-contact-tracing
  > KEY QUOTE: As policymakers coalesce around contact tracing as a means to stabilize the coronavirus outbreak while loosening harsh movement restrictions, the main worry has been about privacy qua privacy. But privacy is not the only, or even primary, concern. We must first think carefully about whether a contact-tracing app can be effective in the United States. And if such a technology is to be developed, it must be built on a foundation of fairness. We cannot ethically accept any solution that will systematically work less well for, or disproportionately harm, some communities—especially the groups that are already the hardest hit by this pandemic.

https://translate.google.com/translate?depth=1&nv=1&pto=aue&rurl=translate.google.com&sl=auto&sp=nmt4&tl=en&u=https://www.cnil.fr/fr/publication-de-lavis-de-la-cnil-sur-le-projet-dapplication-mobile-stopcovid

# Related Materials

## Twitter Lists

**My Twitter list of technologists, advocates, policymakers, lawyers, regulators, etc. w/ a particular focus on privacy.**
* Allen, Christopher (2002-2020) Twitter "Privacy Tech & Advocacy" List [#SocialMedia #Influencers]
  * Retrieved from: https://twitter.com/i/lists/1068260260555579393

## Notable Tweets

- [(1) John Scott-Railton on Twitter: "Lots of contact tracing apps make assertions of unique, private identifiers. This doesn't mean that they are resistant to linkage attacks that leverage beacons to de-anonymize users. Here's a theoretical attack example from @ashk4n... https://t.co/WflNB0C3nv" / Twitter](https://twitter.com/jsrailton/status/1250088001042034689)
- [(1) ashkan soltani on Twitter: "Here's an example linkage attack you could deploy to identify people that report positive for #COVID19 via apps that rely on @Apple / @Google’s "Privacy-Preserving Contact Tracing" API (applies to any contact tracing app that utilize publicly broadcast identifiers) #THREAD:" / Twitter](https://twitter.com/ashk4n/status/1250071326372638736)
- [Andrew Exum on Twitter: "Interesting note from @TexasStandard today: Contact tracing is harder when people don’t answer their phones, and people don’t answer their phones because spammers have conditioned them to not do so when they don’t have the number saved in their contacts." / Twitter](https://twitter.com/exumam/status/1250476647138177027?s=21)
- [Christopher Allen on Twitter: "I do believe that this is a great start for a proscriptive list for the EU to avoid some of the risks to human rights privacy of #ContactTracing. But I believe there should be more. For instance, will compliance by authorities to these standards be auditable? There is much more. https://t.co/HE1ZqVtbmi" / Twitter](https://twitter.com/christophera/status/1250687727139303424?s=21)
- [(1) Alex Gladstein on Twitter: "Thread on the folly of fighting COVID-19 w/ surveillance: 1/ Is there an independent study showing that digital contact tracing has, all things equal, been a big help? As opposed to masks, hand washing, testing, social distancing, public education, healthcare per capita, etc?" / Twitter](https://twitter.com/gladstein/status/1250296349997690883)
- [(1) Adam Harvey on Twitter: "Cyber-physical cross modal biometric leakage: Wi-Fi and Bluetooth MAC addresses can be used to harvest "multiple biometric clusters with ~94% purity" https://t.co/hx3TeFWSCQ In other words: always fully disable (not disconnect) Wi-Fi and Bluetooth when not in use https://t.co/BgXjCkAVdX" / Twitter](https://twitter.com/adamhrv/status/1220630888918196225)
- [(1) Dr Bruce Baer Arnold on Twitter: "so, the people who gave us RoboDebt, CensusFail, MyHRfail &amp; IdentityhubFail are now wanting voluntary mobile contact tracing from sea to sea. Irrespective of a truckload of privacy concerns, the program is a matter of health security theatre ... won't work but reassures voters" / Twitter](https://twitter.com/brucearnoldlaw/status/1250270053158629376)

## Other Privacy Technologies

### Pseudoanonymous Ephemeral Locality

**I worked on some #LocationPrivacy approaches after year one of the iPhone. The target advocacy was not about health care, but personal safety while travelling. Here they are for the record:**

* Allen, Christopher (circa 2008) Pseudoanonymous Ephemeral Locality Service API
  * Retrieved from https://github.com/ChristopherA/Ephemeral-Locality-API

* Allen, Christopher (2020, 26 March) Hilbert Curves and utility for zk range proofs for privacy
  * Retrieved from https://twitter.com/ChristopherA/status/1243413128378892293

* Allen, Christopher (2007-2020) Various links on Hilbert Curves
  * Retrieved from https://pinboard.in/search/u:ChristopherA?query=hilbert

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
>