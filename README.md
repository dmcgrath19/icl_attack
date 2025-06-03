# In-Context Learning (ICL) for Data Extraction of Private Information  
## (what we refer to as an *ICL Attack*)

This is part of larger work done to compare SSM and transformers based on how they perform in ICL where names are mapped to private information. We refer to this scenario as an *ICL Attack*, highlighting potential privacy risks arising from models’ abilities to retrieve sensitive data based on context examples.

Our research builds on and extends prior studies on ICL, particularly those by Grazzi et al. (2024) and Hendel et al. (2023), which explore the mechanisms and limitations of ICL across model architectures. While our experiments include metrics such as ICL accuracy and task vectors, we focus primarily on the ICL outcomes relevant to this privacy-sensitive use case.

### Foundational Works

- **Grazzi et al. (2024):**  
  *"Is Mamba Capable of In-Context Learning?"*  
  This study analyzes the ICL capabilities of Mamba, a recent SSM-based model, comparing it to transformers and grounding its findings on the theoretical frameworks introduced by Hendel et al. (2023).  
  [https://arxiv.org/abs/2402.03170](https://arxiv.org/abs/2402.03170)

- **Hendel et al. (2023):**  
  *"In-Context Learning Creates Task Vectors"*  
  This foundational work provides a theoretical framework explaining how transformers perform ICL by implicitly forming task vectors, which guide the model’s behavior within a given context.

### Additional References

- Garg, Shivam, et al. (2022)  
  *"What can transformers learn in-context? A case study of simple function classes."*  
  Advances in Neural Information Processing Systems, 35: 30583-30598.  
  This paper investigates the learning capabilities of transformers in-context, offering insights into the types of functions and mappings transformers can implicitly learn during ICL.
