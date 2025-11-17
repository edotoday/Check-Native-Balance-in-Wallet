# Check-Native-Balance-in-Wallet

## Описание
Скрипт на Python предназначен для проверки балансов криптовалютных кошельков в сетях Ethereum, Optimism, Arbitrum, Base, BSC и Polygon. 
Он использует RPC-ноды для подключения к блокчейнам, поддерживает работу через прокси, логирует процесс и сохраняет результаты в файл `balances.xlsx`. 
Адреса кошельков читаются из файла `wallet.txt`, прокси (опционально) — из файла `proxy.txt`.

## Установка
1. **Установите Python** (версия 3.7+).
2. **Установите зависимости**: pip install requests pandas web3 openpyxl
   
## Запуск 
python main.py

Удачи! ;)
