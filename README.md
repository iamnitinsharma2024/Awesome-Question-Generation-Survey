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

<hr class="sep" />

<h1 id="sec-3">3. Cognitive Level Based Question</h1>
  <h2 id="sec-3-1">3.1 Distractor Generation</h2>
  <h2 id="sec-3-2">3.2 Bloom’s Taxonomy</h2>
  <h2 id="sec-3-3">3.3 Multi Hop</h2>
  <h2 id="sec-3-4">3.4 Deep Question</h2>
  <h2 id="sec-3-5">3.5 Miscellaneous Higher-Order Thinking</h2>

<hr class="sep" />

<h1 id="sec-4">4. Control and Guidance Mechanism Based Question</h1>
  <h2 id="sec-4-1">4.1 Diverse Question Generation</h2>
  <h2 id="sec-4-2">4.2 Difficulty Control</h2>
  <h2 id="sec-4-3">4.3 Scalable &amp; Efficient</h2>
  <h2 id="sec-4-4">4.4 Miscellaneous Control</h2>

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
      <th>GitHub Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>2022/10</td>
      <td>Learning to Reuse Distractors to support Multiple Choice Question Generation in Education</td>
      <td>(Bitew et&nbsp;al.,&nbsp;2022)</td>
      <td><a href="https://github.com/semerekiros/dist-retrieval">semerekiros/dist-retrieval</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>2023/10</td>
      <td>Few-shot is enough: exploring ChatGPT prompt engineering method for AQG in English education</td>
      <td>(Lee et&nbsp;al.,&nbsp;2023)</td>
      <td>—</td>
    </tr>
    <tr>
      <td>3</td>
      <td>2024/01</td>
      <td>Answer Agnostic Question Generation in Bangla Language</td>
      <td>(Fahad et&nbsp;al.,&nbsp;2024)</td>
      <td>—</td>
    </tr>
    <tr>
      <td>4</td>
      <td>2024/01</td>
      <td>A Novel Multi-Stage Prompting Approach for Language Agnostic MCQ Generation using GPT</td>
      <td>(Maity et&nbsp;al.,&nbsp;2024)</td>
      <td>—</td>
    </tr>
    <tr>
      <td>5</td>
      <td>2024/04</td>
      <td>Automatic Generation and Evaluation of Reading Comprehension Test Items with LLMs</td>
      <td>(Säuberli et&nbsp;al.,&nbsp;2024)</td>
      <td>—</td>
    </tr>
    <tr>
      <td>6</td>
      <td>2024/04</td>
      <td>Towards automatic question generation … Bahasa Indonesia</td>
      <td>(Suhartono et&nbsp;al.,&nbsp;2024)</td>
      <td>—</td>
    </tr>
    <tr>
      <td>7</td>
      <td>2024/05</td>
      <td>Transformer Models for Brazilian Portuguese Question Generation</td>
      <td>(Junqueira et&nbsp;al.,&nbsp;2024)</td>
      <td>—</td>
    </tr>
    <tr>
      <td>8</td>
      <td>2024/05</td>
      <td>Knowledge-Guided Cross-Topic Visual Question Generation</td>
      <td>(Liu et&nbsp;al.,&nbsp;2024)</td>
      <td>—</td>
    </tr>
    <tr>
      <td>9</td>
      <td>2024/06</td>
      <td>FairytaleQA Translated: Enabling Educational Q&amp;A Generation in Less-Resourced Languages</td>
      <td>(Leite et&nbsp;al.,&nbsp;2024)</td>
      <td><a href="https://github.com/bernardoleite/fairytaleqa-translated">bernardoleite/fairytaleqa-translated</a></td>
    </tr>
    <tr>
      <td>10</td>
      <td>2024/06</td>
      <td>Arabic Automatic Question Generation using Transformer</td>
      <td>(Alhashedi et&nbsp;al.,&nbsp;2024)</td>
      <td>—</td>
    </tr>
    <tr>
      <td>11</td>
      <td>2024/06</td>
      <td>Automated Question Generation for Science Tests in Arabic …</td>
      <td>(Tami et&nbsp;al.,&nbsp;2024)</td>
      <td>—</td>
    </tr>
    <tr>
      <td>12</td>
      <td>2024/11</td>
      <td>Cross-lingual Transfer for Automatic Question Generation by Learning Interrogative Structures …</td>
      <td>(Hwang et&nbsp;al.,&nbsp;2024)</td>
      <td>—</td>
    </tr>
  </tbody>
</table>

