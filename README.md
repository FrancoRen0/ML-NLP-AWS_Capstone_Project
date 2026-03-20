# ML-NLP-AWS_Capstone_Project

Implementing an ML solution to locate course learning videos by key phrases and topics.
The challenge was solved by building an NLP pipeline using AWS services in order to extract 
main topics and entities from a dataset of 46 ML course videos.

## NLP Pipeline

1. **Amazon Transcribe** — converts video files (.mp4) to text transcriptions
2. **Text normalization & lemmatization** — cleans and preprocesses the transcribed text
3. **Amazon Comprehend** — extracts key phrases and named entities from each transcription
4. **Amazon OpenSearch** — indexes all 46 videos with their extracted metadata for search
5. **OpenSearch Dashboards** — visualizes topics and enables video search by key phrase

## Technologies
- Jupyter Notebook (Python 3.12, conda)
- Pandas, NumPy, NLTK (lemmatization)
- Amazon S3, Amazon SageMaker
- Amazon Transcribe, Amazon Comprehend
- Amazon OpenSearch Service + OpenSearch Dashboards

## Results
- 46 videos successfully transcribed and indexed
- Key phrases and named entities extracted per video
- Full-text search index enabling retrieval of videos by topic
- Visual dashboard for topic exploration (OpenSearch Dashboards)
- User-facing search by topic: future implementation
  

