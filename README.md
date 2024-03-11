# Reset Admin and User PASS Windows via CMD

START

1. Boot on .ISO Windows Setup
2. Open a CMD (Maj + F10)
3. "copy [disk letter]:\Windows\System32\Utilman.exe [disk letter]:\Windows\System32\Utilman.exe.bkp"
4. "copy [disk letter]:\Windows\System32\cmd.exe [disk letter]:\Windows\System32\Utilman.exe"
   => Replace ? YES
5. Reboot
6. Use Utilman button for open a CMD
7. "net user [USERNAME] [NEW PASSWORD]"

OR

7. control userpasswords2

END
