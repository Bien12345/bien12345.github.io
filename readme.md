## bai hoc dau tien ve html


`HTMl` là viết tắt của **Hyper Text Markup Language** (ngôn ngữ đánh dấu siêu văn bản).



`HTML` cho *phép người dùng tạo và cấu trúc hóa các thành phần* trên một trang web như đoạn văn, tiêu đề, liên kết, trích dẫn, bảng biểu…

### chuong trinh dau tien

> tao file index.html nhu sau

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h2>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos placeat tenetur officia nostrum dignissimos, tempora ratione quam perspiciatis at nemo fugiat iste, tempore iure. Soluta, consequuntur. Alias porro similique in.</h2>

    <h2 id="heading" >Lorem ipsum dolor sit, amet consectetur adipisicing elit. Et, fugit. Magni modi dolore non aspernatur, expedita debitis sapiente fuga ipsam! Eveniet at neque quisquam molestiae nemo minima, ducimus maiores dignissimos.</h2>

    <div class="box">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita sint provident, eaque esse possimus numquam quibusdam dolorum qui. Eum ipsam incidunt ducimus alias laudantium quam! Doloribus, nulla excepturi? Nobis, suscipit!</p>

        <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi laboriosam veniam aliquid ut a. Reprehenderit praesentium, accusantium eaque ducimus esse atque debitis. Maxime totam error molestias provident inventore, eaque esse!</p>
    
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Adipisci blanditiis aspernatur accusantium voluptas, asperiores necessitatibus, aliquid neque eos omnis reiciendis repellat sit maiores odit exercitationem. In reprehenderit dicta nemo ipsa!</p>
    
    </div>
 
 
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Adipisci blanditiis aspernatur accusantium voluptas, asperiores necessitatibus, aliquid neque eos omnis reiciendis repellat sit maiores odit exercitationem. In reprehenderit dicta nemo ipsa!</p>
    
</body>
</html>

```

noi dung file `css` nhu sau

```
.box p {
    font-weight: bold;
}

h2, p{
    text-align: center;
}

#heading + .box {
    background-color: blue;
}

p ~ .text {
    font-style: italic;
}
```

ket qua:

![](link anh vao day)

### tai lieu 
- tttttttttttttttttttttttt
- bbbbbbbbbbbbbb
- cccccccccccccccccc

### code tham khao 

- [buoi hoc so 1](./day-2/index.html)
- [buoi hoc so 2](./card/index.html)