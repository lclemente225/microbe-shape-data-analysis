# microbe shape data analysis

## Description
### Data Source
- The data set contains an array of species of bacteria. <br>
['Spirogyra', 'Volvox', 'Pithophora', 'Yeast', 'Raizopus',
       'Penicillum', 'Aspergillus sp', 'Protozoa', 'Diatom', 'Ulothrix']

- These are the features in the csv file. <br>
['Unnamed: 0', 'Solidity', 'Eccentricity', 'EquivDiameter', 'Extrema',
       'FilledArea', 'Extent', 'Orientation', 'EulerNumber', 'BoundingBox1',
       'BoundingBox2', 'BoundingBox3', 'BoundingBox4', 'ConvexHull1',
       'ConvexHull2', 'ConvexHull3', 'ConvexHull4', 'MajorAxisLength',
       'MinorAxisLength', 'Perimeter', 'ConvexArea', 'Centroid1', 'Centroid2',
       'Area', 'raddi', 'microorganisms']

- Out of all the features, I selected some. <br>
['Solidity', 'Eccentricity', 'EquivDiameter', 'Extrema',
       'FilledArea', 'Extent', 'Orientation', 'EulerNumber', 'BoundingBox1',
       'BoundingBox2', 'BoundingBox3', 'BoundingBox4', 'ConvexHull1',
       'ConvexHull2', 'ConvexHull3', 'ConvexHull4', 'MajorAxisLength',
       'MinorAxisLength', 'Perimeter', 'ConvexArea', 'Centroid1', 'Centroid2',
       'Area', 'raddi']

### Microbe Comparison 1
I selected to compare the Spirogyra and Volvox species due to their differences in cell shape despite both being algae. Spirogyra cells are a cylinder shape and Volvox cells are a spherical shape.
I used PCA (principal components analysis) to simplify the data output.

![image](https://github.com/user-attachments/assets/76955b5c-1429-4eaf-a7c6-33851bfb3c65)

## Results of Microbe Comparison 1
K-means Clustering is used to create clusters of the provided data. The graph shows that the clusters are very distinct from each other, there is barely any overlap among them.  
