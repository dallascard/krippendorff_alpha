# Krippendorff Alpha

Code for computing Krippendorff alpha

#### Requirements:

- python3
- numpy

#### Example:

To reproduce an example from the [wikipedia page](https://en.wikipedia.org/wiki/Krippendorff's_alpha#A_computational_example), run:

`python measure_agreement.py example.jsonlist --null-val "*"`

This should return a Krippendorff alpha value of 0.691.

Note that item-worker pairs with no response can either be noted with a null value (here, "\*"), or omitted from the data entirely. Also note that when specifying "\*" as the null value, quotation marks are required, or else the command line will interpret it as all files in the directory.
