# Useful Google Dorks 🌐

## 💡 What are Google Dorks?

Google dorks are queries that use a combination of search operators to fine-tune your Google searches.

## 🔍 Syntax and Usage

These follow a particular syntax using advanced search operators that refine search results. Some popular operators include:


- **intitle**: Searches for pages with a specific keyword in the title.

   Example: `intitle:"maltego"` will find pages with "maltego" in the title.

- **inurl**: Searches for URLs containing a specific keyword.

   Example: `inurl:maltego` will find URLs containing the word "maltego".

- **filetype**: Narrows results to specific file types (e.g., `pdf`, `doc`, `csv`).

   Example: `filetype:pdf site:example.com` will find PDF files on "example.com".

- **site**: Limits the search to a specific website (e.g., `site:example.com`).

   Example: `site:github.com maskedolive` will search for pages mentioning "maskedolive" only on GitHub.

- **intext**: Searches for pages with a specific keyword in the page content.

   Example: `intext:"artificial intelligence"` will find pages containing the phrase "artificial intelligence".

- **ext**: Limits results to files with a specific extension (e.g., `ext:php`).

   Example: `ext:html inurl:about` will find HTML files with "about" in the URL.

- **cache**: Finds cached versions of a webpage.

   Example: `cache:example.com` will show Google's cached version of "example.com".

- **link**: Finds pages that link to a specific URL.

   Example: `link:example.com` will find pages that link to "example.com".

- **related**: Finds pages related to a specific URL.

   Example: `related:example.com` will find pages related to "example.com".

- **define**: Provides definitions for a specific term.

   Example: `define:cybersecurity` will give a definition for the term "cybersecurity".

- **info**: Provides information about a specific URL.

   Example: `info:example.com` will give information about "example.com".

- **movie**: Finds information about a specific movie.

   Example: `movie:Inception` will provide information about the movie "Inception".

- **book**: Finds information about a specific book.

   Example: `book:"To Kill a Mockingbird"` will provide information about the book "To Kill a Mockingbird".

- **weather**: Provides current weather conditions and forecasts for a specific location.

   Example: `weather:New York` will provide weather information for New York.

- **stocks**: Provides stock market information for a specific company.

   Example: `stocks:GOOGL` will provide stock information for Google.

- **map**: Displays a map centered around a specific location.

   Example: `map:London` will display a map centered around London.

- **movie showtimes**: Provides movie showtimes for a specific location.

   Example: `movie showtimes:Los Angeles` will display movie showtimes for Los Angeles.

- **calculator**: Functions as a basic calculator.

   Example: `calculator:2+2` will return the result "4".

- **define**: Provides definitions for a specific term.

   Example: `define:quantum` will define the term "quantum".

## Categories to Explore

## 🔍 Category: Webcams - Peeking into the World

Discover live camera feeds from all over the globe! Marvel at breathtaking scenery, bustling streets, and serene sunsets. Be a virtual traveler with these dorks:

```
inurl:/view.shtml
intitle:"Live View / - AXIS"
inurl:/control/userimage.html
intitle:"Toshiba Network Camera" user login
intitle:"i-Catcher Console - Web Monitor"
...
```

## 💉 Category: SQL Injection (SQLi)

SQL Injection is a type of security vulnerability that allows attackers to manipulate a web application's database by injecting malicious SQL code into input fields or parameters. This can lead to unauthorized access, data leakage, or even complete control of the database.

```
inurl:"product.php?pid="
inurl:"category.php?id="
inurl:"news.php?id="
inurl:"gallery.php?id="
inurl:"article.php?id="
inurl:"profile.php?id="
inurl:"product-list.php?id="
inurl:"product-detail.php?id="
...
```

## 🥷 Category: Cross-Site Scripting (XSS)

Cross-Site Scripting (XSS) is a security vulnerability that allows attackers to inject malicious scripts into web pages viewed by other users. This can lead to session hijacking, cookie theft, or the execution of arbitrary code in the context of the victim's browser.

```
inurl:"search.php?q="
inurl:"results.php?q="
inurl:"gallery.php?name="
inurl:"blog.php?title="
inurl:"category.php?name="
inurl:"faq.php?question="
inurl:"feedback.php?comment="
...
```

## 🛡️ Category: Vulnerable Servers - Uncovering Weaknesses

Unearth vulnerable servers, weak points, and potential security risks. Help make the web safer by reporting any vulnerabilities you discover. Protect and educate!

```
intitle:"Test Page for the Apache Web Server on Fedora Core"
intitle:"Index of" "CentOS" "Test Page"
intitle:"Test Page for the Nginx HTTP Server"
...
```

## 🔒 Category: Sensitive Directories - Beware of Hidden Paths

Explore hidden directories, secret realms, and confidential data that accidentally made its way into public view. Tread carefully!

```
intitle:"Index of /admin"
intitle:"Index of /backup"
intitle:"Index of /config"
...
```

## 💽 Category: Database Files - Unveiling Sensitive Data

Stumble upon database files that might contain sensitive information. Handle with care and utmost respect for privacy.

```
filetype:sql intext:username password
filetype:sql "insert into" (pass|passwd|password)
...
```

## 🚪 Category: Login Pages - Enter the Gateway

Discover login portals, access points, and entryways into secured systems. Respect the sanctity of access controls and never trespass!

```
intitle:"Login" inurl:/login
intitle:"Login" inurl:/signin
...
```

## 📡 Category: Network Devices - Journey through Networking World

Navigate through network devices, routers, and access points. Find and secure, but never intrude!

```
intitle:"RouterOS" inurl:/winbox
intitle:"Ubiquiti" intext:"airOS"
...
```

## 🎥 Category: CCTV Systems - Peering through Surveillance

Explore CCTV systems, camera setups, and surveillance feeds. Respect privacy and avoid unethical use!

```
intitle:"DVR Login" inurl:/login.htm
...
```

## 🔐 Category: Apache Tomcat - Unveil Tomcat Servers

Discover Apache Tomcat servers and applications. Handle with care and report any vulnerabilities responsibly!

```
intitle:"Apache Tomcat" intext:"Apache Tomcat"
...
```

## 🛑 Category: Error Messages - Understanding Errors

Analyze various error messages to understand web server behavior and potential weaknesses. Report responsibly!

```
intext:"Error 404: Not Found"
...
```

## 🗃️ Category: Git Repository Files - Exploring Repositories

Stumble upon Git repositories, codebases, and version control systems. Respect intellectual property and never exploit!

```
filetype:gitweb inurl:git
...
```

## ⚙️ Category: Configuration Files - Delving into Settings

Uncover configuration files and system settings. Treat them with utmost care and privacy!

```
filetype:conf inurl:web.config
...
```

## 💡 Category: PHP Info Files - PHP Insights

Discover PHP information files. Handle this knowledge responsibly!

```
filetype:php inurl:info
...
```

## 📜 Category: Wordpress Sites - Enter the World of WordPress

Explore WordPress sites and blogs. Respect intellectual property and refrain from unauthorized access!

```
inurl:/wp-admin
...
```

## 📁 Category: Open Directory Listings - Directory Treasure Hunt

Embark on a quest to find open directories with valuable content. Treat what you find with respect and privacy!

```
intitle:"Index of /" + "backup"
...
```

## 🌟 Category: Google Drive Links - Drive to the Clouds

Unlock direct links to Google Drive files. Respect the owner's privacy and intellectual property!

```
inurl:"/uc?id="
...
```

## 📜 Category: Wordpress Configuration Files - WordPress Secrets

Stumble upon WordPress configuration files. Handle them responsibly and respect privacy!

```
filetype:txt inurl:wp-config
...
```

## 🔐 Category: AWS Access Keys - AWS Wonderworld

Find AWS access keys, but be cautious! Report responsibly and never exploit!

```
filetype:pem intext:PRIVATE KEY
...
```

## 🗃️ Category: Configuration Files - Hunting Configuration

Discover various configuration files. Handle with care, and never misuse!

```
filetype:env intext:AWS_SECRET_ACCESS_KEY
...
```


## ⚡ Additional Google Dork Syntax Examples (Continued)

4. **Finding URLs with a Specific Keyword**:
   - `inurl:"keyword"` - Searches for URLs containing the specified keyword.

5. **Excluding Specific Terms**:
   - `-term` - Excludes results containing the specified term.

6. **Searching for Pages with a Specific Title**:
   - `intitle:"your search term"` - Searches for pages with the specified term in the title.

7. **Looking for Pages with a Specific Extension**:
   - `ext:php` - Limits results to files with a PHP extension.
   - `ext:html` - Limits results to HTML files.

8. **Finding Social Media Profiles**:
   - `site:facebook.com "John Doe"` - Searches for Facebook profiles with the name "John Doe".

9. **Locating Login Pages**:
    - `intitle:"Login" inurl:/login` - Finds login pages.

10. **Exploring Subdomains**:
    - `site:*.example.com` - Searches for subdomains of "example.com".

11. **Finding Vulnerable Webcams**:
    - `intitle:"Live View / - AXIS"` - Searches for AXIS webcams.

12. **Discovering Exposed Git Repositories**:
    - `intitle:index.of.git` - Searches for exposed Git repositories.

13. **Uncovering Open Directories**:
    - `intitle:"Index of /"` - Searches for open directories.

14. **Identifying Exposed Elasticsearch Instances**:
    - `intitle:"Kibana" intext:"You know, for search"` - Searches for publicly accessible Elasticsearch instances.

15. **Hunting for Configuration Files**:
    - `filetype:env intext:AWS_SECRET_ACCESS_KEY` - Searches for AWS secret access keys in configuration files.

16. **Revealing WordPress Configuration Files**:
    - `filetype:txt inurl:wp-config` - Searches for WordPress configuration files.

17. **Finding AWS Access Keys**:
    - `filetype:pem intext:PRIVATE KEY` - Searches for AWS private keys.

18. **Finding Vulnerable PHP Scripts**:
   - `intitle:"PHP Shell"` - Searches for pages with PHP shells.

19. **Locating Exposed Admin Panels**:
    - `intitle:"Admin Login"` - Searches for pages with "Admin Login" in the title.

20. **Discovering Network Devices with Default Credentials**:
    - `intitle:"Router Login" | intext:"default username"` - Searches for router login pages with default usernames.

21. **Exploring Database Backup Files**:
    - `ext:sql intext:"-- MySQL dump"` - Searches for MySQL database dump files.

22. **Identifying Exposed MongoDB Instances**:
    - `intitle:"MongoDB Shell"` - Searches for MongoDB admin consoles.

23. **Hunting for Backup Files**:
    - `intitle:"Index of /backup"` - Searches for directories with "backup" in the name.

24. **Uncovering Exposed Jenkins Instances**:
    - `intitle:"Dashboard [Jenkins]"` - Searches for Jenkins dashboard pages.

25. **Finding Apache Struts Vulnerabilities**:
    - `intitle:"Welcome to the Apache Struts" intext:"showcase"` - Searches for Apache Struts showcase applications.

26. **Discovering Exposed WordPress Theme Files**:
    - `inurl:/wp-content/themes/ intitle:"Index of"` - Searches for directories with WordPress theme files.

27. **Locating Exposed GitLab Repositories**:
    - `intitle:"index of /" inurl:".gitlab.yml"` - Searches for GitLab configuration files.

28. **Hunting for Exposed Jupyter Notebooks**:
    - `intitle:"Jupyter Notebook" -"Sign Up" -"Log In"` - Searches for public Jupyter notebooks.

29. **Finding Misconfigured Jenkins Instances**:
    - `intitle:"Dashboard [Jenkins]" inurl:/job/` - Searches for Jenkins jobs.

30. **Exploring Exposed Grafana Dashboards**:
    - `intitle:"Grafana"` - Searches for Grafana dashboard pages.


## Country-Specific Google Dork Lists


| **Country**          | **Most Used Dork List**                                              | **Security Level (%)** |
|----------------------|--------------------------------------------------------------------|------------------------|
| **United States**    | `"inurl:/view.shtml" "intitle:\"Live View / - AXIS\""`             | 85                     |
| **India**            | `"inurl:\"product.php?pid=\"" "inurl:\"category.php?id=\""`        | 75                     |
| **United Kingdom**   | `"inurl:\"search.php?q=\"" "inurl:\"results.php?q=\""`             | 80                     |
| **Australia**        | `"intitle:\"Test Page for Apache Server\"" "inurl:admin"`          | 78                     |
| **Canada**           | `"intitle:\"Test Page for Nginx HTTP Server\"" "filetype:log"`     | 82                     |
| **Germany**          | `"intitle:\"Index of /admin\"" "filetype:sql intext:password"`     | 85                     |
| **France**           | `"filetype:sql intext:username password" "intext:\"Error 404\""`   | 78                     |
| **Brazil**           | `"filetype:env intext:AWS_SECRET_ACCESS_KEY" "inurl:/uc?id="`      | 75                     |
| **Japan**            | `"inurl:/wp-admin" "filetype:log inurl:config"`                    | 80                     |
| **South Africa**     | `"filetype:pem intext:PRIVATE KEY" "filetype:php inurl:info"`      | 76                     |
| **Russia**           | `"intitle:\"index of\" \"backup\"" "filetype:xls inurl:admin"`     | 72                     |
| **China**            | `"inurl:/web-console/ServerInfo.jsp" "filetype:log intext:password"` | 85                  |
| **Mexico**           | `"intext:\"Index of /backup\"" "filetype:log inurl:web.config"`    | 76                     |
| **Spain**            | `"intitle:\"index of\" \"passwords.txt\"" "filetype:txt inurl:config"` | 80                  |
| **Italy**            | `"intitle:\"Index of /config\"" "filetype:xml inurl:admin"`        | 80                     |
| **Sri Lanka**        | `"filetype:sql intext:username password" "inurl:console/"`         | 70                     |
| **Bangladesh**       | `"intitle:\"index of\" \"config.txt\"" "filetype:xml inurl:admin"` | 72                     |
| **Philippines**      | `"filetype:sql intext:username password" "inurl:/console"`         | 75                     |
| **Indonesia**        | `"inurl:/cgi-bin/printer/printer.cgi" "filetype:reg inurl:web.config"` | 75                  |
| **South Korea**      | `"filetype:sql intext:username password" "inurl:/servlet/Main"`    | 80                     |
| **Vietnam**          | `"filetype:log inurl:admin" "intitle:\"index of\" \"config.xml\""` | 75                     |
| **Saudi Arabia**     | `"inurl:/console/CrystalReportsWebFormViewer.aspx" "filetype:sql"` | 85                     |
| **Israel**           | `"filetype:xls inurl:admin" "intitle:\"Index of /admin\""`         | 80                     |
| **Pakistan**         | `"intitle:\"index of\" \"passwords.txt\" "filetype:txt inurl:config"` | 72                  |
| **Iran**             | `"filetype:reg inurl:web.config" "inurl:/cgi-bin/printer"`         | 75                     |

