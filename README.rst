# working_with_FILE_I-O
Cont file i/o python.

## Reading from a file


### Instructions
* Using a with statement, create a file object pointing to the file just_the_first.txt. 
* Store that file object in the variable first_line_doc.


```
with open("just_the_first.txt") as first_line_doc:
  first_line = first_line_doc.readline()
  s= first_line_doc.readline()
  print(first_line)
  print(s)
```


![image](https://user-images.githubusercontent.com/96833570/183856538-7b0fb503-f507-4315-b35e-d99689aa6335.png)


## Writing to a file

### Instructions

* Create a file object for the file bad_bands.txt using the open() function with the w argument. 
* Assign this object to the temporary variable bad_bands_doc.

![image](https://user-images.githubusercontent.com/96833570/183857290-fb47642b-6f4e-47c1-825c-880f6add809e.png)

```
with open("bad_bands.txt","w") as bad_bands_doc:
  bad_bands_doc.write("gio")



## Appending to a File
```




