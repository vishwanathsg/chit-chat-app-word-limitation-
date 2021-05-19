# chit-chat-app-word-limitation-
This code has word limit like in a chit-chat application

def word_list(word_input):
    x= word_input.split()
    y=x[0:30]
    z=y


    if len(x) > 30:
        print()
        print("Result =", z)

    else:
        print()
        print("Result =", word_input) #If characters < 30, then directly print the input string

    return(x)

word_input=str(input("Enter the text you want to send: "))
word_list(word_input)
