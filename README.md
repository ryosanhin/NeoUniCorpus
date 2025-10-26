# NeoUniCorpus
**Search contexts about NeoUniverse(umamusume) containing the specified keyword in the umamusume app**  
I'm a Japanese. English is not my first language so there may be some mistakes. Suggestions or corrections are always welcome. Thank you for your understanding!
## How to use (Google Colab)
1. just run 1st and 2nd cells
2. edit searching option in 3rd cell
   ```python
   # input word here you are looking for
   WORD_LOOKING_FOR = "example word"
   # set accompanying context length
   CONTEXT_LENGTH = 100
   ```
   `WORD_LOOKING_FOR` is expected the word you are looking for.  
   `CONTEXT_LENGTH` is expected additional context length. For example in this case, you can get both of before and after context with 100 characters.
3. run 3rd cell and get output table
