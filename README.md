# selenium_automation_MTS
Work automation selenium for view indicators
 - Автоматизированное управление браузером, для вывода информации с ajax (indicators)
 - Некоторые опции для упрощенного запуска chrome
 
![изображение](https://user-images.githubusercontent.com/112577182/207608450-083c0abd-b4b6-4582-b61e-e25aeae3c39f.png)

- В цикле реализована проверка открытых urls, если не совпадают при определенных статусах попытается переподключиться.
- Из-за того, что  используется ajax, информация подгружается с задержкой, поэтому возникают проблемы если соединение нестабильное, легкий путь slee (не решено)

![изображение](https://user-images.githubusercontent.com/112577182/207609376-d02462c0-71b1-4097-8021-3aac0c767409.png)

Indicators (blurred screen)

![изображение](https://user-images.githubusercontent.com/112577182/207607883-cb753a2a-61ab-481a-8fc3-df5d5387301d.png)
