# Nuclear Option – Русский патч (Localization Patch)

Мод русской локализации для Nuclear Option. Работает как плагин BepInEx и переводит интерфейс, HUD, MFD, миссии, сценарии, технику и оружие — всего **2 865 записей**.

## Требования

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Early Access 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## Установка

1. Установите **BepInEx 5.x** в папку игры.
   ```
   Пример: C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```

2. Запустите игру **один раз** и закройте её. (Это создаст структуру папок BepInEx)

3. Скопируйте все файлы из этого репозитория в:
   ```
   [Папка игры]\BepInEx\plugins\LocalizationPatch\
   ```
   > Если папки «LocalizationPatch» нет, создайте её вручную.

4. Запустите игру — **русский перевод применится автоматически**.

## Включённые файлы

| Файл | Описание |
|------|----------|
| `LocalizationPatch.dll` | Плагин патча |
| `LocalizationPatchDropdown.dll` | Дополнение для выпадающих меню |
| `ru.json` | Данные русского перевода (2 865 записей) |
| `Tektur-Reg.ttf` | Шрифт для отображения кириллицы |

## Горячие клавиши в игре

| Клавиша | Функция |
|---------|---------|
| `F10` | Показать/скрыть отладочный оверлей |
| `Ctrl+F10` | Перезагрузить данные перевода (горячая перезагрузка) |

## Примечания

- Названия фракций (PALA, BDF, BOSCALI, PRIMEVA, FFL, LMA) и кодовые имена техники / оружия (Compass, Alkyon AB-4, FGA-57 Anvil, IRM-S2, и т. д.) остаются на английском.
- При возникновении проблем можно вручную указать язык в файле `BepInEx\config\com.noms.localizationpatch.cfg`, установив `Language = ru`.

## Авторы перевода

- **Shumatsu [UMA]**, **Jonyx2** — первоначальный перевод (~1 456 записей).
- **хомяк** — обновление до 0.33 и расширение до **2 865 записей**: миссии, описания сценариев, энциклопедия, новая техника / оружие, согласование терминологии (`Газ` → `Тяга`) и стандартизация названий самолётов (Cricket → Крикет, Brawler → Боец, Ibis → Ибис, Chicane → Шикана, Revoker → Ревокер, Vortex → Вихрь, Tarantula → Тарантул, Ifrit → Ифрит, Medusa → Медуза, Darkreach → Даркрич, Compass → Компас, Alkyon AB-4 → Алкион АБ-4).
- Плагин / основа: https://github.com/9138noms/NuclearOption-TranslationToolkit

## Лицензия шрифта

Tektur — [SIL Open Font License 1.1](https://fonts.google.com/specimen/Tektur)
