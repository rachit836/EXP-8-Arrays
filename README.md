

#  **Experiment 8: Array Operations in C++**

---

### 🔹 **Aim:**

To perform basic operations on arrays such as:

1. Input and Output of elements
2. Searching for an element
3. Reversing the array
4. Finding Sum and Average
5. Finding Maximum and Minimum element

---

### 🔹 **Tools Used:**

* Programiz c++ compiler

---

### 🔹 **Theory:**

An **array** is a data structure that stores multiple elements of the same data type at contiguous memory locations. It allows indexed access to elements. Common operations performed on arrays include:

* Input/output using loops
* Searching elements (Linear or Binary search)
* Reversing the array order
* Performing aggregate functions like sum, average, etc.
* Identifying max/min elements

A **`for` loop** is a control structure used to repeat a block of code a specific number of times. It is ideal when the number of iterations is known in advance, such as while accessing each element of an array.

---

### 🔹 **Definitions & Syntax:**

---

#### ✅ **1. Input and Output of an Array using `for` loop**

**Definition:**
Input/output using loops simplifies the process of handling multiple data items stored in arrays.

**Syntax:**

```cpp
int arr[10];
for(int i=0; i<10; i++) {
    cin >> arr[i];  // Taking input
}
for(int i=0; i<10; i++) {
    cout << arr[i] << " ";  // Displaying output
}
```

---

#### ✅ **2. Searching an Element in an Array**

**Definition:**
Linear search checks each element one by one to find the target element.

**Syntax:**

```cpp
int key, found = 0;
for(int i=0; i<n; i++) {
    if(arr[i] == key) {
        found = 1;
        break;
    }
}
```

---

#### ✅ **3. Reverse of an Array**

**Definition:**
Reversing an array involves printing or storing its elements in the reverse order.

**Syntax:**

```cpp
for(int i=n-1; i>=0; i--) {
    cout << arr[i] << " ";
}
```

---

#### ✅ **4. Sum and Average of Elements**

**Definition:**
The sum is the total of all array elements, and the average is sum divided by number of elements.

**Syntax:**

```cpp
int sum = 0;
for(int i=0; i<n; i++) {
    sum += arr[i];
}
float avg = (float)sum / n;
```

---

#### ✅ **5. Finding Maximum and Minimum Element**

**Definition:**
Maximum and minimum values are found by comparing all elements with current max/min.

**Syntax:**

```cpp
int max = arr[0], min = arr[0];
for(int i=1; i<n; i++) {
    if(arr[i] > max) max = arr[i];
    if(arr[i] < min) min = arr[i];
}
```

---

### 🔹 **Conclusion:**

In this experiment, we learned and practiced the essential operations on arrays using `for` loops and conditional statements. We successfully:

* Took input/output of arrays,
* Searched elements using linear search,
* Reversed array elements,
* Calculated sum and average,
* Found maximum and minimum values in an array.

These operations form the foundation of array manipulation in programming and are essential for problem-solving in C++.


