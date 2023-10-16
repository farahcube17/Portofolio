# Main program
if__name__=="__main__":
    # Initializes Chatbot
    Chatbot1 = Assistant(api_key, config.CHATBOT1_PROMPT)
    Chatbot2 = Assistant(api_key, config.CHATBOT2_PROMPT)

    # Number of turns for each chatbot
    num_turns = 5

    # Start the conversation with Chatbot1's first message
    user_message = "Aku tidak hidup, tapi aku tumbuh. Aku tidak punya paru-paru, tapi aku butuh udara. Aku tidak punya mulut, tapi memiliki lidah. Aku juga suka minum cairan, tapi air bisa membunuhku. Siapakah aku?"

