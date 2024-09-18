import streamlit as st
import random

# Generate key for encode
def generatekey():
    key = []
    for i in range(26):
        key.append(chr(i + 97))
    random.shuffle(key)
    return key


def inputkey():
    string_key = st.text_input('Input key:')
    key = []
    for i in string_key:
        key.append(chr(ord(i)))
    return key

st.caption("Written by Nguyen Tuan")
option = st.selectbox(
    "Generate a random Key",
    "Add an exist Key")
st.write("You selected:", option)
if option == "Generate a random Key":
    encode_key = generatekey()
else:
    encode_key = inputkey()
print(encode_key)









