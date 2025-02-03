# WPF-AsyncAwait-Demo

## 📌 Opis projektu

**WPF-AsyncAwait-Demo** to aplikacja desktopowa napisana w języku **C#** z wykorzystaniem technologii **Windows Presentation Foundation (WPF)**. Projekt demonstruje implementację programowania asynchronicznego przy użyciu słów kluczowych `async` i `await`, co pozwala na tworzenie responsywnych interfejsów użytkownika.

## 🛠 Wymagania

Aby uruchomić projekt, potrzebujesz:

- **Visual Studio 2019** lub nowszy z zainstalowanymi komponentami **.NET Desktop Development**
- **.NET Framework 4.7.2** lub nowszy

## 🚀 Instalacja i uruchomienie

1. **Klonowanie repozytorium:**

   ```bash
   git clone https://github.com/MatiLUzak/WpfApp1.git
   cd WpfApp1
   ```

2. **Otworzenie projektu w Visual Studio:**

   - Otwórz plik rozwiązania `WpfApp1.sln` za pomocą Visual Studio.

3. **Przywrócenie pakietów NuGet:**

   - W Visual Studio przejdź do **Tools** > **NuGet Package Manager** > **Manage NuGet Packages for Solution** i upewnij się, że wszystkie wymagane pakiety są zainstalowane.

4. **Kompilacja i uruchomienie aplikacji:**

   - Naciśnij `F5` lub kliknij przycisk **Start** w Visual Studio, aby skompilować i uruchomić aplikację.

## 📂 Struktura projektu

```
WpfApp1/
├── ClassLibrary1/
│   ├── Class1.cs
│   └── ...
├── MyApp.Logic/
│   ├── AsyncProcessor.cs
│   └── ...
├── MyApp.ViewModel/
│   ├── MainViewModel.cs
│   └── ...
├── WpfApp1/
│   ├── App.xaml
│   ├── App.xaml.cs
│   ├── MainWindow.xaml
│   ├── MainWindow.xaml.cs
│   └── ...
├── WpfApp1.sln
├── .gitignore
└── README.md
```

- **ClassLibrary1/** – dodatkowa biblioteka klas
- **MyApp.Logic/** – logika aplikacji, w tym klasy odpowiedzialne za operacje asynchroniczne
- **MyApp.ViewModel/** – model widoku (ViewModel) zgodnie z wzorcem MVVM
- **WpfApp1/** – główna aplikacja WPF, zawierająca definicje widoków i kod związany z interfejsem użytkownika

## ✍️ Autorzy

- **Mateusz Luzak** – `{FD9D086C-532F-4AAC-BB99-69D7798837D8}`

## 📜 Licencja

Ten projekt jest licencjonowany na podstawie licencji MIT. Szczegóły znajdują się w pliku `LICENSE`.
