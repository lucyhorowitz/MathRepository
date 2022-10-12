# MathRepository
 
This repository contains my notes from my (ongoing) undergraduate math studies at the University of Chicago. They consist of largely atomic definitions, results, and a few examples. 

## The Notes

The notes are connected by Obsidian's markdown links. I have tried to be as dense as possible, linking to every definition and every result used/stated/cited in any given note. 

### Courses
- MATH 20700 = Honors Analysis in R^n I — Fall 2020 (functional analysis, linear algebra) (Fall 2020)
- MATH 20800 = Honors Analysis in R^n II — Winter 2021 (analysis on manifolds) (Winter 2021)
- MATH 20900 = Honors Analysis in R^n III — Spring 2021 (measure theory)
- MATH 25700 = Honors Basic Algebra I — Fall 2021 (group theory)
- MATH 25800 = Honors Basic Algebra II — Winter 2022(ring theory)
- MATH 26700 = Intro. to Representation Theory of Finite Groups — Winter 2022
- MATH 27700 = Mathematical Logic I — Fall 2022 (cardinals, first-order logic, ...)
- MATH 29501 = Harmonic Analysis on p-Adic Fields — Paris, Spring 2022
— MATH 29512 = Introduction to p-Groups — Paris, Spring 2022
- MATH 32500 = Graduate Algebra I — Fall 2022 (representation theory)
- MATH 36100 = Proseminar in Topology — Fall 2021-present (a combination of notes from a personal project that stemmed from the seminar as a sort of reading course)
- UChicago REU 2021 — Summer 2021 (notes that helped me write my [paper](http://math.uchicago.edu/~may/REU2021/REUPapers/Horowitz.pdf) on the Poincaré group)

### Images

Unfortunately, Obsidian's LaTeX support is limited to stuff that is built-in, so I can't use any packages. Therefore most of the files in the images folder are screenshots of commutative diagrams I typeset elsewhere. 

### Theorems

Sometimes the theorems have proofs associated with them, but in a lot of cases I did not have time to copy proofs from my hand-written notes. These theorem notes are marked with #write_proof in the hopes that I will someday sit down and write the proofs. This definitely makes the linking less dense than I would like, so sometimes when I am typing my notes I will link to definitions and results used in the proof without actually writing the proof to help boost link density. 

## spaCy

I have run spaCy v3.4 on the definitions and put the results into CoNLL-U format so that once I figure out how, I can run some analyses on this to help make NLP better for math. 

### Cleaning up

The notes are Markdown math notes so naturally they include Markdown and a *lot* of LaTeX. I removed certain symbols (pipes, dollar signs, brackets, octothorpes, newlines, backslashes) and words/phrases that generally do not make up the content of the notes (metadata, links, font names). The code I used to do this can be found under [non-note files](https://github.com/lucyhorowitz/MathRepository/tree/main/non-note%20files) as [trimmper.ipnyb](https://github.com/lucyhorowitz/MathRepository/blob/main/non-note%20files/trimmer.ipynb). The result of this can be found in the same folder as [conll.txt](https://github.com/lucyhorowitz/MathRepository/blob/main/non-note%20files/conll.txt).
