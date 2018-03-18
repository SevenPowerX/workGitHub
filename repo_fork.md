FORK REPOSITORY AND SET UPSTREAM
1. После форка в вашем github появится несинхронизованная
копия (fork), склонируем ее и получим рабочую копию форка
  
  git clone https://github.com/YOUR_USERNAME/project.git

2. Свяжем рабочую копию вашего форка с репозиторием курса,
чтобы вы могли их синхронизировать и работать со свежей
версией кода и проверим, что это сработало
  > cd project
  
  > git remote add upstream https://github.com/ORIG_REPO/project.git
  
  > git remote -v
  
  origin https://github.com/YOUR_USERNAME/project.git (fetch)
  
  origin https://github.com/YOUR_USERNAME/project.git (push)
  
  upstream https://github.com/rybalkinsd/project.git (fetch)
  
  upstream https://github.com/rybalkinsd/project.git (push)

Теперь ваш fork будет известен git-у как origin (по умолчанию)
а репозиторий c которого вы сделали fork - как upstream (только что настроили)
