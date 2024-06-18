# Chatgpt-API
## Rap Battle GPT

Welcome to the Rap Battle GPT project, a specialized GPT model designed to generate creative rap battles about notable individuals. This project is a collaboration between Gian Villafañe, Taisgaly Vélez Rodríguez, Rosemary Medina-Casanova, and Maya Wilson-Fernandez.

## Project Overview

The Rap Battle GPT is an experimental language model that leverages the capabilities of GPT to create engaging and creative rap lyrics. The model currently focuses on well-known personalities who have significant online information, potentially expanding to include user-specified individuals in future iterations.

## Features

- **Creativity Settings**: Users can adjust the "temperature" setting to control the creativity of the generated content.
  - `Temperature: 1.0` (Default creativity)
  - `Temperature: 1.5` (Enhanced creativity with potential for unconventional outputs)

- **Token Management**: Controls the length and depth of the generated raps based on the number of tokens.
- **Top_p Adjustment**: Manages the randomness of response generation, affecting the diversity of the output.

## Lessons Learned

- The `temperature` setting significantly influences the directness and creativity of responses. Values above `1.0` can make the content less comprehensible due to increased creativity.
- Managing the `top_p` parameter and token count is crucial for fine-tuning the balance between creativity and coherence in the generated lyrics.

