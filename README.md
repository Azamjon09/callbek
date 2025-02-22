![Screenshot 2025-02-22 013558](https://github.com/user-attachments/assets/72ca4759-8a7b-4f4c-a373-5763651e86ed)


# callbek
Албатта, ин аст тарҷумаи изҳороти "Занги бозпас дар JavaScript ин функсияест, ки ба вазифаи дигар ҳамчун аргумент интиқол дода мешавад ва баъдан вақте ки ин функсия иҷрои худро анҷом медиҳад, даъват карда мешавад.

Мақсад: Усули forEach барои сохтани як дастгоҳи муайян барои ҳар як элементи массив истифода мешавад.
Хусусиятҳои онҳо:
![Screenshot 2025-02-22 013643](https://github.com/user-attachments/assets/4e49af3c-d87f-41a6-a4fc-865446c8687f)
Қайд нагардонидани массиви нав: forEach худаш массиви наверо барнамагардонад. Ин як қисми асосии он аз усулҳои харитаи филтр, ки навро бар асоси сохтани массивҳои коллбэкгардонанд. Таъсироти паҳлуӣ: forEach вақти барои пайдо кардани онҳо истифода мешавад, ки таъсири паҳлуӣ доранд, ба монанди: Тағир додани элементҳои аслии массив. Сабт кардани маълумотҳо дар консол. Навсозии DOM (Modeli Object Document) - и саҳифаи веб.

Усули map()JavaScript воситаи пурқувват барои табдил додани массивҳо мебошад. Ин аст тақсимот:
Он чӣ кор мекунад:
![Screenshot 2025-02-22 013825](https://github.com/user-attachments/assets/b1b4aade-e79f-4d48-8945-a5d39189f165)
Массиви нав эҷод мекунад: Он массиви аслиро тағир намедиҳад. Функсияро татбиқ мекунад: Ин функсия барои ҳар як унсури массиви аслӣ даъват карда мешавад. Арзишҳои нав тавлид мекунад: Функсияи пешниҳодкардаи шумо муайян мекунад, ки кадом арзишҳо дар массиви нав ҷойгир карда мешаванд. Нуқтаҳои асосӣ:
![Screenshot 2025-02-22 013917](https://github.com/user-attachments/assets/73cee25c-2535-450c-8904-899cf5580b30)
Табдилдиҳӣ: Ин барои сенарияҳое, ки шумо бояд маълумотро дар як массив тағир диҳед (масалан, табдил додани ҳарорат, ҳисоб кардани квадратҳо ва ғайра) беҳтарин аст. чандирӣ: Функсияи пешниҳодкардаи шумо метавонад ҳама гуна амалиётро дар элемент иҷро кунад, ки ба шумо чандирии бузург медиҳад.

filter()усулро дар JavaScript хуб дарк кардаед .
Ин аст тақсимот:
![Screenshot 2025-02-22 014009](https://github.com/user-attachments/assets/dfd6d113-b116-4283-83d2-28380c5192c3)
Мақсад: Ин filter()усул массиви наверо эҷод мекунад, ки дорои танҳо унсурҳои массиви аслӣ мебошад, ки шарти мушаххасро қонеъ мекунанд. Чӣ тавр он кор мекунад: Он аз болои ҳар як унсури массиви аслӣ такрор мекунад. Барои ҳар як элемент, он функсияи пешниҳодшударо иҷро мекунад ("функсияи бозгашт"). Агар функсияи бозхонд trueбарои як элемент баргардад, он элемент ба массиви нав дохил карда мешавад. Агар функсияи бозгашт баргардад false, элемент хориҷ карда мешавад. Хусусиятҳои асосӣ: Массиви нав: Ҳамеша массиви навро бармегардонад; он массиви аслиро тағир намедиҳад. Филтр: Беҳтарин барои интихоби унсурҳо дар асоси меъёрҳои мушаххас (масалан, рақамҳои ҷуфт, хосиятҳои мушаххаси объектҳо ва ғайра).
![Screenshot 2025-02-22 014009](https://github.com/user-attachments/assets/3f5fd969-2fd8-4a91-9017-64acb5f472f3)
Мақсад: Усули пайдо кардани ҳаракат барои элементи аввалин массив истифода мешавад, ки шарти додашударо ҷамъ мекунад. Баргардонидан: Агар элементе пайдо шавад, ки шартро қонеъ мекунад, ин усули он элементи аввалинро бармегардонад. Агар ягон элемент шартро қонеъ накунад, он undefined-ро бармегардонад.
Усули нав: toSorted усули навест, ки дар версияҳои охирини забони JavaScript илова карда шудааст. Шабеҳ ба sort: Ин усул ба усули сорт шабеҳ аст, аммо ҳадди имкон дорад. Копиро бармегардонад: toSorted массиви аслиро шакли намедиҳад, балки нусхаи тартибдодашуда бармегардонад. нигоҳдории бехатарӣ: Ин нигоҳ накарда ки шумо маълумоти аслиро ҳифз кунед, бехатариро нигоҳ доред.
![image](https://github.com/user-attachments/assets/9c9b91d9-2385-4073-baa3-1c6e487298ed)
Мақсад: Усул reduce()тавассути массив такрор мешавад ва ба ҳар як элемент функсияи бозхондро татбиқ мекунад. Ин функсия унсури ҷорӣро бо натиҷаи амалиёти қаблӣ муттаҳид мекунад. Хусусиятҳои асосӣ: Ҷамъкунӣ: Он як арзиши ягонаро тавассути муттаҳид кардани элементҳо ҷамъ мекунад. Фасеҳӣ: Барои доираи васеи амалиётҳо истифода бурдан мумкин аст: Ҷамъбасти ҳамаи элементҳо дар массив. Ҷустуҷӯи арзиши ҳадди аксар ё ҳадди аққал. Эҷоди объект аз массиви объектҳо. Ҳамвор кардани массиви лонашуда. Арзиши ибтидоӣ: Шумо метавонед арзиши ибтидоиро барои аккумулятор пешниҳод кунед. Агар арзиши ибтидоӣ дода нашавад, унсури якуми массив ҳамчун арзиши ибтидоӣ истифода мешавад ва такрор аз элементи дуюм оғоз мешавад.
![image](https://github.com/user-attachments/assets/af7757e6-2b1a-469e-ae3c-3f1e892ff3c7)






