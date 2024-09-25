# Tutaj znajdziesz informację w jaki sposób można zaimportować sobie maszynę wirtualną do Waszego VirtualBox'a

## Pobieranie odpowiedniego obrazu
1. Należy pobrać odpowiedni plik stąd - https://download.mikrotik.com/routeros/7.16/chr-7.16.ova

## Import maszyny
2. Uruchomić VirtualBox'a z pendrive używając pliku start_virtualbox.bat

![obraz](https://github.com/user-attachments/assets/32fb13ba-d939-4104-a501-e3ca07b0d314)

4. Z menu plik wybrać "importuj urządzenie wirtualne

![obraz](https://github.com/user-attachments/assets/d1031750-cdd7-422c-a2d2-4bb196e03061)

5. Następnie wskazać miejsce skąd będziemy importować wcześniej pobrany plik

![obraz](https://github.com/user-attachments/assets/e29fd63d-01ff-46f6-8c76-e38692121888)

![obraz](https://github.com/user-attachments/assets/1eb33653-b24b-485d-b86a-973ab3feea54)

6. Klikamy next i na ekranie z parametrami naszej maszyny zmieniamy politykę adresów MAC

![obraz](https://github.com/user-attachments/assets/07be522c-b4e6-483e-8614-f9eb446a375f)

7. Klikamy Zakończ

8. Po udanym imporcie powinna nam się pojawić wirtualna maszyna na liście maszyn

![obraz](https://github.com/user-attachments/assets/8a7573d3-188e-4004-bfae-88a47235edab)

## Zmiana parametrów maszyny w celu posiadania 4 interfejsów sieciowych

9. Na liście maszyn klikamy prawym przyciskiem na naszej zaimportowanej maszynie a następnie wybieramy "Ustawienia"

![obraz](https://github.com/user-attachments/assets/7c680d26-1ac3-43dc-9108-65feee67c3b3)

10. W pierwszej kolejności zachęcam do zmiany nazwy naszej maszyny w okienku "Nazwa"

![obraz](https://github.com/user-attachments/assets/b08c013a-6dd8-4ffe-b617-c02d9de8e54d)

11. Kolejnym krokiem jest uaktywnienie dodatkowych interfejsów ethernet. W tym celu wybieramy z listy po lewej "sieć"
a następnie dla każdej z kart kolejno (Karta 2, Karta 3, Karta 4) zaznaczamy opcję "włącz kartę sieciową". Na ten moment zostawiamy
kartę niepodłączoną, konkretną konfiguracją zajmiemy się później.

![obraz](https://github.com/user-attachments/assets/04024eeb-0aeb-4a4f-88df-9b9e05c1b4f6)












