# Microsoft Store Tool

Простая консольная утилита на Python для восстановления или полного удаления Microsoft Store в Windows 10 и Windows 11.

## Возможности

- Восстановление Microsoft Store — переустановка через `Add-AppxPackage -Register` с использованием манифеста из `AppxManifest.xml`
- Удаление Microsoft Store — деинсталляция пакета `Microsoft.WindowsStore` для текущего пользователя
- Очистка кэша — опциональное удаление кэша Store для решения проблем с запуском
- Работает без сторонних библиотек (только стандартная библиотека Python и PowerShell)
- Проверка прав администратора и подтверждение опасных операций

## Требования

- Windows 10 (1809+) или Windows 11
- Python 3.8+
- Права администратора (для некоторых операций)

## Установка

```bash
git clone https://github.com/username/microsoft-store-tool.git
cd microsoft-store-tool
