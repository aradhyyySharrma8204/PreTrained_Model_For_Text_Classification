# PreTrained_Model_For_Text_Classification




## Project Overview  
This project utilizes the **TOPSIS** (Technique for Order of Preference by Similarity to Ideal Solution) method to assess and rank pretrained models for text classification, considering various performance metrics.


## 1. Models and Evaluation Criteria

The following pretrained models are evaluated:

- DistilBERT  
- RoBERTa  
- ALBERT  
- BERT  
- XLNet  

The models are assessed based on the following evaluation criteria:

- **Accuracy** (Higher is better)
- **F1-score** (Higher is better)
- **Inference Time** (Lower is better)
- **Model Size** (Lower is better)

---

## 2. Implementation Steps

The TOPSIS method is implemented through the following steps:

1. **Normalization** of the decision matrix.
2. **Weighted normalization** of the decision matrix.
3. **Calculation** of the ideal best and worst solutions.
4. **Computation** of distances from the ideal solutions.
5. **Calculation** of TOPSIS scores for each model.
6. **Ranking** of the models based on their scores.

## 6. Conclusion

The implementation of the **TOPSIS** method allows for a systematic and objective ranking of pretrained models for text classification. By considering multiple evaluation criteria such as accuracy, F1-score, inference time, and model size, we can make well-informed decisions about the most suitable model for a given task. This approach provides a clear and structured way to compare models, ensuring that the selected model is optimized for performance and efficiency.

