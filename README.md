# 🧬 Hemoglobin Beta Chain: MSA and Homology Modeling

This project performs multiple sequence alignment and homology modeling of the Hemoglobin beta subunit from various mammals.

## 📌 Objectives
- Align hemoglobin beta sequences from 5 species
- Analyze sequence conservation using a sequence logo
- Build 3D homology model of the human HBB using SWISS-MODEL
- Visualize the predicted model in 3D

## 🧬 Sequences Aligned
- Human (Homo sapiens)
- Mouse (Mus musculus)
- Pig (Ondatra zibethicus)
- Horse (Bos taurus)
- Rabbit (Oryctolagus cuniculus)

## 🧠 Tools Used
- Biopython
- Clustal Omega (via wrapper)
- Logomaker
- SWISS-MODEL (Web)
- py3Dmol (Colab Visualization)

## 📊 Results
- Conserved motifs and domains identified
- Sequence logo shows amino acid frequencies at each position
- 3D model successfully generated and visualized

![Logo](alignment/sequence_logo.png)

## 🔬 Model Visualization
<p align="center">
  <img src="model/spinning_model.gif" width="400"/>
</p>

## 🚀 Run the Code
Open `notebooks/clustal_X_MSA_swissmod.ipynb` in Google Colab.

## ✅ Output Files
- `aligned.aln` – MSA output
- `target_for_swissmodel.fasta` – Clean target sequence
- `model_02.pdb` – Predicted 3D structure
