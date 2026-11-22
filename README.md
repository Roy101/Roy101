### Palash Ranjan Roy

PhD researcher in computer science at the University of Saskatchewan ([SRLab](https://srlab.usask.ca/), [iSE Lab](https://ise.usask.ca/)).

I work on code clones, and lately on what happens to them now that so much code is written by LLMs. Two questions take up most of my time: do clone detectors still work on AI-generated code, and can we merge or compress code models so they generalize better and cost less to run?

**Things I've built**

- [MergeSE](https://github.com/srlabUsask/MergeSE): merges fine-tuned Hugging Face encoder checkpoints without retraining. Two 124M-parameter models merge in under 5 seconds on a CPU. There is a [hosted version](https://mergese.usask.ca) too. ASE 2026.
- [GPTCloneBench](https://github.com/srlabUsask/GPTCloneBench): 37,149 semantic and 20,770 cross-language clone pairs in Java, C, C# and Python. ICSME 2023.
- [CTT](https://github.com/srlabUsask/CTT): a compression pipeline for code models that cuts CO2 emissions by up to 81% while keeping about 98% of clone detection accuracy. FSE 2026, ACM SIGSOFT Distinguished Paper.
- [CLEAR](https://github.com/srlabUsask/CLEAR): clone refactoring suggestions while you write code. ICSME 2025 Doctoral Symposium.

Mostly Python, PyTorch and Hugging Face.

[Website](https://palashroy.me) · [Google Scholar](https://scholar.google.com/citations?user=Vy_sw5UAAAAJ&hl=en) · [LinkedIn](https://www.linkedin.com/in/palashranjanroy/) · palash.roy@usask.ca
