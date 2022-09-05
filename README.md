# IEM-and-Headphone-measurement-raw-database
Original files data pulled from CrinGraph and Squig.link websites like Crinacle, Banbeu, Super Review... with some additional Oratory1990 webplotdigitizer data.


## Direct access to Crinacle's graphtool without visit the main website
Create new .html files and paste the following codes, save it and open with browser

IEM Graphtool: 
```
<!DOCTYPE html>
<html>

<head>
</head>

<body style="margin:0px;padding:0px;overflow:hidden">
    <iframe src="https://crinacle.com/graphing/tooliemfree.html" frameborder="0"
        style="overflow:hidden;overflow-x:hidden;overflow-y:hidden;height:100%;width:100%;position:absolute;top:0px;left:0px;right:0px;bottom:0px"
        height="100%" width="100%"></iframe>
</body>

</html>
```
HEADPHONE Graphtool:
```
<!DOCTYPE html>
<html>

<head>
</head>

<body style="margin:0px;padding:0px;overflow:hidden">
    <iframe src="https://crinacle.com/graphing/toolheadphonefree.html" frameborder="0"
        style="overflow:hidden;overflow-x:hidden;overflow-y:hidden;height:100%;width:100%;position:absolute;top:0px;left:0px;right:0px;bottom:0px"
        height="100%" width="100%"></iframe>
</body>

</html>
```
![file](.assets/file.png)

## How to get the data
Open inspect with F12 or right click, switch to Network tab, set filter as Fetch/XHR

![inspect](.assets/inspect.png)

Right click on the file and copy response

![copy](.assets/copy_response.png)

Paste it to notepad and save as .txt or .csv

![save](.assets/save.png)