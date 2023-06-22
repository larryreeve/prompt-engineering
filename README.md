## Welcome to Prompt Engineering Pages  

Prompt engineering is a technique used to improve the performance and output of large language models for specific tasks or domains. It involves designing and optimizing the prompts or input text that are provided to the language model to generate desired outputs. The process of prompt engineering can involve various steps such as selecting appropriate prompts, tuning the length and complexity of the prompt, fine-tuning the model on specific data, and using techniques such as task-specific tokens, prompt conditioning, and prompt tuning to improve the accuracy and relevance of the output. Prompt engineering is becoming increasingly popular in natural language processing applications, such as text completion, summarization, question answering, and conversational AI, as it allows developers to customize large language models to specific domains and tasks, and achieve better performance and accuracy. [more...](https://en.wikipedia.org/wiki/Prompt_engineering)  
<br>

## Background
- **Large Language Models**: A Large Language Model (LLM) is an artificial intelligence system designed to understand and generate human language. It is a type of deep learning model that uses neural networks with a large number of parameters and is trained on massive amounts of textual data. Large Language Models are used in various natural language processing applications such as language translation, chatbots, content generation, and text summarization. [more...](https://en.wikipedia.org/wiki/Large_language_model)

  - [The emerging types of language models and why they matter
  ](https://techcrunch.com/2022/04/28/the-emerging-types-of-language-models-and-why-they-matter)
  - [Think of language models like ChatGPT as a “calculator for words”](https://simonwillison.net/2023/Apr/2/calculator-for-words)
  - Language Models
    - [AI / ML / LLM / Transformer Models Timeline and List](https://ai.v-gar.de/ml/transformer/timeline/)
    - [Alexa Teacher Model](https://github.com/amazon-science/alexa-teacher-models)
    - [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
    - [BioGPT: generative pre-trained transformer for biomedical text generation and mining](https://academic.oup.com/bib/advance-article/doi/10.1093/bib/bbac409/6713511?guestAccessKey=a66d9b5d-4f83-4017-bb52-405815c907b9)
    - [BloombergGPT: A Large Language Model for Finance](https://doi.org/10.48550/arXiv.2303.17564)
    - [Codex (deprecated March 2023)](https://platform.openai.com/docs/guides/code)    - [Introducing LLaMA: A foundational, 65-billion-parameter large language model](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)
    - [Dramatron - Co-Writing Screenplays and Theatre Scripts with Language Models: An Evaluation by Industry Professionals](https://arxiv.org/abs/2209.14958)
    - [Free Dolly](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm)
    - [Galactica: A Large Language Model for Science](https://arxiv.org/abs/2201.08239)
    - [Koala: A Dialogue Model for Academic Research](https://bair.berkeley.edu/blog/2023/04/03/koala/)
    - [LaMDA: Language Models for Dialog Applications](https://arxiv.org/abs/2201.08239)
    - [LLaMA](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)
    - [Pathways Language Model (PaLM): Scaling to 540 Billion Parameters for Breakthrough Performance](https://ai.googleblog.com/2022/04/pathways-language-model-palm-scaling-to.html)
    - [PubMedGPT](https://crfm.stanford.edu/2022/12/15/pubmedgpt.html)
    - [The Model Hub](https://huggingface.co/docs/hub/models-the-hub)
    - [Vicuna](https://lmsys.org/blog/2023-03-30-vicuna/) [GitHub](https://github.com/lm-sys/FastChat)

  - Architecture
    - [Emerging Architectures for LLM Applications](https://a16z.com/2023/06/20/emerging-architectures-for-llm-applications)

  - Embeddings: numerical representations of concepts converted to number sequences, which make it easy for computers to understand the relationships between those concepts.
    - [What Is Embedding and What Can You Do with It](https://towardsdatascience.com/what-is-embedding-and-what-can-you-do-with-it-61ba7c05efd8)
    - [OpenAI - text-embedding-ada-002](https://openai.com/blog/new-and-improved-embedding-model)
    - [Learning embeddings for your machine learning model](https://medium.com/spikelab/learning-embeddings-for-your-machine-learning-model-a6cb4bc6542e)
    - [What are embeddings](https://vickiboykis.com/what_are_embeddings)

  - Education
    - [Understanding Large Language Models: A Cross-Section of the Most Relevant Literature To Get Up to Speed](https://magazine.sebastianraschka.com/p/understanding-large-language-models)
    - [Eight Things To Know About Large Language Models](https://cims.nyu.edu/~sbowman/eightthings.pdf)
    - [Princeton University: COS 597G (Fall 2022): Understanding Large Language Models](https://www.cs.princeton.edu/courses/archive/fall22/cos597G/)
    - [Stanford University: CS324 - Large Language Models](https://stanford-cs324.github.io/winter2022/)

  - Language Model Generation
    - Caching
      - [GPTCache : A Library for Creating Semantic Cache for LLM Queries](https://gptcache.readthedocs.io/en/latest/)
    - Tokenization
      - [SentencePiece](https://github.com/google/sentencepiece)
      - [Byte-Pair Encoding: Subword-based tokenization algorithm](https://towardsdatascience.com/byte-pair-encoding-subword-based-tokenization-algorithm-77828a70bee0)
      - [ChatGPT Tokenizer](https://platform.openai.com/tokenizer)
      - [The Art of Prompt Design: Prompt Boundaries and Token Healing](https://towardsdatascience.com/the-art-of-prompt-design-prompt-boundaries-and-token-healing-3b2448b0be38)
    - Training Corpora
      - [Anthropic Harmfulness & Helpfulness](https://huggingface.co/datasets/Anthropic/hh-rlhf)
      - [Human ChatGPT Comparison Corpus (HC3)](https://arxiv.org/pdf/2301.07597.pdf)
      - [OpenAI WebGPT](https://huggingface.co/datasets/openai/webgpt_comparisons)
      - [OpenAI Summarization](https://huggingface.co/datasets/openai/summarize_from_feedback)
      - [Open Instruction Generalist (OIG)](https://laion.ai/blog/oig-dataset/)
      - [ShareGPT](https://sharegpt.com/)
      - [Stanford Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html)
    - Transformer
      - [Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf)
      - [A Primer in BERTology: What We Know About How BERT Works](https://arxiv.org/pdf/2002.12327.pdf)

<br>
<br>


## Systems
- [ChatGPT](https://chat.openai.com/chat)
  - [GPT-3 powers the next generation of apps](https://openai.com/blog/gpt-3-apps)
  - [InstructGPT/GPT 3.5](https://arxiv.org/abs/2203.02155)
  - [GPT-4](https://openai.com/product/gpt-4) 
  - [GPT-4 Technical Report](https://doi.org/10.48550/arXiv.2303.08774)
  - [ChatGPT Plugins](https://platform.openai.com/docs/plugins/introduction)
  - [Developer Documentation](https://platform.openai.com/docs/introduction)
  - [Summarizing books with human feedback](https://openai.com/research/summarizing-books)
  - [ChatGPT Is a Blurry JPEG of the Web](https://www.newyorker.com/tech/annals-of-technology/chatgpt-is-a-blurry-jpeg-of-the-web)
  - [Road to ChatGPT](https://www.linkedin.com/posts/ramar_the-road-to-chatgpt-an-informal-explainer-activity-7038334518004482048-h3G5?utm_source=share&utm_medium=member_desktop)   [*pdf*](https://drive.google.com/file/d/1-Gw1QsZEVhPYSeeNYnlrcgk_FbwuUTwq/view?pli=1)
- [Bard](https://bard.google.com)
- [Bing Chat](https://www.microsoft.com/en-us/bing)
- [Claude](https://www.anthropic.com/index/introducing-claude)

<br>


## Prompt Engineering
- Overview
  - [A Complete Introduction to Prompt Engineering For Large Language Models](https://www.mihaileric.com/posts/a-complete-introduction-to-prompt-engineering/)
  - [Prompting Introduction](https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/guides/prompts-intro.md)
  - [Prompting Guides](https://github.com/dair-ai/Prompt-Engineering-Guide/tree/main/guides)  
  - [Prompt Engineering Guide](https://www.promptingguide.ai/)
  - [Prompt Engineering](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering)
  - [Learn Prompting](https://learnprompting.org/docs/intro)

- ChatGPT
  - [Best practices for prompt engineering with OpenAI API](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)
  - [OpenAI Cookbook](https://github.com/openai/openai-cookbook)
  - [The ChatGPT Prompt Cheat Sheet: Tips, Tricks, and Examples for Crafting Effective Prompts](https://docs.kanaries.net/articles/chatgpt-prompt-cheat-sheet)
  - [AutoGPT](https://autogpt.net/category/autogpt/)
- Examples
  - ChatGPT
    - [ChatGPT Examples](https://platform.openai.com/examples)
    - [Simulating an FTP server at ftp.disney.com with ChatGPT4](https://www.filestash.app/2023/04/01/chat-gpt-acting-as-a-ftp-server)
    - [Named Entity Recognition using ChatGPT](src/ner-chatgpt.md)
    - [HTML Table Parser in Python](src/htmltableparser-chatgpt.md)
    - [KDNuggets Cheat Sheet](https://www.kdnuggets.com/publications/sheets/ChatGPT_Cheatsheet_Costa.pdf)
    - [ChatGPT Failures](https://github.com/giuven95/chatgpt-failures)
  - Free Dolly
    - [Free Dolly - Prompt/Response Pairs DataSet](https://github.com/databrickslabs/dolly/tree/master/data)
- Background
  - [Few-shot learning (natural language processing)](https://en.wikipedia.org/wiki/Few-shot_learning_(natural_language_processing))
  - [Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf)
  - [Prompt Programming for Large Language Models: Beyond the Few-Shot Paradigm](https://arxiv.org/pdf/2102.07350.pdf)
  - [GPT3: Language Models are Few-Shot Learners](https://arxiv.org/pdf/2005.14165.pdf)
  - [Building LLM applications for production](https://huyenchip.com/2023/04/11/llm-engineering.html#prompt_engineering_challenges)
  - [Solving a machine-learning mystery: A new study shows how large language models like GPT-3 can learn a new task from just a few examples, without the need for any new training data.](https://news.mit.edu/2023/large-language-models-in-context-learning-0207)
- Tooling
  - [LangChain](https://python.langchain.com/en/latest/index.html) is a framework for developing applications powered by language models.

## Career
- [Tech’s hottest new job: AI whisperer. No coding required.](https://www.washingtonpost.com/technology/2023/02/25/prompt-engineers-techs-next-big-job/) 
- [What Does a Prompt Engineer Do?](https://medium.com/sopmac-ai/what-does-a-prompt-engineer-do-f00c6f2ad1ab)
- ['Prompt engineering' is one of the hottest jobs in generative AI. Here's how it works.](https://www.businessinsider.com/prompt-engineering-ai-chatgpt-jobs-explained-2023-3)
- [In defense of prompt engineering](https://simonwillison.net/2023/Feb/21/in-defense-of-prompt-engineering)
- [Hacker News: Prompt Engineering Jobs](https://news.ycombinator.com/item?id=35411037)
- [PromptBase - DALL·E, GPT, Midjourney, Stable Diffusion, ChatGPT Prompt Marketplace](https://promptbase.com)
