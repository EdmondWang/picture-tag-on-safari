*Max OS version: 10.14.3*

*Safari version: Version 12.0.3 (14606.4.5)*

I am facing a Safari only problem.

I use jQuery to detach() then append() one picture tag, which causes Safari to request same image twice. 
That is not expected. And there is no such problem in Chrome and Firefox.

**To setup**

npm install

npm start

Access http://localhost:3000/

**To reprodcue the problem**

open network panel of developer tool

click "move to red" button

check JPG request is sent in network panel

click "move to blue" button

check JPG request is sent in network panel






