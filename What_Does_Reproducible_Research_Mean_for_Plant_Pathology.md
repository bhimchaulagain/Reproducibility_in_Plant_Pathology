# What Does Reproducible Research Mean for Plant Pathology?
A. H. Sparks, E. M. Del Ponte, N. J. Grünwald, and Z. Foster  
`r Sys.Date()`  


1. Adam H. Sparks: Centre for Crop Health, University of Southern Queensland, 
Toowoomba, Qld 4350, Australia
2. Emerson M. Del Ponte: Universidade Federal de Viçosa, Viçosa, MG, Brasil
3. Niklaus J. Grünwald: Horticultural Crops Research Laboratory, USDA
Agricultural Research Service, Corvallis, OR 97330, USA
4. Zachary Foster: Horticultural Crops Research Laboratory, USDA Agricultural
Research Service, Corvallis, OR 97330, USA

# ABSTRACT

Abstracts are mandatory and limited to one 200 word paragraph.

# MAIN TEXT
Reproductibility and replicability in scientific research have once again been
highlighted recently [@Nature_Editorial_2016; @Baker2016a] as an issue.

Patil et al. [-@Patil066803] have provided several definitions to clarify the
concepts surrounding reproducibility and replicability. For the purposes of this
paper we follow the definitions as given by Patil et al. [-@Patil066803].

* Why reproducible research

## BEST METHODS FOR REPRODUCIBLE RESEARCH
* Provide definitions (provide defintions for terms used so it's clear)
* Data
  * Data formatting (flat files; use Comma Chameleon, Table Tool, others?)
  * Data storage (don't edit raw data files; use file permissions to prevent changes to raw data files, use data bases where possible and appropriate; etc.)
* When publishing
  * Provide data
  * Provide code
* Using GitHub for code (and small data?)
* Using Figshare or Zenodo vs a lab website (DOIs, other reasons)

## WHAT IS THE STATE OF REPRODUCIBLE RESEARCH IN PLANT PATHOLOGY?
* Madden et al. [-@Madden2015] supply an *e-**X**tra*\* with repoducible examples
for readers.
* Duku et al. [-@Duku2016] provide models, data and code, (http://adamhsparks.github.io/MICCORDEA/) necessary to
replicate the entire study modelling the effects of climate change on rice
bacterial blight and rice leaf blast in Tanzania.
* Sparks et al. [-@Sparks2011; -@Sparks2014] provide models, data and code, (http://adamhsparks.github.io/Global-Late-Blight-MetaModelling/)
necessary to replicate model development and the subsequent the study on the effects of climate change on potato late blight.
* Del Ponte provides data and a reproducible report that explan in details all steps of the analysis and the R codes for conducting a meta-analysis for assessing heterogeneity in relationship between white mold incidence and soybean yield and between incidence and soybean yied.
* Other examples from plant pathology providing e-Xtras or supplemental material

## RANDOM SAMPLING OF ARTICLES FROM THE TOP 20 PLANT PATHOLOGY JOURNALS
The top 20 plant pathology discipline journals as ranked by Google Scholar, https://scholar.google.com/ (accessed 05 Dec. 2016), were used to create a database of journals from which to randomly select articles for inspection. One hundred articles were randomly selected from 2012 to 2016 from a list of randomly selected start pages assigned to a randomised list of the 20 journals [@Sparks2017]. The start pages list was numbered from page one and went to 150. This was done since some journals restart their numbering with each issue and also ensures that the journal is more likely to have a page number corresponding to the randomly generated value. This also assumes that there is no effect or bias on reproducibility based on the time of year that an article was published, since most journals start with page number one at the beginning of the year.

The list of journals was saved as a comma separated value (CSV) file and imported into R [@R2016]. 

## DISCUSSION

## ACKOWLEDGEMENTS

### LITERATURE CITED
