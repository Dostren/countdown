# countdown
A countdown timer built with HTML, CSS, and JavaScript. It displays the remaining time, using your device's current time as the reference.

## Changing the date
 
The target date is set in the HTML file on line 56:
 
```js
const targetDate = new Date(2026, 5, 13, 19, 0, 0);
```
 
The parameters are passed in the following order:
 
```js
new Date(year, month-1, day, hour, minute, second)
```
 
Example:
 
```js
new Date(2026, 5, 13, 12, 34, 56);
```
 
This means:
 
```
Year: 2026; month: June; day: 13; hour: 12; minute: 34; second: 56.
```

Default date:
```
Year: 2026; month: June; day: 13; hour: 19; minute: 0; second: 0.
```


## Usage

1. Download the files from the repository;
2. Change the date in the HTML file;
3. Open the HTML file in your browser (with JavaScript support).
