1. soft and hard diff
2. hard: 撤销 本地仓库，暂存区，工作区所有修改， HEAD指向撤销节点(版本回退用)
3. soft: 撤销本地仓库修改，工作区和暂存区的都还在(合并多次commit用)
4. mixed: (不加reset默认) 撤销本地仓库，暂存区的修改，只保留了工作区的修改(commit后文件有错，想去掉这次commit，但那次commit的修改本地还有！！！)
5. 合并本地的多次commit: git rebase -i commitID(要合并到的id), p要用的id, s合并到前一个commit
   若要撤销合并 git rebase --abort
