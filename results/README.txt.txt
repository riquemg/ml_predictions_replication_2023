Description:

These folder has CSV files with the results of the experiments with feature selection variation, use of Polynomial Features and Resample strategies.

Code Smells Initials:
- gc: God Class
- rb: Refused Bequest
- lm: Long Method
- fe: Feature Envy

Other Acronyms:
- fv: Variation of the quantity of selected features.
- poly: The use of PolynomialFeatures for generate polynomial and interaction features.
- undersample: Experiment that vary undersample strategy value
- oversample: Experiment that vary oversample strategy value

There are 4 result files for each Code Smell. Every file has a standard name: code smell initials, plus "_", and the kind of experiment.

Some Examples:

- gc_fv_poly: Results of the experiments to predict God Class, varying the quantity of selected features, using PolynomialFeatures class.
- fe_fv: Results of the experiment to predict Feature Envy, varying the quantity of selected features.
- rb_oversample: Results of the experiment to predict Refused Bequest, varying the oversample strategy.