# javascript-ground
This is a demo project to play with html and javascript:
 dyn-cmpx-tbl.html and dyn-smpl-tbl.html will dynamically create a html table from hardcoded json data:
 <br>Sample json for simple dynamic html table:<br>
 const data = [
                { name: "John", age: 28, city: "New York" },
                { name: "Anna", age: 22, city: "London" },
                { name: "Mike", age: 32, city: "Chicago" }
            ];
<br>
<br>Sample json for little complex dynamic html table:<br>
const input = {
                "headers": ["Range", "Top Speed", "Acceleration to 100 km/h"],
                "data": {
                    "Electric car 1": ["400 km", "200 km/h", "6 seconds"],
                    "Electric car 2": ["300 km", "180 km/h", "8 seconds"]
                }
            };
 <br>
 Output will look like:
<img width="952" alt="output-1-2" src="https://github.com/dev-art-tech/javascript-ground/assets/125658814/ce58caab-c3b6-42df-8c1f-814e1aa53c9a">
