# xion-market
Proyek ini hanya untuk experimen dan edukasi semata, gunakan dengan bijak. kami tidak bertanggung jawab apabila proyek ini digunakan untuk tujuan yang tidak tepat.
**Gunakan dengan bijak** kami tidak bertanggung jawab apa bila akun yang anda gunakan di tangguhkan sementara atau di blokir secara permanet.

## Fitur
- Otomatis beli di market
- Otomatis cek salo
- Multi akun
- Dapat menggunakan proxy dan tidak
  
i'm Moraevx 

**Terima Kasih**

### Clone Repositor

>```
>git clone https://github.com/moraevx/xion-market.git
>```
>```
>cd xion-market
>```

### Persiapan

Persiapkan Sistem  
>```
>pip install colorama pyfiglet
>```
>```
>pip install playwright
>python -m playwright install
>```
### Ganti file `config.json` dan `proxies.txt`

1. Ganti file `config.json`
   
>```
>{
>  "akun1":{
>    "trust:cache:timestamp": "{\"timestamp\":xxxxxxxxxx}",
>    "xion-authz-granter-account": "YOUR_ACCOUNT_ADDRESS",
>    "delay": "xxxxxxxxx",
>    "converted": "true",
>    "ethereum-https://testnet.xionmarkets.com": "{\"chainId\":\"0x465\"}",
>    "isWhitelist": "false",
>    "loglevel": "SILENT",
>    "xion-authz-temp-account": "YOUR_ENCRYPTED_WALLET_DATA",
>    "binance-https://testnet.xionmarkets.com": "{}"
>  },
>  "akun1":{
>    "trust:cache:timestamp": "{\"timestamp\":xxxxxxxxxx}",
>    "xion-authz-granter-account": "YOUR_ACCOUNT_ADDRESS",
>    "delay": "xxxxxxxxx",
>    "converted": "true",
>    "ethereum-https://testnet.xionmarkets.com": "{\"chainId\":\"0x465\"}",
>    "isWhitelist": "false",
>    "loglevel": "SILENT",
>    "xion-authz-temp-account": "YOUR_ENCRYPTED_WALLET_DATA",
>    "binance-https://testnet.xionmarkets.com": "{}"
>  }
>}
>```




