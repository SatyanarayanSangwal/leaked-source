# leaked-source
Have I Been Pwned (HIBP)
🔗 https://haveibeenpwned.com/

2. Intelligence X (Free Tier)
🔗 https://intelx.io/

3. DeHashed (Free & Paid)
🔗 https://www.dehashed.com/

4. Leak-Lookup (Free for Basic Checks)
🔗 https://leak-lookup.com/


5. Vigilante.pw (Free Breach Search)
🔗 https://vigilante.pw/


6. BreachDirectory (Free Lookup)
🔗 https://breachdirectory.org/


7. Pulsedive (Threat Intelligence Search)
🔗 https://pulsedive.com/


8. Search on Pastebin-like Sites
    Manually check:
1. https://pastebin.com/
2. https://ghostbin.com/
3. https://rentry.co/
4. https://controlc.com/
5. https://www.doxbin.org/

9. Google Dorking
1. `intitle:"index of" "database.sql"`  
   → Finds raw SQL database dumps  

2. `filetype:sql intext:"password"`  
   → SQL files containing passwords  

3. `intitle:"index of" "backup.zip"`  
   → Exposed backup files  

4. `filetype:env DB_USERNAME DB_PASSWORD`  
   → Exposed `.env` files (common in web apps)  

5. `ext:ini intext:"api_key"`  
   → Configuration files with API keys  

6. `intitle:"phpMyAdmin" "Welcome to"`  
   → Exposed phpMyAdmin panels

7. `intext:"@gmail.com" filetype:csv`  
   → CSV files with Gmail addresses  

8. `intext:"username" AND intext:"password" filetype:log`  
   → Log files with credentials  

9. `intitle:"login" inurl:/admin ext:txt`  
   → Plaintext admin login details  

10. `"-----BEGIN RSA PRIVATE KEY-----"`  
   → Private encryption keys  

11. `intext:"password" ext:txt | ext:log`  
   → Passwords in text/log files
    
12. `site:github.com "AWS_ACCESS_KEY_ID"`  
   → AWS keys in GitHub repos  

13. `"api.googlemaps key" ext:env`  
   → Google Maps API keys  

14. `site:pastebin.com "mongodb://"`  
   → MongoDB connection strings  

15. `"firebaseio.com" ext:json`  
   → Firebase database URLs  

16. `site:gitlab.com "SECRET_KEY"`  
   → GitLab secrets

17. `site:pastebin.com "companyname"`  
   → Checks Pastebin for leaks  

18. `site:controlc.com "password list"`  
   → Finds password dumps  

19. `site:justpaste.it intext:"breach"`  
   → Checks JustPaste.it for breaches  

20. `site:rentry.co "leaked"`  
   → Searches Rentry.co for leaks

21. `intitle:"webcamXP 5"`  
   → Exposed WebcamXP dashboards  

22. `inurl:/view.shtml`  
   → Live security camera feeds  

23. `intitle:"printer" inurl:/cgi-bin/`  
   → Exposed printer admin panels  

24. `intext:"Hikvision" intitle:"Login"`  
   → Hikvision camera logins  
