<h1 align="center"><a href="https://github.com/RoisyalBariz/DataTeam.git" target="_blank">PSSI Jawa Barat</a></h1>

## About Projects

Aplikasi yang dibuat adalah berbasis website yang kemudian penulis beri nama dengan sebutan PSSI Jawa Barat. PSSI Jawa Barat sendiri adalah website yang berisi informasi-informasi mengenai Team Sepak Bola diantaranya Nama Team, Tahun berdiri, Asal daerah, dan Pelatih. Dalam website tersebut juga terdapat penerapan semantik web berupa mesin pencarian dengan menggunakan SPARQL sehingga setiap input yang diberikan akan menampilkan hasil yang sesuai dengan yang diinputkan.


### Built With

* [Bootstrap](https://getbootstrap.com/)
* [XAMPP](https://www.apachefriends.org/download.html)
* [Apache Jena Fuseki](https://jena.apache.org/documentation/fuseki2/index.html)
* [NGROK](https://ngrok.com/)

## Requirements

<ul>
    <li>Git</li>
    <li>XAMPP</li>
    <li>PHP 7.3+</li>
    <li>Browser</li>
    <li>Apache Jena Fuseki</li>
    <li>NGROK</li>
</ul>

## Installation

1. Prepare and install all Requirements
2. Clone Project on XAMPP folder (../xampp/htdocs)
    ```sh 
        git clone https://github.com/RoisyalBariz/DataTeam.git
    ```
3. Run Apache Jena Fuseki on root folder
    ```sh 
        fuseki-server
    ```
4. Run NGROK on port 3030
    ```
        ngrok http 3030
    ```
5. Add turtle file on `/src/TeamSepakBola.ttl` to Apache Jena Fuseki on http://localhost:3030/
6. Run the app
    ```sh 
        http://localhost/Project Semantik/
    ```

## Author

| NPM           | Name        |
| ------------- |-------------|
| 140810190023  | Roisyal Bariz |
