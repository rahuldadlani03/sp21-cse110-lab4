1. The bug was that num1 and num2 allow strings so adding them together results
in string concatenation.
2. I would fix it by first trying to convert the string to a number. If that
threw an error, print either num1 or num2 is an error. If no errors, calculate
the sum and return.
3. citylots.json 
4. part2.js
5. 11.7 MB
6. 151 ms
7. User Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_3) 
AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.85 Safari/537.36
8. Apache
9. Last-Modified: Tue, 26 Jan 2021 22:14:13 GMT
10. Content-Type: application/json
11. fetchData
