# Week 4 Blog Post 1: Ideation, Persona, Scenario & Scope

## Project summary

My proposed project, provisionally titled **ClaimTrail**, is a multilingual Chrome extension designed to help people understand online information by investigating not only what a claim says, but how it may have developed over time. It is aimed particularly at everyday digital users who have practical technical skills but are not specialists, and who may find it harder to evaluate information when it is written in a language they do not fully understand.

Using retrieval-augmented generation (RAG), multilingual semantic retrieval and interactive data visualisation, ClaimTrail will connect related versions of a claim across sources, platforms and languages. Its intended language coverage is English plus more than 30 additional languages. Users will be able to investigate a claim directly from their browser, explore related versions, compare changes in wording and meaning, and read explanations in their preferred language. An interactive claim-history view will show relevant sources, publication dates, supporting evidence and the relationships between different versions. A separate panel will examine available AI-origin signals, such as content credentials and metadata, alongside the factual evidence.

Building on my earlier proposal, *Human Agency in an AI-Mediated Information World*, ClaimTrail aims to make the development of online information more transparent and accessible. Rather than presenting an unexplained verdict, it will allow users to explore the evidence, understand how a claim may have changed, and make more informed judgements for themselves.

My initial research question is: **How does a multilingual, evidence-linked claim-history interface affect non-specialist users’ ability to understand changes in online claims across sources and languages, compared with a conventional fact-checking summary?**

The intended outcome is a functional Chrome extension prototype, designed around a multilingual architecture and evaluated through documented claim histories, retrieval-quality testing and exploratory user testing.

## 1. Brainstorming: exploring possible directions

I began by exploring several ideas relating to AI, accessibility, mental health and human judgement. I wanted to find a real-world problem that could lead to a tangible creative computing outcome, combine meaningful technical development with human-centred design, and provide opportunities for further research.

### Idea 1: Making AI's influence on our choices visible

I explored an interactive system that would show how AI recommendation systems shape the options people encounter. For example, a user could change a recommendation system's objective from popularity to diversity and observe how the suggested options change, including alternatives that receive less visibility.

The central question would be whether making overlooked alternatives visible helps people recognise how algorithmic recommendations influence their choices. This direction connected strongly to my interest in human agency and would offer opportunities for interactive simulation and data visualisation.

### Idea 2: Helping neurodivergent people navigate unfamiliar environments

Another direction was a digital tool to help autistic people prepare for unfamiliar places and manage unexpected changes. Instead of providing only a map, it could offer a visual preview of an environment, explain important decision points, and provide alternative routes or guidance when the actual environment differs from what the user expected.

This idea would combine accessibility, environmental information and interaction design. It would require research with intended users to understand which types of uncertainty cause the greatest difficulty and how digital guidance could support greater independence.

### Idea 3: Supporting communication during mental health appointments

I considered a user-controlled visual timeline that could help people organise experiences, recognise patterns they have noticed and prepare a summary for a GP or therapist. Another possibility was a low-demand physical interface offering user-selected support during moments of overwhelm.

These directions offered opportunities for human-centred design and meaningful technical development. They would require a clearly defined audience and careful consideration of privacy, accessibility and the experiences of people involved in user research.

### Idea 4: Identifying AI-generated content

I initially considered a Chrome extension that would investigate whether online text or images might have been generated using AI. I wanted it to work directly in the browser and support multiple languages, avoiding the inconvenience of visiting a separate website or copying and pasting content.

This led me to consider a wider issue: readers often need more than an indication of whether content might be AI-generated. They also need to understand whether its claims are supported by evidence and how those claims relate to information they have encountered elsewhere.

Weber-Wulff et al. (2023) evaluated AI-text detection systems and identified important reliability limitations. This reinforced the need for a more evidence-led approach in which origin signals contribute to an investigation rather than becoming the sole basis for a judgement.

### Idea 5: Tracing how online information develops

This direction emerged from combining my interest in AI-origin analysis with multilingual evidence retrieval and fact-checking. Rather than investigating only whether a post may have been generated using AI, the system would explore how different versions of a claim relate to one another.

For example, an original report might describe a limited finding, while a later headline presents it more definitively. A translated social media post might then change the wording again or remove an important qualification. ClaimTrail would help users compare these versions, inspect the evidence and explore how the meaning may have developed.

I selected this direction because it creates an opportunity to design a more exploratory form of information verification. Instead of receiving only a verdict or summary, users could investigate the relationships between claims, compare language versions and follow the evidence behind the information they encounter.

## 2. Why I selected ClaimTrail

ClaimTrail connects most directly to my original proposal, *Human Agency in an AI-Mediated Information World*. My earlier work explored how people can evaluate information in an environment increasingly shaped by AI. This project develops that interest into a practical browser-based tool that combines multilingual retrieval, evidence visualisation and user-led investigation.

The research problem is supported by Quelle et al. (2025), who analysed 264,487 fact-checks across 95 languages. Their study used multilingual sentence embeddings and a graph to identify semantically related claims. The researchers found evidence that claims circulate across languages and can change over time. This provides a strong foundation for investigating how claim relationships and changes in meaning can be presented in a way that everyday users can understand.

Muda et al. (2023) also conducted two preregistered experiments involving 570 participants and found that proficient bilingual participants were less accurate at distinguishing true from false news when reading in a foreign language. This provides a reason to investigate whether accessible multilingual explanations and direct access to supporting evidence can help people evaluate unfamiliar claims.

My initial review has identified existing tools that approach parts of this problem. FactCheck Radar, for example, provides browser-based fact-checking and can retrieve evidence from sources in different languages, presenting its findings in English. OpenErrata offers AI-assisted investigations and inline corrections for supported webpages. These examples provide a useful starting point for understanding how evidence retrieval can be incorporated into everyday browsing.

The direction I want to develop is an integrated, multilingual claim-history experience that helps users explore how information changes across versions. Its potential contribution lies in how the information is connected and presented: making changes in meaning, documented source relationships and supporting evidence accessible to people who may otherwise struggle to investigate the claim independently.

I will investigate this contribution further through a more detailed review of existing systems and academic research. This will help me define a focused research gap and establish how the proposed interaction can be evaluated.

## 3. Initial research question

My current research question is:

**How does a multilingual, evidence-linked claim-history interface affect non-specialist users’ ability to understand changes in online claims across sources and languages, compared with a conventional fact-checking summary?**

This question focuses on a specific interaction that can be prototyped and evaluated. I can prepare a set of documented claim histories, build an interface that connects related versions, and investigate whether users can better understand changes in meaning and the evidence supporting each connection.

The project will combine three connected features:

- **Claim investigation:** RAG will retrieve relevant sources and supporting evidence for a selected claim.
- **Information history:** An interactive timeline or graph will connect related versions and allow users to compare their wording, meaning, sources and dates.
- **AI-origin analysis:** Available content credentials, metadata and other relevant origin signals will be presented separately from the factual assessment.

The intended language coverage is English plus more than 30 additional languages. Multilingual retrieval will help identify related claims even when they are not written using identical words, while language selection will allow users to explore explanations in a language they understand comfortably. The implementation plan will use multilingual models and retrieval components to support this breadth, with the evaluation testing a representative selection of languages in depth.

## 4. User persona

### Mina Rahman

**Age:** 29

**Context:** Mina lives in the UK and speaks Bengali as her first language. She learned English later and uses it regularly for work, everyday activities and accessing information online. She reads news in English as well as Bengali posts and messages shared by family and community networks.

**Digital confidence:** Mina is comfortable using Chrome, search engines, messaging platforms and translation tools. She can navigate websites, compare search results and use everyday digital services independently. However, she is not a technical specialist and may find complex explanations, technical terminology or unfamiliar information systems difficult to interpret, particularly when they are presented in English.

**Goal:** To understand where an online claim came from, whether the available evidence supports it and whether its meaning has changed between versions before deciding whether to share it.

**Frustration:** Mina often encounters claims in English that use unfamiliar terminology or present complicated information in a confident, simplified way. When she searches for the same claim in Bengali, the results may use different wording or provide a different interpretation. She finds it difficult to determine whether the versions communicate the same meaning, what evidence supports them and where important qualifications may have been lost.

**Digital behaviour:** Mina uses Chrome to read articles and social media posts. When something seems questionable, she searches for the claim, opens several sources and sometimes uses a translation tool. Although she is digitally capable, the process can become time-consuming because she has to compare sources manually and work through language differences.

**Motivation:** Mina wants the confidence to investigate unfamiliar information independently, without needing specialist knowledge or relying entirely on someone else's conclusion.

**In her own words:**

“I can use my browser and search for information, but sometimes the English is difficult or the translated version says something slightly different. I want to understand where the claim came from and what the evidence actually says, without having to piece everything together myself.”

### Evidence informing the persona

Mina's context and goals are informed by two relevant research studies.

First, Muda et al. (2023) found that proficient bilingual participants were less accurate at distinguishing true from false news when reading in a foreign language. Their findings support investigating how language can affect people's evaluation of information and whether accessible context and evidence can help users understand claims more effectively.

Second, Quelle et al. (2025) analysed fact-checks across 95 languages and found evidence that claims can recur across languages and change over time. Their findings support the need for tools that help readers compare related versions of information rather than treating each post as an isolated item.

Together, these studies inform the persona's language-related challenges and the proposed need for accessible, multilingual investigation. The persona provides a starting point for design decisions, with user feedback helping to refine the experience as the project develops.

## 5. User scenario (approximately 190 words)

Mina sees a social media post making a strong health-related claim. She remembers reading something similar in an English-language article but is unsure whether both versions describe the same finding. She selects the claim and opens ClaimTrail.

<u>The extension allows Mina to select text directly from the webpage she is reading.</u> ClaimTrail searches for relevant information across English and more than 30 additional languages, using multilingual retrieval to identify related versions even when their wording differs. <u>The interface presents related claims in an interactive timeline, with dates and links to their sources.</u>

Mina opens two entries and notices that the earlier article describes a possible association, while a later post presents it as a proven cause. <u>The extension compares the versions and highlights meaningful changes in wording and interpretation.</u> It also <u>shows the evidence connecting each version and distinguishes documented source relationships from possible similarities.</u>

Mina can select an unfamiliar term or switch the explanation to Bengali. <u>The extension explains the findings in her preferred language using clear wording and links to the underlying evidence.</u> <u>A separate origin panel presents available AI-related signals and content provenance information.</u> Mina follows the source links, explores how the claim developed and reaches her own judgement before deciding whether to share it.

## 6. Initial project scope: MoSCoW

MoSCoW will help me organise the development priorities and focus the initial prototype on the features most relevant to the research question.

| Priority | Features |
|---|---|
| **Must have** | A working Chrome extension interface; user-selected claim analysis; retrieval-augmented generation; a multilingual architecture targeting English and 30+ additional languages; a dated, evidence-linked claim-history view; comparison of related versions; explanations of changes in wording and meaning; a distinction between documented relationships and inferred similarities; language selection for explanations; a separate panel for available AI-origin and provenance signals. |
| **Should have** | Side-by-side comparison of claim wording; filtering by date, language or source type; explanations of why versions have been linked; highlighting of conflicting evidence; checks for available Content Credentials and relevant metadata; accessible interface language for non-specialist users. |
| **Could have** | Image provenance analysis; additional visualisation options; an exportable evidence report; user annotations on claim histories; broader source collections and more advanced comparison features. |
| **Won’t have in this iteration** | Continuous monitoring of the entire internet and automatic moderation. The initial prototype will prioritise user-selected claims, evidence-linked histories and useful explanations. |

### Multilingual implementation plan

The intended breadth of ClaimTrail is English plus more than 30 additional languages. The architecture will be designed around multilingual components rather than relying on a separate, language-specific implementation for every language.

First, the extension will identify the selected claim's language and use a multilingual embedding model to represent the claim in a form that supports semantic comparison across languages. Models such as LaBSE provide a relevant technical starting point: Quelle et al. (2025) used LaBSE in their analysis of multilingual fact-checks, noting its support for at least 109 languages and its suitability for identifying semantically similar sentences across languages.

Second, a retrieval layer will search a multilingual collection of fact-checks, source material and relevant reporting. The retrieval process will use semantic similarity alongside source metadata, dates and available links. This will help locate candidate versions even when the wording differs because of translation, paraphrasing or changes in emphasis.

Third, the retrieved passages and source information will be supplied to a language-capable generation component, which will produce a structured explanation in the user's selected language. The original source text and citation will remain accessible, enabling users to compare the explanation with the underlying material.

The implementation will therefore combine language detection, multilingual retrieval, source ranking, claim-history construction and multilingual explanation within the Chrome extension experience. The interface will be designed to preserve the relationship between each explanation and its sources rather than presenting generated text in isolation.

### Evaluation plan for language coverage

Although the intended system supports English and more than 30 additional languages, the evaluation will examine a representative subset in depth. This will allow the project to assess the quality of multilingual retrieval and the clarity of explanations within the available development time, while retaining the broader language-support ambition.

The initial evaluation will include English and Bengali, reflecting the persona, alongside representative languages such as Arabic, Hindi, Spanish and French. This selection introduces different scripts, linguistic structures and information environments. The exact language sample will be finalised according to source availability and the feasibility of obtaining reliable reference material.

I will create a curated set of documented claim histories with known source links and related versions. For retrieval testing, I will assess whether the system returns relevant sources and related claims, using a manually reviewed reference set and measures such as precision at the top retrieved results. I will also review whether claims are linked appropriately and whether the displayed source information supports the proposed relationship.

Explanation clarity will be assessed through exploratory user testing and structured feedback. Participants will be asked to compare claim versions, identify changes in meaning, locate supporting evidence and explain which relationships are documented versus inferred. Their performance and feedback will help reveal whether the visualisation improves understanding compared with a conventional fact-checking summary.

This approach allows ClaimTrail to retain its multilingual ambition while making the research evaluation measurable. The goal is to examine both the technical performance of retrieval and the human experience of interpreting the resulting claim history.

## 7. Intended audience and project boundaries

ClaimTrail is primarily designed for **multilingual everyday internet users who have practical digital skills but may face language barriers or find technical explanations difficult to interpret**. They can use browsers, search engines and online services independently, but they would benefit from clearer access to evidence and a more accessible way to compare information.

The project is particularly relevant to people who encounter information in English alongside their first language, as well as users who regularly move between languages when reading news, researching unfamiliar topics or reviewing content shared by friends and family.

The design is intended for non-specialist readers rather than professional fact-checkers or digital-forensics experts, whose work often requires much more extensive investigative tools. ClaimTrail will provide an accessible starting point for examining online claims, with links to original sources so that users can pursue further research when needed.

This focus makes the project more specific than a general-purpose AI detector. It connects multilingual accessibility, claim-history visualisation and evidence retrieval in an interface designed for people who want to understand information without needing specialist technical knowledge.

## 8. Social responsibility and design considerations

**Accessible multilingual design:** The language of both the interface and its explanations will be important. ClaimTrail should make it easy to switch languages, understand unfamiliar terms and inspect original sources. The interface should prioritise clear explanations and meaningful comparisons rather than overwhelming users with technical detail.

**Evidence and transparency:** Each claim-history connection should include supporting sources and a clear explanation of why the versions are related. This will help users understand the reasoning behind the visualisation and explore evidence for themselves.

**Human agency:** The system should support users' own judgements. Presenting source information, changes in wording and uncertainty will make the investigation more transparent than a single unexplained score or verdict.

**Privacy:** Claim analysis will be initiated by the user. The prototype should explain how selected text and URLs are processed and minimise unnecessary collection or retention of browsing information.

**Sustainability:** Retrieval will be prioritised over unnecessary repeated generation, with caching used where appropriate. This will help manage computational demand while maintaining the responsiveness of the extension.

## 9. Reflection and next steps

This week's brainstorming helped me move from a broad interest in AI-generated content towards a more specific question about how online claims change across sources and languages. ClaimTrail offers a tangible technical outcome while allowing me to investigate a wider question about human agency and accessibility: whether people can understand information more independently when evidence, language differences and claim history are made visible.

My next steps are to:

1. Review academic research on multilingual claim retrieval, misinformation evolution, information visualisation and content provenance.
2. Examine existing browser extensions and research prototypes in more depth, focusing on their presentation of evidence, source relationships, language support and information history.
3. Prepare a manageable dataset of documented claim histories and establish the multilingual retrieval architecture for the intended English-plus-30-or-more-language coverage.
4. Finalise the representative evaluation languages and define a process for checking retrieval relevance, source relationships and explanation clarity.
5. Refine the persona and scenario through tutor feedback and, where possible, exploratory discussions with potential users who use English as an additional language.
6. Develop an evaluation plan comparing ClaimTrail's interactive claim history with a conventional fact-checking summary.

I will take the research question, MoSCoW scope, persona and scenario to my tutorial. I particularly want feedback on the proposed contribution of the claim-history interface, the accessibility of the multilingual experience and the technical plan for developing the prototype during Block 2.

## References

C2PA (n.d.) *C2PA and Content Credentials Explainer*. C2PA Specifications, version 2.2. Available at: https://spec.c2pa.org/specifications/specifications/2.2/explainer/Explainer.html (Accessed: 27 October 2026).

FactCheck Radar (n.d.) *How it works*. Available at: https://www.factcheckradar.com/about (Accessed: 27 October 2026).

Muda, R., Pennycook, G., Hamerski, D. and Białek, M. (2023) ‘People are worse at detecting fake news in their foreign language’, *Journal of Experimental Psychology: Applied*, 29(4), pp. 712–724. Available at: https://doi.org/10.1037/xap0000475.

OpenErrata (n.d.) *AI-powered fact-checking for the web*. Available at: https://openerrata.com/ (Accessed: 27 October 2026).

Quelle, D., Cheng, C.Y., Bovet, A. and Hale, S.A. (2025) ‘Lost in translation: using global fact-checks to measure multilingual misinformation prevalence, spread, and evolution’, *EPJ Data Science*, 14, article 22. Available at: https://doi.org/10.1140/epjds/s13688-025-00520-6.

Weber-Wulff, D., Anohina-Naumeca, A., Bjelobaba, S., Foltýnek, T., Guerrero-Dib, J., Popoola, O., Šigut, P. and Waddington, L. (2023) ‘Testing of detection tools for AI-generated text’, *International Journal for Educational Integrity*, 19, article 26. Available at: https://doi.org/10.1007/s40979-023-00146-z.
