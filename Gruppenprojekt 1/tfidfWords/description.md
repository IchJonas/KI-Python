getestete Parameter:
        'tfidf__max_df': [0.05, 0.1, 0.3, 0.5],             
        'tfidf__min_df': [2],                 
        'tfidf__max_features': [500, 2500, 5600], 
        'tfidf__sublinear_tf': [True],           
        'clf__min_samples_split': [2],           
        'clf__min_samples_leaf': [1],            
        'clf__max_depth': [80, 130, 200],        
        'clf__criterion': ['gini'],     

top_1
preprocessed/dataLemmaLowerStop_train.csv
Pipeline(steps=[('tfidf',
                 TfidfVectorizer(max_df=0.05, max_features=5600, min_df=2,
                                 stop_words='english', sublinear_tf=True)),
                ('clf',
                 DecisionTreeClassifier(max_depth=200, random_state=42))])
F1-Score:  0.7171292513855766

top_2
preprocessed/dataStop_train.csv
Pipeline(steps=[('tfidf',
                 TfidfVectorizer(max_df=0.05, max_features=5600, min_df=2,
                                 stop_words='english', sublinear_tf=True)),
                ('clf',
                 DecisionTreeClassifier(max_depth=200, random_state=42))])
F1-Score:  0.6957133735778964

top_3
preprocessed/dataLower_train.csv
Pipeline(steps=[('tfidf',
                 TfidfVectorizer(max_df=0.05, max_features=5600, min_df=2,
                                 stop_words='english', sublinear_tf=True)),
                ('clf',
                 DecisionTreeClassifier(max_depth=200, random_state=42))])
F1-Score:  0.6957133735778964

top_4
preprocessed/dataNormal_train.csv
Pipeline(steps=[('tfidf',
                 TfidfVectorizer(max_df=0.05, max_features=5600, min_df=2,
                                 stop_words='english', sublinear_tf=True)),
                ('clf',
                 DecisionTreeClassifier(max_depth=200, random_state=42))])
F1-Score:  0.6808508563110761

top_5
preprocessed/dataKurze_train.csv
Pipeline(steps=[('tfidf',
                 TfidfVectorizer(max_df=0.05, max_features=2500, min_df=2,
                                 stop_words='english', sublinear_tf=True)),
                ('clf',
                 DecisionTreeClassifier(max_depth=200, random_state=42))])
F1-Score:  0.6680730844475825