# MSc-in-Business-Analytics--May

Mapping Information Bottlenecks- Post Office Horizon IT Inquiry
MSc Business Analytics Dissertation- May Brany Aung ()01479743)
University of Greenwich| Supervisor- Guru Ramakrishnan | Programme Leader- Dr. Srinidhi Vasudevan

##Overview
This project compares two automated speech-recognition (ASR) pipelines- AssemblyAPI and Faster-Whisper - on public testimony from the Post Office Horizon IT inquiry , Word Error Rate checked, then applies social network analysis (Burt’s structural holes theory) to locate single-path information bottlenecks in the testimony.

## Repository Structure
Part 1  (Google Colab )- ASR transcription (GPU)
Part 2  (Jupyter Notebook) -WER, NER , network construction, relation extraction pilot, structural hole analysis (CPU)
Gephi - nodes/ edges for Geohi visualisation
Part 2 Datasets.csv- all Part 2 datasets
FW and API transcription texts
Burt constraint effective size top 15

## Data sources
Testimony sessions used -Days 117,143, 152, 156 (Post office Horizon Inquiry), plus one comparative session from the Infected Blood Inquiry (WER validation only)
Source recordings and official transcripts are publicly available at -https://www.postofficehorizoninquiry.org.uk/ 

Source Video Sessions (Youtube)
-Day 143 AM - https://www.youtube.com/watch?v=LY9CfDVj8xI
-Day 152 PM  -https://www.youtube.com/watch?v=uzdKJpphBYM&t=1706s
-Day 156 AM--https://www.youtube.com/watch?v=O3e50SkATjU
-Day 117 AM- https://www.youtube.com/watch?v=sHjw95Zjz2w 

Infected Blood Inquiry (comparative session)- https://www.youtube.com/watch?v=aexVAOf58ZI
How to reproduce 
Run Part 1 Transcription in Google Colab (GPU) to generate raw transcripts and WER comparison.
Run Part 2 notebook locally in Jupyter (Anaconda) using the Part 1 outputs as input

Key Outputs 
-Entity mentions by category (Organisation, Technical System, Individual, Event/Issue)
-Network Fragility metrics- bridges, articulation points, betweenness centrality, Burt’s constraint effective size.
-Cross-pipeline consistency comparison (Assembly API vs Faster-Whisper)

# Note 
This supports the dissertation methodology (Chapter 3) and findings ( Chapter 4-5)
Full analysis and discussion are in the dissertation document not repeated here.


