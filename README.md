# day3-visualization-assignment

# Histogram of GC content

## The Task

1. Create a jupyter notebook which contains a histogram of GC content
for all of the sequences in ```data/records.fa```.
  - Change the number of bins to 20
  - Add sensible titles for the axes.
  - Change the color of the bars and their edges.

2. In a different notebook cell
  - Create a boxplot of the same data
  - Label the axes.

3. In another notebook cell
  - create a single figure which contains both plots as subplots.
  - Use 1 row and 2 columns.

4. Submit the notebook as your answer.


## Hints

This task builds upon the assignment from yesterday.

Use the ```calc_gc_percent``` function from yesterday to calculate the gc content of each sequence.

The matplotlib **hist** and **boxplot** functions accept a **list** of values as input.

If you find that the two plots in task 3 overlap, try adding ```tight_layout()``` after the plotting code.
