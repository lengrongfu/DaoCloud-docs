# 虚拟机功能

虚拟机模块提供虚拟机全生命周期的管理能力，虚拟机支持以下操作：

| 操作 | 描述 | 虚拟机状态 |
| --- | ---- | -------- |
| 创建虚拟机| 创建单台或多台虚拟机。| / |
| yaml编辑/更新虚拟机| 修改虚拟机。| 运行中/已关机/处理中/错误|
| 启动虚拟机| 将处于停止状态的虚拟机启动。| 已关机|
| 关机虚拟机| 将虚拟机关机。| 运行中/处理中|
| 重启虚拟机| 将处于运行状态的虚拟机重启。| 运行中/错误|
| 访问控制台| 打开虚拟机控制台，登录虚拟机系统（vnc、终端）| 运行中|
| 修改计算规格| 修改虚拟机的CPU、内存。支持在线/关机修改计算规格。| 运行中/已关机|
| 创建快照| 为虚拟机创建快照。| 运行中/已关机|
| 克隆虚拟机| 克隆当前虚拟机。| 运行中/已关机/错误|
| 实时迁移| 将虚拟机迁移到其他虚机节点，当前仅支持虚拟机热迁移。| 运行中|
| 数据盘扩容| 为虚拟机的数据盘扩容。| 运行中/已关机/处理中|
| 加载磁盘| 为虚拟机加载可用的数据磁盘。| 运行中/已关机|
| 卸载磁盘| 将已加载的磁盘从虚拟机卸载。| 运行中/已关机|
| 加载网卡| 为虚拟机加载网卡。| 已关机|
| 卸载网卡| 将已加载的网卡从虚拟机卸载。| 已关机|
| 虚拟机转换为模板| 将当前虚拟机转换为模板。| 运行中/已关机|
| 查看虚拟机详情| 进入虚拟机详情页，查看虚拟机基本信息、监控、事件、快照、配置信息。| 运行中/已关机/处理中|
| 删除虚拟机| 立即释放虚拟机的CPU、内存、IP地址等资源，并将虚拟机彻底删除，请谨慎操作。| 运行中/已关机/处理中/错误|
