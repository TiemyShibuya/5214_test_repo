 # Prática de Git
## Exemplo de Markdown
`git init` - inicia o Git no diretório atual





Tiemy Shibuya@DESKTOP-LL7OCQ1 MINGW64 ~/5214 (master)
$ git add .

Tiemy Shibuya@DESKTOP-LL7OCQ1 MINGW64 ~/5214 (master)
$ git commit -m "update readme.md"
[master d665ff4] update readme.md
 1 file changed, 1 insertion(+), 1 deletion(-)

Tiemy Shibuya@DESKTOP-LL7OCQ1 MINGW64 ~/5214 (master)
$ git log
commit d665ff47a7769461db7fdf9914ac810e96d59bfd (HEAD -> master)
Author: Tiemy Watanabe <tyemy0926@gmail.com>
Date:   Thu Apr 25 20:18:19 2019 -0300

    update readme.md

commit 22a4d6787791ca80acf8d20c7ab039baf0b0d37a (origin/master)
Author: Tiemy Watanabe <tyemy0926@gmail.com>
Date:   Thu Apr 25 19:52:21 2019 -0300

    primeiro commit -add readme.md

Tiemy Shibuya@DESKTOP-LL7OCQ1 MINGW64 ~/5214 (master)
$ git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 108.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/TiemyShibuya/5214_test_repo.git
   22a4d67..d665ff4  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

