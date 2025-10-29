# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

## LINE PLOT:
```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()

student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```

<img width="641" height="427" alt="image" src="https://github.com/user-attachments/assets/83e819a2-5c4d-40f9-a4e2-c8d4e7d28041" />
<img width="639" height="440" alt="image" src="https://github.com/user-attachments/assets/71795c71-e4be-4cb9-ad72-60f98544785a" />

## SCATTER PLOT:
```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()

x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```

<img width="615" height="421" alt="image" src="https://github.com/user-attachments/assets/cefa51e5-55a8-4eff-a42e-233130a3c292" />
<img width="636" height="458" alt="Screenshot 2025-10-22 105857" src="https://github.com/user-attachments/assets/eab5a2b4-6a59-489f-a20c-9fd859fb2eb0" />

## PIE CHART:
```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```

<img width="505" height="613" alt="image" src="https://github.com/user-attachments/assets/6f283861-edc7-4832-bd0b-0fcd570592e1" />

## AREA CHART:
```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```

<img width="460" height="318" alt="image" src="https://github.com/user-attachments/assets/18f66116-1abe-4c8e-a840-f9fe84f8517b" />

## BAR CHART:
```
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['red', 'green'] 
 c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()
```

<img width="459" height="336" alt="image" src="https://github.com/user-attachments/assets/cba47cfc-2d60-43a4-9393-68c77e34458a" />

## HISTOGRAM:
```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```

## BOX PLOT:
```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```

<img width="418" height="273" alt="image" src="https://github.com/user-attachments/assets/4a002e55-6553-4eac-aac3-3cca9164f0c3" />

```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```

<img width="460" height="366" alt="image" src="https://github.com/user-attachments/assets/07473db5-d0c0-4840-ba43-cf84e9871f8d" />


# Result:

Thus, all the data visualization techniques of matplotlib has been implemented.
