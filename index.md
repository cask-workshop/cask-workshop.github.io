---
layout: main
title: Home
order: 1
collection: pages_2019
---

<!-- Credit: This repository is a fork of https://github.com/uskb-workshop/uskb-workshop.github.io (the git history of the fork was mistakenly overwritten). -->

<iframe src="https://free.timeanddate.com/countdown/i804ousz/n234/cf11/cm0/cu4/ct0/cs0/ca0/co0/cr0/ss0/cac000/cpc00f/pcfff/tcfff/fs100/szw320/szh135/iso2021-10-07T08:00:00" allowtransparency="true" frameborder="0" width="290" height="19" align="right"></iframe>

## How to attend (on Zoom)
After registering for the conference (see registratiton info below), you can find the Zoom link on [the workshops page](https://akbc.apps.allenai.org/workshops.html#day1).

## Schedule

CASK workshop will be held virtually on October 7th with the following with the following schedule:

<div id="schedule">
    <ul>
<li><b>08:00-08:10</b> - Opening remarks</li>
<li><b>08:10-08:45</b> - Lightning talks 1, 2, 3</li>
<li><b>08:45-09:30</b> - Invited talk: Using Machine Translation to Localize Task Oriented NLG Output, by <a href="https://www.linkedin.com/in/scottroy2">Scott Roy</a>, Waymo</li>
<li>09:30-10:00 - Break</li>
<li><b>10:00-10:30</b> - Lightning talks 4, 5, 6</li>
<li><b>10:30-11:15</b> - Invited talk 2: Duality Exploitation for Language Understanding and Generation, by <a href="https://www.csie.ntu.edu.tw/~yvchen/">Yun-Nung Vivian Chen</a>, National Taiwan University</li>
<li>11:15-11:30 - Break</li>
<li><b>11:30-12:15</b> - Invited talk 3: Grounding Dialogue System Responses on Unstructured Knowledge, by <a href="https://www.linkedin.com/in/dilek-hakkani-tur-9517543/">Dilek Hakkani-Tür</a>, Amazon</li>
<li><b>12:15-13:00</b> - Open discussion</li>
    </ul>
</div>

**All times are in Pacific Time, UTC-7.**
 
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

Make sure to also check out the closely-related AKBC workshop on personal knowledge graphs <a href="https://pkgs.ws/">here</a>.

<!-- **Due to concerns about COVID-19, Workshop on Conversational Agents and Structured Knowledge will be fully virtual.** -->

<h3>Registration</h3>
<p>
	In order to participate in the workshop, we request that you register at the [AKBC 2021 registration page](https://akbc.ws/2021/registration/). There is no separate fee for workshop registration, the conference registration ($50 for non-students, $30 for students) will include all workshops. </p>

<p>
	<i>Invited speakers:</i> you should receive a free registration code by Sep 14. If you don't, please email the AKBC workshop co-chairs: Eunsol Choi (eunsol@utexas.edu) and Waleed Ammar (wammar@google.com).
</p>

<h3>Call for Extended Abstracts</h3>
We invite the submission of extended abstracts to CASK, describing (i) new unpublished or (ii) relevant recently published research in the field. The workshop will not consist of archival proceedings, and the accepted abstracts will be presented as oral (lightning talks) during the workshop and listed on the website.

To submit an abstract to CASK, please send an email to <strong>cask2021@googlegroups.com</strong> with the subject line “<strong>[CASK ABSTRACT]: here-goes-your-title</strong>”. The email should include the following:
	
<ul>
<li>Extended abstracts in PDF format (2 pages max, not including references), as an attachment. Please make sure to include the complete author list, along with their affiliation(s). </li>
<ul>
<li>We encourage the authors to cite all the relevant and related work(s) in the abstract submission. This won&rsquo;t count towards the 2 page limit.</li>
</ul>
<li>Name and email of the author who would be presenting the work as a lightning talk. We will reach out with the details of the lightning talk post acceptance.</li>
<li>(Optional) Full paper, if the authors have a preprint ready.</li>
</ul>

Submitted abstracts will undergo a lightweight review process to make sure they are relevant to the workshop, but no official reviews will be sent to authors. All accepted abstracts will be made available prior to the workshop. We also would make the lightning talks accessible post workshop proceedings.

If you require further assistance in participating in the workshop, please let us know and we’ll be in touch to discuss how we can best address your needs.



<h3>Important Dates</h3>
<ul>
<li>Abstract submission deadline: Sep 17 (extended)</li>
<li>Notification of acceptance: Sep 18</li>
<li style="color:red;">Workshop: Oct 7 </li>
</ul>
<p>All deadlines are 11.59 pm UTC -12h (“anywhere on Earth”).</p>

## Invited Speakers

(1) **Using Machine Translation to Localize Task Oriented NLG Output, by [Scott Roy](https://www.linkedin.com/in/scottroy2/), Waymo**

<p><b>Abstract:</b> One of the challenges in a task oriented natural language application like the Google Assistant, Siri, or Alexa is to localize the output to many languages. This talk explores applying machine translation to the English output. Using machine translation is very scalable, as it can work with any English output and can handle dynamic text, but otherwise the problem is a poor fit: the required quality bar is close to perfection, the range of sentences is extremely narrow, and the sentences are often very different than the ones in the machine translation training data. This combination of requirements makes the problem very different from other domain adaptation problems in machine translation. We are able to reach the required quality bar by building on existing ideas and adding new ones: fine tuning on in-domain translations, adding sentences from the Web, adding semantic annotations, using automatic error detection, and taking advantage of structured data features in addition to the English text. The talk presents the approach and results, together with a distilled data-to-text model to serve the translation models at scale. </p>

<p><b>Bio:</b> Scott Roy is a senior AI researcher and engineering lead at Waymo, where he works on lidar perception.  In his previous role at Google he worked extensively on deep learning for natural language understanding and generation, looking at problems in machine translation, data-to-text generation, and open domain chatbots.  Prior to that he led the CORE project at Yahoo to optimize and personalize the content on the Yahoo home page.  He has a long career at both startups and big companies developing applied ML systems.</p>

(2) **Duality Exploitation for Language Understanding and Generation, by [Yun-Nung Vivian Chen](https://www.csie.ntu.edu.tw/~yvchen/), National Taiwan University**

<p><b>Abstract:</b> Natural language understanding (NLU) and Natural language generation (NLG) tasks hold a strong dual relationship, where NLU aims at predicting semantic labels based on natural language utterances and NLG does the opposite. This talk describes how we can better exploit the duality to improve the performance for both models and for both training and inference stages, demonstrating the great potential of scalable systems for practical usage.</p>

<p><b>Bio:</b> Yun-Nung (Vivian) Chen is currently an associate professor in the Department of Computer Science & Information Engineering at National Taiwan University. She earned her Ph.D. degree from Carnegie Mellon University, where her research interests focus on spoken dialogue systems, language understanding, natural language processing, and multimodality. She received Google Faculty Research Awards, Amazon AWS Machine Learning Research Awards, MOST Young Scholar Fellowship, and FAOS Young Scholar Innovation Award. Prior to joining National Taiwan University, she worked in the Deep Learning Technology Center at Microsoft Research Redmond. http://vivianchen.idv.tw/ </p>

(3) **Grounding Dialogue System Responses on Unstructured Knowledge, by [Dilek Hakkani-Tür](https://www.linkedin.com/in/dilek-hakkani-tur-9517543/), Amazon**
<p><b>Abstract:</b> Incorporating unstructured knowledge from text resources into conversations is a challenging area for task-oriented and open-domain dialogue systems. Our work in this area investigates core issues for these two types of dialogue systems. For task-oriented conversations, to provide users with the appropriate responses, our approach has been detecting knowledge seeking user turns, retrieving and selecting relevant knowledge and then grounding response generation on the selected knowledge. Most of the previous work in this area has focused on written conversations due to the available datasets. However, existing state-of-the-art models trained on written data do not perform well on spoken conversations. Our recent work presents a new benchmark on spoken task-oriented conversations and shows improvements when leveraging n-best speech recognition hypotheses.

Selecting the knowledge to ground the responses on is also core to open-domain dialogue systems. The existing literature on open-domain knowledge selection is limited and makes certain brittle assumptions on knowledge sources to simplify the overall task, such as the existence of a single relevant knowledge sentence per context. We evaluate the existing state of open-domain conversation knowledge selection and improve on them by proposing a new framework for collecting relevant knowledge and benchmark knowledge selection algorithms. We show that models that use the new approach outperform the models trained on standard datasets using both intrinsic evaluation and extrinsic measures of response quality. </p>

<p><b>Bio:</b> Dilek Hakkani-Tür is a senior principal scientist at Amazon Alexa AI focusing on enabling natural dialogues with machines and a Visiting Distinguished Professor at UC Santa Cruz. Prior to joining Amazon, she was leading the dialogue research group at Google (2016-2018), a principal researcher at Microsoft Research (2010-2016), International Computer Science Institute (ICSI, 2006-2010) and AT&T Labs-Research (2001-2005). She received her BSc degree from Middle East Technical Univ, in 1994, and MSc and PhD degrees from Bilkent Univ., Department of Computer Engineering, in 1996 and 2000, respectively. Her research interests include conversational AI, natural language and speech processing, spoken dialogue systems, and machine learning for language processing. She has over 80 patents that were granted and co-authored more than 300 papers in natural language and speech processing. She received several best paper awards for publications she co-authored on conversational systems, including her earlier work on active learning for dialogue systems, from IEEE Signal Processing Society, ISCA and EURASIP. She served as an associate editor for IEEE Transactions on Audio, Speech and Language Processing (2005-2008), member of the IEEE Speech and Language Technical Committee (2009-2014), area editor for speech and language processing for Elsevier's Digital Signal Processing Journal and IEEE Signal Processing Letters (2011-2013), and served on the ISCA Advisory Council (2015-2019). She is currently the Editor-in-Chief of the IEEE/ACM Transactions on Audio, Speech and Language Processing, an IEEE Distinguished Industry Speaker (2021) and a fellow of the IEEE (2014) and ISCA (2014). </p>

## Lightning Talks

(1) **[Get to Know Me: Creating Inclusive and Culturally-Competent Conversational Agents](https://drive.google.com/file/d/1crxDQggFXcEwskn4lqAQZztPf8eThtGu/view?usp=sharing)**

  _Jana Thompson (speaker), Isabella Su, Ali Hosseini_

(2) **[Neural Path Hunter: Reducing Hallucination in Dialogue Systems via Path Grounding](https://drive.google.com/file/d/1tozEPuBHa_FvVjpgl-W0caPLqhA4yjHS/view?usp=sharing)**

  _Nouha Dziri (speaker), Andrea Madotto, Osmar Zaiane, Avishek Joey Bose_

(3) **[Retrieval-Free Knowledge-Grounded Dialogue Response Generation with Adapters](https://drive.google.com/file/d/1afksum4XJe_5QjH9POWtmk5vFBEBIc4E/view?usp=sharing)**

  _Yan Xu (speaker), Etsuko Ishii, Samuel Cahyawijaya, Zihan Liu, Genta Indra Winata, Andrea Madotto, Dan Su, Pascale Fung_

(4) **[Evaluating Pretrained Transformer Language Models for Entity Linking in Task-Oriented Dialog](https://drive.google.com/file/d/1tQwhrle7t_OIm8j8hJ8qsoqrcGz1SBeu/view?usp=sharing)**

  _Sai Muralidhar Jayanthi (speaker), Varsha Embar, Karthik Raghunathan_

(5) **[Challenges for the Conversational Entity Dialog Model](https://drive.google.com/file/d/1OizFtT9qupGpK_AAxSjX5-c06RbjKwff/view?usp=sharing)**

  _Wolfgang Maier (speaker), Stefan Ultes_

(6) **[FeTaQA: Free-form Table Question Answering](https://arxiv.org/abs/2104.00369)**
  _Linyong Nan, Chiachun Hsieh, Ziming Mao, Xi Victoria Lin, Neha Verma, Rui Zhang (speaker), Wojciech Kryściński, Nick Schoelkopf, Riley Kong, Xiangru Tang, Murori Mutuma, Ben Rosand, Isabel Trindade, Renusree Bandaru, Jacob Cunningham, Caiming Xiong, Dragomir Radev_

## Organizing Committee
[Aditya Gupta](https://scholar.google.com/citations?hl=en&user=HW7IZ6sAAAAJ&view_op=list_works&sortby=pubdate), 
[Emily Pitler](https://research.google/people/EmilyPitler/), 
[Mihir Kale](https://www.linkedin.com/in/mkale/), 
[Rahul Goel](https://www.linkedin.com/in/rgoel39/), 
[Shachi Paul](https://www.linkedin.com/in/shachipaul/),
[Shyam Upadhyay](http://shyamupa.com/),
[Waleed Ammar](https://wammar.github.io/). Google.
