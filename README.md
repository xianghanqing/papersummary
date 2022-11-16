# papersummary
1.把D:\papersummary\DataDownloader\sciencedirect_collect.py文件的inlist改成对应路径 inlist = 'D:\papersummary\DataDownloader\cspubsum_test_ids.txt'
2.把 piir = "http://api.elsevier.com/content/article/PII:" + pii + "?httpAccept=text/xml&APIKey=" + apikey改成https：
 piir = "https://api.elsevier.com/content/article/PII:" + pii + "?httpAccept=text/xml&APIKey=" + apikey
