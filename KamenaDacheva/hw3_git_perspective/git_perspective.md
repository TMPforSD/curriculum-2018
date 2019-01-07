# Git Perspective

*Git* перспективата има за цел да предостави опростен интерфейс за най-често срещаните операции на git. 

На наше разположение се намират конзола, Workspace менюто и самият Git компонент, чрез който ще може да управляваме нашите репозиторита.

![gitPerspective](/images/1.jpg)

## Clone Project
Клониранет на проект се случва чрез бутона *+*, който се намира в Git компонента. Необходимо е да се въведе линк д желаното репозитори, както и username и парола. 

![clone](/images/2.jpg)

При успешно свързване и реализиране на компандата ще бъде изписано съобщение за успех в конзолата. Ако са възникнали някакви проблеми отново ще бъдат изписани в конзолата.

![console](/images/2_1.jpg)

След като репозиторито бъде успешно клонирано на наше разположение са видими всички файлове и папки, които се намират в него. 

![folders](/images/2_2.jpg)

Върху отделните файлове могат да се извършват операциите Pull, Push, Reset и Share.
![actions](/images/2_3.jpg)

## Pull All
Pull All командата служи за обновяване с най-новите версии на всички репозиротира от Workspace-а. Необходимо е въвеждането на потребителско име и парола за изпълняване операцията. 

![pullAll](/images/3.jpg)

## Push All
Push All командата служи за качване на направените промени в Git. За направата на тази операция е необходимо да се въведе подходящо съобщение, потребителско име, парола и имейл.

![pushAll](/images/4.jpg)

## Merge conflict 
В случай на конфликт между версията налична в Workbench и Git след работа с Push, ще бъде създаден нов клон с вашите промени. От там насетне можете да използвате предпочитание инструмент за сливането на двете налични версии.