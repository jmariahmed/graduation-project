# Week 6: Methodology and Positionality

## 1. Introduction

ClaimTrail explores how a multilingual, evidence-linked claim-history interface can improve users' understanding of how online claims evolve across different sources and languages. Following the initial audience research in Week 5, this week focuses on establishing a methodology that will guide the design, development and evaluation of the project.

Because ClaimTrail involves both developing a functional technology and investigating how people interact with it, I have chosen a combination of Research through Design and Design Science Research. This approach allows me to use the development process as a way of exploring the research question while evaluating the effectiveness of the resulting artefact.

## 2. Chosen Methodology

**Research through Design**

Research through Design involves using the process of designing and developing an artefact to generate knowledge. It is appropriate for ClaimTrail because the project investigates how an interactive visual interface can help people understand the development of online information.

Through sketching, prototyping and testing different interface approaches, I can explore how users interact with multilingual claims, evidence and source relationships. The design process will therefore contribute to answering the research question rather than simply producing a finished product.

**Design Science Research**

Design Science Research focuses on creating and evaluating an artefact designed to address a particular problem. Hevner et al. (2004) describe how the construction and evaluation of an artefact can contribute to research.

This is relevant to ClaimTrail because the project involves developing a Chrome extension that combines multilingual retrieval, AI-assisted analysis and interactive visualisation. The methodology will allow me to establish design requirements, build a working prototype and evaluate whether it addresses the identified user needs.

Combining these methodologies provides a balance between creative exploration and structured technical evaluation.

## 3. Research and Development Methods

I plan to follow a sequence of methods throughout the project:

**Stage 1: Literature and technical research**

I will investigate multilingual misinformation, cross-language information retrieval, Retrieval-Augmented Generation (RAG), large language models and human-computer interaction. I will also explore existing fact-checking platforms and browser extensions to understand their approaches and identify relevant design opportunities.

**Stage 2: User research and requirements**

Building on the three initial interviews conducted in Week 5, I will review participant responses and identify recurring needs and difficulties. These findings will inform the functional and interface requirements for ClaimTrail.

**Stage 3: Initial design and prototyping**

I will create sketches, wireframes and interactive prototypes of the Chrome extension. These will explore the browser interface, claim selection process, evidence presentation, multilingual comparison and interactive timeline.

**Stage 4: Technical development**

I will develop the core extension functionality and investigate a RAG-based architecture. Multilingual embeddings will support the retrieval of semantically related claims, while an LLM will analyse retrieved material and generate explanations. I will also investigate how image content and available provenance information could be incorporated.

**Stage 5: Testing and evaluation**

I will test the technical functionality and usability of the prototype. This will involve examining retrieval relevance, source accuracy, claim comparison and how easily participants can understand the information presented.

**Stage 6: Refinement and reflection**

Based on the evaluation findings, I will refine the interface and technical implementation. I will document the development process, reflect on limitations and identify improvements for the final outcome.

## 4. Evaluation Criteria and Metrics

To evaluate whether ClaimTrail achieves its intended purpose, I will use both technical and user-centred measures.

| Evaluation area | How it will be assessed |
|---|---|
| Retrieval relevance | Whether the system retrieves sources that are genuinely relevant to the selected claim |
| Source accuracy | Whether displayed URLs, publication dates and source information match the original material |
| Claim comparison | Whether the system identifies meaningful differences in wording and meaning |
| Multilingual performance | Whether related claims can be retrieved and explained across the selected test languages |
| User comprehension | Whether participants can identify changes in a claim and understand its supporting evidence |
| Usability | Task completion, navigation difficulties and participant feedback |

For retrieval testing, I will use a small collection of claims with known relevant sources and assess the proportion of relevant results among the top five retrieved results. For user testing, I will examine whether participants can identify the earliest available source, recognise differences between claim versions and distinguish documented source relationships from possible semantic connections.

These measures will help evaluate both the technical performance and the usefulness of the interface.

## 5. Iterative Development

I plan to use at least two development and evaluation cycles.

**Iteration 1: Initial prototype**

I will develop a basic Chrome extension interface with text-based claim selection, source retrieval and an initial timeline. I will test the functionality and gather feedback on navigation, readability and how evidence is presented.

**Iteration 2: Improved prototype**

Using the findings from the first iteration, I will improve the interface, refine the claim comparison and introduce broader multilingual functionality. I will then conduct further testing to assess whether users can understand the relationships between sources and changes in claim meaning more effectively.

Where feasible, I will also explore image analysis and provenance information as additional features.

This iterative approach will allow design decisions to be informed by testing rather than relying entirely on initial assumptions.

## 6. Participants and Ethical Considerations

The initial research involved three participants with different ages and approaches to consuming online information. For further evaluation, I aim to recruit an additional two to five adult participants through university networks and personal contacts, prioritising people who regularly consume online information and, where possible, use multiple languages.

Participation will be voluntary. Before testing, participants will receive an explanation of the research and how their responses will be used. Informed consent will be obtained, and participants will be able to withdraw in accordance with the university's ethics requirements. I will minimise the collection of personal information and anonymise participant feedback in the project documentation. Participants will not be asked to disclose private messages or sensitive personal information. 

## 7. Positionality Statement

As the designer and researcher behind ClaimTrail, my perspective influences how I approach the problem of online information and misinformation. I am particularly interested in how people encounter information across different sources and languages, and how technology could make the process of investigating claims more accessible.

However, I recognise that my own experiences and assumptions cannot represent every user's circumstances. I may underestimate the difficulties experienced by people with different language abilities, levels of digital confidence or accessibility requirements. I also need to be aware that my interest in AI technology could lead me to place too much emphasis on technical functionality rather than the actual needs of users.

My relationship with participants may also influence the research, particularly where recruitment takes place through personal networks. Participants may feel more comfortable sharing their experiences, but familiarity could also affect how openly they respond. I will therefore use consistent interview questions, avoid leading participants and interpret their responses critically.

I want ClaimTrail to support users in evaluating information independently rather than encouraging unquestioning trust in automated systems. Recognising my positionality will help me remain aware of whose perspectives are represented in the design and whose experiences may be overlooked.

## 8. Reflection and Next Steps

This week's methodology planning has helped establish a clearer development process for ClaimTrail. Combining Research through Design and Design Science Research allows me to investigate the user experience while building and evaluating a functional technical artefact.

My immediate priorities are to finalise the interface requirements, develop the first interactive prototype and establish a small test dataset for multilingual retrieval. I will then use feedback and evaluation results to guide subsequent development.

The overall aim is to create a prototype that is not only technically functional but also understandable, accessible and useful to the people it is intended to support.

## References

Hevner, A.R., March, S.T., Park, J. and Ram, S. (2004) ‘Design science in information systems research’, *MIS Quarterly*, 28(1), pp. 75–105. Available at: https://doi.org/10.2307/25148625.
