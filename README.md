## Hi there 👋

**RepoUnderstander/RepoUnderstander** is a ✨ Official implementation ✨ repository of paper "How to Understand Whole Repository?".

Recently, Large Language Model (LLM) based agents have advanced the significant development of Automatic Software Engineering (ASE). Although verified effectiveness, the designs of the existing methods mainly focus on the local information of codes, e.g., issues, classes, and functions, leading to limitations in capturing the global context and interdependencies within the software system. From the practical experiences of the human SE developers, we argue that an excellent understanding of the whole repository will be the critical path to ASE. However, understanding the whole repository raises various challenges, e.g., the extremely long code input, the noisy code information, the complex dependency relationships, etc. To this end, we develop a novel ASE method named RepoUnderstander by guiding agents to comprehensively understand the whole repositories. Specifically, we first condense the critical information of the whole repository into the repository knowledge graph in a top-to-down mode. In addition, a Monte Carlo tree search based repository exploration module is proposed to enhance the understanding of the whole repository. Subsequently, based on the repository-level knowledge, we instruct the agents to summarize, search API calls, and generate the patches to solve the real-world GitHub issues. Experiments show the superiority and effectiveness of RepoUnderstander. It achieves 5.3\% improvement on SWE-bench Lite. 

![image](https://github.com/RepoUnderstander/RepoUnderstander/assets/170649488/8740ff56-3bf4-41b5-846a-7972d20bd743)
