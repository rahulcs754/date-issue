# date-issue
date issue

# date issue if your date format is not correct

```js
$in_time = DateTime::createFromFormat('!d/m/Y H:i', $in_time);
echo $in_time->format('Y-m-d H:i:s');


function returndate($dateset){
		$in_time = $dateset;
		$in_time = DateTime::createFromFormat('!m-d-Y', $in_time);
		return $in_time->format('Y-m-d');
		}
```
https://stackoverflow.com/questions/27409742/insert-date-and-time-from-excel-sheet-into-db-with-php

