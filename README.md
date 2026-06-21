# 🧪 Chem Annotation Toolkit

A case study and open annotation guideline framework for labeling chemistry-related AI training data.

This project documents how a chemistry Subject Matter Expert (SME) would evaluate and annotate AI-generated responses across multiple chemistry disciplines, including:

* General Chemistry
* Chemical Reactions
* Regulatory Compliance
* Industrial Lubrication Science

The toolkit is intended as a reference framework for AI training, evaluation, benchmarking, and quality assurance workflows involving chemistry-focused datasets.

---

## 🎯 Purpose

The Chem Annotation Toolkit provides:

* Annotation guidelines for chemistry-focused AI outputs
* Sample labeled datasets and evaluation examples
* Quality assessment criteria for scientific content
* A reusable framework for training and evaluating chemistry domain models

Developed by a chemistry professional with more than 20 years of industry experience.

---

## 📋 Annotation Dimensions

AI-generated responses are evaluated using the following dimensions:

| Dimension                | Description                                                                                         |
| ------------------------ | --------------------------------------------------------------------------------------------------- |
| **Scientific Accuracy**  | Is the chemistry factually correct and scientifically valid?                                        |
| **Completeness**         | Are all critical concepts and explanations included?                                                |
| **Clarity**              | Is the response understandable for the intended audience?                                           |
| **Regulatory Alignment** | Does the content accurately reference applicable FDA, EPA, NSF, OSHA, or related regulations?       |
| **Safety Compliance**    | Are hazards, PPE requirements, storage considerations, and handling procedures correctly described? |

---

## 🧬 Sample Annotation Task

### Domain

General Chemistry

### AI Response

> "NaOH dissolves in water to form a basic solution with pH > 7."

### Score

**4 / 5**

### Evaluation

The statement is scientifically accurate; however, it omits important contextual information regarding:

* Exothermic dissolution behavior
* Safe handling practices
* Chemical burn hazards

### Annotation Note

> Add hazard context. Sodium hydroxide is a strong base that can cause severe chemical burns upon contact with skin or eyes.

---

## 🔬 Intended Use Cases

* AI Training Data Annotation
* Reinforcement Learning from Human Feedback (RLHF)
* Model Evaluation & Benchmarking
* Scientific Content Quality Assurance
* Regulatory Content Review
* Educational Chemistry Applications

---

## 📚 Target Domains

* General Chemistry
* Organic Chemistry
* Inorganic Chemistry
* Chemical Engineering
* Industrial Lubricants
* Materials Science
* Environmental Chemistry
* Regulatory Compliance & Safety

---

## ⚠️ Disclaimer

This repository is intended for educational, research, and AI annotation purposes only. Regulatory guidance and safety recommendations should always be verified against current official sources and applicable jurisdictional requirements.

---

## 🤝 Contributions

Contributions, annotation examples, domain-specific evaluation criteria, and improvements to the framework are welcome through issues and pull requests.

---

## 📄 License

This project is released under the MIT License unless otherwise specified.
