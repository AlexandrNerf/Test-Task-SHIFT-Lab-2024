# Тестовое задание ШИФТ-Лаб (Computer Vision 2024)

Здесь предоставлены два моих решения для тестовой задачи от ШИФТ-Лаб. 

Цель - обучить GAN для перевода текста или созданного 


# О ветках

В main ветке - основная версия (выполненая по минимальным условиям) + сами модели. 

Модель: UNet Generator + Patch Discriminator (pix2pix architecture)

Датасет: обработанные текстовые данные из MJSynth-english

---

В alternative ветке - reverse-OCR задача (усложненный вариант)

Модель: UNet Generator + Patch Discriminator (pix2pix architecture) + BERTEncoder (токенайзер)

Датасет: MJSynth-english
