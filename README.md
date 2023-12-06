# SQL-Answering-Key-Business-Questions

## Introduction

For this project, In this scenario, we will act as a data analyst for the Chinook Music Store. We will be tasked with answering business questions, some based on hypothetical scenarios, for the store in order to help them increase their overall performance:

* Which albums should the Chinook Store purchase based on the most popular genres?<br>
* Which Sales Support Rep has the best sales performance?<br>
* Which country has the highest sales amount for the Chinook Store?<br>
* Should Chinook shift the way it allows customers to purchase music from their store?<br>
* Which music artist is used in the most playlists?<br>

## Usage

The database can be downloaded [here](https://github.com/lerocha/chinook-database/tree/master/ChinookDatabase/DataSources). Be sure to select `Chinook_Sqlite.sqlite`. Once downloaded, run the following code in a Jupyter Notebook cell to connect to it:

`%%capture`<br>
`%load_ext sql`<br>
`%sql sqlite:///chinook.db`<br>

To run SQL queries in Jupyter Notebook, you must add `%%sql` at the start of every of cell.

The dataset will be explored using Jupyter Notebook. To run the project you will want to install Jupyter Notebook. The easiest way to do this is by installing Anaconda Navigator. This [link](https://docs.anaconda.com/free/anaconda/install/index.html) will direct you on how to install for your appropriate operating system: Windows, Mac OS, Linux, etc. Once installed, you should have access to several applications, one of them being Jupyter Notebook.

## Brief Overview

The database has 11 tables:

* `album`	
* `artist`	
* `customer`	
* `employee`	
* `genre`	
* `invoice`	
* `invoice_line`	
* `media_type`	
* `playlist`	
* `playlist_track`	
* `track`	

