# local deepseek chat with ollama

## setup and installation:
1. install [ollama](https://www.metriccoders.com/post/how-to-install-and-run-ollama-on-macos) on your device accordingly 
2. open terminal and download the model by typing
   
    ```bash
    ollama run deepseek-r1:7b
    ```
4. install streamlit for UI view
   
    ```bash 
    pip install streamlit ollama
    ```

## run the app
**via terminal**:

    ollama serve
    ollama run deepseek-r1:7b

    
 **via webview**:
 
    streamlit run app.py -w


