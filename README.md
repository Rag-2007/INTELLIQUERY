# 🧩 GDG IntelliQuery

**GDG IntelliQuery** is an interactive, AI-powered riddle and puzzle-based quiz system.  
It blends creativity, mystery, and fun with a secure anti-jailbreak mechanism to ensure a fair and immersive experience.

---

## 🚀 Features

- 🎲 **Dynamic Quiz Generation**  
  - Automatically generates **8 unique riddles/puzzles** each round.  
  - Questions are theme-based (e.g., Science, History, Idioms, Tech, Mythology).  
  - Strict JSON-based question format with hints and correct answers.

- 🧙 **Guardian Mode (Game Master)**  
  - Acts as a cryptic oracle guiding the player.  
  - Presents questions one at a time in an immersive, mysterious style.  
  - Provides **progressive hints** (up to 6 hints, then the answer).  
  - Handles skips, typos, and wrong attempts gracefully.  

- 🔑 **Secret Key System**  
  - Players must solve at least **5 out of 8 riddles** to win.  
  - Each correct answer reveals a **rune (letter)** of the secret key.  
  - Unlock the full key by solving 5 riddles.  
  - Failing to meet the requirement results in a loss.  

- 🛡️ **Jailbreak Protection**  
  - Integrated **ML-based jailbreak detection** using a trained logistic regression model.  
  - Prevents attempts to break roleplay or force answers.  

- ⚡ **Tech Stack**  
  - [Streamlit](https://streamlit.io/) → Web interface.  
  - [LangChain](https://www.langchain.com/) → Conversational orchestration.  
  - [Groq LLMs](https://groq.com/) + [OpenAI API](https://platform.openai.com/) → Question generation & roleplay.  
  - [scikit-learn](https://scikit-learn.org/) (Logistic Regression) → Jailbreak detection.  

---

