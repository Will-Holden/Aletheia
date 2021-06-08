# Aletheia

Aletheia是一个由智能计算驱动的虚拟系统工具组件。旨在通过计算实验/数学工程化的手段，对复杂系统的治理机制的设计、测试、验证进行计算、模拟，以实现系统的科学设计及决策。

基于区块链和智能合约之上的去中心化治理，是一个典型的由复杂的人类行为和群体决策组成的的系统。难以通过经验决策、数学推演，验证其治理策略。Aletheia，基于对现实世界治理系统或治理机制的整体、还原建模，对各类实际或虚拟的实验场景执行计算，观察和量化评估各类参数配置、效果性能，并预测其演变规律，从而实现现实治理系统的科学演化和发展。

## agents 模块

Agent 模块在Aletheia系统中进行对人的建模工作。
在Agent模块预置了一些对于人的建模的模型，例如 预测市场中的零策略智能体模型。

### 智能体结构

每一个智能体都有两个文件组成，一个owl文件，用于表示智能体的知识结构。一个是py文件，包含智能体的观察、推理、行动逻辑。

### 使用方法

python  aletheia.py agent -c -n [name] -p [path]

产生的智能体可以用于多智能体的模拟

### 智能体文件的校验

使用md5码对其进校验, 校验码存储在区块链上。