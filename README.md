# Model Custom LLM Agent Configuration For Idea Refinement

This repository contains an (experimental) model repository of files intended to provide the groundwork for provisioning a custom GPT agent (or another LLM) whose intended purpose is helping the user to iterate through the development of a technological idea. 

In my case, I chose my "Output Hub" project (managing GPT outputs at scale) which I've been working on for a few months. As the idea has run into some technical hurdles, I've broadened my thinking to different architectures - and this, I figured, was a perfect use-case for AI-assisted ideation!

The basic structure here is:

- The `ddl.sql` is a (real) DDL generated from a model Postgres for my project. Having this as a single saved piece of knowledge saves me from having to refer repetitively to specific tables and relationships in the design
-  `agent_config` is a versioned folder of configuration texts which are intended to round off the agent's understanding of the idea I'm working on. 

My idea and thinking was that together these two files - the database spec and the natural language description - would provide a good amount of context to steer the agent towards highly selective and relevant outputs to help me in this particular task.

## Use Case Statement

## Author

Daniel Rosehill  
(public at danielrosehill dot com)

## Licensing

This repository is licensed under CC-BY-4.0 (Attribution 4.0 International) 
[License](https://creativecommons.org/licenses/by/4.0/)

### Summary of the License
The Creative Commons Attribution 4.0 International (CC BY 4.0) license allows others to:
- **Share**: Copy and redistribute the material in any medium or format.
- **Adapt**: Remix, transform, and build upon the material for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the license terms.

#### License Terms
- **Attribution**: You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **No additional restrictions**: You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

For the full legal code, please visit the [Creative Commons website](https://creativecommons.org/licenses/by/4.0/legalcode).