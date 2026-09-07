# AI Prompts - Application Tracking

This file tracks which AI application each prompt is designed for.

## Prompt Registry

| Prompt Name | AI Application | Category | Status | Last Updated |
|------------|----------------|----------|--------|---------------|
| [Example Prompt 1] | ChatGPT | Content Creation | Active | 2026-09-07 |
| [Example Prompt 2] | Claude | Analysis | Active | 2026-09-07 |
| [Example Prompt 3] | Gemini | Research | Active | 2026-09-07 |

## Supported AI Applications

- **ChatGPT** - OpenAI's conversational AI
- **Claude** - Anthropic's AI assistant
- **Gemini** - Google's AI model
- **Copilot** - Microsoft's GitHub Copilot & Copilot Pro
- **LLaMA** - Meta's open-source model
- **Midjourney** - AI image generation
- **DALL-E** - OpenAI's image generation
- **Stable Diffusion** - Open-source image generation
- **Perplexity** - AI research assistant
- **v0 by Vercel** - Generative UI system

## How to Add a Prompt

1. Create a new file in the `AI_Prompts/` directory
2. Name it descriptively (e.g., `content-writer-prompt.md`)
3. Include the following metadata at the top:
   ```markdown
   # Prompt Title
   **AI Application:** [Application Name]
   **Category:** [Category]
   **Purpose:** [Brief description]
   **Created:** [Date]
   ```
4. Add the prompt content below the metadata
5. Update this `prompt_applications.md` file with the new entry

## Categories

- Content Creation
- Code Generation
- Analysis & Research
- Data Processing
- Image Generation
- UI/UX Design
- Marketing & SEO
- Education & Learning
- Problem Solving
- Other
