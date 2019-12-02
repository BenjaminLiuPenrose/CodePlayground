#<center>table of contents</center>

# Python
+ Python Basics
	+ Difference of tuples and lists
		+ immutable and mutable
		+ homogeneous and hetergeneous
		+ hashable and nonhashable
		+ faster and less operations
	+ List add elements
		+ list.append(); list.extend(); list.insert(); 
		+ list.remove(); list.pop();
		+ list.reverse();
		+ list.sort()
	+ speed up python
		+ cpu-bounded, multiprocess and IO bounded, multithread
		+ optimize function inside loop
		+ timeit, cProfiler, profiler
		+ use package, numba, numpy vs pandas
		+ Cpython implemantation of python, JIT get rid of GIT
# Linux
+ Linux Basics
	+ kill -9
	+ tmux
	+ htop, top
	+ df -h
	+ grep [pattern]
	+ ps -ef
# Data
+ AB testing 
	+ Randomized experiment with one variants
	+ 
+ Outlier Detection
	+ Visualization (e.g. box plot)
	+ 1.5 to 2 IQR
	+ 3 std, 5 to 95
	+ Domain Specific
+ Outlier Value
	+ Delete row
	+ fill with avg, 0, interpolated value
	+ model outlier data
	+ Transform like log, clip
+ Missing Value
	+ Delete row
	+ Delete feature
	+ fill with avg, 0, interpolated value
	+ model missing value
+ Imbalanced Data
	+ Have more data
	+ Use imbalance-aware metrics like TPR, FPR
	+ Balance sampling
	+ Reweights the loss function, other algorithm
	+ 
+ Feature Selection
	+ Filter: PCA, LDA
	+ Embedded: LASSO, Tree-based
	+ Wrapper: 
+ Ensemble Learning
	+ Bagging: take the majority or average, Random Forest
	+ Boosting: new classifier work on misclassified samples, XGBoost
	+ Stacking/Blending: create new features based on old models
+ KKT Condition
	+ Primal and Dual feasible
	+ CSC, complementary slackness condition
	+ Lagrangian Stationary
+ Data Normalization
	+ Good for optimization
+ Must be overfit
	+ train and test set have different distribution
+ MSE and normal distribution
+ Cross Entropy and Binomial distribution, KL divergence
+ 

# OLS
+ OLS Assumption
	+ Linear -> GAM (TLS|PCA)
	+ No Colinearity -> VIF, cond number -> drop or transform features
	+ iid normal -> qqplot, resi analysis -> GLS
	+ E[e|X] = 0 
	+ *homoskedasticity -> 
+ Logistic is prob 
	+ If the distribution is binomial

# LASSO, Ridge and Elastic Net
+ Comparison of LASSO, ridge and ElasticNet
	+ LASSO l1 penalty, feature selection, sparsity, coordinate descent
	+ Ridge l2 penalty, shrinkage, closed form, invertable matrix
	+ Elastic Net l1+l2 penalty, unique solution
	+ Huber loss 

# Tree, RandomForest and XGBoost
+ Tree
	+ CART, classification and regression tree
	+ regression tree, MSE, feature + split step
	+ classification tree, information gain
+ GBDT
	+ Gradient descent in the residuals, minimize the residuals
+ Comparison of RandomForest and GBDT
	+ parallel and non-parallel

# SVM and Perceptron Learning
+ support vector - hyper-plane separation
+ kernel trick
+ SVM complexity - O(m^2n + m^3)

# kNN
+ kNN algo
	+ calc and store the dist
	+ store the top k
	+ 
# k-means
+ kmeans algo
	+ EM (Expectation Maximization) Algo
	+ E-step
	+ M-step
+ kmetriods
	+ less sensitive for outliers
	+ 

# Gradient Descent
+ Gradient Descent Convergence Proof
+ Gradient Descent decide param
	+ scheduler
	+ line-search
	+ natural/trusted region

# NN