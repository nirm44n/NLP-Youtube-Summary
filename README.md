# NLP-Youtube-Summary

In this project, I developed a YouTube video transcript summarizer that automatically extracts video transcripts from YouTube and generates concise summaries using the Natural Language Toolkit (NLTK) and sentence tokenization techniques.

To accomplish this, I utilized the YouTube API to fetch the video based on the provided URL or video ID. Once the video was obtained, I extracted the text of the video using its transcript.

With the video transcript in hand, I leveraged the powerful features of NLTK, a widely used natural language processing library, to tokenize the transcript into individual sentences. This sentence tokenization step allowed me to break down the transcript into smaller units for analysis.

To generate the summary, I used NLTK’s summarization algorithms. By applying techniques like extractive summarization, I identified the most significant sentences and constructed a condensed summary that captures the key points and main ideas of the video.
