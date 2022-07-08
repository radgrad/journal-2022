# RadGrad 2022 Journal Article

## To Do
Related work
  * Integrate other paper citations
  * Cal NERDS

Re-code more ratings:
* https://www.radgrad.org/docs/evaluation/overview
* ICS 111, F21 (Philip, *Cam)
* ICS 111, S22  (Cam, Philip)
* ICS 211 S22 (Seungoh, Philip)
* ICS 314 F21 (Peter, *Philip)
* ICS 314 S22 (Philip, *Cam)

Findings

Early Stage Students
  * Descriptive statistics on essays: total words, average per essay, min, max, standard deviation.
  * Descriptive statistics on coding categories
  * Data excerpts for each category

Other stakeholders
  * Descriptive statistics
  * Excerpts

Discussion

Review submission guidelines: 
  * anonymization: https://dl.acm.org/journal/toce/author-guidelines
  * Page limit: 15-25

Improve behavioral instrumentation, redeploy.


111 students aren't necessarily CS majors, which could account for large numbers of Level 1.

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
