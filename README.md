# gt-streamlit
The code for integrating Great Tables with Streamlit is straightforward. The key point to remember is to set `unsafe_allow_html=True` when using `st.write()`. After running the following command, you should see the table displayed in your browser at [http://127.0.0.1:8000](http://127.0.0.1:8000):

```bash
streamlit run main.py
```

![image](https://raw.githubusercontent.com/jrycw/gt-streamlit/refs/heads/master/gt-streamlit.png)

