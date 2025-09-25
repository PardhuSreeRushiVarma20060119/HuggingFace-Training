---
library_name: ml-agents
tags:
- Huggy
- deep-reinforcement-learning
- reinforcement-learning
- ML-Agents-Huggy
---
# PPO Huggy Training 🐻  

**My HuggingFace Repo:** [VarmaHF/ppo-HuggyTraining](https://huggingface.co/VarmaHF/ppo-HuggyTraining)  

This repository contains a **trained Proximal Policy Optimization (PPO) agent** playing the **Huggy environment**, built using the **Unity ML-Agents library** and integrated with the Hugging Face Hub.  

The goal of this project was to explore reinforcement learning (RL) with Unity environments and make the trained agent accessible and interactive through Hugging Face.  

---

## 🚀 Usage  

If you’re new to ML-Agents, check out the official [ML-Agents Documentation](https://unity-technologies.github.io/ml-agents/ML-Agents-Toolkit-Documentation/) for setup, installation, and training details.  

You can also dive into Hugging Face’s **[Deep RL Course](https://huggingface.co/learn/deep-rl-course/)** for step-by-step guidance on how to train agents and upload them to the Hub.  

---

## 🎮 Play with your Huggy 🐕  

This is the fun part! You can **interactively play with your trained Huggy agent** directly in your browser:  

👉 Open the Huggy game here: [Huggy on Hugging Face Spaces](https://huggingface.co/spaces/ThomasSimonini/Huggy)  

1. Click **“Play with my Huggy model”**  
2. In **Step 1**, enter your exact Hugging Face username (case-sensitive). Example: `VarmaHF`  
3. In **Step 2**, select the repository: `ppo-HuggyTraining`  
4. In **Step 3**, choose the model checkpoint you want to replay.  

💡 During training, multiple model checkpoints were saved (e.g., every 200,000 timesteps).  
You can try different versions to observe how Huggy improves over time.  
For example, the most recent model file is: **`Huggy.onnx`**  

---

## ⚙️ Training Setup  

- **Environment**: Huggy (Unity ML-Agents)  
- **Algorithm**: PPO (Proximal Policy Optimization)  
- **Frameworks**: Unity ML-Agents + Hugging Face Hub  
- **Integration**: Model packaged and uploaded to Hugging Face for sharing and deployment  

---

## 📊 Results  

The PPO agent was trained successfully and learned to play the Huggy environment. 
![Trained Huggy Preview](replay.gif)

Thanks to the Hugging Face integration, you can:  
- Preview the trained agent  
- Replay and test different checkpoints  
- Interactively compare performance improvements over training  

---

## 📚 References  

- [Unity ML-Agents Toolkit](https://github.com/Unity-Technologies/ml-agents)  
- [Hugging Face Deep RL Course](https://huggingface.co/learn/deep-rl-course/)  
- [Hugging Face Spaces - Huggy Game](https://huggingface.co/spaces/ThomasSimonini/Huggy)

---

✨ **Enjoy training, exploring, and playing with Huggy!** 🐻
