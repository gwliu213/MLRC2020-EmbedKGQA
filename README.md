# EmbedKGQA: Reproduction and Ablation Study 
This is the code for the [MLRC2020 challenge](https://paperswithcode.com/rc2020) for the [ACL 2020](https://acl2020.org/) paper [Improving Multi-hop Question Answering over Knowledge Graphs using Knowledge Base Embeddings](https://malllabiisc.github.io/publications/papers/final_embedkgqa.pdf)[1]

# Requirements
- Python >= 3.7.5

# Get started

```bash
# Clone the repo
git clone https://github.com/jishnujayakumar/MLRC2020-EmbedKGQA
cd MLRC2020-EmbedKGQA/
pip install -r requirements.txt

# Download and unzip data and pretrained_models
# Google frive folder: https://drive.google.com/drive/folders/1RlqGBMo45lTmWz9MUPTq-0KcjSd3ujxc
# gdown requires anyone with the link id; right click on each file and get it 
gdown --id 1uWaavrpKKllVSQ73TTuLWPc4aqVvrkpx; unzip data.zip;
gdown --id 1Ly_3RR1CsYDafdvdfTG35NPIG-FLH-tz; unzip pretrained_models.zip;

# use pretrained KG embeddings or train from scratch

# Install HugginFace transformers packages from source
git clone https://github.com/huggingface/transformers
cd transformers
pip install .
```


# Helpful links
- [Read](https://github.com/malllabiisc/EmbedKGQA#instructions) for details about data and pretrained weights 
- [Read](https://github.com/malllabiisc/EmbedKGQA#dataset-creation) for details about dataset creation
- [Presentation](https://slideslive.com/38929421/improving-multihop-question-answering-over-knowledge-graphs-using-knowledge-base-embeddings) for [1] by Apoorva Saxena


### Citation:
Please cite the following paper if you use this code in your work.

```bibtex
Placeholder for ReScience C BibTex
```

For any clarification, comments, or suggestions please create an issue or contact [Jishnu](https://jishnujayakumar.github.io/) or [Ashish](mailto:asardana@nvidia.com).
