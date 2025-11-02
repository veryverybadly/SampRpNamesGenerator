# SAMP RP NAMES GENERATOR
# 🎮 Samp RP Names Generator

**Samp RP Names Generator** — программа для генерации случайных имён и фамилий в формате **SAMP RP (San Andreas Multiplayer)**. This tool generates random names and surnames in SAMP RP style, helping players quickly create realistic RP nicknames.

Программа позволяет выбирать национальность имён: русские, английские или смешанные, с автоматической транслитерацией русских имён на латиницу. The program allows selecting nationality: Russian, English, or mixed, with automatic transliteration of Russian names to Latin.

---

## ⚙️ Функции / Features

- 🎲 Генерация имён и фамилий в формате `Имя_Фамилия` / Generates names in `Name_Surname` format  
- 🌍 Выбор национальности / Choose nationality (Russian / English / Mixed)  
- 🔤 Транслитерация русских имён / Automatic transliteration for Russian names  
- 📋 Копирование результата в буфер обмена / Copy results to clipboard  
- 💾 Сохранение списка имён в `.txt` файл / Save generated names to file  
- 🪟 Графический интерфейс (GUI) / Simple GUI interface  
- 💻 CLI-режим для консоли / CLI mode for scripting

---

## 🚀 Установка и запуск / Installation and Usage

### 🪟 Windows
1. установи файл по ссылке: https://github.com/veryverybadly/SampRpNamesGenerator/releases/tag/Windows
2. Запусти .exe файл


3. Установи зависимости / Install dependencies (if any):

   ```bash
   pip install -r requirements.txt
   ```
4. Запусти программу / Run the program:

   ```bash
   python samp_name_generator.py
   ```

Чтобы собрать `.exe` / To build `.exe`:

```bash
pyinstaller --onefile --noconsole samp_name_generator.py
```

Файл появится в папке `dist/` / The file will appear in the `dist/` folder.

### 🐧 Linux

```bash
sudo apt install python3 python3-pip
pip install pyinstaller
pyinstaller --onefile samp_name_generator.py
./dist/samp_name_generator
```

---

## 💡 Примеры / Example

**CLI пример / CLI example:**

```bash
python samp_name_generator.py --cli -n 10 --nationality mixed
```

**Результат / Output:**

```
Nikita_Petrov
John_Smith
Alexey_Miller
Kevin_Walker
```

---

## 🧑‍💻 Автор / Author

Разработчик / Developer: **Alexander / Swar_Dev**
GitHub: [https://github.com/veryverybadly](https://github.com/veryverybadly)

---

## 📜 Лицензия / License

Проект распространяется под лицензией **MIT License**. / Distributed under the **MIT License**.

