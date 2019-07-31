# Real Player Game
### oop-rpg-cli

**Pendahuluan :**

Game ini bercerita tentang sebuah pertarungan antara Hero melawan Maou-sama. Beranggapan bahwa di dunia itu sedang terjadi pertempuran antara kedua kubu, sehingga selama berabad - abad semua kehidupan menjadi sengsara, player yang berperan sebagai hero akan melawan semua bawahan Maou-sama. Hero memiliki sebuah class yang terdiri dari Knight , Mage dan Archer. Sedangkan untuk lawannya dari bawahan Maou-sama terdapat Witch , Troll , Ogre dan Dragon. Akankah Hero dapat menyelamatkan dunia?

**Konsep:**

Main konsep pada game ini adalah pertarungan dengan based-turn. Dengan dibekali dengan basic-stat seperti STR, AGI, INT dengan pertimbangan class yang dipilih. Lalu sistem Level (LVL) yang akan menambah basic-stat setiap naik level. Ditambah MAGIC yang dimiliki oleh setiap Character di Game, MAGIC pada setiap Character berbeda - beda.

- STR : Merujuk pada Health Point dan Basic Attack
- INT : Merujuk pada Mana Point dan Magic Attack
- AGI : Merujuk pada Speed Turn dan Evasion

**Calculation:**
HP = STR * 1.8

**Hero Charachter :**
> Knight : 
- Seorang dengan jiwa kesatria, berani membawa keadilan bagi para rakyatnya 
- Special-basic-stat (STR)
- Skill : Holy Divine (Menambah HP * 0.25 (STR) dan BA * 0.02 (STR + INT))

> Mage :
- Seorang dengan jiwa yang bijaksana, mampu membawa kedamaian bagi semua orang.
- Special-basic-stat (INT)
- Skill : Inferno (Attack 
