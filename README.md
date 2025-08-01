# chat-bot
it is a simple chatbot made using python
print("chatbot:welcome!type 'bye'to end the chat.\n")
for conversation_count in range(10):
  user_message("you:").lower()
  if user_message=="hi" or user_message=="hello":
    print("chatbot:hello! nice to meet you.")
  elif user_message=="how are you":
    print("chatbot:iam doing well,thank you.")
  elif user_message=="what is your name":
    print("chatbot:my name is chatbot.")
  elif user_message=="bye":
    print("chatbot:good bye!")
    break
  else:
    print("chatbot:I don't understand the message.")
  print("\n chatbot:chat ended.")
