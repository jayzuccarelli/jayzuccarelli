### Jay Zuccarelli

building agentic systems and evals. shipping ml models in production.

🌐 [jayzuccarelli.com](https://jayzuccarelli.com) · 𝕏 [@jayzuccarelli](https://x.com/jayzuccarelli) · **in** [jayzuccarelli](https://linkedin.com/in/jayzuccarelli)

**projects**
**[saccade](https://github.com/jayzuccarelli/saccade)** · harness for proactive ambient agents. a cheap always-on model watches continuously and escalates to a larger one only on salience.

**[eden](https://github.com/jayzuccarelli/eden)** · claude agent tending a real hydroponic garden, with an esphome reflex tier holding safety deterministically underneath it.

**[memory-mcp](https://github.com/jayzuccarelli/memory-mcp)** · cross-llm memory over mcp. markdown files are the source of truth, so claude, chatgpt and cursor share one memory.

**[autofill](https://github.com/jayzuccarelli/autofill)** · browser agent that fills any web form from a description of you, built on browser-use. you review and submit.

**contributions**
- [pytorch #193649](https://github.com/pytorch/pytorch/pull/193649) re-parented dynamo's `dict_keys` tracker so `torch.compile` matches eager
- [huggingface transformers #49247](https://github.com/huggingface/transformers/pull/49247) documented left padding for batched generation across the ssm and hybrid model docs
- [huggingface openenv #1074](https://github.com/huggingface/OpenEnv/pull/1074) stopped rate-limited sandbox installs from retrying and hiding the real error
- [huggingface trl #7450](https://github.com/huggingface/trl/pull/7450) fixed flops-per-token over-counting untied models: the embedding is a lookup, the lm head always one matmul
- [cuda (cccl) #11722](https://github.com/NVIDIA/cccl/pull/11722) fixed `cuda::discard_iterator` returning a negated distance in nvidia's cuda c++ core libraries
- [vllm #58557](https://github.com/vllm-project/vllm/pull/58557) block-size errors now name each attention backend and the sizes it supports
- [dspy #10553](https://github.com/stanfordnlp/dspy/pull/10553) streamed chat adapter chunks now join to the parsed value, however the provider splits the whitespace
- [opencv #30093](https://github.com/opencv/opencv/pull/30093) python typing stubs now import `typing` for `Sequence` return types
- [inspect_ai #5375](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5375) agent bridge now passes through web search and code execution items from google and mistral
- [inspect_ai #5102](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5102) fixed chat templates that call dict methods on messages

