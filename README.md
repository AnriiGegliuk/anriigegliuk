
Hi there 👋👋👋👋



![](https://komarev.com/ghpvc/?username=andriigegliuk&label=PROFILE+VIEWS)

from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def home():
    user = {
        'name': 'Andrii',
        'lives': 'Tokyo, Japan',
        'job': 'Data Scientist',
        'skills': 'Python, Machine Learning, Data Analysis, Statistical Modelling',
        'languages': 'English, Portuguese, Ukrainian',
        'fun_fact': 'I am an avid reader and can read in multiple languages.',
        'likes': ['📚', '🗣️', '💻', '🔬', '📊', '🥾', '🚲', '✈️']
    }
    return render_template([index.html](https://andriig.pythonanywhere.com/), user=user)

if __name__ == '__main__':
    app.run(debug=True)


<!--

**AndriiGegliuk/andriigegliuk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning Data Analysis 
- 👯 I’m looking to collaborate on projects that creates value and helps everyone to achieve amazing results 
- 🤔 I’m looking for help with Python code and Data analysis tools
- 💬 Ask me about 
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ... 
-->
