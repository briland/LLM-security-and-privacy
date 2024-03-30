# LLM Security and Privacy

A curated list of papers and tools covering [LLM threats](https://github.com/topics/llm-threats) and [vulnerabilities](https://github.com/topics/llm-vulnerabilities), both from a [security](https://github.com/topics/llm-security) and [privacy](https://github.com/topics/llm-privacy) standpoint. Summaries, key takeaway points, and additional details for each paper are found in the [paper-summaries](./paper-summaries) folder. 

[main.bib](./main.bib) file contains the latest citations of the papers listed here.

<p align="center">
  <img src="./images/taxonomy.png" alt="A taxonomy of security and privacy threats against deep learning models and consecutively LLMs" style="width:100%">
  <b>Overview Figure:</b> A taxonomy of current security and privacy threats against deep learning models and consecutively Large Language Models (LLMs).
</p>

## Table of Contents

* [Papers](#papers)
* [Frameworks & Taxonomies](#frameworks--taxonomies)
* [Tools](#tools)
* [News Articles, Blog Posts, and Talks](#news-articles-blog-posts-and-talks)
* [Contributing](#contributing)
* [Contact](#contact)

## Papers

| No. | Paper Title | Venue | Year | Category | Code | Summary |
| --- | ----------- | ----- | ---- | -------- | ---- | ------- |
| 1.  | [InjectAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents](https://arxiv.org/pdf/2403.02691.pdf) | pre-print | 2024 | Prompt Injection | N/A | TBD |
| 2.  | [LLM Agents can Autonomously Hack Websites](https://arxiv.org/pdf/2402.06664.pdf) | pre-print | 2024 | Applications | N/A | TBD |
| 3.  | [An Overview of Catastrophic AI Risks](https://arxiv.org/pdf/2306.12001.pdf) | pre-print | 2023 | General | N/A | TBD |
| 4.  | [Use of LLMs for Illicit Purposes: Threats, Prevention Measures, and Vulnerabilities](https://arxiv.org/pdf/2308.12833.pdf) | pre-print | 2023 | General | N/A | TBD |
| 5.  | [LLM Censorship: A Machine Learning Challenge or a Computer Security Problem?](https://arxiv.org/pdf/2307.10719.pdf) | pre-print | 2023 | General | N/A | TBD |
| 6.  | [Beyond the Safeguards: Exploring the Security Risks of ChatGPT](https://arxiv.org/pdf/2305.08005.pdf) | pre-print | 2023 | General | N/A | TBD |
| 7.  | [Prompt Injection attack against LLM-integrated Applications](https://arxiv.org/pdf/2306.05499.pdf) | pre-print | 2023 | Prompt Injection | N/A | TBD |
| 8.  | [Identifying and Mitigating the Security Risks of Generative AI](https://arxiv.org/pdf/2308.14840.pdf) | pre-print | 2023 | General | N/A | TBD |
| 9.  | [PassGPT: Password Modeling and (Guided) Generation with Large Language Models](https://arxiv.org/pdf/2306.01545.pdf) | [ESORICS](https://esorics2023.org/program/accepted_papers/) | 2023 | Applications | [![Code](https://img.shields.io/badge/GitHub-black?logo=github&logoColor=white)](https://github.com/javirandor/passgpt) | TBD |
| 10.  | [Harnessing GPT-4 for generation of cybersecurity GRC policies: A focus on ransomware attack mitigation](https://www.sciencedirect.com/science/article/pii/S0167404823003346) | [Computers \& Security](https://www.sciencedirect.com/journal/computers-and-security) | 2023 | Applications | N/A | TBD | 
| 11.  | [Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/pdf/2302.12173.pdf) | pre-print | 2023 | Prompt Injection | [![Code](https://img.shields.io/badge/GitHub-black?logo=github&logoColor=white)](https://github.com/greshake/llm-security) | TBD |
| 12.  | [Examining Zero-Shot Vulnerability Repair with Large Language Models](https://arxiv.org/pdf/2112.02125.pdf) | [IEEE S&P](https://www.ieee-security.org/TC/SP2023/program-papers.html) | 2023 | Applications | N/A | TBD | 
| 13.  | [LLM Platform Security: Applying a Systematic Evaluation Framework to OpenAI's ChatGPT Plugins](https://arxiv.org/pdf/2309.10254.pdf) | pre-print | 2023 | General | N/A | TBD |
| 14.  | [Chain-of-Verification Reduces Hallucination in Large Language Models](https://arxiv.org/pdf/2309.11495.pdf) | pre-print | 2023 | Hallucinations | N/A | TBD |
| 15.  | [Pop Quiz! Can a Large Language Model Help With Reverse Engineering?](https://arxiv.org/pdf/2202.01142.pdf) | pre-print | 2022 | Applications | N/A | TBD |
| 16.  | [Extracting Training Data from Large Language Models](https://www.usenix.org/system/files/sec21-carlini-extracting.pdf) | [Usenix Security](https://www.usenix.org/conference/usenixsecurity21/technical-sessions) | 2021 | Data Extraction | [![Code](https://img.shields.io/badge/GitHub-black?logo=github&logoColor=white)](https://github.com/ftramer/LM_Memorization) | TBD |

## Frameworks & Taxonomies

* [OWASP Top 10 for Large Language Model Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
* [MITRE ATLAS (Adversarial Threat Landscape for Artificial-Intelligence Systems)](https://atlas.mitre.org/)
* [NIST AI 100-2 E2023: Adversarial Machine Learning: A Taxonomy and Terminology of Attacks and Mitigations](https://csrc.nist.gov/pubs/ai/100/2/e2023/ipd)

## Tools

* [Arsenal - CALDERA Plugin](https://github.com/mitre-atlas/arsenal)
* [Vigil - Prompt injection detection](https://github.com/deadbits/vigil-llm)

## News Articles, Blog Posts, and Talks

* [Is Generative AI Dangerous?](https://podcasts.apple.com/us/podcast/malicious-life/id1252417787?i=1000625300252)
* [Adversarial examples in the age of ChatGPT](https://spylab.ai/blog/chatbot-adversarial-examples/)
* [LLMs in Security: Demos vs Deployment?](https://moyix.net/~moyix/NAS_Cyber_Resilience_Aug2023_Dolan-Gavitt.pdf)
* [Free AI Programs Prone to Security Risks, Researchers Say](https://www.bloomberg.com/news/articles/2023-03-29/free-ai-programs-prone-to-security-risks-researchers-say)
* [Why 'Good AI' Is Likely The Antidote To The New Era Of AI Cybercrime](https://www.forbes.com/sites/forbestechcouncil/2023/03/02/why-good-ai-is-likely-the-antidote-to-the-new-era-of-ai-cybercrime/)
* [Meet PassGPT, the AI Trained on Millions of Leaked Passwords](https://decrypt.co/144004/meet-passgpt-ai-trained-millions-leaked-passwords)

## Contributing

If you are interested in contributing to this repository, please see [CONTRIBUTING.md](./CONTRIBUTING.md) for details on the guidelines.

A list of current contributors is found [HERE](./contributors.md).

## Contact

For any questions regarding this repository and/or potential (research) collaborations please contact [Briland Hitaj](mailto:briland.hitaj@sri.com).
