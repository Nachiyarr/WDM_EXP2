### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
## BUYING
![image](https://github.com/Nachiyarr/WDM_EXP2/assets/113497340/c7d3a1bb-8205-418b-a82d-6d359815ff3b)
## EMPLOYEE
![image](https://github.com/Nachiyarr/WDM_EXP2/assets/113497340/48087463-a568-4fc6-bd02-47bd065e74d2)
## BANK
![image](https://github.com/Nachiyarr/WDM_EXP2/assets/113497340/834d0bd3-084f-4070-96b7-c79fcd059454)


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
## BUYING 
![image](https://github.com/Nachiyarr/WDM_EXP2/assets/113497340/1ec7abcb-ae22-48a9-9591-dddbddb9fe7e)
## EMPLOYEE
![image](https://github.com/Nachiyarr/WDM_EXP2/assets/113497340/5c5063d7-7341-4bf1-8fe5-2f2c33b569df)

## BANK
![image](https://github.com/Nachiyarr/WDM_EXP2/assets/113497340/995229f0-72c6-48ce-8bb2-d5d15eeeddc4)


### RESULT: 
Thus this program has been successfully executed.
