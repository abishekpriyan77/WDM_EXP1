### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
### EMPLOYEE DATA:



<img width="1919" height="1020" alt="580535435-6a826b28-f223-4149-8b22-c51a18262496" src="https://github.com/user-attachments/assets/0a4b00ac-9f85-430b-93bb-0d7e5c59791a" />

### WEATHER DATA
<img width="1919" height="1025" alt="580535549-7b2962b5-f4b7-4c30-85d0-0d4c92c832c6" src="https://github.com/user-attachments/assets/6f8be1bb-6d0e-40f4-ae2b-afec67a314b6" />





### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

### EMPLOYEE DATA:
<img width="1919" height="1029" alt="580535833-11bd762c-adcc-4724-9034-33c06980bbf2" src="https://github.com/user-attachments/assets/63f43b08-109b-4e0d-a5fa-a600fac44fa1" />


### WEATHER DATA:
<img width="1918" height="1018" alt="580536280-59f2a3d1-219d-43bc-9f7e-882662462d05" src="https://github.com/user-attachments/assets/799bd42b-1f95-4c03-b6df-5c79b605bcad" />




### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
### EMPLOYEE DATA

<img width="1919" height="1025" alt="580536337-42c17273-b2ac-487e-b83c-8792517f7c2d" src="https://github.com/user-attachments/assets/74f921e4-a68f-49ac-a8ec-465c07555301" />

### WEATHER DATA:

<img width="1918" height="1025" alt="580535992-95a37704-f25f-454a-83f7-e5190d30de81" src="https://github.com/user-attachments/assets/2f80aba0-da26-4807-923e-00139391f026" />



### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:

### EMPLOYEE DATA




<img width="1919" height="1020" alt="580536376-d4087ba4-cab2-444f-9ee3-e75ad54e46b2" src="https://github.com/user-attachments/assets/23c6b7d1-1652-473e-a6a8-02f976cb5028" />
### WEATHER DATA
<img width="1919" height="1014" alt="580536051-5b9fb69d-fef0-4d9c-b31e-c9240b4623bf" src="https://github.com/user-attachments/assets/334d9ebd-ec4a-43bd-8988-41d7d0de5909" />



### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
