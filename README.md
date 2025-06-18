# My Hugging Face Contributions Tracker

This repository serves as a personal log and tracker for my contributions to the Hugging Face ecosystem, primarily through Pull Requests (PRs), issue discussions, and other community engagements across various Hugging Face repositories.

---

### Pull Requests (PRs)

These are my code contributions that have been submitted to various Hugging Face repositories.

* **[Added support for groups in conv layers for LoRA](https://github.com/huggingface/peft/pull/2567)** - **peft**
    * **Description:** Issue [#2549](https://github.com/huggingface/peft/issues/2549) is about error in initializing the model with peft approach of dora and lora and errors in the forward pass for conv layers with `groups>1`. This fix is an approach to resolve the errors by including `groups` as part of the definition of `lora_B` parameter.
    * **Status:** Merged ✅

---

### Issue Discussions & Bug Reports

* **[Issue in accessing Samsum dataset](https://github.com/huggingface/datasets/issues/7573)** - **dataset**
    * **Description:** Resolved a Hugging Face datasets issue where the `Samsung/samsum` dataset was unavailable on the Hub, causing download failures. 
    * **Status:** Closed ✅
* **[Error while using streaming datasets](https://github.com/huggingface/datasets/issues/7566)** - **dataset**
    * **Description:** Analyzing source of failure and possible mitigation. 
    * **Status:** In-progress 🛠️

* **[Query in related to __builtins__](https://github.com/huggingface/datasets/issues/7636)** - **dataset**
    * **Description:** Under different circumstances, `__builtins__` attribute is either a dictionary or a module causing errors if considered to be of the wrong format in the given situation.
    * **Status:** Closed ✅
