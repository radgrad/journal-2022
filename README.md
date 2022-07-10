# RadGrad 2022 Journal Article

## To Do

Next Steps:
* Calculate Inter-rater reliability
* Findings section
  * New Students 
    * Descriptive Statistics on Essays
    * Coding results
      * Inter-rater reliability.
      * Coding Categories.
      * Results by category, including quotes.
    * Behavioral instrumentation
  * Graduating students
    * Descriptive statistics on questionnaire answers.
    * Example comments
  * Repeat for Faculty, Advisors

* Discussion section
  * 111 students aren't necessarily CS majors, which could account for large numbers of Level 1.

Related work
  * Integrate other paper citations
  * Cal NERDS

Re-code more ratings:
* https://www.radgrad.org/docs/evaluation/overview
* ICS 111, F21 (Philip, *Cam)
* ICS 111, S22  (Cam, Philip)
* ICS 211 S22 (Seungoh, Philip)
* ICS 314 F21 (Peter, Philip)
* ICS 314 S22 (Philip, *Cam)

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
