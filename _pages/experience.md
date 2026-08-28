---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---

## Graduate Research Assistant, William & Mary, USA (Sep 2022 - Present)

* <ins>Automated Refactoring quality evaluator</ins> (May 2026 - present)
    * Designing a multi-agent pipeline to evaluate LLM-generated code refactorings for semantic correctness and readability, integrating relative-comprehensibility models with differential testing and formal verification (in progress).
    

* <ins>Relative Code Comprehensibility Prediction</ins> (March 2023 - Aug 2026)
    
    * Introduced a relative-comprehensibility (RC) measurement framework that improved prediction accuracy by 150%
    over a naive baseline and produced a 4.4× larger gain than state-of-the-art comprehensibility prediction models; evaluated across 10M+ datapoints using an 8-model ML pipeline (Random Forest, SVM, XGBoost, etc.) and two LLMs (GPT-5.4, Qwen-2.5) — a scale comparable to production recommendation/ranking system evaluation. Conducted a user study with developers (Qualtrics) to collect data and validate the usefulness of RC models (submitted to TOSEM).

    * Designed and executed a controlled experiment (A/B Style 1,228 control and 935 treatment classifiers across 6 model families and multiple comprehensibility metrics) showing formal-verifier warning counts do not improve comprehensibility prediction; applied Mann–Whitney U (95% CI), Kendall’s τ , mutual information, and SHAP analyses to validate results (EASE’26).

    * Technologies & tools: Scikit-learn, Pytorch, HuggingFace transformers, Tensorflow, SciKeras, Java, Python, Gradle, Pandas, Numpy, Matplotlib, Git, Latex

* <ins> Automated Program Repair</ins> (Dec 2024 - Aug 2026)
    * Replicated RewardRepair, an NLP transformer-based model for program repair, across 960 generated patches for 96 UI-centric Android bugs (46 synthetic, 50 real); measured a 3.4% plausible patch rate and 0% correct patches for real bugs, demonstrating that repair techniques without UI-specific fine-tuning perform poorly on GUI-related issues (ISSTA’26)

    * Technologies & tools: Pytorch, HuggingFace transformers, Python, Android, Git
    
    
* <ins>Bug Localization</ins> (Sep 2022 - Feb 2023)
    * Conducted an empirical study to investigate the effectiveness of using GUI interaction data to improve text retrieval-based bug localization.
    * Constructed a dataset consists of 80 real-world android ui bug reports with their corresponding bug-fixing commits and GUI interaction data.
    * Our results illustrate that augmenting traditional techniques (eg, BugLocator, UnixCoder...) with GUI information leads to a relative increase in Hits@10 of 13-18%.
    * Work is accepted at International Conference of Software Engineering 2024 in the research track.
    * Technologies: Java, Python, Git, Latex

* <ins>Bug Report Chatbot</ins> (Sep 2022 - Feb 2023)
    * Introduced a web-based chatbot for interactive reporting of Android app bugs. 
    * It guides the users in reporting essential bug report elements, i.e., the observed behavior, expected behavior, and the steps to reproduce the bug. It verifies the quality of the text written by the user and provides instant feedback. 
    * In addition, it provides graphical suggestions that the users can choose as alternatives to textual descriptions.
    * Work is accepted at International Conference of Software Engineering 2023 in the tool demo track.
    * Technologies & tools: Android, Java, Python, React, Git, Latex

---

## Graduate Teaching Assistant, William & Mary, USA (Sep 2022 - May 2024)
Perform duties including grading assignments, exam proctoring as a teaching assistant for the following courses.
* Algorithms – Spring 2024
* Computer Organization – Fall 2023
* Data Structures – Spring 2023
* Data Structures – Fall 2022

---

## Senior Software Engineer, Enactor Ltd. (Colombo, Sri Lanka | HQ: Hertfordshire, UK) (February 2020 - July 2022)

I worked under several teams at Enactor Ltd.

* <ins>Senior Software Engineer</ins> at Deployment and Scalability team.
    * docker-based developments and enhancements
    * Improving deployment environments with the usage of AWS Web Services

* <ins>Senior Software Engineer</ins> at ‘Frasers’ a customer project.
    * Implemented a new customer feature called ‘ShoeWall’ for SportsDirect UK
    * fix platform/customer issues, implement tech specs, code reviewing, contribute to designing solutions, technical specification writing, and provide advice and guidance to newcomers and team members

* <ins>Software Engineer</ins> at Core Platform Team
    * Automation framework developments and enhancements
    * fixing platform bugs, and improved code quality and efficiency

    Technologies & tools : Java, Docker, AWS, Jenkins, Jira, Confluence, Maven, Junit, React

---
## Google Summer of Code Intern (Open-Source Project), The Apache Software Foundation, Remote (May 2019 - August 2019)
 * Designed and implemented modularized, reusable React components and Improved JAX-RS-REST APIs for Apache OODT 2.0. [project](https://summerofcode.withgoogle.com/archive/2019/projects/5432463780741120)
 * Technologies & tools: Java, React, Apache OODT, Git, Jira, Confluence, Maven, Junit

---

## Software Engineering Intern, WSO2 Inc. (Colombo, Sri Lanka) (June 2018 - Dec 2018) 
  * Developed a prototype for a Healthcare Data manipulation that supports global HL7/FHIR standards. 
  * published a white paper in InfoQ. [paper](https://www.infoq.com/articles/patient-care-stream-processing/)
  * Technologies & tools: Kafka/Zookeeper mechanism, stream processing-based data processing  