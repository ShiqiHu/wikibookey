# wikibookey
## Members
Shiqi Hu, Cindy Koh, Michael Martinez, Junjie Li

## Description
The project aims to use Wikipedia as the key resource to build books that will focus topics that a reader wants to read, as if the reader were to purchase a complete, coherent book from the bookstore.

In this project, we would like to build an interface that users can interact with the content in Wikipedia. In our project, there would be two main function, automatically producing the book for the users and customizing the book by the users. For automatically producing the book, the user would search the specific topic in our website, and then the website would linked to the relative page of wikipedia. According to the content in Wikibookey, we would category those content by their title into the introduction part, main part and conclusion. In the main part, we would use the wiks APIs to link different part to different chapters. For the customizing part, after linking to Wikipedia, user would click the content they want in Wikipedia and also tag those part with different categories or different chapters. User could also be able to add chapters or specific content to the book, besides, they can also sort the content as they want. After the user has confirm the book, a PDF can be exported and downloaded so that the user can read the book locally. For the whole project, we want to keep the process simple but also try to realize more functions to allow users customize the book.

In order to build the web application, we will use Ruby on Rails. Also, we will do some research to see if there are any API we could use to assist us implementing some functions such as Wikipedia searching function.

## How it works
User could search a scentific topic on our website. Wikibookey would offer the matched wikipedia results to the user. In the result, Wikibookey showes the key words of each part in the wiki page as well as the relationship of each content. By reading the keywords, user could choose the content they want and add them to their customized book. Wikibookey also provides some related wiki pages as "also see" for the users to offer addition resources. Besides, a book structure preview would be shown on the right sides. Finally, user could save the book as PDF and the exported book would be styled like a real book. And the book can also be printed.

## Technical
Python-based Web Frameworks: Flask and Django
Libraries for Web Scraping: BeautifulSoup, scrapy
Libraries for PDF building: xhtmltopdf (Flask), reportlab (Django)
APIs: MediaWiki and Wikidata Query Service
May need to consider IP/copyright issues

## next step
build the skectches
start the paper prototype
figure out the technical issues
fisrt focus on the scentific book (such as plant/flowers)

