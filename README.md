# GenerateKMeansExamples
<h2>Create CSV files with built-in clusters so we can practice K-Means clustering</h2></br>
1. Study the json file provided. There are two example datasets in there. </br>
2. Edit the json file as needed.</br>
3. Run the Jupyter Notebook and it will process the JSON file. A .txt file and a .csv file will be generated with the same name as the JSON file </br>
4. Look in the .txt file for the centroids that were used to create the CSV file and also </br>
the centroids that were computed when the data in the CSV file was K-Means processed.
 </br>
 </br>
 Note: the Euclidean distances used in the cluster fitting may be way off if the scaling of the x and y axes are far apart. For example, </br>
 if the x-axis range is 1-10 and the y-axis range is 0-20000 then the y distance from the centroid will overwhelm the x distance from the centroid.</br>
</br>
 
 Note Note: the gaussian distribution logic is not functional: just leave the distribution as uniform.
 </br>
Other fun stuff the program will do for you: </br>
</br>
</br>

After generating the CSV file, the program will plots the housing.csv file (generated by the metadata in the example JSON file) and the computed K-means centroids for that data.</br>


