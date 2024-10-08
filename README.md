
<div align="center">

![image](https://github.com/user-attachments/assets/55a38e74-ab93-4d80-91c8-0fa6130af45a)

<h1>Out of Focus v1.0</h1>

<a href="https://www.buymeacoffee.com/outofai" target="_blank"><img src="https://img.shields.io/badge/-buy_me_a%C2%A0coffee-red?logo=buy-me-a-coffee" alt="Buy Me A Coffee"></a>
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Ashleigh%20Watson)](https://twitter.com/OutofAi) 
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Alex%20Nasa)](https://twitter.com/banterless_ai)
[![xl](https://img.shields.io/badge/🤗-HuggingFaceDemo-orange)](https://huggingface.co/spaces/fffiloni/OutofFocus)

</div>


Out of AI presents a flexible tool in Gradio to manipulate your images. This is our first version of Image modification tool through prompt manipulation by reconstruction through diffusion inversion process.
We recommend running it on GPU with at least 15GB VRAM and preferably a A100 GPU for the best experience.


https://github.com/user-attachments/assets/de8a4f9d-cdad-4b73-962e-2cc42bbc2e0d



## Download the project

```bash
git clone https://github.com/OutofAi/OutofFocus.git
cd  OutofFocus
```

# 🚀 Run Gradio Demo locally
After downloading the project and navigating to the correct folder

**Install dependencies:**
```bash
pip install -r requirements.txt
```
**Run the app**
```bash
python app.py
```
If you running on a GPU with less than 15GB VRAM, you could try the --enable_low_memory argument when starting the app, the test we ran we managed to run it with 11GB VRAM when enable_low_memory was turned on


# 🚀 Run Gradio Demo locally in Virtual Environment
If you face any dependency, token or cuda issues we higly recommend running it in a virtual environment.

To run it in a virtual environment use these commands instead, after downloading the project and navigating to the correct folder

**Create a virtual environment:**
```bash
python -m venv venv
```

**Activate the environment:**

*Windows:*
```bash
.\venv\Scripts\activate
```
*macOS/Linux:*
```bash
source venv/bin/activate
```
**Install dependencies:**
```bash
pip install -r requirements.txt
```
**Run the app in virtual environment:**
```bash
python app.py
```

# 🚀 Run Gradio Demo on Google Colab (GPU based)

If you want to run it on [Colab](https://colab.research.google.com/drive/11cfx7h6qQWEvBFXO3U_aO8oRukLBOnZs?usp=sharing) make sure you got a GPU notebook enabled (Views->Notebook Info) a A100 GPU or a L4 GPU and run the following commands

```bash
!git clone https://github.com/OutofAi/OutofFocus
%cd OutofFocus
!pip install -r requirements.txt
!python app.py --share
```


https://github.com/user-attachments/assets/1f71553d-d41d-45d6-a256-df3e06f93182


# More Examples:
![image](https://github.com/user-attachments/assets/d9f7aac4-abd6-448f-9c1a-c046958086a9)
![image](https://github.com/user-attachments/assets/a19e1a43-de42-4244-ba39-5fcdbff509d4)
![image](https://github.com/user-attachments/assets/6b80e011-3959-4b3e-a686-365bdb32ae94)
![image](https://github.com/user-attachments/assets/62a324b5-a792-438a-97c5-0e40953a84ed)



