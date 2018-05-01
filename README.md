## VaccineSideEffect-AsthmaPrediction
In the last two centuries, vaccinations have been used as an essential tool in the fight against infectious diseases, and succeeded in improving public health and in eradicating or minimizing the extent of several diseases around the world. Drugs and vaccines are chemicals that treat, cure, prevent, or diagnose diseases, and are beneficial for human health. Almost, all drugs have side effects, and unintended side effects may do harm to human and lead to serious consequences. Identifying side effects of drugs is meaningful and urgent. 

One of those side effects, asthma is a chronic disease involving the airways in the lungs. These airways, or bronchial tubes, allow air to come in and out of the lungs. It is a common lung condition that causes occasional breathing difficulties. An asthma flare-up can come on slowly (over hours, days or even weeks) or very quickly (over minutes). A sudden or severe asthma flare-up is sometimes called an asthma attack. Asthma cannot be cured, but for most people it can be well controlled by following a daily management plan.

People with asthma experience symptoms when the airways tighten, inflame, or fill with mucus. Common asthma symptoms include: coughing - especially at night, shortness of breath, chest tightness, pain, or pressure, wheezing. 
It may occur randomly or after exposure to a trigger. Common asthma triggers include: allergies – to house dust mites, animal fur or pollen, for example-smoke, pollution and cold air, exercise, infections like colds or flu, drug or vaccine side effects etc.

##### Identifying and avoiding asthma triggers can help people to keep asthma symptoms under control.

Dataset used in the project is obtained from Vaccine Adverse Event Reporting System (VAERS) which is a nation vaccine surveillance program which collects and shares information about adverse events following immunization. Dataset contains patient's symptom stories. The problem is the presence of random 10 textual data and phrases, which makes the task of prediction very challenging.
Moreover, the dataset is cleaned, filtered and restructured to make it useful. Special characters, language specifics and repetitions in data are dealt with carefully. There are some columns in the dataset which does not contribute to the purpose of prediction and hence are removed.

#### We perform Naive Bayes, Logistic Regression, Artificial Neural Network and Random Forest and get almost same type of results. And the accuracy of the Random Forest is the most.  We observe that our model predicts with more accuracy.

