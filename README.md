# Glass-Identification-project

Outline
<br>
Importing libraries
<br>
Importing Dataset
<br>
Exploring Dataset
<br>
Preparing Dataset
<br>
Cleaning (removing outliers, normalizing)
<br>
Visualization
<br>
Train/Test Split
<br>
Applying Machine Learning Models
<br>
Summary
<br>
Method 2 to solve dataset (Different method to detect glasses)

## Machine learning models that we have applied:
<br>
1-KNN
<br>
2-Logistic Regression
<br>
3-Decision Tree
<br>
4-SVM (Linear Kernal)
<br>
5-SVM (Non Linear Kernal)
<br>
6-Random Forest
<br>
7-Neural Network

Gradient Decent Tree Boosting

### Attribute Information:

1- Id number: 1 to 214
<br>
2- RI: refractive index
<br>
3-  Na: Sodium (unit measurement: weight percent in corresponding oxide, as are attributes 4-10)
<br>
4- Mg: Magnesium
<br>
5- Al: Aluminum
<br>
6- Si: Silicon
<br>
7- K: Potassium
<br>
8- Ca: Calcium
<br>
9- Ba: Barium
<br>
10- Fe: Iron
<br>
11- Type of glass: (class attribute) -- Label attribute
  . building_windows_float_processed
.  building_windows_non_float_processed
<br>
. vehicle_windows_float_processed
<br>
. vehicle_windows_non_float_processed (none in this database)
<br>
. containers
<br>
. tableware
<br>
. headlamps
### Data Set Information:
Vina conducted a comparison test of her rule-based system, BEAGLE, the nearest-neighbor algorithm, and discriminant analysis. BEAGLE is a product available through VRS Consulting, Inc.; 4676 Admiralty Way, Suite 206; Marina Del Ray, CA 90292 (213) 827-7890 and FAX: -3189. In determining whether the glass was a type of "float" glass or not, the following results were obtained (# incorrect answers):
<br>
Type of Sample -- Beagle -- NN -- DA
<br>
Windows that were float processed (87) -- 10 -- 12 -- 21
<br>
Windows that were not: (76) -- 19 -- 16 -- 22
<br>

The study of classification of types of glass was motivated by criminological investigation. At the scene of the crime, the glass left can be used as evidence...if it is correctly identified!

###Source:
Creator:
<br>
B. German
<br>
Central Research Establishment
<br>
Home Office Forensic Science Service
<br>
Aldermaston, Reading, Berkshire RG7 4PN
<br>

Donor:
<br>
Vina Spiehler, Ph.D., DABFT
<br>
Diagnostic Products Corporation
<br>
(213) 776-0180 (ext 3014)
<br>
https://archive.ics.uci.edu/ml/datasets/glass+identification
