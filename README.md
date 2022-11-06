# Kodluyoruz-proje1
Insertion Sort Projesi

#[22,27,16,2,18,6]-> Insertion Sort

##1 Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

#Bu sayı öbeğinin en küçüğünü en başa yazıp en başta olanla yerini değiştir.

#[2,27,16,22,18,6]
#[2,6,16,22,18,27] ikinci elemandaki sayının en küçük olması gerekiyor.
#[2,6,16,18,22,27] artık sıralandı.

##2 Big-O gösterimini yazınız.

#O(n^2)

##3 Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, 
##Best case: Aradığımız sayının dizinin en başında olması.

##Average case göre sıralama  [2,6,16,18,22,27]
##Worst case göre sıralama  aradığımız sayının yani en küçük elemanın sonda olması gerekiyor.Diziyi buna göre
##sıraladığımızda [27,22,18,16,6,2]  şeklinde olur.
##Best case göre sıraladığımızda aradığımız sayının dizinin en başında olması gerekiyor. [2,6,16,18,22,27] şeklindedir.


##Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

#[2,6,16,18,22,27]  18 sayısı ortada olduğu için average case kapsamına girer.

##[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

##Dizideki en küçük sayının en başa gelip onunla yer değiştirmesi gerekiyor böylelikle birinci eleman en küçük olmuş oluyor. Daha sonra ikinci eleman en küçük olacak şekilde sıralama ilerliyor.

##[2,3,5,8,7,9,4,15,6]
##[2,3,4,8,7,9,5,15,6]
##[2,3,4,5,7,9,8,15,6]
##[2,3,4,5,6,9,8,15,7]

##Patika.dev](https://www.patika.dev/tr)
