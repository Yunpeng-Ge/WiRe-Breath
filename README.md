# WiRe-Breath (Submitted)
## Overview

**WiRe-Breath** is a WiFi-based real-time respiratory monitoring framework designed to offer continuous, non-invasive tracking of breathing patterns. Our primary goal is to enable both researchers and practitioners to integrate this technology into diverse applications, promoting broader discussions and potential collaborations in the community.

## Purpose

- **Non-Intrusive Monitoring**  
  Uses off-the-shelf WiFi equipment to collect respiratory data without disturbing the user.  
- **Real-Time Performance**  
  Provides near-instantaneous breathing rate estimations and apnea alerts to assist in daily healthcare and potential clinical evaluations.  
- **Long-Term Sustainability**  
  Minimizes interference with network performance and lowers energy consumption, making the system feasible for extended monitoring.

## System Design (High-Level)

1. **Signal Collection**  
   Periodic WiFi signals are passively received by the monitoring device with no extra burden placed on the existing network.  
2. **Processing Pipeline**  
   Our framework employs robust preprocessing and motion-enhancement modules to extract subtle respiratory features from noisy environments.  
3. **Respiratory Feature Extraction**  
   Key algorithms estimate airflow patterns and breathing rates, with additional provisions to detect events like apnea in real time.  
4. **Deployment Considerations**  
   The solution is flexible for various indoor settings and sleeping positions, ensuring that users have minimal restrictions on where or how they rest.

## Data and Collaboration

We are not publicly releasing our datasets or detailed implementations due to privacy concerns. If you are a researcher or developer interested in reproducing benchmarks or requiring datasets, please reach out via email:

- **Contact**: [yunpeng.ge@connect.polyu.hk](mailto:yunpeng.ge@connect.polyu.hk)

---

For further details regarding our experimental setup and performance insights, stay tuned for the official publication of our paper. We’d be happy to discuss potential research collaborations or answer any general questions you may have.
