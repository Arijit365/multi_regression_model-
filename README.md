
# House Habitibiliy Regression Model

In this model , we predict the Habitibiliy score
 each house according different parameters
 
## Parameters
Target Varible
Habitibility Score
Independedent Variable
1. Property Type
2. Property Area 
3. Number of Windows
4. Number of Doors
5. PowerCut frequency
6. Traffic density
7. Air Quality Index
8. Neghibourhood Review
## Build Pipeline
In the model model we build simple Pipeline using column Transformer from sklearn
The reason behind using column Transformer is to create perfect architecture of the necessary stpes , that data can pass through and code resubility.
STEPS:
1. Avoiding null and NAN
2. Encoding
3. Scaling
4. feature selection
5. applying ML algoritham
Command from create ML pipeline in python.
```bash
from sklearn.compose import ColumnTransformer
from sklearn.pipeline import Pipeline
```
