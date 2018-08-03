# Pedestrian-Detection
In order to improve the accuracy of static pedestrian detection, this paper propose a novel algorithm, which is based on the improved co-occurrence probability features of Histogram of Oriented Gradients (HOG). Firstly the HOG feature is combined with the Local Binary Pattern (LBP) and Color Self-Similarity (CSS) features to generate improved HOG features respectively, and then based on this feature generate the Co-occurrence Probability Feature (CPF) by using the first stage Real AdaBoost Algorithm. Secondly, the strong classifier can be trained and generated by utilizing the second phase Real AdaBoost algorithm based on CPF. In the end, the pedestrian are detected by using the strong classifier described above. Experiments are conducted on the INRIA pedestrian database, the maximum detection accuracy of 99 % can be achieved which is better than the traditional algorithms. The experimental results prove the effectiveness of our proposed algorithm.
