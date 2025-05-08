# LobeHub Desktop Application

LobeHub Desktop 是 [LobeChat](https://github.com/lobehub/lobe-chat) 的跨平台桌面应用程序，使用 Electron 构建，提供了更加原生的桌面体验和功能。

## Funkcje

- Obsługa wielu platform: Obsługuje systemy macOS (Intel/Apple Silicon), Windows i Linux
- Aktualizacje automatyczne: Wbudowany mechanizm aktualizacji, dzięki któremu zawsze korzystasz z najnowszej wersji
- **Obsługa wielu języków**: Pełna obsługa internacjonalizacji, w tym chiński, angielski i inne języki
- **Natywna integracja**: Głęboka integracja z systemem operacyjnym, zapewniająca natywne menu, skróty i powiadomienia
- **Bezpieczny**: Wersja dla systemu macOS jest poświadczona notarialnie w celu zapewnienia bezpieczeństwa
- Wersje wielokanałowe: Dostępne są wersje stabilne, beta i codzienne

## Ustawienia środowiska programistycznego

### Wymagania wstępne

- Node.js 22+
- pnpm 10+

### Instalowanie zależności

```bash
pnpm install-isolated
```

### Uruchamianie w trybie programowania

```bash
pnpm electron:dev
```

### Kompilowanie aplikacji

Zbuduj wszystkie platformy：

```bash
pnpm build
```

Zbuduj na konkretną platformę：

```bash
# macOS
pnpm build:mac

# Windows
pnpm build:win

# Linux
pnpm build:linux
```

## Kanały wydawnicze

Aplikacja oferuje trzy kanały dystrybucji:

- Stabilny: W pełni przetestowane oficjalne wydanie
- Beta: wersja przedpremierowa z nowymi funkcjami, które zostaną wkrótce udostępnione
- Nightly: kompilacja, która zawiera najnowsze postępy w rozwoju
