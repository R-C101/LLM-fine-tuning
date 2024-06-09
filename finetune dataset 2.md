Finetuning videos

- https://www.youtube.com/watch?v=eeM6V5aPjhk&pp=ygUSZmluZXR1bmluZyBheG9sb3Rs
- https://www.youtube.com/watch?v=74NSDMvYZ9Y&pp=ygUSZmluZXR1bmluZyBheG9sb3Rs

Dataset
- Start with Orca (https://mlabonne.github.io/blog/notes/Large%20Language%20Models/orca.html). Find the training dataset (dont ask us for it. We expect you to do your own research)
- Removed instructions with less than 100 tokens in response.
- Data deduplication by doing grouping using cosine similarity (threshold>0.95)
- publish this dataset on huggingface (https://huggingface.co/docs/datasets/upload_dataset). We will need the link to this dataset.
- Do a finetune of llama2 using this new dataset that you created.

# Deadline & instructions. for interview
1. Please do whatever you can and send it within 2 days.  Even if not complete. we will evaluate basis that.
2. Create zip file of notebook code and upload it to google drive. Create a shareable link 
3. Create a demo video using https://www.loom.com/. We want you to share your desktop screen and walk us through the code and explain what is happening. send us the loom.com demo video link
4. **INTERVIEW SUBMISSION** - please send the THREE links (Google Drive zip file of your code, Huggingface link of your dataset and loom) on chat. it will help us track your submission. We will not proceed without these three links.
5. please do NOT upload your code on github under any circumstances.

