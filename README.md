# TXT
1. **Создать внешний репозиторий c названием TXT.**

Зайти в раздел Repositories на Github. Нажать "NEW". Создать репозиторий "TXT"

 2. **Клонировать репозиторий TXT на локальный компьютер.**
 
Перейти в репозиторий "TXT", вкладка "Code", скопировать HTTPS. В терминале вызвать команду git clone https://github.com/Vikaufo/TXT.git

 3. **Внутри локального TXT создать файл “new.txt”.**
 
cd TXT 

touch new.txt

 4. **Добавить файл под гит.**
 
git add new.txt

 5. **Закоммитить файл.**
 
git commit -m "Add new file"

 6. **Отправить файл на внешний GitHub репозиторий.**
 
git push

 7. **Отредактировать содержание файла “new.txt” - написать информацию о себе. Всё написать в формате TXT.**
 
vim new.txt (i - инфа о себе) esc :wq

 8. **Отправить изменения на внешний репозиторий.**
 
git add .

git commit -m "Modifided file"

git push

 9. **Создать файл preferences.txt**
 
touch preferences.txt

 10. **В файл preferences.txt” добавить информацию о своих предпочтениях в формате TXT.**
 
vim preferences.txt (i - предпочтения) esc :wq

 11. **Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT**

touch skills.txt

vim (i - навыки) esc :wq

 12. **Сделать коммит в одну строку.**
 
git add . && git commit -m "Add preferences and skills" 

 13. **Отправить сразу 2 файла на внешний репозиторий.**

git push

 14. **На веб интерфейсе создать файл bug_report.txt.**
 
Вкладка "Add file - Create new file". Указать комментарий.

 15. **На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.**
 
Нажать "Edit this file"

 16. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
 
Нажать "Commit changes"

 17. **Синхронизировать внешний и локальный репозиторий TXT**

git pull
