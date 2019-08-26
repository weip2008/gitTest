
# Learn Git

```js

>
 git branch
* master
PS C:\Users\u229040\Documents\GitHub\gitTest>
PS C:\Users\u229040\Documents\GitHub\gitTest> git branch ruan
PS C:\Users\u229040\Documents\GitHub\gitTest> git branch
* master
  ruan
PS C:\Users\u229040\Documents\GitHub\gitTest> git checkout
Your branch is up to date with 'origin/master'.
PS C:\Users\u229040\Documents\GitHub\gitTest> git checkout ruan
Switched to branch 'ruan'
PS C:\Users\u229040\Documents\GitHub\gitTest> git branch
  master
* ruan

```

PS C:\Users\u229040\Documents\GitHub\gitTest> git status
On branch ruan
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        RuanLearnGit.md

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\u229040\Documents\GitHub\gitTest> git add *
PS C:\Users\u229040\Documents\GitHub\gitTest> git status
On branch ruan
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   RuanLearnGit.md

PS C:\Users\u229040\Documents\GitHub\gitTest> git commit -m "create a new file"
[ruan eaa1a27] create a new file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 RuanLearnGit.md
PS C:\Users\u229040\Documents\GitHub\gitTest> git status
On branch ruan
nothing to commit, working tree clean
PS C:\Users\u229040\Documents\GitHub\gitTest> git push
fatal: The current branch ruan has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ruan

PS C:\Users\u229040\Documents\GitHub\gitTest> git push --set-upstream origin ruan
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 276 bytes | 138.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ruan' on GitHub by visiting:
remote:      https://github.com/weip2008/gitTest/pull/new/ruan
remote:
To https://github.com/weip2008/gitTest.git
 * [new branch]      ruan -> ruan
Branch 'ruan' set up to track remote branch 'ruan' from 'origin'.
PS C:\Users\u229040\Documents\GitHub\gitTest> PS C:\Users\u229040\Documents\GitHub\gitTest> git add *
Get-Process : A positional parameter cannot be found that accepts argument 'git'.
At line:1 char:1
+ PS C:\Users\u229040\Documents\GitHub\gitTest> git add *
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-Process], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.GetProcessCommand
 
PS C:\Users\u229040\Documents\GitHub\gitTest> PS C:\Users\u229040\Documents\GitHub\gitTest> git status
Get-Process : A positional parameter cannot be found that accepts argument 'git'.
At line:1 char:1
+ PS C:\Users\u229040\Documents\GitHub\gitTest> git status
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-Process], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.GetProcessCommand
 
PS C:\Users\u229040\Documents\GitHub\gitTest> On branch ruan
On : The term 'On' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling 
of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ On branch ruan
+ ~~
    + CategoryInfo          : ObjectNotFound: (On:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> Changes to be committed:
Changes : The term 'Changes' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ Changes to be committed:
+ ~~~~~~~
    + CategoryInfo          : ObjectNotFound: (Changes:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest>   (use "git restore --staged <file>..." to unstage)
use : The term 'use' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling 
of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:4
+   (use "git restore --staged <file>..." to unstage)
+    ~~~
    + CategoryInfo          : ObjectNotFound: (use:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest>         new file:   RuanLearnGit.md
new : The term 'new' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling 
of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:9
+         new file:   RuanLearnGit.md
+         ~~~
    + CategoryInfo          : ObjectNotFound: (new:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest>
PS C:\Users\u229040\Documents\GitHub\gitTest> PS C:\Users\u229040\Documents\GitHub\gitTest> git commit -m "create a new file"
Get-Process : A positional parameter cannot be found that accepts argument 'git'.
At line:1 char:1
+ PS C:\Users\u229040\Documents\GitHub\gitTest> git commit -m "create a ...
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-Process], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.GetProcessCommand
 
PS C:\Users\u229040\Documents\GitHub\gitTest> [ruan eaa1a27] create a new file
At line:1 char:6
+ [ruan eaa1a27] create a new file
+      ~
Missing ] at end of attribute or type literal.
At line:1 char:7
+ [ruan eaa1a27] create a new file
+       ~~~~~~~~
Unexpected token 'eaa1a27]' in expression or statement.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : EndSquareBracketExpectedAtEndOfAttribute
 
PS C:\Users\u229040\Documents\GitHub\gitTest>  1 file changed, 0 insertions(+), 0 deletions(-)
At line:1 char:4
+  1 file changed, 0 insertions(+), 0 deletions(-)
+    ~~~~
Unexpected token 'file' in expression or statement.
At line:1 char:32
+  1 file changed, 0 insertions(+), 0 deletions(-)
+                                ~
Missing expression after unary operator '+'.
At line:1 char:48
+  1 file changed, 0 insertions(+), 0 deletions(-)
+                                                ~
Missing expression after unary operator '-'.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : UnexpectedToken
 
PS C:\Users\u229040\Documents\GitHub\gitTest>  create mode 100644 RuanLearnGit.md
create : The term 'create' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:2
+  create mode 100644 RuanLearnGit.md
+  ~~~~~~
    + CategoryInfo          : ObjectNotFound: (create:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> PS C:\Users\u229040\Documents\GitHub\gitTest> git status
Get-Process : A positional parameter cannot be found that accepts argument 'git'.
At line:1 char:1
+ PS C:\Users\u229040\Documents\GitHub\gitTest> git status
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-Process], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.GetProcessCommand
 
PS C:\Users\u229040\Documents\GitHub\gitTest> On branch ruan
On : The term 'On' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling 
of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ On branch ruan
+ ~~
    + CategoryInfo          : ObjectNotFound: (On:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> nothing to commit, working tree clean
nothing : The term 'nothing' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ nothing to commit, working tree clean
+ ~~~~~~~
    + CategoryInfo          : ObjectNotFound: (nothing:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> PS C:\Users\u229040\Documents\GitHub\gitTest> git push
Get-Process : A positional parameter cannot be found that accepts argument 'git'.
At line:1 char:1
+ PS C:\Users\u229040\Documents\GitHub\gitTest> git push
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-Process], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.GetProcessCommand
 
PS C:\Users\u229040\Documents\GitHub\gitTest> fatal: The current branch ruan has no upstream branch.
fatal: : The term 'fatal:' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ fatal: The current branch ruan has no upstream branch.
+ ~~~~~~
    + CategoryInfo          : ObjectNotFound: (fatal::String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> To push the current branch and set the remote as upstream, use
To : The term 'To' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling 
of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ To push the current branch and set the remote as upstream, use
+ ~~
    + CategoryInfo          : ObjectNotFound: (To:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest>
PS C:\Users\u229040\Documents\GitHub\gitTest>     git push --set-upstream origin ruan
Everything up-to-date
Branch 'ruan' set up to track remote branch 'ruan' from 'origin'.
PS C:\Users\u229040\Documents\GitHub\gitTest>
PS C:\Users\u229040\Documents\GitHub\gitTest> PS C:\Users\u229040\Documents\GitHub\gitTest> git push --set-upstream origin ruan
Get-Process : A positional parameter cannot be found that accepts argument 'git'.
At line:1 char:1
+ PS C:\Users\u229040\Documents\GitHub\gitTest> git push --set-upstream ...
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-Process], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.GetProcessCommand
 
PS C:\Users\u229040\Documents\GitHub\gitTest> Enumerating objects: 4, done.
Enumerating : The term 'Enumerating' is not recognized as the name of a cmdlet, function, script file, or operable program. 
Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ Enumerating objects: 4, done.
+ ~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (Enumerating:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> Counting objects: 100% (4/4), done.
Counting : The term 'Counting' is not recognized as the name of a cmdlet, function, script file, or operable program. Check 
the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ Counting objects: 100% (4/4), done.
+ ~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (Counting:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> Delta compression using up to 8 threads
Delta : The term 'Delta' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ Delta compression using up to 8 threads
+ ~~~~~
    + CategoryInfo          : ObjectNotFound: (Delta:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> Compressing objects: 100% (2/2), done.
Compressing : The term 'Compressing' is not recognized as the name of a cmdlet, function, script file, or operable program. 
Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ Compressing objects: 100% (2/2), done.
+ ~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (Compressing:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> Writing objects: 100% (3/3), 276 bytes | 138.00 KiB/s, done.
At line:1 char:42
+ Writing objects: 100% (3/3), 276 bytes | 138.00 KiB/s, done.
+                                          ~~~~~~
Expressions are only allowed as the first element of a pipeline.
At line:1 char:49
+ Writing objects: 100% (3/3), 276 bytes | 138.00 KiB/s, done.
+                                                 ~~~~~
Unexpected token 'KiB/s' in expression or statement.
At line:1 char:54
+ Writing objects: 100% (3/3), 276 bytes | 138.00 KiB/s, done.
+                                                      ~
Missing argument in parameter list.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : ExpressionsMustBeFirstInPipeline
 
PS C:\Users\u229040\Documents\GitHub\gitTest> Total 3 (delta 1), reused 0 (delta 0)
delta : The term 'delta' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:10
+ Total 3 (delta 1), reused 0 (delta 0)
+          ~~~~~
    + CategoryInfo          : ObjectNotFound: (delta:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: : The term 'remote:' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ remote: Resolving deltas: 100% (1/1), completed with 1 local object.
+ ~~~~~~~
    + CategoryInfo          : ObjectNotFound: (remote::String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> remote:
remote: : The term 'remote:' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ remote:
+ ~~~~~~~
    + CategoryInfo          : ObjectNotFound: (remote::String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> remote: Create a pull request for 'ruan' on GitHub by visiting:
remote: : The term 'remote:' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ remote: Create a pull request for 'ruan' on GitHub by visiting:
+ ~~~~~~~
    + CategoryInfo          : ObjectNotFound: (remote::String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> remote:      https://github.com/weip2008/gitTest/pull/new/ruan
remote: : The term 'remote:' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ remote:      https://github.com/weip2008/gitTest/pull/new/ruan
+ ~~~~~~~
    + CategoryInfo          : ObjectNotFound: (remote::String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> remote:
remote: : The term 'remote:' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ remote:
+ ~~~~~~~
    + CategoryInfo          : ObjectNotFound: (remote::String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest> To https://github.com/weip2008/gitTest.git
To : The term 'To' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling 
of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ To https://github.com/weip2008/gitTest.git
+ ~~
    + CategoryInfo          : ObjectNotFound: (To:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\u229040\Documents\GitHub\gitTest>  * [new branch]      ruan -> ruan
* : The term '*' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of
the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:2
+  * [new branch]      ruan -> ruan
+  ~
    + CategoryInfo          : ObjectNotFound: (*:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\u229040\Documents\GitHub\gitTest> Branch 'ruan' set up to track remote branch 'ruan' from 'origin'.
Branch : The term 'Branch' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ Branch 'ruan' set up to track remote branch 'ruan' from 'origin'.
+ ~~~~~~
    + CategoryInfo          : ObjectNotFound: (Branch:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\u229040\Documents\GitHub\gitTest> PS C:\Users\u229040\Documents\GitHub\gitTest>