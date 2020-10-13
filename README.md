# current-apps 
aplikasi ini adalah untuk menghitung atau mengkonversi mata uang dolar ke rupiah 
dengan apps ini kita bisa dengan mudah menghitung uang dolar ke rupiah
# Scope & Functions
-pengguna dapat memasukkan angka 
-pengguna tidak dapat menulis huruf di apps
# How Does it works?
'''
public string usdToIdr(string nominal)
        {
            var nominalDouble = Convert.ToDouble(nominal);
            var result = nominalDouble * 15000;
            return Convert.ToString(result);
        }
'''




# Pemrog Lanjut jawab soal 

1)	Mengapa perlu membuat class CurrencyController.cs pada percobaan 4 ?
2)	Jelaskan kegunaan method isAllowed pada percobaan 4!
3)	Jelaskan secara singkat mengenai Regex pada percobaan 4!
4)	Buatlah class diagramnya pada percobaan 4! 

1.	Class CurrencyController.cs adalah coding yang telah kita buat dan untuk mengontrol aplikasinya.
2.	Method isAllowed berfungsi untuk menentukan karakter seperti angka atau huruf apakah sesuai apa tidak seperti yang kita inginkan
3.	Regex berfungsi untuk mencari angka yang dimasukkan ke method isAllowed 
4.	 	


