# Project Title

This is an HTML5 Canvas where you can paint. Based on the 30 days Javascript challenge.

## Getting Started

Click your mouse and move it to enjoy a colorful experience =).

## Demo

## [HTML5 Canvas](https://danielgarciaguillen.github.io/html5canvas/)
![HTML5 Canvas](/image/html5canvas.jpg?raw=true "CssClock")


## Learnings

* How to use basic canvas with:

```
const canvas = document.querySelector("#draw");
const ctx = canvas.getContext('2d');
canvas.width = window.innerWidth;
canvas.height = window.innerHeight;
```
* How to not draw while moving mouse with:
`let isDrawing = false`

* How to stablish an starting point when drawing:
```
let lastX = 0;
let lastY = 0;
```
* Update last position with `[lastX , lastY] =[e.offsetX, e.offsetY];`

## Built With

* Vanilla Javascript
* Css
* Html
