# Top Thematic Differences Between Classic Female Romance Authors and Top Modern Female Romance Authors

## Corpus Description
This corpus contains notable novels from famous classic female romance genre writers Jane Austen and Charlotte Bronte, as well as popular modern female romance authors, Colleen Hoover and Tessa Bailey. Novels by Austen include Pride and Prejudice and Sense and Sensibility; by Bronte include Jane Eyre and The Professor; by Bailey include It Happened One Summer and Fix Her Up; and by Hoover include Ugly Love and November 9.

## Target Audience
This dataset is ideal for historical and/or literary analysts, scholars and students, feminist and womens' studies activists and/or scholars, and cultural researchers who are interested in comparing the classic female authors within genres that are predominantly romantic to those of the modern day to analyze thematic metamorphosis.

## Intended Usage of the Dataset
This dataset is intended for commentary, educational, and research purposes, as the copyright allows its usage only in these dimensions. This corpus allows for comparison of writing styles, trends, language used, subject matter, and thematic elements of popular female romance writers between the early 19th century and the modern day (2023).

## Text Selection Criteria
The two major criteria when selecting works were that the authors of the works had to be female and widely regarded as romance writers, or at least with heavy romantic themes or plots as a focal point in the texts, and had to publish works in the English language. The authors also had to be writing during a similar period in the early 19th century and in the recent years of the 21st century, so as not to create 3 comparison points but 2 to simplify the focus of the dataset. The texts had to be legally obtained or purchased through online platforms so that they could be converted to .txt files. The authors were selected for their relative popularity for their time periods - Austen and Bronte are widely recognized as prominent female English romance novelists of the 19th century, while Bailey and Hoover are widely popular romance novelists in the 21st century.

## The Data Collection Process
Collecting this data involved downloading the novels from various online platforms (after legally purchasing e-books online for modern writers). In some cases, this involved converting pdf files to txt files using an online tool.

## Cleaning and Preprocessing
The .txt files in the corpus were cleaned up using a simple replace function for \n markers. They were also tokenized and lemmatized for standardization purposes. 

## Annotations
Annotations were achieved through part-of-speech tagging which was made possible through the prior tokenization and lemmatization. These annotations identified both part-of-speech and named entities, creating texts that were labeled in detail.

## File Format and Columns Description
| Variable | Description |
| --- | --- |
| file_name | The name of the file of the novel text in format Author Last Name - Title Keyword(s) |
| author_name | Name of the author |
| year_published | The year of publication of the novel |
| author_type | A Classic author or a Modern author |
| Doc | Text processed through spaCy |
| Tokens | Text broken down into words or 'tokens' |
| Lemmas | Wordcounts expended to include root words |
| POS | Part-of-speech tag for each word |
| Proper_Nouns | Extracted every proper noun in each file |
| Named_Entities | Categories assigned to known entity types |
| NE_Words | The words that the named entities are assigned to |

## Side Notes
The corpus is big. While more accuracy is achieved by including a larger dataset, it could also be possible to create smaller sets with only 2 novels in each.
