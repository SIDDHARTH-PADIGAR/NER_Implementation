## Named Entity Recognition (NER)

- Serves as a bridge between unstructured text and structured data, enaqbling machines to sift through vast amounts of textual information.
- Extracting nuggets of valueable data in categorized form.

**Purpose:**
-Is to comb through unstructured data and chunk it up as named entities into predefined categories
-- Making data more actionable, facilitating tasks like Data Analysis, Information Retrieval, and Knowledge graph construction.

**How it works**
1. Tokenization
2. Entity Identification: Using various linguistic rules or statistical methods(involves recognizing patterns)
3. Entity Classififcation: Categorized into pre-defined classes such as "Person", "Organization", etc.
4. Contextual Analysis: NER systems often consider the surrounding context to improve accuracy. For example, in the sentence "Apple released a new phone", the context helps the system recognizes "Apple" as an organisation rather than a fruit.
5. Post-Processing: After initial recognition and classification, post-processing is applied to refine results, like resolving ambiguities, merging multi-token entities or using knowledge bases to enhance entity data.

**NER Methods**
1. Rule-Based: Grounded to manually crafted rules, Entity based on linguistic patterns, regex or dictionaries: extracting standard medical terms from clinical notes, they might struggle with large/diverse datasets due to rigid rules.
2. Statistical: Transitioning from manual rules, statistical methods employ models like: HMM(Hidden Markov Models) or CRF(Conditional Random Fields). They predict named entities based on likelihoods dericed from training data. APt for tasks with ample labeled datasets at their disposal, strength liew in generalizing across diverse texts.
3. ML(Machine Learning): This takes it a step further by using algorithms such as Decision Trees or SVM. Learning from labeled data, their widespread adoption in modern NER systems is attributed to their prowess in handlingvast datasets and intricate patterns. However they're hungry for substantial labeled dataand can be computationally demanding.
4. DL(Deep Learning): The latest in line are DL methods, which harness the power of Neural Networks, with the pros being similar to ML Methods.

**Note: Since there are no one-size-fits-all in NER, leading to intertwining 1, 2, 3, 4 capturing the best of all worlds.**

