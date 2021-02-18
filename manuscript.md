---
title: 'The Trich of the matter: Temporary title for Trichinella spiralis project'
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2021-02-18'
author-meta:
- Mainul Hogue
- Patricia Soteropoulos
- Mark Siracusa
- Alexander Lemenze
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="The Trich of the matter: Temporary title for Trichinella spiralis project" />
  <meta name="citation_title" content="The Trich of the matter: Temporary title for Trichinella spiralis project" />
  <meta property="og:title" content="The Trich of the matter: Temporary title for Trichinella spiralis project" />
  <meta property="twitter:title" content="The Trich of the matter: Temporary title for Trichinella spiralis project" />
  <meta name="dc.date" content="2021-02-18" />
  <meta name="citation_publication_date" content="2021-02-18" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Mainul Hogue" />
  <meta name="citation_author_institution" content="Genomics Core, Rutgers University- New Jersey Medical School" />
  <meta name="citation_author" content="Patricia Soteropoulos" />
  <meta name="citation_author_institution" content="Genomics Core, Rutgers University- New Jersey Medical School" />
  <meta name="citation_author" content="Mark Siracusa" />
  <meta name="citation_author_institution" content="Department of Medicine, Rutgers University- New Jersey Medical School" />
  <meta name="citation_author_institution" content="Center for Immunity and Inflammation, Rutgers University- New Jersey Medical School" />
  <meta name="citation_author" content="Alexander Lemenze" />
  <meta name="citation_author_institution" content="Molecular and Genomics Informatics Core, Rutgers University- New Jersey Medical School" />
  <meta name="citation_author_institution" content="Department of Pathology, Immunology, and Laboratory Medicine, Rutgers University- New Jersey Medical School" />
  <meta name="citation_author_institution" content="Center for Immunity and Inflammation, Rutgers University- New Jersey Medical School" />
  <meta name="citation_author_orcid" content="0000-0003-3053-0849" />
  <link rel="canonical" href="https://alemenze.github.io/MaGIC-Trich/" />
  <meta property="og:url" content="https://alemenze.github.io/MaGIC-Trich/" />
  <meta property="twitter:url" content="https://alemenze.github.io/MaGIC-Trich/" />
  <meta name="citation_fulltext_html_url" content="https://alemenze.github.io/MaGIC-Trich/" />
  <meta name="citation_pdf_url" content="https://alemenze.github.io/MaGIC-Trich/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://alemenze.github.io/MaGIC-Trich/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://alemenze.github.io/MaGIC-Trich/v/22d975dbb39559df5ab5957870c0da199e049c3c/" />
  <meta name="manubot_html_url_versioned" content="https://alemenze.github.io/MaGIC-Trich/v/22d975dbb39559df5ab5957870c0da199e049c3c/" />
  <meta name="manubot_pdf_url_versioned" content="https://alemenze.github.io/MaGIC-Trich/v/22d975dbb39559df5ab5957870c0da199e049c3c/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://alemenze.github.io/MaGIC-Trich/v/22d975dbb39559df5ab5957870c0da199e049c3c/))
was automatically generated
from [alemenze/MaGIC-Trich@22d975d](https://github.com/alemenze/MaGIC-Trich/tree/22d975dbb39559df5ab5957870c0da199e049c3c)
on February 18, 2021.
</em></small>

## Authors



+ **Mainul Hogue**<br><br>
  <small>
     Genomics Core, Rutgers University- New Jersey Medical School
  </small>

+ **Patricia Soteropoulos**<br><br>
  <small>
     Genomics Core, Rutgers University- New Jersey Medical School
  </small>

+ **Mark Siracusa**<br><br>
  <small>
     Department of Medicine, Rutgers University- New Jersey Medical School; Center for Immunity and Inflammation, Rutgers University- New Jersey Medical School
  </small>

+ **Alexander Lemenze**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0003-3053-0849](https://orcid.org/0000-0003-3053-0849)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [alemenze](https://github.com/alemenze)<br>
  <small>
     Molecular and Genomics Informatics Core, Rutgers University- New Jersey Medical School; Department of Pathology, Immunology, and Laboratory Medicine, Rutgers University- New Jersey Medical School; Center for Immunity and Inflammation, Rutgers University- New Jersey Medical School
  </small>



## Abstract {.page_break_before}




## Introduction {.page_break_before}




## De Novo Genome Assembly {.page_break_before}

### Premise:
Currently the best genome assemblies for *Trichinella spiralis* are at ~98% complete depending upon the species, mostly using Illumina and a few used PacBio RSII (ick). We plan to use Oxford Nanopore for ultra long reads assembly to further complete the genome, possibly incorporate some Illumina for hybrid correction. 

- Also look at methlyation of ONT reads?

### Target information
- Genome size: ~50-65Mb
- 3 Chromosomes

One flowcell would generate ~100-200X coverage raw. 

### Protocols
#### Extraction/Size selection
Recent PacBio paper [@10.1038/s42003-021-01650-z] simply used phenol/chloroform extraction followed by Covaris G-tube.
Previous papers [@10.1038/ncomms10513;@10.1038/ng.769] for Illumina sequencing appear to use classic Qiagen or phenol/chloroform as well. 

**Requires >2ug HMW DNA**

## De Novo Transcriptome {.page_break_before}

### Premise:
Annotation of genes can be done in several ways- one of which is pure computational prediction. Since *T. spiralis* is eukaryotic- we cant exclude alternative splicing playing a role here as well, which Im not sure anyone else has looked at yet. Nanopore direct RNA-sequencing will capture spliceforms and improve genome annotation. 

### Target information
- 15k-20k genes/transcripts per genome
- Primarily should be polyA+

Go after non-polyA too?

### Protocols
#### Extraction/Size selection
TBD polyA tagging of non-polyA RNAs.
**Requires >500ng polyA+ RNA for direct nanopore sequencing**


## Vesicle RNA {.page_break_before}

### Premise:
The crux of this project- *T. spiralis* transcripts have been found in vesicles, leading to immune modulation and neuronal alterations. Believed to be to benefit the worm, but also providing benefits to autoimmune and neurodegradation disorders. By using the stronger genome/transcriptome, we can try to identify the collection of transcripts in vesicles. 

### Target information


### Protocols
#### Extraction/Size selection
TBD polyA tagging of non-polyA RNAs.
**Requires >500ng polyA+ RNA for direct nanopore sequencing**


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
