---
# For reference on model card metadata, see the spec: https://github.com/huggingface/hub-docs/blob/main/datasetcard.md?plain=1
# Doc / guide: https://huggingface.co/docs/hub/datasets-cards
{{ card_data }}
---

# Dataset Card for Starbucks Reviews

## Dataset Description

- **Homepage:** [Starbucks Reviews Dataset on Kaggle](https://www.kaggle.com/datasets/harshalhonde/starbucks-reviews-dataset)
- **Repository:** [Starbucks Reviews Dataset on Kaggle](https://www.kaggle.com/datasets/harshalhonde/starbucks-reviews-dataset)

  
- **Paper:** {{ paper_url | default("", true)}}
- **Leaderboard:** {{ leaderboard_url | default("", true)}}
- **Point of Contact:** {{ point_of_contact | default("", true)}}

### Dataset Summary

This dataset contains a comprehensive collection of consumer reviews and ratings for Starbucks, a renowned coffeehouse chain. The data was collected through web scraping and includes textual reviews, star ratings, location information, and image links from multiple pages on the ConsumerAffairs website. It offers valuable insights into customer sentiment and feedback about Starbucks locations.

### Supported Tasks and Leaderboards

The Starbucks Review Dataset is designed to support:
- **Sentiment Analysis:** Researchers and data analysts can use this dataset to perform sentiment analysis to understand customer sentiment towards Starbucks.
- **Consumer Insights:** Businesses can gain valuable insights into customer preferences and areas for improvement based on the reviews and ratings.
- **Natural Language Processing (NLP):** NLP practitioners can utilize textual reviews for various NLP tasks, such as text classification, summarization, and topic modelling.

### Languages

The Starbucks Review Dataset is primarily focused on the English language. All data instances within this dataset are in English.


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
