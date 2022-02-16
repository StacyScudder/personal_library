![so many books so little time](img/so_little_time.jpg)

# personal_library
This project will incorporate pieces from several other repos dealing with book data to build a personal library.

## Purpose  
I have a large personal library that includes books, ebooks, and audiobooks. For several years, I've used a free program called [Calibre](https://calibre-ebook.com/) to manage my ebooks. Recently, I've thought about including my audiobooks and physical books, as well, but I'm still trying to find the best way to include everything I want. Calibre is highly customizable, so I've added columns for the books format that will let me include everything together. Of course, those extra columns have to be updated manually, which isn't ideal since there are so many that have multiple formats. Calibre has a plug-in that allows it to import a csv list of books, so I thought it might be better to combine all my books into one csv file and import them already set up with the formats for each book already there. Once I have the library set up correctly in Calibre, there are several programs that will let me use the Calibre database to create a website. I have one at the moment running on a Synology home server in Docker, but it only has ebooks.

## Data
I haven't included my data in the repo, but I'll add details about how I gathered it all. If anyone wants to use my code for their own books, make sure you either create a folder called my_data to hold the files with your data, or change the code to reflect the location of your own data.

**Goodreads**
I keep up with the number of books I read per year with the Goodreads Challenge. Many of the other shelves in my goodreads library are old and really need to be cleaned. However, I exported all the books I have on the site so sort out later which ones to keep and which to delete. To get your own books from goodready, go to My Books on the top menu, then scroll down the page. Towards the bottom on the left side under your shelves, you'll see Tools with Import and Export at the bottom of that list.
![Goodreads Import and Export](img/gr_tools.png)
