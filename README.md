# RadGrad 2022 Journal Article

Discussion
  * Revisit the theory of change.

Behavioral instrumentation?

Related work:
  * Integrate other paper citations
  * Cal NERDS
  * Something I saw along the way mentioned the goal of fostering "communities of practice". This is difficult to do just by making a technological tool like RadGrad. If you want to takle this Wenger's 1998 book is a great theoretical read, but you might find practical ideas in some chapters of Wenger, E., McDermott, R. A., & Snyder, W. (2002). Cultivating Communities of Practice: A Guide to Managing Knowledge. Boston, Mass.: Harvard Business School Press. (written for industry) or in Wenger, E., White, N., & Smith, J. D. (2009). Digital Habitats: Stewarding Technology for Communities. Portland, OR: CPsquare.

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
