---
layout: page
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial

  # Course details
       # "name" -> The acronym of the course
       # "about" -> The extended name of the course
       # "description" -> Short description of the course
  name: "CPANG18 - Computational PANGenomics"
  description: "Training Material aimed in the exploration of modern bioinformatic tools that allow researchers to use pangenomes as their reference system when engaging in studies of organisms of all types."

  # Keywords -> Consult EDAM:Topic
  keywords:  "http://edamontology.org/topic_0622"

  # Audience -> Following Elixir-Tess input
  audience: ["Academia/ Research Institution", "Industry", "Non-Profit Organisation"]

  # Author info
  author:
    - "@type": Organization
      name: "The Gulbenkian Training Programme in Bioinformatics"
      alternateName: "GTPB"
      sameAs: "gtpb.igc.gulbenkian.pt/bicourses/index.html"

  # predominant type of learning resources
  "learningResourceType": ["presentation", "exercise", "scripts", "handout"]

  # Contributor info
  contributor:
    - "@type": Person
      name: "Erik Garrison"
    - "@type": Person
      name: "Mikko Rautiainen"
    - "@type": Person
      name: "Jordan Eizenga"

  # License & Language & url
  license: https://creativecommons.org/licenses/by/4.0/
  inLanguage: "en-us"
  url: "https://gtpb.github.io/CPANG18/"
---


![CPANG18](/assets/Header.png)

## Course Description
Reference genomes have become central to bioinformatics approaches, and form the core of standard analyses using contemporary sequencing data. However, the use of linear reference genomes, which provide the sequence of one representative genome for a species, is increasingly becoming a limitation as the number of sequenced genomes grows. In particular, they tend to bias us away from the observation of variation in the genomes we study. A general solution to this problem is to use a pangenome that incorporates both sequence and variation from many individuals as our reference system. This pangenome is naturally modeled as a graph with annotations, and can provide all the functionality traditionally provided by linear reference genomes. Unlike linear reference genomes, a pangenome readily incorporates both small and large variation, allowing bias-free genotyping at known alleles. In this course we will explore the use of modern bioinformatic tools that allow researchers to use pangenomes as their reference system when engaging in studies of organisms of all types. Such techniques will aid any researcher working on organisms of high genetic diversity or on organisms lacking a high-quality reference genome. This course targets all researchers interested in learning about an exciting paradigm shift in computational genomics.

## Target Audience
This course is oriented towards biologists and bioinformaticians with at least an intermediate level of experience working with sequencing data formats and methods in the unix shell. The course will be of particular interest to researchers investigating organisms without a reference genome or populations featuring high levels of genetic diversity.

---

## Course Documentation
All the datasets used for this training course is available throughout the documentation.

<br/>

### Day 1
#### [Intro slides](assets/day1-intro.pdf) [PDF Download]
#### [Slides](assets/CPANG18_Computational_Pangenomics_2018_(day1).pdf) [PDF Download]
#### Practical 1: [toy examples](pages/toy_examples.md)

<br/>

### Day 2
#### [Slides](assets/Computational_Pangenomics_CPANG18-(day2).pdf) [PDF Download]
#### Practical 2: [HIV](pages/HIV_exercises.md)

<br/>

### Day 3
#### [Slides](assets/Computational_Pangenomics_CPANG18-(day3).pdf) [PDF Download]
#### Practical 3: [Bacteria](pages/bacteria.md)

<br/>

### Day 4
#### [Slides](assets/Computational_Pangenomics_CPANG18-(day4).pdf) [PDF Download]
#### [Practical overview](assets/Alignment_methods_for_graph_construction.pdf) [PDF Download]
#### [Theory slides](assets/Graph_genome_theory_slides.pdf) [PDF Download]
#### Practical 4: [MHC](pages/mhc.md)

---

### [Learning objectives](pages/learning_objective.md)

### [Instructors](pages/instructors.md)

---

The source for this course webpage is [on github](https://github.com/GTPB/CPANG18).

<br>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">CPANG18</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">GTPB</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
