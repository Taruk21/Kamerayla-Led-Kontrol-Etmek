# ArduinoVePython1
Arduinoya bağladığımız ledleri opencv yardımıyla kameradan kontrol edeceğiz 
---------------------------------------------------------------------------
Bağlantı.png dosyasındaki gibi ardunio ve ledleri birbirine bağlayalım eğer led ler 5w desteklemiyorsa ( genelde yeşil ledler tek destekler ) 220ohm lık dirençler kullana bilirsiniz.
çalıştırmak için ise ilk öncelikle terminali açıp altaki komutları girerek gerekli kütüphaneleri kuralım.

`pip install cv2`

`pip install mediapipe`

Kütüphaneler kurulduktan sonra arduino uno yu bilgisayara bağlayalım ve FRİMİTA.cpp dosyasını Arduino İDE programında açıp arduino kartına kuralım.
Kurduktan sonra aygıt yöneticisinden veya Arduino İDE programından arduino uno nun hangi coma bağlı olduğunu bulalım.
Bulduktan sonra controller.py dosyasında girip comport bölümüne comu yazalım örnek

![örnek resim](https://github.com/Taruk21/hebele/blob/main/com%20%C3%B6rnek.png)

Yazdıktan sonra main.py dosyasına girip çalıştıralım ondan sonra kameraya elimizi göstermemiz yeterlidir eğer hatalı birşey yapmışsanız bana instegram veya discordan ulaşa bilirsiniz
