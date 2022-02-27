# Beyond Systematic and Unsystematic Responding: Latent Class Mixture Models to Characterize Response Patterns in Discounting Research

## Abstract

Operant behavioral economic methods are increasingly used in basic research on the efficacy of reinforcers as well as in large-scale applied research (e.g., evaluation of empirical public policy). Various methods and strategies have been put forward to assist discounting researchers in conducting large-scale research and detecting irregular response patterns. Although rule-based approaches are based on well-established behavioral patterns, these methods for screening discounting data make assumptions about decision-making patterns that may not hold in all cases and across different types of choices. Without methods well-suited to the observed data, valid data could be omitted or invalid data could be included in study analyses, which subsequently affects study power, the precision of estimates, and the generality of effects. This review and demonstration explore existing approaches for characterizing discounting and presents a novel, data-driven approach based on Latent Class Analysis. This approach (Latent Class Mixed Modeling) characterizes longitudinal patterns of choice into classes, the goal of which is to classify groups of responders that differ characteristically from the overall sample of discounters. In the absence of responders whose behavior is characteristically distinct from the greater sample, modern approaches such as mixed-effects models are robust to less-systematic data series. This approach is discussed, demonstrated with a publicly available dataset, and reviewed as a potential supplement to existing methods for inspecting and screening discounting data.

## Instructions for Repository

This repository features the RMarkdown code necessary to reconstruct the analyses and results of an exploration of Latent Class Mixture Modeling (LCMM) for identifying aberrant responding on traditional discounting tasks. Specifically, LCMMs are run and then the resulting classes are contrasted against the critiera commonly used to screen for nonsystematic discounting data.

### Instructions for Obtaining Data

This repository and syntax will not run in the state in which it is downloaded. Specifically, the data to be analyzed must be obtained individually and individuals who wish to access these data must be apply for access at the following [location](https://db.humanconnectome.org/ "location"). Specifically, interested parties will need to access Level 2 access (with partial demographics available) for the "WU-Minn HCP Data - 1200 Subjects" dataset.

### Instructions for Running Analyses

The user will need to adjust the syntax to reference the data obtained from the site. In this current code, the file provided by the project was "unrestricted_shawnpgilroy_2_14_2021_10_59_54.csv". Naturally, this will need to be renamed in order to execute the code.

## Acknowledgements and Credits

* Shawn P. Gilroy, Louisiana State University

* Justin C. Strickland, Gideon P. Naudé, and Matthew W. Johnson, Behavioral Pharmacology Research Unit, Department of Psychiatry and Behavioral Sciences, Johns Hopkins

* Michael Amlung & Derek D. Reed, Department of Applied Behavioral Science, Cofrin Logan Center for Addiction Research and Treatment, University of Kansas
