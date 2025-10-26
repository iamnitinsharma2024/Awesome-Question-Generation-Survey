# Awesome-Question-Generation-Survey
This repository serves as the supporting resource for our research survey on question generation.


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />

</head>
<body>

<h1 id="top">Question Generation Taxonomy</h1>

<!-- ===== TABLE OF CONTENTS ===== -->
<nav aria-label="Table of contents">
  <strong>Table of Contents</strong>
  <ol>
    <li><a href="#sec-1">1. Answer Format Based Question</a>
      <ol>
        <li><a href="#sec-1-1">1.1 MCQ</a></li>
        <li><a href="#sec-1-2">1.2 Questionnaires/Quiz</a></li>
        <li><a href="#sec-1-3">1.3 Miscellaneous Answer Format</a></li>
      </ol>
    </li>
    <li><a href="#sec-2">2. Context Base Question</a>
      <ol>
        <li><a href="#sec-2-1">2.1 Conversational Question</a></li>
        <li><a href="#sec-2-2">2.2 Context Length Based</a></li>
      </ol>
    </li>
    <li><a href="#sec-3">3. Cognitive Level Based Question</a>
      <ol>
        <li><a href="#sec-3-1">3.1 Distractor Generation</a></li>
        <li><a href="#sec-3-2">3.2 Bloom’s Taxonomy</a></li>
        <li><a href="#sec-3-3">3.3 Multi Hop</a></li>
        <li><a href="#sec-3-4">3.4 Deep Question</a></li>
        <li><a href="#sec-3-5">3.5 Miscellaneous Higher-Order Thinking</a></li>
      </ol>
    </li>
    <li><a href="#sec-4">4. Control and Guidance Mechanism Based Question</a>
      <ol>
        <li><a href="#sec-4-1">4.1 Diverse Question Generation</a></li>
        <li><a href="#sec-4-2">4.2 Difficulty Control</a></li>
        <li><a href="#sec-4-3">4.3 Scalable &amp; Efficient</a></li>
        <li><a href="#sec-4-4">4.4 Miscellaneous Control</a></li>
      </ol>
    </li>
    <li><a href="#sec-5">5. Multilingual &amp; Multimodality Based Question</a>
      <ol>
        <li><a href="#sec-5-1">5.1 Multi-Lingual</a></li>
        <li><a href="#sec-5-2">5.2 Multimodality–Image</a></li>
        <li><a href="#sec-5-3">5.3 Multimodality–Other</a></li>
      </ol>
    </li>
    <li><a href="#sec-6">6. Datasets</a></li>
    <li><a href="#sec-7">7. Evaluation Metrics</a>
      <ol>
        <li><a href="#sec-7-1">7.1 Automatic Metrics</a></li>
        <li><a href="#sec-7-2">7.2 Human Metrics</a></li>
      </ol>
    </li>
    <li><a href="#sec-8">8. FAQ</a></li>
  </ol>
</nav>

<hr class="sep" />

<!-- ===== CONTENT SECTIONS (headings only; add your content under each) ===== -->

<h1 id="sec-1">1. Answer Format Based Question</h1>
  <h2 id="sec-1-1">1.1 MCQ</h2>
  
  <table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2022/09</td>
      <td>Automatic computer science domain multiple-choice questions generation based on informative sentences</td>
      <td>Maheen et&nbsp;al., 2022</td>
      <td>PeerJ Comput. Sci.</td>
      <td><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9454961/pdf/peerj-cs-08-1104.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2022/12</td>
      <td>End-to-End generation of Multiple-Choice questions using Text-to-Text transfer Transformer models</td>
      <td>Rodríguez-Torrealba et&nbsp;al., 2022</td>
      <td>ESWA</td>
      <td><a href="https://www.sciencedirect.com/science/article/pii/S0957417422014014/pdfft">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2023/07</td>
      <td>English grammar multiple-choice question generation using Text-to-Text Transfer Transformer</td>
      <td>Chomphooyod et&nbsp;al., 2023</td>
      <td>Comput. Educ.: AI</td>
      <td><a href="https://www.sciencedirect.com/science/article/pii/S2666920X2300158X/pdfft">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2023/08</td>
      <td>ChatGPT versus human in generating medical graduate exam multiple choice questions—A multinational prospective study</td>
      <td>Cheung et&nbsp;al., 2023</td>
      <td>PLOS ONE</td>
      <td><a href="https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0290691&type=printable">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/07</td>
      <td>Math Multiple Choice Question Generation via Human–Large Language Model Collaboration</td>
      <td>Lee et&nbsp;al., 2024</td>
      <td>EDM 2024</td>
      <td><a href="https://people.umass.edu/~andrewlan/papers/24edm-collab.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2024/10</td>
      <td>ChatGPT prompts for generating multiple-choice questions in medical education and evidence on their validity: a literature review</td>
      <td>Kıyak et&nbsp;al., 2024</td>
      <td>Postgrad Med J</td>
      <td><a href="https://academic.oup.com/pmj/article/100/1189/858/7688383">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2024/11</td>
      <td>DiVERT: Distractor Generation with Variational Errors Represented as Text for Math Multiple-choice Questions</td>
      <td>Fernandez et&nbsp;al., 2024</td>
      <td>EMNLP 2024</td>
      <td><a href="https://people.umass.edu/~andrewlan/papers/24emnlp-divert.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>8</td>
      <td>2025/01</td>
      <td>Automatic Multiple-Choice Question Generation and Evaluation Systems Based on LLM: A Study Case With University Resolutions</td>
      <td>Mucciaccia et&nbsp;al., 2025</td>
      <td>COLING 2025</td>
      <td><a href="https://aclanthology.org/2025.coling-main.154.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>9</td>
      <td>2025/04</td>
      <td>MCQG-SRefine: Multiple Choice Question Generation and Evaluation with Iterative Self-Critique, Correction, and Comparison Feedback</td>
      <td>Yao et&nbsp;al., 2025</td>
      <td>NAACL 2025</td>
      <td><a href="https://aclanthology.org/2025.naacl-long.538.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>10</td>
      <td>2025/06</td>
      <td>Enhancing Clinical Multiple-Choice Questions Benchmarks with Knowledge Graph Guided Distractor Generation</td>
      <td>Yang et&nbsp;al., 2025</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2506.00612">PDF</a></td>
    </tr>
    <tr>
      <td>11</td>
      <td>2025/06</td>
      <td>Multiple-Choice Question Generation Using Large Language Models: Methodology and Educator Insights</td>
      <td>Biancini et&nbsp;al., 2025</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2506.04851">PDF</a></td>
    </tr>
  </tbody>
</table>

  
  
  
  <h2 id="sec-1-2">1.2 Questionnaires/Quiz</h2>
<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2022/07</td>
      <td>Reading Comprehension Quiz Generation using Generative Pre-trained Transformers</td>
      <td>Dijkstra et&nbsp;al., 2022</td>
      <td>AIED-ITB’22 (WS)</td>
      <td><a href="https://e.humanities.uva.nl/publications/2022/dijk_read22.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2024/02</td>
      <td>EvalQuiz — LLM-based Automated Generation of Self-Assessment Quizzes in Software Engineering Education</td>
      <td>Meißner et&nbsp;al., 2024</td>
      <td>SEUH&nbsp;2024</td>
      <td><a href="https://dl.gi.de/bitstreams/6d43a6cc-37c5-4cb5-80d7-b9c2a642a7c0/download">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/07</td>
      <td>Scaling Up Mastery Learning with Generative AI: Exploring How Generative AI Can Assist in the Generation and Evaluation of Mastery Quiz Questions.</td>
      <td>Hutt &amp;&nbsp;Hieb, 2024</td>
      <td>ACM&nbsp;L@S&nbsp;’24</td>
      <td><a href="https://dl.acm.org/doi/pdf/10.1145/3657604.3664699">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/10</td>
      <td>Automated Generation of Ethical Profile-Building Questionnaires.</td>
      <td>Memon et&nbsp;al., 2024</td>
      <td>ASE&nbsp;Workshops&nbsp;’24</td>
      <td><a href="https://dl.acm.org/doi/pdf/10.1145/3691621.3694961">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/11</td>
      <td>QuerIA: Contextual Learning-Driven Questionnaire Generation and Assessment based on Large Language Models</td>
      <td>Eyzaguirre &amp;&nbsp;Badenes-Olmedo, 2024</td>
      <td>EKAW-PDWT&nbsp;’24 (CEUR)</td>
      <td><a href="https://ceur-ws.org/Vol-3967/PD_paper_162.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2025/05</td>
      <td>Methodological Foundations for AI-Driven Survey Question Generation.</td>
      <td>Mburu et&nbsp;al., 2025</td>
      <td>JEE&nbsp;(Early&nbsp;View)</td>
      <td><a href="https://arxiv.org/pdf/2505.01150">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2025/07</td>
      <td>Exploring LLMs for Automated Generation and Adaptation of Questionnaires</td>
      <td>Adhikari et&nbsp;al., 2025</td>
      <td>ACM&nbsp;CUI&nbsp;’25</td>
      <td><a href="https://dl.acm.org/doi/pdf/10.1145/3719160.3736606">PDF</a></td>
    </tr>
  </tbody>
</table>






  
  <h2 id="sec-1-3">1.3 Miscellaneous Answer Format</h2>
<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2022/05</td>
      <td>Mask and Cloze: Automatic Open Cloze Question Generation Using a Masked Language Model</td>
      <td>Matsumori et&nbsp;al., 2022</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2205.07202">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2024/05</td>
      <td>Opinerium: Subjective Question Generation Using Large Language Models</td>
      <td>Babakhani et&nbsp;al., 2024</td>
      <td>IEEE Access</td>
      <td><a href="https://doi.org/10.1109/ACCESS.2024.3398553">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/06</td>
      <td>QOG: Question and Options Generation based on Language Model</td>
      <td>Zhou, 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2406.12381">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/07</td>
      <td>Automatic Question Generation and Constructed Response Scoring in Intelligent Texts.</td>
      <td>Morris et&nbsp;al., 2024</td>
      <td>CEUR-WS (L3MNGET@EDM)</td>
      <td><a href="https://ceur-ws.org/Vol-3840/L3MNGET24_paper2.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/10</td>
      <td>MIRROR: A Novel Approach for the Automated Evaluation of Open-Ended Question Generation.</td>
      <td>Deroy et&nbsp;al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2410.12893">PDF</a></td>
    </tr>
  </tbody>
</table>





<hr class="sep" />

<h1 id="sec-2">2. Context Base Question</h1>
  <h2 id="sec-2-1">2.1 Conversational Question</h2>
 <table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2020/10</td>
      <td>Job Interviewer Android with Elaborate Follow-up Question Generation</td>
      <td>Inoue et&nbsp;al., 2020</td>
      <td>ICMI 2020</td>
      <td><a href="https://sap.ist.i.kyoto-u.ac.jp/EN/bib/intl/INO-ICMI20.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2023/07</td>
      <td>Synthesize, Prompt and Transfer: Zero-shot Conversational Question Generation with Pre-trained Language Model</td>
      <td>Zeng et&nbsp;al., 2023</td>
      <td>ACL 2023</td>
      <td><a href="https://aclanthology.org/2023.acl-long.500.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/04</td>
      <td>Question Generation in Knowledge-Driven Dialog: Explainability and Evaluation</td>
      <td>Faille et&nbsp;al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2404.07836">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/08</td>
      <td>Consistency Training by Synthetic Question Generation for Conversational Question Answering</td>
      <td>Hemati et&nbsp;al., 2024</td>
      <td>ACL 2024 (Short)</td>
      <td><a href="https://aclanthology.org/2024.acl-short.57.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/09</td>
      <td>Corpus-informed Retrieval Augmented Generation of Clarifying Questions</td>
      <td>Krasakis et&nbsp;al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2409.18575">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2024/09</td>
      <td>Co-Trained Retriever-Generator Framework for Question Generation in Earnings Calls</td>
      <td>Juan et&nbsp;al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2409.18677">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2024/10</td>
      <td>AGENT-CQ: Automatic Generation and Evaluation of Clarifying Questions for Conversational Search with LLMs</td>
      <td>Siro et&nbsp;al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://staff.fnwi.uva.nl/m.derijke/wp-content/papercite-data/pdf/siro-2024-agent-cq-arxiv.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>8</td>
      <td>2024/11</td>
      <td>Context-Aware and User Intent-Aware Follow-Up Question Generation (CA-UIA-QG): Mimicking User Behavior in Multi-Turn Setting</td>
      <td>Dong et&nbsp;al., 2024</td>
      <td>Amazon Science (TR)</td>
      <td><a href="https://assets.amazon.science/ae/95/fc6b781a40b3866041e919468a55/context-aware-and-user-intent-aware-follow-up-question-generation-ca-uia-qg-mimicking-user-behavior-in-multi-turn-setting.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>9</td>
      <td>2025/01</td>
      <td>Improving Retrieval-Augmented Generation in Medicine with Iterative Follow-up Questions</td>
      <td>Xiong et&nbsp;al., 2025</td>
      <td>PSB 2025</td>
      <td><a href="https://psb.stanford.edu/psb-online/proceedings/psb25/xiong.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>10</td>
      <td>2025/01</td>
      <td>From Superficial to Deep: Integrating External Knowledge for Follow-up Question Generation Using Knowledge Graph and LLM</td>
      <td>Liu et&nbsp;al., 2025</td>
      <td>COLING 2025</td>
      <td><a href="https://aclanthology.org/2025.coling-main.55.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>11</td>
      <td>2025/07</td>
      <td>Follow-up Question Generation For Enhanced Patient-Provider Conversations</td>
      <td>Gatto et&nbsp;al., 2025</td>
      <td>ACL 2025</td>
      <td><a href="https://aclanthology.org/2025.acl-long.1226.pdf">PDF</a></td>
    </tr>
  </tbody>
</table>

  
  
  <h2 id="sec-2-2">2.2 Context Length Based</h2>
<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2020/02</td>
      <td>Capturing Greater Context for Question Generation</td>
      <td>Luu et&nbsp;al., 2020</td>
      <td>AAAI&nbsp;2020</td>
      <td><a href="https://cdn.aaai.org/ojs/6440/6440-13-9665-1-10-20200517.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2020/05</td>
      <td>Transformer-based End-to-End Question Generation</td>
      <td>Lopez et&nbsp;al., 2020</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2005.01107">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2020/07</td>
      <td>How to Ask Good Questions? Try to Leverage Paraphrases</td>
      <td>Jia et&nbsp;al., 2020</td>
      <td>ACL&nbsp;2020</td>
      <td><a href="https://aclanthology.org/2020.acl-main.545.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2023/07</td>
      <td>Selecting Better Samples from Pre-trained LLMs: A Case Study on Question Generation</td>
      <td>Yuan et&nbsp;al., 2023</td>
      <td>Findings&nbsp;ACL&nbsp;2023</td>
      <td><a href="https://aclanthology.org/2023.findings-acl.820.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/01</td>
      <td>A Unified Framework for Contextual and Factoid Question Generation</td>
      <td>Dong et&nbsp;al., 2024</td>
      <td>TKDE</td>
      <td><a href="https://openreview.net/forum?id=aQywPbwfTc">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2024/02</td>
      <td>NewsQs: Multi-Source Question Generation for the Inquiring Mind</td>
      <td>Hwang et&nbsp;al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2402.18479">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2024/05</td>
      <td>SGCM: Salience-Guided Context Modeling for Question Generation</td>
      <td>Ding et&nbsp;al., 2024</td>
      <td>LREC-COLING&nbsp;2024</td>
      <td><a href="https://aclanthology.org/2024.lrec-main.1285.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>8</td>
      <td>2024/05</td>
      <td>Long-Span Question-Answering: Automatic Question Generation and QA-System Ranking via Side-by-Side Evaluation</td>
      <td>Bohnet et&nbsp;al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2406.00179">PDF</a></td>
    </tr>
    <tr>
      <td>9</td>
      <td>2024/10</td>
      <td>Expanding Chatbot Knowledge in Customer Service: Context-Aware Similar Question Generation Using Large Language Models</td>
      <td>Hong et&nbsp;al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2410.12444">PDF</a></td>
    </tr>
    <tr>
      <td>10</td>
      <td>2025/01</td>
      <td>Leveraging In-Context Learning and Retrieval-Augmented Generation for Automatic Question Generation in Educational Domains</td>
      <td>Maity et&nbsp;al., 2025</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2501.17397">PDF</a></td>
    </tr>
  </tbody>
</table>

<hr class="sep" />

<h1 id="sec-3">3. Cognitive Level Based Question</h1>
  <h2 id="sec-3-1">3.1 Distractor Generation</h2>
<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2020/12</td>
      <td>Automatic Distractor Generation for Multiple-Choice Questions in Standard Tests</td>
      <td>Qiu et&nbsp;al., 2020</td>
      <td>COLING&nbsp;2020</td>
      <td><a href="https://aclanthology.org/2020.coling-main.189.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2021/07</td>
      <td>Multiple-choice question generation with auto-generated distractors for computer-assisted educational assessment</td>
      <td>Das et&nbsp;al., 2021</td>
      <td>MTAP&nbsp;2021</td>
      <td><a href="https://search.proquest.com/openview/3c6d3f8adb843e56f55510fa78695aca/1.pdf?cbl=54626&pq-origsite=gscholar">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2022/12</td>
      <td>CDGP: Automatic Cloze Distractor Generation based on Pre-trained Language Model</td>
      <td>Chiang et&nbsp;al., 2022</td>
      <td>Findings&nbsp;EMNLP’22</td>
      <td><a href="https://aclanthology.org/2022.findings-emnlp.429.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2023/07</td>
      <td>Distractor generation for multiple-choice questions with predictive prompting and large language models</td>
      <td>Bitew et&nbsp;al., 2023</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2307.16338">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2023/08</td>
      <td>Automated Distractor and Feedback Generation for Math Multiple-choice Questions via In-context Learning</td>
      <td>McNichols et&nbsp;al., 2023</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2308.03234">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2024/04</td>
      <td>Exploring Automated Distractor Generation for Math MCQs via LLMs</td>
      <td>Feng et&nbsp;al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2404.02124">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2024/06</td>
      <td>Exploring Automated Distractor Generation for Math Multiple-choice Questions via Large Language Models</td>
      <td>Feng et&nbsp;al., 2024</td>
      <td>Findings&nbsp;NAACL’24</td>
      <td><a href="https://aclanthology.org/2024.findings-naacl.193.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>8</td>
      <td>2024/08</td>
      <td>Enhancing Distractor Generation for Multiple-Choice Questions with Retrieval Augmented Pretraining and Knowledge Graph Integration</td>
      <td>Yu et&nbsp;al., 2024</td>
      <td>Findings&nbsp;ACL’24</td>
      <td><a href="https://aclanthology.org/2024.findings-acl.655.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>9</td>
      <td>2024/11</td>
      <td>DisGeM: Distractor Generation for Multiple Choice Questions with Span Masking</td>
      <td>Çavuşoğlu et&nbsp;al., 2024</td>
      <td>Findings&nbsp;EMNLP’24</td>
      <td><a href="https://aclanthology.org/2024.findings-emnlp.568.pdf">PDF</a></td>
    </tr>
  </tbody>
</table>



  
  <h2 id="sec-3-2">3.2 Bloom’s Taxonomy</h2>
  <table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2024/01</td>
      <td>How Teachers Can Use Large Language Models and Bloom’s Taxonomy to Create Educational Quizzes</td>
      <td>Elkins et&nbsp;al., 2024</td>
      <td>EAAI-24 (AAAI)</td>
      <td><a href="https://arxiv.org/pdf/2401.05914">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2024/07</td>
      <td>Automated Educational Question Generation at Different Bloom’s Skill Levels using Large Language Models: Strategies and Evaluation</td>
      <td>Scaria et&nbsp;al., 2024</td>
      <td>AIED&nbsp;2024 (LNCS)</td>
      <td><a href="https://arxiv.org/pdf/2408.04394">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/11</td>
      <td>Cognicraft: Smart Exam Question Generation with AI and Bloom’s Taxonomy</td>
      <td>Sagadraca et&nbsp;al., 2024</td>
      <td>ICCE&nbsp;2024</td>
      <td><a href="https://library.apsce.net/index.php/ICCE/article/download/4918/4847/6155">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2025/06</td>
      <td>From Objectives to Questions: A Planning-based Framework for Educational Mathematical Question Generation</td>
      <td>Cheng et&nbsp;al., 2025</td>
      <td>ACL&nbsp;2025</td>
      <td><a href="https://aclanthology.org/2025.acl-long.628.pdf">PDF</a></td>
    </tr>
  </tbody>
</table>

  
  
  
  <h2 id="sec-3-3">3.3 Multi Hop</h2>
  <table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2023/06</td>
      <td>Transformer-Based Multi-Hop Question Generation (Student Abstract)</td>
      <td>Emerson &amp; Chali, 2023</td>
      <td>AAAI’23 (Student Abstract)</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/26963/26735">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2023/12</td>
      <td>Improving Question Generation with Multi-level Content Planning</td>
      <td>Xia et&nbsp;al., 2023</td>
      <td>Findings EMNLP’23</td>
      <td><a href="https://aclanthology.org/2023.findings-emnlp.57.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/05</td>
      <td>Explainable Multi-hop Question Generation: An End-to-End Approach without Intermediate Question Labeling</td>
      <td>Hwang et&nbsp;al., 2024</td>
      <td>LREC-COLING’24</td>
      <td><a href="https://aclanthology.org/2024.lrec-main.599.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/06</td>
      <td>Prompting Few-shot Multi-hop Question Generation via Comprehending Type-aware Semantics</td>
      <td>Lin et&nbsp;al., 2024</td>
      <td>Findings NAACL’24</td>
      <td><a href="https://aclanthology.org/2024.findings-naacl.236.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2025/07</td>
      <td>Multi-Hop Question Generation via Dual-Perspective Keyword Guidance</td>
      <td>Li et&nbsp;al., 2025</td>
      <td>Findings ACL’25</td>
      <td><a href="https://aclanthology.org/2025.findings-acl.526.pdf">PDF</a></td>
    </tr>
  </tbody>
</table>

  
  
  <h2 id="sec-3-4">3.4 Deep Question</h2>
  <table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2020/07</td>
      <td>Semantic Graphs for Generating Deep Questions</td>
      <td>Pan et&nbsp;al., 2020</td>
      <td>ACL&nbsp;2020</td>
      <td><a href="https://aclanthology.org/2020.acl-main.135.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2020/12</td>
      <td>Exploring Question-Specific Rewards for Generating Deep Questions</td>
      <td>Xie et&nbsp;al., 2020</td>
      <td>COLING&nbsp;2020</td>
      <td><a href="https://aclanthology.org/2020.coling-main.228.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2020/12</td>
      <td>Answer-driven Deep Question Generation based on Reinforcement Learning</td>
      <td>Wang et&nbsp;al., 2020</td>
      <td>COLING&nbsp;2020</td>
      <td><a href="https://aclanthology.org/2020.coling-main.452.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/09</td>
      <td>RTRL: Relation-aware Transformer with Reinforcement Learning for Deep Question Generation</td>
      <td>Zeng et&nbsp;al., 2024</td>
      <td>KBS&nbsp;2024</td>
      <td><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4730126">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2025/05</td>
      <td>From Recall to Reasoning: Automated Question Generation for Deeper Math Learning through Large Language Models</td>
      <td>Yu et&nbsp;al., 2025</td>
      <td>AIED&nbsp;2025&nbsp;(LNCS)</td>
      <td><a href="https://arxiv.org/pdf/2505.11899">PDF</a></td>
    </tr>
  </tbody>
</table>

  
  
  <h2 id="sec-3-5">3.5 Miscellaneous Higher-Order Thinking</h2>

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>PDF Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2021/04</td>
      <td>Automatically Generating Cause-and-Effect Questions from Passages</td>
      <td>(Stasaski et&nbsp;al., 2021)</td>
      <td>BEA&nbsp;2021</td>
      <td><a href="https://aclanthology.org/2021.bea-1.17.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2024/05</td>
      <td>Can LLMs Generate Competency Questions?</td>
      <td>(Rebboud et&nbsp;al., 2024)</td>
      <td>ESWC&nbsp;2024</td>
      <td><a href="https://2024.eswc-conferences.org/wp-content/uploads/2024/05/77770070.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/06</td>
      <td>Improving Socratic Question Generation using Data Augmentation and Preference Optimization</td>
      <td>(Kumar &amp;&nbsp;Lan, 2024)</td>
      <td>BEA&nbsp;2024</td>
      <td><a href="https://aclanthology.org/2024.bea-1.10.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/09</td>
      <td>Automated Generation of Competency Questions Using Large Language Models and Knowledge Graphs</td>
      <td>(Di&nbsp;Nuzzo et&nbsp;al., 2024)</td>
      <td>NLP4KGC@SEMANTICS&nbsp;2024</td>
      <td><a href="https://ceur-ws.org/Vol-3874/paper10.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/11</td>
      <td>Critical Questions Generation: Motivation and Challenges</td>
      <td>(Calvo&nbsp;Figueras &amp;&nbsp;Agerri, 2024)</td>
      <td>CoNLL&nbsp;2024</td>
      <td><a href="https://aclanthology.org/2024.conll-1.9.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2025/07</td>
      <td>Automatic Generation of Inference Making Questions for Reading Comprehension Assessments</td>
      <td>(Ma et&nbsp;al., 2025)</td>
      <td>BEA&nbsp;2025</td>
      <td><a href="https://aclanthology.org/2025.bea-1.31.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2025/07</td>
      <td>ELLIS Alicante at CQs-Gen 2025: Winning the critical thinking questions shared task: LLM-based question generation and selection</td>
      <td>(Favero et&nbsp;al., 2025)</td>
      <td>ArgMining&nbsp;2025</td>
      <td><a href="https://aclanthology.org/2025.argmining-1.31.pdf">PDF</a></td>
    </tr>
  </tbody>
</table>























<hr class="sep" />

<h1 id="sec-4">4. Control and Guidance Mechanism Based Question</h1>
  
  <h2 id="sec-4-1">4.1 Diverse Question Generation</h2>
<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2023/12</td>
      <td>Diversify Question Generation with Retrieval-Augmented Style Transfer</td>
      <td>Gou et&nbsp;al., 2023</td>
      <td>EMNLP&nbsp;2023</td>
      <td><a href="https://aclanthology.org/2023.emnlp-main.104.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2023/12</td>
      <td>PROTEGE: Prompt-based Diverse Question Generation from Web Articles</td>
      <td>Puranik et&nbsp;al., 2023</td>
      <td>Findings&nbsp;EMNLP&nbsp;2023</td>
      <td><a href="https://aclanthology.org/2023.findings-emnlp.362.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/03</td>
      <td>Understanding the Role of Temperature in Diverse Question Generation by GPT-4</td>
      <td>Agarwal et&nbsp;al., 2024</td>
      <td>SIGCSE&nbsp;TS&nbsp;2024&nbsp;(Poster)</td>
      <td><a href="https://arxiv.org/pdf/2404.09366">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/05</td>
      <td>Diversifying Question Generation over Knowledge Base via External Natural Questions</td>
      <td>Guo et&nbsp;al., 2024</td>
      <td>LREC-COLING&nbsp;2024</td>
      <td><a href="https://aclanthology.org/2024.lrec-main.454.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/11</td>
      <td>Enhancing Diversity in Difficulty-Controllable Question Generation for Reading Comprehension via Extended T5</td>
      <td>Goto et&nbsp;al., 2024</td>
      <td>ICCE&nbsp;2024</td>
      <td><a href="https://library.apsce.net/index.php/ICCE/article/download/4813/4748">PDF</a></td>
    </tr>
  </tbody>
</table>

  
  <h2 id="sec-4-2">4.2 Difficulty Control</h2>
  <table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link to PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2024/07</td>
      <td>AI-Assisted Generation of Difficult Math Questions</td>
      <td>Shah et&nbsp;al.,&nbsp;2024</td>
      <td>arXiv (preprint)</td>
      <td><a href="https://arxiv.org/pdf/2407.21009" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2024/11</td>
      <td>Enhancing Diversity in Difficulty-Controllable Question Generation for Reading Comprehension via Extended T5</td>
      <td>Goto et&nbsp;al.,&nbsp;2024</td>
      <td>ICCE&nbsp;2024</td>
      <td><a href="https://library.apsce.net/index.php/ICCE/article/download/4813/4748" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/11</td>
      <td>Difficulty-Controllable Reading Comprehension Question Generation Considering the Difficulty of Reading Passages</td>
      <td>Tomikawa &amp; Uto,&nbsp;2024</td>
      <td>ICCE&nbsp;2024</td>
      <td><a href="https://library.apsce.net/index.php/ICCE/article/download/4931/4861/6183" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/12</td>
      <td>Give me Some Hard Questions: Synthetic Data Generation for Clinical QA</td>
      <td>Bai et&nbsp;al.,&nbsp;2024</td>
      <td>ML4H&nbsp;2024 Findings (arXiv)</td>
      <td><a href="https://arxiv.org/pdf/2412.04573" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2025/05</td>
      <td>KAQG: A Knowledge-Graph-Enhanced RAG for Difficulty-Controlled Question Generation</td>
      <td>Chen &amp; Shiu,&nbsp;2025</td>
      <td>arXiv (preprint)</td>
      <td><a href="https://arxiv.org/pdf/2505.07618" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2025/05</td>
      <td>KG-QAGen: A Knowledge-Graph-Based Framework for Systematic Question Generation and Long-Context LLM Evaluation</td>
      <td>Tatarinov et&nbsp;al.,&nbsp;2025</td>
      <td>arXiv (preprint)</td>
      <td><a href="https://arxiv.org/pdf/2505.12495" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2025/07</td>
      <td>Advancing Question Generation with Joint Narrative and Difficulty Control</td>
      <td>Leite &amp; Lopes&nbsp;Cardoso,&nbsp;2025</td>
      <td>BEA&nbsp;2025 (ACL Workshop)</td>
      <td><a href="https://aclanthology.org/2025.bea-1.46.pdf" target="_blank">PDF</a></td>
    </tr>
  </tbody>
</table>

  
  
  <h2 id="sec-4-3">4.3 Scalable &amp; Efficient</h2>
  <table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link to PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2023/05</td>
      <td>Scalable Educational Question Generation with Pre-trained Language Models</td>
      <td>Bulathwela et&nbsp;al.,&nbsp;2023</td>
      <td>AIED&nbsp;2023 (arXiv)</td>
      <td><a href="https://arxiv.org/pdf/2305.07871.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2024/10</td>
      <td>GaQR: An Efficient Generation-augmented Question Rewriter</td>
      <td>Young et&nbsp;al.,&nbsp;2024</td>
      <td>CIKM&nbsp;2024</td>
      <td><a href="https://staff.fnwi.uva.nl/m.derijke/wp-content/papercite-data/pdf/young-2024-gaqr.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2025/01</td>
      <td>A Novel Approach to Scalable and Automatic Topic-Controlled Question Generation in Education</td>
      <td>Li et&nbsp;al.,&nbsp;2025</td>
      <td>LAK&nbsp;2025 (arXiv)</td>
      <td><a href="https://arxiv.org/pdf/2501.05220.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2025/02</td>
      <td>Savaal: Scalable Concept-Driven Question Generation to Enhance Human Learning</td>
      <td>Noorbakhsh et&nbsp;al.,&nbsp;2025</td>
      <td>arXiv (preprint)</td>
      <td><a href="https://arxiv.org/pdf/2502.12477.pdf" target="_blank">PDF</a></td>
    </tr>
  </tbody>
</table>

  
  
  
  <h2 id="sec-4-4">4.4 Miscellaneous Control</h2>
<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link to PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2020/02</td>
      <td>Neural Question Generation with Answer Pivot</td>
      <td>Wang&nbsp;et&nbsp;al.,&nbsp;2020</td>
      <td>AAAI&nbsp;2020</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/download/6449/6305" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2020/02</td>
      <td>Improving Question Generation with Sentence-Level Semantic Matching and Answer Position Inferring</td>
      <td>Ma&nbsp;et&nbsp;al.,&nbsp;2020</td>
      <td>AAAI&nbsp;2020</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6366/6222" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2020/11</td>
      <td>Tell Me How to Ask Again: Question Data Augmentation with Controllable Rewriting in Continuous Space</td>
      <td>Liu&nbsp;et&nbsp;al.,&nbsp;2020</td>
      <td>EMNLP&nbsp;2020</td>
      <td><a href="https://aclanthology.org/2020.emnlp-main.467.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2023/06</td>
      <td>Automatic Skill-Oriented Question Generation and Recommendation for Intelligent Job Interviews</td>
      <td>Qin&nbsp;et&nbsp;al.,&nbsp;2023</td>
      <td>ACM&nbsp;TOIS&nbsp;2023</td>
      <td><a href="https://dl.acm.org/doi/pdf/10.1145/3604552" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2023/11</td>
      <td>Encoding Paraphrase Information Generated by ChatGPT and Introducing Interrogative Word Control Mechanism for Question Generation</td>
      <td>Jiang&nbsp;et&nbsp;al.,&nbsp;2023</td>
      <td>IALP&nbsp;2023</td>
      <td><a href="https://www.colips.org/conferences/ialp2023/proceedings/papers/IALP2023_P050.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2024/01</td>
      <td>How the Advent of Ubiquitous Large Language Models both Stymie and Turbocharge Dynamic Adversarial Question Generation</td>
      <td>Sung&nbsp;et&nbsp;al.,&nbsp;2024</td>
      <td>arXiv&nbsp;(preprint)</td>
      <td><a href="https://arxiv.org/pdf/2401.11185" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2024/05</td>
      <td>Agenda-Driven Question Generation: A Case Study in the Courtroom Domain</td>
      <td>Fung&nbsp;et&nbsp;al.,&nbsp;2024</td>
      <td>LREC-COLING&nbsp;2024</td>
      <td><a href="https://aclanthology.org/2024.lrec-main.49.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>8</td>
      <td>2024/08</td>
      <td>Planning First, Question Second: An LLM-Guided Method for Controllable Question Generation</td>
      <td>Li&nbsp;&amp;&nbsp;Zhang,&nbsp;2024</td>
      <td>Findings&nbsp;of&nbsp;ACL&nbsp;2024</td>
      <td><a href="https://aclanthology.org/2024.findings-acl.280.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>9</td>
      <td>2024/11</td>
      <td>Disentangling Questions from Query Generation for Task-Adaptive Retrieval</td>
      <td>Lee&nbsp;et&nbsp;al.,&nbsp;2024</td>
      <td>Findings&nbsp;of&nbsp;EMNLP&nbsp;2024</td>
      <td><a href="https://aclanthology.org/2024.findings-emnlp.274.pdf" target="_blank">PDF</a></td>
    </tr>
  </tbody>
</table>






<hr class="sep" />

<h1 id="sec-5">5. Multilingual &amp; Multimodality Based Question</h1>
  <h2 id="sec-5-1">5.1 Multi-Lingual</h2>
<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2022/10</td>
      <td>Learning to Reuse Distractors to support Multiple Choice Question Generation in Education</td>
      <td>(Bitew et&nbsp;al.,&nbsp;2022)</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2210.13964">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2023/10</td>
      <td>Few-shot is enough: exploring ChatGPT prompt engineering method for automatic question generation in English education</td>
      <td>(Lee et&nbsp;al.,&nbsp;2023)</td>
      <td>E&IT</td>
      <td><a href="https://link.springer.com/article/10.1007/s10639-023-12249-8">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/01</td>
      <td>Answer Agnostic Question Generation in Bangla Language</td>
      <td>(Fahad et&nbsp;al.,&nbsp;2024)</td>
      <td>IJNDC</td>
      <td><a href="https://link.springer.com/article/10.1007/s44227-023-00018-5">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/01</td>
      <td>A Novel Multi-Stage Prompting Approach for Language Agnostic MCQ Generation using GPT</td>
      <td>(Maity et&nbsp;al.,&nbsp;2024)</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/abs/2401.07098">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/04</td>
      <td>Automatic Generation and Evaluation of Reading Comprehension Test Items with Large Language Models</td>
      <td>(Säuberli et&nbsp;al.,&nbsp;2024)</td>
      <td>arXiv/LREC-COLING&nbsp;REaDIt</td>
      <td><a href="https://arxiv.org/abs/2404.07720">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2024/04</td>
      <td>Towards automatic question generation using pre-trained model in academic field for Bahasa Indonesia</td>
      <td>(Suhartono et&nbsp;al.,&nbsp;2024)</td>
      <td>E&IT</td>
      <td><a href="https://link.springer.com/article/10.1007/s10639-024-12717-9">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2024/05</td>
      <td>Transformer Models for Brazilian Portuguese Question Generation: An Experimental Study</td>
      <td>(Junqueira et&nbsp;al.,&nbsp;2024)</td>
      <td>FLAIRS&nbsp;2024</td>
      <td><a href="https://journals.flvc.org/FLAIRS/article/download/135334/139788/260102">PDF</a></td>
    </tr>
    <tr>
      <td>8</td>
      <td>2024/05</td>
      <td>Knowledge-Guided Cross-Topic Visual Question Generation</td>
      <td>(Liu et&nbsp;al.,&nbsp;2024)</td>
      <td>LREC-COLING&nbsp;2024</td>
      <td><a href="https://aclanthology.org/2024.lrec-main.861.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>9</td>
      <td>2024/06</td>
      <td>FairytaleQA Translated: Enabling Educational Q&amp;A Generation in Less-Resourced Languages</td>
      <td>(Leite et&nbsp;al.,&nbsp;2024)</td>
      <td>arXiv/Springer</td>
      <td><a href="https://arxiv.org/abs/2406.04233">PDF</a></td>
    </tr>
    <tr>
      <td>10</td>
      <td>2024/06</td>
      <td>Arabic Automatic Question Generation using Transformer</td>
      <td>(Alhashedi et&nbsp;al.,&nbsp;2024)</td>
      <td>AIP&nbsp;Conf.&nbsp;Proc.</td>
      <td><a href="https://pubs.aip.org/aip/acp/article-pdf/doi/10.1063/5.0199032/19984173/050035_1_5.0199032.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>11</td>
      <td>2024/06</td>
      <td>Automated Question Generation for Science Tests in Arabic Language Using NLP Techniques</td>
      <td>(Tami et&nbsp;al.,&nbsp;2024)</td>
      <td>arXiv/Springer</td>
      <td><a href="https://arxiv.org/abs/2406.08520">PDF</a></td>
    </tr>
    <tr>
      <td>12</td>
      <td>2024/11</td>
      <td>Cross-lingual Transfer for Automatic Question Generation by Learning Interrogative Structures in Target Languages</td>
      <td>(Hwang et&nbsp;al.,&nbsp;2024)</td>
      <td>EMNLP&nbsp;2024</td>
      <td><a href="https://aclanthology.org/2024.emnlp-main.186.pdf">PDF</a></td>
    </tr>
  </tbody>
</table>

  
  <h2 id="sec-5-2">5.2 Multimodality–Image</h2>

  <table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link of PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2017/09</td>
      <td>Visual Question Generation as Dual Task of Visual Question Answering</td>
      <td>(Li et&nbsp;al., 2018)</td>
      <td>CVPR</td>
      <td><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Visual_Question_Generation_CVPR_2018_paper.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2023/09</td>
      <td>SSN MLRG at MEDVQA-GI 2023: Visual Question Generation and Answering using Transformer based Pre-trained Models</td>
      <td>(Mohamed et&nbsp;al., 2023)</td>
      <td>CLEF (CEUR-WS)</td>
      <td><a href="https://ceur-ws.org/Vol-3497/paper-135.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/01</td>
      <td>Advancing Large Multi-modal Models with Explicit Chain-of-Reasoning and Visual Question Generation</td>
      <td>(Uehara et&nbsp;al., 2024)</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2401.10005" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/02</td>
      <td>ConVQG: Contrastive Visual Question Generation with Multimodal Guidance</td>
      <td>(Mi et&nbsp;al., 2024)</td>
      <td>AAAI</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/28216/28427" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/05</td>
      <td>Look before You Leap: Dual Logical Verification for Knowledge-based Visual Question Generation</td>
      <td>(Liu et&nbsp;al., 2024)</td>
      <td>LREC-COLING</td>
      <td><a href="https://aclanthology.org/2024.lrec-main.943.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2024/05</td>
      <td>Knowledge-Guided Cross-Topic Visual Question Generation</td>
      <td>(H. Liu et&nbsp;al., 2024)</td>
      <td>LREC-COLING</td>
      <td><a href="https://aclanthology.org/2024.lrec-main.861.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2024/07</td>
      <td>Synthetic Multimodal Question Generation</td>
      <td>(Wu et&nbsp;al., 2024)</td>
      <td>Findings of EMNLP</td>
      <td><a href="https://aclanthology.org/2024.findings-emnlp.759.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>8</td>
      <td>2025/01</td>
      <td>Automated Generation of Challenging Multiple-Choice Questions for Vision Language Model Evaluation</td>
      <td>(Zhang et&nbsp;al., 2025)</td>
      <td>CVPR</td>
      <td><a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Zhang_Automated_Generation_of_Challenging_Multiple-Choice_Questions_for_Vision_Language_Model_CVPR_2025_paper.pdf" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>9</td>
      <td>2025/03</td>
      <td>AutoDrive-QA: Automated Generation of Multiple-Choice Questions for Autonomous Driving Datasets Using Large Vision-Language Models</td>
      <td>(Khalili &amp; Smyth, 2025)</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2503.15778" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>10</td>
      <td>2025/04</td>
      <td>AI-Assisted Multiple-Choice Questions Generation with Multimodal Large Language Models in Engineering Higher Education</td>
      <td>(Shu et&nbsp;al., 2025)</td>
      <td>EDUCON</td>
      <td><a href="https://qmro.qmul.ac.uk/xmlui/bitstream/handle/123456789/107960/Shu%20Ai-Assisted%20Multiple-Choice%202025%20Accepted.pdf?sequence=2" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>11</td>
      <td>2025/06</td>
      <td>Focusing on Students, not Machines: Grounded Question Generation and Automated Answer Grading</td>
      <td>(Meyer &amp; Breuer, 2025)</td>
      <td>arXiv (Thesis)</td>
      <td><a href="https://arxiv.org/pdf/2506.12066" target="_blank">PDF</a></td>
    </tr>
    <tr>
      <td>12</td>
      <td>2025/02</td>
      <td>Explicitly Guided Difficulty-Controllable Visual Question Generation</td>
      <td>(Xie et&nbsp;al., 2025)</td>
      <td>AAAI</td>
      <td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/34745/36900" target="_blank">PDF</a></td>
    </tr>
  </tbody>
</table>

  <h2 id="sec-5-3">5.3 Multimodality–Other</h2>


<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Venue (short)</th>
      <th>Link to PDF</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2020/11</td>
      <td>PathQG: Neural Question Generation from Facts</td>
      <td>Wang et al., 2020</td>
      <td>EMNLP 2020</td>
      <td><a href="https://aclanthology.org/2020.emnlp-main.729.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2020/12</td>
      <td>Knowledge-enriched, Type-constrained and Grammar-guided Question Generation over Knowledge Bases</td>
      <td>Bi et al., 2020</td>
      <td>COLING 2020</td>
      <td><a href="https://aclanthology.org/2020.coling-main.250.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2023/10</td>
      <td>Prompting Large Language Models with Chain-of-Thought for Few-Shot Knowledge Base Question Generation</td>
      <td>Liang et al., 2023</td>
      <td>EMNLP 2023</td>
      <td><a href="https://aclanthology.org/2023.emnlp-main.263.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/04</td>
      <td>SGSH: Stimulate Large Language Models with Skeleton Heuristics for Knowledge Base Question Generation</td>
      <td>Guo et al., 2024</td>
      <td>Findings NAACL 2024</td>
      <td><a href="https://aclanthology.org/2024.findings-naacl.59.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/04</td>
      <td>QANA: LLM-based Question Generation and Network Analysis for Zero-shot Key Point Analysis and Beyond</td>
      <td>Fukuma et al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2404.18371">PDF</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2024/05</td>
      <td>Diversifying Question Generation over Knowledge Base via External Natural Questions</td>
      <td>Guo et al., 2024</td>
      <td>LREC-COLING 2024</td>
      <td><a href="https://aclanthology.org/2024.lrec-main.454.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2024/07</td>
      <td>Automated Question Generation on Tabular Data for Conversational Data Exploration</td>
      <td>Chaudhuri et al., 2024</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2407.12859">PDF</a></td>
    </tr>
    <tr>
      <td>8</td>
      <td>2024/11</td>
      <td>ECIS-VQG: Generation of Entity-centric Information-seeking Questions from Videos</td>
      <td>Phukan et al., 2024</td>
      <td>EMNLP 2024</td>
      <td><a href="https://aclanthology.org/2024.emnlp-main.798.pdf">PDF</a></td>
    </tr>
    <tr>
      <td>9</td>
      <td>2025/03</td>
      <td>Queryfy: from knowledge graphs to questions using open Large Language Models — Enabling finetuning by question generation on given knowledge</td>
      <td>Brei et al., 2025</td>
      <td>IT-Information Technology (Journal)</td>
      <td><a href="https://www.degruyterbrill.com/document/doi/10.1515/itit-2024-0079/pdf?licenseType=open-access">PDF</a></td>
    </tr>
    <tr>
      <td>10</td>
      <td>2025/03</td>
      <td>ETVA: Evaluation of Text-to-Video Alignment via Fine-grained Question Generation and Answering</td>
      <td>Guan et al., 2025</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2503.16867">PDF</a></td>
    </tr>
    <tr>
      <td>11</td>
      <td>2025/04</td>
      <td>Context Selection and Rewriting for Video-based Educational Question Generation</td>
      <td>Yu et al., 2025</td>
      <td>arXiv</td>
      <td><a href="https://arxiv.org/pdf/2504.19406">PDF</a></td>
    </tr>
  </tbody>
</table>



<hr class="sep" />

<h1 id="sec-6">6. Datasets</h1>

<hr class="sep" />

<h1 id="sec-7">7. Evaluation Metrics</h1>
  <h2 id="sec-7-1">7.1 Automatic Metrics</h2>
  <h2 id="sec-7-2">7.2 Human Metrics</h2>

<hr class="sep" />

<h1 id="sec-8">8. FAQ</h1>

<p><a class="top" href="#top">Back to top ↑</a></p>

</body>
</html>

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Code Repository / GitHub Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2022/01</td>
      <td>Leaf: Multiple-Choice Question Generation</td>
      <td>Vachev et al., 2022</td>
      <td><a href="https://github.com/KristiyanVachev/Leaf-Question-Generation" target="_blank">github.com/KristiyanVachev/Leaf-Question-Generation</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2022/07</td>
      <td>Reading Comprehension Quiz Generation using Generative Pre-trained Transformers</td>
      <td>Dijkstra et al., 2022</td>
      <td><a href="https://github.com/RamonDijkstra/EduQuiz" target="_blank">github.com/RamonDijkstra/EduQuiz</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/10</td>
      <td>MCQG-SRefine: Multiple Choice Question Generation and Evaluation with Iterative Self-Critique, Correction, and Comparison Feedback</td>
      <td>Yao et al., 2024</td>
      <td><a href="https://github.com/bio-nlp/MedQG" target="_blank">github.com/bio-nlp/MedQG</a></td>
    </tr>
  </tbody>
</table>
<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation in Short form</th>
      <th>Code Repository / GitHub Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2023/07</td>
      <td>Synthesize, Prompt and Transfer: Zero-shot Conversational Question Generation with Pre-trained Language Model</td>
      <td>[Zeng&nbsp;et&nbsp;al.,&nbsp;2023]</td>
      <td><a href="https://github.com/hongweizeng/ZeroCQG">https://github.com/hongweizeng/ZeroCQG</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2024/08</td>
      <td>Consistency Training by Synthetic Question Generation for Conversational Question Answering</td>
      <td>[Hematian&nbsp;&amp;&nbsp;Beigy,&nbsp;2024]</td>
      <td><a href="https://github.com/HamedHematian/SynCQG">https://github.com/HamedHematian/SynCQG</a></td>
    </tr>
  </tbody>
</table>

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Code Repository / GitHub Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2020/04</td>
      <td>Semantic Graphs for Generating Deep Questions</td>
      <td>(Pan et&nbsp;al., 2020)</td>
      <td><a href="https://github.com/WING-NUS/SG-Deep-Question-Generation">github.com/WING-NUS/SG-Deep-Question-Generation</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2020/12</td>
      <td>Exploring Question-Specific Rewards for Generating Deep Questions</td>
      <td>(Xie et&nbsp;al., 2020)</td>
      <td><a href="https://github.com/YuxiXie/RL-for-Question-Generation">github.com/YuxiXie/RL-for-Question-Generation</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2020/12</td>
      <td>Automatic Distractor Generation for Multiple-Choice Questions in Standard Tests (EDGE)</td>
      <td>(Qiu et&nbsp;al., 2020)</td>
      <td><a href="https://github.com/zpqiu/EDGE">github.com/zpqiu/EDGE</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2022/12</td>
      <td>CDGP: Automatic Cloze Distractor Generation based on Pre-trained Language Model</td>
      <td>(Chiang et&nbsp;al., 2022)</td>
      <td><a href="https://github.com/AndyChiangSH/CDGP">github.com/AndyChiangSH/CDGP</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2023/07</td>
      <td>Distractor Generation for MCQs with Predictive Prompting &amp; LLMs</td>
      <td>(Kiros et&nbsp;al., 2023)</td>
      <td><a href="https://github.com/semerekiros/distractGPT">github.com/semerekiros/distractGPT</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2024/03</td>
      <td>Improving Socratic Question Generation using Data Augmentation &amp; Preference Optimization</td>
      <td>(Ashok&nbsp;Kumar &amp; Lan, 2024)</td>
      <td><a href="https://github.com/umass-ml4ed/socratic-quest-gen">github.com/umass-ml4ed/socratic-quest-gen</a></td>
    </tr>
    <tr>
      <td>7</td>
      <td>2024/03</td>
      <td>Explainable Multi-hop Question Generation: End-to-End without Intermediate Labeling</td>
      <td>(Hwang et&nbsp;al., 2024)</td>
      <td><a href="https://github.com/SeonjeongHwang/e2eQR">github.com/SeonjeongHwang/e2eQR</a></td>
    </tr>
    <tr>
      <td>8</td>
      <td>2024/04</td>
      <td>Exploring Automated Distractor Generation for Math MCQs via LLMs</td>
      <td>(Feng et&nbsp;al., 2024)</td>
      <td><a href="https://github.com/umass-ml4ed/prompt_distractor_generation_NAACL">github.com/umass-ml4ed/prompt_distractor_generation_NAACL</a></td>
    </tr>
    <tr>
      <td>9</td>
      <td>2024/08</td>
      <td>Automated Educational Question Generation at Different Bloom’s Skill Levels</td>
      <td>(Scaria et&nbsp;al., 2024)</td>
      <td><a href="https://github.com/nicyscaria/AEQG_Blooms_Evaluation_LLMs">github.com/nicyscaria/AEQG_Blooms_Evaluation_LLMs</a></td>
    </tr>
    <tr>
      <td>10</td>
      <td>2024/09</td>
      <td>DisGeM: Distractor Generation for MCQs with Span Masking</td>
      <td>(Ekmekci et&nbsp;al., 2024)</td>
      <td><a href="https://github.com/obss/disgem">github.com/obss/disgem</a></td>
    </tr>
    <tr>
      <td>11</td>
      <td>2024/10</td>
      <td>Critical Questions Generation: Motivation and Challenges</td>
      <td>(Figueras et&nbsp;al., 2024)</td>
      <td><a href="https://github.com/hitz-zentroa/critical_questions_generation">github.com/hitz-zentroa/critical_questions_generation</a></td>
    </tr>
  </tbody>
</table>


<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation in Short form</th>
      <th>Code Repository/ GitHub Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2023/10</td>
      <td>Diversify Question Generation with Retrieval-Augmented Style Transfer (RAST)</td>
      <td>(Gou et&nbsp;al., 2023)</td>
      <td><a href="https://github.com/gouqi666/RAST" target="_blank">github.com/gouqi666/RAST</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2024/05</td>
      <td>Diversifying Question Generation over Knowledge Base via External Natural Questions</td>
      <td>(Guo et&nbsp;al., 2024)</td>
      <td><a href="https://github.com/PersistenceForever/DiversifyQG" target="_blank">github.com/PersistenceForever/DiversifyQG</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/10</td>
      <td>GaQR: An Efficient Generation-augmented Question Rewriter</td>
      <td>(Young et&nbsp;al., 2024)</td>
      <td><a href="https://github.com/youngbeauty250/GaQR" target="_blank">github.com/youngbeauty250/GaQR</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2025/05</td>
      <td>KG-QAGen: A Knowledge-Graph-Based Framework for Systematic Question Generation and Long-Context LLM Evaluation</td>
      <td>(Tatarinov et&nbsp;al., 2025)</td>
      <td><a href="https://github.com/gtfintechlab/KG-QAGen" target="_blank">github.com/gtfintechlab/KG-QAGen</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2025/05</td>
      <td>KAQG: A Knowledge-Graph-Enhanced RAG for Difficulty-Controlled Question Generation</td>
      <td>(Chen &amp; Shiu, 2025)</td>
      <td><a href="https://github.com/mfshiu/kaqg" target="_blank">github.com/mfshiu/kaqg</a></td>
    </tr>
  </tbody>
</table>




<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>SN</th>
      <th>Time (YYYY/MM)</th>
      <th>Title</th>
      <th>Inline Citation (short)</th>
      <th>Code Repository / GitHub Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2020/11</td>
      <td>PathQG: Neural Question Generation from Facts</td>
      <td>Wang et&nbsp;al., 2020</td>
      <td><a href="https://github.com/SiyuanWangw/PathQG">https://github.com/SiyuanWangw/PathQG</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2024/04</td>
      <td>SGSH: Stimulate Large Language Models with Skeleton Heuristics for Knowledge Base Question Generation</td>
      <td>Guo et&nbsp;al., 2024</td>
      <td><a href="https://github.com/RUCKBReasoning/SGSH">https://github.com/RUCKBReasoning/SGSH</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/05</td>
      <td>Diversifying Question Generation over Knowledge Base via External Natural Questions</td>
      <td>Guo et&nbsp;al., 2024</td>
      <td><a href="https://github.com/RUCKBReasoning/DiversifyQG">https://github.com/RUCKBReasoning/DiversifyQG</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/11</td>
      <td>ECIS-VQG: Generation of Entity-centric Information-seeking Questions from Videos</td>
      <td>Phukan et&nbsp;al., 2024</td>
      <td><a href="https://github.com/thePhukan/ECIS-VQG">https://github.com/thePhukan/ECIS-VQG</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>2025/03</td>
      <td>ETVA: Evaluation of Text-to-Video Alignment via Fine-grained Question Generation and Answering</td>
      <td>Guan et&nbsp;al., 2025</td>
      <td><a href="https://github.com/guankaisi/ETVA">https://github.com/guankaisi/ETVA</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td>2025/05</td>
      <td>KG-QAGen: A Knowledge-Graph-Based Framework for Systematic Question Generation and Long-Context LLM Evaluation</td>
      <td>Tatarinov et&nbsp;al., 2025</td>
      <td><a href="https://github.com/gtfintechlab/KG-QAGen">https://github.com/gtfintechlab/KG-QAGen</a></td>
    </tr>
  </tbody>
</table>










