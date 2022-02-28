# proj114-balloon-mem-statistics
基于stratovirt新增balloon内存统计功能

## 项目描述

轻量虚拟机（Micro VM）是近几年新兴的一项虚拟化技术，StratoVirt是华为openEuler社区开源的轻量虚拟化软件，基于Rust语言编写，具备功能完善、安全可靠、启动快速、内存底噪小等特点，在容器和serverless场景有广阔的应用空间。本实验的目标是基于StratoVirt现有的能力，基于virtio以及balloon现有的能力，增加balloon的内存信息统计功能。最终实现通过qmp命令查询到虚拟机内存使用信息的功能。



## 所属赛道

2022全国大学生操作系统比赛的“OS功能设计”赛道

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2022年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求

## 难度

简单

## 项目导师

杨铭

* github
* email  yangming73@huawei.com



## 特征

- 为stratovirt的balloon特性添加内存信息统计功能
- 支持虚拟机内存信息统计查询的qmp接口。



## 进阶特性

- 在上面的基础上面增加free-page hitting功能。



## 参考资料

https://gitee.com/openeuler/stratovirt



## License

MulanPSL-2.0



## 预期目标

特征中的要求为必备能力，进阶特性为建议内容，不要求一定完成。选择本项目的同学也可提出自己的新想法，尤其是如何提高单机场景下的内存复用率。得到导师认可支持后亦可加入预期目标或进阶特性。
