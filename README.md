# AI_Powered_Story_Generator
# 📖 AI Story Generator using Gradio and Hugging Face API

An interactive web application that generates short stories using the **Mistral-7B-Instruct** model via Hugging Face API. Users can select genres, choose tropes, set word counts, and pick creativity levels to generate rich and structured narratives.

## 🔥 Features

- 🎨 **Genre & Trope Selection**: Choose from a curated list of genres and related tropes.
- 🎲 **Surprise Me!**: Randomly selects a genre and trope for inspiration.
- ✍️ **Customizable Output**: Set word count and creativity level.
- 💬 **Three-Act Structure**: Each story follows a beginning, middle, and end.
- 📥 **Downloadable Stories**: Save your story with a timestamped filename.
- 🚀 **Gradio Interface**: Clean and user-friendly UI powered by Gradio Blocks.

## 🛠️ Tech Stack

- **Frontend**: [Gradio](https://www.gradio.app/)
- **Backend**: Python, Requests
- **Model**: [`mistralai/Mistral-7B-Instruct-v0.1`](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1)
- **Hosting API**: Hugging Face Inference Endpoint
- **Extras**: Timestamping, file saving, creative options

## 🧪 Example Genres & Tropes

| Genre     | Tropes                            |
|-----------|-----------------------------------|
| Fantasy   | Chosen One, Dragons Return, Magic School |
| Sci-Fi    | Alien Invasion, Time Travel, Cyber Revolution |
| Romance   | Enemies to Lovers, Fake Dating, Second Chance |
| Horror    | Haunted House, Possession, Living Doll |
| Mystery   | Cold Case, Hidden Treasure, Unreliable Narrator |
| Adventure | Treasure Hunt, Survival Journey, Race Against Time |

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/ai-story-generator.git
   cd ai-story-generator
