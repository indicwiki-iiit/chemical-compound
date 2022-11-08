# Chemical-Compound
Generating Wikipedia Articles on 10k+ chemical compounds in Hindi.

## Stages of the Project -
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
- `compound` - Contains first 50 articles.
- `Selenium`: Contains browser setup for the project.
- `Template`: Contains the jinja template for the XML generation of a chemical compound article.

## Datasets -
- [CompoundCID](https://github.com/indicwiki-iiit/chemical-compound/blob/main/compoundCID.csv)- This file contains the compound ids of compounds
- [PubChem_compound_list](https://github.com/indicwiki-iiit/chemical-compound/blob/main/PubChem_compound_list.csv) - This file contains the basic informations of chemical compounds.

## Generating Articles -
- [DataExtraction](https://github.com/indicwiki-iiit/chemical-compound/blob/main/DataExtraction.py) - This file contains code for data extraction from website.
- [article_compilation](https://github.com/indicwiki-iiit/chemical-compound/blob/main/article_compilation.py) -This file contains code to accumulate all the articles in a single xml file.
- [final_xmlDUMP](https://github.com/indicwiki-iiit/chemical-compound/blob/main/final_xmlDUMP.xml) - This is a xml file which contains 10k+ articles.
- [XMLDump](https://github.com/indicwiki-iiit/chemical-compound/blob/main/XMLDump.xml) - This is a xml file contains first 50 test articles.
