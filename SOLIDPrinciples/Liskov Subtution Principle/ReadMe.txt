﻿Liskov Substitution Principle

-Alt sınıflarda oluşan nesneler üst sınıflardan oluşan nesneler ile yer değiştirilebilir olmalıdır. 
-Örneğin, karenin ve dikdörtgenin alanını hesaplayan basit bir uygulamamız olsun. Bir dikdörtgen sınıf oluşturarak bu sınıfa 2 member veriyoruz. Yüksekllik ve uzunluk, fakat kare geometrik şekili için bu ata sınıf çokta uygun olmamaktadır. Yani dikdörtgen sınıfından kalıtım alan bir kare sınıfından nesne oluşturmaya kalkarsak ata sınıfların mantığından ve amacından şaşmış oluyoruz ve bu prensibe ters düşmüş oluyoruz. Bu hatayı düzeltmek için dörtgen yapısnın ortak özelliklerini barındıracak bir sınıf oluşturulmalı ve her bir geometrik şekil için bir sınıf oluşturularak kendi alan hesaplamalarına sahip olduğundan emin olmalıyız.
