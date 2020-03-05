# MapComparison
Often, we need to validate how accurate a prediction is to ground truth, or to compare an area of interest over multiple time points in raster image analysis. This script includes methods for such comparisons, including hits, misses, correct rejections, false alarms, exchange, quantity, and shift.

Hits are the number of pixels correctly defined in both images. False alarms are the number of pixels defined as hits when they should be defined as a different category. Misses are the number of pixels omitted from a category where they should exist. Correct rejections are the number pixels correctly defined as absence in a boolean comparison, where the raster images only contain two categories (presence and absence).

Exchange is the switching of an equal number of pixels between two categories. Shift is the movement of any number of pixels from one category to another.

Quantity is the amount of difference between a reference and comparison map.