# ABOUT CHALLENGE

## All YOU NEED TO KNOW:

Are you ready to bridge the gap between possibilities and reality? If yes, this is the opportunity for you to get a dream job at HCL Technologies in Noida. 

HCL Technologies is looking to hire machine learning enthusiasts both freshers and working professionals who can come up with the most practically efficient, well-engineered solutions to text extraction and image processing problems. 

It’s your chance to earn the right to an exclusive job offer from HCL’s EXACTO™ Product Team, which has a pedigree of some of the world’s best engineering institutes and where you will get to upskill your career by learning the latest technologies. EXACTO™ Team helps leading enterprises to bring their businesses to the future by making their processes intelligent by using Computer Vision, Natural Language Processing (NLP), Machine Learning (ML) techniques and Data Science.

About EXACTO™:

EXACTO™ is developed in collaboration with a leading university in the field of AI and is a result of our continued investments in research and development. EXACTO™ harnesses the latest innovations in Artificial Intelligence (AI), Machine Learning (ML) and Computer Vision techniques that integrate seamlessly with Robotic Process Automation (RPA) to create a differentiated product. The Natural Language Processing (NLP) based engine allows EXACTO™ in interpreting, extracting and reading both structured and unstructured text information. This enables handling and identifying any missing, unseen and ill-formed data from not only when it comes to printed documents but handwritten as well. 


Curious to know more about EXACTO™. [Click Here!](https://youtu.be/ASC_C951R-w)

Find Your Fit: Techies with 0 to 8 years of experience (2019 and below graduates) and hands-on with Python/Machine Learning/Data Science are preferred. 

Hiring Challenge Format & Process:  Solve a machine learning problem, and if you are shortlisted the HR partner from HCL will get in touch with you. 

So, don’t settle for the realities of today. 


# Extract values from Financial Statement documents

Balance Sheet presents the assets, liabilities, and equity of the entity as of the reporting date. Thus, the information 
presented is as of a specific point in time. The report format is structured so that the total of all assets equals the 
total of all liabilities and equity (known as the accounting equation). This is typically considered the second most 
important financial statement, since it provides information about the liquidity and capitalization of an organization. 
You are provided with 2 sample balance sheet documents for reference and 500 balance sheet documents as test 
data. Your task is to extract the values for Year '201 9' only from the test data. 
• If '2019' does not exist in a given balance sheet document, you still need to extract the relevant metrics and 
associate them with an 'NaN' value 

Please refer 'Submission Format' section for more details. 



## Dataset folder comprises of 3 files

  1.** HCL ML Challenge Dataset folder** contains 500 .txt files: you need to train & apply your NLP model on these files 
  2. **Sample Dataset** folder contains 2 sample files for reference and understanding of problem statement 
  3. **sample_submission.csv**  contain the format in which your output file needs to be 
  4. **Results.csv:**  contains expected format of submission file with test data values 


## Submission Format: 
Notes on values to be extracted: 

	- Although the files represent financial statements, the values to be extracted are not numeric for all the  documents. The values can be string ('(%d)','-',etc.) or numeric (%d) 
	- If value extracted is in '(\d+)' format, re-format to '-\d+'. Example: '(23,000)' becomes '-23000' 
	- Some of the balance sheets do not have '2019' column. In such cases, the assets, liabilities, etc. reported need  to be extracted with their corresponding value being "nan" 
	- Replace currency and utf-encoded characters/symbols in the assets column with respective html codes 
	- Your submission record must be convertible to its dictionary representation. You can ensure this by applying `json.loads()` to each entry 
  
  

## Evaluation Criteria: 

Total score is based on number of documents you have successfully extracted the values for: 

`if(actuals_dict[ 'Extracted Values ' ][i]. items() == predicted_dict[ ' Extracted Values ' ] [i] . items()) :
	  score = score+1 `

**Note:**  Uploading source code is mandatory for for manual evaluation of algorithm used. 


## Additional Resources:

1. **Ways to extract information from invoices:** https://www.hypi.io/post/reading-text-from-invoice-images-with-python
2. **Text Annotation:** https://www.cogitotech.com/text-annotation/
3. **Accenture way to extract details from text:** https://www.searchtechnologies.com/blog/natural-language-processing-techniques
4. **Web scrapping code for uploading the records in file and obtaining the score:** https://github.com/CP-4/Auto-Submit-Hcl
5. **How to Tokenise the sentences:** https://www.geeksforgeeks.org/nlp-how-tokenizing-text-sentence-words-works/
6. **How to extract Keywords from text:** https://towardsdatascience.com/textrank-for-keyword-extraction-by-python-c0bae21bcec0

