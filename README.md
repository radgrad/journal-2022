# RadGrad 2022 Journal Article

## To Do

Discussion
  * Revisit the research questions.
  * Revisit the theory of change.
  * Revisit the curriculum vs. volunteer thing from beginning.

Future directions

Behavioral instrumentation

Directions to PIs
* Paper
* Template
* Need refs

Discussion section
  * 111 students aren't necessarily CS majors, which could account for large numbers of Level 1.

Related work
  * Integrate other paper citations
  * Cal NERDS

Review submission guidelines: 
  * anonymization: https://dl.acm.org/journal/toce/author-guidelines
  * Page limit: 15-25

## Image conversion

```
convert -monochrome wodcard.jpg -resize 35% wodcard.eps
convert dora.png dora.eps

cd images; convert radgrad-workflow.png radgrad-workflow.eps; cd ..   
```

## Fixing "sed RE error: illegal byte sequence" problem

```
export LANG=C
```
