# Random number between 1 and 10
secret_number = random.randint(1, 10) #by NOUR
print("🔥 Welcome to Guess the Number 🔥") by Sadim
print("Guess correctly and WIN a shawarma 🌯!") #by NOUR
guess = int(input("Enter your guess (1-10): ")) by Sadim
if guess == secret_number:
    print("🎉 Correct! You win a shawarma 🌯!") #by NOUR
else:
    print("❌ Wrong! No shawarma today 😢")
    print("The correct number was:", secret_number) by Sadim
