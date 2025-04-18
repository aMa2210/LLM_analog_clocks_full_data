# LLM_analog_clocks

This repository contains data and scripts for analyzing the ability of Multimodal Large Language Models (MLLMs) to read analog clocks.

Repository Contents
- Datasets: Contains the full datasets, including images of analog clocks representing every second over a 12-hour period for 6 different types of clocks.
- Test_data: Contains the data used for performing the experiments.
- Train_data: Contains the data used for fine-tuning gpt-4o-2024-08-06.
- Results: Contains the results from various models, including gpt-4.1, chatgpt-4o-latest, gpt-4o-2024-08-06 and its fine-tuned version.
- Figures: Contains visualizations of the results. The numbers after 'MAE' in figure names correspond to the Mean Absolute Error for the respective data.

The promot used in the experiment is _What time is shown on the clock in the given image?_
