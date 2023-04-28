# Naive_Bayes_exercise
# First i save my "wine ataset" as "wine" """wine = datasets.load_wine()""" and load it into columns """df = pd.DataFrame(wine.data, columns=wine.feature_names)"""
# And create new "target" column """df['target'] = wine.target"""
# I have my data ready, so I import "train_test_split" and get "train" and "test" set, my "X" is "wine.data" and "y" "wine.target"
# Now I import two models "GaussianNB", "MultinomialNB" 
