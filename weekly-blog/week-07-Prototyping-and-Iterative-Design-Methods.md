# Week 7: Prototyping and Iterative Design

## Introduction

This week, I began translating the ClaimTrail concept into visual prototypes. My main objective was to explore how a user would interact with the proposed Chrome extension, from selecting an online claim to discovering related sources, exploring its history and comparing different versions.

I focused on understanding the interface structure and user journey before moving towards more detailed visual design. I developed two complementary prototypes with different levels of fidelity.

## Prototype 1: Low-Fidelity Wireframe

<img width="1536" height="1024" alt="ClaimTrail Multilingual Fact-Checking Workflow" src="https://github.com/user-attachments/assets/d4dc7626-c880-4fc4-96ba-390d8647cb32" />

I started with a low-fidelity wireframe, created in Figma, to establish the basic layout and information hierarchy of ClaimTrail. I divided the interface into four main stages:

1. **Select:** The user highlights a statement within an online article and captures it using ClaimTrail.
2. **Sources:** The extension displays related versions of the claim across different languages, alongside source names and dates.
3. **History:** A chronological timeline illustrates how the claim may have developed across different publications.
4. **Compare:** Users can examine different versions side by side to identify changes in wording, meaning and scope.

I deliberately kept this prototype simple, using basic shapes, text, outlines and placeholder elements rather than detailed colours or styling. This allowed me to concentrate on the functionality and organisation of information rather than the finished appearance.

## Prototype 2: Higher-Fidelity Visual Exploration

<img width="1417" height="791" alt="Screenshot_15-11-2026_214947_framer com" src="https://github.com/user-attachments/assets/937b9d26-8bb5-42b0-b145-f7b521fc5844" />

<img width="1418" height="791" alt="Screenshot_15-11-2026_215026_framer com" src="https://github.com/user-attachments/assets/e054ffdc-d2cf-447d-a215-1af0c6d808a9" />

<img width="1415" height="790" alt="Screenshot_15-11-2026_215111_framer com" src="https://github.com/user-attachments/assets/ebfb254b-6333-4786-9a7e-c8f570e9edf7" />

<img width="1419" height="790" alt="Screenshot_15-11-2026_215136_framer com" src="https://github.com/user-attachments/assets/2a4939b7-22e8-4909-99f5-8224f79329a3" />

After establishing the initial structure, I used Framer to explore a more developed visual representation of ClaimTrail. Framer includes an AI agent that can generate interface designs from written instructions. I used this to translate my own design direction into a more detailed visual prototype.

I specified the intended Chrome browser layout, extension side panel, navigation, four main sections and example content within my prompt. I also described the visual style, layout and information I wanted each screen to communicate. The AI agent generated the initial interface based on these design instructions, allowing me to explore how the wireframe could develop into a more realistic browser extension.

The example uses a fictional news publication and demonstration content to illustrate the proposed experience. It is not connected to live sources or functioning AI retrieval.

## What I Wanted to Find Out

My main question for this prototype was:

**How can an interactive claim-history interface help users understand how online claims evolve across different sources and languages?**

I wanted to explore whether presenting information through four connected stages would make the process easier to understand than presenting users with a conventional list of search results.

The prototypes helped me visualise how multilingual source discovery, chronological information and side-by-side comparisons could work together within one browser interface.

## Initial Design Evaluation

To evaluate the initial ClaimTrail prototype, I considered how three of my previously interviewed users, Neyhan, Mina and Shuily, might interact with the proposed interface. I used their different levels of digital experience and information needs to identify potential usability issues and questions that the design should address.

Neyhan (21 – University Student)

From Neyhan's perspective, one important question was how ClaimTrail determines whether two sources are discussing the same claim. The timeline displays related publications, but it may not immediately explain why they have been connected. This highlighted the importance of making the relationship between sources transparent.

Design consideration: Include expandable source information explaining why two claims have been linked, distinguishing documented references from possible semantic similarities.

Mina (29 – Multilingual Reader)

Mina's persona raised questions about how the extension handles different languages. For example, if a claim originally appears in Bengali but is later reported in English, would users be able to compare both versions? Would translations preserve the original meaning?

This highlighted the need to make multilingual information accessible without removing the original wording.

Design consideration: Introduce a preferred-language setting, translated explanations and the ability to view original source text alongside translations.

Shuily (47 – Everyday Internet User)

From Shuily's perspective, the main concern was whether the timeline and comparison features would be easy to understand without specialist knowledge. The interface contains several sections and information categories, which could potentially overwhelm users who simply want to understand where a claim came from.

Design consideration: Use simpler explanations, clearer navigation and short descriptions of what each section does. Avoid relying on technical terminology when explaining source relationships.

Key Evaluation Findings

This persona-based walkthrough highlighted three areas requiring further attention:

Transparency: Users need to understand why sources are connected, rather than simply seeing a list of related articles.

Multilingual accessibility: Original wording, translations and explanations should work together to help users understand differences across languages.

Usability: The interface should communicate complex information without making the experience unnecessarily complicated.

These observations informed the next iteration of the prototype and helped identify which aspects of the interface required further development.

## Secondary Design Evaluation

Following the development of the two prototypes, I considered the interface from the perspective of the intended audience. I focused on whether the four-stage journey was understandable, whether the information was presented clearly and whether users could distinguish between different types of source relationships.

This initial evaluation identified several areas that should be investigated further through feedback sessions with my three proposed user personas, Neyhan, Mina and Shuily.

Three potential usability issues emerged:

1. Understanding the timeline

The history screen presents sources chronologically, but users may not immediately understand why particular sources are connected. A timeline alone may communicate the order of publication without explaining how a claim has changed or travelled between sources.

Proposed improvement: Introduce short explanations or expandable evidence details for individual timeline entries, showing why a source is linked and whether the relationship is directly documented or based on semantic similarity.

2. Interpreting multilingual sources

Although the sources screen demonstrates English, Bengali, Arabic and Spanish content, users may not understand every language displayed. Showing the original wording without an accessible translation could make the feature less useful to multilingual readers.

Proposed improvement: Introduce a preferred-language setting and an option to view translated explanations alongside the original source wording. This would support comprehension while retaining access to the original material.

3. Understanding changes between claims

The comparison screen displays different versions side by side, but the significance of the differences may not be immediately obvious. Users could overlook important changes in scope, qualification or certainty.

Proposed improvement: Highlight specific wording changes and provide concise explanations of how the meaning has shifted, rather than relying on users to identify every difference themselves.

These are provisional design observations rather than confirmed user findings. I plan to investigate them through feedback sessions with Neyhan, Mina and Shuily, asking participants to complete simple tasks using the prototype and explain what they understand from each screen.
Iteration Plan
Based on the initial evaluation, I identified three priorities for the next design iteration:
- Iteration 1 – Improve source transparency: Make the relationships between sources easier to understand by including evidence details and clearer relationship labels.
- Iteration 2 – Improve multilingual accessibility: Add a preferred-language option and make translations more accessible without removing the original source text.
- Iteration 3 – Improve claim comparison: Introduce clearer visual highlighting of changes in wording, scope and meaning.
I will use feedback from the planned user sessions to prioritise these changes rather than assuming that every proposed improvement is necessary. The revised prototype will then be reviewed against the original user journey to assess whether the changes improve clarity and usability.

## Reflection and Next Steps

Developing these prototypes helped me move from an abstract product concept towards a more structured user experience. The low-fidelity wireframe allowed me to establish the main navigation and information hierarchy, while the Framer exploration helped me consider how the same structure could appear within a realistic browser environment.

An important insight from this process is that presenting related information is not sufficient on its own. ClaimTrail must also help users understand why sources are connected, how the wording of a claim has changed and what evidence supports the relationship. This is particularly important for the multilingual aspect of the project, where translation and differences in context could affect how users interpret information.

My next step is to conduct feedback sessions with potential users, using simple tasks to investigate whether the interface communicates its purpose effectively. I will use their responses to inform the next iteration and document which design decisions are retained, changed or removed. This will help ensure that the development of ClaimTrail is guided by user understanding and evidence rather than visual appearance alone.


