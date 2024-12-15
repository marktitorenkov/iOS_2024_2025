# Създаване на приложение за комикси с VisionKit


Мария обича да създава комикси, но никога не може да намери инструмент, който да й позволи лесно да изрязва графични обекти от снимки и да ги комбинира в уникални панели за комикси. Тя мечтае за приложение, което да й позволи да създава персонализирани комикси, използвайки само своя iPhone и камерата му.

Реализирайте iOS приложение, което позволява на потребителите да създават комикси чрез изрязване на графични обекти от снимки с помощта на `VisionKit`. Приложението трябва да позволява подреждане на тези графични обекти в комикс панели и добавяне на текстови балони, за да разказват история.

Основна функционалност:
-----------------------

1.  **Изрязване на обекти с `VisionKit`**  
    Потребителят може да заснеме или качи снимка и да изреже обекти с VisionKit. Изрязаните обекти се запазват като отделни елементи в библиотека.
    
2.  **Създаване на панели**  
    Приложението трябва да предлага готови шаблони за панели (примерно: 2x2, 3x3 или 4x3), в които потребителят може да поставя изрязаните обекти.
    
3.  **Добавяне на текстови балони**  
    Потребителите могат да добавят текстови балони (диалогови, мисловни и други) с лесно управление на шрифта, размера и позицията.
    
4.  **Редактиране на панели**  
    Панелите могат да се редактират: мащабиране, завъртане, промяна на слоеве, добавяне на ефекти като сенки или филтри.
    
5.  **Експортиране и споделяне**  
    Създадените комикси могат да се експортират като изображения или PDF и да се споделят в социалните мрежи.
    

* * *

Допълнителни функционалности (Bonus):
-------------------------------------

*   **AI разпознаване на обекти**  
    Вграден AI модел може автоматично да разпознава и изрязва обекти на базата на тяхната форма (например: хора, предмети, животни).
    
*   **Онлайн библиотека**  
    Потребителите могат да качват и споделят своите комикси в обща библиотека или да свалят комикси, създадени от други.
    
*   **Колаборативна работа**  
    Разрешете на няколко потребители да работят заедно върху един и същи проект.
    

* * *

Технически изисквания:
----------------------

*   **Използване на VisionKit**  
    За разпознаване и изрязване на обекти от изображения.
    
*   **Firebase Backend**  
    За съхранение на създадените проекти, библиотека с обекти и панелни шаблони.
    
*   **Поддръжка на Drag & Drop**  
    Лесно преместване на елементи между панелите.
    
*   **Локално кеширане**  
    Проектите да могат да се запазват локално, дори без интернет.
    

* * *

Ресурси:
--------

*   Графични иконки за обекти, текстови балони и шаблони.
*   **Wireframes** за основния интерфейс:
    *   Екран за качване/снимане на изображение.
    *   Библиотека с изрязани обекти.
    *   Редактор на панели.
    *   Екран за споделяне.

* * *

Презентация:
------------
*   Видео (до 3 минути), което показва:  
    *   Kак се използва приложението, от изрязването на обекти до създаването на комикс.
*   Интерактивна презентация с демонстрация на функционалностите в реално време.