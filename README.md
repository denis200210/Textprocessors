# Textprocessors
Создаем файл file1.txt с помощью такого приложения

![image](https://user-images.githubusercontent.com/71909269/161757161-56b1e23b-90fc-4099-b419-b252d78bb6d8.png)


![image](https://user-images.githubusercontent.com/71909269/161692240-06229dcc-9d06-4bd3-93f4-6520f15e84d3.png)

Выберем последние 40 строк из file1.txt и записываем в file2.txt. Командой:tail -n 40 file1.txt >> file2.txt

![image](https://user-images.githubusercontent.com/71909269/161692642-cff8a2f9-e9a2-4c94-b1af-232116c1aa79.png)

Запишем первые 10 строк из file2.txt в file3.txt. Командой:head -n 10 file2.txt >> file3.txt

![image](https://user-images.githubusercontent.com/71909269/161693019-0e2ed892-de48-44c1-8dc7-f21e4f15b448.png)

Выберем строки из file2.txt, содержащие “коко”, заменим в них “коко” на “куку” и запишем в file3.txt

![image](https://user-images.githubusercontent.com/71909269/161693288-d1663f16-4b2e-4296-af0e-4d26eb03611f.png)

Уникальные строки и вывести количество каждой строки
sort file3.txt | uniq -c >> final.txt
![image](https://user-images.githubusercontent.com/71909269/161753325-4c027398-0502-4e56-aa8f-e13614be44e8.png)

rm -rf file3.txt
mv final.txt file3.txt

![image](https://user-images.githubusercontent.com/71909269/161754376-5b3300b5-2c11-4c51-a086-c1ec17547ba6.png)

![image](https://user-images.githubusercontent.com/71909269/161705198-225e92c6-0912-4c7c-b3a5-68e470e2de3e.png)
