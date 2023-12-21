# CodeGen Magic: Transforming Text into Python Code

Welcome to the fascinating world of CodeGen, where the art of turning human language into Python code is elevated to new heights! This repository is your gateway to a revolutionary text-to-code generation project, unleashing the power of large language models (LLMs) in the programming realm.

## 🌟 Introduction

Have you ever wished for a code wizard that could understand your intentions in plain English and effortlessly translate them into Python? Well, the wait is over! Our text-to-code generation model is designed with an encoder-decoder architecture, boasting attention mechanisms that give it an uncanny understanding of both human language and Python syntax.

In this repository, we dive deep into the magic behind CodeGen, exploring how we fine-tune pre-trained LLMs, such as StarChat-alpha, CodeParrot, and Codegen-350M-mono, to achieve unparalleled accuracy in generating Python code.

## 🚀 Model Architecture

Meet the heroes of our story: CodeGen, CodeParrot, and StarCoderBase-1B. Each model brings its own unique flair to the table, from transformer-based autoregressive language modeling to GPT-2 dedicated Python code generation. The finetuning process involves a symphony of in-context learning and parameter-efficient finetuning, unleashing the true potential of these models.

## 📚 Dataset Wonderland

Our models are trained on the PyLoomer dataset, a treasure trove of text-to-Python code translations from diverse sources. Cleaning and preprocessing, done with meticulous care, ensure that only the highest-quality data fuels the magic behind CodeGen. The journey takes us from custom datasets to Hugging Face's powerful library, simplifying the loading and processing of large datasets.

![](https://github.com/anujsahani01/PyLoomer/assets/83875986/a9deb286-1aa5-418f-92b7-aa08fd9e864d)


## 🌈 In-Context Learning and Results

Peek behind the curtain as we perform in-context learning on both pre-trained and finetuned models. The results are showcased in detailed tables, comparing original and finetuned models using ROUGE scores and loss curves that tell the story of model refinement.

### Original vs. Finetuned Models ROUGE Scores

**CodeGen:**

| Metric | Original Model | Finetuned Model |
| ------ | -------------- | --------------- |
| Rouge1  | 0.1605         | 0.1880          |
| Rouge2  | 0.0369         | 0.0537          |
| RougeL  | 0.1109         | 0.1255          |
| RougeLsum | 0.1524       | 0.1808          |

**StarCoder:**

| Metric | Original Model | Finetuned Model |
| ------ | -------------- | --------------- |
| Rouge1  | 0.1220         | 0.1511          |
| Rouge2  | 0.0258         | 0.0394          |
| RougeL  | 0.0910         | 0.1073          |
| RougeLsum | 0.1201       | 0.1470          |

**CodeParrot:**

| Metric | Original Model | Finetuned Model |
| ------ | -------------- | --------------- |
| Rouge1  | 0.1520         | 0.1778          |
| Rouge2  | 0.0320         | 0.0441          |
| RougeL  | 0.1048         | 0.1261          |
| RougeLsum | 0.1629       | 0.1428          |

### Model Loss Curves

![CodeGen Loss Curve ](https://github.com/anujsahani01/PyLoomer/assets/83875986/41c71d69-31ca-47b3-bff3-e94486784b1c)

![StarCoder Loss Curve](https://github.com/anujsahani01/PyLoomer/assets/83875986/76a5d546-6fa7-4ad5-9dc1-7b99b0ae71ba)

![CodeParrot Loss Curve](https://github.com/anujsahani01/PyLoomer/assets/83875986/84bbfecd-e018-4281-a77a-fdbdf7954cb2)

## 🎉 Conclusion

Spoiler alert: our models outshine their original selves! Whether you're a seasoned developer or a coding novice, these models promise accurate code generation, opening up exciting possibilities for everyone.

## 🌟 Feedback

If you have any feedback, please reach out to me at: [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/anuj-sahani-34363725b) 

Author: [@anujsahani01](https://github.com/anujsahani01)
