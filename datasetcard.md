---
# For reference on model card metadata, see the spec: https://github.com/huggingface/hub-docs/blob/main/datasetcard.md?plain=1
# Doc / guide: https://huggingface.co/docs/hub/datasets-cards
{{ card_data }}
---

# Dataset Card for Sexism Identifier

## Dataset Description

- **Homepage:** {{ http://nlp.uned.es/exist2022/}}
- **Repository:** {{ repo_url | default("", true)}}

### Dataset Summary

{{ The dataset consists of expressions and terms, both in English and Spanish, which are commonly used to undermine the role of women in society. These expressions were sourced from various Twitter accounts that collect phrases and expressions frequently encountered by women (Twitter users) in their daily lives. The dataset also includes terms used in previous state-of-the-art approaches. This collection of terms underwent analysis and filtering by two gender issues experts, Trinidad Donoso and Miriam Comet. These experts examined examples of tweets that were extracted using these terms as seeds. The final dataset comprises more than 200 expressions commonly used in sexist contexts.

To maintain a balanced dataset, expressions with fewer than 60 associated tweets were excluded. The curated set of expressions includes 94 seeds for the Spanish language and 91 seeds for English. For each seed, approximately 50 tweets were randomly selected from the period of December 1st to December 31st, 2020, for the training set, and 22 tweets per seed were selected from the period of February 1st to February 28th, 2021, for the test set. This distribution was designed to ensure temporal separation between the training and test data. Consequently, the training set consists of 4,500 tweets per language, while the test set comprises 2,000 tweets per language.

The final EXIST dataset comprises 6,977 tweets for training and 3,386 tweets for testing. Both sets were randomly selected from larger pools of labeled sets, totaling 9,000 and 4,000 examples for training and testing, respectively, to maintain class balance.

Additionally, a collection of 492 instances in English and 490 instances in Spanish was gathered from the uncensored social network Gab.com, following a similar data collection procedure as previously described. These instances will be integrated into the EXIST test set to assess differences between social networks with and without "content control," specifically Twitter and Gab.com, respectively.}}

### Supported Tasks and Leaderboards

{{ Sexist Content Detection: Given a text or tweet, the task is to detect and classify whether it contains sexist content or not. This task is crucial for identifying and mitigating online harassment and promoting gender equality.
Task Description: In the sexist content detection task, models are trained to classify text as either containing sexist content or being free from sexist content. This dataset is suitable for binary classification and can be used to develop and evaluate models for identifying and addressing sexist language and behavior on social media platforms.

Additional Resources: We provide separate training and test sets for this task, along with evaluation scripts to measure model performance. These resources have been extracted from the IberLEF 2021 shared task and are available for download on our dataset's homepage.

Related Work: The Sexism Identifier dataset has been used in research conducted during the IberLEF 2021 (http://nlp.uned.es/exist2022/) shared task, and subsequent publications may provide insights into model architectures and approaches for sexist content detection in social networks.

}}

### Languages

{{ languages_section | default("[More Information Needed]", true)}}

## Dataset Structure

### Data Instances

{{ data_instances_section | default("[More Information Needed]", true)}}

### Data Fields

{{ data_fields_section | default("[More Information Needed]", true)}}

### Data Splits

{{ data_splits_section | default("[More Information Needed]", true)}}

## Dataset Creation

### Curation Rationale

{{ curation_rationale_section | default("[More Information Needed]", true)}}

### Source Data

#### Initial Data Collection and Normalization

{{ data_collection_section | default("[More Information Needed]", true)}}

#### Who are the source language producers?

{{ source_language_producers_section | default("[More Information Needed]", true)}}

### Annotations

#### Annotation process

{{ annotation_process_section | default("[More Information Needed]", true)}}

#### Who are the annotators?

{{ who_are_annotators_section | default("[More Information Needed]", true)}}

### Personal and Sensitive Information

{{ personal_and_sensitive_information_section | default("[More Information Needed]", true)}}

## Considerations for Using the Data

### Social Impact of Dataset

{{ social_impact_section | default("[More Information Needed]", true)}}

### Discussion of Biases

{{ discussion_of_biases_section | default("[More Information Needed]", true)}}

### Other Known Limitations

{{ known_limitations_section | default("[More Information Needed]", true)}}

## Additional Information

### Dataset Curators

{{ dataset_curators_section | default("[More Information Needed]", true)}}

### Licensing Information

{{ licensing_information_section | default("[More Information Needed]", true)}}

### Citation Information

{{ citation_information_section | default("[More Information Needed]", true)}}

### Contributions

{{ contributions_section | default("[More Information Needed]", true)}}
