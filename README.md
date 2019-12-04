
## What is modelLearn?

modelLearn is a ***high performance***, ***easy-to-use***, and ***scalable*** machine learning package that contains linear model (LR), factorization machines (FM), and field-aware factorization machines (FFM), all of which can be used to solve large-scale machine learning problems. modelLearn is especially useful for solving machine learning problems on large-scale sparse data. Many real world datasets deal with high dimensional sparse feature vectors like a recommendation system where the number of categories and users is on the order of millions. In that case, if you are the user of liblinear, libfm, and libffm, now modelLearn is your another better choice.



### Performance



modelLearn is developed by high-performance C++ code with careful design and optimizations. Our system is designed to maximize CPU and memory utilization, provide cache-aware computation, and support lock-free learning. By combining these insights, modelLearn is 5x-13x faster compared to similar systems.

### Ease-of-use



modelLearn does not rely on any third-party library and users can just clone the code and compile it by using cmake. Also, modelLearn supports very simple Python and CLI interface for data scientists, and it also offers many useful features that have been widely used in machine learning and data mining competitions, such as cross-validation, early-stop, etc.

### Scalability


modelLearn can be used for solving large-scale machine learning problems. First, modelLearn supports out-of-core training, which can handle very large data (TB) by just leveraging the disk of a PC. In addition, modelLearn supports distributed training, which scales beyond billions of example across many machines by using the Parameter Server framework.







