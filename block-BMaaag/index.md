writeCode

Write code to:-

- create a database named `mountains`
- a collection inside that database named `himalayas`
- insert 1 document into that collection `{name: 'Dhauldhar range', height: '4000 mtrs'}`

- insert multiple document using insertMany command
- find all documents from mountains
- find a single document using name

```js
var mountains = 
[    
    {name: "Dhauldhar range", height: "4000 mtrs"},
    {name: "big range", height: "5000 mtrs"},
    {name: "nice range", height: "6969 mtrs"},
    {name: "small range", height: "20 mtrs"}
]

db.himalayas.insertMany([    
    {name: "Dhauldhar range", height: "4000 mtrs"},
    {name: "big range", height: "5000 mtrs"},
    {name: "nice range", height: "6969 mtrs"},
    {name: "small range", height: "20 mtrs"}
])
```