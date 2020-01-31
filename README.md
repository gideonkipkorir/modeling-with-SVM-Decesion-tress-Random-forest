# Modeling-with-SVM-Decesion-trees-Random-forest
## Problem statement:
Build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroid.
### Part 1: Decision trees:
- For this section, you should build a model that makes the above prediction. You should not use individual decision trees, rather you should use at least 2 out of the 3 advanced models we have studied: Random forests, Ada boosted trees, and gradient boosted trees.
- Try and optimize each of the 2 models, making sure to document how you've set up your hyperparameters.
- Identify which of the 2 models you trust most, and use your model to determine which features are most impactful in influencing the prediction
- Note that with decision trees, you don't need to do a lot of data cleaning. This will be very different with SVM.

### Part 2: SVM:

- In this section, you may be required to clean the data a little bit so as to make sense of the features.

- Document what transformation you've done on the data.

- Apply Polynomial, linear and rbf kernel function to build your SVM model and then evaluate their performance and pick the kernel that performs the best. Remember to tune your parameters to improve the performance of your model. To make your life easier, make sure to visualize the models you've created. Use any two features to build the models for this step.

Hint: You may want to use decision trees to give you the most preferable features you can use. but also keep in mind that those features might not be suitable for SVM. It might be a good idea to graph them first.

-  After getting your best performing kernel, use this kernel together with your tuned parameters and repeat the prediction but this time using additional features. Compare the model you've just created with the 2-features version. 
**Dataset Columns**

*	Age
*	Sex
*	on_thyroxine
*	query_on_thyroxine
*	on_antithyroid_medicationthyroid_surgery
*	query_hypothyroid
*	query_hyperthyroid
*	pregnant
*	sick
*	tumor
*	lithium:is concentrated by the thyroid and inhibits thyroidal iodine uptake. It also inhibits iodotyrosine coupling, alters thyroglobulin structure, and inhibits thyroid hormone secretion
*	goitre:a swelling of the neck resulting from enlargement of the thyroid gland.
*	TSH_measured:A TSH test is done to find out if your thyroid gland is working the way it should. ... If untreated, a thyroid disorder can cause health problems. TSH stands for “thyroid stimulating hormone” and the test measures how much of this hormone is in your blood
*	TSH
*	T3_measured
*	T3 : A T3 test is performed as part of an evaluation of thyroid function. It measures the blood level of the hormone T3 (triiodothyronine)
*	TT4_measured:This test measures the level of the hormone thyroxine (T4) in your blood. The hormone is made by your thyroid gland
*	TT4
* TBG:TBG binds thyroid hormones in circulation. It is one of three transport proteins (along with transthyretin and serum albumin) responsible for carrying the thyroid hormones thyroxine (T4) and triiodothyronine (T3) in the bloodstream.
