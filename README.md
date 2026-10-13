# 📚 AI Storytelling Bot

An AI-powered storytelling application that creates imaginative, engaging, and original stories based on user-provided ideas, characters, genres, and themes. The application transforms simple prompts into creative narratives using artificial intelligence and provides an interactive interface for users to explore different storytelling styles.

## 1. Problem Statement

Creating original stories can be challenging for people who struggle with creativity, inspiration, or finding the right words to express their ideas. Writers and students may need assistance developing characters, building plots, and creating engaging narratives.

The **AI Storytelling Bot** addresses this problem by allowing users to provide a story idea, character description, or preferred genre and receive an AI-generated story. It encourages creativity and makes storytelling more accessible, interactive, and enjoyable.

**Target Users:**
- Students who want to improve their creative writing.
- Aspiring writers looking for story inspiration.
- Children and readers interested in imaginative stories.
- Content creators developing fictional narratives.
- Anyone who enjoys exploring AI-generated stories.

## 2. Features

- **AI Story Generation:** Generate original stories from user prompts.
- **Genre Selection:** Create stories in genres such as horror, fantasy, mystery, adventure, and romance, depending on the application's configuration.
- **Character-Based Storytelling:** Generate narratives using user-defined characters.
- **Custom Story Prompts:** Enter ideas, settings, or situations to guide the story.
- **Creative Narratives:** Transform simple ideas into engaging storylines.
- **Interactive User Interface:** Generate stories through a user-friendly interface.
- **Flexible Story Ideas:** Experiment with different themes and storytelling styles.

## 3. Tech Stack

- **Programming Language:** Python
- **AI and NLP:** Hugging Face Transformers
- **Language Model:** The configured pretrained text-generation model
- **Deep Learning Framework:** PyTorch
- **User Interface:** Gradio
- **Model Hosting:** Hugging Face

## 4. How to Run Locally

### Prerequisites

- Python 3.10 or later
- Git
- Internet access to download the model, if required

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### Step 2: Navigate to the Project Folder

```bash
cd YOUR-REPOSITORY
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

If you do not have a `requirements.txt` file, install the dependencies used by your application. For a typical Transformers-based Gradio project:

```bash
pip install torch transformers gradio
```

### Step 4: Run the Application

```bash
python app.py
```

### Step 5: Open the Application

Open the local URL displayed in the terminal to access the Storytelling Bot. Enter a prompt, select your preferred options if available, and generate your story.

## 5. Working Pipeline

**User Prompt → Input Processing → Language Model → Text Generation → Generated Story**

### How It Works

1. **User Input:** The user enters a story idea, character description, or theme.
2. **Prompt Processing:** The application prepares the input for the language model.
3. **AI Text Generation:** The configured language model generates a narrative based on the prompt.
4. **Story Formatting:** The generated text is prepared for display.
5. **Output Display:** The complete story is presented through the interactive interface.

## 6. Evaluation

The application can be tested with different prompts to evaluate creativity, relevance, coherence, and instruction following.

| No. | Test Prompt | Expected Behaviour |
|---|---|---|
| 1 | Write a short horror story in an abandoned hospital. | Generates a suspenseful horror narrative. |
| 2 | Create a fantasy story about a magical kingdom. | Produces an imaginative fantasy story. |
| 3 | Write an adventure about a lost explorer. | Generates an adventure with challenges and discoveries. |
| 4 | Create a mystery involving a missing necklace. | Develops a mystery with clues. |
| 5 | Write a story about a robot who wants to become human. | Creates a science-fiction narrative. |
| 6 | Create a story with a brave girl as the main character. | Incorporates the requested character. |
| 7 | Write a story about friendship and trust. | Develops a narrative around the requested theme. |
| 8 | Generate a story about a village with a strange secret. | Builds suspense around the village's secret. |
| 9 | Write a short story with a surprising ending. | Attempts to produce an unexpected conclusion. |
| 10 | Write a story using a simple one-line idea. | Expands the idea into a coherent narrative. |

### Evaluation Criteria

- **Relevance:** Does the story follow the user's prompt?
- **Creativity:** Does it introduce interesting ideas and details?
- **Coherence:** Does the story maintain a logical flow?
- **Character Development:** Are the characters consistent and meaningful?
- **Readability:** Is the story understandable and engaging?

*Note: These are proposed test cases and expected behaviours, not measured evaluation results.*

## 7. Limitations and Safety

### Limitations

- Generated stories may contain repetitive ideas or predictable plots.
- Long stories may lose consistency in characters or events.
- The quality of output depends on the language model being used.
- The model may misunderstand vague or contradictory prompts.
- Generating long narratives may require additional processing time.

### Safety Considerations

- AI-generated stories may occasionally contain inappropriate or misleading content.
- User prompts should follow the application's content guidelines.
- Avoid including personal or confidential information in prompts.
- Generated stories should be reviewed before publication.
- The application should not reproduce copyrighted stories on request or imitate living authors' styles when prohibited by applicable policies.

## 8. Live App Link

**Hugging Face Spaces:** [Add Your Deployed Application Link Here](https://huggingface.co/spaces)

Replace the placeholder with your actual deployed application URL.

## 9. Screenshots

Add screenshots of your Storytelling Bot to demonstrate its interface and generated output.

### Application Interface
![Storytelling Bot Interface](screenshots/home.png)

### Story Prompt
![Story Prompt](screenshots/prompt.png)

### Generated Story
![Generated Story](screenshots/story.png)

*Replace these paths with the actual screenshot filenames uploaded to your GitHub repository.*

## Future Improvements

- Add interactive storytelling with multiple choices.
- Support different languages.
- Add character profiles and story continuation.
- Allow users to save and download stories.
- Add text-to-speech narration.
- Introduce customizable story length and difficulty.
- Improve plot consistency and character memory.

## Conclusion

The AI Storytelling Bot demonstrates how natural language processing and text generation can support creative writing. By turning user ideas into imaginative narratives, the application offers an interactive way to explore storytelling and experiment with artificial intelligence.

---

**Developed using Python, Hugging Face Transformers, PyTorch, and Gradio.**
