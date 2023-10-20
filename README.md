# Практическая работа №1  
Научился делать следующие комманды:
```
git add
git commit
git status
git push
```
---  

___  

[GitHub](https://github.com/ "Ссылка на сайт")  

__Хеш__ — основной идентификатор коммита и позволяет узнать его автора, дату и содержимое закоммиченных файлов.
Все хеши, а также таблицу соответствий ```хеш → информация о коммите``` Git хранит в папке ```.git.```  

В числе прочих файлов в папке ```.git есть``` служебный файл ```HEAD```. Он указывает на самый свежий коммит.  
Вместо хеша последнего коммита можно написать слово ```HEAD``` — Git вас поймёт.  

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
```