## Zapisanie hasła do połączenia RDP

Po aktualizacji do Windowsa 11 nie jest możliwe zapamiętanie hasła do połączenia RDP w prosty sposób.

Z powershella trzeba wywołać polecenie:
```powershell
cmdkey /generic:TERMSRV/<targetname> /user:<username> /pass:<password>
```

[źródło](https://learn.microsoft.com/en-us/answers/questions/1021785/windows-11-22h2-cant-use-saved-credential)
