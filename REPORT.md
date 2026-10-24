# Лабораторная работа 1. Установка Git и первый репозиторий

### $ git --version
git version 2.54.0.windows.1

### $ git config --global user.name
Ali717-code

### $ git config --global user.email
guy70659@gmail.com

### $ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

### $ git log --format=%h %an <%ae> %ad %s
a0a496c Ali717-code <guy70659@gmail.com> Sat Oct 24 14:36:46 2026 +0300 Изменён hello.txt
e57c7a8 Ali717-code <guy70659@gmail.com> Sat Oct 24 14:36:46 2026 +0300 Добавлен hello.txt
20aebbd Ali717-code <guy70659@gmail.com> Sat Oct 24 14:36:46 2026 +0300 Первый коммит: добавлен README

### $ git log --oneline --stat
a0a496c Изменён hello.txt
 hello.txt | 1 +
 1 file changed, 1 insertion(+)
e57c7a8 Добавлен hello.txt
 hello.txt | 1 +
 1 file changed, 1 insertion(+)
20aebbd Первый коммит: добавлен README
 README.md | 1 +
 1 file changed, 1 insertion(+)
