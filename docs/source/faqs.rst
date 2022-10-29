FAQS
==================

1. What can I do if the elements in the plot appear to be overlapping each other due to the displayed plot size?

- You may want to increase the height and/or width of the plot offered in the download option, based on your need before downloading the plot.

2. Where can I get the source code of these R plots if I would like to modify the code based on my need?

- You may visit this GitHub repository (https://github.com/pendy05/DiveR) to get the corresponding source codes.

3. What is the maximum image size (in inches) that can be downloaded via vDiveR R Shiny App deployed on Shiny server?

- Maximum 50 (H) x50 (W) inches to prevent the common error of specifying dimensions in pixels encountered in R ggsave() function.

4. I encountered *'Error in x$clone: attempt to apply non-function'* in plot 'entropy and incidence of total variants' when I submit files for two hosts. Other plots work fine though. Why does this happen?

- vDiveR expects the proteins with same protein name have same length (number of positions) across both the hosts to carry out the comparison plot.

5. What should I do if I would like to run each function in vDiveR separately and locally?

- vDiveR will be soon released as a Bioconductor package. Tentatively, you may visit our GitHub repository (https://github.com/pendy05/DiveR) for its source code.