# 🤖 Vityarthi Chatbot Project (AI & ML)

## 📌 Overview
This project is a **simple rule-based chatbot built using Python**.  
It can interact with users by responding to basic messages like greetings, questions, and commands.

---

## 🎯 Aim
To create a chatbot that:
- Takes user input
- Processes it using basic logic
- Responds with predefined answers

---

## 🚀 Why This Project Matters
Chatbots are widely used in:
- Websites
- Mobile applications
- Customer service systems

### This project helps in:
- Understanding human-computer interaction
- Building a base for advanced AI systems
- Improving programming and logical thinking
- Learning real-world applications of Python

---

## ⚙️ How It Works
- User input is taken using `input()`
- Converted to lowercase using `.lower()`
- Keywords are matched using `if-elif-else`
- Responses are generated accordingly
- Runs continuously using a loop until user exits

---

## 💻 Code

```python
# Simple Chatbot

print("Chatbot: Hi! Type 'bye' to exit.")

while True:
    user = input("You: ").lower()

    if user == "bye":
        print("Chatbot: Goodbye!")
        break

    elif "hello" in user or "hi" in user:
        print("Chatbot: Hello there!")

    elif "how are you" in user:
        print("Chatbot: I'm just code, but I'm doing great!")

    elif "your name" in user:
        print("Chatbot: I'm a simple Python chatbot.")

    elif "help" in user:
        print("Chatbot: You can say hello, ask my name, or say bye.")

    else:
        print("Chatbot: Sorry, I don't understand that.")
```

---

## 🧠 Key Decisions
- Used keyword matching instead of exact sentences
- Applied `.lower()` to handle case sensitivity
- Used infinite loop (`while True`) for continuous interaction
- Added default response for unknown inputs

---

## ⚠️ Challenges Faced
- Handling variations in user input
- Avoiding program crashes on unexpected input
- Keeping responses simple yet meaningful
- Managing multiple conditions cleanly

---

## 📚 What I Learned
- Basics of chatbot development
- Python loops and conditional statements
- User input handling
- Limitations of rule-based systems
- Importance of planning before coding

---

## 🏁 Conclusion
This project demonstrates how a simple chatbot can simulate interaction with users.  
It serves as a foundation for building more advanced AI-powered systems.

---

## 🙏 Acknowledgment
Project by **Rabnoor Kaur Bhatia**  
Faculty: **Ashfaq Ahmad Najar**  
Date: 30 March 2026

---

⭐ *Thank you for checking out this project!*
