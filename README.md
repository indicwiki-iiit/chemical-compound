# Chemical-Compound
Generating Wikipedia Articles on 10k+ chemical compounds in Hindi.

## Stages of the Poject -
The following ordered list will give an idea as to what were the stages to complete the project - 

- [x] Scrape Data from Web sources.
- [x] Clean and Format the data.
- [x] Scrape infobox information from Wikipedia.
- [x] Create a sample article.
- [x] Review of the sample article.
- [x] Work on feedback from review of sample article.
- [x] Review of the dataset
- [x] Create template for article generation.
- [x] Review of the template.
- [x] Work on feedback from review of template.
- [x] Create articles for 50 compounds.
- [x] Work on feedback from review of template.
- [x] Create the XML dump for all the chemical compounds to be published.

##  Folders -
- `full_length_articles`: Contains all the compound files that have been used for this project.
- `Selenium`: Contains browser setup for the project.
- `Template`: Contains the jinja template for the XML generation of a chemical compound article.

## Datasets -
- [CompoundCID](https://pages.github.com/)- This file contains the compound ids of compounds

## Generating Articles -
- [DataExtraction]() - This file contains code for data extraction from website.
- [article_generation]() -This file contains code to accumulate all the articles in a single xml file.
- [final_xmlDUMP]() - This is a xml file which contains 10k+ articles.
- [XMLDump]() - This is a xml file contains first 50 test articles.


