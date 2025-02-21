
## Conditionals -:

```
if(Condition){
	//Action
}
else if (Condition) {
	//Action
}
else{
	//Action
}
```

## Loops -:
To repeat something multiple times
```
for(int i = 0; i < 5; i++){
	cout >> "Hello"
}
```

## Patterns -:
In Pattern Questions, count the number of rows and the number of columns, in this type of question always a nested loop is used where the inner loop is for columns and outer loop is for the rows

### 1. Solid Rectangle  
	Here we have 3 rows and 5 columns
```
for(int row = 0; row < 3; row++) {
        for(int col = 0; col < 5; col++) {
            cout << "*";
        }
        cout << endl;
    }
``` 


### 2. Square Pattern
	Here we have 4 rows and 4 columns  
```
for(int row = 0; row < 4; row++){
	for(int col = 0; col <4; col++){
		cout << "* ";
	}
	cout << endl;
}
```


### 3. Hollow Rectangle
Here we have -> 1st row - all stars, last row all stars, and remaining rows 1st star then spaces then at last star
```

```