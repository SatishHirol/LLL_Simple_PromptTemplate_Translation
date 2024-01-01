Install Langchain

Install HuggingFaceHub

Get Any Model Key From HuggingFace 

Import OS

Create Environment of That Key

Create Object of Any LLm Model by passing Model name, Model_kwargs -> Temp_value, Max_Length

import PromptTemplate module from langchain.prompts

Create Your Prompt By Using Both Parameter 
      Input_Variables= ['sentence', 'give language in which you want to translate'],
      template= " Here You can Give Any Instruction to Model For Behaviour."
                " Listen, You are Translator, and you need to translate {sentences} in : second variable (A language in which you want to translate)"

pass senteces to prompt for translation
      translator=model(prompt.format(sentences="________________"))

Get the answer
