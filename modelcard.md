---
# For reference on model card metadata, see the spec: https://github.com/huggingface/hub-docs/blob/main/modelcard.md?plain=1
# Doc / guide: https://huggingface.co/docs/hub/model-cards
{{ card_data }}
---

# Model Card for Clothing Reviews

The model used is a Long Short-Term Memory (LSTM) model, a type of recurrent neural network (RNN) designed to analyze product reviews and predict whether people are likely to recommend the product or not. It leverages the structure of text data to capture dependencies and patterns in reviews, allowing it to make binary recommendations based on the sentiment and content of incoming reviews.

## Model Details

### Model Description

The LSTM (Long Short-Term Memory) model is a sequential neural network architecture with dropout regularization. It is trained on X% of the dataset, and is designed for opinion analysis and product recommendation prediction.

Each opinion is associated with a binary recommendation label (1 for recommended and 0 for not recommended). During training, the model adjusts its internal parameters to make accurate predictions based on patterns it learns from the training data.

The metric used was Accuracy, as it is as relevant to know the good ones as the bad ones.

- **Developed by:** Valèria Caro Via, Esther Fanyanàs i Ropero, Claudia Len Manero
- **Shared by [optional]:** {{ shared_by | default("[More Information Needed]", true)}}
- **Model type:** LSTM
- **Language(s) (NLP):** English
- **License:** {{ license | default("[More Information Needed]", true)}}
- **Finetuned from model [optional]:** {{ finetuned_from | default("[More Information Needed]", true)}}

### Model Sources [optional]

<!-- Provide the basic links for the model. -->

- **Repository:** {{ repo | default("[More Information Needed]", true)}}
- **Paper [optional]:** {{ paper | default("[More Information Needed]", true)}}
- **Demo [optional]:** {{ demo | default("[More Information Needed]", true)}}

## Uses

The model is designed to analyze customer reviews and comments in order to understand sentiment and determine whether customers are likely to recommend a product positively or not. 

### Direct Use

This is useful for other customers and companies to make data-driven decisions, without having to read all the reviews and only know whether or not they recommend the product.

<!-- This section is for the model use without fine-tuning or plugging into a larger ecosystem/app. -->


### Downstream Use [optional]

<!-- This section is for the model use when fine-tuned for a task, or when plugged into a larger ecosystem/app -->

{{ downstream_use | default("[More Information Needed]", true)}}

### Out-of-Scope Use

<!-- This section addresses misuse, malicious use, and uses that the model will not work well for. -->

{{ out_of_scope_use | default("[More Information Needed]", true)}}

## Bias, Risks, and Limitations

- **Biased content**: The model may be less accurate in predicting the sentiment of opinions that use less common language than the training data.

- Risks**: The model will learn from opinions about people, and will not have a context for identifying whether this opinion fits a person or not. e.g. fat people.

- Limitations**: The model may be less accurate for text data that is significantly different from the e-commerce reviews it was trained on. For example, it may not work well with social media posts or formal business communications.
<!-- This section is meant to convey both technical and sociotechnical limitations. -->

### Recommendations

The model is recommended for analyzing overall trends in customer sentiment and identifying areas for improvement based on customer feedback.

## How to Get Started with the Model

Use the code below to get started with the model.

{{ get_started_code | default("[More Information Needed]", true)}}

## Training Details

### Training Data

<!-- This should link to a Data Card, perhaps with a short stub of information on what the training data is all about as well as documentation related to data pre-processing or additional filtering. -->

{{ training_data | default("[More Information Needed]", true)}}

### Training Procedure 

<!-- This relates heavily to the Technical Specifications. Content here should link to that section when it is relevant to the training procedure. -->

#### Preprocessing [optional]

{{ preprocessing | default("[More Information Needed]", true)}}


#### Training Hyperparameters

- **Training regime:** {{ training_regime | default("[More Information Needed]", true)}} <!--fp32, fp16 mixed precision, bf16 mixed precision, bf16 non-mixed precision, fp16 non-mixed precision, fp8 mixed precision -->

#### Speeds, Sizes, Times [optional]

<!-- This section provides information about throughput, start/end time, checkpoint size if relevant, etc. -->

{{ speeds_sizes_times | default("[More Information Needed]", true)}}

## Evaluation

<!-- This section describes the evaluation protocols and provides the results. -->

### Testing Data, Factors & Metrics

#### Testing Data

<!-- This should link to a Data Card if possible. -->

{{ testing_data | default("[More Information Needed]", true)}}

#### Factors

<!-- These are the things the evaluation is disaggregating by, e.g., subpopulations or domains. -->

{{ testing_factors | default("[More Information Needed]", true)}}

#### Metrics

The evaluation metrics used have been:

- Accuracy: 
<!-- These are the evaluation metrics being used, ideally with a description of why. -->

{{ testing_metrics | default("[More Information Needed]", true)}}

### Results

{{ results | default("[More Information Needed]", true)}}

#### Summary

{{ results_summary | default("", true) }}

## Model Examination [optional]

<!-- Relevant interpretability work for the model goes here -->

{{ model_examination | default("[More Information Needed]", true)}}

## Environmental Impact

<!-- Total emissions (in grams of CO2eq) and additional considerations, such as electricity usage, go here. Edit the suggested text below accordingly -->

Carbon emissions can be estimated using the [Machine Learning Impact calculator](https://mlco2.github.io/impact#compute) presented in [Lacoste et al. (2019)](https://arxiv.org/abs/1910.09700).

- **Hardware Type:** {{ hardware | default("[More Information Needed]", true)}}
- **Hours used:** {{ hours_used | default("[More Information Needed]", true)}}
- **Cloud Provider:** {{ cloud_provider | default("[More Information Needed]", true)}}
- **Compute Region:** {{ cloud_region | default("[More Information Needed]", true)}}
- **Carbon Emitted:** {{ co2_emitted | default("[More Information Needed]", true)}}

## Technical Specifications [optional]

### Model Architecture and Objective

{{ model_specs | default("[More Information Needed]", true)}}

### Compute Infrastructure

{{ compute_infrastructure | default("[More Information Needed]", true)}}

#### Hardware

{{ hardware | default("[More Information Needed]", true)}}

#### Software

{{ software | default("[More Information Needed]", true)}}

## Citation [optional]

<!-- If there is a paper or blog post introducing the model, the APA and Bibtex information for that should go in this section. -->

**BibTeX:**

{{ citation_bibtex | default("[More Information Needed]", true)}}

**APA:**

{{ citation_apa | default("[More Information Needed]", true)}}

## Glossary [optional]

<!-- If relevant, include terms and calculations in this section that can help readers understand the model or model card. -->

{{ glossary | default("[More Information Needed]", true)}}

## More Information [optional]

{{ more_information | default("[More Information Needed]", true)}}

## Model Card Authors [optional]

{{ model_card_authors | default("[More Information Needed]", true)}}

## Model Card Contact

{{ model_card_contact | default("[More Information Needed]", true)}}



