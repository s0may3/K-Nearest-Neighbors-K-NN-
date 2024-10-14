 K-Nearest Neighbors (K-NN)**

1. **Objective**

   * Understand and implement the **K-NN algorithm**
   * Explore how different values of:

     * **K (number of neighbors)**
     * **Sample size**
     * **Noise level**
       affect the **fitting** and **stability** of the K-NN model.

2. **Algorithm Description**

   * Given a new input `x`, training set `S`, and parameter `K`:

     1. Compute distances between `x` and all points in `S`
     2. Sort the distances in ascending order
     3. Select the **K nearest neighbors**
     4. Predict the output using a rule appropriate for the task (e.g., average for regression, majority vote for classification).

3. **Core Concepts to Explore**

   * **K controls the bias-variance trade-off**:

     * Smaller K → more variance (overfitting risk)
     * Larger K → more bias (underfitting risk)
   * **Effect of noise and training set size**:

     * Larger datasets reduce variance
     * Noise degrades prediction performance, especially for small K values.

4. **Hands-On Tasks**

   * Implement and analyze K-NN by varying:

     * **K**
     * **Training set size**
     * **Noise level**
   * Specifically evaluate:

     * **Fitting** → assessed via training set performance
     * **Stability** → assessed via prediction on a newly generated test set (simulated future data).
