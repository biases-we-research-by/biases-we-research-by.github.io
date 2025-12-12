---
layout: page
title: Home
description: home page
menu: Home
permalink: /
---

# Biases We Research By

Reducing the presence of bias in Natural Language Processing (NLP) technologies remains one of the most pressing challenges for the research community. A vast body of literature has shown that bias affects datasets \citep{sap2019risk}, neural-based models \citep{bolukbasi2016man}, and even research practices \citep{hovy2021five}.

Despite multiple efforts to debias NLP technologies \citep{lin2024towards} and datasets \citep{davani2024disentangling}, the field still suffers from a fragmentation of approaches, resulting in methodological and theoretical vagueness. As \citet{blodgett2020language} note in their survey, research on bias in NLP tends to focus primarily on stereotypical representation, while giving far less attention to historical and structural issues affecting vulnerable groups, such as silencing \citep{spivak2023can} and underrepresentation \citep{onwuachi2008celebrating}. This lack of awareness can lead to unintended forms of discrimination, including: the erasure of vulnerable identities from pretraining datasets \citep{dodge2021documenting}; reduced cultural sensitivity during annotation \citep{abdelkadir2025role}; and demographic biases in content moderation systems \citep{thiago2021fighting}.

Biases We Research By is a tutorial on detecting and mitigating understudied forms of bias in NLP research. Its aim is to address existing gaps by providing a comprehensive overview of approaches and methods for conceptualizing and uncovering bias, integrating theoretical insights from the social sciences, actionable methodologies, and perspectives from data labelers themselves. The tutorial has three main objectives:

Clarify the concept of bias as defined in the social sciences.
We introduce foundational social-psychological theories, including implicit and explicit biases, the stereotype content model, and intersectionality \citep{greenwald1995implicit, fiske2002we}. This section highlights how social categorization processes give rise to cognitive biases and how these subsequently manifest in technological systems.

Present methods to reduce underrepresentation and prevent silencing in NLP resources and systems.
We survey existing practices for detecting and mitigating the underrepresentation of vulnerable communities at different stages in the NLP pipeline—including data selection and filtering, annotation workflows, and model development. The overview draws on methodologies from the Semantic Web, gender studies, applied mathematics, social sciences, and NLP.

Discuss issues stemming from the human labor behind fair and ethical NLP systems.
Although discussions of bias in NLP often focus on datasets, models, and algorithms, far less attention is paid to the human labor that underlies them. Data labelers, content moderators, and annotators form a global workforce whose often-invisible contributions shape every AI system. This section connects academic discussions of bias with worker realities, showing how structural inequalities, pay disparities, and cultural invisibility introduce another layer of bias—one rooted not in data points, but in labor practices.
