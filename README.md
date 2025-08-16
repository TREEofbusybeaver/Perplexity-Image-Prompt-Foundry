# Perplexity Image Prompt Foundry

An open-source collection of advanced JSON prompt templates and research for creating high-fidelity images aligned with Perplexity's "surreal-real with retro vibes" brand aesthetic. Includes a Lyra System Prompt for guided creativity.

## Table of Contents
- [Core Philosophy](#core-philosophy)
- [How to Use](#how-to-use)
- [File Descriptions](#file-descriptions)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Core Philosophy

This repository is built on a deep analysis of Perplexity AI's visual brand identity. The guiding aesthetic is **"Surreal-Real with Retro Vibes"**:

-   **Real (Base):** The foundation is always photorealistic, grounded, and credible, reflecting the brand's commitment to accurate, cited answers.
-   **Surreal (Modifier):** Conceptual, subtle, and orderly surrealism is layered on top. This isn't fantasy; it's a visual metaphor for knowledge discovery and layered perspectives, akin to magical realism.
-   **Retro Vibes (Finish):** The "retro" feel comes from an "editorial modernity"—the timeless, curated aesthetic of classic magazines. This is achieved through refined color grading, soft film grain, and balanced compositions, not heavy-handed filters.

For a complete breakdown, please see the [RESEARCH.md](./RESEARCH.md) file.

## How to Use

1.  **Start with the Template:** Open [`PROMPT_TEMPLATE.json`](./PROMPT_TEMPLATE.json). This file contains the complete, modular structure for a brand-aligned prompt.
2.  **Fill the Fields:** Populate the empty fields like `title`, `objective`, and `narrative_hook`.
3.  **Select and Customize:** Adjust values within the `style`, `color_lighting`, and `composition` blocks. Modify strengths like `photorealism_strength` and `surreal.intensity` to fine-tune the output.
4.  **Choose a Target Model:** The `targets` block contains pre-configured structures for different AI models (Midjourney, DALL-E 3, etc.). Use the one that best fits your needs.
5.  **Generate:** Copy the constructed prompt into your image generation tool of choice.

## File Descriptions

-   **`PROMPT_TEMPLATE.json`**: The master JSON template with all modular components for creating a new image prompt.
-   **`RESEARCH.md`**: A detailed document reverse-engineering Perplexity's visual brand and outlining the principles behind the prompt system.
-   **`SYSTEM_PROMPT_LYRA.md`**: A system prompt for "Lyra," an AI persona designed to help you optimize image prompts.
-   **`.gitignore`**: A standard gitignore file for this project.
-   **`/examples`**: This directory contains completed JSON prompts and the corresponding output images.

## Examples

Here are three examples created using the template.

#### 1. Cosmic Vista from Observatory
*A wide, eye-level view from a minimalist observatory interior onto an expansive alien canyon beneath a majestic planetary sky.*

![Cosmic Vista from Observatory](./examples/images/01_cosmic_vista_observatory.png)

#### 2. Geode Caverns
*A mystical, serene subterranean geode cavern with glimmering crystals, grounded in realism with restrained, conceptual surreal cues.*

![Geode Caverns](./examples/images/02_geode_caverns.png)

#### 3. Data Spire Garden
*A monumental glass-and-steel skyscraper entwined with elegant digital flora at golden hour, with restrained, conceptual surreal overlays.*

![Data Spire Garden](./examples/images/03_data_spire_garden.png)

## Contributing

Contributions are welcome! If you develop a new prompt that fits the brand aesthetic, please feel free to open a pull request. Ensure your submission includes both the completed `.json` prompt file and the generated image.

## License

This project is licensed under the [MIT License](LICENSE).