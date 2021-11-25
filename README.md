# Side_Project-plagiarism_detection_tool
## function introduction
1. Select file
2. Read the file
3. Compare the similarity
4. Clear files
## algorithms introduction
1. Compare the difference in the number of occurrences of a word
<br> - Retrieve all words in the file content
<br> - Store it in the dictionary and count the number of occurrences of the word
<br> - Calculate the degree of difference: total difference / (total number of dictionaries 1 + total number of dictionaries 2)
<br> - Similarity = 1-Difference
2. Compare jaccard similarity
![image](https://user-images.githubusercontent.com/56544982/143402647-b9ebfe48-a768-41cd-9634-4ca61ef4ef14.png)
3. Compare Cosine similarity
![image](https://user-images.githubusercontent.com/56544982/143402599-58431839-ad6e-46ae-9012-f7ae5902538e.png)
## tool exhibition
<img src="https://user-images.githubusercontent.com/56544982/143400529-8bad8c8b-9460-49cf-b9c0-28404c37cc36.png" width = "600" height = "400" alt="1" align=center />
<img src="https://user-images.githubusercontent.com/56544982/143402817-8e835c49-eb00-4c89-88af-24e3b7093bf5.png" width = "600" height = "400" alt="1" align=center />



