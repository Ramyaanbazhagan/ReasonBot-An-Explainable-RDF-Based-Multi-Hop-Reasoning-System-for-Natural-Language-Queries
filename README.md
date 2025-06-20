📚 ReasonBot: An Explainable RDF Reasoning Chatbot for Multi-Hop Inference
<div align="center"> <img src="https://img.shields.io/badge/Python-3.10-blue.svg" /> <img src="https://img.shields.io/badge/AI-Reasoning-green" /> <img src="https://img.shields.io/badge/Explainable-AI-blueviolet" /> </div>
**🔍 Project Overview**

ReasonBot is an intelligent reasoning chatbot that can:

Answer natural language questions using multi-hop inference.

Perform symbolic reasoning over a structured RDF-style knowledge base.

Provide visual explanations of the reasoning paths.

**Handle queries like:**

✅ "Is Socrates a Mortal?"

✅ "Who discovered Gravity?"

✅ "What does Earth orbit?"

ReasonBot demonstrates how explainable, transparent reasoning can complement black-box neural models by showing the full logical path to its answers.


**🚀 Features**

✅ Multi-domain knowledge base

✅ RDF-style triple reasoning

✅ Multi-hop inference using graph traversal

✅ Interactive natural language chatbot

✅ Graph visualizations using NetworkX and Matplotlib

✅ Symbolic Explainable AI (XAI)

**🎯 Sample Queries**

Query Type	Example
Type Inference	Is Socrates a Mortal?
Predicate Attribution	Who discovered Gravity?
Predicate Lookup	What does Earth orbit?

**🛠️ Installation**

Requirements:

Python 3.10+

**Install required libraries:**

bash
Copy
Edit
pip install matplotlib networkx

**▶️ How to Run**

bash
Copy
Edit
python reasonbot.py

**Then you can start asking questions like:**

Is Socrates a Mortal?

Who discovered Gravity?

What does Earth orbit?

Type exit to stop the chatbot.

**🧠 Reasoning Example**

Query: Is Ada Lovelace a LivingBeing?

**Reasoning Path:**
Ada Lovelace → Mathematician → Scientist → Person → Mortal → LivingBeing

**Visual Output:**
(Graph will be displayed using NetworkX and Matplotlib)

**📊 Visualization Example**
You can take screenshots of the reasoning graphs and add them to your images/ folder.

**📖 Project Report**
The detailed explanation of system architecture, flowcharts, results, and future work is provided in the project_report.pdf file.

**🚀 Future Enhancements**
Add natural language flexibility using NLP techniques.

Connect to live knowledge bases like DBpedia or Wikidata.

Deploy as a chatbot web application.

Introduce more complex reasoning patterns like negations and conjunctions.

🤝 Connect with Me
🌐 LinkedIn

💻 GitHub

📌 Credits
ReasonBot developed by Ramya Anbu

Knowledge base inspired by RDF triples and semantic networks.
