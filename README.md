# Math Problem Solver

This repository contains a deep learning-based model for solving various types of math problems.

## Overview

The purpose of this project is to develop a robust model capable of solving a wide range of mathematical problems using deep learning techniques. We initially experimented with several open-source models to establish a baseline for performance. Subsequently, we fine-tuned the DeepSeek-Math model with Qlora to enhance its capabilities and accuracy.

## Features

- Solves diverse types of math problems.
- Utilizes state-of-the-art deep learning techniques.
- Easy integration into existing systems or applications.

## Usage

To use the fine-tuned DeepSeek-Math model with Qlora, download the Lora adapters from [Kaggle](https://www.kaggle.com/models/jatinsinghsagoi/deepseek-math-qlora) and follow the instructions provided in the model card for integration.

## Models Used

- **Open-Source Models**: We experimented with various open-source models available in the literature.
- **Fine-Tuned Model**: The DeepSeek-Math model was fine-tuned with Qlora to improve its accuracy and performance. For a detailed fine-tuning report, refer to [W&B report](https://api.wandb.ai/links/jatinsingh/d4e9kl91).

## Fine-Tuning Report

![Fine-Tuning Report 1](https://i.imgur.com/JNkwAJv.png)

![Fine-Tuning Report 2](https://i.imgur.com/HQs58j8.png)

## Data

Data used for training and fine-tuning the models are not included in this repository due to licensing restrictions. Instructions for obtaining the data can be found [here](https://www.kaggle.com/datasets/alejopaullier/aimo-external-dataset).

## Acknowledgements

- We thank the developers of the open-source models used in this project for their contributions.
- Special thanks to the team behind Qlora for providing a powerful platform for fine-tuning deep learning models.

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Please feel free to open issues or pull requests.

