## 🧮 localAGI 🧮
Fulltime nerd. Passionate developer. DevOp at heart.

Thats me. :bowtie: Building AGI on local hardware.

*You want to **run your own inferences** with ease? Good you are awake.*


Building contaners for effectively running a local artificial general intelligence. :mechanical_arm:

## :climbing_woman: Motivation :climbing:

Initially started my work for deployments of [josh-XT/AGiXT](https://github.com/Josh-XT/AGiXT)

Having reproducable software environments to spin up services on demand for testing and sky-netting.
Setup and streamline docker containers for quick and user friendly usage.

:rocket: CUDA enabled. :desktop_computer: BLAS enabled. :smirk: Conda-less. :onion: Matrix builds. :office: Multiarch builds. :child: :adult: :older_adult: For everyone.



## :hibiscus: Sharing is caring :hibiscus:

With strong expertise in `docker` and `github workflows` I want to test all the AI-related projects online using docker containers.

**Working on [AI-dedicated Workflows](https://github.com/localagi/ai-dedicated-workflows)** to share best practices over several repositories and projects.

### :star2: When you like any of my work, leave a star! Thank you! :star2:

## State of work

The following projects are built using the **[AI pipeline](https://github.com/localagi/ai-dedicated-workflows)**.

My maintenance is focussed on build stabilty and availability of service containers. >200h of work. 50.000h of experience.

* **Build Passing == Working**
* (:heavy_check_mark:) == Working soonish
* (WIP) == some unstable state

### AI-pipeline-built services for *running* inference
| Service                                                          | Release            | Model-types     | Model-quantisations | API-compatibility | Original Repo |
-------------------------------------------------------------------|--------------------|-----------------|---------------------|-------------------|---------------|
| [FastChat](https://github.com/localagi/FastChat-docker)          | ![](https://github.com/localagi/FastChat-docker/actions/workflows/publish-docker.yml/badge.svg?branch=main) | e.g. Vicuna, T5 | T5, HF              | OpenAI            | [lm-sys/FastChat](https://github.com/lm-sys/FastChat) |
| [oobabooga](https://github.com/localagi/oobabooga-docker)        | ![](https://github.com/localagi/oobabooga-docker/actions/workflows/publish-docker.yml/badge.svg?branch=main) | LLama           | HF, GGML, GPTQ      | oobabooga         | [oobabooga/text-generation-webui](https://github.com/oobabooga/text-generation-webui) |
| [llama-cpp-server](https://github.com/localagi/llama-cpp-docker) |(:heavy_check_mark:)| LLama           | HF, GGML            | OpenAI            | [abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python) |
| [gpt4all](https://github.com/localagi/gpt4all-docker)            | ![](https://github.com/localagi/gpt4all-docker/actions/workflows/publish-docker.yml/badge.svg?branch=main) | GPTJ, LLAMA, MTP (see [backend](https://github.com/nomic-ai/gpt4all/tree/main/gpt4all-backend)) | ?                 | ? | [nomic-ai/gpt4all](https://github.com/nomic-ai/gpt4all) |
| [gpt4all-ui](https://github.com/localagi/gpt4all-ui-docker)            | ![](https://github.com/localagi/gpt4all-ui-docker/actions/workflows/publish-docker.yml/badge.svg?branch=main) | GPTJ, LLAMA, MTP (??) | GGML...?          | ? | [nomic-ai/gpt4all-ui](https://github.com/nomic-ai/gpt4all-ui) |
| [gpt4free](https://github.com/localagi/gpt4free-docker)  | ![](https://github.com/localagi/gpt4free-docker/actions/workflows/publish-docker.yml/badge.svg?branch=main) | | | | [xtekky/gpt4free](https://github.com/xtekky/gpt4free)  |
| [stablediffusion2](https://github.com/localagi/stablediffusion2-docker) |         WIP  |        |                     |                   | |

### AI-pipeline-built services for *using* inference
| Service                                                                |  Release              | Original Repo |
|------------------------------------------------------------------------|-----------------------|---------------|
| [AGiXT](https://github.com/localagi/AGiXT-docker)                      | ![](https://github.com/localagi/AGiXT-docker/actions/workflows/publish-docker.yml/badge.svg?branch=main)  | [josh-XT/AGiXT](https://github.com/josh-xt/AGiXT)  | 
| [AGiXT-Frontend](https://github.com/localagi/agent-llm-frontend)       | :heavy_check_mark: | [JamesonRGrieve/Agent-LLM-Frontend](https://github.com/JamesonRGrieve/Agent-LLM-Frontend) |
| [gpt-code-ui](https://github.com/localagi/gpt-code-ui-docker)          | ![](https://github.com/localagi/gpt-code-ui-docker/actions/workflows/publish-docker.yml/badge.svg?branch=main)  | [ricklamers/gpt-code-ui](https://github.com/ricklamers/gpt-code-ui) |


### CLI tools and packages
| Tool                                                                | Release              | Model-types  | Model-quantisations | API-compatibility  | Original Repo |
|---------------------------------------------------------------------|----------------------|--------------|---------------------|--------------------|---------------|
| [llama-cpp](https://github.com/localagi/llama-cpp-docker)           | (:heavy_check_mark:) | Llama        | HF, GGML            | N/A                | [abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python) |
| [llama-gptq](https://github.com/localagi/llama-gptq-docker)         | (:heavy_check_mark:) | Llama        |  GPTQ               | N/A                | [oobabooga/GPTQ-for-Llama](https://github.com/oobabooga/GPTQ-for-LLaMa)  [qwopqwop200/GPTQ-for-Llama](https://github.com/qwopqwop200/GPTQ-for-LLaMa)  |
| [AutoGPTQ](https://github.com/localagi/AutoGPTQ-docker)             | WIP                  | Llama        |  GPTQ               | N/A                | [PanQiWei/AutoGPTQ](https://github.com/PanQiWei/AutoGPTQ) |

## Requests
Any? Contact me (curently on AGiXT-Discord)


## Things to consider
- `conda` is commercial. The license prohibits any commercial use. We try to omit it on our builds, but it's your responsibility.
- NVidia images have a license. Make sure you read them.
- streamlit app collects heavy analytics even when running locally. This includes events for every page load, form submission including metadata on queries (like length), browser and client information including host ips. These are all transmitted to a 3rd party analytics group, Segment.com.

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
