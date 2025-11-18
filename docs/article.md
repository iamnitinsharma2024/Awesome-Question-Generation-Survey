# Question Types for Primary Education and Neural Question Generation

## 1. Introduction

Question generation is a key activity in both classroom teaching and AI-based learning systems. A clear list of question types helps teachers plan worksheets, tests, and discussions. It also gives a practical framework for researchers who design neural question generation (QG) models for education.

The document behind this article organises question types into five broad groups: (1) format-based questions, (2) higher-order thinking questions, (3) context and interaction questions, (4) generation strategy questions, and (5) personalization and accessibility questions. Each type is described using a short definition, when and why it is used in teaching, a simple primary-school example, and a reference to research or curriculum sources. 

This structure is useful for both human teachers and Gen AI systems. It connects concrete classroom practices (such as CBSE/NCERT outcomes or PISA-style items) with technical ideas in neural QG, such as difficulty control, multi-hop reasoning, and adaptive testing.  

---

## 2. Format-Based Question Types

Format-based questions are defined mainly by how the learner answers.

- **Multiple-choice questions (MCQ)** present fixed options with one best answer. They are common in quick checks, unit tests, and large-scale assessments.  
- **Cloze questions** are fill-in-the-blank items used for vocabulary, grammar, and factual recall.  
- **Questionnaires or short quizzes** collect information about attitudes, habits, or reading behaviours using yes/no or frequency responses.  
- **Open-ended questions** ask for free-form responses, such as explanations or short stories.  
- **Subjective questions** invite personal opinions, reflections, and preferences, and are useful in journals and reflective tasks.  

For neural QG systems, each format creates a different technical requirement. MCQs need one correct option and good distractors. Cloze questions need a masked word or phrase. Open-ended and subjective questions require more flexible natural language generation. In primary education, teachers often mix several formats in the same worksheet to balance speed, coverage, and depth.

### Table . Answer-Format Based Question Types
| SN | Question Type | Application | Example |
|----|---------------|-------------|---------|
| 1 | MCQ | Quick checks | Which shape has 3 sides? |
| 2 | Cloze | Vocabulary & recall | The sun rises in the _____. |
| 3 | Questionnaire | Attitudes/habits | I read 15 minutes daily: Yes/No |
| 4 | Open-Ended | Creativity | Why do plants need water? |
| 5 | Subjective | Reflection | What did you like about today’s story? |

---
## 3. Context and Interaction Question Types

Context and interaction types depend strongly on previous turns, documents, or local passages.

- **Follow-up questions** build directly on a learner’s earlier response in a discussion or tutoring session.
- **Clarifying questions** remove ambiguity in the learner’s request or in the content (for example, “area” vs “perimeter”).
- **Conversational questions** appear in multi-turn teacher–pupil or human–AI dialogues and adapt to the learner’s explanation.
- **Long or multi-source questions** require synthesis across multiple texts or documents.
- **Contextual and factoid questions** are short, fact-based questions closely tied to a particular passage.
- **Paragraph-level QG** targets the main idea of an entire passage.
- **Sentence-level QG** focuses on individual sentences, often for grammar or vocabulary practice. 

For neural QG, these types correspond to different input scopes (sentence, paragraph, multiple documents) and different context windows in conversational systems. They are especially important for building reading comprehension tools and interactive tutors that can adapt within a dialogue.
### Table . Context / Interaction Based Question Types
| Question Type | Application | Example |
|----------------|-------------|---------|
| Follow-up | Builds on learner answer | How do whales breathe? |
| Clarifying | Resolve confusion | Do you mean area or perimeter? |
| Conversational | Multi-turn tutoring | What’s your next step? |
| Multi-source | Compare sources | List 3 ways to save water. |
| Factoid | Quick recall | What is the capital mentioned? |
| Paragraph-level | Comprehension | What is the main problem? |
| Sentence-level | Grammar | Who built the nest? |

---
## 4. Higher-Order Thinking Question Types

Higher-order question types focus on reasoning, explanation, and conceptual understanding.

- **Bloom’s-based questions** are aligned with levels such as remember, understand, apply, analyse, evaluate, and create.
- **Competency questions** are linked directly to curriculum outcomes (for example, CBSE or NCERT learning outcomes).
- **Critical-thinking questions** ask learners to examine reasons and evidence, often in social science or EVS contexts.
- **Cause-and-effect questions** help students see how one action or event leads to another, especially in science.
- **Socratic questions** probe assumptions and reasoning in a structured, dialogue-based way.
- **Inference-making questions** require learners to “read between the lines”.
- **Deep questions** look for underlying principles or structures.
- **Multi-hop questions** require combining information from more than one sentence or part of a text.   

For Gen AI, these types motivate methods that go beyond surface patterns. They require multi-step reasoning, stronger semantic representations, and better alignment between model outputs and cognitive frameworks such as Bloom’s taxonomy.
### Table . Higher-Order Thinking Question Types
| Type | Application | Example |
|-------|-------------|---------|
| Bloom’s | Cognitive depth | How is a square like a rectangle? |
| Competency | Standards-aligned | Measure a pencil. |
| Critical Thinking | Judgement | Is recycling always good? |
| Cause–Effect | Science reasoning | What happens to a shadow? |
| Socratic | Probe assumptions | What proves the hero is kind? |
| Inference | Hidden meaning | How is the boy feeling? |
| Deep | Concepts | Why is zero special? |
| Multi-hop | Two facts | Which animal eats plants & fish? |

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
- **Topic/concept-driven, agenda-driven, intent-aware, answer-agnostic, and similar-question generation** support curriculum mapping, lesson planning, goal clarification, open inquiry, and paraphrased variants for spaced practice.   

These types are central for Gen AI applications where an educational agent must generate many questions, adapt to different students, and still remain aligned with teacher goals and curriculum constraints.
### Table 4. Controlled Generation Strategy Types
| Type | Application | Example |
|--------|-------------|---------|
| Adversarial | Robustness | Which shape has equal sides but not angles? |
| Answer-aware | Generate from answer | What turns water into vapor? |
| Difficulty-control | Differentiation | Level Easy vs Hard questions |
| Narrative-control | Story tasks | Compare morals of a fable |
| Difficult Math | Enrichment | Rectangles in 3×3 grid |
| Adaptive | Personalized | Harder question after correct answer |
| Controllable | Teacher-steered | Generate Grade-3 EVS “why” questions |
| Diverse | Avoid repetition | Multiple stems for same text |
| Scalable | Mass generation | 100 questions for 10 passages |
| Topic-driven | Concept mastery | Fractions sequence |
| Agenda-driven | Lesson plan | Measurement: units → tools |
| Intent-aware | Learner goal | Do you want a hint or example? |
| Answer-agnostic | Inquiry | What questions about rainfall? |
| Similar QG | Paraphrases | Perimeter of 4×3 rectangle |

---

## 6. Personalization and Accessibility Question Types

The final group focuses on learner modelling, emotions, and ethics.

- **Questions that detect user intentions** help the system choose the next best action (for example, giving a hint vs. giving a full solution).
- **Personalized QG** adapts questions to the learner’s profile, level, and interests (for example, sports-themed word problems).
- **Emotional QG** supports social and emotional learning by helping children name and reflect on their feelings.
- **Ethical profile-building questions** encourage discussion of fairness, honesty, and appropriate behaviour in everyday classroom situations.   
### Table 5. Personalization & Accessibility Types
| Type | Application | Example |
|--------|-------------|---------|
| Detect Intent | Learning guidance | Checking homework or learning? |
| Personalized | Interest-based | Cricket math problem |
| Emotional | SEL | How do you feel when sharing? |
| Ethical | Morality | Is skipping turns fair? |




## 7. Conclusion

The taxonomy presented in the document offers a structured view of question types for primary education and neural question generation. It links concrete classroom examples with research datasets and frameworks, and it spans simple formats, higher-order reasoning, conversational context, advanced generation strategies, and personalization.

For educators, this list can act as a design checklist when creating worksheets, lesson plans, and assessments. For Gen AI and NLP researchers, it provides a practical, education-focused perspective on what kinds of questions a neural QG system should be able to generate, control, and evaluate in real learning environments.




