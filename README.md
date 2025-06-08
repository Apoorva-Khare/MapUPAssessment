# MapUPAssessment
This dataset consist of total 665314 entries and 9 columns
# Steps:
1. Uploaded and Read the File
2. Data Preprocessing and Cleaning(dropped null values)
3. Exploratory Data Analysis
4. Data Visualization
5. Summary
   
# Libraries used:
1. Pandas
2. matplotlib.pyplot
3. Regular Expression
4. Datetime
5. Seaborn
   
# Summary
* Total log entries: 665,314

* Successfully parsed entries: ~399,865 (rest had issues like missing/invalid datetime)

* Daily trends show a consistent volume of traffic, with noticeable peaks on specific days.

* Top IPs:

local (339260 requests)

remote (326054 requests)

Suggests the system is tested or used heavily in internal and remote setups

* Request Methods
GET: 664,779 → Standard resource requests

* Top Resources Accessed
Most requested URL: index.html (104,136 times)

Others include image and GIF files like 3.gif, 2.gif, 8870.jpg, etc.

* Status Code Distribution
200 OK: 566,858 → Successful responses

304 Not Modified: 97,792 → Cached content (no data transfer)

302, 403, 500 are rare → Very few redirects, forbidden accesses, or errors

This log reflects a mostly static website with high GET traffic, minimal dynamic interaction (POST), 
and solid uptime (few 500 errors). The request patterns align with human usage during working hours, and caching is efficiently used (many 304 responses). The server appears to serve a mix of HTML pages and media files, possibly for a public-facing portal or documentation site.

Email: apkhare29@gmail.com
Likedin: www.linkedin.com/in/apoorva-khare-7548642a6
