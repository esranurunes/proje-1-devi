# proje-1-devi
proje 1 ödevi
[22,27,16,2,18,6] -> Ekleme Sıralaması
1. Yukarıya verilen derece derecesini aşamalarını onaylar.
Algoritma oynayarak onu satın alınabilir ileri doğru ilerler, bir parçayı satın alır üzerinde doğru elemanlar ile bir sıralar ve ona doğru elemanlarla bir sıra elemanlarından daha küçükse o elemanla yer bir uç atar.

ilk adın başınamız için ( 22 ) kendi sıralıdır. Hiç bir okula devam eder.

1.Adım	22	27	16	2	18	6
22 verisi ve 27 verisi deneme yapılır. 22, 27 küçük ilk iki veri tamamlanır. neredeyse bir kolaylıkz.

2. Adım	22	27	16	2	18	6
16 ile bir gerisindeki sayıyı karşılaştırır 16, 27 den küçük. 16 ile 27 yer yani takas yapar. Daha sonra tekrar 16 ile 22 ü kıyaslar 16, 22 den düşük. 16 ile 22 yer değiştirin.

3. Adım	22	16	27	2	18	6	-->	16	22	27	2	18	6
2 ile bir gerisindeki sayıyı karşılaştırır 2, 27 den küçük. 2 ile 27 yer yani takas yapar. Daha sonra tekrar 2 ile 22 ü kıyaslar 2, 22 den düşük. 2 ile 22 yer değiştirin. Daha sonra tekrar 2 ile 16 kıyaslar 2, 16 den küçüldü. 2 ile 16 yer değiştirin.

4. Adım	16	22	2	27	18	6	-->	16	2	22	27	18	6
-->	2	16	22	27	18	6
18 ile bir gerisindeki sayıyı karşılaştırır 18, 27 den küçük. 18 ile 27 yer yani takas yapar. Daha sonra tekrar 18 ile 22 kıyaslar 18, 22 den küçülmüş. 18 ile 22 yer değiştirin. Daha sonra tekrar 18 ile 16 kıyaslar 18, 16 den de oranda. neredeyse bir kolaylıkz.

5. Adım	2	16	22	18	27	6	-->	2	16	18	22	27	6
6 ile bir gerisindeki sayıyı karşılaştırır 6, 27 den küçük. 6 ile 27 yer yani takas yapar. Daha sonra tekrar 6 ile 22 kıyaslar 6, 22 den küçülmüş. 6 ile 22 yer değiştirin. Daha sonra tekrar 6 ile 18 kıyaslar 6, 18 den küçüldü. 6 ile 18 yer değiştirin. Daha sonra tekrar 6 ile 16 kıyaslar 6, 16 dan de oldu. 6 ile 16 yer değiştir

6.Adım	2	16	18	22	6	27	-->	2	16	18	6	22	27
6.Adım	2	16	6	18	22	27	-->	2	6	16	18	22	27
2. Büyük-O gösterimini yazınız.
O(n^2)

3. Zaman Karmaşıklığı:
- En kötü ihtimal: Aradığımız sayının sonda olması,
Tam kısa dizi, durumda bu durumda onun bir parçası bir gerisindekinden küçük olacaktır. Dolayısıyla 1inci eleman için iç model 0 2 eleman için doğru 1, 3. 3 4 5 6… n kadar yukarı harekettır. Yani 0+1+2+3+4…..+n-1 = [n*(n-1)]/2 : n^2

- Ortalama vaka: Aradığımız sayının ortada olmaması,
En kötü durum ile en iyi casein ortalamasını hedefinde n^2 olarak buluruz.

- En iyi durum: Aradığımız sayının en başında olması.
Tam sıralı, n tane sayinin üzerinden birer defa geçer ve hiç bittiğinde doğru ilerletme olması gereken için bu tek geçişle kalır. Yani n

4. Diziden sonra 18 sayı hangi davaya giriş yapılacak? Yazınız.
Veri setinin kullanımına yönelik olarak ortalama vaka kapsamına girer.

2. [7,3,5,8,2,9,4,15,6] dizinin Ekleme Sırala'a göre ilk 4 adımını yazın.
1.Adım	7	3	5	8	2	9	4	15	6
2. Adım	3	7	5	8	2	9	4	15	6
3. Adım	3	5	7	8	2	9	4	15	6
4. Adım	3	5	7	8	2	9	4	15	6
