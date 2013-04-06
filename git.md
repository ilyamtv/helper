
## Отмена изменений после push  
git push -f origin HEAD^:master  
Можно откатить не только на один шаг (^), но на любое количество: HEAD^^ (HEAD~2, HEAD~n).
  
## Отмена коммита  
git checkout HEAD^  

## Отмена изменения файла
git checkout -- file.name  