# Sorting Algorithm Visualizer

Interactive sorting algorithm visualization with Web Audio API sound effects.

## Demo

https://hwkim3330.github.io/sort/

## Features

- **8 Sorting Algorithms**
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
  - Heap Sort
  - Shell Sort
  - Cocktail Shaker Sort

- **Audio Feedback**
  - Pitch based on element value (200Hz - 1200Hz)
  - Different sounds for comparing vs swapping
  - Completion melody

- **Real-time Stats**
  - Comparisons count
  - Swaps count
  - Elapsed time

- **Controls**
  - Adjustable array size (10-200)
  - Adjustable speed (1-200ms delay)
  - Sound toggle
  - Stop/Generate buttons

- **Algorithm Info Panel**
  - Time complexity (Best/Average/Worst)
  - Space complexity
  - Stability
  - Method

## Color Legend

| Color | Meaning |
|-------|---------|
| Blue | Normal |
| Yellow | Comparing |
| Red | Swapping |
| Purple | Pivot (Quick Sort) |
| Green | Sorted |

## Tech Stack

- Vanilla JavaScript
- Web Audio API
- CSS3 Animations
