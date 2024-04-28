# This presentation was given at the Midwest Biopharmaceutical Statistics Workshop (MBSW) in May 2023.

# We present a case study applying innovative statistical methods to build models for predicting clinical
# outcomes based on baseline patient characteristics from a multi-arm clinical trial.
# We built a composite biomarker model to predict Disease Free Survival, with the goal of inferring the nature
# of the association of each biomarker with outome and the extent to which that association differed between treatment arms.

# Out analysis used data for 9 candidate biomarkers and 4 routine clinical features from 323 subjects with Urothelial Carcinoma who received one of 2 therapies.
# We describe how we overcame several statistical hurdles that are particularly challenging in the context of penalized regression.
# These challenges included avoiding linearity assumptions when assessing interactions, maintaining hierarchy while parameterizing a model in a way to target interactions,
# and handling scaling issues when combining categorical and continuous candidate predictor variables.
