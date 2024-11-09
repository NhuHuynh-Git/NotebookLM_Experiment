# Question-Answering Experiment

## Objective
Evaluate NotebookLM's accuracy and relevance in answering specific questions.

## Document Used
*Title*: An Overview of Machine Learning-Based
 Techniques for Solving Optimization
 Problems in Communications
 and Signal Processing  
*Type*: Research Article   
*Length*: 31 pages 

## Questions and Responses
**Question 1**: What is perceptron model and give explanation on the flow and roles of each step in the this model?

**Answer provided 1**: A Look at the Perceptron Model: The perceptron model is the simplest form of a neural network, consisting of a single layer. It forms the basis for understanding more complex neural network architectures. Here's a breakdown of the perceptron model's flow and the role of each step:
-   Inputs (xi): The model takes multiple inputs, denoted as x<sub>i</sub>, where 'i' represents the index of each input. These inputs can represent various features or variables relevant to the problem the perceptron is trying to solve. For example, in a spam detection task, the inputs could be the frequency of certain words in an email.
-   Weights (wi): Each input is associated with a weight, denoted as w<sub>i</sub>. Weights determine the importance of each input in influencing the perceptron's output. During the learning process, these weights are adjusted to improve the model's accuracy.
-   Summation: The perceptron calculates the weighted sum of the inputs. This involves multiplying each input (x<sub>i</sub>) with its corresponding weight (w<sub>i</sub>) and then adding up all the resulting products. Mathematically, this step can be represented as: ∑<sup>N</sup><sub>i=1</sub> w<sub>i</sub>x<sub>i</sub> , where 'N' is the total number of inputs.
-   Bias (b): A bias term, denoted as 'b', is added to the weighted sum. The bias acts as an offset and allows the perceptron to make adjustments even when all inputs are zero. It helps the model fit the data better.
-   Activation Function (σ): An activation function, denoted as σ(.), is applied to the sum of the weighted inputs and the bias. This function introduces non-linearity into the model, allowing it to learn more complex patterns and make more sophisticated decisions. Common activation functions include sigmoid, tanh, and ReLU. The purpose of the activation function in a perceptron model is to transform the linear combination of inputs and weights into a non-linear output. This non-linearity is crucial for allowing the perceptron to model complex relationships and make decisions that go beyond simple linear separations of data.
-   Output (Y): The output of the perceptron, denoted as 'Y', is the result of the activation function. It represents the perceptron's prediction or classification based on the given inputs.
Mathematically, the entire process of the perceptron model can be expressed as:
Y = σ (∑<sup>N</sup><sub>i=1</sub> w<sub>i</sub>x<sub>i</sub> + b)

The  perceptron model learns by adjusting its weights and bias during the training process. This adjustment is typically done using algorithms like gradient descent or backpropagation, which aim to minimize the difference between the perceptron's output and the desired output for a given set of training data.

**Question 2**: How to apply perceptron model concept in businesses like banking industries?

**Answer provided 2**: Applying the Perceptron Model in Banking: The sources provided do not offer specific examples of applying the perceptron model in the banking industry. However, based on our conversation about the perceptron model and the general discussion of machine learning applications in the sources, we can explore potential use cases. Remember that the following information about banking applications draws upon general knowledge of the perceptron model and is not directly derived from the sources. You may want to verify this information independently. Potential Applications in Banking:
- Credit Risk Assessment: A perceptron model could be trained on historical data of loan applicants, including features like credit score, income, employment history, and debt-to-income ratio. The model could then predict the likelihood of a new applicant defaulting on a loan. For example, the inputs (x<sub>i</sub>) could be credit score, income, employment history, and debt-to-income ratio, each with its own weight (w<sub>i</sub>) reflecting its importance in assessing credit risk. The model would compute a weighted sum of these inputs, add a bias term, and apply an activation function to generate an output (Y) representing the probability of default.
- Fraud Detection: Perceptrons could be employed to detect fraudulent transactions by analyzing patterns in transaction data such as amount, time, location, and merchant type. In this case, inputs (x<sub>i</sub>) might include transaction amount, time of day, location, and merchant category. The model could learn to identify unusual combinations of these features that deviate from typical customer behavior, flagging potentially fraudulent transactions for further investigation.
- Customer Churn Prediction: Banks could use perceptrons to predict which customers are likely to close their accounts or switch to a competitor. This prediction could be based on factors like account activity, demographics, and customer service interactions. Here, inputs (x<sub>i</sub>) could be account balance, transaction frequency, age, and number of customer service calls. The model could learn to recognize patterns that indicate a customer's dissatisfaction or disengagement, allowing the bank to proactively address potential churn.
- Personalized Marketing: Perceptrons can help banks personalize marketing campaigns by predicting customer responses to different offers based on their profile and past interactions. For example, inputs (x<sub>i</sub>) could represent a customer's demographics, purchase history, and website browsing behavior. The model could predict the likelihood of a customer responding to specific product promotions or marketing messages, enabling more targeted and effective campaigns.

## Conclusion
- Strengths:
- Weaknesses:
  
## Reference
Link to document: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9429227


