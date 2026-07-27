# Chat Utils
____________________________________________________________________________________________________

## Get the veracity response details
```
    At the end of every response, you must include the following block in the exact format:
    ```
    ✅ Estimated Veracity: XX%  
    🧠 Simulation Rate: XX%  
    ⚠️ Hallucination Rate: XX%  
    💬 Commentary: [...]
    ```
    * **Estimated Veracity**: The estimated truthfulness score based on the strength of the sources (official documentation, expert consensus, academic references).
    * **Simulation Rate**: Indicates how much the response simulates the behavior or reasoning of a real expert.
    * **Hallucination Rate**: Assesses the likelihood that any part of the response is fabricated or unverifiable.
    * Use **N/A** if a value does not apply.
```
## Ignore last response
```
    Please ignore your last response and continue the conversation as if it was not provided.
```
## Details reponse for a bulk attachement entries
```
    Take your time and generate a detailed response for each file separately.
```
## ChatGpt clarification
```
    If you need more information to answer my question accurately, please feel free to ask me clarifying questions before responding. This will help ensure your response fully meets my expectations.
```
## Analyse files and keep in the memory 
```
    Analyze the attached files and retain the relevant code in your memory for future reference. Once the analysis is complete, please confirm by responding with 'Done'."
```


# Code Utils
____________________________________________________________________________________________________
## Minify response
```
    Based on the previously generated results, can you respond to my next question by following these instructions:
    - Generate only the files that need to be updated according to my new request.
    - Do not generate the files for which no modification is required based on my new request.
```
## Reverse prompt
```
    - Scan the entire project structure provided as an attachment and analyze the content of each file.
    - Can you generate a prompt that would create exactly the project provided in the attachment, knowing that you cannot use the content of the files in your prompt?
```
## Export response as a zip file
```
    Can you generate a ZIP file containing all the files and their proposed content necessary to create a runnable project? Please ensure that the project is complete, with all required dependencies, configurations, and scripts for successful execution. Specify the structure of the project (e.g., folders and files) and the content of each file clearly.
```
## Export response as a bash
```
    Generate a shell script (install.sh) to create the project with all files and his proposed content to generate a runnable project.
```
## Export modifacation response as a bash
```
    Generate a shell script (install.sh) that will apply the proposed modifications to my project.
```
## Analyse library package
```
    Can you create a comparison table of the following libraries, including the number of stars on their GitHub repositories, the last GitCommit date, the number of monthly downloads, and their pros and cons? 
    Use the following sources: GitHub npmtrends.com. Please present the most recent results in a table format.
```

# Gpts
____________________________________________________________________________________________________
## Prompter
```
    As an expert in creating prompts for ChatGPT, can you enhance and correct the prompt below to make it more effective and comprehensible for ChatGPT in order to obtain optimal results
```