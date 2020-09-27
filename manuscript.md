---
author-meta:
- John Doe
- Jane Roe
bibliography:
- content/manual-references.json
date-meta: '2020-09-27'
header-includes: '<!--

  Manubot generated metadata rendered from header-includes-template.html.

  Suggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html

  -->

  <meta name="dc.format" content="text/html" />

  <meta name="dc.title" content="Manuscript Title" />

  <meta name="citation_title" content="Manuscript Title" />

  <meta property="og:title" content="Manuscript Title" />

  <meta property="twitter:title" content="Manuscript Title" />

  <meta name="dc.date" content="2020-09-27" />

  <meta name="citation_publication_date" content="2020-09-27" />

  <meta name="dc.language" content="en-US" />

  <meta name="citation_language" content="en-US" />

  <meta name="dc.relation.ispartof" content="Manubot" />

  <meta name="dc.publisher" content="Manubot" />

  <meta name="citation_journal_title" content="Manubot" />

  <meta name="citation_technical_report_institution" content="Manubot" />

  <meta name="citation_author" content="John Doe" />

  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />

  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />

  <meta name="twitter:creator" content="@johndoe" />

  <meta name="citation_author" content="Jane Roe" />

  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />

  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />

  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />

  <link rel="canonical" href="https://lubianat.github.io/codigobonito/" />

  <meta property="og:url" content="https://lubianat.github.io/codigobonito/" />

  <meta property="twitter:url" content="https://lubianat.github.io/codigobonito/" />

  <meta name="citation_fulltext_html_url" content="https://lubianat.github.io/codigobonito/" />

  <meta name="citation_pdf_url" content="https://lubianat.github.io/codigobonito/manuscript.pdf" />

  <link rel="alternate" type="application/pdf" href="https://lubianat.github.io/codigobonito/manuscript.pdf" />

  <link rel="alternate" type="text/html" href="https://lubianat.github.io/codigobonito/v/c20d5476a55ce0e365ff4b21fb7e9c548f6fdf5d/" />

  <meta name="manubot_html_url_versioned" content="https://lubianat.github.io/codigobonito/v/c20d5476a55ce0e365ff4b21fb7e9c548f6fdf5d/" />

  <meta name="manubot_pdf_url_versioned" content="https://lubianat.github.io/codigobonito/v/c20d5476a55ce0e365ff4b21fb7e9c548f6fdf5d/manuscript.pdf" />

  <meta property="og:type" content="article" />

  <meta property="twitter:card" content="summary_large_image" />

  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />

  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />

  <meta name="theme-color" content="#ad1457" />

  <!-- end Manubot generated metadata -->'
keywords:
- markdown
- publishing
- manubot
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: Manuscript Title
...






<small><em>
This manuscript
([permalink](https://lubianat.github.io/codigobonito/v/c20d5476a55ce0e365ff4b21fb7e9c548f6fdf5d/))
was automatically generated
from [lubianat/codigobonito@c20d547](https://github.com/lubianat/codigobonito/tree/c20d5476a55ce0e365ff4b21fb7e9c548f6fdf5d)
on September 27, 2020.
</em></small>

## Authors



+ **John Doe**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [johndoe](https://twitter.com/johndoe)<br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Jane Roe**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [janeroe](https://github.com/janeroe)<br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>



## Abstract {.page_break_before}




# Reunião 24/09/2020

## A Quick Guide to Organizing Computational Biology Projects
[@doi:10.1371/journal.pcbi.1000424]

### Highlights
Curriculum fails to address many of the day-to-day organizational challenges

Someone unfamiliar with your project should be able to look at your computer files and understand in detail what you did and why.
Everything you do, you will probably have to do over again.

data directory for storing fixed data sets, a results directory for tracking computational experiments peformed on that data, a doc directory with one subdirectory per manuscript, and directories such as src for source code 

In parallel with this chronological directory structure, I find it useful to maintain a chronologically organized lab notebook.
In practice, I ask members of my research group to put their lab notebooks online, behind password protection if necessary.

driver script (I usually call this runall) that carries out the entire experiment automatically

Avoid editing intermediate files by hand. Doing so means that your script will only be semi-automatic
Use relative pathnames to access other files within the same project

Even in a simple script, you should check for bogus parameters, invalid input, etc.

how much effort to put into software engineering
### Comments

It goes on to a lot of personal notes, which are okay, but far from statndard.
GitHub logs work well. 


# Template

## Ten Simple Rules for Effective Computational Research
[@doi:10.1371/journal.pcbi.1003506]

### Highlights
the present guide is aimed specifically at the vast majority of scientific researchers: those without formal training in computer science.
conduct a software literature review to ascertain what software is available.

The program code itself can be made more understandable by using meaningful variable names and formatting the code consistently.
 you should maintain a record of the “big picture” functionality (i.e., interconnectivity of components and input/output formats)
 keep a record of your work

 all scientists could be better educated in design, so any investment will be rewarded

 Simple tests that the software behaviour matches expectations are essential for ensuring robust results.
Get the computer to run tests for you automatically and alert you to problems, using a suitable testing framework.

 we advocate an open approach of sharing source code, data, and results as freely as possible.
 
prioritise in a way that suits you and your projects and career aspirations



### Comments
Gostei mais que o outro. 
Lista de links ao fim é interessante.

## Ten Simple Rules for Taking Advantage of Git and GitHub
[@doi:10.1371/journal.pcbi.1004947]

### Highlights
It provides developers and researchers with a dynamic and collaborative environment, often referred to as a social coding platform, that supports peer review, commenting, and discussion [7]
GitHub hooks can be used to automate numerous tasks to help improve the overall quality of your project

GitHub now integrates with archiving services such as Zenodo and Figshare, enabling DOIs to be assigned to code repositories.

### Comments



# Template

## Title
[@doi:]

### Highlights

### Comments

## Ten Simple Rules for a Bioinformatics Journal Club

[@doi:10.1371/journal.pcbi.1004526]

### Highlights
Don’t be a “lonely bioinformatician”[1], create a journal club

We recommend you find a time that is typically free for the majority and suits both students and early career researchers, who may have time commitments during “normal” working hours. For us, that time was 8 A.M.

--> Claramente nao sao brasileiros. 

a self-selection bias that we can live with.

ruled out formal presentations with PowerPoint slides.

for every paper, there will be someone who knows nothing about the topic and others who are near-experts

open membership approach and encourage attendance from different cohorts. Mixing research students, coursework students, and early career researchers

We have discussed overcoming procrastination, writing more effectively, online learning, editing Wikipedia, student groups, Software Carpentry, document preparation systems for sci- ence, and even the PLOS Ten Simple Rules collection itself

Although we didn’t originally envisage journal club as a platform for collaborations, we’ve found that meeting regularly to write amongst a group ofsupportive peers has led to a publica- tion, with a style that suits the informal atmosphere of the club.

Keep the barrier to entry low.

### Comments

o cdb eh um grupo de estudo

# Template

## Ten simple rules to increase computational skills among biologists with Code Clubs
[@doi:10.1371/journal.pcbi.1008119]

### Highlights
participants need regular opportunities to engage in repeated deliberate practice that encourage them to practice their retrieval and application of the material

Initially, the Code Club was used to review code from trainee projects. Instead ofa presentation, the presenter would project their code onto a screen and the participants would go through the code, stating the logic behind each line.

someone may have an R script with a repeating chunk ofcode. The chal- lenge for the session would be to convert the code chunk into a function to be called through- out the script to make it “DRY” (i.e., Don’t Repeat Yourself [12]). The presenter leaves the session with several partial or working solutions to their problem, and the importance ofwrit- ing DRY code is reinforced.

We generally find that preparing a Code Club session takes similar effort to preparing a Journal Club presentation
“think-pair-share” approach.

It is critical that the presenter and participants respect each other and that a designated indi- vidual (e.g., the lab director) enforces a code of conduct.

After the Code Club, try to incorporate that material into new code or refactor old code.

Set specific goals.

A typical schedule for Code Club is 10 minutes ofintroduction and instruction, 30 minutes ofpaired program- ming, 5 minutes to get groups to wrap up, and 10 minutes to report back to the group.

Using GitHub repositories for each Code Club can help make information, scripts, and data easily available to participants.

Perhaps a first Code Club could introduce using git and GitHub to engage in collaborative coding.

Central to the Code Club format is the use ofpaired programming.

Regardless ofhow partners are selected, consider asking the pairs to identify a navigator and a driver [16]
### Comments
Table 1. Examples of successful Code Club topics. !! This is RICH.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
