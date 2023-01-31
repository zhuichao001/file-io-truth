## 文件IO知识架构

**文件IO为什么很重要**
- 复杂，调用链长，往往是存储系统的主要瓶颈
- 使用对用户透明，但是如果涉及调优则必须关心底层细节

![IO分层架构](images/linux_io_stack_diagram.jpg =900*700)  
参考：https://fio.readthedocs.io/en/latest/
