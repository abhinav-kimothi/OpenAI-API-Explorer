<img src="./Assets/Images/Readme Header.png">


# OpenAI API Explorer

Welcome to the OpenAI API Explorer repository!

`Note : This is still a WIP repository, Don't forget to star ⭐ and follow this repository for new notebooks every week! `

This repository attempts to become a gateway to mastering the OpenAI APIs for natural language processing and artificial intelligence tasks. This is a work-in-progress bootcamp designed to provide you with the knowledge and skills you need to harness the full potential of the OpenAI models through their APIs.

Through this repository, we will use available OpenAI models to explore -

- Large Language Models like GPT 3.5
- Multimodal Models like GPT 4
- Text Embeddings Models and their application
- Image generation diffusion models like DALL-E
- Text to Speech Models
- Audio to Text Models like Whisper

Through these models, we will attempt to understand concepts of -

- Prompt Engineering
- Supervised Fine Tuning (SFT)
- Retrieval Augmented Generation (RAG)
- AI Agents (OpenAI Assitants API)

... and more



## Prerequisites

Before you begin, make sure you have the following:

- __An OpenAI API key__: To access the OpenAI API, sign up for an API on [www.openai.com](www.openai.com) 

    _You can also refer to the Day 0 Notebook for steps to create an OpenAI account and get an API key. OpenAI charges for the API calls. However, you receive credits from OpenAI for the first time sign up. For the purpose of the code here, the credits will be more than enough._
- __Python__: Ensure that Python >=3.10.0 is installed on your system and that you can create a virtual environment for a safer and cleaner project setup.
- __Jupyter Notebooks__: Install Jupyter Notebooks using Anaconda or pip


## Getting Started

1. Clone this repository to your local machine:

    ```
    git clone https://github.com/your-username/openai-api-bootcamp.git
    ```

2. Navigate to the cloned repository:

    ```
    cd openai-api-bootcamp
    ``` 

3. It's recommended to use a virtual environment to avoid conflicts with other projects or system-wide Python packages.

    Run the following command to create a virtual environment named venv (you can name it anything you like):

    ```
    python3 -m venv ./venv
    ```

    Activate the Virtual Environment:

    - On Windows, activate the virtual environment by running:

        ```
        venv\Scripts\activate.bat
        ```
    - On macOS and Linux, activate it with:
        ```
        source venv/bin/activate
        ```

4. Install required Python packages:


    ```
    pip install -r requirements.txt
    ```

5. Store your OpenAI API key in a .env file in the Notebooks folder:

    ```
    OPENAI_API_KEY=<YOUR API KEY>

    ### You can also look at the Notebooks\example_dot_env file in this repo for the structure. Remeber to rename to .env
    ```



---
## Notebook Contents
__/Notebooks/__

### Day 0 - Getting Started.ipynb 
<code style="color : Darkorange">[Released : 28/APR/2024]</code>


[Go to Notebook](./Notebooks/Day%200%20-%20Getting%20Started.ipynb)

- Installing the OpenAI python library
- Creating an OpenAI account
- Getting an API key
- Setting up OpenAI Client
- Making the first API Call

### Day 1 - Text Generation with Chat Completions API 

<code style="color : Darkorange">[Released : 28/APR/2024]</code>


[Go to Notebook](./Notebooks/Day%201%20-%20Text%20Generation%20with%20Chat%20Completions%20API.ipynb)

- Introduction to LLMs
- Understanding the available OpenAI LLMs
- Looking at the OpenAI Chat Messages (Prompt) Structure
- Studying Chat Completions API Parameters
- Decoding the Chat Completions Response Object
- Learning how to Stream responses
- Looking at JSON Response format
- Understanding Reproducibility
- Learning about managing Tokens

### Day 2 - Basic Prompt Engineering 

<code style="color : Orangered">[To be Released : 05/MAY/2024]</code>

### Day 3 - OpenAI Text Embeddings

<code style="color : Orangered">[To be Released : TBD]</code>

### Day 4 - Retrieval Augmented Generation with OpenAI & LangChain

<code style="color : Orangered">[To be Released : TBD]</code>

### Day 5 - Supervised Fine-Tuning of OpenAI Models

<code style="color : Orangered">To be Released : TBD]</code>

### Day 6 - AI Agents with OpenAI Assistants API

<code style="color : Orangered">[To be Released : TBD]</code>

### Day 7 & Beyond

<code style="color : Red">__[To be Decided]__</code>






## Assets

__Data__ : Data for the notebooks can be found in the [Assets/Data](./Assets/Data/) directory.

__Images__ : All explainer images used in the notebooks are stored in the [Assets/Images](./Assets/Images/) directory.

## Contributing
If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request. Contributions from the community are highly encouraged and appreciated!

I'm also eager to hear back from you to guide this bootcamp. Please email me your suggestions at abhinav.kimothi.ds@gmail.com

## License
This repository is licensed under the MIT [LICENSE](./LICENSE). See the LICENSE file for details.

## Connect with Abhinav

<img src="./Assets/Images/Profile_AK.png" width=100> 

Hi! I'm Abhinav, a data science and AI professional with over 15 years in the industry. Passionate about AI advancements, I constantly explore emerging technologies to push the boundaries and create positive impacts in the world. Let’s build the future, together!

<span style="font-size: 20px; color: orange"><b>Connect with me!</b></span>


[![GitHub followers](https://img.shields.io/badge/Github-000000?style=for-the-badge&logo=github&logoColor=black&color=orange)](https://github.com/abhinav-kimothi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=orange&color=black)](https://www.linkedin.com/comm/mynetwork/discovery-see-all?usecase=PEOPLE_FOLLOWS&followMember=abhinav-kimothi)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=black&color=orange)](https://medium.com/@abhinavkimothi)
[![Insta](https://img.shields.io/badge/Instagram-000000?style=for-the-badge&logo=instagram&logoColor=orange&color=black)](https://www.instagram.com/akaiworks/)
[![Mail](https://img.shields.io/badge/email-000000?style=for-the-badge&logo=gmail&logoColor=black&color=orange)](mailto:abhinav.kimothi.ds@gmail.com)
[![X](https://img.shields.io/badge/Follow-000000?style=for-the-badge&logo=X&logoColor=orange&color=black)](https://twitter.com/abhinav_kimothi)
[![Linktree](https://img.shields.io/badge/Linktree-000000?style=for-the-badge&logo=linktree&logoColor=black&color=orange)](https://linktr.ee/abhinavkimothi)
[![Gumroad](https://img.shields.io/badge/Gumroad-000000?style=for-the-badge&logo=gumroad&logoColor=orange&color=black)](https://abhinavkimothi.gumroad.com/)


<span style="font-size: 20px; color: orange"><b>You can also book a time-slot with me</b></span>


[![Static Badge](https://img.shields.io/badge/Resume%20Review%20(DS/AI/ML)%20(30%20min)-000000?style=for-the-badge&logo=googlecalendar&logoColor=blue&color=black)](https://topmate.io/abhinav_kimothi/544382)
[![Static Badge](https://img.shields.io/badge/AIML%20Learning%20Path%20(30%20min)-000000?style=for-the-badge&logo=googlecalendar&logoColor=black&color=blue)](https://topmate.io/abhinav_kimothi/544380)
[![Static Badge](https://img.shields.io/badge/Generative%20AI%20Consulting%20(60%20min)-000000?style=for-the-badge&logo=googlecalendar&logoColor=blue&color=black)](https://topmate.io/abhinav_kimothi/544379)


<span style="font-size: 20px; color: orange"><b>Also, read my ebooks for more on Generative AI!</b></span>


<a href="https://abhinavkimothi.gumroad.com/l/GenAILLM" target="_blank">
    <img src="https://public-files.gumroad.com/jsdnnne2gnhu61f6hrdprwx2255i" width=150>
</a><a href="https://abhinavkimothi.gumroad.com/l/RAG" target="_blank">
    <img src="https://public-files.gumroad.com/v17k9tp2fnbbtg8iwoxt4m3xgivq" width=150>
</a><a href="https://abhinavkimothi.gumroad.com/l/GenAITaxonomy" target="_blank">
    <img src="https://public-files.gumroad.com/a730ysxb7a928bb5xkz6fuqabaqp" width=150>
</a>








