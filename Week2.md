## Writing Test week 2 Web Development Basic      
### Scope dalam Javascript     
- Scope menentukan suatu variabel dapat diakses pada scope tertentu atau tidak          
-  Blocks adalah code yang berada di dalam curly braces atau {}. Conditional, looping, function dalam javascript menggunakan curly braces
-  Global Scope merupakan variabel yang dapat kita akses secara global atau dimanapun dalam suatu file. Untuk menjadikannya global scope, kita harus mendeklarasikannya di luar Blocks
  <!-- Image Global Scope -->
- Local Scope merupakan variabel yang kita deklaraikan di dalam blokcs seperti pada function, looping, conditional. Oleh karena itu, variabel tersebut hanya dapat diakses di dalam blocks saja
<!-- Image local scope -->

### Tipe Data di Javascript
Dalam Javascript, terdapat beberapa tipe data. tipe-tipe data tersebut dikelompokkan menjadi tipe data primitive dan tipe data non-primitive.   
- Tipe data Primitive:
    - String
  ![](asset/string..png)
    - Number
  ![](asset/number..png)
    - Boolean
  ![](asset/boolean..png)
- Tipe data non primitive:
    - Array
  ![](asset/array..png)
    - Object 
  ![](asset/object..png)
### Property dan Method dalam Javascript 
- Property yang ada di dalam string:
  - typeof : mengetahui tipe data
  ![](asset/typeof..png)
  - length : untuk mengetahui berapa banyak karakter
  ![](asset/string-length..png)
- Method yang dimiliki dalam string
Method adalah sebuah function dalam javascript
  - toUpperCase()
  ![](asset/touppercase..png)
  - toLowerCase()
  ![](asset/tolowercase..png)
- Method yang ada di dalam number
  - isNaN() = Mengecek apakah angka atau bukan
  ![](asset/isNaN..png)
  - toString() = merubah tipe data number menjadi string
  ![](asset/tostring..png)
## Math
Math merupakan objek yang sudah disediakan oleh javascript
- Math Method
  - Math.abs () = mengembalikan nilai absolut dari angka
  ![](asset/math-abs..png)
  - Math.pow() = mencari nilai pangkat
  ![](asset/math-pow..png)
  - Math.sqrt() = mencari akar bilangan
  ![](asset/math-sqrt..png)
  - Math.round() = membulatkan bilangan
  ![](asset/math-round..png)
  - Math.floor() = membulatkan bilangan ke bawah
  ![](asset/math-floor..png)
  - Math.ceil() = membulatkan bilangan ke atas
  ![](asset/math-ceil..png)
  - Math.random() = membuat bilangan random
  ![](asset/math-random..png)
## Document Object Model (DOM)
- ### Definisi DOM
DOM adalah jembatan agar bahasa pemograman dapat berinteraksi dengan dokumen HTML. Dengan DOM, Javascript dapat memanipulasi HTML. DOM bukan milik Javascript namun milik web browser. DOM berbentuk Tree Structure
File HTML -> load -> DOM
- ### Traversing
  - getElementByID = mengakses element berdasarkan ID
  ![](asset/h1%20html..png)
  Kita dapat akses dengan: 
  ![](asset/h1-getelbyid..png)
  - getElementsByClassName = mengakses element berdasarkan class name
  ![](asset/class-html..png)
  Kita dapat akses dengan:
  ![](asset/getelclassname..png)
  - querySelector = mengakses element berdasarkan selector
  ![](asset/query-selector..png)
  - children = mengakses anak dari parent element
  ![](asset/children..png)
  - previousSibling = mengakses element setara sebelumnya
  ![](asset/prevsibling..png)
  - nextSibling = mengakses element setara setelahnya
  ![](asset/nextsibling..png)
- ### DOM Manipulation
Memanipulasi element HTML dengan DOM
  - innerHTML = memasukkan tag html ke element HTML
  ![](asset/innerhtml..png)
  - innerText = memasukkan teks ke dalam element HTML
  ![](asset/inntertext..png)
  - createElement = membuat element baru
  ![](asset/createElement..png)
  - append = menyisipkan element baru tersebut ke dalam HTML
  ![](asset/append..png)
  - getAttribute = mengakses atribut tertentu dari element HTML
  ![](asset/gettribute..png)
  - setAttribute = menambahkan atribut tertentu ke element HTML
  ![](asset/setattribute..png)
  - style = melakukan styling element HTML
  ![](asset/style..png)
- ### DOM events
Events adalah kejadian/interaksi yang terjadi pada website
  - Terdapat 3 cara dalam memberikan events:
    - HTML Attribute
  ![](asset/html-attribute..png)
    - Event Property
  ![](asset/onclick..png)
    - addEventListener() 
  ![](asset/addeventlistener..png)
  - Event
    - click
   ![](asset/addeventlistener..png)
    - submit
  ![](asset/submit..png)
    - focus
  ![](asset/focus..png)
    - hover
  ![](asset/hover..png)
  - Form
  Kita dapat mengambil hasil dari user input pada form yang kita buat dengan DOM. yaitu dengan cara:
  ![](asset/form-value..png)