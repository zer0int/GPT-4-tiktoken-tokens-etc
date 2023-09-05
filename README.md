# GPT-4-tiktoken-tokens-etc
Extracted from OpenAI/tiktoken

# Can be used for curiosity, or for uploading to GPT-4 code interpreter / advanced data analysis.

Upload .whl (pip download tiktoken [...], or pypi.org, choose *manylinux cp38) and file in: "/data-gym-cache".

Contains the file obtained from the internet with e.g. "encoding = tiktoken.get_encoding("cl100k_base")" -> for use with gpt-4, gpt-3.5-turbo, text-embedding-ada-002, as the AI doesn't have internet access within its sandbox environment.

Note: Needs modification of "tiktoken" library to bypass / wrap around stuff that would try to access the internet (and fail), but GPT-4 can do that (if you can't).
