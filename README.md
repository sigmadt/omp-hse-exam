# Экзамен по ОМП Осень 2024
Ниже будет представлена инструкция по заданиям экзамена. 

На выполнение заданий дается ровно 2 часа. За каждое задание можно получить 0 или 1 балл. 

Чтобы сдать задание `N` нужно после его выполнения прописать:
```bash
omp taskN check
```

## 3. Структура директорий и файлов

**Инициализация:**

```bash
omp task3 init
```

### Задание

В директории `task3` создать папку `project`, внутри нее:

- Создать поддиректории `src`, `bin`, `docs`.
- В директории `src` создать файлы: `main.c`, `utils.c`, `config.c`, `main.h`.
- В директории `docs` создать файл `README.md` с содержимым `# README`.
- В директории `bin` создать файл `run.sh` с правами на выполнение.
---

## 4. Права доступа

**Инициализация:**

```bash
omp task4 init
```

### Задание

В директории `task4`:

- Создать файл `secret.txt` с содержимым `"Top secret data"` и правами доступа только для владельца.
- Создать файл `public.txt` с содержимым `"Public information"` и правами доступа на чтение для всех пользователей.
- Создать файл `confidential.txt` с содержимым `"Confidential data"`, доступный для записи владельцу и группе `students`, закрытый для других.

---

## 5. Поиск и фильтрация файлов

**Инициализация:**

```bash
omp task5 init
```

### Задание

В директории `task5` найти все файлы с расширением `.log` и записать их список в файл `loglist.txt`.

Примерное содержание файла `loglist.txt`:

```bash
$ cat loglist.txt

logfile_0_txxxhxh.log
logfile_0_knjgt.log
logfile_2_iqosiurbuh.log
logfile_0_jhnusftnlhjpr.log
logfile_0_gvqwmo.log
logfile_0_enszhb.log
logfile_2_qiruadtcry.log
logfile_3_urezlbr.log
logfile_3_dtdcfltvcpqdmaa.log
logfile_0_figpji.log
```

---

## 6. Работа с архивами

**Инициализация:**

```bash
omp task6 init
```

### Задание

В директории `task6`:

- Создать поддиректорию `to_archive`.
- Переместить файлы `file1.txt`, `file2.txt`, `file3.txt`, `README.md` в `to_archive`.
- Архивировать содержимое `to_archive` в файл `archive_task.tar.gz` в корневой директории `task6`.
- Разархивировать `prepared_files.tar.gz` в поддиректорию `extracted_tar`.

---

## 7. Поиск и фильтрация

**Инициализация:**

```bash
omp task7 init
```

### Задание

В директории `task7`:

- Найти все строки, содержащие `"ERROR"`, во всех файлах вида `log*.txt` и вывести их в файл `errors.txt`.
- Найти все строки, содержащие `"WARNING"`, и вывести их в файл `warnings.txt`.


Примерное содержание файлов errors.txt и warnings.txt:
```bash
$ cat errors.txt

ERROR: cmonmb
ERROR: kttkcodkoyyw
ERROR: wgjpwzqknhd
ERROR: iayerxbq
ERROR: pezdpmoxco
ERROR: nmthtyuckl
ERROR: bqvmzvdtyfdoq
ERROR: fnmyknkqh
ERROR: yuytv
ERROR: ibyiwnbxy
```

```bash

$ cat warnings.txt

WARNING: oxlaxwofxdskqt
WARNING: ehtoehqvetc
WARNING: riuwhlmzeihq
WARNING: wrsaguaxtji
WARNING: znnbd
WARNING: yljlhr
WARNING: zreybgmrxyen
WARNING: vadwzrlqzqgbpj
WARNING: ndvvffhmgxg
WARNING: berkcblwlwdwph

```
---
