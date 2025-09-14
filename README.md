# RAG AI Teaching Assistant: How to Use with Your Own Data

This guide explains how to set up and use the RAG AI Teaching Assistant with your own data.

---

## Steps to Get Started

### Step 1: Collect Your Videos
- Place all your video files in the `videos` folder.

### Step 2: Convert Videos to MP3
- Run the `video_to_mp3.py` script to convert all video files into MP3 format.

### Step 3: Convert MP3 to JSON
- Use the `mp3_to_json.py` script to convert the MP3 files into JSON format.

### Step 4: Generate Vectors from JSON
- Run the `preprocess_json.py` script to:
  - Convert the JSON files into a dataframe with embeddings.
  - Save the dataframe as a `.joblib` pickle file.

### Step 5: Generate Prompts and Feed to LLM
- Load the `.joblib` file into memory.
- Create a relevant prompt based on the user query.
- Feed the prompt to the Language Learning Model (LLM).

---

## Notes
- Ensure all scripts are in the same directory or properly referenced.
- Follow the steps sequentially for the best results.
- For any issues, refer to the documentation or raise a query.

---

Happy Teaching!


