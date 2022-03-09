药物研发量子计算解决方案（Quantum Ready Architecture for Drug Discovery, QRADD）旨在帮助客户研究药物发现问题，比如分子对接，蛋白质折叠等。通过Amazon Braket调用量子计算资源进行实验，同时调用经典计算资源进行对比，从而让客户提升研究效率，获取研究的新思路。

本解决方案主要具备以下特点：

- 一键部署包含量子计算和经典计算工作流的混合架构
- 完全托管的Jupyter笔记本，用于设计和调试药物研发算法
- 基于AWS Step Functions和AWS Batch的工作流，用于批量验证算法性能
- 通过Amazon Quicksight展示XXX结果
- 自定义其它药物研发问题的算法并进行复用

同时，该方案还提供配套的[动手实验](workshop/background.md)，以分子展开为例，介绍相关背景知识，建模和优化方法，批量验证和自定义算法等，从而帮助您更快了解如何运用量子计算技术研究药物研发问题。

本实施指南介绍在亚马逊云科技云中部署药物研发量子计算解决方案的架构信息和具体配置步骤。它包含指向[CloudFormation][cloudformation]模板的链接，这些模板使用亚马逊云科技在安全性和可用性方面的最佳实践来启动和配置本解决方案所需的亚马逊云科技服务。

本指南面向具有亚马逊云科技架构实践经验的IT架构师、开发人员、DevOps、数据科学家和算法工程师、以及药物研发领域的技术人员。

[cloudformation]: https://aws.amazon.com/en/cloudformation/