# LinkedIn AI Post Generator – Automated LinkedIn Content Creation
This workflow automatically generates professional motivational LinkedIn posts using **n8n**, **OpenRouter AI** and **FLUX Image Generation** — producing quotes, explanations, hashtags, AI images and posting them to LinkedIn without manual effort.
## 🚀 Features
- Fetches motivational quotes automatically  
- Generates a cinematic visual description using AI  
- Creates high-quality images using **FLUX.1 (HuggingFace Router)**  
- Produces a professional 60–120 word motivational caption  
- Generates 12–18 curated hashtags  
- Combines quote + caption + hashtags into a final post  
- Automatically posts to **LinkedIn** with the image
- 
## ⚙️ Workflow Overview
**Quote API → JavaScript Parse → AI Explanation → AI Hashtags → Merge Caption → AI Image Description → FLUX Image Generation → LinkedIn Publish**

## 🧭 Workflow Diagram
![Workflow Diagram](workflow.png)

## ▶️ Demo Preview

<p align="center">
  <a href="demo.mp4">
    <img src="https://img.shields.io/badge/▶️ Click_to_Watch_Demo-FF0000?style=for-the-badge" width="300"/>
  </a>
</p>

<p align="center">
  <video width="700" controls>
    <source src="demo.mp4" type="video/mp4">
  </video>
</p>


## 🧩 Tech Stack
- **n8n** – Automation engine  
- **OpenRouter (LLM)** – AI explanation + hashtags  
- **FLUX.1 Schnell (HuggingFace Router)** – Cinematic image generation  
- **JavaScript (n8n Code Node)** – Quote parsing  
- **LinkedIn API (OAuth 2.0)** – Auto publishing
- 
## 🧠 Key Highlights
- Generates viral-style LinkedIn content automatically  
- Cinematic artwork with **no text inside the image**  
- Motivational explanations written in a professional tone  
- Fully automated end-to-end posting pipeline  
- Perfect for daily content posting
-   
## 🖼️ Example Output
### Caption Example
```
Some people want it to happen, some wish it would happen, others make it happen. - Michael Jordan

I have learned through years of professional challenges that true progress demands more than desire or hope. It requires stepping into the arena with resolve, turning vision into action through disciplined effort and strategic choices. In my own path, this shift from passive longing to proactive creation unlocked doors I once only imagined.

You hold that power too.

**Key Takeaway:** Embrace the maker's mindset, and transform your ambitions into achievements.
```
### Hashtags Example
`#motivation hashtag#mindset hashtag#lifelessons hashtag#inspiration hashtag#action hashtag#personalgrowth hashtag#wisdom hashtag#psychology hashtag#success`

### Image Example
*(Generated using **FLUX.1 Schnell**, no text inside the image)*  
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/028f44e6-fc8d-495c-a555-9e106002c385" />


## 🧑‍💻 Author
**Muhammad Musab**  
🌐 https://github.com/muhammadmusabyaqoob
## 🏷️ Tags
`n8n` `OpenRouter` `FLUX` `AI` `Automation` `LinkedIn` `Content Generator` `Workflow`
## 🌟 Badges
![n8n Workflow](https://img.shields.io/badge/Automation-n8n-blue?style=for-the-badge)  
![AI Powered](https://img.shields.io/badge/AI%20Powered-OpenRouter-brightgreen?style=for-the-badge)  
![Image Generation](https://img.shields.io/badge/FLUX-Image%20Generation-orange?style=for-the-badge)  
![LinkedIn Automation](https://img.shields.io/badge/LinkedIn-Automation-blue?style=for-the-badge)
