# AI & 互联网热词

> 每日更新：每次日报随机抽取 2~3 个术语，结合当前行业热点生成新例句。
> 注意：AI 领域发展迅速，例句应尽量使用最新动态（模型发布、技术突破、行业事件），不确定时优先使用 LLM/Agent 相关的成熟词汇。

## 一、基础概念

| 术语 | 释义 | 例句 |
|------|------|------|
| LLM (Large Language Model) | 大语言模型 | GPT-4 is one of the most capable LLMs available today. |
| Foundation model | 基础模型 | A foundation model is pre-trained on vast data and fine-tuned for specific tasks. |
| Generative AI (GenAI) | 生成式 AI | Generative AI can create text, images, and code from prompts. |
| Prompt | 提示词 | Crafting a good prompt is key to getting useful outputs from an LLM. |
| Prompt engineering | 提示工程 | Prompt engineering is a new and valuable skill in the AI era. |
| Zero-shot | 零样本 | This model can handle zero-shot tasks without any examples. |
| Few-shot | 少样本 | Few-shot prompting gives the model a couple of examples to follow. |
| In-context learning | 上下文学习 | The model learns from examples provided in the prompt — that's in-context learning. |
| Token | 词元 | A token is roughly 0.75 words in English. GPT-4 can handle 128K tokens. |
| Inference | 推理/推断 | Inference cost is the main expense for running LLMs in production. |
| Fine-tuning | 微调 | We fine-tuned a base model on our customer support data. |
| Pre-training | 预训练 | Pre-training on large-scale data gives the model general language understanding. |
| Hallucination | 幻觉 | Hallucination is when an LLM generates plausible-sounding but incorrect information. |
| Context window | 上下文窗口 | A larger context window means the model can process longer documents. |
| Temperature | 温度参数 | Lower temperature makes output more deterministic; higher temperature makes it more creative. |

## 二、模型与架构

| 术语 | 释义 | 例句 |
|------|------|------|
| Transformer | Transformer 架构 | The Transformer architecture is the backbone of most modern LLMs. |
| Attention mechanism | 注意力机制 | Attention allows the model to focus on relevant parts of the input. |
| Multi-head attention | 多头注意力 | Multi-head attention lets the model track different types of relationships. |
| GPT (Generative Pre-trained Transformer) | 生成式预训练模型 | GPT-4o set new benchmarks across reasoning and multimodal tasks. |
| Claude | Claude 模型 | Claude is known for its strong reasoning and nuanced responses. |
| Gemini | Gemini 模型 | Google's Gemini is a natively multimodal model. |
| Llama | Llama 开源模型 | Meta's Llama models have accelerated open-source AI development. |
| Mixture of Experts (MoE) | 混合专家模型 | Mixture of Experts architectures allow massive models with lower inference cost. |
| Embedding | 嵌入向量 | We converted all documents into embeddings for semantic search. |
| Vector database | 向量数据库 | We use a vector database to store embeddings for similarity search. |
| RAG (Retrieval-Augmented Generation) | 检索增强生成 | RAG combines retrieval with generation to reduce hallucinations. |
| Chunking | 分块处理 | We split documents into 512-token chunks for embedding. |
| Cross-encoder | 交叉编码器 | A cross-encoder gives more accurate relevance scoring than bi-encoders. |
| Sparse model | 稀疏模型 | Sparse models activate only relevant pathways, reducing compute. |
| Dense model | 稠密模型 | Dense models activate all parameters for every input. |
| Quantization | 模型量化 | Quantization reduces model size with minimal quality loss. |
|蒸馏 (Distillation) | 模型蒸馏 | We distilled the large model into a smaller, faster version. |

## 三、AI Agent

| 术语 | 释义 | 例句 |
|------|------|------|
| AI Agent | AI 智能体 | An AI agent can plan, use tools, and complete multi-step tasks autonomously. |
| Agentic | 智能体化的 | We're seeing more agentic AI applications in enterprise workflows. |
| Tool use / function calling | 工具调用 | The agent uses tool calling to fetch real-time data when needed. |
| ReAct (Reason + Act) | 推理-行动框架 | ReAct combines reasoning traces with action execution. |
| Chain-of-thought (CoT) | 思维链 | Chain-of-thought prompting improves reasoning on complex problems. |
| Tree of thoughts | 思维树 | Tree of thoughts explores multiple reasoning paths simultaneously. |
| Self-reflection | 自我反思 | The agent uses self-reflection to evaluate and correct its own outputs. |
| Memory | 记忆 | We give the agent short-term and long-term memory for context continuity. |
| Session memory | 会话记忆 | Session memory lets the agent remember what happened earlier in the conversation. |
| Persistent memory | 持久记忆 | Persistent memory stores learnings across different sessions. |
| Multi-agent | 多智能体系统 | A multi-agent system coordinates several specialized agents. |
| Agent orchestration | 智能体编排 | Agent orchestration frameworks like LangGraph manage complex workflows. |
| Orchestrator | 编排器 | The orchestrator decides which agent handles each subtask. |
| Sub-agent | 子智能体 | Each sub-agent specializes in one domain, like search or coding. |
| Delegation | 委托/分派 | The orchestrator handles delegation of tasks to specialized agents. |
| Handoff | 任务交接 | When a task goes out of scope, the agent does a clean handoff. |
| Long-horizon task | 长期任务 | Long-horizon tasks require planning and milestone tracking. |
| Goal decomposition | 目标分解 | The agent breaks down a vague goal into concrete, executable steps. |
| Loop detection | 循环检测 | Loop detection prevents the agent from repeating the same failed action. |
| Retry logic | 重试逻辑 | Retry logic kicks in when a tool call fails. |

## 四、提示工程

| 术语 | 释义 | 例句 |
|------|------|------|
| System prompt | 系统提示词 | The system prompt defines the persona and behavior of the AI. |
| User prompt | 用户提示词 | The user prompt is the actual task or question from the user. |
| System instruction | 系统指令 | A clear system instruction prevents the model from going off-topic. |
| Chain-of-thought prompting | 思维链提示 | We use chain-of-thought prompting to improve math accuracy. |
| Few-shot prompting | 少样本提示 | Few-shot prompting is great for tasks with consistent formatting. |
| Prompt template | 提示词模板 | We use prompt templates to standardize our LLM calls. |
| Prompt injection | 提示词注入攻击 | Prompt injection is a security concern in production LLM systems. |
| Prompt leakage | 提示词泄露 | We need to protect against prompt leakage in customer-facing apps. |
| Suffix attack | 后缀攻击 | Suffix attacks attempt to bypass safety guardrails. |
| Constraint prompting | 约束提示 | Constraint prompting tells the model exactly what format to output in. |
| Role prompting | 角色提示 | Role prompting improves quality: \"You are an experienced copywriter...\" |
| Negative prompting | 负面提示 | Negative prompting tells the model what NOT to do. |
| Structured output | 结构化输出 | We use structured output to force JSON responses. |
| Output parser | 输出解析器 | The output parser validates and extracts data from LLM responses. |
| Jailbreak | 越狱攻击 | We test for jailbreak vulnerabilities during red-teaming. |

## 五、安全与对齐

| 术语 | 释义 | 例句 |
|------|------|------|
| Alignment | 对齐 | AI alignment ensures models behave in accordance with human values. |
| RLHF (Reinforcement Learning from Human Feedback) | 基于人类反馈的强化学习 | RLHF is key to making LLMs helpful and harmless. |
| RLAIF (RL from AI Feedback) | 基于 AI 反馈的强化学习 | RLAIF uses AI feedback instead of human feedback to train models. |
| Constitutional AI | 宪法 AI | Constitutional AI guides model behavior through a set of principles. |
| Guardrail | 安全护栏 | We added guardrails to prevent the model from sharing PII. |
| Content moderation | 内容审核 | AI-powered content moderation catches 95% of policy violations. |
| Red-teaming | 红队测试 | We ran a red-teaming exercise to find safety vulnerabilities. |
| Toxicity | 有害内容 | We measure toxicity to ensure the model doesn't produce harmful output. |
| Bias | 偏见 | We're auditing the model for demographic bias in hiring recommendations. |
| Fairness | 公平性 | Fairness evaluation is part of our model release checklist. |
| Explainability | 可解释性 | Explainability helps users understand why the model made a decision. |
| Interpretability | 可解释性（模型层面）| Interpretability research aims to understand what happens inside neural nets. |
| Privacy | 隐私保护 | We anonymize all training data to protect user privacy. |
| Data governance | 数据治理 | Data governance ensures responsible use of data in AI systems. |
| Responsible AI | 负责任 AI | Responsible AI is a company-wide initiative, not just an engineering concern. |
| Auditability | 可审计性 | Auditability is required for compliance in regulated industries. |
| Watermarking | 水印 | We embed invisible watermarks in AI-generated content. |
| Synthetic data | 合成数据 | We're using synthetic data to augment training sets without privacy risk. |

## 六、工具与平台

| 术语 | 释义 | 例句 |
|------|------|------|
| API (Application Programming Interface) | 应用程序接口 | We exposed the LLM via a REST API for internal teams. |
| SDK (Software Development Kit) | 软件开发包 | The AI SDK makes it easy to integrate the model into our app. |
| Model serving | 模型服务 | We're optimizing model serving for lower latency. |
| Model registry | 模型注册中心 | All models are versioned and stored in the model registry. |
| Evaluation benchmark | 评估基准 | MMLU is a common evaluation benchmark for language models. |
| Benchmarks | 基准测试 | The model scored 92% on the MMLU benchmark. |
| Tokenizer | 分词器 | The tokenizer converts text into tokens for the model. |
| Playground | 调试平台 | We use the playground to experiment with prompts before production. |
| Evaluation harness | 评测框架 | We built an evaluation harness to track model performance over time. |
| Evals (Evaluations) | 测试评估 | We ran 500 evals before shipping the new model version. |
| LLMOps | LLM 运维 | LLMOps covers everything from deployment to monitoring in production. |
| MCP (Model Context Protocol) | 模型上下文协议 | MCP enables AI models to connect to external data sources and tools. |
| AI gateway | AI 网关 | We route all LLM requests through an AI gateway for monitoring. |
| Rate limiting | 速率限制 | We implemented rate limiting to prevent API abuse. |

## 七、应用与行业

| 术语 | 释义 | 例句 |
|------|------|------|
| Copilot | AI 副驾驶 | GitHub Copilot has changed how developers write code. |
| Pair programming with AI | AI 结对编程 | AI结对编程 is becoming standard practice in software teams. |
| AI-first company | AI 优先公司 | We're transitioning to an AI-first product strategy. |
| Automation | 自动化 | AI is automating knowledge work, not just manual tasks. |
| Augmentation | 人机协作增强 | The goal is augmentation, not replacement of human workers. |
| AI-powered search | AI 搜索 | AI-powered search understands intent, not just keywords. |
| Semantic search | 语义搜索 | Semantic search uses embeddings to find conceptually related content. |
| Conversational AI | 对话式 AI | Our conversational AI handles 60% of customer inquiries. |
| Voice assistant | 语音助手 | Voice assistants are getting much smarter with LLM integration. |
| Autonomous agent | 自主智能体 | An autonomous agent can complete an entire workflow without human input. |
| Agentic workflow | 智能体工作流 | Agentic workflows string together multiple AI capabilities. |
| Digital twin | 数字孪生 | The digital twin simulates the physical system for AI-driven optimization. |
| Industrial AI | 工业 AI | Industrial AI is transforming manufacturing quality control. |
| Healthcare AI | 医疗 AI | Healthcare AI assists doctors with diagnosis but requires strict regulation. |
| Legal AI | 法律 AI | Legal AI tools draft contracts and conduct research in minutes. |

## 八、模型训练与研发

| 术语 | 释义 | 例句 |
|------|------|------|
| Training data | 训练数据 | Training data quality is more important than quantity. |
| Data curation | 数据清洗和筛选 | Data curation removes noise and improves model performance. |
| Data labeling | 数据标注 | We used a combination of human labeling and synthetic labeling. |
| Active learning | 主动学习 | Active learning selects the most informative examples for labeling. |
| Transfer learning | 迁移学习 | Transfer learning lets us fine-tune a pre-trained model on our domain. |
| Continual learning | 持续学习 | Continual learning enables models to update without full retraining. |
| Pre-training corpus | 预训练语料 | The pre-training corpus includes web text, books, and code. |
| Instruction tuning | 指令微调 | Instruction tuning aligns the model with human instructions. |
| Reward model | 奖励模型 | The reward model is trained to score outputs by human preference. |
| PPO (Proximal Policy Optimization) | 近端策略优化 | PPO is used in the RLHF training pipeline. |
| Gradient descent | 梯度下降 | Gradient descent optimizes model parameters during training. |
| Overfitting | 过拟合 | The model started overfitting after too many training epochs. |
| Underfitting | 欠拟合 | Underfitting means the model is too simple to capture the pattern. |
| Generalization | 泛化能力 | Good generalization means the model handles unseen data well. |
| Emergent capability | 涌现能力 | Reasoning emerged as an emergent capability in larger models. |
| Scaling law | Scaling 法则 | Scaling laws predict that larger models and data improve performance. |
| Compute | 算力 | Compute requirements for training frontier models are enormous. |
| GPU cluster | GPU 集群 | Training runs on a 10,000-GPU cluster for 30 days. |

## 九、最佳实践

| 术语 | 释义 | 例句 |
|------|------|------|
| Production readiness | 生产就绪 | We have a production readiness checklist before any AI feature ships. |
| Cost optimization | 成本优化 | We switched to a smaller model for simple tasks to cut costs. |
| Latency | 延迟 | Target latency for real-time features is under 500ms. |
| Throughput | 吞吐量 | We optimized batching to improve throughput by 3x. |
| Graceful degradation | 优雅降级 | The app should show a friendly message when the AI service is down. |
| Fallback | 降级方案 | If the AI is unavailable, we fall back to rule-based logic. |
| Observability | 可观测性 | We added observability to track LLM costs and quality in production. |
| Cost attribution | 成本归因 | Cost attribution helps us understand which features use the most AI budget. |
| Model versioning | 模型版本管理 | We pin specific model versions in production for stability. |
| A/B testing LLM outputs | AI 输出测试 | We A/B test different prompts to find the best-performing version. |
| Human-in-the-loop (HITL) | 人在回路 | Critical decisions require human-in-the-loop review. |
| Monitoring drift | 监控数据漂移 | We monitor for model drift to catch quality degradation early. |
| Caching | 缓存 | We cache LLM responses to reduce cost and improve latency. |
| Prompt versioning | 提示词版本管理 | Prompt changes are versioned alongside model versions. |
| Model evaluation | 模型评估 | We conduct model evaluation quarterly on a holdout dataset. |
