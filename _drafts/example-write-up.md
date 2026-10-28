---
title: "[Project write-up title]"
summary: "[One line on the problem and the result]"
tldr: "[Two sentences: the question, what you built, and the main result.]"
math: true # loads MathJax; remove if the post has no equations
links:
  - name: paper
    url: "#"
  - name: code
    url: "#"
---

This is a template. Drafts in `_drafts/` are not published. To publish, move it to
`_posts/` and name it `YYYY-MM-DD-short-title.md`.

## Motivation

[What problem were you trying to solve, and why does it matter? Who else has worked on it?]

## Approach

[What you built or tried. Inline math like $\mathcal{L}(\theta)$ works, as do display equations:]

$$
\theta^{*} = \arg\min_\theta \; \mathbb{E}_{(x,y)}\big[\ell(f_\theta(x), y)\big]
$$

```python
loss = criterion(model(x), y)
loss.backward()
```

## Results

<figure>
  <!-- <img src="/assets/img/your-figure.png" alt="[Describe the figure]"> -->
  <div class="placeholder" style="height: 280px; border-radius: 4px">[results figure]</div>
  <figcaption>Figure 1. [Caption describing what the reader should notice.]</figcaption>
</figure>

## What I learned

[What surprised you, what didn't work, and what you'd try next.]
