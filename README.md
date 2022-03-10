# hse_hw2_chip
## Целевой объект
Клеточная линия: GM23248  
Гистоновая метка: H3K9me3
## Google colab
https://colab.research.google.com/drive/1PnlmsS7in_Cbz_nc2z8aBmzUe7c3PssB?usp=sharing
## FastQC
![image](https://user-images.githubusercontent.com/93263163/157728687-11fe19cf-5455-4e1c-bd16-699bee4bf039.png)
![image](https://user-images.githubusercontent.com/93263163/157729271-86886c87-8a22-4a1b-a777-8b3ed785f8b5.png)
![image](https://user-images.githubusercontent.com/93263163/157729127-dfb41e70-9876-4a58-8f5b-cbfaf86c6e2f.png)
![image](https://user-images.githubusercontent.com/93263163/157729353-a740a757-c3bb-4d38-9607-9a0e4d0d1cac.png)
![image](https://user-images.githubusercontent.com/93263163/157729413-c300277e-cb04-4188-a5cd-932b74459a1f.png)
![image](https://user-images.githubusercontent.com/93263163/157729503-ac553e0f-ff09-478a-8a45-e4776bc65066.png)
CG несколько отличается от теоретического распределения, хотя не сильно отличается от нормального. В остальном, как можно посмотреть в данных, существенных отклонений нет.
## Выравнивание на 7 хромосому
||ENCFF422LCV|ENCFF118JBS|ENCFF127SEC|
|----|----|----|----|
|Ридов|28962089|29882617|13477857|
|Уникальных|1802664 (6.22%)|1858233 (6.22%)|797490 (5.92%)|
|Не уникальных|4313967 (14.9%)|4466827 (14.95%)|1384381 (10.27%)|
|Не выровнялось|22845458(78.88%)|23557557 (78.83%)|11295986 (83.81%)|        

Поскольку выравнивание производится только на одну хромосому, закартировалось меньшинство. Для одной хромосомы этого достаточно.
## Диаграммы Виенна
Диаграмма №1 для реплики ENCFF422LCV
![image](https://user-images.githubusercontent.com/93263163/157729581-0d2433c1-2aca-40aa-be00-b396d7de7006.png)
Диаграмма №2 для реплики ENCFF422LCV
![image](https://user-images.githubusercontent.com/93263163/157729843-b3ae254f-fa45-43b3-aea9-0e28fd70d63b.png)
Диаграмма №1 для реплики ENCFF118JBS 
![image](https://user-images.githubusercontent.com/93263163/157730110-9559cc33-efef-4b92-9a39-ad9ec789c2d6.png)
Диаграмма №2 для реплики ENCFF118JBS
![image](https://user-images.githubusercontent.com/93263163/157735217-ff6181ad-0ff9-4939-9c86-a95d4ad46ed9.png)
Поскольку выравнивание производилось только на одну хромосому, пересечений пиков ENCODE и выявленных пиков получилось достаточно мало. Их процент того же порядка, что и при выравнивании (сотые доли), поэтому можно допустить, что результат в пределах нормы.
