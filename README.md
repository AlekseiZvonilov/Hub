**JSON**         
**1) Создать внешний репозиторий c названием JSON**      
• Зайти на сайт https://github.com/               
• Войти под своей учетной записью         
• Нажить зеленую кнопку "New"         
• В поле "Repository name" ввести "JSON", выбрать "Public","Add a README file"          
• Нажать "Create repository"            
**2) Клонировать репозиторий JSON на локальный компьютер**             
• Нажать "Code", выбрать пункт HTTPS, скопировать ссылку, открыть или зайти в папку где будет расположен репозиторий                 
• gti clone https://github.com/AlekseiZvonilov/JSON.git              
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
{         
        "ful_name":"Zvonilov Aleksei Mihailovich",         
        "age":33,         
        "Numder of pets":0,        
        "Future desired salary":500"$"         
                
}            
**8) Отправить изменения на внешний репозиторий**      
• git status   
• git add new.fson     
• git commit "add new.json"   
• git push    
**9) Создать файл preferences.json**    
• cat > preferences.json    
• В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON                  
{     "favorite movie":"A Nightmare on Elm Street",          
      "favorite serial":"The Big Bang Theory",           
      "favorite food":"ice cream",           
      "favorite time of year":"summer",            
      "Country you would like to visit":"New Zealand",             
      }                 
• Enter                
• Ctrl + D                                
**10) Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**          
• cat > skills.json                  
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
{ 
  "https://docs.google.com/spreadsheets/d/1sBzTaRsWcJAJcvIYXEU67vvfv7cC1JBv3a69DYAV2e8/edit?usp=sharing"
}     
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
 <its_me>
         <ful_name>Zvonilov_Aleksei_Mihailovich</ful_name>
        <age>33</age>
        <Numder_of_pets>0</Numder_of_pets>
        <Future_desired_salary>500$</Future_desired_salary>
  </its_me>        
• Esc           
• :wq        
**8) Отправить изменения на внешний репозиторий**           
• git add new.xml    
• git commit -m "chenges new.xml"    
• git push    
**9) Создать файл preferences.xml**     

     












