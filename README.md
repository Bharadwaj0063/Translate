# Write a program that receives a set of English text and displays its translated text in Persian for us 


# =>Importing Libraries :
   Translator: This class is imported from the translate library. It is used to perform text translation from one language to another.
   Fore and init: These are imported from the colorama library. Fore is used to apply colored text in the terminal, while init (not used here) initializes the color settings for cross-platform compatibility.
   Subprocess: This library allows you to spawn new processes, connect to their input/output/error pipes, and retrieve their return codes. Here, it’s used to execute a shell command.
   Fore.YELLOW and Fore.WHITE: These change the text color to yellow and white respectively for a more visually appealing prompt.
   
# => User Input :
  input: This function collects user input (a string of text) that the program will translate.
  Fore.YELLOW and Fore.WHITE: These change the text color to yellow and white respectively for a more visually appealing prompt.
  
# =>Translation Setup :
  *Translator(from_lang='en', to_lang='persian'):*
  Sets up the translation options to translate text from English (en) to Persian (persian).
  options.translate(user):
  Translates the text entered by the user and stores the translated string in the translate variable.
  
# => How it work:
The program welcomes the user.
The user enters a text string to be translated.
The text is translated from English to Persian using the Translator class.
The translated text is displayed in the terminal.
The translated text is saved to a file (translate.txt) using a shell command.
