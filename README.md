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
```

<img width="719" height="537" alt="image" src="https://github.com/user-attachments/assets/07c0485b-5bce-4c35-ac85-b548652a5ca7" />

```
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```
<img width="693" height="537" alt="image" src="https://github.com/user-attachments/assets/6c08806c-2232-4972-ad28-508155fbd333" />

## SCATTER PLOT:

```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
```
<img width="689" height="516" alt="image" src="https://github.com/user-attachments/assets/d6890619-8f5e-4e41-94a0-13579df65aa1" />

```
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
<img width="705" height="571" alt="image" src="https://github.com/user-attachments/assets/bbb06281-e77e-43dd-a6bc-d32a2e5529bf" />

## PIE CHART:

```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```
<img width="567" height="517" alt="image" src="https://github.com/user-attachments/assets/083fa123-c349-4496-ab4c-39264f71aff0" />

```
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="548" height="503" alt="image" src="https://github.com/user-attachments/assets/d8fdca81-a639-44bb-864b-7b4afc858241" />

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
<img width="691" height="513" alt="image" src="https://github.com/user-attachments/assets/1c1a43c6-46b7-45a0-9b73-028c64d38952" />


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
<img width="707" height="570" alt="image" src="https://github.com/user-attachments/assets/8a4d7a9c-18ce-4043-a731-689caacffc9a" />

## HISTOGRAM:
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```

<img width="665" height="518" alt="image" src="https://github.com/user-attachments/assets/8a987a43-69ae-4ae6-b27b-677b0e629444" />


## BOX PLOT:

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```

<img width="759" height="458" alt="image" src="https://github.com/user-attachments/assets/255b8bd5-3b6f-440d-ad2a-c7220c50b9b8" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
<img width="763" height="603" alt="image" src="https://github.com/user-attachments/assets/401dd9b0-985e-4cd0-aa24-49f688ab98db" />


# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
 
