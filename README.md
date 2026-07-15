## README

This is for releasing the source code of the paper [SAFEGuard: Detect Optimization-Based Jailbreak Atacks Through Harmful Semantic Analysis and Fluency Measurement](https://...)

### Abstract

Despite the significant efforts devoted to aligning large language models (LLMs) with human
values and ensuring safe deployment, recent work has revealed that LLMs remain vulnerable
to adversarial jailbreak attacks that can bypass safety guardrails and elicit harmful responses.
Many defense methods are proposed to detect jailbreaks but they are limited in their effectiveness
to counter wide-range optimization based jailbreak mechanisms that can yield highly fluency-optimized
or harmful semantic obfuscated prompts. To tackle this challenge, we propose a unified detection framework
SAFEGuard—which incorporates a hybrid fluency measurement based on cross-layer distribution distance
and perplexity, and the analysis of harmful semantics through gradient matching. Our method is grounded
in a paramount observation: high fluency prompts maintain their malicious intention close to harmful prompts
while harmful semantic obfuscated prompts often inject gibberish token sequences. 
Our evaluation demonstrates that SAFEGuard consistently outperforms state-of-the-art baselines and 
achieves significant improvement in accuracy across different optimization-based jailbreaks. This
underscores the effectiveness of SAFEGuard against evolving jailbreak attacks.


If you find our research useful for your work please cite:
```
@article{Vo2026
  author    = {Quoc Viet Vo, Trung Le, Damith R. and , Ehsan A.},
  title     = {SAFEGuard: Detect Optimization-Based Jailbreak Atacks Through Harmful Semantic Analysis and Fluency Measurement},
  journal   = {EMNLP},
  year      = {2026},
}
```

# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
