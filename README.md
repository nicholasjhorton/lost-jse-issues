# lost-jse-issues
Repository for the retrieval and curation of the lost Journal of Statistics Education (now JSDSE) volumes 7 (1999) and 8 (2000)

## link

Great news! Tim Gill to the rescue!  See https://web.archive.org/web/20130307010900/http://www.amstat.org/publications/jse/jse_archive.htm
Ron


## thoughts from Wednesday, October 27, 2021

Nick populated a sample paper that's in the Taylor and Francis system (see `sample_taylor_francis_paper`).

Nick also populated a sample paper that's not (see `sample_lost_paper`)

Finally, Nick downloaded the abstracts for the two missing volumes

Nick's speculation:

- the pdf of the html contains most information and will be straightforward to curate
- the metadata is most important to put into a form that is accessible
  - title
  - author information (each author and affiliation)
  - volume
  - issue
  - abstract

Proposal: grab pdf and html of the archived html from Wayback machine and save in:

- papers/firstauthor_X_Y.pdf  where X is volume and Y is issue
- papers/firstauthor_X_Y.html  where X is volume and Y is issue
- add metadata to a Googlesheet which will eventually end up here.
  - link to Googlesheet https://docs.google.com/spreadsheets/d/1MGvhHoNrxp3xxfhu7CHUdmxVMPAU1wvLUNY3DNldDvg/edit#gid=0



Issues to be thinking about

- what if there are other links outside the paper?  need to flag these (paper plus page number from the pdf?)
- did we miss anything?
- did Nick somehow mess up the Google sheet?
