## Documentation

#### Number Class

```py
import xxt

ten = xxt.Number(10) #Make the object

print(ten) # Print the traits
print(ten.prime) # Print whether it is a prime or not
print(ten.evenodd) # Print whether it is even or odd
print(ten.numtype) # Print whether it is a float or an integer
print(ten.square) # Print whether it is a square or not
print(ten.cube) # Print whether it is a cube or not
print(ten.palindrome) # Print whether it is a palindrome or not
print(ten.strobogrammatic) # Print whether it is strobogrammatic (when turned upside down is the same)
print(ten.strobogrammaticdifferent) # Print whether it is strobogrammatic different (when turned upside down is a different number)
```

#### Chatbot Class
```py
import xxt

bot = xxt.Chatbot("Bot", "You are a friendly bot.", "Replace with OpenAI API key") # Make the object
message = input("Message: ") # Get the message
print(bot.chat(message)) # Chat with the bot and print the response
bot.clear() # Clear the chat history
```

#### Imagebot Class
```py
import xxt

bot = xxt.Imagebot("Replace with OpenAI API key") # Make the object
print(bot.generate("A blue cat", 512, 512)) # Generate a link for the image
```

#### Random Class

```py
import xxt

ran = xxt.Random()
list = ["Hello", "World", "How", "Are", "You"]

print(ran.integer(1, 10)) # Print a random integer between 1 and 10
print(ran.float(1, 10)) # Print a random float between 1, 10
print(ran.choice(list)) # Print a random choice from 'list'
```

#### QR Code
```py
import xxt

xxt.qr("Hello World", "file.png") # Generate a QR code for "Hello World" to "file.png"
```

#### Other Functions

```py
import xxt

print(f"{xxt.gettime()} on {xxt.getdate()}") # Prints (time) on (date)
xxt.wait(1) #Waits one second
xxt.clear() # Clears console
```