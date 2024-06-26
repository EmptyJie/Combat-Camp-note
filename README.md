# 书生·浦语大模型全链路开源体系笔记

### 1.人工智能技术发展方向的改变：

在早期时，人工智能领域技术多为专用模型：针对特定任务，一个模型解决一个问题。最近两年在往通用模型发展，一个大模型可以解决多类问题。



### 2.书生·浦语大模型开源历程：

2023.6.7 **InternLM**千亿参数语言大模型发布

7月6日 全面升级，支持8K语境、26种语言**全面开源，免费商用**：InternLM-7B

8月14日 **书生·万卷 1.0 **多模态预训练语料库开源发布

8月21日升级版对话模型**InternLM-Chat-B v1.1** 发布

8月28日 **InternLM**千亿参数模型参数量升级至123B

9月20日 **增强版InternLM-20B**开源

2024.1.17 **InternLM 2** 开源



### 3.书生·浦语2.0（InternLM2）的体系：

7B：为轻量级的研究和应用提供了一个轻便但性能不俗的模型

20B：模型的综合性能更为强劲，可有效支持更加复杂的实用场景



### 4.书生·浦语2.0（InternLM2）的主要亮点：

- 超长上下文
- 综合性能全面提升：在轻量级开源模型、中量级开源模型性能超过ChatGLM3-6B-32K、BaiChuan2-7B-Chat等，比肩ChatGPT（3.5）的水平
- 优秀的对话和创作体验：贴心可靠的AI助手、充满人文关怀的对话、富有想象力的创作
- 工具调用能力整体升级：：可通过调用BINGMap API、Email API等工具完成复杂任务
- 突出的数据能力和实用的数据分析功能：简单运算的高准确率和复杂运算、分析表格、数据预测



### 5.书生·浦语全链条开源开放体系：

- 数据：书生·万卷 1.0 总数居量达到2.0TB（符合主流中国价值观的中文语料）；书生·万卷CC开源数据集 400GB（安全、信息密度更高的英文语料）
- 预训练：高可扩展、极致性能优化、兼容主流、开箱即用
- 微调：增量续训（垂直领域），有监督微调（高效微调框架XTuner：适配多种生态，适配多种硬件）
- 部署：LMDeploy全流程解决方案，高效推理引擎，完备易用的工具链，支持交互式推理，不为历史对话买单
- 评测：
  - 2023年5月1日完成Alpha版本开发
  - 7月6日OpenCompass正式开源
  - 8月18日OpenCompass数据和性能对比上线
  - 9月7日支持多编程语言代码评测
  - 10月26日联合南京大学推出大模型司法能力评测基准
  - 12月1日发布多模态评测工具套件VLMEvalKit
  - 2024年1月30日OpenCompass 2.0 司南大模型评测体系正式发布
- 应用
- 智能体：轻量级智能体框架Lagent：支持多种类型的智能体能力，灵活支持多种大语言模型，简单易拓展，支持丰富的工具



### 总结

​	通过这节课对书生·浦语大模型有了更深入和全方位的了解，首先是全面开源免费商用，反映了其开放、共享的胸怀，体现了书生·浦语大模型对科研和应用需求的关注。并且书生·浦语大模型的持续迭代升级：从千亿级参数到1230亿级，以及支持多种语言和长语境，展现了实验室团队的不懈努力和持续创新精神。再就是全链条开源开放体系体现了书生·浦语大模型的完整性和易用性。

