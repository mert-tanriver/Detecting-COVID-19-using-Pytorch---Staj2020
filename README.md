# staj2020

					-KURULUM TALİMATLARI-

Kodun çalışması için Visual Studio Code editörü kullanılmıştır.Aşağıdaki linkten güncel sürüm indirilebilir.
Rapor içerisinde kullanılan kütüphanelere yer verilmiştir.Kütüphanelerin "pip install kütüphane_ismi" komutu
ile indirilmesi gerekmektedir.Ardından VS Code içerisinde Python extension da yüklenmelidir.
* https://code.visualstudio.com/

VS Code'un indirilmesi ardından 64 bit Python Interpreter bilgisayara indirilmelidir.
* https://www.python.org/downloads/

pylint "max" member hatası için VS Code'da aşağıdaki aşamalar yapılmalıdır:
Basınız: CTRL + Shift + P

Tıklayınız "Preferences: Open Settings (JSON)"

Bu satırı belirtilen dosyaya ekleyiniz JSON : "python.linting.pylintArgs": ["--generate-members"] 

torch kütüphanesi için indirme linki : ttps://pytorch.org/

Kurduğumuz bütün paketler (pip install):
os
shutil
numpy
matplotlib
PIL

Kodu çalıştırmak için proje, klasör olarak VS Code'a eklenmelidir.
Çalıştırmak için terminale "py covid.py" komutu girilebilir. 

Projenin işlem süresi (10 dakika) aşağıdaki bilgisayar özelliklerine göredir ve bilgisayarlara göre değişebilir:
Intel i7 9750H 
16 Gb 2400 Mhz Ram
GTX 1650 4GB

Dorukhan DOĞAN - 17290026
Mert TANRIVER - 17290060
