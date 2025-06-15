# Awesome-CNUS

本仓库是为了收集信息安全四大会2025年发表论文所关注的领域,为读者提供近年的发文方向。

- C (ACM CCS)
- N (NDSS)
- U (USENIX Security)
- S (IEEE Symposium on Security and Privacy)

## Table of Contents 

- [Awesome-CNUS](#awesome-cnus)
- [Table of Contents](#table-of-contents)
- [Field](#field)
  - [Autonomous Driving](#autonomous-driving)
  - [Blockchain](#blockchain)
  - [Computer security](#computer-security)
  - [computer vision](#computer-vision)
  - [Differential Privacy](#differential-privacy)
  - [Diffusion Models](#diffusion-models)
  - [Distributed System security](#distributed-system-security)
  - [Ethereum](#ethereum)
  - [federated learning](#federated-learning)
  - [Fingerprint-based Authentication](#fingerprint-based-authentication)
  - [IoT security](#iot-security)
  - [LLM](#llm)
  - [machine learning](#machine-learning)
  - [metaverse](#metaverse)
  - [Mobile device security](#mobile-device-security)
  - [natural language processing](#natural-language-processing)
  - [Outsourcing](#outsourcing)
  - [Secure Multi-Party Computation](#secure-multi-party-computation)
  - [side-channel attack](#side-channel-attack)
  - [Trusted execution environment](#trusted-execution-environment)
  - [Transformer](#transformer)
  - [Web security](#web-security)

- [all paper](#all-paper)
  - [NDSS 2025](#ndss-2025)

-----------------------------------------

## Field

## Autonomous Driving

|Problem|Paper|conference|
|-|-|-|
|LiDAR Safety|[On the Realism of LiDAR Spoofing Attacks against Autonomous Driving Vehicle at High Speed and Long Distance](https://www.ndss-symposium.org/ndss-paper/on-the-realism-of-lidar-spoofing-attacks-against-autonomous-driving-vehicle-at-high-speed-and-long-distance/)|NDSS 2025|
|LiDAR Safety|[PhantomLiDAR: Cross-modality Signal Injection Attacks against LiDAR](https://www.ndss-symposium.org/ndss-paper/phantomlidar-cross-modality-signal-injection-attacks-against-lidar/)|NDSS 2025|
|Physical-World Adversarial Attacks|[Revisiting Physical-World Adversarial Attack on Traffic Sign Recognition: A Commercial Systems Perspective](https://www.ndss-symposium.org/ndss-paper/revisiting-physical-world-adversarial-attack-on-traffic-sign-recognition-a-commercial-systems-perspective/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Blockchain

|Problem|Paper|conference|
|-|-|-|
|Payment Channel Networks (PCNs) + <br> web security|[Horcrux: Synthesize, Split, Shift and Stay Alive; Preventing Channel Depletion via Universal and Enhanced Multi-hop Payments](https://www.ndss-symposium.org/ndss-paper/horcrux-synthesize-split-shift-and-stay-alive-preventing-channel-depletion-via-universal-and-enhanced-multi-hop-payments/)|NDSS 2025|
|sharding blockchain consensus|[Kronos: A Secure and Generic Sharding Blockchain Consensus with Optimized Overhead](https://www.ndss-symposium.org/ndss-paper/kronos-a-secure-and-generic-sharding-blockchain-consensus-with-optimized-overhead/)|NDSS 2025|
|blockchain throughput|[Manifoldchain: Maximizing Blockchain Throughput via Bandwidth-Clustered Sharding](https://www.ndss-symposium.org/ndss-paper/manifoldchain-maximizing-blockchain-throughput-via-bandwidth-clustered-sharding/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Computer security

|Problem|Paper|conference|
|-|-|-|
|OLE vulnerability|[Be Careful of What You Embed: Demystifying OLE Vulnerabilities](https://www.ndss-symposium.org/ndss-paper/be-careful-of-what-you-embed-demystifying-ole-vulnerabilities/)|NDSS 2025|
|Kernel Compartmentalization|[BULKHEAD: Secure, Scalable, and Efficient Kernel Compartmentalization with PKS](https://www.ndss-symposium.org/ndss-paper/bulkhead-secure-scalable-and-efficient-kernel-compartmentalization-with-pks/)|NDSS 2025|
|Malware Detection|[Careful About What App Promotion Ads Recommend! Detecting and Explaining Malware Promotion via App Promotion Graph](https://www.ndss-symposium.org/ndss-paper/careful-about-what-app-promotion-ads-recommend-detecting-and-explaining-malware-promotion-via-app-promotion-graph/)|NDSS 2025|
|CSS-based fingerprinting|[Cascading Spy Sheets: Exploiting the Complexity of Modern CSS for Email and Browser Fingerprinting](https://www.ndss-symposium.org/ndss-paper/cascading-spy-sheets-exploiting-the-complexity-of-modern-css-for-email-and-browser-fingerprinting/)|NDSS 2025|
|Bit-Flip Attack|[Compiled Models, Built-In Exploits: Uncovering Pervasive Bit-Flip Attack Surfaces in DNN Executables](https://www.ndss-symposium.org/ndss-paper/compiled-models-built-in-exploits-uncovering-pervasive-bit-flip-attack-surfaces-in-dnn-executables/)|NDSS 2025|
|Evasive Ransomware|[ERW-Radar: An Adaptive Detection System against Evasive Ransomware by Contextual Behavior Detection and Fine-grained Content Analysis](https://www.ndss-symposium.org/ndss-paper/erw-radar-an-adaptive-detection-system-against-evasive-ransomware-by-contextual-behavior-detection-and-fine-grained-content-analysis/)|NDSS 2025|
|memory disclosure vulnerabilities & <br> transient execution attacks|[LeakLess: Selective Data Protection against Memory Leakage Attacks for Serverless Platforms](https://www.ndss-symposium.org/ndss-paper/leakless-selective-data-protection-against-memory-leakage-attacks-for-serverless-platforms/)|NDSS 2025|
|firmware corpora|[Mens Sana In Corpore Sano: Sound Firmware Corpora for Vulnerability Research](https://www.ndss-symposium.org/ndss-paper/mens-sana-in-corpore-sano-sound-firmware-corpora-for-vulnerability-research/)|NDSS 2025|
|GPU driver vulnerability|[Moneta: Ex-Vivo GPU Driver Fuzzing by Recalling In-Vivo Execution States](https://www.ndss-symposium.org/ndss-paper/moneta-ex-vivo-gpu-driver-fuzzing-by-recalling-in-vivo-execution-states/)|NDSS 2025|
|Zero-knowledge compiler vulnerability|[MTZK: Testing and Exploring Bugs in Zero-Knowledge (ZK) Compilers](https://www.ndss-symposium.org/ndss-paper/mtzk-testing-and-exploring-bugs-in-zero-knowledge-zk-compilers/)|NDSS 2025|
|SSD vulnerability|[Secret Spilling Drive: Leaking User Behavior through SSD Contention](https://www.ndss-symposium.org/ndss-paper/secret-spilling-drive-leaking-user-behavior-through-ssd-contention/)|NDSS 2025|
|Executable Stack|[Too Subtle to Notice: Investigating Executable Stack Issues in Linux Systems](https://www.ndss-symposium.org/ndss-paper/too-subtle-to-notice-investigating-executable-stack-issues-in-linux-systems/)|NDSS 2025|
|Programming language security|[type++: Prohibiting Type Confusion with Inline Type Information](https://www.ndss-symposium.org/ndss-paper/type-prohibiting-type-confusion-with-inline-type-information/)|NDSS 2025|
|Binary software security|[VeriBin: Adaptive Verification of Patches at the Binary Level](https://www.ndss-symposium.org/ndss-paper/veribin-adaptive-verification-of-patches-at-the-binary-level/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## computer vision

|Problem|Paper|conference|
|-|-|-|
|Adversarial Attacks |[AlphaDog: No-Box Camouflage Attacks via Alpha Channel Oversight](https://www.ndss-symposium.org/ndss-paper/alphadog-no-box-camouflage-attacks-via-alpha-channel-oversight/)|NDSS 2025|
|Physical-World Adversarial Attacks|[Revisiting Physical-World Adversarial Attack on Traffic Sign Recognition: A Commercial Systems Perspective](https://www.ndss-symposium.org/ndss-paper/revisiting-physical-world-adversarial-attack-on-traffic-sign-recognition-a-commercial-systems-perspective/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Differential Privacy

|Problem|Paper|conference|
|-|-|-|
|Data flow accuracy|[Delay-allowed Differentially Private Data Stream Release](https://www.ndss-symposium.org/ndss-paper/delay-allowed-differentially-private-data-stream-release/)|NDSS 2025|
|Parameter estimation optimization|[Revisiting EM-based Estimation for Locally Differentially Private Protocols](https://www.ndss-symposium.org/ndss-paper/revisiting-em-based-estimation-for-locally-differentially-private-protocols/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Diffusion Models

|Problem|Paper|conference|
|-|-|-|
|Membership Inference attack|[Black-box Membership Inference Attacks against Fine-tuned Diffusion Models](https://www.ndss-symposium.org/ndss-paper/black-box-membership-inference-attacks-against-fine-tuned-diffusion-models/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Distributed System security

|Problem|Paper|conference|
|-|-|-|
|performance|[Rondo: Scalable and Reconfiguration-Friendly Randomness Beacon](https://www.ndss-symposium.org/ndss-paper/rondo-scalable-and-reconfiguration-friendly-randomness-beacon/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Ethereum

|Problem|Paper|conference|
|-|-|-|
|PTXPHISH phishing|[Dissecting Payload-based Transaction Phishing on Ethereum](https://www.ndss-symposium.org/ndss-paper/dissecting-payload-based-transaction-phishing-on-ethereum/)|NDSS 2025|
|anti-reentrancy patterns detection|[Silence False Alarms: Identifying Anti-Reentrancy Patterns on Ethereum to Refine Smart Contract Reentrancy Detection](https://www.ndss-symposium.org/ndss-paper/silence-false-alarms-identifying-anti-reentrancy-patterns-on-ethereum-to-refine-smart-contract-reentrancy-detection/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## federated learning

|Problem|Paper|conference|
|-|-|-|
|Gradient Inversion Attack|[CENSOR: Defense Against Gradient Inversion via Orthogonal Subspace Bayesian Sampling](https://www.ndss-symposium.org/ndss-paper/censor-defense-against-gradient-inversion-via-orthogonal-subspace-bayesian-sampling/)|NDSS 2025|
|Split Learning|[Passive Inference Attacks on Split Learning via Adversarial Regularization](https://www.ndss-symposium.org/ndss-paper/passive-inference-attacks-on-split-learning-via-adversarial-regularization/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Fingerprint-based Authentication

|Problem|Paper|conference|
|-|-|-|
|FpAuth+FpAPIs|[An Empirical Study on Fingerprint API Misuse with Lifecycle Analysis in Real-world Android Apps](https://www.ndss-symposium.org/ndss-paper/an-empirical-study-on-fingerprint-api-misuse-with-lifecycle-analysis-in-real-world-android-apps/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## IoT security

|Problem|Paper|conference|
|-|-|-|
|supply chain risk|[CHAOS: Exploiting Station Time Synchronization in 802.11 Networks](https://www.ndss-symposium.org/ndss-paper/chaos-exploiting-station-time-synchronization-in-802-11-networks/)|NDSS 2025|
|Sensors safety|[PowerRadio: Manipulate Sensor Measurement via Power GND Radiation](https://www.ndss-symposium.org/ndss-paper/powerradio-manipulate-sensor-measurement-via-power-gnd-radiation/)|NDSS 2025|
|Sensors safety|[ReThink: Reveal the Threat of Electromagnetic Interference on Power Inverters](https://www.ndss-symposium.org/ndss-paper/rethink-reveal-the-threat-of-electromagnetic-interference-on-power-inverters/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## LLM

|Problem|Paper|conference|
|-|-|-|
|API security <br> API Parameter Security Rule|[Generating API Parameter Security Rules with LLM for API Misuse Detection](https://www.ndss-symposium.org/ndss-paper/generating-api-parameter-security-rules-with-llm-for-api-misuse-detection/)|NDSS 2025|
|malicious shell commands|[RACONTEUR: A Knowledgeable, Insightful, and Portable LLM-Powered Shell Command Explainer](https://www.ndss-symposium.org/ndss-paper/raconteur-a-knowledgeable-insightful-and-portable-llm-powered-shell-command-explainer/)|NDSS 2025|
|The misuse of resource management API|[The Midas Touch: Triggering the Capability of LLMs for RM-API Misuse Detection](https://www.ndss-symposium.org/ndss-paper/the-midas-touch-triggering-the-capability-of-llms-for-rm-api-misuse-detection/)|NDSS 2025|
|LLM security|[The Philosopher’s Stone: Trojaning Plugins of Large Language Models](https://www.ndss-symposium.org/ndss-paper/the-philosophers-stone-trojaning-plugins-of-large-language-models/)|NDSS 2025|
|LLM security|[THEMIS: Regulating Textual Inversion for Personalized Concept Censorship](https://www.ndss-symposium.org/ndss-paper/themis-regulating-textual-inversion-for-personalized-concept-censorship/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## machine learning

|Problem|Paper|conference|
|-|-|-|
|Membership Inference Attack <br> Model Poisoning Attack|[A Method to Facilitate Membership Inference Attacks in Deep Learning Models](https://www.ndss-symposium.org/ndss-paper/a-method-to-facilitate-membership-inference-attacks-in-deep-learning-models/)|NDSS 2025|
|Adversarial Attacks|[AlphaDog: No-Box Camouflage Attacks via Alpha Channel Oversight](https://www.ndss-symposium.org/ndss-paper/alphadog-no-box-camouflage-attacks-via-alpha-channel-oversight/)|NDSS 2025|
|data leakage|[Automated Expansion of Privacy Data Taxonomy for Compliant Data Breach Notification](https://www.ndss-symposium.org/ndss-paper/automated-expansion-of-privacy-data-taxonomy-for-compliant-data-breach-notification/)|NDSS 2025|
|Bit-Flip Attack|[Compiled Models, Built-In Exploits: Uncovering Pervasive Bit-Flip Attack Surfaces in DNN Executables](https://www.ndss-symposium.org/ndss-paper/compiled-models-built-in-exploits-uncovering-pervasive-bit-flip-attack-surfaces-in-dnn-executables/)|NDSS 2025|
|Membership Inference attack|[Diffence: Fencing Membership Privacy With Diffusion Models](https://www.ndss-symposium.org/ndss-paper/diffence-fencing-membership-privacy-with-diffusion-models/)|NDSS 2025|
|Model Ownership Verification|[Explanation as a Watermark: Towards Harmless and Multi-bit Model Ownership Verification via Watermarking Feature Attribution](https://www.ndss-symposium.org/ndss-paper/explanation-as-a-watermark-towards-harmless-and-multi-bit-model-ownership-verification-via-watermarking-feature-attribution/)|NDSS 2025|
|Wireless channel data leakage|[Magmaw: Modality-Agnostic Adversarial Attacks on Machine Learning-Based Wireless Communication Systems](https://www.ndss-symposium.org/ndss-paper/magmaw-modality-agnostic-adversarial-attacks-on-machine-learning-based-wireless-communication-systems/)|NDSS 2025|
|unlearning|[Reinforcement Unlearning](https://www.ndss-symposium.org/ndss-paper/reinforcement-unlearning/)|NDSS 2025|
|unlearning|[TrajDeleter: Enabling Trajectory Forgetting in Offline Reinforcement Learning Agents](https://www.ndss-symposium.org/ndss-paper/trajdeleter-enabling-trajectory-forgetting-in-offline-reinforcement-learning-agents/)|NDSS 2025|
|data privacy|[Understanding Data Importance in Machine Learning Attacks: Does Valuable Data Pose Greater Harm?](https://www.ndss-symposium.org/ndss-paper/understanding-data-importance-in-machine-learning-attacks-does-valuable-data-pose-greater-harm/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## metaverse

|Problem|Paper|conference|
|-|-|-|
|Virtual faces|[A Key-Driven Framework for Identity-Preserving Face Anonymization](https://www.ndss-symposium.org/ndss-paper/a-key-driven-framework-for-identity-preserving-face-anonymization/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Mobile device security

|Problem|Paper|conference|
|-|-|-|
|security bugs|[MALintent: Coverage Guided Intent Fuzzing Framework for Android](https://www.ndss-symposium.org/ndss-paper/malintent-coverage-guided-intent-fuzzing-framework-for-android/)|NDSS 2025|
|User privacy|[The Power of Words: A Comprehensive Analysis of Rationales and Their Effects on Users' Permission Decisions](https://www.ndss-symposium.org/ndss-paper/the-power-of-words-a-comprehensive-analysis-of-rationales-and-their-effects-on-users-permission-decisions/)|NDSS 2025|
|mini-apps|[The Skeleton Keys: A Large Scale Analysis of Credential Leakage in Mini-apps](https://www.ndss-symposium.org/ndss-paper/the-skeleton-keys-a-large-scale-analysis-of-credential-leakage-in-mini-apps/)|NDSS 2025|
|ios user privacy|[Transparency or Information Overload? Evaluating Users’ Comprehension and Perceptions of the iOS App Privacy Report](https://www.ndss-symposium.org/ndss-paper/transparency-or-information-overload-evaluating-users-comprehension-and-perceptions-of-the-ios-app-privacy-report/)|NDSS 2025|
|Super App Security|[Understanding Miniapp Malware: Identification, Dissection, and Characterization](https://www.ndss-symposium.org/ndss-paper/understanding-miniapp-malware-identification-dissection-and-characterization/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## natural language processing

|Problem|Paper|conference|
|-|-|-|
|data leakage|[Automated Expansion of Privacy Data Taxonomy for Compliant Data Breach Notification](https://www.ndss-symposium.org/ndss-paper/automated-expansion-of-privacy-data-taxonomy-for-compliant-data-breach-notification/)|NDSS 2025|
|Dynamic Backdoor Attack|[CLIBE: Detecting Dynamic Backdoors in Transformer-based NLP Models](https://www.ndss-symposium.org/ndss-paper/clibe-detecting-dynamic-backdoors-in-transformer-based-nlp-models/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Outsourcing

|Problem|Paper|conference|
|-|-|-|
|web security|[Heimdall: Towards Risk-Aware Network Management Outsourcing](https://www.ndss-symposium.org/ndss-paper/heimdall-towards-risk-aware-network-management-outsourcing/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## radio frequency Sensing

|Problem|Paper|conference|
|-|-|-|
|Through-Wall Detection|[RadSee: See Your Handwriting Through Walls Using FMCW Radar](https://www.ndss-symposium.org/ndss-paper/radsee-see-your-handwriting-through-walls-using-fmcw-radar/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Secure Multi-Party Computation

|Problem|Paper|conference|
|-|-|-|
|Secure Inference|[BumbleBee: Secure Two-party Inference Framework for Large Transformers](https://www.ndss-symposium.org/ndss-paper/bumblebee-secure-two-party-inference-framework-for-large-transformers/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## side-channel attack

|Problem|Paper|conference|
|-|-|-|
|CPU caches side-channel attack|[A Systematic Evaluation of Novel and Existing Cache Side Channels](https://www.ndss-symposium.org/ndss-paper/a-systematic-evaluation-of-novel-and-existing-cache-side-channels/)|NDSS 2025|
|TCP hijacking attacks|[Off-Path TCP Hijacking in Wi-Fi Networks: A Packet-Size Side Channel Attack](https://www.ndss-symposium.org/ndss-paper/off-path-tcp-hijacking-in-wi-fi-networks-a-packet-size-side-channel-attack/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Trusted execution environment

|Problem|Paper|conference|
|-|-|-|
|TrustZone systems|[SCRUTINIZER: Towards Secure Forensics on Compromised TrustZone](https://www.ndss-symposium.org/ndss-paper/scrutinizer-towards-secure-forensics-on-compromised-trustzone/)|NDSS 2025|
|data security|[WAVEN: WebAssembly Memory Virtualization for Enclaves](https://www.ndss-symposium.org/ndss-paper/waven-webassembly-memory-virtualization-for-enclaves/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Transformer

|Problem|Paper|conference|
|-|-|-|
|Private Inference|[BumbleBee: Secure Two-party Inference Framework for Large Transformers](https://www.ndss-symposium.org/ndss-paper/bumblebee-secure-two-party-inference-framework-for-large-transformers/)|NDSS 2025|
|Dynamic Backdoor Attack|[CLIBE: Detecting Dynamic Backdoors in Transformer-based NLP Models](https://www.ndss-symposium.org/ndss-paper/clibe-detecting-dynamic-backdoors-in-transformer-based-nlp-models/)|NDSS 2025|
|Secure transformer inference|[Secure Transformer Inference Made Non-interactive](https://www.ndss-symposium.org/ndss-paper/secure-transformer-inference-made-non-interactive/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝

## Web security

|Problem|Paper|conference|
|-|-|-|
|SOP vulnerability|[Cross-Origin Web Attacks via HTTP/2 Server Push and Signed HTTP Exchange](https://www.ndss-symposium.org/ndss-paper/cross-origin-web-attacks-via-http-2-server-push-and-signed-http-exchange/)|NDSS 2025|
|Tracker Detection|[Duumviri: Detecting Trackers and Mixed Trackers with a Breakage Detector](https://www.ndss-symposium.org/ndss-paper/duumviri-detecting-trackers-and-mixed-trackers-with-a-breakage-detector/)|NDSS 2025|
|Evasive Ransomware|[Evasive Ransomware: A Case Study of the Evasion Tactics of the Black Basta Ransomware](https://www.ndss-symposium.org/ndss-paper/evasive-ransomware-a-case-study-of-the-evasion-tactics-of-the-black-basta-ransomware/)|NDSS 2025|
|web vulnerabilities|[EvoCrawl: Exploring Web Application Code and State using Evolutionary Search](https://www.ndss-symposium.org/ndss-paper/evocrawl-exploring-web-application-code-and-state-using-evolutionary-search/)|NDSS 2025|
|API security <br> API Parameter Security Rule|[Generating API Parameter Security Rules with LLM for API Misuse Detection](https://www.ndss-symposium.org/ndss-paper/generating-api-parameter-security-rules-with-llm-for-api-misuse-detection/)|NDSS 2025|
|cyber attacks|[Incorporating Gradients to Rules: Towards Lightweight, Adaptive Provenance-based Intrusion Detection](https://www.ndss-symposium.org/ndss-paper/incorporating-gradients-to-rules-towards-lightweight-adaptive-provenance-based-intrusion-detection/)|NDSS 2025|
|memory disclosure vulnerabilities & <br> transient execution attacks|[LeakLess: Selective Data Protection against Memory Leakage Attacks for Serverless Platforms](https://www.ndss-symposium.org/ndss-paper/leakless-selective-data-protection-against-memory-leakage-attacks-for-serverless-platforms/)|NDSS 2025|
|Wireless channel data leakage|[Magmaw: Modality-Agnostic Adversarial Attacks on Machine Learning-Based Wireless Communication Systems](https://www.ndss-symposium.org/ndss-paper/magmaw-modality-agnostic-adversarial-attacks-on-machine-learning-based-wireless-communication-systems/)|NDSS 2025|
|Cryptomining Detection|[MineShark: Cryptomining Traffic Detection at Scale](https://www.ndss-symposium.org/ndss-paper/mineshark-cryptomining-traffic-detection-at-scale/)|NDSS 2025|
|Misdirection Attack in abusing DUSS|[Misdirection of Trust: Demystifying the Abuse of Dedicated URL Shortening Service](https://www.ndss-symposium.org/ndss-paper/misdirection-of-trust-demystifying-the-abuse-of-dedicated-url-shortening-service/)|NDSS 2025|
|TCP hijacking attacks|[Off-Path TCP Hijacking in Wi-Fi Networks: A Packet-Size Side Channel Attack](https://www.ndss-symposium.org/ndss-paper/off-path-tcp-hijacking-in-wi-fi-networks-a-packet-size-side-channel-attack/)|NDSS 2025|
|malicious shell commands|[RACONTEUR: A Knowledgeable, Insightful, and Portable LLM-Powered Shell Command Explainer](https://www.ndss-symposium.org/ndss-paper/raconteur-a-knowledgeable-insightful-and-portable-llm-powered-shell-command-explainer/)|NDSS 2025|
|DoS attacks|[Redan: An Empirical Study on Remote DoS Attacks against NAT Networks](https://www.ndss-symposium.org/ndss-paper/redan-an-empirical-study-on-remote-dos-attacks-against-nat-networks/)|NDSS 2025|
|IP address allocation|[Secure IP Address Allocation at Cloud Scale](https://www.ndss-symposium.org/ndss-paper/secure-ip-address-allocation-at-cloud-scale/)|NDSS 2025|
|Content Management System security|[The (Un)usual Suspects – Studying Reasons for Lacking Updates in WordPress](https://www.ndss-symposium.org/ndss-paper/the-unusual-suspects-studying-reasons-for-lacking-updates-in-wordpress/)|NDSS 2025|
|The misuse of resource management API|[The Midas Touch: Triggering the Capability of LLMs for RM-API Misuse Detection](https://www.ndss-symposium.org/ndss-paper/the-midas-touch-triggering-the-capability-of-llms-for-rm-api-misuse-detection/)|NDSS 2025|
|Satellite communication security|[Time-varying Bottleneck Links in LEO Satellite Networks: Identification, Exploits, and Countermeasures](https://www.ndss-symposium.org/ndss-paper/time-varying-bottleneck-links-in-leo-satellite-networks-identification-exploits-and-countermeasures/)|NDSS 2025|
|Twitter security incident detection|[Tweezers: A Framework for Security Event Detection via Event Attribution-centric Tweet Embedding](https://www.ndss-symposium.org/ndss-paper/tweezers-a-framework-for-security-event-detection-via-event-attribution-centric-tweet-embedding/)|NDSS 2025|
|Great Firewall of China|[Wallbleed: A Memory Disclosure Vulnerability in the Great Firewall of China](https://www.ndss-symposium.org/ndss-paper/wallbleed-a-memory-disclosure-vulnerability-in-the-great-firewall-of-china/)|NDSS 2025|
|Node.js|[Welcome to Jurassic Park: A Comprehensive Study of Security Risks in Deno and its Ecosystem](https://www.ndss-symposium.org/ndss-paper/welcome-to-jurassic-park-a-comprehensive-study-of-security-risks-in-deno-and-its-ecosystem/)|NDSS 2025|

⬆️[Back to the directory](#table-of-contents)🔝




-------------

# all paper
## NDSS 2025
- [A Key-Driven Framework for Identity-Preserving Face Anonymization](https://www.ndss-symposium.org/ndss-paper/a-key-driven-framework-for-identity-preserving-face-anonymization/)
- [A Method to Facilitate Membership Inference Attacks in Deep Learning Models](https://www.ndss-symposium.org/ndss-paper/a-method-to-facilitate-membership-inference-attacks-in-deep-learning-models/)
- [A Systematic Evaluation of Novel and Existing Cache Side Channels](https://www.ndss-symposium.org/ndss-paper/a-systematic-evaluation-of-novel-and-existing-cache-side-channels/)
- [AlphaDog: No-Box Camouflage Attacks via Alpha Channel Oversight](https://www.ndss-symposium.org/ndss-paper/alphadog-no-box-camouflage-attacks-via-alpha-channel-oversight/)
- [An Empirical Study on Fingerprint API Misuse with Lifecycle Analysis in Real-world Android Apps](https://www.ndss-symposium.org/ndss-paper/an-empirical-study-on-fingerprint-api-misuse-with-lifecycle-analysis-in-real-world-android-apps/)
- [Automated Expansion of Privacy Data Taxonomy for Compliant Data Breach Notification](https://www.ndss-symposium.org/ndss-paper/automated-expansion-of-privacy-data-taxonomy-for-compliant-data-breach-notification/)
- [Be Careful of What You Embed: Demystifying OLE Vulnerabilities](https://www.ndss-symposium.org/ndss-paper/be-careful-of-what-you-embed-demystifying-ole-vulnerabilities/)
- [Black-box Membership Inference Attacks against Fine-tuned Diffusion Models](https://www.ndss-symposium.org/ndss-paper/black-box-membership-inference-attacks-against-fine-tuned-diffusion-models/)
- [BULKHEAD: Secure, Scalable, and Efficient Kernel Compartmentalization with PKS](https://www.ndss-symposium.org/ndss-paper/bulkhead-secure-scalable-and-efficient-kernel-compartmentalization-with-pks/)
- [BumbleBee: Secure Two-party Inference Framework for Large Transformers](https://www.ndss-symposium.org/ndss-paper/bumblebee-secure-two-party-inference-framework-for-large-transformers/)
- [Careful About What App Promotion Ads Recommend! Detecting and Explaining Malware Promotion via App Promotion Graph](https://www.ndss-symposium.org/ndss-paper/careful-about-what-app-promotion-ads-recommend-detecting-and-explaining-malware-promotion-via-app-promotion-graph/)
- [Cascading Spy Sheets: Exploiting the Complexity of Modern CSS for Email and Browser Fingerprinting](https://www.ndss-symposium.org/ndss-paper/cascading-spy-sheets-exploiting-the-complexity-of-modern-css-for-email-and-browser-fingerprinting/)
- [CENSOR: Defense Against Gradient Inversion via Orthogonal Subspace Bayesian Sampling](https://www.ndss-symposium.org/ndss-paper/censor-defense-against-gradient-inversion-via-orthogonal-subspace-bayesian-sampling/)
- [CHAOS: Exploiting Station Time Synchronization in 802.11 Networks](https://www.ndss-symposium.org/ndss-paper/chaos-exploiting-station-time-synchronization-in-802-11-networks/)
- [CLIBE: Detecting Dynamic Backdoors in Transformer-based NLP Models](https://www.ndss-symposium.org/ndss-paper/clibe-detecting-dynamic-backdoors-in-transformer-based-nlp-models/)
- [Compiled Models, Built-In Exploits: Uncovering Pervasive Bit-Flip Attack Surfaces in DNN Executables](https://www.ndss-symposium.org/ndss-paper/compiled-models-built-in-exploits-uncovering-pervasive-bit-flip-attack-surfaces-in-dnn-executables/)
- [Cross-Origin Web Attacks via HTTP/2 Server Push and Signed HTTP Exchange](https://www.ndss-symposium.org/ndss-paper/cross-origin-web-attacks-via-http-2-server-push-and-signed-http-exchange/)
- [Delay-allowed Differentially Private Data Stream Release](https://www.ndss-symposium.org/ndss-paper/delay-allowed-differentially-private-data-stream-release/)
- [Diffence: Fencing Membership Privacy With Diffusion Models](https://www.ndss-symposium.org/ndss-paper/diffence-fencing-membership-privacy-with-diffusion-models/)
- [Dissecting Payload-based Transaction Phishing on Ethereum](https://www.ndss-symposium.org/ndss-paper/dissecting-payload-based-transaction-phishing-on-ethereum/)
- [Duumviri: Detecting Trackers and Mixed Trackers with a Breakage Detector](https://www.ndss-symposium.org/ndss-paper/duumviri-detecting-trackers-and-mixed-trackers-with-a-breakage-detector/)
- [ERW-Radar: An Adaptive Detection System against Evasive Ransomware by Contextual Behavior Detection and Fine-grained Content Analysis](https://www.ndss-symposium.org/ndss-paper/erw-radar-an-adaptive-detection-system-against-evasive-ransomware-by-contextual-behavior-detection-and-fine-grained-content-analysis/)
- [EvoCrawl: Exploring Web Application Code and State using Evolutionary Search](https://www.ndss-symposium.org/ndss-paper/evocrawl-exploring-web-application-code-and-state-using-evolutionary-search/)
- [Explanation as a Watermark: Towards Harmless and Multi-bit Model Ownership Verification via Watermarking Feature Attribution](https://www.ndss-symposium.org/ndss-paper/explanation-as-a-watermark-towards-harmless-and-multi-bit-model-ownership-verification-via-watermarking-feature-attribution/)
- [Generating API Parameter Security Rules with LLM for API Misuse Detection](https://www.ndss-symposium.org/ndss-paper/generating-api-parameter-security-rules-with-llm-for-api-misuse-detection/)
- [Heimdall: Towards Risk-Aware Network Management Outsourcing](https://www.ndss-symposium.org/ndss-paper/heimdall-towards-risk-aware-network-management-outsourcing/)
- [Horcrux: Synthesize, Split, Shift and Stay Alive; Preventing Channel Depletion via Universal and Enhanced Multi-hop Payments](https://www.ndss-symposium.org/ndss-paper/horcrux-synthesize-split-shift-and-stay-alive-preventing-channel-depletion-via-universal-and-enhanced-multi-hop-payments/)
- [Incorporating Gradients to Rules: Towards Lightweight, Adaptive Provenance-based Intrusion Detection](https://www.ndss-symposium.org/ndss-paper/incorporating-gradients-to-rules-towards-lightweight-adaptive-provenance-based-intrusion-detection/)
- [Kronos: A Secure and Generic Sharding Blockchain Consensus with Optimized Overhead](https://www.ndss-symposium.org/ndss-paper/kronos-a-secure-and-generic-sharding-blockchain-consensus-with-optimized-overhead/)
- [LeakLess: Selective Data Protection against Memory Leakage Attacks for Serverless Platforms](https://www.ndss-symposium.org/ndss-paper/leakless-selective-data-protection-against-memory-leakage-attacks-for-serverless-platforms/)
- [Magmaw: Modality-Agnostic Adversarial Attacks on Machine Learning-Based Wireless Communication Systems](https://www.ndss-symposium.org/ndss-paper/magmaw-modality-agnostic-adversarial-attacks-on-machine-learning-based-wireless-communication-systems/)
- [MALintent: Coverage Guided Intent Fuzzing Framework for Android](https://www.ndss-symposium.org/ndss-paper/malintent-coverage-guided-intent-fuzzing-framework-for-android/)
- [Manifoldchain: Maximizing Blockchain Throughput via Bandwidth-Clustered Sharding](https://www.ndss-symposium.org/ndss-paper/manifoldchain-maximizing-blockchain-throughput-via-bandwidth-clustered-sharding/)
- [Mens Sana In Corpore Sano: Sound Firmware Corpora for Vulnerability Research](https://www.ndss-symposium.org/ndss-paper/mens-sana-in-corpore-sano-sound-firmware-corpora-for-vulnerability-research/)
- [MineShark: Cryptomining Traffic Detection at Scale](https://www.ndss-symposium.org/ndss-paper/mineshark-cryptomining-traffic-detection-at-scale/)
- [Misdirection of Trust: Demystifying the Abuse of Dedicated URL Shortening Service](https://www.ndss-symposium.org/ndss-paper/misdirection-of-trust-demystifying-the-abuse-of-dedicated-url-shortening-service/)
- [Moneta: Ex-Vivo GPU Driver Fuzzing by Recalling In-Vivo Execution States](https://www.ndss-symposium.org/ndss-paper/moneta-ex-vivo-gpu-driver-fuzzing-by-recalling-in-vivo-execution-states/)
- [MTZK: Testing and Exploring Bugs in Zero-Knowledge (ZK) Compilers](https://www.ndss-symposium.org/ndss-paper/mtzk-testing-and-exploring-bugs-in-zero-knowledge-zk-compilers/)
- [Off-Path TCP Hijacking in Wi-Fi Networks: A Packet-Size Side Channel Attack](https://www.ndss-symposium.org/ndss-paper/off-path-tcp-hijacking-in-wi-fi-networks-a-packet-size-side-channel-attack/)
- [On the Realism of LiDAR Spoofing Attacks against Autonomous Driving Vehicle at High Speed and Long Distance](https://www.ndss-symposium.org/ndss-paper/on-the-realism-of-lidar-spoofing-attacks-against-autonomous-driving-vehicle-at-high-speed-and-long-distance/)
- [Passive Inference Attacks on Split Learning via Adversarial Regularization](https://www.ndss-symposium.org/ndss-paper/passive-inference-attacks-on-split-learning-via-adversarial-regularization/)
- [PhantomLiDAR: Cross-modality Signal Injection Attacks against LiDAR](https://www.ndss-symposium.org/ndss-paper/phantomlidar-cross-modality-signal-injection-attacks-against-lidar/)
- [PowerRadio: Manipulate Sensor Measurement via Power GND Radiation](https://www.ndss-symposium.org/ndss-paper/powerradio-manipulate-sensor-measurement-via-power-gnd-radiation/)
- [RACONTEUR: A Knowledgeable, Insightful, and Portable LLM-Powered Shell Command Explainer](https://www.ndss-symposium.org/ndss-paper/raconteur-a-knowledgeable-insightful-and-portable-llm-powered-shell-command-explainer/)
- [RadSee: See Your Handwriting Through Walls Using FMCW Radar](https://www.ndss-symposium.org/ndss-paper/radsee-see-your-handwriting-through-walls-using-fmcw-radar/)
- [ReDAN: An Empirical Study on Remote DoS Attacks against NAT Networks](https://www.ndss-symposium.org/ndss-paper/redan-an-empirical-study-on-remote-dos-attacks-against-nat-networks/)
- [Reinforcement Unlearning](https://www.ndss-symposium.org/ndss-paper/reinforcement-unlearning/)
- [ReThink: Reveal the Threat of Electromagnetic Interference on Power Inverters](https://www.ndss-symposium.org/ndss-paper/rethink-reveal-the-threat-of-electromagnetic-interference-on-power-inverters/)
- [Revisiting EM-based Estimation for Locally Differentially Private Protocols](https://www.ndss-symposium.org/ndss-paper/revisiting-em-based-estimation-for-locally-differentially-private-protocols/)
- [Revisiting Physical-World Adversarial Attack on Traffic Sign Recognition: A Commercial Systems Perspective](https://www.ndss-symposium.org/ndss-paper/revisiting-physical-world-adversarial-attack-on-traffic-sign-recognition-a-commercial-systems-perspective/)
- [Rondo: Scalable and Reconfiguration-Friendly Randomness Beacon](https://www.ndss-symposium.org/ndss-paper/rondo-scalable-and-reconfiguration-friendly-randomness-beacon/)
- [SCRUTINIZER: Towards Secure Forensics on Compromised TrustZone](https://www.ndss-symposium.org/ndss-paper/scrutinizer-towards-secure-forensics-on-compromised-trustzone/)
- [Secret Spilling Drive: Leaking User Behavior through SSD Contention](https://www.ndss-symposium.org/ndss-paper/secret-spilling-drive-leaking-user-behavior-through-ssd-contention/)
- [Secure IP Address Allocation at Cloud Scale](https://www.ndss-symposium.org/ndss-paper/secure-ip-address-allocation-at-cloud-scale/)
- [Secure Transformer Inference Made Non-interactive](https://www.ndss-symposium.org/ndss-paper/secure-transformer-inference-made-non-interactive/)
- [Silence False Alarms: Identifying Anti-Reentrancy Patterns on Ethereum to Refine Smart Contract Reentrancy Detection](https://www.ndss-symposium.org/ndss-paper/silence-false-alarms-identifying-anti-reentrancy-patterns-on-ethereum-to-refine-smart-contract-reentrancy-detection/)
- [The (Un)usual Suspects – Studying Reasons for Lacking Updates in WordPress](https://www.ndss-symposium.org/ndss-paper/the-unusual-suspects-studying-reasons-for-lacking-updates-in-wordpress/)
- [The Midas Touch: Triggering the Capability of LLMs for RM-API Misuse Detection](https://www.ndss-symposium.org/ndss-paper/the-midas-touch-triggering-the-capability-of-llms-for-rm-api-misuse-detection/)
- [The Philosopher’s Stone: Trojaning Plugins of Large Language Models](https://www.ndss-symposium.org/ndss-paper/the-philosophers-stone-trojaning-plugins-of-large-language-models/)
- [The Power of Words: A Comprehensive Analysis of Rationales and Their Effects on Users' Permission Decisions](https://www.ndss-symposium.org/ndss-paper/the-power-of-words-a-comprehensive-analysis-of-rationales-and-their-effects-on-users-permission-decisions/)
- [The Skeleton Keys: A Large Scale Analysis of Credential Leakage in Mini-apps](https://www.ndss-symposium.org/ndss-paper/the-skeleton-keys-a-large-scale-analysis-of-credential-leakage-in-mini-apps/)
- [THEMIS: Regulating Textual Inversion for Personalized Concept Censorship](https://www.ndss-symposium.org/ndss-paper/themis-regulating-textual-inversion-for-personalized-concept-censorship/)
- [Time-varying Bottleneck Links in LEO Satellite Networks: Identification, Exploits, and Countermeasures](https://www.ndss-symposium.org/ndss-paper/time-varying-bottleneck-links-in-leo-satellite-networks-identification-exploits-and-countermeasures/)
- [Too Subtle to Notice: Investigating Executable Stack Issues in Linux Systems](https://www.ndss-symposium.org/ndss-paper/too-subtle-to-notice-investigating-executable-stack-issues-in-linux-systems/)
- [TrajDeleter: Enabling Trajectory Forgetting in Offline Reinforcement Learning Agents](https://www.ndss-symposium.org/ndss-paper/trajdeleter-enabling-trajectory-forgetting-in-offline-reinforcement-learning-agents/)
- [Transparency or Information Overload? Evaluating Users’ Comprehension and Perceptions of the iOS App Privacy Report](https://www.ndss-symposium.org/ndss-paper/transparency-or-information-overload-evaluating-users-comprehension-and-perceptions-of-the-ios-app-privacy-report/)
- [Tweezers: A Framework for Security Event Detection via Event Attribution-centric Tweet Embedding](https://www.ndss-symposium.org/ndss-paper/tweezers-a-framework-for-security-event-detection-via-event-attribution-centric-tweet-embedding/)
- [type++: Prohibiting Type Confusion with Inline Type Information](https://www.ndss-symposium.org/ndss-paper/type-prohibiting-type-confusion-with-inline-type-information/)
- [Understanding Data Importance in Machine Learning Attacks: Does Valuable Data Pose Greater Harm?](https://www.ndss-symposium.org/ndss-paper/understanding-data-importance-in-machine-learning-attacks-does-valuable-data-pose-greater-harm/)
- [Understanding Miniapp Malware: Identification, Dissection, and Characterization](https://www.ndss-symposium.org/ndss-paper/understanding-miniapp-malware-identification-dissection-and-characterization/)
- [VeriBin: Adaptive Verification of Patches at the Binary Level](https://www.ndss-symposium.org/ndss-paper/veribin-adaptive-verification-of-patches-at-the-binary-level/)
- [Wallbleed: A Memory Disclosure Vulnerability in the Great Firewall of China](https://www.ndss-symposium.org/ndss-paper/wallbleed-a-memory-disclosure-vulnerability-in-the-great-firewall-of-china/)
- [WAVEN: WebAssembly Memory Virtualization for Enclaves](https://www.ndss-symposium.org/ndss-paper/waven-webassembly-memory-virtualization-for-enclaves/)
- [Welcome to Jurassic Park: A Comprehensive Study of Security Risks in Deno and its Ecosystem](https://www.ndss-symposium.org/ndss-paper/welcome-to-jurassic-park-a-comprehensive-study-of-security-risks-in-deno-and-its-ecosystem/)