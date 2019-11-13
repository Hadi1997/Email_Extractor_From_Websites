# Email_Extractor_From_Websites
Python programme to extract emails from different websites.

Object: 
- To scrape emails from different websites.
- To check website by adding different page links in order to scrape emails if present there.
- Page links used: ['about','contact','find','inquiry','touch','reservation','location','contacts','about-us','contact-us','support']

Python libraries used:
1. Openpyxl
2. Urllib
3. BeautifulSoup
4. Selenium
5. Time
6. Pandas

Points to consider:
- Make sure to setup all these libraries first.
- Also make sure to install Chrome driver and add the path to chrome driver in system variables.

Description: 
Put all the websites link in "inputLinks.csv", run "emailscrapper.py" file, It will fetch the links and search the website for email and social links, after that if the email is founded, the programme will write the email in "EmailAndSocialLinksScrapping1.xlsx" file.
