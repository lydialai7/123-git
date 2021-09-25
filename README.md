$ echo "#123 Git" > README.md
$ git init
Initialized empty Git repository in /private/tmp/123-git/.git/

$ git add README.md

$ git commit -m "first commit"
[master (root-commit) adc1a5a] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
 $ git remote add origin git@github.com:lydialai7/123-git.git
 $ git push -u origin master
 #include <stdio.h>

int main( void ){
    printf("%s\n", "My name is 賴盈如");
    printf("%s\n", "My ID is D1090434");
    printf("%s\n", "My major is 資訊一甲");
}
To github.com:lydialai7/123-git.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
