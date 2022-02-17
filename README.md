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
**4) Закоммитить файл**        
• git commit -m "add new.json"     
**5)Отправить файл на внешний GitHub репозиторий**     
• git push      
**6)Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.**      
• vim new.json     
•  i      
{ 
        "ful_name":"Zvonilov Aleksei Mihailovich",
        "age":33,
        "Numder of pets":0,
        "Future desired salary":500"$"
          
}           





