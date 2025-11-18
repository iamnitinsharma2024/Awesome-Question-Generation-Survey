# Question Types for Primary Education and Neural Question Generation

## 1. Introduction

Question generation is a key activity in both classroom teaching and AI-based learning systems. A clear list of question types helps teachers plan worksheets, tests, and discussions. It also gives a practical framework for researchers who design neural question generation (QG) models for education.

The document behind this article organises question types into five broad groups: (1) format-based questions, (2) higher-order thinking questions, (3) context and interaction questions, (4) generation strategy questions, and (5) personalization and accessibility questions. Each type is described using a short definition, when and why it is used in teaching, a simple primary-school example, and a reference to research or curriculum sources. :contentReference[oaicite:1]{index=1}  

This structure is useful for both human teachers and Gen AI systems. It connects concrete classroom practices (such as CBSE/NCERT outcomes or PISA-style items) with technical ideas in neural QG, such as difficulty control, multi-hop reasoning, and adaptive testing. :contentReference[oaicite:2]{index=2}  

---

## 2. Format-Based Question Types

Format-based questions are defined mainly by how the learner answers.

- **Multiple-choice questions (MCQ)** present fixed options with one best answer. They are common in quick checks, unit tests, and large-scale assessments.  
- **Cloze questions** are fill-in-the-blank items used for vocabulary, grammar, and factual recall.  
- **Questionnaires or short quizzes** collect information about attitudes, habits, or reading behaviours using yes/no or frequency responses.  
- **Open-ended questions** ask for free-form responses, such as explanations or short stories.  
- **Subjective questions** invite personal opinions, reflections, and preferences, and are useful in journals and reflective tasks. :contentReference[oaicite:3]{index=3}  

For neural QG systems, each format creates a different technical requirement. MCQs need one correct option and good distractors. Cloze questions need a masked word or phrase. Open-ended and subjective questions require more flexible natural language generation. In primary education, teachers often mix several formats in the same worksheet to balance speed, coverage, and depth.

---

## 3. Higher-Order Thinking Question Types

Higher-order question types focus on reasoning, explanation, and conceptual understanding.

- **Bloom’s-based questions** are aligned with levels such as remember, understand, apply, analyse, evaluate, and create.
- **Competency questions** are linked directly to curriculum outcomes (for example, CBSE or NCERT learning outcomes).
- **Critical-thinking questions** ask learners to examine reasons and evidence, often in social science or EVS contexts.
- **Cause-and-effect questions** help students see how one action or event leads to another, especially in science.
- **Socratic questions** probe assumptions and reasoning in a structured, dialogue-based way.
- **Inference-making questions** require learners to “read between the lines”.
- **Deep questions** look for underlying principles or structures.
- **Multi-hop questions** require combining information from more than one sentence or part of a text. :contentReference[oaicite:4]{index=4}  

For Gen AI, these types motivate methods that go beyond surface patterns. They require multi-step reasoning, stronger semantic representations, and better alignment between model outputs and cognitive frameworks such as Bloom’s taxonomy.

---

## 4. Context and Interaction Question Types

Context and interaction types depend strongly on previous turns, documents, or local passages.

- **Follow-up questions** build directly on a learner’s earlier response in a discussion or tutoring session.
- **Clarifying questions** remove ambiguity in the learner’s request or in the content (for example, “area” vs “perimeter”).
- **Conversational questions** appear in multi-turn teacher–pupil or human–AI dialogues and adapt to the learner’s explanation.
- **Long or multi-source questions** require synthesis across multiple texts or documents.
- **Contextual and factoid questions** are short, fact-based questions closely tied to a particular passage.
- **Paragraph-level QG** targets the main idea of an entire passage.
- **Sentence-level QG** focuses on individual sentences, often for grammar or vocabulary practice. :contentReference[oaicite:5]{index=5}  

For neural QG, these types correspond to different input scopes (sentence, paragraph, multiple documents) and different context windows in conversational systems. They are especially important for building reading comprehension tools and interactive tutors that can adapt within a dialogue.

---

## 5. Generation Strategy Question Types

Generation strategy types describe how questions are constructed and controlled.

- **Adversarial QG** produces intentionally tricky items to test robustness and prepare learners for difficult exams.
- **Answer-aware QG** starts from a known answer and generates a matching question.
- **Difficulty-controlled QG** adjusts question difficulty for different levels of learners.
- **Joint narrative and difficulty control** keeps questions consistent with a story while changing their difficulty.
- **Difficult math and hard questions** provide stretch tasks for enrichment or gifted learners.
- **Adaptive questions (CAT)** adjust in real time to the learner’s performance.
- **Controllable QG** allows teachers or systems to steer style, topic, and difficulty.
- **Diverse and scalable QG** seek to generate many non-repetitive items for large item banks.
- **Topic/concept-driven, agenda-driven, intent-aware, answer-agnostic, and similar-question generation** support curriculum mapping, lesson planning, goal clarification, open inquiry, and paraphrased variants for spaced practice. :contentReference[oaicite:6]{index=6}  

These types are central for Gen AI applications where an educational agent must generate many questions, adapt to different students, and still remain aligned with teacher goals and curriculum constraints.

---

## 6. Personalization and Accessibility Question Types

The final group focuses on learner modelling, emotions, and ethics.

- **Questions that detect user intentions** help the system choose the next best action (for example, giving a hint vs. giving a full solution).
- **Personalized QG** adapts questions to the learner’s profile, level, and interests (for example, sports-themed word problems).
- **Emotional QG** supports social and emotional learning by helping children name and reflect on their feelings.
- **Ethical profile-building questions** encourage discussion of fairness, honesty, and appropriate behaviour in everyday classroom situations.   


## Summary of Question Types
---
<table>
  <tr>
    <th>SN</th>
    <th>Type</th>
    <th>Application</th>
    <th>Example</th>
    <th>Reference</th>
  </tr>

  <!-- Format-Based Questions -->
  <tr><td>1</td><td>MCQ</td><td>Quick checks and tests</td><td>Which shape has 3 sides?</td><td>QGSurvey24</td></tr>
  <tr><td>2</td><td>Cloze</td><td>Fill-in-the-blank vocabulary</td><td>The sun rises in the ____.</td><td>ClozeEd25</td></tr>
  <tr><td>3</td><td>Questionnaire</td><td>Habits and attitudes</td><td>I read 15 min daily: Yes/No</td><td>PISA2018</td></tr>
  <tr><td>4</td><td>Open-ended</td><td>Creative expression</td><td>Why do plants need water?</td><td>PISA2018</td></tr>
  <tr><td>5</td><td>Subjective</td><td>Personal reflection</td><td>What did you like today?</td><td>PISA2018</td></tr>

  <!-- Higher-Order Thinking -->
  <tr><td>6</td><td>Bloom Level</td><td>Teach higher reasoning</td><td>Analyze: How is a square like a rectangle?</td><td>Bloom2001</td></tr>
  <tr><td>7</td><td>Competency</td><td>Check curriculum outcomes</td><td>Measure the pencil in cm.</td><td>NCERT-LO</td></tr>
  <tr><td>8</td><td>Critical Thinking</td><td>Evaluate evidence</td><td>Is recycling always good?</td><td>CT Guide</td></tr>
  <tr><td>9</td><td>Cause & Effect</td><td>Science process understanding</td><td>What happens when light moves closer?</td><td>PISA2018</td></tr>
  <tr><td>10</td><td>Socratic</td><td>Probe logic and assumptions</td><td>What evidence shows the hero is kind?</td><td>Socratic Guide</td></tr>
  <tr><td>11</td><td>Inference</td><td>Reading comprehension</td><td>How is the boy feeling?</td><td>PISA Reading</td></tr>
  <tr><td>12</td><td>Deep Question</td><td>Conceptual understanding</td><td>Why is zero not a counting number?</td><td>QGSurvey24</td></tr>
  <tr><td>13</td><td>Multi-hop</td><td>Combine multiple facts</td><td>Which animal eats plants and fish?</td><td>HotpotQA</td></tr>

  <!-- Context and Interaction -->
  <tr><td>14</td><td>Follow-up</td><td>Use previous learner answer</td><td>You said mammals breathe air. How do whales do that?</td><td>ConvQA Survey</td></tr>
  <tr><td>15</td><td>Clarifying</td><td>Resolve ambiguity</td><td>Do you mean area or perimeter?</td><td>Clarify23</td></tr>
  <tr><td>16</td><td>Conversational</td><td>Interactive dialogue</td><td>Tell me your method. What is next?</td><td>ConvSearch25</td></tr>
  <tr><td>17</td><td>Multi-source</td><td>Synthesize from multiple texts</td><td>List 3 ways to save water.</td><td>QASPER</td></tr>
  <tr><td>18</td><td>Factoid</td><td>Short factual checks</td><td>What is the capital in the passage?</td><td>SQuAD</td></tr>
  <tr><td>19</td><td>Paragraph QG</td><td>Covers entire passage</td><td>What is the main problem?</td><td>QGSurvey24</td></tr>
  <tr><td>20</td><td>Sentence QG</td><td>Grammar and vocabulary</td><td>Who built the nest?</td><td>QGSurvey24</td></tr>

  <!-- Generation Strategy -->
  <tr><td>21</td><td>Adversarial</td><td>High difficulty</td><td>Which shape has equal sides but not equal angles?</td><td>AdvQA</td></tr>
  <tr><td>22</td><td>Answer-aware</td><td>Generate from answer</td><td>Given "evaporation", ask: Which process turns water to vapor?</td><td>QGSurvey24</td></tr>
  <tr><td>23</td><td>Difficulty-controlled</td><td>Easy/medium/hard control</td><td>7 x 3 = ? / 21 / 3 = ?</td><td>DiffQG</td></tr>
  <tr><td>24</td><td>Narrative + Difficulty</td><td>Story-based graded items</td><td>Compare two morals in the story.</td><td>CTLGen</td></tr>
  <tr><td>25</td><td>Difficult Math</td><td>Enrichment</td><td>How many rectangles in 3 x 3 grid?</td><td>PISA2018</td></tr>
  <tr><td>26</td><td>Hard Question</td><td>Gifted level</td><td>Make 100 using 3, 5, 7 with + and x.</td><td>PISA2018</td></tr>
  <tr><td>27</td><td>Adaptive (CAT)</td><td>Personalized difficulty</td><td>Next question gets harder after correct answer.</td><td>CAT Overview</td></tr>
  <tr><td>28</td><td>Controllable QG</td><td>Control style and topic</td><td>Generate Grade 3 EVS "why" questions.</td><td>CTLGen</td></tr>
  <tr><td>29</td><td>Diverse QG</td><td>Avoid repetition</td><td>Produce why/how/compare versions.</td><td>QGSurvey24</td></tr>
  <tr><td>30</td><td>Scalable QG</td><td>Large question banks</td><td>Generate 100 questions for 10 stories.</td><td>QGSurvey24</td></tr>
  <tr><td>31</td><td>Topic-driven</td><td>Concept mastery</td><td>Fractions: What is half of 10?</td><td>NCERT-LO</td></tr>
  <tr><td>32</td><td>Agenda-driven</td><td>Lesson planning</td><td>Today we practice measurement.</td><td>ConvSearch</td></tr>
  <tr><td>33</td><td>Intent-aware</td><td>Detect learner goal</td><td>Do you want a hint or solution?</td><td>Clarify23</td></tr>
  <tr><td>34</td><td>Answer-agnostic</td><td>Exploratory questioning</td><td>What questions can we ask about rain?</td><td>QGSurvey24</td></tr>
  <tr><td>35</td><td>Similar Question</td><td>Spaced repetition</td><td>Find perimeter of 4 x 3 rectangle.</td><td>QGSurvey24</td></tr>

  <!-- Personalization -->
  <tr><td>36</td><td>User Intent Detection</td><td>Choose next best step</td><td>Are you checking homework or learning?</td><td>ConvSearch</td></tr>
  <tr><td>37</td><td>Personalized QG</td><td>Adapt to interests</td><td>Cricket problem: Player scores 12 then 8.</td><td>Personalized-LLM25</td></tr>
  <tr><td>38</td><td>Emotional QG</td><td>Social-emotional learning</td><td>How do you feel when a friend shares toys?</td><td>CASEL</td></tr>
  <tr><td>39</td><td>Ethical QG</td><td>Values and ethics</td><td>Is it fair to skip turns?</td><td>NAEYC</td></tr>

</table>



## 7. Conclusion

The taxonomy presented in the document offers a structured view of question types for primary education and neural question generation. It links concrete classroom examples with research datasets and frameworks, and it spans simple formats, higher-order reasoning, conversational context, advanced generation strategies, and personalization.

For educators, this list can act as a design checklist when creating worksheets, lesson plans, and assessments. For Gen AI and NLP researchers, it provides a practical, education-focused perspective on what kinds of questions a neural QG system should be able to generate, control, and evaluate in real learning environments.




