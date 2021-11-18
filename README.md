1.Import libraries: 
Numpy: Numpy in python which is we find any mathematical and scientific calculation. 
Pandas: Pandas in python we need to create dataframe. 
MATLAB: We have any charts for using maplotlib. 
Sklearn: Machine learning in python. 
 
2.Reading data: 
1.Import dataset. 
2.How many datapoints and features. 
3.Veiw data summary. 
 
3.Pre_processing:  
EX: Categorical features. Let’s if we take one feature 
1.How many values count. 
2.we need to remove all spaces, replaces the ‘_’ and convert the all latters to small. 
3.Check if we have any nan value are present. 
4.we are removing the words from stop words list: ‘no’, ‘not’, ‘the’. 
Similarly we do all features. 
EX: Numerical features: 
1.Standardscalar 
2.MinMax scalar 
Dataset Ready: 
4.Exploratory data analysis(EDA): 
1.How many raws and columns are present. 
2.What are the column names in our dataset. 
3.How many data point for each class are present. 
4. Line shown on histogram is called prabability density function(PDF). X_axis class lable and y_axis feature. 
5.Let’s we know have any outlier in our dataset for using box_plot. 
6. check which pair is significant with point distribution using pair_plot. 
5.Spliting dataset: train_teat_split 
 
6.Vectorizing text data. 
6.1.Bag of words(BOW): 
        classroom  students  should  take  break        low  income  homes  students  receive  free  breakfast 
        
break','breakfast','classroom','free','homes','income','low','receive', 'should', 'students', 'take'. 
 
            1 0 1 0 0 0 0 0 1 1 1  
            0 1 0 1 1 1 1 1 0 1 0  
 
6.2.Term frequency   Inverse document frequency (TFIDF): 
 He asked why the government should be allowed to set up a committee. 
 Term frequency(TF): 
          tf(committee) = 1/13  =  0.07692 
  Inverse document frequency(IDF): 
          idf(committee) = ln((1+2)/(1+2)) + 1 =  1 
 
Adding “1” to the numerator and denominator if extra documents was seen containing every term in the collection exactly once. 
7.Machanics of the models: 
Classification and regression models. 
Any algorithm. 
The hyper paramter tuning using for gridsearch cv or randomsearch cv. 
Performance matrix of classification using for confusion matrix, f1_score, Accuracy and AUC\Roc. 
Performance matrix of regression using for MAPE, RMSE and R squar. 
