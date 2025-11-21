# Humanoid Benchmark - проект в рамках студкемпа от Яндекса и СПБГУ "Математика в ИИ"


### The goal of this project is to develop a benchmark for evaluating social bias in Large Language Models (LLM)


### Base Notation

* D - set of words from the target domain
* $$w \in D$$ - word from the target domain
* $$h_{model}(w)$$ - hidden representation of the word  from the model
* $$P$$ = {"love", "like", "prefer", ... }  - set of positive emotion words
* $$N$$ = {"hate", "anger", "disgust", ... } - set of negative emotion words

### Intuition
Our approach is grounded in the following intuition: a model exhibits stronger bias towards a
domain word $$w$$ if its internal representation $$h_{model}(w)$$ is semantically closer to words
representing positive emotions and simultaneously farther from words representing negative emotions

### Formuls

<img width="779" height="125" alt="Снимок экрана 2025-11-22 в 01 03 53" src="https://github.com/user-attachments/assets/6f0e384f-792d-4e5e-8a87-30c99db2d322" />


<img width="1219" height="244" alt="Снимок экрана 2025-11-22 в 01 04 33" src="https://github.com/user-attachments/assets/68339bcd-8c61-42af-a6bc-a849eb3eae4c" />


<img width="955" height="169" alt="Снимок экрана 2025-11-22 в 01 04 52" src="https://github.com/user-attachments/assets/323c1f73-3e88-410a-8783-15e1c15cb4e2" />


<img width="860" height="109" alt="Снимок экрана 2025-11-22 в 01 05 08" src="https://github.com/user-attachments/assets/26aa776c-5a57-4d89-bfe4-96aa1c3c6cc9" />

### Tests

<img width="1248" height="518" alt="Снимок экрана 2025-11-22 в 01 05 35" src="https://github.com/user-attachments/assets/a1c4cfac-4362-4bad-a9e4-49f1d7c75325" />
