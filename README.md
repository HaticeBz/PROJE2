# **PROJE2**
## SORU1:
[16, 21, 11, 8, 12, 22] -> Merge Sort     
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.   

Önce diziyi küçük parçalara ayıracağız.

Aşama1 : [16,21,11],[8,12,22]      
Aşama2 : [[16],[21,11]],[[8],[12,22]]   
Aşama3 : [[16],[21],[11]],[[8],[12],[22]]

Şimdi küçük parçalara ayırdığımız diziyi sıralama yaparak büyük parçalar haline getireceğiz.

Aşama1 : [[16],[11,21]],[[8],[12,22]]   
Aşama2 : [[11,16,21]],[[8,12,22]]   
Aşama3 : [8,11,12,16,21,22]

Sonuç : [8,11,12,16,21,22]

## SORU2: 
Big-O gösterimini yazınız.   
Diziye Merge Sort uygularken diziyi bölüp tekrar birleştirerek işlem yaptığımızdan dolayı Big-O gösterimi O(n log(n)) olarak ifade edilir.
