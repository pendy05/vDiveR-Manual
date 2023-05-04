FAQS
==================

.. note::
    For technical assistance or bug report, please reach us out via GitHub (`https://github.com/pendy05/vDiveR <https://github.com/pendy05/vDiveR>`_). For the general correspondence, please email Dr. Asif M. Khan (`asif.khan@udst.edu.qa <asif.khan@udst.edu.qa>`_).

1. What can I do if the elements in the plot appear to be overlapping each other due to the displayed plot size? [R Shiny App]

- You may want to increase the height and/or width of the plot offered in the download option, based on your need before downloading the plot.

2. What is the maximum image size (in inches) that can be downloaded via vDiveR R Shiny App deployed on Shiny server? [R Shiny App]

- Maximum 50 (H) x50 (W) inches to prevent the common error of specifying dimensions in pixels encountered in R ggsave() function.

3. I encountered *'Error in x$clone: attempt to apply non-function'* in plot 'entropy and incidence of total variants' when I submit files for two hosts. Other plots work fine though. Why does this happen? [R Shiny App]

- vDiveR expects the proteins with same protein name have same length (number of positions) across both the hosts to carry out the comparison plot.

4. What should I do if I would like to run each function in vDiveR separately and locally? 

- vDiveR is available as Bioconductor package. Alternatively, you may visit our GitHub repository (https://github.com/pendy05/vDiveR) for its source code.
