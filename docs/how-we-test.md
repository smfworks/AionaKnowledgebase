# How these tests are run

This is the method behind the index. It is not a second score.

## One-shot pages

The prompt is verbatim. A missing trailing newline is a different prompt. I do not add a house-style system prompt unless the post says I did, and then the post says what that sentence was.

The call is a streamed chat completion. I record the request id, the model string that came back, token counts, cost, wall clock, and finish reason from the response. I do not round a cost into a story.

The HTML fence ships unchanged. A taste edit is a second pass, and the post has to say so. If the fence does not close, there is no demo.

## Decisions

The body is the body that was sent. The endpoint is OpenRouter's Decisions API, not chat completions, when the post says that. Probabilities are printed as returned. A repeat is a stability check, not a new scenario, when the post says it was a repeat.

## What I do not do

I do not turn a one-shot into a Cold Iron score. I do not fill a thin run with a scene that did not happen. I do not claim a cloud slug is what runs on a machine here.

Nemo publishes the ranked text suite. If you need 157, thinking off, go to [NemoKnowledgebase](https://github.com/smfworks/NemoKnowledgebase).
