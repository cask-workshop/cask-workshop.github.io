---
layout: main
title: Home
order: 1
collection: pages_2019
---

<!-- Credit: This repository is a fork of https://github.com/uskb-workshop/uskb-workshop.github.io (the git history of the fork was mistakenly overwritten). -->

## Overview

Conversational agents are increasingly becoming part of our day-to-day life on the phone, in the car and in the living room, performing tasks on our behalf which often require interfacing with various forms of structured knowledge. The goal of this workshop is to shed light and encourage interdisciplinary research on some of the open problems situated on the interface of dialog systems and structured knowledge (e.g., knowledge bases, tables etc.), which is critical to the development of digital assistants like Google Home, Alexa and Siri. Our hope is to help bridge the gap between academic and industry research in this area. Open questions include, but are not limited to: 
- How to enable more natural conversations about structured objects and their properties? 
- How to model the structured context of a conversation? 
- Can we develop dialog systems that can inter-operate across arbitrary knowledge base schemas? 
- How to reason about, model, and make updates to an evolving world / knowledge base in a conversational setting? 
- How to characterize and respond to ambiguous references to entities? 
- How to address acoustic ambiguity in references to KB items in spoken queries? 
- How to segment user speech into meaningful utterances? 
- How do Conversational Agents interact with a Situated KB (e.g., user devices)? 
- How to use knowledge encoded in Pre-trained LMs in Conversational Agents? 


<!-- **Due to concerns about COVID-19, Workshop on Conversational Agents and Structured Knowledge will be fully virtual.** -->

## Registration

Workshop registration is included in [AKBC 2021 registration](https://www.akbc.ws/2021/), along with access to the main conference.

## Call for Papers

<h3>Call for Abstracts</h3>

<h3>Submission Instructions</h3>

<h3>Reviewing Policy</h3>

<h3>Important Dates</h3>

<p style="color:red;">Abstract submission deadline: Sep 10</p>
<p>Notification of acceptance: Sep 17</p>
<p>Date of workshop: Oct 7 </p>

<p>All deadlines are 11.59 pm UTC -12h (“anywhere on Earth”).</p>

## Invited Speakers


## Tentative Schedule

CASK workshop will be held virtually on October 7th from 8am in Pacific Time (UTC-7).

<div id="schedule">
    <ul>
        <li>
            8:25-8:30 - Opening remarks
        </li>
        <!-- <li>
            8:30-9:00 - Invited talk: <a href="https://users.cs.northwestern.edu/~forbus/">Kenneth Forbus</a> -- <b>Analogy and the Construction of more Human-like Knowledge Bases</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#ken-card" aria-expanded="false" aria-controls="ken-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="ken-card"><div class="card card-body">
            Humans remain the most capable learners and reasoners on the planet today.  This talk argues that lessons from cognitive science can be used to create AI systems that reason and learn more like people do.  I start by summarizing the Companion cognitive architecture, our structure-mapping models of analogical matching, retrieval, and generalization, and the language and visual processing Companions use to construct structured, relational representations from natural inputs.  I then describe the continuum of knowledge hypothesis, that argues one source of abstract knowledge is distillation via analogical generalization from experience, and illustrate via examples from a model of human conceptual change and work on learning by reading and on commonsense reasoning.  Analogical training for question-answering provides another illustration of the data-efficiency of analogical learning.  Finally, I close with some suggestions for the community.</div></div>
        </li>
        <li>
            9:00-9:30 - Invited talk: <a href="http://www.sc.cit-ec.uni-bielefeld.de/team/philipp-cimiano/">Philipp Cimiano</a> -- <b>Knowledge graphs for information extraction</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#philipp-card" aria-expanded="false" aria-controls="philipp-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=30m16s" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="philipp-card"><div class="card card-body">
            In template-based information extraction, a template is described by a predefined set of slots that need to be filled with entities mentioned in a text. Compared to traditional relation extraction that aims at classifying binary relations involving a pair of entities only, template-based slot-filling is of higher complexity as interdependencies between slot-filler values need to be taken into account. To model these dependencies, we tackle the slot-filling task as a joint inference problem and build on factorized distributions as used in conditional random fields. These dependencies are often described by textual features only, but in some cases dependencies are of semantic nature and not directly expressed in text. To exploit this potential, we propose the incorporation of semantic dependencies extracted from knowledge graphs into an information extraction model. Dependencies are extracted from the variable bindings of queries executed over a knowledge graph and capture semantic soft constraints that are weighted as part of model training. We evaluate our approach on five distantly supervised labeled datasets extracted from Wikipedia/DBpedia and compare our approach to a most frequent entity baseline as well as a purely textual model. We show that there is an overall positive impact of integrating factual background knowledge in all datasets, yielding an improvement of up to 10 points in F1-score.</div></div>
        </li>
        <li>
            9:30-10:00 - Invited talk: <a href="https://williamleif.github.io/">Will Hamilton</a> -- <b>Meta Learning and Logical Induction on Knowledge Graphs</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#will-card" aria-expanded="false" aria-controls="will-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=58m40s" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="will-card"><div class="card card-body">
            Traditional knowledge graph completion (KBC) methods focus on the setting where one has access to a single, static knowledge graph. For example, it is generally assumed that one has access to the full set of entities in the knowledge graph during training, and KBC research has predominantly focused on entity-centric, embedding-based methods (e.g., TransE). In this talk, I will discuss more challenging forms of knowledge graph completion, which involve generalizing to unseen entities, inducing logical rules, and meta-learning from multiple disjoint graphs. I will highlight new methodological directions that extend and complement traditional embedding-based techniques to handle these more complicated learning regimes.</div></div>
        </li>
        <li>
            10:00-10:15 - Break 1
        </li>
        <li>
            10:15-10:45 - Invited talk: <a href="https://researcher.watson.ibm.com/researcher/view.php?person=us-yunyaoli">Yunyao Li</a> -- <b>Building Domain-Specific Knowledge with Human in the Loop</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#yunyao-card" aria-expanded="false" aria-controls="yunyao-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=90m39s" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="yunyao-card"><div class="card card-body">
            We describe the development of human-in-the-loop tools to capture the implicit knowledge in the mind of human experts to build domain-specific knowledge bases as the foundation for many AI systems. The ability to build large-scale domain-specific knowledge bases that capture and extend the implicit knowledge of human experts is the foundation for many AI systems. We use an ontology-driven approach for the creation, representation and consumption of such domain-specific knowledge bases. This approach relies on several well-known building blocks: natural language processing, entity resolution, data transformation and fusion. We will present several human-in-the-loop work  that target domain experts (rather than programmers) to extract the domain knowledge from the human expert and map it into the "right" models or algorithms. We will also share successful use cases in several domains, including Compliance, Finance, and Healthcare: by using these tools we can match the level of accuracy achieved by manual effort, but at a significantly lower cost and much higher scale and automation. If time permits, we will demonstrate a knowledge base built for the Finance domain.</div></div>
        </li>
        <li>
            10:45-11:15 - Invited talk: <a href="https://www.fabiopetroni.com/">Fabio Petroni</a> -- <b>How can we compare unstructured, structured and self-structured knowledge representation?</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#fabio-card" aria-expanded="false" aria-controls="fabio-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=121m21s" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="fabio-card"><div class="card card-body">Several approaches have been proposed to represent world knowledge. It can be unstructured in text corpora, organised in structured collections (e.g, KBs, key-value memories), or self-structured in the parameters of a neural model. However, it is still unclear how to compare these different solutions. Most of the existing NLP benchmarks focus on tasks that humans can solve by just examining local information. In this talk I will review some knowledge-intensive tasks, that require to seek knowledge in a large body of documents even for humans in order to be solved. I will present some of the latest models proposed to solve those and which representation they use for knowledge. Moreover, I will present some ideas to investigate models' explainability in this setting.</div></div>
        </li>
        <li>
            11:15-11:45 - Invited talk: <a href="https://craffel.github.io/">Colin Raffel</a> -- <b>Answering Questions by Querying the Implicit Knowledge Base Inside T5</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#colin-card" aria-expanded="false" aria-controls="colin-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=152m43s" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="colin-card"><div class="card card-body">
            It has recently been observed that language models trained on unlabeled, unstructured text corpora form a sort of implicit knowledge base. In this talk, I connect this ability to the important NLP task of question answering by introducing "closed-book question answering" (CBQA): In CBQA, a model is only provided with a natural language query and must "look up knowledge" in its parameters in order to produce the correct answer. To attack this problem, we leverage the recent T5 models that cast every text problem into a unified text-to-text format. We find that model performance scales with model size and show that T5-11B attains surprisingly strong performance on the open-domain variants of WebQuestions and TriviaQA, outperforming models that explicitly retrieve a document and extract the answer from it. We also find that existing evaluation procedures for open-domain question-answering often treat correct answers produced by our model as incorrect, suggesting that they are a poor fit for CBQA. I will conclude by outlining some strengths and weaknesses of our approach.</div></div>
        </li>
        <li>
            11:45-12:00 - Break 2
        </li>
        <li>
            12:00-12:45 - <b>Panel discussion</b><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=188m54s" class="btn btn-outline-info btn-xs">Video</a>
        </li> -->
    </ul>
    <p>Each talk is 25 min + 5 min Q&A.</p>
</div>


## Organizing Committee
- [Aditya Gupta](https://scholar.google.com/citations?hl=en&user=HW7IZ6sAAAAJ&view_op=list_works&sortby=pubdate), Google
- [Emily Pitler](https://research.google/people/EmilyPitler/), Google
- [Mihir Kale](https://www.linkedin.com/in/mkale/), Google
- [Rahul Goel](https://www.linkedin.com/in/rgoel39/), Google
- [Shachi Paul](https://www.linkedin.com/in/shachipaul/), Google
- [Shyam Upadhyay](http://shyamupa.com/), Google
- [Waleed Ammar](https://wammar.github.io/), Google
