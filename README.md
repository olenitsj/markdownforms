# MarkdownForms
Simplify forms and surveys through Markdown

## My problem
Working in the IAM domain, integrating machines into the IAM platform requires a lot of requirements gathering. To simplify the process we use surveys with default questions. However, the tools to make and publish surveys always lack the simplicity and integration with proper CI/CD and the easy-of-use that we apply for our code and documentation generation.
What I always missed, is a way to write surveys in Markdown and deploy them consistently to different mediums. 

Additional problems that occurred: lock in with vendors e.g. Google forms, Microsoft forms, survey monkey etc. all lock you into their eco-system. What I needed is a "stand-alone" tool that will enable me to make the survey decentralized. And ask the person that is surveyed to send me the responses in a way that they or I desire. Either via secure encrypted file transfer, e-mail or any other way that suits my need. Without me needing to use a platform,  store data on that platform (Microsoft onedrive, google-drive etc.) 

This has led me to the idea of MarkdownForms. A decentralized, stand-alone survey tool that seemingly fits in-to the work flows of software engineers.

## Basic design

- Use basic markdown where possible.
- Annotate "input" fields inside the markdown
- Turn Markdown in-to a static website. 
- Turn input fields in-to user input.
- Store answers in cache.
- A "download" button enables to save the input data for sharing and/or analyzing.
- A import button enables continuing with the survey from other machine or at other moment.
