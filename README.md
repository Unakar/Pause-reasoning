# Pause-reasoning
 Official implementation of paper "Hesitation for Brilliance: Dynamic Pause Tokens as Regulatory Mechanisms in LLM's Complex Reasoning Odyssey"
 
 官方代码实现: “犹豫的智慧:动态停顿token实现大模型复杂问题推理增强”

利用自适应门控网络实现不同下游任务的pause tokens分发，增加计算宽度的同时几乎不会带来额外的FLOPS计算量消耗。

实验证明，在预训练，微调，推理阶段都采用此方法(但不同阶段使用不同停顿策略)可以大幅提升LLM在GSM8K, CommonSense, ruozhiba 的复杂推理能力。

