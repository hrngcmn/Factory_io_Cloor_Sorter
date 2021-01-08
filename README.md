# Factory IO Cloor Sorter

S7-1500 PLC ile Tiaportal Üzerinden ladder diyagramını oluşturduğum renk ayırıcı projemin, S7-PLCSIM ve Factory io üzerinden simülasyon edilmesini içerir. 

## Çalışma mantığı. 
* Birinci konveyöre sürekli yeşil, mavi ve metal maddegirişi olmaktadır.
* Bu maddelerin renklerine göre ayrıştırılması amaçlanmıştır. 
* Uvision sensörler sayesinde renk algılanması yapılmaktadır.
* Pivot Arm Sorter sayesinde maddelerin bant sisteminden ittirilme işlemi gerçekleştirilmektedir.
* Projede üç tane konveyör kullanılmaktadır.
* Üçüncü konveyörün çalışması enerji tasarrufu sağlanması maksadıyla, 1. konveyör çalıştıktan 10 sn sonra devreye girmektedir. 
* Maddeler ittirildikten sonra kaydırma düzeneğinden kaydırılır.
* Mavi maddeler 1. Pivot Arm Sorter ile, yeşil maddeler 2.  Pivot Arm Sorter ile bant sisteminden ayrılır. Metal maddeler ise bant sisteminden ayrılmayarak yoluna devam eder. 
## Projeye Genel Bakış(Factory IO)
Renk ayrıştırıcı projemin genel görünümü aşağıdaki şekilde verilmiştir.
![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/projeye%20genel%20bak%C4%B1%C5%9F.png?raw=true)
## Pivot Arm Sistem ve uvision sensör konumlandırılması
 ![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/Screenshot_1.png?raw=true)
 ## Pano görüntüsü 
![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/pano.png?raw=true)
## Ayırıcıların yerleştirilmesi
![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/Screenshot_2.png?raw=true)
## Kuş bakışı
![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/ku%C5%9F%20bak%C4%B1%C5%9F%C4%B1.png?raw=true)
## PLC Bağlantısı
![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/plc%20ba%C4%9Flant%C4%B1s%C4%B1.png?raw=true)

# Tia Portal / Ladder Diyagram oluşturulması
### PLC Taglarının isimlendirilmesi
![plctag.png](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/plctag.png?raw=true)

## Ladder Diyagramı
![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/nw1,2,3.png?raw=true)

![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/nw4,5,6.png?raw=true)
![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/nw7,8,9.png?raw=true)
![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/nw10,11,12.png?raw=true)
![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/nw13.png?raw=true)

## S7-PLCSIM 
 
![enter image description here](https://github.com/hrngcmn/Factory_io_Cloor_Sorter/blob/main/PLCSIM.png?raw=true)
