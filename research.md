---
layout: page
title: Research 
---

We are the Birol Labs, a group invested in genome research. Our informatics lab develops computational technologies that enable the analysis of genomic data at unprecedented scale and resolution, while our wet lab explores novel biologics and host defence molecules to address antimicrobial resistance and infectious disease.

Our research lies at the intersection of biology, computer science, and artificial intelligence, where we create algorithms, software, and analytical frameworks for genome assembly, comparative genomics, ancestry inference, population genetics, and clinical genomics.

By transforming massive sequencing datasets into biological knowledge, we seek to advance our understanding of genome structure, evolution, diversity, and disease. Our work supports a wide range of applications, from biodiversity monitoring and forest genomics to precision medicine and the development of ancestry-aware genomic technologies. Through both methodological innovation and collaborative research, we aim to expand the capabilities of modern genomics and make advanced genomic analyses accessible to the broader scientific community.

Below is an overview of our key research activities.

#### **Funding**

The lab's current flagship research program (2025–2030) is supported through a [CIHR-funded project](https://webapps.cihr-irsc.gc.ca/decisions/p/project_details.html?applId=524284&lang=en) focused on sequence-based ancestry inference, large-scale multi-genome synteny detection, and interactive visualization technologies for precision medicine applications. Le principal programme de recherche actuel du laboratoire (2025–2030) est soutenu par un [projet financé par les IRSC](https://webapps.cihr-irsc.gc.ca/decisions/p/project_details.html?applId=524284&lang=fr) portant sur l’inférence de l’ascendance génomique à partir des données de séquençage, la détection de synténie à grande échelle entre multiples génomes et le développement d’outils de visualisation interactive pour la médecine de précision.

We currently receive additional funding from NSERC. Le laboratoire bénéficie également d'un financement du Conseil de recherches en sciences naturelles et en génie du Canada (CRSNG). 

[![](/assets/logos/cihr-logo.png)](https://webapps.cihr-irsc.gc.ca/decisions/p/project_details.html?applId=524284&lang=en)
<br>
[![](assets/logos/nserc-logo.png)](https://www.nserc-crsng.gc.ca/)
<br>

#### **Fundamental Bioinformatics: Algorithms and Data Structures**

Bioinformatics is a *big data* science. With the continual improvements in high-throughput DNA and RNA sequencing, scalable algorithms and data structures are essential to underpin the bioinformatics tools needed to analyze this immense data. To support and facilitate the development of these bioinformatics tools, we develop advanced, efficient data structures, [common code libraries](https://github.com/birollab/btllib) and algorithms for storing, hashing and processing ‘omics data.  


#### **Genome, Transcriptome and Epigenome Assembly and Analysis**

The many revolutionary improvements to sequencing technologies have made data generation accessible to labs big and small. Yet, deciphering the precise nucleotide sequence that makes up the genome, transcriptome and epigenomes of a species – *de novo* assembly – remains an informatics challenge, especially when the genome is large and complex. Beginning with [ABySS](https://doi.org/10.1101/gr.089532.108)/[ABySS2](https://doi.org/10.1101/gr.214346.116), the first short-read assembler to scale to human-sized genomes, and more recently [GoldRush](https://doi.org/10.1038/s41467-023-38716-x), a linear time complexity genome assembler for long sequencing reads, the lab has an established track record in developing scalable and high-quality assembly tools. We develop [open-source solutions](https://github.com/birollab) for [all steps of the assembly workflow](https://www.birollab.ca/resources), including the initial assembly of reads, correction, scaffolding, polishing, and gap-filling. 


#### **Comparative Genomics**

As sequencing technologies and assembly algorithms mature, the diversity of available complete, chromosome-scale genome assemblies is expanding rapidly across the tree of life. These resources provide unprecedented opportunities to study genome evolution, structural variation, adaptation, and the genetic basis of phenotypic diversity within and between species. Realizing the full potential of these data requires computational approaches capable of comparing not just pairs of genomes, but increasingly large collections of genomes simultaneously.

Our lab develops [scalable comparative genomics technologies](https://github.com/birollab/ntsynt) for analyzing genome structure and organization across diverse species. Our work includes methods for whole-genome alignment, [synteny detection](https://doi.org/10.1186/s12915-025-02455-w), structural variation discovery, pangenome analysis, and [comparative visualization](https://github.com/birollab/ntsynt-viz). By identifying conserved and rearranged genomic regions, these approaches help reveal evolutionary relationships, characterize genome architecture, and uncover genetic changes associated with important biological traits.

A major focus of our current research is the development of efficient algorithms for multi-genome synteny analysis. Traditional approaches often rely on pairwise genome comparisons, limiting their ability to capture complex patterns across large collections of assemblies. We are developing methods that can identify, quantify, and visualize syntenic relationships across hundreds of genomes simultaneously, enabling researchers to explore structural variation and genome evolution at population and species scales. These technologies support applications ranging from evolutionary biology and biodiversity studies to clinical genomics and precision medicine.

#### **Genomic Ancestry and Population Genomics**

Human genomes contain a rich record of ancestral origins, demographic history, and population relationships. Accurate characterization of genomic ancestry is increasingly important in biomedical research and precision medicine, where ancestry can influence disease risk prediction, variant interpretation, and the selection of appropriate reference genomes for genomic analyses. However, existing methods often struggle with increasingly diverse datasets, admixed populations, and the growing scale of modern sequencing studies.

We develop computational methods for ancestry inference directly from genomic sequencing data. [Our research](https://doi.org/10.1093/bioadv/vbaf287) focuses on creating scalable, accurate, and platform-independent approaches that can characterize both global and local ancestry across the genome. These methods. which include the [ntRoot framework](https://github.com/birollab/ntroot) are designed to work with diverse populations and complex admixture patterns, providing a more complete representation of genetic diversity than traditional categorical ancestry assignments.

In addition to ancestry inference, we develop statistical and [visualization frameworks](/viz/TyrHardEk45.report.html) that help researchers and clinicians interpret ancestry-related patterns of genetic variation. These tools support population genetic studies, facilitate ancestry-aware genomic analyses, and improve the selection of reference genomes and comparative resources for downstream analyses. By making these technologies openly available, we aim to advance equitable and inclusive genomics research and help ensure that genomic medicine benefits individuals from all ancestral backgrounds.

<div style="max-width:900px; margin: 2rem auto; border:1px solid #ddd; border-radius:6px; overflow:hidden;">
    <iframe
        src="/viz/TyrHardEk45.report.html"
        style="
            width:100%;
            height:360px;
            border:none;
            transform: translateY(-1px);
        ">
    </iframe>
</div>
<p style="text-align:center; margin-top:0.5rem;">
<a href="/viz/TyrHardEk45.report.html" target="_blank">Open interactive visualization in a new tab</a>
</p>

Our ancestry research is closely integrated with our work in comparative genomics and multi-genome analysis. Together, these efforts provide a foundation for understanding how genomic variation is distributed across populations, how genome structure differs among individuals, and how this diversity influences human health and disease.


#### **Antimicrobial Research & Technology**

Bacteria can rapidly evolve to develop resistance to antibiotics, presenting a growing and very dangerous problem. In a “post-antibiotic era”, bacterial diseases would once again be untreatable, and many standard treatments, including surgical operations, could become unusable. To boost the search for new treatment options, we focus on short proteins called antimicrobial peptides (AMPs), which are produced naturally by various animal and plant species. These host defence proteins can protect against infection, or reduce the harm caused by an existing infection.


#### **Environmental Genomics**

The [iTrackDNA project](https://itrackdna.ca/) utilizes advanced DNA tracking technology to monitor and trace various species in the environment. It aims to enhance conservation efforts by providing detailed insights into wildlife movements and population dynamics. By analyzing DNA samples from environmental sources, such as water and soil, iTrackDNA enables efficient and non-invasive biodiversity monitoring. Integral to the project, we develop bioinformatics technologies to help characterize environmental DNA and identify unique regions and/or conserved regions within individual species genomes. This research aims to develop specific eDNA assays, enhancing the project's ability to identify and track target species within diverse ecosystems. Through this integration of bioinformatics, iTrackDNA strengthens its capacity for precise biodiversity monitoring and conservation efforts.


#### **Clinical Genomics**

Substantial advancements in healthcare can be realized through the development of genomics technologies to detect variations, sequence repeats and mutations in DNA and RNA in a manner that allows: i) effective preventative care, and/or ii) efficient diagnosis and treatment. One technology that enables this vision is high throughput DNA and RNA sequencing. This requires thorough and streamlined downstream data analysis and interpretation. To address this challenge, we are building and validating bioinformatics frameworks for clinical genomics. In collaborative projects, we are deploying these solutions for clinical research, including [COVID-19](https://genomecanada.ca/challenge-areas/cancogen/), cancer research and for diagnosing rare genetic diseases.


#### **Forest Genomics & Beyond**

Conifers in general and spruce trees in particular are Canada’s most significant forest resource. Spruces produce high quality wood and fibre that is widely used in the industry, and as dominant species of Canada’s forests, they provide essential local and global ecosystem services. As part of the [spruce-up](https://spruce-up.ca/) project and in collaboration with multiple organizations that includes [CGEn](https://www.cgen.ca/), [CanSeq150](https://www.cgen.ca/canseq150-overview), the [Canada BioGenome](https://earthbiogenome.ca/index.mhtml) and [Earth BioGenome](https://www.earthbiogenome.org/) projects, we are building genomic resources and technologies to help protect our forests and preserve their biodiversity for future generations.

