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

Here are a few sample data instances from the Starbucks Review Dataset to illustrate its content and structure:

1. **Name:** Helen
- **Location:** Wichita Falls, TX
- **Date:** Reviewed Sept. 13, 2023
- **Rating:** 5
- **Review:** Amber and LaDonna at the Starbucks on Southwest Parkway are always so warm and welcoming. There is always a smile in their voice when they greet you at the drive-thru. And their customer service is always spot-on, they always get my order right and with a smile. I would actually give them more than 5 stars if they were available.
- **Image_Links:** ['No Images']

2. **Name:** Courtney
- **Location:** Apopka, FL
- **Date:** Reviewed July 16, 2023
- **Rating:** 5
- **Review:** ** at the Starbucks by the fire station on 436 in Altamonte Springs, FL made my day and finally helped me figure out the way to make my drink so I‚Äôd love it. She took time out to talk to me for 2 minutes to make my experience better than what I‚Äôm used to. It was much appreciated! I‚Äôve had bad experiences one after another at the Starbucks that‚Äôs closest to me in my work building with my drinks not being great along with not great customer service from specific baristas. Niko was refreshing to speak to and pleasant. The drink was perfect! Store 11956
- **Image_Links:** ['No Images']

### Data Fields

The Starbucks Review Dataset includes the following key data fields, each serving a specific purpose in organizing and describing the data:

1. **Name:** Name of the reviewer (text).
2. **Location:** Location or city of the reviewer (text).
3. **Date:** Date when the review was posted (text).
4. **Rating:** Star rating given by the reviewer (1 to 5).
5. **Review:** Textual content of the review (text) = Image_Links: Links to associated images (text).
6. **Image Links:** Images.


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
