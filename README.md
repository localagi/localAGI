## 🧮 localAGI 🧮
Fulltime nerd. Passionate developer. DevOp at heart.

Thats me. :bowtie: Building AGI on local hardware.

*You want to **run your own inferences** with ease? Good you are awake.*


Building contaners for effectively running a local artificial general intelligence. :mechanical_arm:

## :stars: Motivation :stars:

Initially started my work for deployments of [josh-XT/AGiXT](https://github.com/Josh-XT/AGiXT)

Having reproducable software environments to spin up services on demand for testing and sky-netting.
Setup and streamline docker containers for quick and user friendly usage.

:rocket: CUDA enabled. :desktop_computer: BLAS enabled. :smirk: Conda-less. :onion: Matrix builds. :office: Multiarch builds. :child: :adult: :older_adult: For everyone.



## :hibiscus: Sharing is caring :hibiscus:

With strong expertise in `docker` and `github workflows` I want to test all the AI-related projects online using docker containers.

**Working on [AI-dedicated Workflows](https://github.com/localagi/ai-dedicated-workflows)** to share best practices over several repositories and projects.

## State of work

The following projects on my namespace are built using the **[AI pipeline](https://github.com/localagi/ai-dedicated-workflows)**.
My maintenance is focussed on build stabilty and availability of service containers.

* :heavy_check_mark: == Working
* (:heavy_check_mark:) == Working soonish
* (WIP) == some unstable state

### AI-pipeline-built services for *running* inference
| Service                                                          | Model-types     | Model-quantisations | API-compatibility | Release              | Original Repo |
-------------------------------------------------------------------|-----------------|---------------------|-------------------|----------------------|---------------|
| [FastChat](https://github.com/localagi/FastChat-docker)          | e.g. Vicuna, T5 | T5, HF              | OpenAI            | :heavy_check_mark:   | [lm-sys/FastChat](https://github.com/lm-sys/FastChat) |
| [oobabooga](https://github.com/localagi/oobabooga-docker)        | LLama           | HF, GGML, GPTQ      | oobabooga         | (:heavy_check_mark:) | [oobabooga/text-generation-webui](https://github.com/oobabooga/text-generation-webui) |
| [llama-cpp-server](https://github.com/localagi/llama-cpp-docker) | LLama           | HF, GGML            | OpenAI            | (WIP) | [abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python) |
| gpt4all | | | | WIP |  |
| gpt4free | | | | WIP |  |
| [stablediffusion2](https://github.com/localagi/stablediffusion2-docker) |        |                     |                   |                     WIP  | |

### AI-pipeline-built services for *using* inference
| Service                                                                |  Release              | Original Repo |
|------------------------------------------------------------------------|-----------------------|---------------|
| [AGiXT](https://github.com/localagi/agent-llm)                         | :heavy_check_mark:  | [josh-XT/AGiXT](https://github.com/josh-xt/AGiXT) |
| [AGiXT-Frontend](https://github.com/localagi/agent-llm-frontend)       | :heavy_check_mark:  | [JamesonRGrieve/Agent-LLM-Frontend](https://github.com/JamesonRGrieve/Agent-LLM-Frontend) |
| [gpt-code-ui](https://github.com/localagi/gpt-code-ui-docker)          | :heavy_check_mark:  | [ricklamers/gpt-code-ui](https://github.com/ricklamers/gpt-code-ui) |


### CLI tools and packages
| Tool                                                                | Model-types  | Model-quantisations | API-compatibility  | Release              | Original Repo |
|---------------------------------------------------------------------|--------------|---------------------|--------------------|----------------------|---------------|
| [llama-cpp](https://github.com/localagi/llama-cpp-docker)           | Llama        | HF, GGML            | N/A                | (:heavy_check_mark:) | [abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python) |
| [llama-gptq](https://github.com/localagi/llama-gptq-docker)          | Llama       |  GPTQ               | N/A                | (:heavy_check_mark:) | [oobabooga/GPTQ-for-Llama](https://github.com/oobabooga/GPTQ-for-LLaMa)  [qwopqwop200/GPTQ-for-Llama](https://github.com/qwopqwop200/GPTQ-for-LLaMa)  |
| [AutoGPTQ](https://github.com/localagi/AutoGPTQ-docker)             | Llama        |  GPTQ               | N/A                | WIP                  | [PanQiWei/AutoGPTQ](https://github.com/PanQiWei/AutoGPTQ) |

## Requests
Any? Contact me (curently on AGiXT-Discord)



<!--
**localagi/localAGI** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
