# Тестовое задание ШИФТ-Лаб (Computer Vision 2024)

Здесь предоставлены два моих решения для тестовой задачи от ШИФТ-Лаб. 

Цель - обучить GAN для перевода текста или созданного по тексту программно изображения в датасет для OCR задачи


# О ветках

В main ветке - основная версия (выполненая по минимальным условиям) + сами модели. 

Модель: UNet Generator + Patch Discriminator (pix2pix architecture)

Датасет: обработанные текстовые данные из MJSynth-english

---

В alternative ветке - reverse-OCR задача (усложненный вариант)

Модель: UNet Generator + Patch Discriminator (pix2pix architecture) + BERTEncoder (токенайзер)

Датасет: MJSynth-english

Посмотреть веса и ноутбуки в коллабе можно по ссылке: https://drive.google.com/drive/folders/18eGr1kytp9esQ9sVJN_oQa0zxRONp-Gw
