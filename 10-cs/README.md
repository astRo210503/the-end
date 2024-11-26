# Syllabus

| **Unit No.** | **Topic** | **Actual Teaching Hours** | **Contact Hours Equivalence** |
|--------------|-----------|---------------------------|--------------------------------|
| **1** | Introduction to Cognitive Systems: Basics, introduction to computational theories of human cognition, drawing on formal models from classic and contemporary artificial intelligence approaches to cognition, philosophy of cognition, fundamental issues in human knowledge representation, inductive learning and reasoning, forms of knowledge, the inductive principles, computation of cognitive functioning in machines, Human-robotics interaction, difference between AI and Cognitive systems, Computational intelligence techniques, cognitive linguistics. | 15 | 15 |
| **2** | Cognitive science: Concept Learning and Categorization, Reasoning about Natural Kinds, Learning Causal Relations, The Structure and Formation of Intuitive Theories of Physical, Biological, and Social Systems, The Acquisition of Natural Language (syntax and semantics), Theory of Mind: How we Understand the Behavior and Mental States of Other People. | 12 | 12 |
| **3** | Formal modeling: Bayesian Inference and Hierarchical Bayesian Models, Frameworks for Knowledge Representation: First-order Logic, Formal Grammars, Associative Networks, Taxonomic Hierarchies, Relational Schemas, Probabilistic and Causal Graphical Models, Relational Probabilistic Models, Controlling Complexity: Minimum Description Length, Bayesian Occam's Razor, Nonparametric Bayesian Models, Inductive Logic Programming, Sampling Algorithms for Inference in Complex Probabilistic Models. | 10 | 10 |
| **4** | Applications: Speech recognition, sentiment analysis, face detection, risk assessment, and fraud detection. | 8 | 8 |
| **Total** | - | **45** | **45** |
 

# recordings 
https://drive.google.com/drive/folders/1V9Pc8n8QSK7Hd7TNiCHlvvK4IlFyBjpk



# Unit 1- 
## Links

https://chat.mistral.ai/chat/43d0d667-bcae-4b82-99ea-5d8b5473e1f6

https://notebooklm.google.com/notebook/c3bc573f-e626-4985-a58e-b25e6965315f?original_referer=https:%2F%2Fnotebooklm.google%23&pli=1&authuser=1

https://chatgpt.com/share/673f8743-166c-800f-9fd4-396022fc5229

## Notes

![enter image description here](https://assets.channelinsider.com/uploads/2021/07/CI.CognitiveSystemRelationships-768x453.png)

![enter image description here](https://miro.medium.com/v2/resize:fit:828/format:webp/0*b2wXGd6AHcx0yDx9.png)

## GPT

Here’s a deeper breakdown of the key concepts, structured to aid exam preparation and ensure understanding of the subject:

----------

### **Unit 1: Introduction to Cognitive Systems**

#### **1.1 Basics of Cognitive Systems**

-   **Definition**: Systems designed to mimic human cognitive processes such as learning, reasoning, perception, and problem-solving.
-   **Purpose**:
    -   Augment human capabilities.
    -   Provide insights for decision-making rather than automating it completely.
-   **Applications**:
    -   Personalized healthcare recommendations.
    -   Enhanced educational tools.
    -   Intelligent assistants like IBM Watson.

#### **1.2 Computational Theories of Cognition**

-   Draws from:
    -   **Classic AI Approaches**: Rule-based systems, symbolic logic.
    -   **Contemporary AI Approaches**: Machine learning, neural networks, probabilistic models.
-   **Philosophy of Cognition**: Questions the nature of intelligence, consciousness, and reasoning in machines.
-   **Human Knowledge Representation**: Fundamental to understanding how knowledge is structured and applied.

#### **1.3 Key Differences: AI vs. Cognitive Systems**

**Aspect**

**Artificial Intelligence**

**Cognitive Systems**

**Goal**

Automation

Augmentation

**Focus**

Independent problem-solving

Contextual, human-like reasoning

**Technology**

Algorithms, neural networks

Human-computer interaction, reasoning

**Example**

Self-driving cars

Decision support in critical scenarios

----------

### **Knowledge Representation (KR)**

#### **2.1 Purpose of KR**

-   Represent knowledge in a format that AI systems can:
    -   Understand.
    -   Infer from (e.g., medical diagnosis).
    -   Adapt to new information.

#### **2.2 Types of Knowledge**

1.  **Declarative Knowledge**:
    -   Descriptive facts (e.g., "The sky is blue").
    -   Stored as propositions or sentences.
2.  **Procedural Knowledge**:
    -   Steps or processes for tasks (e.g., "How to bake a cake").
    -   Includes rules and strategies.
3.  **Meta-Knowledge**:
    -   Knowledge about other knowledge (e.g., "Knowing how to learn").
4.  **Heuristic Knowledge**:
    -   Rules of thumb based on experience (e.g., "If it rains, roads may be slippery").
5.  **Structural Knowledge**:
    -   Describes relationships (e.g., "Dogs are mammals").

#### **2.3 Techniques of KR**

1.  **Logical Representation**:
    
    -   Propositional logic (statements connected by "AND," "OR").
    -   Predicate logic (includes variables, relationships, quantifiers like ∀, ∃).
    -   **Pros**: Precise, supports deductive reasoning.
    -   **Cons**: Inflexible, not intuitive.
2.  **Semantic Networks**:
    
    -   Graphical representation with nodes (objects) and edges (relationships).
    -   **Example**:
        -   Jerry → is-a → Cat
        -   Cat → is-a → Mammal
        -   Mammal → is-a → Animal
    -   **Advantages**:
        -   Intuitive, extendable.
    -   **Disadvantages**:
        -   Computationally expensive, lacks quantifiers.
3.  **Frame Representation**:
    
    -   Data structures with attributes (slots) and values (facets).
    -   **Example**: A frame for “Car” may have slots like color, brand, speed.
    -   **Advantages**:
        -   Easy to extend, modular.
    -   **Disadvantages**:
        -   Generalized, inference is challenging.
4.  **Production Rules**:
    
    -   Condition-action pairs (e.g., IF rain THEN carry an umbrella).
    -   **Advantages**:
        -   Modular, easy to modify.
    -   **Disadvantages**:
        -   No learning capability, inefficient during runtime.

----------

### **Modeling Intelligence**

#### **3.1 Understanding the Mind and Brain**

-   **Key Questions**:
    -   How can the brain be modeled as a computational entity?
    -   What mechanisms underlie intelligent behavior?
-   **Models**:
    -   **Pattern Recognition**: Deep neural networks, CNNs, RNNs.
    -   **Prediction Models**: Bayesian networks, predictive coding.
    -   **Symbolic Manipulation**: Logic-based inference.

#### **3.2 Challenges in Combining Models**

-   Integrating sensory input with higher-order reasoning.
-   Balancing top-down (feedback) and bottom-up (data-driven) processes.

----------

### **AI Knowledge Cycle**

1.  **Data Collection**: Gathering information from sensors, databases, or user inputs.
2.  **Preprocessing**: Cleaning and formatting data.
3.  **Representation**: Encoding knowledge into usable formats (e.g., graphs, vectors).
4.  **Inference**: Making predictions or decisions based on data.
5.  **Evaluation**: Testing the system’s performance.
6.  **Refinement**: Improving the system based on feedback.

#### **Common Challenges**:

-   **Scalability**: Handling large, complex datasets.
-   **Uncertainty**: Reasoning with incomplete or ambiguous information.
-   **Integration**: Combining diverse data sources seamlessly.
-   **Explainability**: Making decisions interpretable and transparent.

----------

### **Cognitive Computing and Human Interaction**

#### **4.1 Human-Computer Interaction (HCI)**

-   Optimizes how users interact with systems.
-   Examples: Touchscreens, voice assistants.

#### **4.2 Brain-Computer Interface (BCI)**

-   Directly connects brain activity with external devices.
-   Applications: Prosthetics, restoring sensory functions.

#### **4.3 Human-Robot Interaction (HRI)**

-   Collaborative systems that integrate AI, robotics, and psychology.
-   Examples: Autonomous cars, social robots.

----------

### **Potential Exam Questions**

#### **Short Answer**:

1.  Define cognitive systems and their goals.
2.  Explain the role of procedural knowledge in AI.
3.  What are the advantages and disadvantages of semantic networks?

#### **Essay**:

1.  Compare and contrast logical representation and frame representation in KR.
2.  Discuss the AI knowledge cycle and its challenges.
3.  How do cognitive systems augment human decision-making?

#### **Application-Based**:

1.  Design a simple semantic network for a knowledge base about animals.
2.  Provide examples of cognitive computing in real-world applications.

By studying these detailed notes and understanding the implications of each concept, you can confidently approach the exam and tackle theoretical and application-based questions.

## Mistral 

# Deep Notes on Cognitive Systems Lecture

## Key Concepts and Arguments

### Cognitive Systems Relationships
- **Cognitive Computing:** Uses theories and models of the human mind to mimic the mind on computer systems.
- **Computational Cognitive Modeling:** Understanding the human mind and brain in terms of their underlying computational processes. Building computer simulations that mimic human intelligent behavior.

### Key Questions
1. What is intelligence?
2. What kind of computer is the mind and brain?
3. Can we better understand the mind/brain by building computational cognitive models?
4. Can we better understand behavioral data by building computational cognitive models?
5. Can we improve machine intelligence by incorporating insights from human intelligence?

### Cognitive Computing vs. Artificial Intelligence
- **Cognitive Computing:** Part of AI, informed decisions, extracts information for decision-making, humans make the final decision.
- **Artificial Intelligence:** Broader concept, problem-solving tasks, suggests the best way to solve the problem, makes better decisions on behalf of humans.

### Features of Cognitive Systems
- Mimics human behavior
- Simulates human behavior
- Dynamic learning without human intervention

### Connections between Computational Cognitive Modeling and Data Science
- Similar goals: build computational models to explain or predict behavioral data.
- Similar computational paradigms and techniques: neural networks, deep learning, reinforcement learning, Bayesian modeling, probabilistic graphical models, program induction.
- Data science is about extracting knowledge from data. The human mind is the best system for extracting knowledge from data.

### Computational Models of Cognition
- **Brain + Minds + Machines:** What kind of computer is the brain/mind? How can we characterize intelligence in computational terms?
- **Pattern Recognition Engine:** AI side, neuroscience-based, CNN/RNN and variants.
- **Prediction Engine:** Bayesian networks, causal models, predictive coding, causal reasoning, causal inference.
- **Symbol Processing/Manipulation Engine:** Logic, calculus, symbolic expressions.

### Knowledge Representation
- **Goal:** Facilitate inference from knowledge.
- **Types of Knowledge:**
  1. **Declarative Knowledge:** Knowing about something, concepts, facts, objects.
  2. **Procedural Knowledge:** Knowing how to do something, rules, strategies, procedures.
  3. **Meta-knowledge:** Knowledge about other types of knowledge.
  4. **Heuristic Knowledge:** Rules of thumb based on previous experiences.
  5. **Structural Knowledge:** Basic knowledge to problem-solving, describes relationships between concepts.

### Techniques of Knowledge Representation
1. **Logical Representation:** Propositional and predicate logics.
2. **Semantic Network Representation:** Graphical networks with nodes and arcs.
3. **Frame Representation:** Record-like structure with attributes and values.
4. **Production Rules:** (Condition, action) pairs.

### AI Knowledge Cycle
- **Stages:** Data collection, data preprocessing, knowledge representation, knowledge inference, knowledge evaluation, knowledge refinement, knowledge utilization.
- **Continuous Process:** AI systems learn and adapt based on new information.

### Problem with Knowledge Representation
- **Scalability:** Efficiently representing and processing large knowledge bases.
- **Uncertain or Incomplete Information:** Handling uncertainty and reasoning with inadequate data.
- **Knowledge Fusion and Integration:** Combining knowledge from various sources.
- **Explainability & Interpretability:** Providing clear explanations for AI decisions.

### Difference between AI and Cognitive Systems
- **AI:** Automation, focuses on finding effective algorithms to generate the best solution.
- **Cognitive Computing:** Augmentation, focuses on making the best decision based on circumstances and providing information for the best decision.

### Various Tasks under Cognitive Computing
- **Affective Computing:** Applications in marketing, customer service, human resources, healthcare, insurance, retail, driving assistance, education, gaming, government, technology.
- **Human-Computer Interaction (HCI):** Optimizing user-computer interactions.
- **Brain-Computer Interface (BCI):** Direct communication link between the brain's electrical activity and an external device.
- **Human-Robot Interaction (HRI):** Study of interactions between humans and robots.

## Potential Exam Questions
1. **Compare Cognitive Computing with AI.**
2. **What are the features of cognitive systems?**
3. **Explain the AI knowledge cycle and its components.**
4. **What are the different types of knowledge in AI systems?**
5. **Describe the techniques of knowledge representation in AI.**
6. **What are the key questions in computational cognitive modeling?**
7. **How does cognitive computing differ from artificial intelligence?**
8. **What are the requirements for a good knowledge representation system?**
9. **Explain the connections between computational cognitive modeling and data science.**
10. **What are the problems with knowledge representation in AI?**

These notes cover the key points and arguments presented in the lecture, highlighting the most important concepts and their implications. They also include potential exam questions that may be covered based on the lecture content.


# Question Bank

## Question Bank: Cognitive Systems

### 1. What are cognitive systems, and how do they differ from traditional artificial intelligence systems?

Cognitive systems are a superset of artificial intelligence (AI). **Cognitive computing aims to create systems that can mimic human-like cognitive functions.** This includes processes related to perception, learning, reasoning, and problem-solving. The goal of cognitive computing is to develop systems that can understand, interpret, and respond to complex information similar to how humans do.

While both cognitive computing and AI use technologies like machine learning, neural networks, and deep learning, they differ in their applications and goals. **The purpose of AI is to make decisions independently, whereas cognitive computing focuses on simulating human reasoning.** AI focuses on finding effective algorithms to generate the best solution to a problem, while cognitive computing aims to make the best decision based on circumstances and provide information for the best decision.

### 2. Compare and contrast symbolic AI with connectionist approaches in modeling human cognition.

The sources provided do not make a distinction between symbolic AI and connectionist approaches to modeling human cognition. However, the source does discuss different computational models of cognition that can be considered analogous:

-   **Pattern recognition engine:** Modeled on the AI side using neuroscience-based CNN/RNN and deep neural networks.
-   **Prediction Engine:** Utilizing Bayesian networks, causal models, predictive coding, and causal reasoning/inference.
-   **Symbol Processing/Manipulation Engine:** Based on logic, calculus, and symbolic expressions.

### 3. How do cognitive architectures like SOAR and ACT-R contribute to our understanding of human cognition?

The provided sources do not contain information about SOAR and ACT-R and their contributions to our understanding of human cognition.

### 4. Discuss the mind-body problem and its implications for developing cognitive systems.

The sources provided do not contain information about the mind-body problem and its implications for the development of cognitive systems.

### 5. What is the significance of representationalism in cognitive science, and how does it influence the design of cognitive systems?

The sources provided do not explicitly discuss representationalism in cognitive science and its influence on cognitive system design. However, the sources do highlight the importance of **knowledge representation**, which can be considered a key aspect of representationalism.

The fundamental goal of knowledge representation is to **facilitate inference from knowledge**. This involves representing information about the real world so that a computer can understand and utilize this knowledge to solve complex problems. **Knowledge representation is not simply storing data but enabling an intelligent machine to learn from knowledge and experiences to behave intelligently.**

### 6. Explain the differences between declarative and procedural knowledge. How are these types of knowledge represented in cognitive systems?

**Declarative knowledge** is knowledge "about" something, including concepts, facts, and objects. It is also called descriptive knowledge and is expressed in declarative sentences.

**Procedural knowledge** is knowledge "how" to do something. It includes rules, strategies, procedures, and agendas. Procedural knowledge is directly applicable to tasks and depends on the specific task to which it is applied.

The sources provide examples of knowledge to represent in AI systems, which can be categorized as declarative or procedural:

**Declarative:**

-   Objects: Facts about objects. For example, "cars have brakes," "dogs have two ears."
-   Events: Actions that occur.
-   Facts: Truths about the real world.

**Procedural:**

-   Performance: Knowledge about how to do things.

### 7. What are semantic networks, and how do they facilitate knowledge representation in cognitive systems?

**Semantic networks are an alternative to predicate logic for knowledge representation.** They represent knowledge as graphical networks with nodes representing objects and arcs describing the relationships between objects. Semantic networks categorize objects in different forms and link them together. They are easy to understand and can be easily extended.

The sources present the following advantages and disadvantages of semantic networks:

**Advantages:**

-   Natural representation of knowledge.
-   Convey meaning transparently.
-   Simple and easy to understand.

**Disadvantages:**

-   Computational time at runtime as the entire network tree may need to be traversed.
-   Difficult to build a vast semantic network in practice.
-   Inadequate for representing quantifiers (e.g., "for all," "for some," "none").
-   No standard definition for link names.
-   Not intelligent and dependent on the creator of the system.

### 8. Describe the process of inductive learning in cognitive systems. How does it differ from deductive reasoning?

The provided sources do not explicitly describe the process of inductive learning in cognitive systems and its distinction from deductive reasoning. However, the sources mention "**inductive learning and reasoning**" as part of the introduction to computational theories of human cognition.

### 9. What are the challenges associated with generalization in inductive learning, and how are these addressed in computational models?

The sources provided do not contain information about the challenges associated with generalization in inductive learning and how these challenges are addressed in computational models.

### 10. How is cognitive functioning computationally modeled in machines, and what are the key challenges in this area?

Computational cognitive modeling aims to understand the human mind and brain in terms of underlying computational processes. It involves building computer simulations that mimic the intelligent behavior of humans. These simulations are then used to predict and explain human behavior.

**Key challenges in computationally modeling cognitive functioning**:

-   **Scalability:** Representing and processing large knowledge bases as knowledge volume and complexity increase. This requires efficient methods and distributed computing concepts.
-   **Uncertain or Incomplete Information:** Managing uncertainty and reasoning with incomplete data is a major research area.
-   **Knowledge Fusion and Integration:** Combining knowledge from various sources and modalities is challenging. Research is focused on creating methods to seamlessly integrate heterogeneous knowledge for improved AI performance.
-   **Explainability & Interpretability:** AI systems should be able to justify their decisions. Research is focused on developing clear and understandable knowledge representation approaches to build trust, ensure ethical AI, and satisfy legal standards.


## Question Bank: Cognitive Systems Continued

### 11. What are the key considerations in designing cognitive systems for effective human-robot interaction?

The sources provide some information about Human-Robot Interaction, but they do not offer specific considerations for designing cognitive systems for this purpose. Source defines **Human-robot interaction (HRI)** as the study of interactions between humans and robots and states that it is a multidisciplinary field.

The source also mentions that cognitive computing, a superset of AI, aims to create systems capable of mimicking human-like cognitive functions. However, the connection between the design of cognitive systems and effective HRI is not explicitly addressed.

### 12. How do cognitive systems differ from traditional AI in terms of their goals and methodologies?

**Goal Differences**:

-   **Traditional AI**: Aims to create systems that can think and make decisions independently. This involves finding the most effective algorithm to generate the best overall solution to a problem.
-   **Cognitive Systems**: Focuses on simulating the human mind's reasoning processes. The goal is to make the best decision based on circumstances and provide information to support human decision-making.

**Methodological Differences**:

-   **Traditional AI**: Emphasizes automation and finding the best algorithm for a given problem.
-   **Cognitive Systems**: Emphasizes augmentation and providing insights and suggestions to aid human decision-making.

**Example**:

The sources illustrate the distinction between AI and cognitive computing through a pizza ordering scenario.

-   **AI**: Would analyze past pizza orders to create an algorithm for predicting future orders and might even automatically place the order.
-   **Cognitive Computing**: Would consider past orders and contextual factors (e.g., location, number of people) to suggest a few suitable options, leaving the final decision to the user.

### 13. What computational intelligence techniques are commonly used in cognitive systems and how do they contribute to cognitive modeling?

While the sources don't explicitly list common computational intelligence techniques used in cognitive systems, they do highlight the relevance of **computational neuroscience** to this field. Computational neuroscience uses studies of the human brain to create artificial learning systems, which can inform cognitive modeling.

The sources also provide a list of computational methods and paradigms from machine learning, AI, and data science that contribute to cognitive science and psychology:

-   Artificial neural networks
-   Temporal difference learning
-   Factor analysis
-   Multi-dimensional scaling
-   Probabilistic graphical models
-   Structured Bayesian models
-   Bayesian non-parametric models
-   Probabilistic programming
-   Recurrent neural networks

These techniques are relevant for **data science**, which aims to extract knowledge from data. The human mind excels at this task, suggesting that these techniques can be adapted and applied to cognitive modeling.

### 14. How does cognitive linguistics contribute to our understanding of language processing in cognitive systems?

The sources list **cognitive linguistics** as a relevant area for computational theories of human cognition. However, they do not elaborate on how cognitive linguistics specifically contributes to understanding language processing in cognitive systems.

### 15. How does the prototype theory of categorization differ from the classical view of concepts? Provide examples to illustrate the differences.

The sources do not provide information about the prototype theory of categorization and its differences from the classical view of concepts.

### 16. What role do exemplars play in the process of concept learning, and how does exemplar theory explain human categorization?

The sources do not provide information about the role of exemplars in concept learning or how exemplar theory explains human categorization.

### 17. What is the theory of mind, and why is it essential for understanding the behavior and mental states of others?

The sources do not provide information about the theory of mind. However, they do include a hypothetical scenario involving a crying baby and a mother. The source describes how the mother recognizes the baby's panicked state and reacts accordingly. This example could be considered relevant to the theory of mind, as it highlights the ability to understand and respond to the mental states of others.

### 18. How does the development of theory of mind in children influence their social interactions and relationships?

The sources do not explicitly discuss the development of theory of mind in children and its influence on social interactions and relationships. However, the example of the mother and crying baby suggests that the ability to understand others' mental states is crucial for effective social interaction.

### 19. How does Bayesian inference differ from traditional statistical inference, and why is it particularly useful in cognitive science?

**Bayesian Inference**:

-   **Method**: Uses Bayes' theorem to update the probability of a hypothesis as more evidence becomes available.
-   **Key Feature**: Utilizes prior knowledge, in the form of a prior distribution, to estimate posterior probabilities.

**Traditional Statistical Inference**:

-   Information on how traditional statistical inference differs from Bayesian inference is not provided in the sources.

**Usefulness in Cognitive Science**:

-   **Dynamic Analysis**: Bayesian updating is valuable for dynamically analyzing data sequences.
-   **Prediction Engine:** Bayesian networks are part of the computational models of cognition as prediction engines.

### 20. What are hierarchical Bayesian models, and how do they allow for more complex representations of cognitive processes?

The sources provide information on Bayesian inference and its applications but do not mention hierarchical Bayesian models and their role in cognitive science.

### 21. Describe relational probabilistic models and discuss how they combine relational structures with probabilistic reasoning.

Information on relational probabilistic models is not available in the sources.

### 22. What are sampling algorithms, and why are they necessary for inference in complex probabilistic models? Give an example of how one such algorithm might be used in cognitive modeling.

The sources do not offer information about sampling algorithms and their application in cognitive modeling.

### 23. What is the minimum description length principle, and how does it help control the complexity of models in cognitive science?

The sources do not define or discuss the minimum description length principle.

### 24. Explain the concept of Bayesian Occam's Razor and its application in model selection within cognitive science.

The sources provide information about Bayesian inference and its applications, including its use as a prediction engine in cognitive models. However, they do not mention Bayesian Occam's Razor or its role in model selection within cognitive science.

### 25. Describe relational probabilistic models and discuss how they combine relational structures with probabilistic reasoning.

Information on relational probabilistic models is not available in the sources.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MDUzNzg5NDddfQ==
-->