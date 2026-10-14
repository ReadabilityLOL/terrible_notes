---
title: "Conway's Game of Life: Let's Add a Sparse Matrix"
tags:
  - code
  - tutorial
  - conway
publish: "true"
---
## Intro

I thought I was done making Conway's game of life, but it turns out there are some improvements to be made. The previous method of storing every single cell in the matrix is, to say the least, quite slow. Now, though, I've learned about a new method, storing cells in a [sparse matrix](https://en.wikipedia.org/wiki/Sparse_matrix). Basically, instead of storing every single cell individually, I can instead store only the coordinates of the living cells, allowing them to move on an infinite grid, rather than a finite one.

Although this will allow the game of life to be run on an infinite grid, infinite scrolling will be added in the next update, mainly because I have to learn how to do it.

## Converting the matrix

Thankfully, we can keep a good bit of the old code.
