# CHIRon-A-Generative-Foundation-Model-for-Structured-Sequential-Medical-Data

# CHIRon: A Generative Foundation Model for Structured Sequential Medical Data

This project implements and evaluates a simplified version of the CHIRon architecture — a generative model for structured sequential electronic health records (EHRs) using transformers.

The work is inspired by the CHIRon paper presented at the NeurIPS 2023 Generative AI for Science Workshop.

---

##  Paper Reference

- **Paper Title**: CHIRon: A Generative Foundation Model for Structured Sequential Medical Data
- **Authors**: Vinay Prabhu, Pushpak Pati, etc.
- **Conference**: NeurIPS 2023 - Generative AI for Science Workshop
- **Paper Link**: [https://openreview.net/forum?id=RlDAULa6N7](https://openreview.net/forum?id=RlDAULa6N7)

---

##  Project Goals

- Build a transformer-based generative model for structured sequential patient events.
- Pre-train the model to predict next event tokens autoregressively.
- Evaluate the quality of generated sequences using accuracy and diversity metrics.
- Explore healthcare-specific pretraining using synthetic datasets (e.g., Synthea).

---


---

##  Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/chiron-foundation-model.git
cd chiron-foundation-model
