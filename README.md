# Sorting_Visualizer

## Project Description: Sorting Algorithms Visualizer

The Sorting Algorithms Visualizer is a web-based application that aims to enhance the learning experience and understanding of sorting algorithms through interactive visualizations. This project provides a platform where users can observe the step-by-step execution of various sorting algorithms in real-time, enabling them to comprehend the algorithms' inner workings and compare their performances.

Key Features:
1. Interactive Visualization: The visualizer offers an intuitive and interactive interface where users can input a set of data elements and visualize the sorting process. The algorithm's progress is displayed dynamically, allowing users to observe how the elements are rearranged at each step.

2. Multiple Sorting Algorithms: The visualizer supports a range of commonly used sorting algorithms, such as Bubble Sort, Insertion Sort, Selection Sort, Merge Sort, Quick Sort, and Heap Sort, among others. Users can select their preferred algorithm and witness its behavior through the visual representation.

3. Speed Control: To aid comprehension and analysis, the visualizer includes a speed control feature. Users can adjust the speed of the visualization to their preference, either slowing it down for a more detailed observation or speeding it up for a quick overview.

4. Customizable Data Sets: Users have the flexibility to input custom data sets of varying sizes and distributions. This feature allows them to explore how different data characteristics, such as sorted, reverse-sorted, or random, affect the efficiency and behavior of the sorting algorithms.

5. Real-time Statistics: Alongside the visualizations, the visualizer provides real-time statistics and metrics. Users can monitor the number of comparisons, swaps, and other relevant information specific to each sorting algorithm. These statistics offer quantitative insights into the algorithms' performances.

6. User-Friendly Interface: The visualizer is designed with a clean and user-friendly interface, ensuring a seamless experience for users of all levels. The controls and options are easily accessible, and the visualizations are presented in a visually appealing manner.

7. Educational Tool: The Sorting Algorithms Visualizer serves as an educational tool for students, developers, and anyone interested in understanding sorting algorithms. It fosters a deeper understanding of how different sorting techniques work and empowers users to make informed decisions regarding algorithm selection based on their specific requirements.

The Sorting Algorithms Visualizer project aims to bridge the gap between theoretical knowledge and practical implementation by offering an engaging and interactive platform. By visualizing the sorting algorithms' step-by-step execution, users can grasp their intricacies, compare their performances, and gain a solid foundation in algorithmic design and analysis.

### Implemented algorithms:
1) Bubble sort
2) Selection sort
3) Insertion sort
4) Merge sort
5) Quick sort
6) Heap sort

### Features:

1) Colored representation of step being executed:
(1.1) Blue:default ; 
  (1.2) Yellow: Being compared
  (1.3) Red: Identified as in incorrect position and to be moved ;
  (1.4) Green: In correct position.
  
2) 3 Controls for visualizations :
  (2.1) Speed of visualization (5 speed levels) ;
  (2.2) Data size () ;
   (2.3) Generation of new data (Randomly generate new data).
  
4) Time and Space complexity of algorithm being visualized.

### Instructions to use Sorting Algorithm Visualizer:
1. Select size and speed.
2. Then select the desired algorithm.
3. To again visualize the different algorithms please refresh the page and repeat above steps.


### Azure Technologies used :

1.Microsoft Azure Portal

2.Static Web Apps

3.Azure Monitor

### Steps followed While Deploying :

1. Create a Resource Group in Microsoft Azure Portal to make and manage group of all resources required in this project.
<img width="960" alt="azure3" src="https://github.com/kunalshaw-IT/Sorting-Algorithms-Visualizer/assets/109387394/ed53e1b6-1ab1-4a22-9e2c-747a33fd35fd">



2. Then goto desired resource group and search and create Azure Static Webapps and deploy code using Github actions.
<img width="960" alt="azure2" src="https://github.com/kunalshaw-IT/Sorting-Algorithms-Visualizer/assets/109387394/4af15224-410a-4e37-8f50-5c93ff5c294d">


3. After that search for Azure Monitor | Metrics and create it in the same resource group from which we can get insights of our webapp.
<img width="960" alt="azure1" src="https://github.com/kunalshaw-IT/Sorting-Algorithms-Visualizer/assets/109387394/7bdd856f-a584-4c24-a06e-536e02d7a58e">


4. Using the above steps code will be successfully deployed and ready to use.
![azure4](https://github.com/kunalshaw-IT/Sorting-Algorithms-Visualizer/assets/109387394/870e392b-bb19-4135-ba5d-ddf4175bcb4a)

WebApp Link: https://kind-desert-0e40f5510.3.azurestaticapps.net/



