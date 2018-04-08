# My-grid-system
<p>This is a grid system I created using html and css only to contain a maximum of 8 colums.
There are to css files: The grid.css file which is the main grid structure and the custom css to adjust the properties
like height, padding etc to suit the users test.</p>
<p> The topmost column is the space for the navigation and Header,
The colums at the center is for pictures or cards and the last column is for the footer
<p> I used the formula  width=calc(100% / 8 * x) to get the exact number of columns. Where 8 is the maximum number 
of columns it can contain and is equal to 100%, i.e to say 8 represents 100%.</p> 
<p>* For col-1, x = 1, i.e calc(100%/ 8 * 1) means that the total number of columns 
8 and each has a size of one relative to the total size 8 and a percentage of 12.5 each.</p>
<p>* For col-2, x = 2, i.e calc(100% / 8 * 2) means that each column has a percentage of 25 and there are 4 colums in that row
Wheas 8/2 =4.</p>
</p>* For col-3, x =3 i.e calc(100% / 8 * 3) it means that there are 3 columns in that row and each has a percentage of 33.3 
i.e 100/3.
**NOTE** : This won't give a round number. And it will cause unequal alignment in the grid system because 8/3 will give each column a size of 
approximately 2.66 each and suming them up will not give exactly 8 .So to accomodate this, I created a special width for it which 
I gave in the next line as col-33.</p>
<p>* For col-33 , x = 3 i.e calc(100% / 8 * 2.66),there will now be 3 columns each on that row.<p>
<p>* For col-4 x = 4, i.e calc(100% / 8 * 4) it means that there are 2 columns in that row and each has a percentage of 50 or size 4 each relative to 
the size.</p>
<p>* For col-5, x = 5, i.e calc(100% / 8 * 5) it means that there are 2 columns that are not equal. One has a size of 5 and the other 3 to give a
total of 8. i.e 62.5% and 37.5% respectively.</p>
<p>* For col-6, x = 6, i.e calc(100% /8 * 6) it means that there are 2 columns that are not equal. One has a size of 6 and the other 2 to give a total 
of 8 which is the maximum size.</p>
<p>*  For col-7, x =7 i.e calc(100% /8 * 7) it means that one column will have a size of 7 and the other 1 0r 87.5% and 12.5% respectively.
<p>* For col-8, x = 8 i.e calc(100% / 8 * 8) it means that there will be only one column of size 8 and 100% in that row.</p>

# Usage
<p>* Let's say we want to create a webpage that has a main section of 3 colums each across two rows</p>
<p>* We simply link our grid.css file to the Head section of our index.html file, add our style.css below so 
as to able to overide the grid.css in order to modify it </p>
<p>* Then in the index.html page we create 6 divs inside a div called grid which is inside another div called container
and use the appropriate class from the htm which in this case is col-33 as already stated above</p>

## License
MIT License

Copyright (c) [2018] [Anukam Uchechukwu]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this grid system and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
