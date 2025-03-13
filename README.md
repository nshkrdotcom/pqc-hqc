# Secure HQC Implementation Guide

This repository contains comprehensive documentation on implementing the Hamming Quasi-Cyclic (HQC) post-quantum cryptography algorithm with a focus on side-channel resistance and security best practices. It includes detailed analyses and reviews of the HQC reference implementation, highlighting both strengths and vulnerabilities.

## Contents

### [1-claude.md](1-claude.md)
A complete technical reference guide covering:

- Core constant-time techniques
- Advanced mitigation strategies
- Implementation best practices
- Testing and verification methods
- NIST standards compliance
- Educational project enhancements

This document provides a deep dive into the practical aspects of secure cryptographic engineering, with specific examples and recommendations for implementing HQC. It serves as a foundational resource for developers.

### [2-grok.md](2-grok.md)
A security review and analysis of the HQC reference implementation, built upon the foundational knowledge in `1-claude.md`.  This document:

- Summarizes and prioritizes the vulnerabilities identified in the reference implementation.
- Provides specific code examples demonstrating the weaknesses.
- Offers concrete recommendations for mitigating the identified issues.
- Highlights the most critical areas that need immediate attention.
- Cites relevant research and NIST publications.

This document acts as a practical guide for developers to understand *where* the reference implementation needs improvement and *how* to address those issues.

### [security-review-of-hqc-claude-1.md](security-review-of-hqc-claude-1.md)
The initial, comprehensive security review of the HQC reference implementation produced by Claude. This document provides a detailed, line-by-line analysis of the codebase, identifying a wide range of potential vulnerabilities and areas for improvement. It forms the basis for the prioritized recommendations in `2-grok.md`.

### [security-review-of-hqc-claude-2.md](security-review-of-hqc-claude-2.md)
A follow-up security review by Claude, focusing on *additional* vulnerabilities discovered after a deeper analysis of the codebase. This document builds upon the findings of `security-review-of-hqc-claude-1.md`, uncovering more subtle and complex security issues.

### [security-review-of-hqc-gemini.md](security-review-of-hqc-gemini.md)
A separate security review of the HQC reference implementation performed by Google's Gemini model. This document provides an independent perspective on the codebase, highlighting vulnerabilities and offering recommendations. Comparing this review with the Claude reviews allows for a more comprehensive understanding of the implementation's security posture.

## Purpose

This documentation is intended for software developers, security engineers, students, and researchers working with post-quantum cryptography implementations, with particular focus on HQC. The multiple reviews provide a well-rounded and in-depth analysis, helping to guide the development of secure and robust HQC implementations.

Last updated: 2025-03-12
