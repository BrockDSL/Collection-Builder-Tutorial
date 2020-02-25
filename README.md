![DSL Logo](dsl_logo.png)

# A Tutorial on Using CollectionBuilder
![Cat Photo Metadata](https://124135-361502-raikfcquaxqncofqfm.stackpathdns.com/asset/img/banners/kb/data-glossary/metadata.png)
 
## Introduction
CollectionBuilder is a lightweight digital tool that creates exhibits with metadata support through Github. It was created and is maintained by librarians from the University of Idaho to aid librarians and others in visualizing metadata and browsing through metadata rich collections.

It is very similar to Omeka S in that it creates exhibits surrounding metadata. However if one could say that Omeka S runs along a dimension of few objects with a great deal of metadata, then one could also say that CollectionBuilder runs along a separate dimension of more objects bound together by a csv file with metadata, and allows for visualization of connections between the objects.

CollectionBuilder Test for the Brock DSL: https://kat-a-t.github.io/Brock_DSL_CollectionBuilder/

### Steps
1) Procure a collection of jpg images, YouTube videos, pdf, mp3 and/or mp4 files. Acquire relevant metadata surrounding the files.

2) Apply metadata information to metadata template provided for CollectionBuilder (https://docs.google.com/spreadsheets/d/14iWUEoAJ6T9WDqlPnIHRN7M8-YgmMV4_bjFPVuSZ0yk/edit?usp=sharing) 

	* Note: Can automate process through coding 

3) Import the CollectionBuilder repository 

	1) Find repository at https://github.com/CollectionBuilder/collectionbuilder-gh 

	2) Click on 'Clone or download' 

	3) Click 'Clone with HTTPS' copy to clipboard icon 

	4) Under the + sign on the top right corner of the screen, press 'Import repository' 

	5) Paste URL into 'Your old repository's clone URL' 

	6) Name, then begin import 

4) Upload the files to the "objects" directory 

5) Upload the csv file of metadata to _data directory 

6) Go back to root directory and find _config.yml file 

	* Edit the file according to the specifications recorded in file 

7) Navigate to the _data directory from the root branch and open theme.yml 

	* Work through file and edit according to specifications

	* Note: be sure to edit the name beside the 'metadata' tag to the name of your csv file that contains your metadata 

8) Publish digital collection through master branch 

9) Continue to edit theme/csv files until the website fits specifications 

## Conclusion
CollectionBuilder is a very easy-to-use and intuitive tool. It allows for visualization of the connections between objects within a collection, such as location and time period. Furthermore, all that it requires from the user is a free to creat Github account.
