print("=== CodeAlpha FAQ Chatbot ===")
print("By Mahrukh Baloch - BSIT MNSUAM\n")

# FAQ Database - You can add more questions here
faqs = {
    "hello": "Hello! How can I help you? 😊",
    "hi": "Hi there! Ask me anything about CodeAlpha.",
    "what is codealpha": "CodeAlpha is a platform offering free internships to build your skills.",
    "internship duration": "CodeAlpha internship is 1 month - 4 weeks, fully remote.",
    "is it free": "Yes! CodeAlpha internship is 100% free, no charges.",
    "certificate": "Yes, you get a certificate after completing tasks and LinkedIn post.",
    "tasks": "You need to complete minimum 2 tasks from your domain. I did Language Translator and this Chatbot.",
    "return policy": "This is a demo FAQ bot. In real e-commerce, return is within 7 days.",
    "contact": "Contact CodeAlpha at codealpha.tech or via LinkedIn.",
    "bye": "Allah Hafiz! Thanks for chatting. Good luck!"
}

print("Bot: Hello! Type your question or type 'bye' to exit.\n")
print("Try: hello, what is codealpha, internship duration, certificate, tasks, bye\n")

while True:
    user = input("You: ").lower().strip()
    
    if not user:
        continue
        
    if user == "bye" or user == "exit" or user == "quit":
        print(f"Bot: {faqs['bye']}")
        break
    
    # Check if question matches any FAQ keyword
    answered = False
    for key in faqs:
        if key in user:
            print(f"Bot: {faqs[key]}\n")
            answered = True
            break
    
    if not answered:
        print("Bot: Sorry, I don't know that. Try asking about: codealpha, internship duration, certificate, tasks, is it free\n")
