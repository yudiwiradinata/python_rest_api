# python_rest_api
Contoh python rest api

Hello, udah lama ga posting nih, kali ini mau sharing tentang restful API dengan Python. ini hal baru bagi penulis, karena biasa develop restful API dengan java. yuk mari kita mulai bagi yang belum paham atau belum kenal REST itu apa, kenalan dulu yuk dengan REST tak kenal maka tak sayang.... :) , dibawah ini penjelasannya.
REST

Apa itu REST (REpresentational State Transfer) ?
menurut laman TutorialPoints REST itu : REST stands for REpresentational State Transfer. REST is a web standards based architecture and uses HTTP Protocol for data communication. It revolves around resources where every component is a resource and a resource is accessed by a common interface using HTTP standard methods.
jadi kalau tidak salah kesimpulan penulis tentang REST singkatnya sepeti ini, REST Merupakan standard dalam arsitektur web yang menggunakan Protocol HTTP untuk pertukaran data. Rest merupakan salah satu metode dari implementasi Web Services. ada satu metode lain yaitu SOAP (Simple Object Access Protocol). untuk yang ingin tau lebih lanjut silahkan mampir ke TutorialPoints.

sudah kenalan dengan REST kan.  sekarang kita masuk ke materinya.

Bahan yang diperlukan :

    Python 3.6.3
    Flask
    Flask-SQLAlchemy
    Flask-Restful
    SQlite3
    Jsonify

Lest get started

Rest punya 4 opsi method

    GET
    PUT
    POST
    DELETE

disini penulis akan menggunakan method GET dulu, method yang lain akan di kerjakan nanti.

sebelum masuk ke code, download terlebih dahulu databasenya disini,  kita akan menggunakan SQLite, pembahasan SQLite akan di post nanti. dan extract file bernama chinook.db ke folder project , misalnya 'python_rest'. setelah download file db, lalu buat file server.py di folder 'python_rest'

Lalu kita buat virtual environment untuk Python 3.6 setelah install paket2 yang diperlukan lalu di aktifasi.
