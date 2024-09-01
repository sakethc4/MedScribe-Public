Public Repo for my team's George Washington University (George Hacks Project).
Built by Saketh Chintalapati, Hemang Vasu, Rachit Raval, and Vishal Kotha. 
George Hacks 2025 1st Prize winner and Best Overall Hack. 
Problem Statement: Sarah Poloma's topic Clinical trials that are not representative of patient populations are problematic for public health. Diverse populations need to be recruited and retained in research studies so that the resulting approved treatments are not harmful or less effective to patient populations that vary across demographic categories including ethnicity, sex and age. The barriers to recruit and retain participants to clinical research trials sometimes includes language barriers. Potential participants that fit the “inclusion criteria” of a study may not speak English or may speak it as a second language.

We solved this problem by building MedScribe a full stack application that allows users to upload consent forms in any language.
And have their form automatically translated to whatever language they desire. After the pdf or other file type
is uploaded we extracted the text and passed it through the Google Translation API's. We then took the outputted 
translated text and passed it through OpenAI API calls to summarize the legal jargon of the document to something 
an elementary school student could easily understand. I also built a chatbot using OpenAI API that I planned to integrate 
with the full stack application (essentially using the document as a knowledge base allowing users to ask it questions 
and get their doubts clarified) but unfortunately we ran out of time. 

Future improvements for this idea are chatbot integration. Also want to use existing e-sig APIS to allow users to 
sign consent/release forms within the application as well. 
