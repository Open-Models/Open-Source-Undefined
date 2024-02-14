---
bibliography: history.bib
---

# History of « open source »

[DRAFT DOCUMENT, WORK IN PROGRESS]

## 1940s-1960s | The origins of computers and software

::: {layout-ncol=2}

![The ENIAC computer (1945)](/images/eniac.jpg)

![Deck of punched cards for a computer program](/images/punch_card.jpg)

:::

The history of « open source » takes its roots in the early days of computing, a story that can begin around
1945 following the Second World War. In the first decades, computers were huge machines that weighed tons and filled
rooms. The ENIAC, considered as the first computer created in 1945, weight more than 25 tons and was programmed with
physical punch cards, in binary, the machine language composed of 0 and 1. Soon at the end of 40s arrived « stored-program »
computers enabling early software. A landscape with much more primitive tools than nowadays, mainframe computers used
exclusively for calculation by universities, public agencies or some big companies.

**During more than 20 years at the origins of computing, it was the norm to provide software with their source code.** Computers were manipulate
only by specialized people, often mathematicians, who required to adapt custom software to their needs with important portability
issues to run them from one device to another. Initially, compagnies in the computer industry built mainly their business around the selling of
hardware components since early 50', with progressively organisations contracted to support the production of software such as
the Computer Usage Company in March 1955.

The oldest signs of collaborative practices around software between stakeholders date back to the very first commercially available computer, to the first
programming languages. Remington Rand was a machine facturer which developed the computer UNIVAC in 1951, selling tens of units,
with Grace Hopper working for them to develop programming language utilities, the compiler A-2 which was then provided with
the machine in 1953. She received feedback and lists of implemented improvements by UNIVAC's users, from actors like the Army Map
Service or during training workshops on the software, suggestions that are then implemented in new versions of the compiler [@beyer_grace_2012]. Because of the
state of computing at the time, a culture of sharing software and its source code has always existed offering configurations where nascent collaborative
approaches were able to emerge through these interactions between universities, public administrations or corporations,
with hardware providers gathering some core, shared software.

By the time, no one was talking about « open source »; the first writings using the term « software » date from around 1958 [@leonhardt_john_2000].

> *Hopper realized that the process of invention could not be confined to the artificial boundaries of her staff or even
> her company.*
>
> *“It was evident that Remington Rand’s Programming Research Group had progressed considerably further in the
> development and application of automatic programming techniques than had any other single or combined effort in this
> field.”*  
> **Grace Hopper and the Invention of the Information Age, Kurt W. Beyer**

![Grace Hopper with a team at the UNIVAC I console (1960)](/images/grace_hopper.jpg){width=60%}

1969 was a turning point in the history of computing. In the industry, software began to be sold as a separate product from hardware, with the
IBM's unbundling announcement in June being a driving force in this change [@grad_personal_2002]. The 29 October 1969, two computers from the
University of California and the Stanford Research Institute established the first remote connection that
give birth to the ARPANET network, the Internet ancestor, initiating a revolution in the way information is shared and
produced.

## 1970s-1980s | The Divergent Philosophies: Copyright Vs Copyleft

### Copyright: Source Closure by the Software Industry

::: {layout-ncol=2 height=60%}

![Altair 8800, first microcomputer with commercial success](/images/altair_8800.jpg)

![Bill Gates, Micro-soft co-founder in 1975](/images/bill_gates.jpg)

:::


The mid-70s saw a breakthrough in computing with the introduction of « microcomputers », the size of computers reduced to
become personal allowing them to be popularized among (techie) individuals. In 1975, the Altair 8800 was one of the first
microcomputers to achieve popularity, attracting the attention of a certain Bill Gates who saw in the trend a business opportunity with software.
He provided the first BASIC programming language for this Altair 8800, the first software of the initially named Micro-soft company (combination of MICROcomputers and SOFTware). 
Microsoft's software was widely "theft", the source code remained supplied and copied.
It circulated on paper tapes within communities such as the Hombrew Computer Club, which was attended by people like Steve Jobs and Steve Wozniak who founded apple in april 1976.
Realizing that those who owned his software had only marginally bought it, Bill Gates sent to the club the « [Open Letter to the
Hobbyist](https://en.wikipedia.org/wiki/An_Open_Letter_to_Hobbyists#Open_letter) » in February 1976 pointing out the problem of
paying for the work they've done.
Economic interests in software was growing with a specialized industry maturing for both microcomputer and mainframe markets, this
consoliding commercial culture drive the desire to close the code in order to control software distribution and sales.

Before 1976, as a new type of artifact software was in legal vagueness when it came to copyright. Not intially sought after, it began to be.
In the U.S., a 1908 case ruled that encoded piano roll instructions were not protectable under current
copyright laws, but software as a similar format began to be registered in the Copyright Office during 60s [@hollaar_history_2002]. The U.S.
Copyright Act of 1976 clarified the situation by a broad inclusion of "literary works" and therefore software. Whereas
works previously needed to be registered, this act will also provide automatic copyright protection at the moment of their creation.

A software industry that continues to mature, the evolution of copyright will support its desire to protect and control
software and its source code. In this context and with the help of new technical developments, a new practice has
emerged: distribution of software without its source code, through a binary in machine-readable format only. In 1983, IBM announced its "object
code only" policy [@ibm_ibm_1983]. Software becomes legally protected, by default, with a disappearing source code as a commercial and closed culture
takes over.

### Copyleft: Formalization of Source Sharing Philosophy and the Free Software Movement

::: {layout="[[2,1]]"}

![Copyright and Copyleft logos](/images/copyleft_copyright.png)

![Richard Stallman, Initiator of the Free Software Movement](/images/stallman.jpg)

:::

The software world is shaped continuously by the variety of cultures that co-exist within it: with open or closed practices, with
collaborative or competitive mindset, through a business or scientific culture, a public or private culture, by
profesionals or hobbyist and so on. A whole range of relations to software with some antagonistic interests. The arrival of
copyright philosophy, based on an idea of ownership and control over the copy, the « intellectual property », will lead to the emergence of the concept
of « copyleft » in opposition, where this copy is left to be used and shared.

The notion of copyleft emerged in 1976, the year of the U.S. Copyright Act, and the spark that gave birth to it was Bill Gates'
letter to the Homebrew Computer Club. In reaction to the letter, the member of the club Li-Chen Wang wrote it's own interpreter for the BASIC
language, mentioning "COPYLEFT ALL WRONGS RESERVED" in the software notice [@noauthor_li-chen_nodate]. At this stage,
copyleft remains a declaration of intent with no legal value. By the automatic protection of literary works provided by the Copyright
Act, all software becomes subject to copyright and can no longer be theoretically and legally freely used, sharing
becomes outlawed.

> *However, since Mr. Bill Gates claims that he did not get payed [sic] enough and is in the mood of calling people
> thieves. I decided to code one myself. [...] For the time being you are welcome to copy mine and I will not call you a thief (this includes
> Mr. Gates).*  
> **Li-Chen Wang, Homebrew Computer Club newsletter, April 1976** 

Since early 80', Richard Stallman has truly given substance to this philosophy of sharing
source code by initiating the « free software » movement, building on the idea of « copyleft ». He was a programmer at Massachusetts Institute of Technology (MIT)
when he witnessed the cultural shift within the software ecosystem towards closed practices, considering being victim of a non-disclosure
agreement in an attempt to improve the software of a regularly jammed printer from the compagny Xerox [@stallman_free_2001]. Stallman launched
the GNU project in 1983 with the goal to provide all "free" software required for an operating system to be able to « continue to use computers without dishonor »,
without closed components.
In the GNU Manifesto, he states: « *Software sellers want to divide the users and conquer them, making each user agree not to share with others. I refuse to break
solidarity with other users in this way »* [@stallman_gnu_1983]. A project with a philosophical approach in favour of the freedoms of computer users,
where the [Free Software Definition](https://www.gnu.org/philosophy/free-sw.en.html#fs-definition) was formulated with
4 freedoms: the freedom to run, change(/study), redistribute and distribute modified
version of the software. With the evolution of the copyright framework, his battle will also be on legal ground
to guarantee these 4 freedom resulting in one of the first open license: the GNU General Public License.
**With Stallman's approach, copyleft becomes the use of copyright against copyright, formalizing the idea of sharing sources through
« free software ».**

More than sharing sources, the GNU project was already impregnated with a culture of collaboration that could bring certain benefits:

> *In the early '90's, somebody found a way to do a scientific measurement of reliability of software. So they measured
> it, and the most reliable set of programs was the GNU programs. All the commercial alternatives which were proprietary
> software were less reliable.*  
> **Richard Stallman, « Free Software: Freedom and Cooperation » speech**

### The Unix Philosophy and Internet Explosion

{{< video https://www.youtube.com/watch?v=tc4ROCJYbm0
    start="297"
    width="560"
    height="315"
    fig-align="center"
>}}

Interoperability, the ability to use software from one machine to another, was still an issue in the 70s and 80s,
as well as « time-sharing », the ability of the computer to be used by multiple program or users. Launched in early 70',
UNIX operating systems (with C programing language) will have a profound influence on
computing as the first portable, multi-user and multi-tasking system. A « UNIX philosophy » emerged, based on modularity
and the idea of « software tools » working together [@kernighan_software_1976]. In the development of the network of computers
ARPANET, the DARPA agency faced portability issues caused by dying computers.
The agency established a contract in 1980 with the University of California, Berkeley, which was developing its own distribution
of UNIX, the Berkeley Software Distribution (BSD). DARPA asked them to develop software to implement the communication protocol TCP/IP,
a freely available software suite published originally in 1983 that will be shared with the distribution contributing considerably to
the democratisation of the Internet [@mckusick_twenty_1999]. In 1989, a new form of information communication over the network was emerging
with the arrival of the World Wide Web. **Internet was ready to explode based on software with code openly available and,
to a certain extent, collaboration was being integrated into the system itself by the interaction between tools.**

UNIX systems have been crossed by all the cultures that were part of the software world during this period. It leads
to what have been called « [UNIX wars](https://en.wikipedia.org/wiki/Unix_wars) » around the standardisation of tools
with intents to build « [open systems](https://en.wikipedia.org/wiki/Open_system_(computing)) » to get software able to run on the
growing variety of computers. Several organisations were set up during this conflict by the major hardware suppliers of the time,
such as the **Open Software Foundation** in 1988, which gradually led major industrial players to adopt openness practices [@loveluck_open_2005].

| Year | Number of computers (or users)|
|:------:|:----------------:|
| 1969 | 4              |
| 1971 | 19             |
| 1975 | 61             |
| 1985 | 2'000          |
| 1990 | 300'000        |
| 1998 | 147 millions   |
| 2020 | 5 billions     |
:Development of Internet Usage

**Sources:** [Internet History 1962 to 1992](https://www.computerhistory.org/internethistory/) and [History and Growth of the Internet from 1995 till Today](https://www.internetworldstats.com/emarketing.htm)

## 1990s | Open Source: a Theorization of Collaborative Development Methodology

::: {layout="[[1,2]]" height=50%}

![Essay The Cathedral and the Bazaar (1997)](https://m.media-amazon.com/images/I/71z3HAIppDL._AC_UF1000,1000_QL80_.jpg){height=50%}

![Linux computer kernel (1991)](https://i0.wp.com/www.titanui.com/wp-content/uploads/2014/01/06/GNU-Linux-Logo-Penguin-SVG.png?resize=970%2C824)

:::

Although appearing sporadically before then [@tournoij_lets_2023], the term "open source" was strategically adopted in 1998
by a group of actors who will create the [Open Source Initiative](https://opensource.org/). This will be part of a desire to
disseminate these code-sharing and collaboration practices, following the publication of Eric Raymond's
essay "The Cathedral and the Bazaar" in 1997 which proposed a decentralised development methodology around « free software », inspired by the Linux community.
A book that will influence strongly the world of computing and the software industry,
revealing some collaborative potential of a nascent Internet.

at a time when the sharing of source code had been a reality for 40 years, with various forms of collaboration
transformed by the democratisation of the Internet.

- Confusion factor free software
- marketing/reach business

Slowly appearing 

The Cathedral and the Bazaar: A Software Methodology leading to Open Source (collaborative + theorization +
development methodology)

- (1991) Linux arrival, World Wide Web and Internet democratisation (Red Hat & business on freely available software)
- (1997) Publication the Cathedral and the bazaar by Eric Raymond => Brooks's law limit and collaborative methodology
- (1998) Coining of « open source », (january/february) Netscape source code release & Open Source Summit (April): free software confusion factors and marketing
campaign for business
- (October 1998) Microsoft Halloween Documents, Linux is a cancer (2001)


> *Most hackers know that Free Software and Open Source are just two words for the same thing.*  
> **Bruce Perens**

> Brooks's Law predicts that a project with thousands of contributors ought to be a flaky, unstable mess. Somehow the
> Linux community had beaten the N-squared effect and produced an OS of astonishingly high quality. I was determined to
> understand how they did it.
>
> What I saw around me was a community which had evolved the most effective software-development method ever *and didn't
> know it!*.
> Eric Raymond, Revenge of the Hackers

> The ability of the OSS process to collect and harness the collective IQ of thousands of individuals across the
> Internet is simply amazing. More importantly, OSS evangelization scales with the size of the Internet much faster than
> our own evangelization efforts appear to scale.
> Microsoft Halloween documents

### Open Source Ubiquity/Normalization (post-2000)

- Programming languages open source
- Open souce everywhere in modern application
- Github generation
- Microsoft Loves linux
- Google, Facebook, Amazon... Web companies powered by open source
- Lack of training/understanding.
- Critcal bugs (log4shell)
- Reinforcement of business involvement for maintainance (OSPO)
- Contemporary « open source » confusion factors

## Learning goals:

=> Multi public, not software centrics! Meaningful for non IT folks

Primary:

- Provide a background on « open source » origin
- Sharing and collaboration around software over the history, « open source » from computers origin
- Evolution of the wording and the meaning of open source
- Formalization of sharing (free software) + theorization of collaboration methodologies (cathedral and bazaar)
- Evolution of open source acceptance + Current state of open source

Secondary:

- Culture on computers/software/internet history
- Open models development steps: 1/ Sharing, collaboration, cultural maturation
- Growing discovery of collaboration benefit
- Evolution of business/economical acceptance and relation, evolution of software industry

Extra:

- Microsoft historical relation to openness movement

Activable knowledge:
- Distinguish source sharing and collaboration dimensions composing « open source »
- Understanding progressive exploration of digital collaboration
- Overview of the state of « open source » understanding

Section approaches (?):
- Contextualization of the computer history (a way to imagine the situation):
  * computer and software state
  * culture
  * industry relation + importance
- Code sharing practices
- Collaboration practices
- Specification of semantic
- Context of the software culture and the industry relation: acceptance + importance
