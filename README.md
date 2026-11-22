# Palash Ranjan Roy

<img align="right" width="170" src="https://palashroy.me/images/palash_roy_headshot.jpg" alt="Palash Ranjan Roy, PhD researcher in Computer Science at the University of Saskatchewan"/>

**PhD researcher in Computer Science, University of Saskatchewan**<br/>
[Software Research Lab](https://srlab.usask.ca/) · [iSE Lab](https://ise.usask.ca/) · supervised by Dr. Kevin Schneider<br/>
<sub>Published as Palash Roy and Palash R. Roy · ORCID <a href="https://orcid.org/0000-0001-9470-4233">0000-0001-9470-4233</a></sub>

I study code clones, clone detection, LLMs for software engineering, model compression and model merging. My publications, tools and replication packages are at **[palashroy.me](https://palashroy.me/)**.

[![Website](https://img.shields.io/badge/palashroy.me-0f172a?style=flat-square)](https://palashroy.me)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-0f172a?style=flat-square)](https://scholar.google.com/citations?user=Vy_sw5UAAAAJ&hl=en)
[![ORCID](https://img.shields.io/badge/ORCID-0f172a?style=flat-square)](https://orcid.org/0000-0001-9470-4233)
[![dblp](https://img.shields.io/badge/dblp-0f172a?style=flat-square)](https://dblp.org/pid/355/4465.html)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0f172a?style=flat-square)](https://www.linkedin.com/in/palashranjanroy/)
[![Email](https://img.shields.io/badge/palash.roy%40usask.ca-0f172a?style=flat-square)](mailto:palash.roy@usask.ca)

<br clear="right"/>

> **Latest:** two papers at ASE 2026 ([research track](https://palashroy.me/publications/cross-domain-clone-detection-model-merging/), [tool track](https://palashroy.me/publications/mergese/)) and an [ACM SIGSOFT Distinguished Paper Award](https://palashroy.me/publications/carbon-taxed-transformers/) at FSE 2026.

## Research

<table>
  <tr>
    <td width="50%" valign="top">
      <b>Code clones in the LLM era</b><br/>
      Do clone detectors and benchmarks hold up when the code is written by AI?<br/><br/>
      <a href="https://palashroy.me/publications/classical-clone-detectors-ai-era/">ICSME '25</a> ·
      <a href="https://palashroy.me/publications/gptclonebench/">ICSME '23</a> ·
      <a href="https://palashroy.me/publications/llm-clone-generation-iwsc/">IWSC '23</a>
    </td>
    <td width="50%" valign="top">
      <b>Model merging for software engineering</b><br/>
      One model across clone domains, with no retraining: 93% of multi-task performance and up to 4× better on unseen AI-generated clones.<br/><br/>
      <a href="https://palashroy.me/publications/cross-domain-clone-detection-model-merging/">ASE '26</a> ·
      <a href="https://palashroy.me/publications/mergese/">ASE '26 Tool</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>Efficient, sustainable code models</b><br/>
      Compressing code transformers: up to 81% lower CO2 emissions while keeping about 98% of clone detection accuracy.<br/><br/>
      <a href="https://palashroy.me/publications/carbon-taxed-transformers/">FSE '26 · Distinguished Paper</a>
    </td>
    <td width="50%" valign="top">
      <b>Just-in-time clone refactoring</b><br/>
      Helping developers refactor clones as they write code.<br/><br/>
      <a href="https://palashroy.me/publications/jit-inclusive-clone-refactoring/">ICSME '25 DS · Best Doctoral Proposal</a>
    </td>
  </tr>
</table>

## Tools and benchmarks

| | | |
| :-- | :-- | :-- |
| **[MergeSE](https://github.com/srlabUsask/MergeSE)** | Training-free merging of Hugging Face encoder checkpoints for SE tasks. Two 124M-parameter models merge in under 5 seconds on a CPU. | [Live tool](https://mergese.usask.ca) · [Paper](https://palashroy.me/publications/mergese/) |
| **[GPTCloneBench](https://github.com/srlabUsask/GPTCloneBench)** | 37,149 semantic and 20,770 cross-language clone pairs in Java, C, C# and Python. | [Dataset](https://doi.org/10.5281/zenodo.8259987) · [Paper](https://palashroy.me/publications/gptclonebench/) |
| **[CTT](https://github.com/srlabUsask/CTT)** | Compression pipeline that cuts the memory, latency and carbon cost of code models. | [arXiv](https://arxiv.org/abs/2604.25903) · [Paper](https://palashroy.me/publications/carbon-taxed-transformers/) |
| **[CLEAR](https://github.com/srlabUsask/CLEAR)** | Clone refactoring support inside the developer's workflow. | [Paper](https://palashroy.me/publications/jit-inclusive-clone-refactoring/) |

## Selected publications

- **A Unified Model for Cross-Domain Clone Detection via Model Merging.** ASE 2026. [Summary](https://palashroy.me/publications/cross-domain-clone-detection-model-merging/) · [arXiv](https://arxiv.org/abs/2608.04215)
- **MergeSE: Post-Hoc Model Merging for Software Engineering Tasks Without Retraining.** ASE 2026 Tool Track. [Summary](https://palashroy.me/publications/mergese/) · [arXiv](https://arxiv.org/abs/2608.04181)
- **Carbon-Taxed Transformers: A Green Compression Pipeline for Overgrown Language Models.** FSE 2026, Distinguished Paper. [Summary](https://palashroy.me/publications/carbon-taxed-transformers/) · [arXiv](https://arxiv.org/abs/2604.25903)
- **Are Classical Clone Detectors Good Enough for the AI Era?** ICSME 2025. [Summary](https://palashroy.me/publications/classical-clone-detectors-ai-era/) · [arXiv](https://arxiv.org/abs/2509.25754)
- **GPTCloneBench: A Comprehensive Benchmark of Semantic Clones and Cross-Language Clones.** ICSME 2023. [Summary](https://palashroy.me/publications/gptclonebench/) · [arXiv](https://arxiv.org/abs/2308.13963)

[All publications](https://palashroy.me/publications/) · [Blog](https://palashroy.me/blog/) · [About](https://palashroy.me/about/)

---

<sub>Python · PyTorch · Hugging Face Transformers · ONNX · Flask · Docker · Treaty 6 Territory, Saskatoon</sub>
