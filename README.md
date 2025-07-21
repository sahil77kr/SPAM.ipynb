CODSOFT_TASK4

SPAM SMS DETECTION

This project addresses a binary classification task: detecting whether an incoming SMS message is spam or not. The dataset consists of SMS messages labeled as either "spam" or "ham" (legitimate). The textual data is first preprocessed by converting to lowercase, removing punctuation, and eliminating stopwords. The cleaned messages are then transformed into numerical form using TF-IDF (Term Frequency–Inverse Document Frequency), which captures the importance of each word relative to the message and the entire corpus. For classification, a Multinomial Naive Bayes model is employed, which is particularly well-suited for text classification problems with word frequency features. The model is evaluated using standard metrics such as Accuracy, Precision, Recall, and F1-Score, ensuring both high detection rates and minimal false positives.
