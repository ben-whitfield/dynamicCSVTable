# Generate a HTML table from a .csv file

Simple example of taking a local csv file and converting that to a html table using Javascript.

Note, this does not deal with multiple variants of csv files

To use, copy your CSV data into the data.csv file. It should look something like this:

```
id,text,time,latency,foo
1,text1,time1,latency1,foo1
2,text2,time2,latency2,foo2
```

You can add as many items as you like, the table is dynamic.

Run `npm run start`

and boom

![alt text](https://github.com/benwdev/dynamicCSVTable/blob/main/img/tableOutputExample.png "Example of table output")
