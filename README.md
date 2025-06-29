# Do zoos still draw crowds?

## Project 1 - Lede 2025

### Objective
For my first project, I decided to see how much impact has the awareness around animal rights had on people. I was curious to know how steeply has the visitors number fallen in zoos across India.

### Findings
My assumption about the shrinking popularity of zoos fell flat when I checked the visitors data. I found no decline in the footfall in Indian zoos. Although the initial narrative of my story changed, but the broader theme about the number of zoo visitors still stood. I packaged it with the reasons about why zoos still attract masses.

### Story URL
[https://namanxshah.github.io/zoos/](https://namanxshah.github.io/zoos/)

### How I collected the data
Part of the reason why I chose this story was the opportunity to utilise my newly-acquired scrapping skills and extract the data from the website of India's Central Zoo Authority - [https://cza.nic.in/information-about-zoos/en](https://cza.nic.in/information-about-zoos/en)  
However, scrapping the webpage only helped with a small dataset about the total number of zoos and the state-wise numbers. To find the data of visitors, I had to dig in through the annual reports of each zoo separately. But very few zoos were consistent in submitting their annual reports. So I took the visitors' data of only those zoos, which had published their annual reports for 2024-25 and compared them with their visitors data of the previous eight years. Annual reports for earlier years were not available at [https://cza.nic.in/annual-reports-of-zoos/en](https://cza.nic.in/annual-reports-of-zoos/en).  
I thought that data of the last eight years was enough to give a decent picture about the trend, as it goes back till 2017-18 i.e. three years before the COVID pandemic disruption.  
Out of the total 156 recognized zoos in the country, only 13 had submitted their annual reports for 2024-25. Four of these 13 were rescue / research centres and one of the zoos had free entry, so there was no visitors data for these five. For the remaining eight zoos, I manually collected the visitors data in a spreadsheet.  
The remaining data about categorization and ownership of zoos in India, as well as the classification of animals was taken from [https://cza.nic.in/page/en/faqs](https://cza.nic.in/page/en/faqs)

### How I analysed data
I started by scrapping [https://cza.nic.in/information-about-zoos/en](https://cza.nic.in/information-about-zoos/en) through BeautifulSoup. Since website had data about 525 zoos, which was paginated in 53 pages, I took help of a Teaching Assistant to apply a for loop. Then Pandas helped me filter out the derecognized zoos and get the state-wise data of the recognized zoos.  
Rest of the data was readily available at [https://cza.nic.in/page/en/faqs](https://cza.nic.in/page/en/faqs) and didn't require any analysis.

### New skills applied
This project is the first time I put Python programming and BeautifulSoup scrapping into practice for my own story. Even if it is through a templatised ([https://jsoma.github.io/page-templates/basic/index.html](https://jsoma.github.io/page-templates/basic/index.html)) manner, this project is the first time that I created a webpage that included HTML and CSS structuring.

### Shortcomings
The biggest drawback was the selection of the story. I wanted my first project to require an extensive application of my python / API / scrapping skills. When I checked the website of Central Zoo Authority, I thought it could be a good practice pitch. But the limited scope for scrapping and pandas analysis was a let down for me. A large portion of this story included manual data collection, which is not what I want to do in my Lede projects.  
Other than this, the little bit of scrapping that I did in this story, involved major assistance from a Teaching Assistant. So, I feel underconfident about my learnings.
