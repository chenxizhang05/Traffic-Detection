Analysis Pipeline
1. Automated frame extraction from the video with pre-specified frequency
2. Analyze image with ML model for counts in 4 categories:
Cars
Buses
Trucks 
Motorcycles
3. Post-processing of counts for enhanced accuracy:
Cropped the image to exclude non-road regions
Filter identified objects with excessively small sizes (high error rates)
Removed double-counts (e..g when 2 boxes overlap by > 50%) 
Additional filters can be added to enhance results for each day’s series of images
4. Generate counts for identified object

