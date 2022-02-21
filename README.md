# HOMEWORK GIT. XML
XML
1. **Создать внешний репозиторий c названием XML.**  

 - Заходим на github.com  в свой аккаунт. 
 - Переходим на вкладку "Repositories" и создаем новый репозиторий c названием XML. 

2. **Клонировать репозиторий XML на локальный компьютер.**  

 - Нажимаем вкладку "Code" и копируем ссылку. 
 - Переходим в  = git bash 
 - В разделе создаем папку =  mkdir 2homework
 - Заходим в папку = cd 2homework
 - git clone (вставляем то что скопировали)

3. **Внутри локального XML создать файл “new.xml”.**  

 - touch new.xml

4. **Добавить файл под гит.**  

 - git add new.xml

5. **Закоммитить файл.**  

 - git commit -m "Add file xml"

6. **Отправить файл на внешний GitHub репозиторий.**  

 - git push 

7. **Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.**  

 - vim new.xml (Вносим данные)
 - ESQ -> :WQ -> Enter 

8. **Отправить изменения на внешний репозиторий.**  

 - git add new.xml
 - git commit -am "Add file, and add information about me"
 - git push 

9. **Создать файл preferences.xml**  

 - touch preferences.xml

10. **В файл preferences.xml” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате xml.**  

 - vim preferences.xml (Вносим данные)
 - ESQ -> :WQ -> Enter

11. **Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате xml.**  

 - vim preferences.xml (Вносим данные)
 - ESQ -> :WQ -> Enter

12. **Сделать коммит в одну строку.**   

 - git add . | git commit -m "Add 2 files with comment"

13. **Отправить сразу 2 файла на внешний репозиторий.**  

 - git push

14. **На веб интерфейсе создать файл bug_report.xml**  

 - Заходим на свою страницу в github.com -> Repositories -> JSON -> Add file -> Create new file -> Имя файла bug_report.xml

15. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.**  

 - Edit repository details -> save changes

16. **На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате xml.**  

 - Нажимаем на bug_report.xml ->  edit this file ->  Пишем  баг репорт. 

17. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.**  

 - Edit repository details -> save changes

18. **Синхронизировать внешний и локальный репозиторий JSON**  

 - переходим в git bash
 - git pull 
 








