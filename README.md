**Multi Threading Assignment**
**Methodology**
1. Matrix Multiplication: mat_mul() function conducts matrix multiplication of matrices A and B using np.dot(). The answer is stored at a specific index of result array.
2. Threads utilization: Implement runthreads() to execute matrix multiplication using n (1-10) number of threads. Initialize a list threads to store thread objects. Iterate over the list of matrices, creating a new thread for each matrix multiplication operation using threading.Thread() constructor. Start each thread using the start() method. After creating all threads, wait for all threads to complete using the join() method. Return the time taken for the multiplication operations.
3. Matrix Generation: Generating a constant matrix A of size 1000x1000 using numpy.random.rand(). Creating a list of 100 random matrices of the same size.
4. Execution: Calling runthreads() for each number of threads from 1 to 10, recording the time taken for each operation in results_table.
5. Results: Results are displayed in a tabular format using tabulate().
6. Plotting: We plot the number of threads against the corresponding time taken using matplotlib.pyplot.plot() and display the plot.

Result table:
![image](https://github.com/Parth321636/Multi-Threadhing/assets/91376441/83bf2fad-eeff-4d0a-8d8e-0700fb41923e)
Result graph:
![image](https://github.com/Parth321636/Multi-Threadhing/assets/91376441/b904cf82-4486-4cbd-b340-ce0de078a621)
