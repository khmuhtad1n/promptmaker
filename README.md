# Article Prompt Generator

This Python script helps you generate detailed prompts for writing articles, meta descriptions, and keyphrase guidelines. It's designed to assist content creators in producing high-quality, SEO-optimized content with specific guidelines to avoid detection as AI-generated content.

## Features

- Generate prompts for various types of articles including listicles, how-to guides, product reviews, and more.
- Create detailed meta descriptions that are actionable, include a call to action, and are optimized for search engines.
- Provide keyphrase guidelines to ensure proper keyphrase usage throughout the content.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/khmuhtad1n/article-prompt-generator.git
    cd article-prompt-generator
    ```

2. Run the script:

    ```bash
    python main.py
    ```

## Usage

Follow the prompts in the terminal to generate your article prompt, meta description, and keyphrase guidelines.

1. **Enter the topic**: Provide the topic of the article.
2. **AI as a/an**: Specify the profession or role for the AI (e.g., marketing expert, tech reviewer).
3. **Enter the target market**: Define the target audience for the article.
4. **SEO keyword**: Enter the focus keyphrase for SEO optimization.
5. **Enter the total word count**: Specify the desired word count for the article.
6. **Choose an article type**: Select the type of article from the provided list.
7. **Enter the filename**: Specify the filename for the output text file.

The script will generate the prompts and write them to a file with the specified filename.

## Example

```plaintext
Enter the topic: Sustainable Living
AI as a/an (e.g., marketing expert, tech reviewer): environmental consultant
Enter the target market: eco-conscious consumers
SEO keyword: sustainable living tips
Enter the total word count: 1500
Choose an article type:
1. listicle (e.g. '10 Ways to...')
2. how-to guide
3. product review
4. opinion piece
5. interview with an expert
6. case study
7. research-based article
8. personal story
9. tips and advice
Enter the number of your chosen article type: 2
filename: sustainable_living_guide
