**TXT**<br>
 4. Создать внешний репозиторий c названием TXT<br> **->**`GitHub>Repositories>New "TXT" repositories`<br>
 5. Клонировать репозиторий TXT на локальный компьютер<br> **->**`git clone ssh-link`<br>
 6. Внутри локального TXT создать файл “new.txt”<br> **->**`touch new.txt`<br>
 7. Добавить файл под гит<br> **->**`git add new.txt`<br>
 8. Закоммитить файл<br> **->**`git commit -m "new"`<br>
 9. Отправить файл на внешний GitHub репозиторий<br> **->**`git push`<br>
 10. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT<br> **->**`vim new.txt`<br>
 11. Отправить изменения на внешний репозиторий<br> **->**`git commit -am "update">git push`<br>
 12. Создать файл preferences.txt<br> **->**`touch preferences.txt`<br>
 13. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT<br> **->**`vim preferences.txt`<br>
 14. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT<br> **->**`touch skills.txt`<br>
 15. Отправить сразу 2 файла на внешний репозиторий<br> **->**`git add * >git commit -m "new files">git push`<br>
 16. На веб интерфейсе создать файл bug_report.txt<br> **->**`Github>Repositories>"TXT">Add file>Create new file`<br>
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе<br> **->**`Tap on the [Commit changes...]button`<br>
 18. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT<br> **->**`bug_report.txt>[Edit this file]`<br>
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе<br> **->**`Tap on the [Commit changes...]button`<br>
 20. Синхронизировать внешний и локальный репозиторий TXT<br> **->**`git pull`<br>
