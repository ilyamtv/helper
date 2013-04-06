
## Отмена изменений после push  
git push -f origin HEAD^:master  
Можно откатить не только на один шаг (^), но на любое количество: HEAD^^ (HEAD~2, HEAD~n).
  
## Добавить изменения в последний коммит  
git commit -m 'initial commit'  
git add forgotten_file  
git commit --amend  

