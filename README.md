| Controller            | Purpose                          | Model / API      |
| --------------------- | -------------------------------- | ---------------- |
| summaryController     | Summarizes text                  | text-davinci-003 |
| paragraphController   | Writes detailed paragraph        | text-davinci-003 |
| chatbotController     | Chat like Yoda                   | text-davinci-003 |
| jsconverterController | Converts instructions to JS code | text-davinci-002 |
| scifiImageController  | Generates sci-fi images          | OpenAI Image API |

<!-- default response from open AI -->
{
  "id": "cmpl-abc123",
  "object": "text_completion",
  "created": 1234567890,
  "model": "text-davinci-003",
  "choices": [
    {
      "text": "This is the AI's generated text.",
      "index": 0,
      "logprobs": null,
      "finish_reason": "stop"
    }
  ],
  "usage": {
    "prompt_tokens": 10,
    "completion_tokens": 8,
    "total_tokens": 18
  }
}
