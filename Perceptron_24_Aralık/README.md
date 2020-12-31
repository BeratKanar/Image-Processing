# FUNCTIONS

## activation_fn(self,x) Aktivasyon fonksiyonu , gelen x değerine göre 1 veya 0 döndürür.

## predict(self,x) Insert fonksiyonu ile x' 1 ve 0 değerini ekler.Ardından T nin transpozunu alır x le çarpar ve z ye atar.Daha sonra activation fonksiyonuna yollar ve 0 dan küçük olup olmadığını kontrol eder.

## fit(self , X ,d) Her Epoch için w değerlerini tüm train seti boyunca günceller.Güncelleme yapılırken bias da input olarak eklenir.

# İmza Tanıması İmza için X ve d , boy ve en e eşit olur.(mxnxn3) =>image_1.reshape(mn3,1) =>m,n=100 ise 40 imza için X ve d değerleri (1001003,40) olur
