# Canvass
Python code for the Code Assessment for Canvass<br /> 
Code contains two folders Challange_1 and Challange_2<br />

To run each assignment:<br />

### Challange 1
- CD to the folder Challange_1<br />
- Run the command: python Challange_1.py 1000 3000<br />
- (1000 3000 are the range for the list of numbers)<br />


### Challange 2
- CD to the folder Challange_2<br />
- Run the command python Challange_2.py 2<br />
- (2 is the number of Device IDs)<br />


Proud of two things:<br />
1. Decision to seperate the data by device ID when reading from the CSV in Challange 2<br />
2. The sorting method by data in Challange 2<br />
3. Making the code very dynamic in terms of unknown variables (Date Format, Devive ID range) in Challange 2<br />
4. Simplicity of the method in Challange 1<br />
Not proud of:<br />
1. The amount of variables used, specially in the sort function in Challange 2<br />


Design Decisions:<br />
Seperating the data by Device ID while reading from CSV to make sorting simpler<br />
Use of Lists and Dictionaries, for the ease and efficiency of retriving items.<br />
In my first implementation for getting the data, I used two dictionaries to store them.<br />
But this was heavily reliant on the fact that there will always be two device IDs.<br />
So I implemented the method above, which is more dynamic.<br />
But I left my first implementation below to show my initial thought process, and the fact that I can manipulate dictionaries.<br />
I left in the print statements commented out to show what i did for the testing phase of each function<br />
