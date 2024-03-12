from colorama import Fore
def encrypted(user_input, shift_key):
    encrypted_mes = ""
    for char in user_input:
        encrypted_mes += chr(ord(char) + shift_key)
    print(f"Encrypted message: {Fore.BLUE}{encrypted_mes}")

def decrypted(user_input, shift_key):
    decrypted_mes = ""
    for char in user_input:
        decrypted_mes += chr(ord(char) - shift_key)
    print(f"Decrypted message: {Fore.LIGHTBLUE_EX}{decrypted_mes}")
def main():
    print("ENCRYPTION AND DECRYPTION USING CAESAR CIPHER ALGORITHM ")
    print("SELECT THE OPTIONS:")
    print("1     Encryption")
    print("2     Decryption")
    choice = int(input("Enter your choice : "))

    if choice == 1:
            user_input = input("Enter your message: ")
            shift_key = int(input("Enter the shift number (0-45): "))
            encrypted(user_input, shift_key)
    elif choice==2:
           user_input = input("Enter your message: ")
           shift_key = int(input("Enter the shift number (0-45):"))
           decrypted(user_input,shift_key)
    else :
      print("enter the correct choice")

if __name__ == "__main__":
    main()
