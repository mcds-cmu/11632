---
layout: f25
title: Fall Capstone Poster Session
nav_order: 7
---

<html>
 <style>
  table, tr {
    table-layout: fixed;
    width: 100%;
  }
  img {
    width: 100%;
    height: auto;
    overflow: hidden;
    position: relative;
  }
  td {
    vertical-align: top;
  }
  .center {
    display: block;
    margin-left: auto;
    margin-right: auto;
  }
  p {
    text-align: center; 
  }
  h2 {
    vertical-align: top;
    text-align: center;
    padding-top: 25px;
    padding-bottom: 25px;
  }
 </style>

<div style="text-align:center; padding: 25px; font-size: 26px; font-weight: bold; color: #7a003c; line-height: 1.4;">
  ⭐ Join us!! December 3, 2025 · GHC 4400 / 4300 · 12 pm–4 pm<br>
  Language Technologies Institute<br>
  Master of Computational Data Science<br>
  Capstone Project Showcase
</div>

<!-- TAG LEGEND
<div style="text-align:center; padding: 20px; font-size: 20px; font-weight: bold;">
  Project Tags Legend
</div>

<div style="display:flex; flex-wrap:wrap; justify-content:center; gap:12px; padding-bottom:30px;">

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Large Language Models (LLMs)
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Retrieval-Augmented Generation (RAG)
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Multi-Agent Systems
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Benchmarking & Evaluation
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Machine Learning for Science
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Computer Vision
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Natural Language Processing (NLP)
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Autonomous Agents
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Optimization & Systems
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    AI for Education
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    AI for Healthcare & Sustainability
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Data Engineering & Pipelines
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Human-AI Interaction (HAI)
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Security & Safety in AI
  </span>

  <span style="padding:6px 14px; border:1px solid #7a003c; border-radius:6px; font-size:14px;">
    Scientific Computing & Simulation
  </span>

</div> -->

 <div>
  <div>
   <table>
    <tbody>

<!-- CARD 1–3 -->
<tr style="text-align: center;">
<td>
<h2>AIDEN: AI-based Interactive TA for Educational Needs</h2>
<img src="https://cmu.box.com/shared/static/7sv1r6qfhp96hb6s9dsey08ovcihpomk.png"/>
<p>Emily Guo, Helen Wang, Ken Ye</p>
<p>
Teaching Assistants in large technical courses often struggle to keep pace with the volume and complexity
of Piazza questions. To address this challenge, we developed AIDEN, an in-browser AI assistant that
generates draft responses directly inside Piazza. We redesigned the system from a Slack-based prototype
into a fully deployed Chrome Extension backed by a secure cloud server. The updated system incorporates
course documents, starter code, and follow-up thread context through an expanded retrieval-augmented
generation pipeline, and uses proactive pre-generation to reduce response delays.
AIDEN was deployed in a live course, enabling us to collect real usage data—including TA interaction
logs, ratings, and paired model–TA answers. Analysis of this data shows that TAs frequently engaged with
the system, that pre-generation substantially reduced wait time, and that integrating starter code improved
technical accuracy. Comparative experiments further revealed that Claude outperformed GPT-4o-mini
within our enhanced pipeline.
</p>
<p>
These findings demonstrate that tightly integrating AI assistance into TA workflows can reduce friction and
enhance support for high-enrollment courses. The deployment infrastructure and usage dataset built this
semester provide a strong foundation for future data-driven improvements and continued refinement of the
generation pipeline.
</p>
<p><i>Tags: Retrieval-Augmented Generation (RAG); Large Language Models; Semantic Search; Context-Aware Automation; Chrome Extension; React Frontend; Backend API Integration; Intelligent Response Generation; User Feedback Loop; AI-Assisted Workflows</i></p>
</td>

<td>
<h2>ORBIT - Open Recommendation Benchmark for Reproducible Research with Hidden Tests</h2>
<img src="https://cmu.box.com/shared/static/pgmw0imohqd3ebwsnaqnlpzjmdw2ji77.png"/>
<p>
Vishan Vishesh Oberoi, Bolin Wu, Mahima Jagadeesh Patel, Kangrui Mao, Chuning Shi
</p>
<p>
Recommender systems are among the most impactful AI applications, interacting with billions of users
every day, guiding them to relevant products, services, or information tailored to their preferences. However,
the research and development of recommender systems are hindered by existing datasets that fail to capture
realistic user behaviors and inconsistent evaluation settings that lead to ambiguous conclusions. This project
introduces the Open Recommendation Benchmark for Reproducible Research with HIdden Tests (ORBIT),
a unified benchmark for consistent and realistic evaluation of recommendation models. ORBIT offers a
standardized evaluation framework of public datasets with reproducible splits and transparent settings for its
public leaderboard. Additionally, ORBIT introduces a new webpage recommendation task, ClueWeb-Reco,
featuring web browsing sequences from 87 million public, high-quality webpages. ClueWeb-Reco is a
synthetic dataset derived from real, user-consented, and privacy-guaranteed browsing data. It aligns with
modern recommendation scenarios and is reserved as the hidden test part of our leaderboard to challenge
recommendation models’ generalization ability. ORBIT measures 12 representative recommendation
models on its public benchmark and introduces a prompted LLM baseline on the ClueWeb-Reco hidden
test. Our benchmark results reflect general improvements of recommender systems on the public datasets,
with variable individual performances. The results on the hidden test reveal the limitations of existing
approaches in large-scale webpage recommendation and highlight the potential for improvements with
LLM integrations. This work is a collaborative effort with Meta AI and has been accepted to NeurIPS
2025, available at https://arxiv.org/abs/2510.26095. The ORBIT benchmark, leaderboard,
and codebase are available at https://www.open-reco-bench.ai.
</p>
<p><i>Tags: Recommendation System; Benchmarking and Evaluation; Large-Scale Retrieval; LLM-based Query Generation</i></p>
</td>

<td>
<h2>Theory of Mind for Explainable AI</h2>
<img src="https://cmu.box.com/shared/static/gibbze8e04wpcgmgoya4y08s0edftt41.png"/>
<p>Aditi Saini, Akshita Gupta, Krishnaprasad Vijayshankar</p>
<p>
Large Language Models (LLMs) have been gaining traction for performing complex reasoning tasks,
including those involving ethical and rationale-based decision-making. This raises important questions
about whether a model’s beliefs and reasoning can be influenced by external factors, and whether such
influence can be measured in terms of LLM faithfulness. This project focuses on evaluating LLM
faithfulness through theory of mind concepts. We define simulatability as a measure of how faithfully
a model adheres to its own reasoning - specifically, whether an LLM remains consistent with its beliefs
and ideological stance when confronted with counterfactual questions. We hypothesize that factors such
as toxicity and the presence or absence of explanations can induce variations in a model’s reasoning,
potentially revealing adversarial effects or reinforcing faithfulness. The objective of this project is to
systematically examine whether these factors affirm or undermine faithfulness in LLMs and to benchmark
their impact on ethical and non-objective questions derived from the ALMANACS, a language model
explainability benchmark.
</p>
<p><i>Tags: Large language model (LLM) Faithfulness; Theory of Mind; Ethical Reasoning; Counterfactual Analysis; Explainable AI</i></p>
</td>

<!-- CARD 4–6 -->
<tr style="text-align: center;">
<td>
<h2>RAG Modeling and Agent Evaluation</h2>
<img src="https://cmu.box.com/shared/static/kx6u8in8iewgpl8ks5x31c5wrss4x6f8.png"/>
<p>Abhijay Sai Paladugu, Andy Tang, Pranav Setlur</p>
<p>
Current evaluation of Retrieval-Augmented Generation (RAG) systems relies heavily on automated metrics
that fail to capture human preferences or assess performance on complex, multi-step tasks. This project first
addresses this gap by developing a multimodal RAG (mRAG) pipeline and RAG Arena, a scalable interface
for human-in-the-loop evaluation. Our analysis using this framework revealed a fundamental limitation:
RAG’s single-step retrieval is insufficient for long-horizon workflows. We therefore extended our work to
create a comprehensive diagnostic benchmark for LLM agents across code, search, and reasoning tasks.
By analyzing full trajectories, we successfully distinguish between agent failures caused by poor planning
versus those from long-context memory limitations. Our key finding is that while retrieval relevance is
critical for RAG, failures in complex tasks stem systematically from flawed planning, establishing a robust
evaluation paradigm for next-generation autonomous agents.
</p>
<p><i>Tags: Retrieval-Augmented Generation (RAG); Multimodal RAG (mRAG); Agent Evaluation; Long-Context Agents; RAG Arena; Human-in-the-Loop Evaluation; Agentic Benchmarking; Trajectory Analysis; Diagnostic Framework; Autonomous Agents; Large Language Models (LLMs); Planning vs. Memory Limitations</i></p>
</td>

<td>
<h2>Harmful Algae Bloom Detection</h2>
<img src="https://cmu.box.com/shared/static/q1o6vnlyoo6lfi33ibrinxbrbvl4yjt2.png"/>
<p>Yi Qun Heng, Madison Teague, Sarvesh Navare</p>
<p>
Harmful algae blooms (HABs) pose a serious threat to coastal communities in Madagascar where economic
dependence is on aquatic resources. Their erratic occurrence makes blanket seasonal fishing advisories
impractical and ineffective. Existing machine learning approaches for HAB detection achieve high accuracy
within their training regions but fail to transfer across geographic boundaries, dropping from 90 percent to 57 percent
accuracy when applied to Madagascar’s waters. This performance degradation is linked with Madagascar’s
limited historical HAB data and underscores the need to develop models trained on global data that
generalize well. In this project we develop a transferable HAB detection system using empirical findings
and publicly available comprehensive oceanographic and atmospheric data, deploy it on cloud and make
it available for usage via a dashboard that takes in a location and date and returns a classification (HAB
or not) for that location or time. This system enables targeted alerts that protect public health and coastal
livelihoods.
</p>
<p><i>Tags: Harmful Algal Bloom (HAB); Remote Sensing; Machine Learning; Big Data; Copernicus Climate Data Store; Harmful Algal Event Database (HAEDAT); Transformer; Mamba; SVM; AWS; kNN; Hierarchical Clustering</i></p>
</td>

<td>
<h2>Transforming Textbooks into Nonlinear Interactive Study Guides</h2>
<img src="https://cmu.box.com/shared/static/fo739tu4e6af8znui4biluil3srfdevn.png"/>
<p>
Mahita Kandala, Aijia Lei, Jacob Scriffiny
</p>
<p>
This project presents an end-to-end system that transforms traditional linear textbooks into interactive study
guides by automatically identifying and visualizing semantic relationships between paragraphs. Our team
combines embedding-based similarity filtering with large language model inference to detect background
and elaboration dependencies across full-length textbooks, constructing a directed graph that reflects each
textbook’s underlying conceptual structure. The backend stores these relationships in a Neo4j database and
serves them through a FastAPI service, while a React-based PDF reader overlays paragraph anchors on the
source PDF and enables nonlinear navigation with on-demand AI-generated explanations. Applied to five
textbooks across diverse domains, the system demonstrates that long-range discourse dependencies can be
inferred at scale and used to support more connected and exploratory modes of learning.
</p>
<p><i>Tags: NLP; Semantic Similarity; Discourse Modeling; Knowledge Graph; Educational Technology; Text Analysis; Interactive Visualization</i></p>
</td>

<!-- CARD 7–9 -->
<tr style="text-align: center;">
<td>
<h2>Agent4Molecule: LLM Agent for Discovery</h2>
<img src="https://cmu.box.com/shared/static/cvyx4vg59d1ktl287k2zaxchnyopn2j7.png"/>
<p>
Dhruv Garg, Emily Shen, Kaavya Subramanian
</p>
<p>
Several artificial intelligence (AI) tools aimed at accelerating the molecular discovery pipeline have recently
emerged. However, with the exception of AlphaFold, most tools in this domain have not been widely
adopted yet due to several factors. In parallel, Large Language Model (LLM) agents have recently gained
significant traction due to their scalable reasoning and problem-solving capabilities. Motivated by these
developments, we propose an LLM agent that automates molecular discovery pipelines by orchestrating
state-of-the-art AI tools, stitching them together along with structured evaluation on outputs, and using
strong reasoning capabilities to reliably produce high-quality molecules. To showcase the capabilities of our
agent, we automate two representative pipelines using natural language prompts: Heme binder generation
and EnzyGen, and successfully reproduced key results reported in the original work.
</p>
<p><i>Tags: Large Language Models (LLMs); Agent; MCP Server; AI for Science; Molecule Generation; Protein Design</i></p>
</td>

<td>
<h2>LLM Data Attribution Benchmark</h2>
<img src="https://cmu.box.com/shared/static/piufw8hpknxzy3lbwv6epo4fr5o0or5c.png"/>
<p>
Hanzhang Zhao, Niket Jain, Ishita Dasgupta
</p>
<p>
This work studies how training data quality and data attribution jointly shape large language model (LLM)
behavior. We first introduce DATE-LM, a benchmark for evaluating data attribution methods across three
practical tasks: training-data selection, toxicity and bias filtering, and factual influence tracing. DATE-
LM provides standardized evaluation protocols and scalable infrastructure for consistent comparison of
attribution techniques. Motivated by the dependence of attribution reliability on underlying data quality, we
further investigate an end-to-end LLM-based web rewriting pipeline as an alternative to traditional heuristic
cleaning in pretraining datasets. Through experiments involving multiple extraction methods, filtering
pipelines, and LLM rewriters, we observe meaningful variation in document quality, repetition patterns,
and scoring metrics. Our findings show that cleaner, more coherent corpora not only benefit pretraining but
also improve the stability and interpretability of data attribution. Together, these results highlight a unified
perspective on building attribution-aware data curation pipelines for modern LLMs.
</p>
<p>
<i>Tags: Large Language Models (LLMs); Data Attribution; Training Data Quality; Data Curation; Benchmarking; Web Corpus Construction; End-to-End Web Rewriting; CommonCrawl; Heuristic Filtering; LLM Rewriting; Influence Tracing; Toxicity and Bias Mitigation; Pretraining Data Selection; Quality Scoring; Dataman; fastText; Corpus Refinement; Attribution-Aware Data Pipelines</i>
</p>
</td>

<td>
<h2>Automated SQL Hinting for Postgres Query Optimization</h2>
<img src="https://cmu.box.com/shared/static/k2b8ammcfogxr8p2qhr4eod5gxc9yt2w.png"/>
<p>
Wenda Fu, Xueqi Li, Bobby Norwood
</p>
<p>
We introduce pg hint engine, an extensible framework for automatically generating SQL hint represen-
tations of arbitrary query plans. We demonstrate the engine’s functionality by forcing Datafusion plans
to run on Postgres. We further demonstrate the ability of pg hint engine to improve query performance
through query plan management, leading to a fourteen percent speed up in the Join Ordering Benchmark.
</p>
<p><i>Tags: Query Optimization; SQL Hints; Query Plan Management</i></p>
</td>

<!-- CARD 10–12 -->
<tr style="text-align: center;">
<td>
<h2>Optimizing Hybrid Cloud Partition and Placement of Data and Compute</h2>
<img src="https://cmu.box.com/shared/static/0a0sshlk6bco4f9a8pksw9xxbig1etqk.png"/>
<p>
Adarsh Nandanwar, Ananya Angadi, Chenghui Yu, Junwei Chen
</p>
<p>
The hybrid cloud deployment model is becoming increasingly popular with large organizations. In such a
hybrid environment, data may need to be moved frequently from one side to another, leading to thousands
of dollars spent per year in data movement or replication costs. Moirai is a new framework for optimizing
data and job placement in hybrid cloud deployments. It involves extracting and using relevant details about
jobs from job scheduler logs to guide data placement, job placement, and job scheduling decisions. The
goal here is to minimize the total cost and peak utilization of resources to improve resource utilization. The
framework is designed to run periodically for maximal efficiency, and is capable of scaling to large data
analytics infrastructure.
</p>
<p><i>Tags: Cloud Infrastructure; Hybrid Cloud; Data Placement; Job Scheduling; Optimization; Linear Programming</i></p>
</td>

<td>
<h2>NL2SQL: Natural Language to SQL</h2>
<img src="https://cmu.box.com/shared/static/5916u52g3omvkj2pwddkph1qcprdzv27.png"/>
<p>
Venu Arvind Arangarajan, Tim Han, Ziming Wang
</p>
<p>
Text-to-SQL systems have streamlined data analysis by allowing natural language queries to replace manu-
ally written SQL, enabling analysts to focus on insights rather than query construction. However, current
approaches, such as fine-tuning a single strong model, struggles to scale to complex, real-world databases.
These methods fail when handling large-scale relational structures and dynamic query requirements in
industrial settings. To address this gap, we propose a multi-agent Text-to-SQL generation framework that
automates schema linking, error detection and iterative refinement through reasoning plan generation and
multi-agent collaboration. By moving beyond fixed schema retrieval methods and refinement strategies,
our approach improves robustness, offering a scalable solution for complex database environments.
</p>
<p><i>Tags: Text-to-SQL; Multi-Agent Framework; Large Language Models; Database Schema Analysis; SQL Generation; Spider 2.0; Generative AI</i></p>
</td>

<td>
<h2>WayBuddy</h2>
<img src="https://cmu.box.com/shared/static/dioi210h84kbawqet66kvxrjmmrmmvbp.jpg"/>
<p>
Rithvik Senthil, Gunavardhan Akiti, Naveen Shenoy, Rupsa Dhar
</p>
<p>
Mobile vision applications often rely on compact object detection models that must operate under tight
computational constraints and adapt to continuously changing environments. However, maintaining these
small models typically requires costly manual annotation and frequent retraining. We introduce WayBuddy,
an automated fine-tuning framework that combines active learning with supervision from a large vision–
language model (VLM). The system identifies uncertain on-device detections, routes them to a server, and
uses the VLM as a drop-in replacement for human annotators to produce high-quality pseudo-labels. These
labels are integrated with historical data and periodically distilled back into the on-device detector, enabling
continuous improvement without human involvement. We evaluate this architecture on real-world mobile
video data, demonstrating that VLM-guided active learning reduces annotation cost to zero while improving
detection accuracy across multiple metrics. Our results highlight a practical pathway for maintaining small
models through selective, large-model supervision in resource-constrained environments.
</p>
<p><i>Tags: WayBuddy; On-Device Object Detection; Automated Active Learning; Fine-Tuning</i></p>
</td>

<!-- CARD 13–15 -->
<tr style="text-align: center;">
<td>
<h2>Less LLM, More Documents: Searching for Improved RAG</h2>
<img src="https://cmu.box.com/shared/static/qy8rbyzlxtmslr5vq2zje0ta3eg5828o.png"/>
<p>
Jingjie Ning, Yibo Kong, Yunfan Long
</p>
<p>
Retrieval-Augmented Generation (RAG) couples document retrieval with large language models (LLMs). While
scaling generators improves accuracy, it also raises cost and limits deployability. We explore an orthogonal axis:
enlarging the retriever’s corpus to reduce reliance on large LLMs. Experimental results show that corpus scaling
consistently strengthens RAG and can often serve as a substitute for increasing model size, though with diminishing
returns at larger scales. Small- and mid-sized generators paired with larger corpora often rival much larger models
with smaller corpora; mid-sized models tend to gain the most, while tiny and large models benefit less. Our analysis
shows that improvements arise primarily from increased coverage of answer-bearing passages, while utilization
efficiency remains largely unchanged. These findings establish a principled corpus–generator trade-off: investing in
larger corpora offers an effective path to stronger RAG, often comparable to enlarging the LLM itself.
</p>
<p><i>Tags: Retrieval-Augmented Generation; Passage Retrieval; Large Language Models; Corpus Scaling; Resource-Constrained Inference</i></p>
</td>

<td>
<h2>FAIRMUNI-2</h2>
<img src="https://cmu.box.com/shared/static/o4b78h1yztef0bngsimdzafv8pmrzxfr.png"/>
<p>
Lucy Sun, Nachaun Zhao, Bolin Zhang, Sayak Banerjee
</p>
<p>
Municipal bonds are a crucial mechanism for local governments to finance public projects, yet the factors
that influence their borrowing costs remain complex and often opaque. This project aims to identify the
key determinants that impact the True Interest Cost (TIC) of municipal bond issuers. To enable large-scale
and accurate TIC analysis, we develop a large language model (LLM)-based extraction pipeline that
automatically retrieves bond CUSIP schedules, bond information, and cost tables from unstructured
offering statement PDFs. Using the extracted data, we compute TIC at scale and build predictive models
that highlight the key features driving borrowing costs. The results indicate that years to maturity is the
dominant factor associated with higher borrowing costs. The detailed results are presented in Section 12
and also through an interactive dashboard.
</p>
<p><i>Tags: Large Language Model; Financial Analysis; Municipal Bond</i></p>
</td>

<td>
<h2>GPU Program Partitioning for Superoptimization</h2>
<img src="https://cmu.box.com/shared/static/6es4h8tanzastlr4tioofm75unx71ey0.png"/>
<p>
Man Kit Ao, Jiaying Li, Ayush Kumar
</p>
<p>
As Large Language Models (LLMs) become more and more complex and ubiquitous, the demand for
efficient computation of these LLMs is also increasing. Graphic Processing Units (GPUs) are often
the hardware of choice for training and running LLMs. However, programming GPU kernels requires
extensive domain knowledge and engineering efforts. Currently, there are tensor optimizers that can
automatically generate GPU kernels. Mirage is one such superoptimizer, capable of searching through
multiple levels of the GPU hierarchy. However, this large search space means Mirage can only effectively
optimize small subgraphs consisting of a few operators. Applying Mirage to larger models like GPT or
Llama requires users to manually partition the model, which is engineering-intensive.
</p>
<p>
In our project, we propose and implement a cost-model-based automatic program partitioner that automates
the partitioning and Mirage superoptimization of large models. We built an end-to-end pipeline that extracts
and partitions the computational graph of arbitrary PyTorch programs into Mirage-compatible and
incompatible partitions. Afterwards, we perform cost-model-informed dynamic programming to automatically
partition these programs and apply Mirage superoptimization. Our goal is to enable users to run Mirage on
their own PyTorch programs to improve computational efficiency.
</p>
<p><i>Tags: GPU, CUDA kernels, program partitioning, tensor parallelism, model parallelism, graphs, cost modelling</i></p>
</td>
</tr>

<!-- CARD 16–18 -->
<tr style="text-align: center;">
<td>
<h2>CyberLife AI</h2>
<img src="https://cmu.box.com/shared/static/kz7rpp71a7pvkxm4fhjuefavxwwh9art.png"/>
<p>
Webber Wu, Eagle Lo, Brad Chen
</p>
<p>
This report presents CyberLife AI, a no-code platform for creating personalized, topic-driven conversational
agents with persistent memory and knowledge grounding. We address limitations in existing platforms
through a memory-augmented dual-retrieval RAG pipeline combining conversation history recall with
document-based knowledge retrieval. The system enables non-technical users to create agents by uploading
domain-specific documents, defining personality traits, and customizing voice and appearance through
integrated speech recognition, text-to-speech synthesis, and animated avatar generation. The architecture
comprises a TypeScript/React frontend, Python Flask backend, and a separate GPU model server for avatar
generation.
</p>
<p><i>Tags: No-Code Conversational Agents Generation Platform, RAG, Long-Term Memory, Dual-Database Retrieval, Multimodal Ingestion, Large Language Models (LLMs) Systems, Knowledge Indexing, Applied AI Engineering</i></p>
</td>

<td>
<h2>Reproducible determination of 3D model and porosity of fuel cell cathode layers from pFIB-SEM data</h2>
<img src="https://cmu.box.com/shared/static/94ina5hiohn7val7atkypze1tnxgxio1.png"/>
<p>
Nicole Wang, Aryan Mehta, Enora Petry
</p>
<p>
This project presents a reproducible pipeline for 3D reconstruction and porosity analysis of fuel cell cathode
layers using pFIB-SEM image data. Existing approaches rely heavily on manual parameter tuning, which
introduces inconsistencies across datasets and limits reproducibility (Ferner et al., 2024a). To overcome
the scarcity of labeled data, we also generate synthetic 3D porous structures using Porous Microstructure
Analysis (PuMA) (Ferguson et al., 2018) and Blender (Blender Foundation, 2023), allowing us to create
diverse training datasets with known ground truth. Our approach improves reproducibility and sets the
foundation for future integration with scalable machine learning models and automated analysis of real and
synthetic materials.
</p>
<p><i>Tags: Mechanical Engineering; Machine Learning; Vision Model; Image Segmentation; 3D Software; AI for Science, AI for Materials Science</i></p>
</td>

<td>
<h2>MetaSafetyReasoner</h2>
<img src="https://cmu.box.com/shared/static/binvevchy6ltt7rjuftd6a4hg1rwzhcm.png"/>
<p>
Shrey Jain, Nishoak Kosaraju, Sathwik Acharya, James Ding
</p>
<p>
Large Reasoning Models, or LRMs, despite their excellence in mathematical and analytical reasoning, pose
serious safety risks. Their thinking chains can often be left unmonitored and with outcome-level reward a
chain with unsafe content in thinking chain but then a refusal in the output could be inadvertently reinforced
through outcome-level post-alignment methods. Fine-grained annotation within reasoning chains is gaining
popularity with recent benchmarks such as SafeRBench proposing novel schemes. We take a step further
towards leveraging fine-grained annotation for fine-grained rewards and propose MetaSafetyReasoner, a
scalable framework that can differently reinforce safety inducing, safety destabilizing and neutral behaviors
in model’s reasoning chains. Our approach centers around leveraging an LM trained for reasoning
chunk annotations on the SafeRBench labels. Through chunking and then labeling each chunk, a risk
profile for each behavior is assigned as the reward for the chunk. We then leverage a GSPO-inspired
training methodology to derive loss at subsequence-level. We expect gains on both explicit output safety
classification benchmarks and SafeRBench.
</p>
<p><i>Tags: Large Reasoning Models, Safety Alignment, Dense Reward Model, Reasoning Supervision, Jailbreak Attacks, Reinforcement Learning</i></p>
</td>

<!-- CARD 19–21 -->
<tr style="text-align: center;">
<td>
<h2>Multi-Agent LLM Systems for Code Migration</h2>
<img src="https://cmu.box.com/shared/static/m3f2a1zui9wp8256grtw3p6ib7mpx2kq.png"/>
<p>
Shanru Lin, Xinyu Li, Yogesh Adhi Narayan
</p>
<p>
Code migration between libraries is critical for security and compatibility but remains tedious and error-
prone in large, real-world codebases. We introduce an end-to-end multi-agent LLM system for Python
library migration that orchestrates three specialized agents: (1) an environment-setup agent that automati-
cally builds Dockerized runtimes for each repository; (2) a code-migration agent, extending SWE-Agent
with web documentation retrieval and a new LSP-RepoGraph module for symbol-centric structural context;
and (3) a testing agent, based on Qodo-Cover, that synthesizes Helper Tests for regression safety and
Evaluation Tests for post-migration validation. Our pipeline targets real repositories from PyMigBench
and evaluates migration quality via AST-level patch similarity and the pass rate of generated tests inside
project-specific containers. Early results suggest that structured retrieval and documentation-aware editing
reduce hallucinated API usages and missed call sites. This system shows the promise of multi-agent,
tool-augmented LLM workflows for realistic Python library migration.
</p>
<p><i>Tags: Code Migration; Large Language Models (LLMs) Agent; Multi-Agent; Python Library Migration; SWE-Agent; Qodo-Cover; RepoGraph</i></p>
</td>

<td>
<h2>LLM Secure Code Generation via Reasoning and Reinforcement Learning</h2>
<img src="https://cmu.box.com/shared/static/71lki76uhkfrl4jkmr4usjqcf62wy1fl.png"/>
<p>
Yanlin Fei, Arihant Sheth
</p>
<p>
Large language models for code generation frequently produce code containing security vulnerabilities,
yet existing mitigation approaches rely solely on unreliable reward signals from either high-false-positive
static analyzers or non-specialized general-purpose LLMs. We propose a two-stage framework combining
Chain-of-Thought Supervised Fine-Tuning with multi-reward Reinforcement Learning to enhance security
while preserving functional correctness. Our approach first employs CoT-SFT on security-related coding
tasks to instill explicit security reasoning, then applies RL with two complementary rewards: functional
and security-focused unit tests for dynamic execution validation, combined with static analysis using
CodeQL for vulnerability detection. Evaluation on the Python subset of CWEval demonstrates competitive
performance with state-of-the-art models, achieving secure code generation rates matching GPT-4o despite
using a 20× smaller model. Future evaluation on the complete CWEval set and CodeGuardPlus benchmarks
covering over 40 CWE categories will assess generalization to unseen vulnerability patterns across multiple
programming languages, demonstrating whether principled multi-reward optimization can achieve robust
security without sacrificing code quality.
</p>
<p><i>Tags: Secure Code Generation; Large Language Models (LLMs) Code Generation; Common Weakness Enumerations</i></p>
</td>

<td>
<h2>Interactive Vision-Language Navigation</h2>
<img src="https://cmu.box.com/shared/static/1ka7mofxw1dqo06l860siun37d7ppri3.png"/>
<p>
Wei Bin Au Yeong, Calvin Qin, Anubhav Sharma, Yaqi Wang
</p>
<p>
We present an Interactive Vision-Language Navigation (VLN) system that enhances robot navigation
in real-world environments through multi-turn dialogue. Unlike existing VLN agents that assume ideal,
unambiguous instructions, our approach addresses the ambiguity and inconsistency common in natural
human communication. Our system detects uncertainty in user instructions arising from under-specification
or mismatches with the environment and actively resolves it through dialogue. The pipeline integrates
a large language model (LLM) with environmental perception modules to reason about semantic and
contextual cues. To evaluate ambiguity detection and resolution methods, we augment current datasets with
ambiguous instruction scenarios and generate additional natural tasks using LLMs. Experiments show that
our dialogue-enabled agent achieves higher task completion rates in ambiguous settings, demonstrating the
promise of conversational VLN for more adaptable and user-friendly human-robot interaction.
</p>
<p><i>Tags: Vision-Language Navigation; Ambiguity Detection; Dialogue-based Resolution; Human-Robot Interaction; Embodied AI</i></p>
</td>
</tr>

<!-- CARD 22–24 -->
<tr style="text-align: center;">
<td>
<h2>Abstraction and Reasoning Challenge for LLMs</h2>
<img src="https://cmu.box.com/shared/static/jx4264csfl8mje66i18q6ur3ihp29ntx.png"/>
<p>
Akhil Dua, Jake Bentley, Naman Tuli
</p>
<p>
This work presents a data pipeline, modular system, and hardware strategy designed to improve the
abstraction and reasoning capabilities of large language models (LLMs) on the ARC-AGI-2 benchmark,
a challenging suite of grid-based visual reasoning tasks requiring generalization to entirely novel test
problems. We combine staged fine-tuning on curated ARC-style datasets with increasing difficulty with an
optimized test-time training (TTT) pipeline, enabling dynamic model adaptation using few-shot supervision
at inference. Our framework integrates a 4-bit quantized Mistral NeMo 8B model optimized for memory
efficiency and deployed across 4 GPUs under strict compute constraints. While experimental results
demonstrated substantial gains over baseline models, our staged data pipeline experiments failed to produce
substantial accuracy gains on the actual leaderboard. Although with the help of inference-level optimizations
and parameter averaging, the team’s best submission scored 6.67% on the public leaderboard, placing 85th
out of more than 1400 teams.
</p>
<p><i>Tags: ARC-AGI-2; Visual Reasoning; Test-Time Training; Few-Shot Adaptation; Model Quantization; Mistral NeMo; Multi-GPU Inference; Curriculum Fine-Tuning; Generalization Benchmarking</i></p>
</td>

<td>
<h2>Sotopia-ToM: Evaluating and Advancing Information Management in Multi-Agent Interaction with Theory of Mind (ToM)</h2>
<img src="https://cmu.box.com/shared/static/mf3yasgx0eeqciwt8ee3l6mfy2ql2rs7.png"/>
<p>
Ruichen Wang, Shihua Zeng, Yashwanth Yerabudala Surendra
</p>
<p>
Large language model (LLM) based agents in multi-agent systems (MAS) often fail to account for
information asymmetry, leading to over-disclosure or the omission of critical details. We introduce
Sotopia-ToM, a framework built on Sotopia V2 that evaluates an agent’s ability to share the right
information while protecting sensitive data during multi-party interactions. We collected and created
1,360 multi-party scenarios exhibiting varying degrees of information asymmetry, forming an extensive
benchmark for multi-agent conversation with a focus on privacy. We implemented and tested algorithmic
improvements such as chain-of-thought prompting and machine Theory of Mind (ToM), enabling agents
to infer and predict other agents’ knowledge states.
</p>
<p><i>Tags: Multi Agent Systems (MAS); Information Sharing, Privacy; Chain-of-Thought (CoT); Theory of Mind (ToM)</i></p>
</td>

<td>
<h2>Cross Lingual Natural Language Inference</h2>
<img src="https://cmu.box.com/shared/static/jol2vartp6d8mejxgjkgdltmd97mb5mk.png"/>
<p>
Jared Cochrane, Clint Zhu, Declan Tan
</p>
<p>
Natural Language Inference (NLI) examines whether a hypothesis sentence logically follows from,
contradicts, or is unrelated to a premise. Cross-Lingual NLI (XNLI) extends this task across languages,
where the premise and hypothesis appear in different languages. While widely useful for downstream tasks
such as question-answering, summarization, and translation evaluation, existing XNLI datasets contain only
about four hundred thousand examples per language pair, limiting the effectiveness of modern large-scale
models.
</p>
<p>
In this project, we leverage large parallel corpora and sentence perturbation to construct a greatly expanded
XNLI dataset with roughly one million examples per language pair. We fine-tune two XNLI classifiers on
this expanded dataset and integrate them into a reference-free machine translation evaluation system. The
XNLI-based MT evaluator shows strong correlation with state-of-the-art metrics, demonstrating that
entailment-driven evaluation can reliably assess translation quality without requiring manually translated
gold references.
</p>
<p><i>Tags: Natural Language Inference; Machine Translation Evaluation; Reference-Free Evaluation; XNLI; Entailment Classification; Large language model (LLM) Data Generation</i></p>
</td>

<!-- CARD 25 (final row, 1 card only) -->
<tr style="text-align: center;">
<td>
<h2>Beyond H-Index: New Metrics of Scientific Impact</h2>
<img src="https://cmu.box.com/shared/static/d3yeyr7ijuyqvxx2bidow64y8rn313po.png"/>
<p>
Divyan Goyal, Wang Xiang, Wenhao Xu
</p>
<p>
Evaluating scientific impact remains challenging because widely used citation-based metrics, such as the
H-Index, fail to reflect how researchers actually assess influence, novelty, or interdisciplinary reach. This
project introduces a human-centered framework for modeling academic impact by integrating large-scale
researcher metadata with empirical evidence from controlled pairwise comparisons.
</p>
<p>
We construct a comprehensive NLP researcher dataset by combining ACL Anthology and Semantic Scholar
metadata, along with a cross-disciplinary database to support broader analysis. An IRB-approved survey
administered at CMU and major NLP conferences presents both anonymous and named researcher comparisons,
allowing us to measure evaluation criteria as well as the influence of name visibility.
</p>
<p>
Using ranking models, we estimate how different metadata features contribute to human judgments of impact
and analyze discrepancies between participants’ stated values and their revealed preferences. The resulting
composite metric captures community judgment more faithfully than traditional citation-based indices,
offering a scalable and more holistic method for assessing interdisciplinary scientific influence.
</p>
<p><i>
Tags: Citation Context Analysis; Scientific Impact Measurement; Metric Learning; Researcher Profiling; Human-Guided Ranking
</i></p>
  </td>
</tr>
    </tbody>
   </table>
  </div>
 </div>
</html>
