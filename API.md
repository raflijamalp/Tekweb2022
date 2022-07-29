# API POINTS




## PORTFOLIO
### Menampilkan seluruh data portfolio
```
GET: /portfolio
response:
[
  {
    "id"          : "",
    "gambar"      : "",
    "title"       : "",
    "author"      : "",
    "markdown"    : ""
  },
  {
    ...
  }
]
```
### Menampilkan data portfolio berdasarkan ```id```
```
GET: /portfolio/[id]
response:
{
  "id"          : "",
  "gambar"      : "",
  "title"       : "",
  "author"      : "",
  "markdown"    : ""
}
```
### Menambahkan data porfolio
```
POST: /portfolio
data:
{
  "gambar"      : "",
  "title"       : "",
  "author"      : "",
  "markdown"    : ""
}
response:
true    //if true
false   //if false
```

### Mengubah data porfolio
```
PUT: /portfolio
data:
{
  "gambar"      : "",
  "title"       : "",
  "author"      : "",
  "markdown"    : "" 
}
response:
true    //if true
false   //if false
```
### Menghapus data portfolio
```
DELETE: /portfolio/[id]
response:
true    //if true
false   //if false
```


# DATABASE DESIGN
![Design Database](https://raw.githubusercontent.com/firoos18/tekweb2022/main/assets/img/Database%20Design.png)
