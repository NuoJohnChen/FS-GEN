# FS-GEN
## Abstract
Large Language Models (LLMs) demonstrate impressive performance in diverse applications, yet they face significant drawbacks, including high inference latency, expensive training cost, and generation of hallucination. Collaborative decoding between large and small language models (SLMs) offers a novel approach to address these challenges. Inspired by dual-process cognitive theory, we integrate these methods into a unified framework termed Fast and Slow Generating (FS-GEN). This paper explores several techniques within the FS-GEN framework, including speculative decoding, contrastive decoding, and emulator or proxy fine-tuning. We provide a comprehensive analysis of these methodologies, offering insights into their similarities and differences under this framework. Our study delves into the differential knowledge capabilities of LLMs versus SLMs through the FS-GEN lens, revealing that fewer than 20\% of collaborative interactions are required across various methods. These interactions adhere to a scaling law relative to the parameter ratios, thereby facilitating predictable collaboration. Furthermore, we investigate the specific positions where collaboration is most effective from an uncertainty perspective, yielding novel insights that could refine FS-GEN methods. Our findings reveal that the essential difference between models of different sizes lies in the uncertainty of the next token prediction, where interventions by larger models are most needed to assist the smaller ones.