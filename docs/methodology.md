# Methodology

## Base Model
Microsoft Phi-3 Mini 4K Instruct

## Dataset
MBPP (Mostly Basic Python Problems)

The dataset contains Python programming tasks used to train the model to fix buggy code.

## Fine-Tuning Method
Parameter Efficient Fine-Tuning (PEFT)

Technique used:
LoRA (Low Rank Adaptation)

## Training Configuration

LoRA Rank: 16  
LoRA Alpha: 32  
Learning Rate: 2e-4  
Epochs: 3  
Batch Size: 1  
Gradient Accumulation: 8

## Hardware

Tesla T4 GPU

Training Time:
~7 minutes

## Frameworks Used

HuggingFace Transformers  
PEFT  
TRL  
Datasets