There are 699 samples in the Breast Cancer Wisconsin dataset, and each sample has 10 features and 1 class information. Below we mentioned all the features with the description.

Clump thickness: Benign cells tend to be grouped in monolayers, while cancerous cells are often grouped in multilayers.  
Uniformity of cell size: Cancer cells usually vary in size and these parameters help to determine whether the cells are cancerous or not.  
Uniformity of cell shape: Cancer cells usually vary in size and these parameters help to determine whether the cells are cancerous or not.  
Marginal adhesion: Cancer cells tend to spread away or stay loose. So, loss of adhesion is a sign of malignancy.  
Single epithelial cell size: Epithelial cells that are significantly enlarged is a sign of malignancy. 
Bare nuclei: This is a term used for nuclei that are not surrounded by the cytoplasm as the rest of the cells. Those are typically seen in benign tumors. 
Bland chromatin: It describes the uniform “texture” of the nucleus which is seen in benign cells. In cancer cells, the chromatin is coarser.  
Normal nucleoli: The nucleoli are small in structure and cannot be seen. But in cancer cells, nucleoli are bigger and more prominent.  
Mitoses: it describes is level of division of cancerous cells. 
 Class: Benign (non-cancerous) or malignant (cancerous) lump in the breast.

All the features describe the characteristics of cells that are observed in biopsy samples.Breast tumors can be categorized as malignant (cancerous) or benign (non-cancerous). Generally speaking, benign tumors do not pose a threat to life and do not metastasize to other bodily regions. Depending on their size and symptoms, they might still need medical attention, but they are typically not as dangerous as malignant tumors.alignant tumors, on the other hand, are cancerous and have the capacity to metastasize—a term used to describe the spread of a tumor to other parts of the body. Globally, breast cancer is the most prevalent cancer type among women. Effective management of breast cancer and better results depend on early detection and treatment. It's critical to do routine screenings and self-examinations to find any anomalies in the breast tissue.
Here, Class 2: benign 458 (65.5%) , 4: malignant 241 (34.5%).

The value range of the properties of the dataset is in the range of 1 to 10. The missing data in various properties of 16 samples were filled with an average value of 5 using the missing data filling method, which is a pre-processing method commonly used in data mining. Input and output values were created by separating the feature and class values in the dataset. 80% of the generated input and output values are divided as training (599 samples) and  20% as test data (140 samples).

Machine learning algorithms like K-NN, Decision Tree, and Support Vector Machine were applied to the prepared data for testing. 


