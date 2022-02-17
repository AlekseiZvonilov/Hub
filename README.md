**JSON**         
**1) Создать внешний репозиторий c названием JSON**      
• Зайти на сайт https://github.com/               
• Войти под своей учетной записью         
• Нажить зеленую кнопку "New"         
• В поле "Repository name" ввести "JSON", выбрать "Public","Add a README file"          
• Нажать "Create repository"   
           
**2) Клонировать репозиторий JSON на локальный компьютер**             
• Нажать "Code", выбрать пункт HTTPS, скопировать ссылку, открыть или зайти в папку где будет расположен репозиторий                 
• git clone https://github.com/AlekseiZvonilov/JSON.git   
              
**3) Внутри локального JSON создать файл “new.json”**              
• git add new.json  
    
**4) Добавить файл под гит**                      
• git status файл new.json отслеживается(отображается зеленым цветом)   
                
**5) Закоммитить файл**        
• git commit -m "add new.json"   
     
**6)Отправить файл на внешний GitHub репозиторий**     
• git push     
   
**7)Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.**      
• vim new.json     
•  i  
```
 {         
        "ful_name":"Zvonilov Aleksei Mihailovich",         
        "age":33,         
        "Numder of pets":0,        
        "Future desired salary":500"$"         
                
}     
 ```           
**8) Отправить изменения на внешний репозиторий**      
• git status   
• git add new.fson     
• git commit "add new.json"   
• git push 
     
**9) Создать файл preferences.json**    
• cat > preferences.json    
• В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON 
```
{     "favorite movie":"A Nightmare on Elm Street",          
      "favorite serial":"The Big Bang Theory",           
      "favorite food":"ice cream",           
      "favorite time of year":"summer",            
      "Country you would like to visit":"New Zealand",             
      }
  ```
• Enter                
• Ctrl + D   
                               
**10) Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**          
• cat > skills.json 
```
{                                                   
"Hard skills at the end of the course":
["Basic theory (What is testing, bug reports, documentation, types, methods, testing directions, etc.) SDLC, STLC.,"                                     
"client-server architecture",           
"HTTP Server Request Methods",                            
"HTTP server response codes",                            
"Structures of HTTP Requests and Responses",                           
"What is JSON, XML. Their structure",                            
"API testing via Postman (JS, API autotests)",                       
"Removing and reading logs from an external server",                    
"Sniffing http web traffic with Charles and Fiddler",                      
"Web Browser Dev Tools (Google Chrome, FireFox)",                       
"VPN. (How it works, why you need it, how to use it, tool options)",                                    
"Mobile testing",                            
"Feature iOS, Android, guidelines",                    
"Building iOS Apps with Xcode",                             
"Building Android Applications with Android Studio",                          
"ADB (управление андройд девайсами),"                        
"Настройка прокси и vpn на iOS и Android",                                
"Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android",                            
"Command line (terminal) Linux (copy, create, view, move files on servers without a graphical interface)",                                           
"Basics of bash scripting, automation of routine tasks on the server.",        
"Access to remote servers",             
"SQL Basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",             
"Postgres database (installation, configuration and use)",             
"Non-relational Redis database (installation, configuration and use)",               
"Load Testing in Jmeter",               
"Scrum Development Methodology",                      
"Python. (Learning the basics. Creating a client-server application)"]                
} 
```
• Enter              
• Ctrl + D  
                      
**11) Отправить сразу 2 файла на внешний репозиторий**     
• git add .     
• git commit -m "add skills.json and preferences.json"     
• git push  
    
**12) На веб интерфейсе создать файл bug_report.json**     
• Нажать "Add file"   
• Во всплывающем окне выбрать "Create new file"    
• В поле "Name new file" ввести "bug_report.json" 
    
**13) Сделать Commit changes (сохранить) изменения на веб интерфейсе**     
• Нажать кнопку "Commit new file"   
    
**14) На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON**    
• открыть файл "bug_report.json" 
```
{ 
  "https://docs.google.com/spreadsheets/d/1sBzTaRsWcJAJcvIYXEU67vvfv7cC1JBv3a69DYAV2e8/edit?usp=sharing"  
} 
```
     
**15) Сделать Commit changes (сохранить) изменения на веб интерфейсе**     
• Нажать "Commit change"   
     
**16) Синхронизировать внешний и локальный репозиторий JSON**    
• git pull 

     
**XML**    
**1) Создать внешний репозиторий c названием XML**    
• Зайти на сайт https://github.com/    
• Войти под своей учетной записью    
• Нажить зеленую кнопку "New"    
• В поле "Repository name" ввести "XML", выбрать "Public","Add a README file"    
• Нажать "Create repository"  
    
**2) Клонировать репозиторий XML на локальный компьютер**    
• Нажать "Code", выбрать пункт HTTPS, скопировать ссылку, открыть или зайти в папку где будет расположен репозиторий         
• gti clone https://github.com/AlekseiZvonilov/XML.git   
     
**3) Внутри локального XML создать файл “new.xml”**     
• git add new.xml  
    
**4) Добавить файл под гит**     
• git status файл new.xml отслеживается(отображается зеленым цветом)   
       
**5) Закоммитить файл**    
• git commit -m "add new.xml"  
         
**6) Отправить файл на внешний GitHub репозиторий**         
• git push   
   
**7) Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML**    
• vim new.xml     
• i  
```
 <its_me>
         <ful_name>Zvonilov_Aleksei_Mihailovich</ful_name>
        <age>33</age>
        <Numder_of_pets>0</Numder_of_pets>
        <Future_desired_salary>500$</Future_desired_salary>
  </its_me>  
  ```
• Esc           
• :wq  
         
**8) Отправить изменения на внешний репозиторий**           
• git add new.xml    
• git commit -m "chenges new.xml"    
• git push    
  
**9) Создать файл preferences.xml**       
• cat > preference.xml   
       
**10) В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML** 
```
<preference>             
      <favorite movie>A Nightmare on Elm Street</favorite movie>                         
      <favorite serial>The Big Bang Theory</favorite serial>                           
      <favorite food>ice cream</favorite food>                                   
      <favorite time of year>summer</favorite time of year>                                 
      <Country you would like to visit>New Zealand</Country you would like to visit>                                    
 </preference> 
 ```
 • Enter       
 • Ctrl + D    
               
 **11) Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML**    
 ```
 <hard_skills_at_the_end_of_the_course>            
  <1>Basic theory (What is testing, bug reports, documentation, types, methods, testing directions, etc.) SDLC, STLC.</1>            
  <2>client-server architecture</2>            
  <3>HTTP Server Request Methods</3>                                                
  <4>"HTTP server response codes</4>                     
  <5>Structures of HTTP Requests and Responses</5>                    
  <6>What is JSON, XML. Their structure</6>                     
  <7>API testing via Postman (JS, API autotests)</7>                    
  <8>Removing and reading logs from an external server</8>                 
  <9>Sniffing http web traffic with Charles and Fiddler</9>                    
  <10>Web Browser Dev Tools (Google Chrome, FireFox)</10>                          
  <11>VPN. (How it works, why you need it, how to use it, tool options)</11>                    
  <12>Mobile testing</12>                      
  <13>Feature iOS, Android, guidelines</13>                     
  <14>Building iOS Apps with Xcode</14>                       
  <15>Building Android Applications with Android Studio</15>                     
  <16>ADB (управление андройд девайсами)</16>                     
  <17>Настройка прокси и vpn на iOS и Android</17>             
  <18>Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android</18>         
  <19>Command line (terminal) Linux (copy, create, view, move files on servers without a graphical interface)</19>         
  <20>Basics of bash scripting, automation of routine tasks on the server</20>     
  <21>Access to remote servers</21>                      
  <22>SQL Basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)</22>                       
  <23>Postgres database (installation, configuration and use)</23>                    
  <24>Non-relational Redis database (installation, configuration and use)</24>                    
  <25>Load Testing in Jmeter</25>                      
  <26>Scrum Development Methodology</26>                    
  <27>Python (Learning the basics. Creating a client-server application)</27>                     
</hard_skills_at_the_end_of_the_course>   
```
              
**12) Сделать коммит в одну строку**       
• add . ; git commit -m "add 2 files"  
     
**13) Отправить сразу 2 файла на внешний репозиторий**    
• get push     
  
**14) На веб интерфейсе создать файл bug_report.xml**      
• В репозитории XML нажать кнопку "Add File"       
• Во всплывающем окне нажать "Create new file"     
• В поле "Name new file" ввести "bug_report.xml"   
   
**15) Сделать Commit changes (сохранить) изменения на веб интерфейсе**           
• Нажать кнопку "Commit new file"    
           
**16) На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML**               
• Открыть файл "bug_report.xml" 
```
{      
     "https://docs.google.com/spreadsheets/d/1sBzTaRsWcJAJcvIYXEU67vvfv7cC1JBv3a69DYAV2e8/edit?usp=sharing"  
   }   
   ```
               
**17) Сделать Commit changes (сохранить) изменения на веб интерфейсе**         
• Нажать "Commit change"        
**18) Синхронизировать внешний и локальный репозиторий XML      
• git pull
     
**TXT**      
**1) Создать внешний репозиторий c названием TXT**     
• Зайти на сайт https://github.com/    
• Войти под своей учетной записью  
• Нажить зеленую кнопку "New"  
• В поле "Repository name" ввести "TXT", выбрать "Public","Add a README file"  
• Нажать "Create repository" 
     
**2) Клонировать репозиторий TXT на локальный компьютер**   
• Нажать "Code", выбрать пункт HTTPS, скопировать ссылку, открыть или зайти в папку где будет расположен репозиторий    
• gti clone https://github.com/AlekseiZvonilov/TXT.git   
      
**3) Внутри локального TXT создать файл “new.txt”**  
• git add new.txt  
    
**4) Добавить файл под гит**    
• git status файл new.json отслеживается(отображается зеленым цветом)  
    
**5) Закоммитить файл**  
• git commit -m "add new.txt" 
      
**6)Отправить файл на внешний GitHub репозиторий**   
• git push 
        
**7) Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT**  
```
        ful_name:Zvonilov Aleksei Mihailovich    
        age:33  
        Numder of pets:0  
        Future desired salary:500"$  
  ```
           
**8) Отправить изменения на внешний репозиторий**   
• git status  
• git add new.txt  
• git commit "add new.txt"  
• git push   
     
**9) Создать файл preferences.txt**   
• cat >  preferences.txt  
   
**10) В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT**  
```
Preference:  
      favorite movie:A Nightmare on Elm Street  
      favorite serial:The Big Bang Theory  
      favorite food:ice cream  
      favorite time of year:summer  
      Country you would like to visit:New Zealand
```      
             
**11) Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT**   
• cat > skills.txt
```
Hard skills at the end of the course:  
  Basic theory (What is testing, bug reports,   documentation, types, methods, testing directions, etc.) SDLC, STLC.  
  client-server architecture  
  HTTP Server Request Methods   
  HTTP server response codes   
  Structures of HTTP Requests and Responses   
  What is JSON, XML. Their structure   
  API testing via Postman (JS, API autotests)    
  Removing and reading logs from an external server    
  Sniffing http web traffic with Charles and Fiddler     
  Web Browser Dev Tools (Google Chrome, FireFox)    
  VPN. (How it works, why you need it, how to use it, tool options)     
  Mobile testing     
  Feature iOS, Android, guidelines     
  Building iOS Apps with Xcode     
  Building Android Applications with Android Studio     
  ADB (управление андройд девайсами)     
  Настройка прокси и vpn на iOS и Android      
  Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android       
  Command line (terminal) Linux (copy, create, view, move files on servers without a graphical interface)      
  Basics of bash scripting, automation of routine tasks on the server.      
  Access to remote servers         
  SQL Basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)        
  Postgres database (installation, configuration and use)     
  Non-relational Redis database (installation, configuration and use)      
  Load Testing in Jmeter      
  Scrum Development Methodology      
  Python. (Learning the basics. Creating a client-server application)
  ```
• Enter   
• Ctrl + D  
     
**12) Сделать коммит в одну строку**   
• add . ; git commit -m "add 2 files"   
   
**13) Отправить сразу 2 файла на внешний репозиторий**  
• get push   
     
**14) На веб интерфейсе создать файл bug_report.txt**  
• В репозитории XML нажать кнопку "Add File"  
• Во всплывающем окне нажать "Create new file"  
• В поле "Name new file" ввести "bug_report.txt"   
     
**15) делать Commit changes (сохранить) изменения на веб интерфейсе**  
• Нажать кнопку "Commit new file"  
     
**16) На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT**  
• Открыть файл "bug_report.xml" 
  ```   
{  
"https://docs.google.com/spreadsheets/d/1sBzTaRsWcJAJcvIYXEU67vvfv7cC1JBv3a69DYAV2e8/edit?usp=sharing"  
}  
 ```   
**17) Сделать Commit changes (сохранить) изменения на веб интерфейсе**
• Нажать "Commit change"  
     
**18)Синхронизировать внешний и локальный репозиторий TXT**  
• git pull  
   
 
  




     












