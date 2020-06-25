# [Placeholder name]

Placeholder is an Insight initiative that challenges Fellows to experiment with the latest cryptographic developments, creative protocol design, and extremely secure distributed system design, while collaborating on a large codebase in a faux-production environment. 

The underlying framework will initially focus on storage and transfer of value, with every precaution taken to ensure privacy. 

**Please note: Placeholder is an educational experiment, and NOT intended for use in production.** Placeholder has not been audited, there are no security guarantees, and you should not ascribe any value to the tokens. To provide the best privacy, Placeholder may adopt cryptography with system requirements that preclude deployment until a future generation of consumer devices has sufficient resources. We hope that this experiment provides results that are useful for other ecosystems, and we encourage you to audit and adopt any features from our open-source codebase.

## Principles:

-  **Privacy over performance.** Slower verification times and bigger transactions are the price of privacy. 
-  **Enforce all features in the protocol as consensus rules.** Features implemented in core txn/block generation but not protocol verification creates software fingerprinting heuristics.
-  **Encrypt all fields when possible.** Chain analysis algorithms love plaintext data. Privacy coins should not.
-  **Anything plaintext must be bounded and quantized.** (For example, a power of 2^N for 4 < N < 16)
-  **Basic research is crucial, never be afraid to ask a question.** Given the exponential increase in processsing power and bandwidth for residential and commercial devices, it is useful to study tomorrow's solutions even if they're not performant toady.
-  **Build for tomorrow’s adversaries.** Due to the dire threat of retrospective deanonymization, transactions should remain private against future generations of statistical and cryptographic analyses.
-  **No devotion to parameters.** Any parameter or protocol should be subject to continuous introspection, and changed if circumstances or models suggest that a different value would improve network performance. In other words, every algorithm or value is subject to future optimization.
-  **Always deploy the best technology.** Avoid ossification, and always integrate the most secure technology. 
-  **Compliance mechanisms should preserve privacy.** A variety of privacy levels/models should be considered (e.g. all-private, user/issuer differential privacy, semi-permissioned issuance, etc)
