# Spidy-data-crawler
Data crawler to extract data
# Description
Our solution is to develop a web application that crawls for a given set of keywords to extract URLs of the websites that promotes pornography, child abuse, women abuse and cyber bullying.

This crawler is not only limited for those areas but also it can be used to collect data about several illegal websites that promotes drugs, terrorism, ammunition etc.

# Working 

<li>
<ul>1. The keywords will be given to the Data Crawler through a Web based Application by the operator.</ul>
<ul>2. Data Crawler performs the obfuscation process and enables the Tor proxies.</ul>
<ul>3. After the above process is initiated , the crawler will query multiple search engines for the given keywords</ul>
<ul>4. The response provided by the search engines is then parsed using a HTML parser and the respective URLs are obtained.</ul>
<ul>5. The URLs obtained from the previous step will then be stored into a cloud database for the purpose of data integrity and remote access.</ul>
<ul>6. The data that is stored in the database will then be presented to the operator through the web application.</ul></li>

# Flowchart 
![alt text](https://github.com/hackzzdogs1337/Spidy-data-crawler/blob/master/Picture1.jpg)

# Working Functionality


<ul>1. “Robots.txt” is a special file which will disallow some crawlers . To overcome this ,the spider will automatically change its User-Agent field of the HTTP Header.</ul>

<ul>2. Since we will be imposing huge traffic on domains the WAF (Web application Firewall ) behind some domains may block the requests coming out from the operator’s IP .So to bypass this we will integrate our spider with multiple proxies so that we can crawl effectively.
</ul>

# Salient Features

<ul>1. Performing Obfuscation (spoofing) process prevents the crawler from being blocked by the web servers.</ul>

<ul>2. The operator will be able to view the results while the crawler is running in the background.</ul>

<ul>3. The operator can upload a text document that contains several keywords for crawling.</ul>

### Technology Used :
1. Python
2. Tor 
3. Google Cloud
4. Flask
5. Mongo DB

# Snapshot 
Here is a snapshot showcasing the working of our prototype

## Developed By Team Novato Leets 
### Team Members : 
<ul>1. Elisha Sam Peter Prabhu </ul>
<ul>2. Anirudh N </ul>
<ul>3. Anirudh TT </ul>
<ul>4. Ashwath Kumar A </ul>
<ul>4. Infant Sheerin K </ul>                                                      
<ul>5. Ezhilarasi V </ul>
