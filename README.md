# Git教程 
##  git简介
    - Git(读音为/gɪt/)是一个开源的分布式版本控制系统，可以有效、高速地处理从很小到非常大的项目版本管理。
    - Git 是 Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本控制软件。
    - Torvalds 开始着手开发 Git 是为了作为一种过渡方案来替代 BitKeeper。
    - Git是目前世界上最先进的分布式版本控制系统，在处理各种项目时都十分高效，而且非常的高大上。  
    - SVN是集中式版本控制系统，版本库是集中放在中央服务器的，而干活的时候，用的都是自己的电脑，所以首先要从中央服务器哪里得到最新的版本，  
    - 然后干活，干完后，需要把自己做完的活推送到中央服务器。而且集中式版本控制系统是必须联网才能工作。  
    - Git是分布式版本控制系统，它就没有中央服务器的，每个人的电脑就是一个完整的版本库，这样，工作的时候就不需要联网了，因为版本都是在自己的电脑上。  
##  git的功能特性
    - 从服务器上克隆完整的Git仓库(包括代码和版本信息)到单机上。
    - 在自己的机器上根据不同的开发目的，创建分支，修改代码。
    - 在单机上自己创建的分支上提交代码。
    - 在单机上合并分支。
    - 把服务器上最新版的代码fetch下来，然后跟自己的主分支合并。
    - 生成补丁(patch)，把补丁发送给主开发者。
    - 看主开发者的反馈，如果主开发者发现两个一般开发者之间有冲突(他们之间可以合作解决的冲突)，就会要求他们先解决冲突，然后再由其中一个人提交。如果主开发者可以自己解决，或者没有冲突，就通过。
    - 一般开发者之间解决冲突的方法，开发者之间可以使用pull 命令解决冲突，解决完冲突之后再向主开发者提交补丁。
##  git安装  
    - （仅列出在Windows系统下的安装过程）  
    -打开Git官网下载安装程序，然后按照默认选项安装即可。  
    -安装完成后，打开Git bash软件，弹出一个类似cmd的命令行窗口，证明安装成功        
##  创建版本库   
    -版本库(repository)也叫仓库，可以看做一个目录，这个目录里的所以文件都由Git进行管理，每个文件的修改、删除，Git都能跟踪    
##  工作区和暂存区  
    -工作区（Working Directory）  
    -learngit 文件夹就是一个工作区。  
    -版本库（Repository）  
    -工作区有个隐藏目录 .git ，这个不算工作区，而是 Git 的版本库  
    -版本库里面的 index(stage) 文件叫暂存区，还有Git为我们自动创建的第一个分支 master ，以及指向 master 的一个指针叫做 HEAD  
github项目地址：https://github.com/CyberHunterMK5/-
