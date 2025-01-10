# **TensProv: A Python Class for Data Provenance Tracking**

## **Overview**

The **TensProv** class is a robust Python framework designed to construct and manage **sparse binary provenance tensors**, making it ideal for tracking the origin and transformations of data in large datasets.  

This class is tailored for use cases that involve complex data processing workflows, such as:  
- **Vertical Reduction**: Removing unnecessary columns.  
- **Horizontal Reduction**: Filtering rows based on specific criteria.  
- **Augmentation**: Adding rows or columns to enrich the dataset.  
- **Joining**: Combining datasets through shared keys.  
- **Concatenation**: Sequentially merging datasets by rows.  

By providing **flexible and efficient methods**, **TensProv** ensures comprehensive tracking of data transformations while optimizing performance for large-scale operations.  

---

## **Key Features**

### **Supported Operations**

1. **Horizontal Reduction (`filter_data`)**  
   - Filters rows based on specified conditions.  

2. **Vertical Reduction (`drop_columns`)**  
   - Removes unnecessary columns to streamline datasets.  

3. **Horizontal Augmentation (`oversample_data`)**  
   - Adds new rows to the dataset for enrichment.  

4. **Vertical Augmentation (`one_hot_encode`)**  
   - Adds new columns to introduce additional dimensions or features.  

5. **Join (`join_data`)**  
   - Merges two datasets using one or more common keys.  

6. **Concatenation (`append_data`)**  
   - Combines datasets by appending rows sequentially.  

### **Auxiliary Methods**

1. **`evaluate_performance`**  
   - Measures and returns the execution time for each operation.  

2. **`get_tensor`**  
   - Retrieves the sparse binary provenance tensor in dense format for further analysis.  

---

## **Project Goals**

This project aims to establish a computationally efficient way to track and infer the provenance of data transformations in large datasets. By leveraging **binary sparse tensors**, it focuses on:  

- Capturing dependencies between input and output datasets.  
- Ensuring scalability and efficiency for operations like filtering, oversampling, joining, and concatenation.  
- Providing multiple alternative methods for each operation to adapt to various use cases.  

### **Deliverables**  
- **TensProv Class**: A comprehensive implementation of provenance tracking.  
- **Performance Evaluation**: Detailed assessment of processing times for operations.  
- **Alternative Methods**: At least two optimized approaches for each operation type.  
- **CPU Usage Monitoring**: To ensure the performance of data processing operations.
- **Memory Usage Tracking**: a function to measure the peak memory consumption (in MB) during the execution of a given function.


## **Why Use TensProv?**

- **Efficiency**: Designed to handle large-scale datasets with minimal computational overhead.  
- **Flexibility**: Supports multiple approaches for each operation to cater to diverse requirements.  
- **Traceability**: Provides detailed lineage tracking for all transformations, enhancing data quality and reliability.  


