# **experiment 8: Arrays and Strings**

---

#  Arrays

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

---

# Strings

---

### 🔹 **Aim:**

To perform basic operations on strings such as:

1. Input and Output of strings
2. Concatenation of strings
3. Reversing a string
4. Checking if a string is a palindrome

---

### 🔹 **Tools Used:**

* Programiz c++ compiler

---

### 🔹 **Theory:**

A **string** is a sequence of characters stored in contiguous memory locations, often represented as an array of characters terminated by a null character `'\0'` in C-style strings, or using the `std::string` class in C++. Strings allow various operations such as input/output, concatenation, reversing, and comparison.

Strings are fundamental in programming for handling text data. Using **`for` loops**, we can access or manipulate individual characters of a string by their index.

---

### 🔹 **Definitions & Syntax:**

---

#### ✅ **1. Input and Output of Strings**

**Definition:**
Input/output of strings can be done using `cin` or `getline` for complete lines, and displayed using `cout`.

**Syntax:**

```cpp
string str;
cin >> str;          // Input (no spaces)
cout << str << endl; // Output

// For input with spaces:
getline(cin, str);
cout << str << endl;
```

---

#### ✅ **2. Concatenation of Strings**

**Definition:**
Concatenation joins two or more strings end-to-end.

**Syntax:**

```cpp
string str1 = "Hello ";
string str2 = "World";
string str3 = str1 + str2;  // Concatenation using '+'
cout << str3 << endl;
```

---

#### ✅ **3. Reversing a String**

**Definition:**
Reversing a string means rearranging its characters in the opposite order.

**Syntax:**

```cpp
string str = "example";
for(int i = str.length() - 1; i >= 0; i--) {
    cout << str[i];
}
cout << endl;
```

---

#### ✅ **4. Checking Palindrome of a String**

**Definition:**
A palindrome is a string that reads the same backward as forward.

**Syntax:**

```cpp
string str;
bool isPalindrome = true;
int n = str.length();

for(int i = 0; i < n/2; i++) {
    if(str[i] != str[n - i - 1]) {
        isPalindrome = false;
        break;
    }
}

if(isPalindrome) cout << "Palindrome" << endl;
else cout << "Not Palindrome" << endl;
```

---

### 🔹 **Conclusion:**

In this experiment, we learned and practiced essential string operations in C++. We successfully:

* Performed input and output of strings,
* Concatenated two strings,
* Reversed strings using indexing,
* Checked whether a string is a palindrome.



---

If you'd like, I can also provide a full combined sample code for either arrays or strings! Would you like me to do that?
