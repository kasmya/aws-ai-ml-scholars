## AWS AI & ML Scholars Exam – One-Page Revision Notes

| Topic | Short Notes / Keywords |
| -------------------------------- | --------------------------------------------------------------------------------------------- |
| **Artificial Intelligence (AI)** | Machines performing tasks requiring human intelligence (vision, speech, reasoning). |
| **Machine Learning (ML)** | AI subset where models learn patterns from data instead of explicit programming. |
| **Deep Learning** | ML using multi-layer neural networks; powers image recognition and LLMs. |
| **Generative AI** | Creates new text, images, code, audio, or video from prompts. |
| **Foundation Model (FM)** | Large pretrained model adaptable to many tasks (e.g., Amazon Nova, Claude). |
| **LLM** | Foundation model specialized for language understanding and generation. |
| **Training** | Learning from data; computationally expensive. |
| **Inference** | Using a trained model to make predictions or generate responses. |
| **Prompt Engineering** | Writing effective prompts to improve AI outputs. |
| **Zero-shot** | No examples provided in the prompt. |
| **One-shot** | One example included. |
| **Few-shot** | Multiple examples included. |
| **RAG** | Retrieves external knowledge before generation; improves accuracy and reduces hallucinations. |
| **Fine-tuning** | Retrains a model on domain-specific data to specialize it. |
| **Embedding** | Numeric vector representation of text/images used for semantic similarity. |
| **Vector Database** | Stores embeddings for semantic search and RAG applications. |
| **Hallucination** | AI generates incorrect information confidently. |
| **Responsible AI** | Fairness, transparency, privacy, explainability, accountability, security, human oversight. |

---

## Types of Machine Learning

| Type | Description | Example |
| -------------------------- | --------------------------------------- | --------------------- |
| **Supervised Learning** | Uses labeled data | Spam detection |
| **Unsupervised Learning** | Finds hidden patterns in unlabeled data | Customer segmentation |
| **Reinforcement Learning** | Learns through rewards and penalties | Robotics, game AI |

---

## ML Workflow

| Step | Purpose |
| ------------------- | ----------------------------------------- |
| Collect Data | Gather dataset |
| Clean Data | Remove errors, duplicates, missing values |
| Feature Engineering | Create useful input features |
| Train | Learn patterns |
| Validate | Tune hyperparameters |
| Test | Measure final performance |
| Deploy | Release model |
| Monitor | Track accuracy and drift |

---

## Overfitting vs Underfitting

| Overfitting | Underfitting |
| --------------------------------------------- | ------------------------------------------------- |
| Memorizes training data | Model too simple |
| High train accuracy | Low train accuracy |
| Low test accuracy | Low test accuracy |
| Fix: More data, regularization, simpler model | Fix: Better model, more training, better features |

---

## Evaluation Metrics

| Metric | Use |
| --------- | --------------------------------------------- |
| Accuracy | Overall correct predictions |
| Precision | Of predicted positives, how many are correct? |
| Recall | Of actual positives, how many were found? |
| F1 Score | Balance of Precision and Recall |
| MAE | Average prediction error |
| RMSE | Penalizes larger errors more heavily |
| R² | Goodness of fit (higher is better) |

---

## Classification vs Regression

| Classification | Regression |
| ------------------- | ---------------- |
| Predicts categories | Predicts numbers |
| Spam/Not Spam | House Price |
| Disease/Healthy | Temperature |

---

## Common Algorithms

| Algorithm | Use |
| ------------------- | ------------------------------------------- |
| Linear Regression | Predict continuous values |
| Logistic Regression | Binary classification |
| Decision Tree | Rule-based decisions |
| Random Forest | Multiple decision trees for better accuracy |
| K-Means | Clustering |
| Neural Network | Deep learning tasks |
| Transformer | LLMs and Generative AI |

---

## AWS AI Services (Most Important)

| Service | Purpose |
| ------------------------- | ------------------------------------------------ |
| **Amazon Bedrock** | Build Generative AI apps using foundation models |
| **Amazon SageMaker** | Build, train, deploy ML models |
| **Amazon Rekognition** | Image and video analysis |
| **Amazon Textract** | OCR for scanned documents |
| **Amazon Comprehend** | NLP, sentiment, entities |
| **Amazon Translate** | Language translation |
| **Amazon Transcribe** | Speech → Text |
| **Amazon Polly** | Text → Speech |
| **Amazon Lex** | Chatbots |
| **Amazon Personalize** | Recommendation systems |
| **Amazon Forecast** | Time-series forecasting |
| **Amazon Fraud Detector** | Fraud detection |
| **Amazon Kendra** | Enterprise intelligent search |
| **Amazon Q** | AI assistant for developers and businesses |
| **PartyRock** | No-code Generative AI app builder |

---

## Service Selection Cheat Sheet

| Use Case | AWS Service |
| --------------------- | --------------------- |
| Chatbot | Amazon Lex |
| Build LLM apps | Amazon Bedrock |
| Train ML model | Amazon SageMaker |
| OCR | Amazon Textract |
| Detect faces/objects | Amazon Rekognition |
| Sentiment Analysis | Amazon Comprehend |
| Speech to Text | Amazon Transcribe |
| Text to Speech | Amazon Polly |
| Translation | Amazon Translate |
| Recommendation Engine | Amazon Personalize |
| Forecast Sales | Amazon Forecast |
| Enterprise Search | Amazon Kendra |
| Fraud Detection | Amazon Fraud Detector |

---

## Cloud Computing Benefits

| Benefit | Meaning |
| ----------------- | -------------------------------------------- |
| Scalability | Increase or decrease resources automatically |
| Elasticity | Match resources to demand |
| Pay-as-you-go | Pay only for what you use |
| High Availability | Reliable services with minimal downtime |
| Managed Services | AWS manages infrastructure |

---

## Frequently Tested Concepts

| Concept | Remember |
| ------------------ | ------------------------------------- |
| Foundation Model | Large pretrained model |
| LLM | Language-focused foundation model |
| Embedding | Vector representation |
| RAG | Retrieves knowledge before generation |
| Fine-tuning | Changes model weights |
| Prompt Engineering | Improves responses without retraining |
| Hallucination | Confident but incorrect output |
| Bias | Systematic unfairness in predictions |
| Variance | Sensitivity to training data |
| Explainability | Understand why the AI made a decision |
| Data Privacy | Protect sensitive information |
| Human-in-the-loop | Human reviews AI outputs when needed |

---

## Last-Minute Memorization

- **Bedrock = Generative AI**
- **SageMaker = ML lifecycle**
- **Lex = Chatbots**
- **Polly = Text → Speech**
- **Transcribe = Speech → Text**
- **Translate = Language Translation**
- **Textract = OCR**
- **Comprehend = NLP**
- **Rekognition = Images & Video**
- **Personalize = Recommendations**
- **Forecast = Time-series**
- **Kendra = Enterprise Search**
- **Fraud Detector = Fraud Detection**
- **Amazon Q = AI Assistant**
- **RAG = Retrieval + Generation**
- **Embedding = Vector**
- **Fine-tuning = Retrain**
- **Inference = Use model**
- **Training = Learn model**

These condensed notes cover the core concepts that repeatedly appear in AWS AI Practitioner materials and are commonly reported by AWS AI & ML Scholars candidates as being relevant for the Challenge assessment.
