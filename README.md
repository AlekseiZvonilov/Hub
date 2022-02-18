**JSON**         
**1) Создать внешний репозиторий c названием JSON**      
*  Зайти на сайт https://github.com/               
*  Войти под своей учетной записью         
*  Нажить зеленую кнопку "New"         
*  В поле "Repository name" ввести "JSON", выбрать "Public","Add a README file"          
*  Нажать "Create repository"   
           
**2) Клонировать репозиторий JSON на локальный компьютер**             
* Нажать "Code", выбрать пункт HTTPS, скопировать ссылку, открыть или зайти в папку где будет расположен репозиторий                 
* gti clone https://github.com/AlekseiZvonilov/JSON.git   
              
**3) Внутри локального JSON создать файл “new.json”**              
* git touch new.json   
* git status файл new.json не отслеживается(отображается красным цветом)    
    
**4) Добавить файл под гит** 
* git add new.json                        
* git status файл new.json отслеживается(отображается зеленым цветом)   
                
**5) Закоммитить файл**        
* git commit -m "add new.json"   
     
**6)Отправить файл на внешний GitHub репозиторий**     
* git push     
   
**7)Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.**      
* vim new.json     
*  i    
```json    
{         
"fulName":"Zvonilov Aleksei Mihailovich",         
"age":33,         
"pets":0,        
"FutureDesiredSalary":500"$",                       
}     
```     
* Esc   
* :wq    

**8) Отправить изменения на внешний репозиторий**         
* git add new.fson     
* git commit "changed new.json"   
* git push 
     
**9) Создать файл preferences.json**    
* cat > preferences.json
      
**10) В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON** 
```json                 
{    
      "favoriteMovie":"A Nightmare on Elm Street",          
      "favoriteSerial":"The Big Bang Theory",           
      "favoriteFood":"ice cream",           
      "favoriteTimeOfYear":"summer",            
      "CountryYouWouldLikeToVisit":"New Zealand",             
      }   
 ```               
* Enter                
* Ctrl + D   
                               
**11) Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**          
* cat > skills.json
```json                  
{                                                   
"skills" :[
"Basic theory (What is testing, bug reports, documentation, types, methods, testing directions, etc.) SDLC, STLC."                                    
"client-server architecture"           
"HTTP Server Request Methods"                            
"HTTP server response codes"                            
"Structures of HTTP Requests and Responses"                           
"What is JSON, XML. Their structure"                            
"API testing via Postman (JS, API autotests)"                       
"Removing and reading logs from an external server"                    
"Sniffing http web traffic with Charles and Fiddler"                      
"Web Browser Dev Tools (Google Chrome, FireFox)"                       
"VPN. (How it works, why you need it, how to use it, tool options)"                                   
"Mobile testing"                            
"Feature iOS, Android, guidelines"                    
"Building iOS Apps with Xcode"                             
"Building Android Applications with Android Studio"                          
"ADB (управление андройд девайсами),"                        
"Настройка прокси и vpn на iOS и Android"                                
"Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android"                            
"Command line (terminal) Linux (copy, create, view, move files on servers without a graphical interface)"                                           
"Basics of bash scripting, automation of routine tasks on the server."        
"Access to remote servers"             
"SQL Basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)"             
"Postgres database (installation, configuration and use)"             
"Non-relational Redis database (installation, configuration and use)"               
"Load Testing in Jmeter"               
"Scrum Development Methodology"                      
"Python. (Learning the basics. Creating a client-server application)"   
]  
             
}   
```               
* Enter              
* Ctrl + D  
                      
**12) Отправить сразу 2 файла на внешний репозиторий**     
* git add . ; git commit -m "add skills.json and preferences.json" ; git push     
    
**13) На веб интерфейсе создать файл bug_report.json**     
* Нажать "Add file"   
* Во всплывающем окне выбрать "Create new file"    
* В поле "Name new file" ввести "bug_report.json" 
    
**14) Сделать Commit changes (сохранить) изменения на веб интерфейсе**     
* Нажать кнопку "Commit new file"   
    
**15) На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON**    
* открыть файл "bug_report.json"
```json   
{ 
  "https://docs.google.com/spreadsheets/d/1sBzTaRsWcJAJcvIYXEU67vvfv7cC1JBv3a69DYAV2e8/edit?usp=sharing"  
} 
```
     
**16) Сделать Commit changes (сохранить) изменения на веб интерфейсе**     
* Нажать "Commit change"   
     
**17) Синхронизировать внешний и локальный репозиторий JSON**    
* git pull 

     
**XML**    
**1) Создать внешний репозиторий c названием XML**    
* Зайти на сайт https://github.com/    
* Войти под своей учетной записью    
* Нажить зеленую кнопку "New"    
* В поле "Repository name" ввести "XML", выбрать "Public","Add a README file"    
* Нажать "Create repository"  
    
**2) Клонировать репозиторий XML на локальный компьютер**    
* Нажать "Code", выбрать пункт HTTPS, скопировать ссылку, открыть или зайти в папку где будет расположен репозиторий         
* git clone https://github.com/AlekseiZvonilov/XML.git   
     
**3) Внутри локального XML создать файл “new.xml”**     
* touch new.xml   
* git status файл new.xml не отслеживается(отображается красным цветом)   
    
**4) Добавить файл под гит**    
* git add new.xml    
* git status файл new.xml отслеживается(отображается зеленым цветом)   
       
**5) Закоммитить файл**    
* git commit -m "add new.xml"  
         
**6) Отправить файл на внешний GitHub репозиторий**         
* git push   
   
**7) Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML**    
* vim new.xml     
* i  
```xml      
 <its_me>
         <ful_name>Zvonilov_Aleksei_Mihailovich</ful_name>
        <age>33</age>
        <Numder_of_pets>0</Numder_of_pets>
        <Future_desired_salary>500$</Future_desired_salary>
  </its_me> 
  ```       
* Esc           
* :wq  
         
**8) Отправить изменения на внешний репозиторий**           
* git add new.xml    
* git commit -m "chenges new.xml"    
* git push    
  
**9) Создать файл preferences.xml**       
* cat > preference.xml   
       
**10) В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML**  
```xml        
<preference>             
      <favoriteMovie>A Nightmare on Elm Street</favoriteMovie>                         
      <favoriteSerial>The Big Bang Theory</favoriteSerial>                           
      <favoriteFood>ice cream</favorite food>                                   
      <favoriteTimeOfYear>summer</favoriteTimeOfYear>                                 
      <countryYouWouldLikeToVisit>New Zealand</countryYouWouldLikeToVisit>                                    
 </preference> 
 ```                         
 * Enter       
 * Ctrl + D    
               
 **11) Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML** 
 ```xml                            
 <skills>            
  <one>Basic theory (What is testing, bug reports, documentation, types, methods, testing directions, etc.) SDLC, STLC.</one>            
  <two>client-server architecture</two>            
  <three>HTTP Server Request Methods</three>                                                
  <four>"HTTP server response codes</four>                     
  <five>Structures of HTTP Requests and Responses</five>                    
  <six>What is JSON, XML. Their structure</six>                     
  <seven>API testing via Postman (JS, API autotests)</seven>                    
  <eight>Removing and reading logs from an external server</eight>                 
  <nine>Sniffing http web traffic with Charles and Fiddler</nine>                    
  <ten>Web Browser Dev Tools (Google Chrome, FireFox)</ten>                          
  <eleven>VPN. (How it works, why you need it, how to use it, tool options)</eleven>                    
  <twelve>Mobile testing</twelve>                      
  <thirteen>Feature iOS, Android, guidelines</thirteen>                     
  <fourteen>Building iOS Apps with Xcode</fourteen>                       
  <fiveteen>Building Android Applications with Android Studio</fiveteen>                     
  <sixteen>ADB (управление андройд девайсами)</sixteen>                     
  <seventeen>Настройка прокси и vpn на iOS и Android</seventeen>             
  <eighteen>Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android</eighteen>         
  <nineteen>Command line (terminal) Linux (copy, create, view, move files on servers without a graphical interface)</nineteen>         
  <twenty>Basics of bash scripting, automation of routine tasks on the server</twenty>     
  <twentyone>Access to remote servers</twentyone>                      
  <twentytwo>SQL Basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)</twentytwo>                       
  <twentythree>Postgres database (installation, configuration and use)</twentythree>                    
  <twentyfour>Non-relational Redis database (installation, configuration and use)</twentyfour>                    
  <twentyfive>Load Testing in Jmeter</twentyfive>                      
  <twentysix>Scrum Development Methodology</twentysix>                    
  <twentyseven>Python (Learning the basics. Creating a client-server application)</twentyseven>                     
</skills>  
```   
* Enter    
* Ctrl + D
              
**12) Сделать коммит в одну строку**       
* add . ; git commit -m "add preferences.xml and skills.xml"  
     
**13) Отправить сразу 2 файла на внешний репозиторий**    
* get push     
  
**14) На веб интерфейсе создать файл bug_report.xml**      
* В репозитории XML нажать кнопку "Add File"       
* Во всплывающем окне нажать "Create new file"     
* В поле "Name new file" ввести "bug_report.xml"   
   
**15) Сделать Commit changes (сохранить) изменения на веб интерфейсе**           
* Нажать кнопку "Commit new file"    
           
**16) На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML**               
* Открыть файл "bug_report.xml" 
```xml       
{      
     "https://docs.google.com/spreadsheets/d/1sBzTaRsWcJAJcvIYXEU67vvfv7cC1JBv3a69DYAV2e8/edit?usp=sharing"  
   } 
```     
               
**17) Сделать Commit changes (сохранить) изменения на веб интерфейсе**         
* Нажать "Commit change"
        
**18) Синхронизировать внешний и локальный репозиторий XML**      
* git pull
     
**TXT**      
**1) Создать внешний репозиторий c названием TXT**     
* Зайти на сайт https://github.com/    
* Войти под своей учетной записью  
* Нажить зеленую кнопку "New"  
* В поле "Repository name" ввести "TXT", выбрать "Public","Add a README file"  
* Нажать "Create repository" 
     
**2) Клонировать репозиторий TXT на локальный компьютер**   
* Нажать "Code", выбрать пункт HTTPS, скопировать ссылку, открыть или зайти в папку где будет расположен репозиторий    
* gti clone https://github.com/AlekseiZvonilov/TXT.git   
      
**3) Внутри локального TXT создать файл “new.txt”**  
* git add new.txt  
    
**4) Добавить файл под гит**    
* git status файл new.json отслеживается(отображается зеленым цветом)  
    
**5) Закоммитить файл**  
* git commit -m "add new.txt" 
      
**6)Отправить файл на внешний GitHub репозиторий**   
* git push 
        
**7) Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT**  
* vim new.txt   
* i
```txt 
        ful_name:Zvonilov Aleksei Mihailovich    
        age:33  
        Numder of pets:0  
        Future desired salary:500"$  
``` 
* Esc  
* :wq   
         
**8) Отправить изменения на внешний репозиторий**     
* git add new.txt  
* git commit "add new.txt"  
* git push   
     
**9) Создать файл preferences.txt**   
* cat >  preferences.txt  
   
**10) В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT** 
```txt 
Preference:  
      favorite movie:A Nightmare on Elm Street  
      favorite serial:The Big Bang Theory  
      favorite food:ice cream  
      favorite time of year:summer  
      Country you would like to visit:New Zealand 
```  
* Enter 
* Ctrl + D    
            
**11) Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT**   
* cat > skills.txt 
```txt   
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
* Enter   
* Ctrl + D  
     
**12) Сделать коммит в одну строку**   
* add . ; git commit -m "add preferences.txt and skills.txt"   
   
**13) Отправить сразу 2 файла на внешний репозиторий**  
* get push   
     
**14) На веб интерфейсе создать файл bug_report.txt**  
* В репозитории XML нажать кнопку "Add File"  
* Во всплывающем окне нажать "Create new file"  
* В поле "Name new file" ввести "bug_report.txt"   
     
**15) Cделать Commit changes (сохранить) изменения на веб интерфейсе**  
* Нажать кнопку "Commit new file"  
     
**16) На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT**  
* Открыть файл "bug_report.xml" 
 ```txt    
{  
"https://docs.google.com/spreadsheets/d/1sBzTaRsWcJAJcvIYXEU67vvfv7cC1JBv3a69DYAV2e8/edit?usp=sharing"  
}  
```    
**17) Сделать Commit changes (сохранить) изменения на веб интерфейсе**
* Нажать "Commit change"  
     
**18)Синхронизировать внешний и локальный репозиторий TXT**  
* git pull  
   
 
  




     












