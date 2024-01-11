 # Text Summarizer Using Transformers and LLM Model

This project contains code for a text summarizer built using Transformers and the Large Language Model (LLM) model. The goal of this summarizer is to reduce the length of a given text while maintaining its original meaning and context.

shubham5027/Text_Summarizer
![Screenshot 2024-01-11 150531](https://github.com/shubham5027/Text-Summarizer-using-Transformers/assets/132193443/a13292d4-897e-4f8a-a466-76194a269f02)
![Screenshot 2024-01-11 151039](https://github.com/shubham5027/Text-Summarizer-using-Transformers/assets/132193443/9b655ff7-d11e-4821-b94a-b4f294df4651)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.8 
- Transformers library from Hugging Face (version 4.17.0 or higher)


### Installing

1. Clone this repository onto your local machine:

   ```
   git clone https://github.com/shubham5027/Text-Summarizer-using-Transformers


2. Install the required dependencies by running:

   ```
   pip install -r requirements.txt
   ```


## Customizing the Summarizer

You can adjust various aspects of the model, including hyperparameters, by modifying the `config.py` file. Here are a few key options you may want to alter:

- `MAX_SOURCE_LENGTH`: The maximum length of the input text used for training and summary generation.
- `MAX_TARGET_LENGTH`: The maximum length of the summary used for training and summary generation.

## Built With

- [Transformers](https://huggingface.co/transformers/) - The Transformers library from Hugging Face.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Acknowledge the inspiration, direct or indirect, for this project. Feel free to include links to useful resources and libraries used.
- Here is an example of the acknowledgements you can include: "[Transformers](https://huggingface.co/transformers/)" and "[Hugging Face](https://huggingface.co/)" for providing the foundational library and models used in this project.  
