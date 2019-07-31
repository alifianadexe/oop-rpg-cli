# Real Player Game
### oop-rpg-cli

> Pendahuluan

Game ini bercerita tentang sebuah pertarungan antara Hero melawan Maou-sama. Beranggapan bahwa di dunia itu sedang terjadi pertempuran antara kedua kubu, sehingga selama berabad - abad semua kehidupan menjadi sengsara, player yang berperan sebagai hero akan melawan semua bawahan Maou-sama. Hero memiliki sebuah class yang terdiri dari Knight , Mage dan Archer. Sedangkan untuk lawannya dari bawahan Maou-sama terdapat Witch , Troll , Ogre dan Dragon. Akankah Hero dapat menyelamatkan dunia?


> Konsep

Main konsep pada game ini adalah pertarungan dengan based-turn. Dengan dibekali dengan basic-stat seperti STR, AGI, INT dengan pertimbangan class yang dipilih. Lalu sistem **Level (LVL)** yang akan menambah basic-stat setiap naik level. Ditambah MAGIC yang dimiliki oleh setiap Character di Game, MAGIC pada setiap Character berbeda - beda.

MAGIC pada setiap memiliki karakteristik tersendiri, terdapat magic yang bisa bersifat buff dan ada lagi magic on turn, tergantung pada Magic yang dimiliki oleh setiap character. 

TURN pada game ini akan ditentukan oleh Turn Speed setiap character, sehingga jika turn speed character lebih besar dari character lain (lawan) maka character tersebut akan beraksi terlebih dahulu dan setiap turn memiliki max cost turn sebesar 50. Jika terdapat character yang memiliki turn speed lebih dari max cost turn, Maka sisa dari turn speed itu akan diakumulasikan ke turn berikutnya.

Setiap turn setiap character akan mendapatkan regen HP dan regen MP sesuai dengan stat mereka masing - masing.

**BASIC STAT Explain : **

- STR : Merujuk pada Health Point dan Basic Attack
- INT : Merujuk pada Mana Point dan Magic Attack
- AGI : Merujuk pada Turn Speed dan Evasion

Setiap character Level Up maka basic stat akan ditambah 2 point. dan ketika level up maka Exp Requirement nya pun akan ikut naik.


**Hero Charachter**
> Knight 
- Seorang dengan jiwa kesatria, berani membawa keadilan bagi para rakyatnya 
- Special-basic-stat (STR)
- Skill : Holy Divine (Add HP * 3(STR) and Basic Attack * 0.6(STR) + 0.1(INT)) , Only last up for 3 Turn

> Mage
- Seorang dengan jiwa yang bijaksana, mampu membawa kedamaian bagi semua orang.
- Special-basic-stat (INT)
- Skill : Inferno (Attack an enemy in Magic Attack that have damage equal to (Magic Attack + (INT * 5))

> Archer
- Seorang dengan mata elang, yang dapat melihat ke dalam hati manusia
- Specisal-basic-stat (AGI)
- Skill : Heaven's Wind (Add Basic Attack + (Magic Attack + 0,075) + (AGI * 0,25) , Add Evasion + (AGI * 0,175) , Add )

