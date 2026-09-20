# AIGateway

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/v1/audio/speech` | Generate speech from text | [View](../operations/post-v1-audio-speech.md) |
| POST | `/v1/audio/speech/batch` | Generate speech for multiple texts in a single request | [View](../operations/post-v1-audio-speech-batch.md) |
| POST | `/v1/audio/transcriptions` | Transcribe audio to text | [View](../operations/post-v1-audio-transcriptions.md) |
| GET | `/v1/audio/voices` | List available voices of a text-to-speech model | [View](../operations/get-v1-audio-voices.md) |
| PUT | `/v1/audio/voices` | Update an uploaded voice sample | [View](../operations/put-v1-audio-voices.md) |
| POST | `/v1/audio/voices` | Upload a voice sample for voice cloning | [View](../operations/post-v1-audio-voices.md) |
| DELETE | `/v1/audio/voices/{name}` | Delete an uploaded voice sample | [View](../operations/delete-v1-audio-voices-name.md) |
| POST | `/v1/chat/completions` | Create chat completion | [View](../operations/post-v1-chat-completions.md) |
| POST | `/v1/embeddings` | Create embeddings | [View](../operations/post-v1-embeddings.md) |
| POST | `/v1/images/edits` | Edit image from prompt and input image | [View](../operations/post-v1-images-edits.md) |
| POST | `/v1/images/generations` | Generate image from text prompt | [View](../operations/post-v1-images-generations.md) |
| GET | `/v1/mcp/resources` | List recommanded mcp servers | [View](../operations/get-v1-mcp-resources.md) |
| POST | `/v1/messages` | Anthropic Messages API | [View](../operations/post-v1-messages.md) |
| GET | `/v1/models` | List available models | [View](../operations/get-v1-models.md) |
| GET | `/v1/models/{model}` | Get model details | [View](../operations/get-v1-models-model.md) |
| POST | `/v1/ocr` | OCR | [View](../operations/post-v1-ocr.md) |
| POST | `/v1/rerank` | Rerank | [View](../operations/post-v1-rerank.md) |
| POST | `/v1/responses` | Create a model response | [View](../operations/post-v1-responses.md) |
| POST | `/v1/video/generations` | Create a video generation | [View](../operations/post-v1-video-generations.md) |
| GET | `/v1/video/generations/{video_id}` | Get a video generation | [View](../operations/get-v1-video-generations-video-id.md) |
| GET | `/v1/video/generations/{video_id}/content` | Download generated video content | [View](../operations/get-v1-video-generations-video-id-content.md) |
