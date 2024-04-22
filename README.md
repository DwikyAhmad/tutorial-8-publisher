# tutorial-8-publisher

a. How many data your publlsher program will send to the message broker in one
run?

Publisher akan mengirimkan 5 data ke message broker, terlihat dari fungsi main yang melakukan call publish_event sebanyak 5 kali

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?

Publisher dan subscriber terhubung dengan message broker yang sama melalui protokol amqp dengan parameter koneksi yang sama, hal ini membuat publisher dan listener dapat saling berkomunikasi.