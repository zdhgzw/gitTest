1. soft and hard diff
2. hard: 撤销 暂存区，工作区所有修改， HEAD指向撤销节点(版本回退用)
3. soft: 仅撤销仓库提交，工作区和暂存区的都还在(合并多次commit用)
4. mixed: (不加reset默认) 只保留了工作区的修改
