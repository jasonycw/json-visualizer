# json-visualizer
> Very straight forward prompt
> ```
> Create a single page HTML that can do the following without any external library and other public scripts, no CSS support library, nothing, just single HTML page in a folder with nothing else.
> 
> 1. There should be 2 columns layout
> 
> 2. The left panel is just a huge input box that allow user to input any text. Having JSON syntax highlight is a plus.
> 
> 3. The right panel react when there are new text input to the left panel. When the left panel is not a valid JSON, there should be a red alert on the top saying the input in not a valid JSON. When the left panel is a valid JSON, it should convert the JSON into a single layer JSON, all the nested object should be flattened and then on the right panel show show a table with one column showing the JSON key and another column showing the JSON value. If the JSON value is a HTML string, it should be rendered out.
> ```

| LLM                                                                                                              | The result |
|------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| [Gemini 3.1 Pro](https://gemini.google.com/share/0c9745914225)                                                   | [Go](https://jasonycw.github.io/json-visualizer/gemini/)|
| [Google AI mode](https://share.google/aimode/HDVPhgwcVbVhWjYFp)                                                  | [Go](https://jasonycw.github.io/json-visualizer/google-ai-mode/)|
| [Perplexity](https://www.perplexity.ai/search/create-a-single-page-html-that-t08yXELHR72YQCJi5GreBw?preview=1)   | [Go](https://jasonycw.github.io/json-visualizer/perplexity/)|
| [Grok](https://grok.com/share/c2hhcmQtMg_d8c58954-8961-49e0-a8e8-fccdb0bec59e)                                   | [Go](https://jasonycw.github.io/json-visualizer/grok/)|
| Claude Sonnet                                                                                                    | [Go](https://jasonycw.github.io/json-visualizer/claude-sonnet/)|
| GitHub Copilot with GPT 4.1                                                                                      | [Go](https://jasonycw.github.io/json-visualizer/github-copilot-gpt-4.1/)|
| [OpenAI GPT-5.3](https://chatgpt.com/share/69eb6d5a-fc2c-83ea-b6e5-56a3916c8461)                                 | [Go](https://jasonycw.github.io/json-visualizer/openai-gpt-5.3/)|
| OpenAI GPT-5.4 Think                                                                                             | [Go](https://jasonycw.github.io/json-visualizer/openai-gpt-5.4-thinkg/)|
| [OpenAI GPT-5.5](https://chatgpt.com/s/cd_69eb787f88fc81918b3a3f0c8eb78281)                                      | [Go](https://jasonycw.github.io/json-visualizer/openai-gpt-5.5/)|
| CopilotCLI GPT-5.6 Sol                                      | [Go](https://jasonycw.github.io/json-visualizer/copilot-cli-gpt-5.6-sol//)|