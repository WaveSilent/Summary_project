# 📚 Библиотечная система (Library Management System)

Десктопное приложение для автоматизации работы библиотеки. Разработано на **Windows Presentation Foundation (WPF)** с использованием **Entity Framework** и **MS SQL Server**.

---

## 🚀 Возможности

- **Управление книгами** — добавление, редактирование, удаление, поиск
- **Управление читателями** — регистрация, просмотр истории выдач
- **Выдача и возврат книг** — отслеживание сроков возврата
- **Статистика** — самые популярные книги, должники
- **Авторизация** — разделение ролей (администратор/библиотекарь)

---

## 🛠 Технологии

- **Платформа:** .NET Framework / .NET Core
- **UI:** WPF (XAML)
- **База данных:** MS SQL Server / SQLite
- **ORM:** Entity Framework (Code First)
- **Архитектура:** MVVM (Model-View-ViewModel)

---

## 📁 Структура проекта
Summary_project/
├── Models/ # Классы сущностей (Book, Reader, Loan)
├── Data/ # Контекст базы данных (LibraryContext)
├── Views/ # XAML окна
│ ├── BookViews/ # CRUD для книг
│ ├── ReaderViews/ # CRUD для читателей
│ ├── LoanViews/ # Выдача и возврат
│ └── AuthorViews/ # Справочник авторов
├── App.xaml # Точка входа приложения
└── MainWindow.xaml # Главное окно

---

## 🚀 Быстрый старт

### Требования
- Windows 7/10/11
- Visual Studio 2019/2022
- MS SQL Server (или SQL Server Express)

### Запуск
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/WaveSilent/Summary_project.git
