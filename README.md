# RadGrad 2022 Journal Article

Discussion
  * Revisit the theory of change.

Behavioral instrumentation?

Related work:
  * Integrate other paper citations
  * Cal NERDS

Review submission guidelines: 
  * anonymization: https://dl.acm.org/journal/toce/author-guidelines
  * Remove authors!


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
