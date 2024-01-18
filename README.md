# ¿Qué es PortaSense?
**PortaSense** es un proyecto inspirado por las personas que comienzan con una persona con demencia en su casa o simplemente para un ámbito de seguridad.

Este proyecto consta principalmente de 2 dispositivos distintos, un dispositivo portátil y una centralita.
- Dispositivo Portátil: Este dispositivo consta de un microcontrolador ESP32 que gestionará los sensores deseados y enviar los datos a la centralita, en este caso un Sensor PIR (Sensor de Movimiento)
- Centralita: Este dispositivo consta de un microcontrolador ESP32 que gestionará la conexión de 1-20 dispositivos portátiles y posteriormente 
Sensor de movimiento inalámbrico que se puede colocar en cualquier lugar con una interfaz web y una centralita que recibe todos los datos vía ESP-NOW.

Este proyecto se está creando con micropython para la parte de los microcontroladores ESP32 y con python (Reflex) para la parte Web.

# Módulo Sensor Inalámbrico (Microcontrolador Esclavo)
 **HARDWARE:**
 
- [ESP32 D1 MINI](https://www.amazon.es/AZDelivery-Bluetooth-Desarrollo-Internet-compatible/dp/B08BTLYSTM/ref=sr_1_5?crid=2FLT0Q20T8M2C&keywords=esp32%2Bmini&qid=1704080852&sprefix=esp%2Bmini%2Caps%2C111&sr=8-5&th=1) **x1**
- [Pantalla OLED 0,91 Pulgadas I2C DC 3,3 V ~ 5 V](https://www.amazon.es/RUIZHI-Pulgadas-Display-Controlador-Pantalla/dp/B0CN8J64WV/ref=sr_1_27?__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=HTUXCNCSUGXH&keywords=lcd+for+esp32&qid=1704080011&sprefix=lcd+for+esp32%2Caps%2C94&sr=8-27)  **x1**
- [Batería recargable AAA1.5V de iones de litio, 8800mAh, 1,5 V, AAA](https://es.aliexpress.com/item/1005006185354411.html?spm=a2g0o.productlist.main.21.13f37d6bRVV1S0&algo_pvid=384aeed8-4d82-498d-834b-b01e2722d872&algo_exp_id=384aeed8-4d82-498d-834b-b01e2722d872-10&pdp_npi=4%40dis%21EUR%2111.78%210.99%21%21%2190.37%21%21%40210387dd17040793591945804e7926%2112000036180435168%21sea%21ES%214613488704%21AB&curPageLogUid=1Jn9aLpZASci)  **x4**
- [Conector USB tipo C](https://es.aliexpress.com/item/1005006224531815.html?src=google&aff_fcid=c615c86bd97d43fab47ad2b506eb74bc-1704080169767-05580-UneMJZVf&aff_fsk=UneMJZVf&aff_platform=aaf&sk=UneMJZVf&aff_trace_key=c615c86bd97d43fab47ad2b506eb74bc-1704080169767-05580-UneMJZVf&terminal_id=2e966bb2dfd149cbb9f9f432eafd1f10&afSmartRedirect=y) **x1**

 
# Centralita (Microcontrolador Maestro)
**HARDWARE:**
 
- [ESP32 D1 MINI](https://www.amazon.es/AZDelivery-Bluetooth-Desarrollo-Internet-compatible/dp/B08BTLYSTM/ref=sr_1_5?crid=2FLT0Q20T8M2C&keywords=esp32%2Bmini&qid=1704080852&sprefix=esp%2Bmini%2Caps%2C111&sr=8-5&th=1) **x1**
# Web
