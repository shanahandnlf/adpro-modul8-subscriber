a. what is amqp?

AMQP atau Advanced Message Queuing Protocol adalah protokol yang digunakan untuk mengirim dan menerima pesan antara aplikasi atau sebuah sistem yang terpisah. AMQP memudahkan pertukaran pesan antar aplikasi yang berbeda. Hal ini dikarenakan AMQP memungkinkan aplikasi yang berbeda untuk berkomunikasi satu sama lain tanpa harus mengetahui detail implementasi dari aplikasi lainnya. Kemampuan ini cocok untuk digunakan jika program kita menggunakan bahasa pemrograman yang berbeda atau berjalan di platform yang berbeda. Secara keseluruhan, AMQP menyediakan kerangka kerja yang kuat untuk integrasi aplikasi yang fleksibel.

b. what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for?

guest:guest@localhost:5672 merupakan sebuah URL yang digunakan untuk mengakses AMQP server. Pada URL tersebut, guest pertama merupakan username untuk autentikasi. Kemudian, guest kedua merupakan password yang digunakan untuk autentikasi juga. Sedangkan localhost:5672 merupakan port dari AMQP server yang akan diakses. Pada kasus ini, AMQP server berada pada localhost dan menggunakan port 5672.