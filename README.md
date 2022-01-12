# Simulasi blockchain menggunakan Python3 #

## Api endpoints

* Menampilkan daftar block
```
GET /blockchain
```

* Lakukan mining
```
GET /mine
```

* Buat transaksi baru
```
POST /transactions/new
content-type: application/json

{
    "sender": "dslddsiodowjheoldsllssd",
    "recipient": "sduowoeksldsdooslsdsp",
    "amount": 10
}
```