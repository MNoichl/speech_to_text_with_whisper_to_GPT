# Actually useful speech to text via Whisper and GPT-4
This repo provides a notebook (whisper_to_GPT_MN.ipynb) to turn a dictation, which you can create e.g. with Audacity on your PC, into a reasonable piece of text of the genre that you need. After transcribing your text using the whisper model, the notebook passes it to GPT-4, with the instructions to fix any dictation infedilities, and to adapt it to your predefined style, usually without any typos. You can also create your own styles with the style_instruction_generator_MN.ipynb notebook.

I use this for E-Mails, to-do-lists, drafting, meeting-minutes and also to turn ramblings into reasonable notes. This GitHub-repo contains also a style-sheet, and a notebook that helps in the creation of styles.

Importantly, for this to work, you will need an OpenAi-API-key, and pay for your usage. I feel this is quite reasonably priced, but until you get a feeliong for it, I suggest you monitor your spending! Also make sure to double check your texts. E.g. dictated last names in E-Mails are commonly mispelled, and might need post-hoc fixing.

Please feel free to share new styles you create, or additional languages with me!
