# Awesome-Story-Generation

## Paper

- **Storyline** : Plan-And-Write: Towards Better Automatic Storytelling  AAAI, 2019  [[paper]](https://arxiv.org/pdf/1811.05701.pdf)   [[code]](https://bitbucket.org/VioletPeng/language-model)
- **Propmt for hierarchical generation**: Hierarchical Neural Story Generation   ACL, 2018 [[paper]](https://arxiv.org/pdf/1805.04833.pdf)   [[code]](https://github.com/kevalnagda/StoryGeneration)
- **New paper**: Guiding Neural Story Generation with Reader Models  arXiv  [[paper]](https://arxiv.org/pdf/2112.08596.pdf)  
- **New paper with controllable gpt**：Goal-Directed Story Generation: Augmenting Generative Language Models with Reinforcement Learning arXiv [[paper]](https://arxiv.org/pdf/2112.08593v1.pdf)
- **Using control factors**: Towards Controllable Story Generation WS, 2018 [[paper]](https://aclanthology.org/W18-1505.pdf)
- **By sentence rewriting and reordering**: Towards Document-Level Paraphrase Generation with Sentence Rewriting and Reordering Findings(EMNLP), 2021  [[paper]](https://arxiv.org/pdf/2109.07095v1.pdf)   [[code]](https://github.com/l-zhe/corpg)
- **By event representation**: Event Representations for Automated Story Generation with Deep Neural Nets [[paper]](https://arxiv.org/pdf/1706.01331v3.pdf)  [[code]](https://github.com/lara-martin/ASTER)
- **Dialogue generation concerning character relations**: Telling Stories through Multi-User Dialogue by Modeling Character Relations SIGDIAL (ACL) 2021[[paper]](https://arxiv.org/pdf/2105.15054v1.pdf)
- **By plot**: Story Realization: Expanding Plot Events into Sentences [[paper]](https://arxiv.org/pdf/1909.03480v2.pdf)  [[code]](https://github.com/rajammanabrolu/StoryRealization)
- NEUROLOGIC A* Fesque Decoding: Constrained Text Generation with Lookahead Heuristics arXiv [[paper]](https://arxiv.org/pdf/2112.08726v1.pdf)
- Plans and Planning in Narrative Generation: A Review of  Plan-Based Approaches to the Generation of Story, Discourse and Interactivity in Narratives
- **An old review**: From Linear Story Generation to Branching Story Graphs
- **Story gan(Vision)**: StoryGAN: A Sequential Conditional GAN for Story Visualization  CVPR, 2019  [[paper]](https://arxiv.org/pdf/1812.02784v2.pdf)   [[code]](https://github.com/yitong91/StoryGAN)
- **Plug and play**: A Plug-and-Play Method for Controlled Text Generation Findings(EMNLP), 2021 [[paper]](https://arxiv.org/pdf/2109.09707v1.pdf)  [[code]](https://github.com/dapascual/k2t)
- **Plug and Blend**: Plug-and-Blend: A Framework for Controllable Story Generation with Blended Control Codes [[paper]](https://arxiv.org/pdf/2104.04039v2.pdf)  [[code]](https://github.com/xxbidiao/plug-and-blend)
- **Score system**: Toward Educator-focused Automated Scoring Systems for Reading and Writing arXiv  [[paper]](https://arxiv.org/ftp/arxiv/papers/2112/2112.11973.pdf)
- **A survey**：A Survey of Natural Language Generation arXiv [[paper]](https://arxiv.org/pdf/2112.11739.pdf)
- **Reward shaping**: Controllable Neural Story Plot Generation via Reward Shaping arXiv [[paper]](https://arxiv.org/pdf/1809.10736v3.pdf)  

#### Some about extraction

- **An up-to-date Review of  Relation Extraction**: More Data, More Relations, More Context and More Openness: A Review and Outlook for Relation Extraction
- **Information extraction**: Neural Information Extraction From Natural Language Text
- **Event extraction**: Joint Extraction of Events and Entities within a Document Context

####  Microsoft Textworld

- **Nearly review**: Modeling Worlds in Text
- **Introduction**: TextWorld: A Learning Environment for Text-based Games
- State Prediction in TextWorld with a Predicate-Logic Pointer Network Architecture
- Generating Interactive Worlds with Text
- https://github.com/microsoft/TextWorld

#### FAIR LIGHT

- Learning to Speak and Act in a Fantasy Text Adventure Game
- https://github.com/facebookresearch/ParlAI/tree/main/projects/light
- **Some other awesome projects in ParlAI**: https://github.com/facebookresearch/ParlAI

## Dataset

- [**ROC Stories**](https://cs.rochester.edu/nlp/rocstories/):   is a collection of commonsense short stories. The corpus consists of 100,000 five-sentence stories. Each story logically follows everyday topics created by Amazon Mechanical Turk workers. These stories contain a variety of commonsense causal and temporal relations between everyday events. Writers also develop an additional 3,742 Story Cloze Test stories which contain a four-sentence-long body and two candidate endings. The endings were collected by asking Mechanical Turk workers to write both a right ending and a wrong ending after eliminating original endings of given short stories. Both endings were required to make logical sense and include at least one character from the main story line. The published ROCStories dataset is constructed with ROCStories as a training set that includes 98,162 stories that exclude candidate wrong endings, an evaluation set, and a test set, which have the same structure (1 body + 2 candidate endings) and a size of 1,871. This corpus is unique in two ways: 

  ​		(1) it captures a rich set of causal and temporal commonsense relations between daily events；

  ​		(2) it is a high quality collection of everyday life stories that can also be used for story generation.

- [**CommonGen**](https://inklab.usc.edu/CommonGen/):  CommonGen is constructed through a combination of crowdsourced and existing caption corpora, consists of 79k commonsense descriptions over 35k unique concept-sets.

- [**Writing prompt**](https://www.kaggle.com/ratthachat/writing-prompts): Use to generate consistent stories by Hierarchical Neural Story Generation (Fan et al., 2018)

- [**CMU Movie Summary Corpus**](http://www.cs.cmu.edu/~ark/personas/): This page provides links to a dataset of movie plot summaries and associated metadata. (https://www.dropbox.com/s/i5dsk92735jpunf/EventRepresentationDataRelease.zip?dl=0)

- [**Scifi TV Shows (Scifi TV Show Plot Summaries & Events)**](https://huggingface.co/datasets/lara-martin/Scifi_TV_Shows): A collection of long-running (80+ episodes) science fiction TV show synopses, scraped from Fandom.com wikis.

- [**Clever(vision)**](https://cs.stanford.edu/people/jcjohns/clevr/):  is a synthetic Visual Question Answering dataset. It contains images of 3D-rendered objects; each image comes with a number of highly compositional questions that fall into different categories. Those categories fall into 5 classes of tasks: Exist, Count, Compare Integer, Query Attribute and Compare Attribute. The CLEVR dataset consists of: a training set of 70k images and 700k questions, a validation set of 15k images and 150k questions, A test set of 15k images and 150k questions about objects, answers, scene graphs and functional programs for all train and validation images and questions. Each object present in the scene, aside of position, is characterized by a set of four attributes: 2 sizes: large, small, 3 shapes: square, cylinder, sphere, 2 material types: rubber, metal, 8 color types: gray, blue, brown, yellow, red, green, purple, cyan, resulting in 96 unique combinations.



