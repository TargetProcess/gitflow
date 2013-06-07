HubFlow
=======

Adds the 'git hf' Git extension to provide high-level repository operations
for [DataSift's HubFlow branching model](http://datasift.github.com/gitflow/), which is based on [Vincent Driessen’s original blog post](http://nvie.com/posts/a-successful-git-branching-model/).

![](http://nvie.com/img/2009/12/Screen-shot-2009-12-24-at-11.32.03.png)

Installation
------------
Execute these lines outside TP trunk!


    git clone https://github.com/TargetProcess/gitflow.git --recursive
    cd gitflow\contrib
    msysgit-install.cmd "c:\Program Files (x86)\Git"


Goto your trunk and execute following lines:

    git stash -u
    git checkout master
    git branch develop
    git hf init


And now you can use git flow from console.


Getting Started
---------------

See our tutorial website to learn more about the [GitFlow](http://datasift.github.com/gitflow/IntroducingGitFlow.html) branching model and [how to use the HubFlow tools](http://datasift.github.com/gitflow/GitFlowForGitHub.html).

Changelog
---------

To see what's new in each release, see our [Changelog](http://datasift.github.com/gitflow/ChangeLog.html).

License Terms
-------------
HubFlow is published under the liberal terms of the BSD License, see the
[LICENSE](LICENSE) file. Although the BSD License does not require you to share
any modifications you make to the source code, you are very much encouraged and
invited to contribute back your modifications to the community, preferably
in a Github fork, of course.
