
# 🐪 Perl Concepts Repository

Welcome to the **Perl Concepts Repository**! This repository showcases various programming concepts with practical examples and explanations. Each folder within this repository is dedicated to a specific topic, providing insights and hands-on code samples.

---

### 📜 History of Perl

Perl, which stands for **"Practical Extraction and Report Language,"** was developed by **Larry Wall** in 1987. Initially, Perl was designed as a tool to help Larry Wall, a linguist and a systems administrator at the time, with system administration tasks in a Unix environment. He needed a language that combined the best features of existing tools like **sed, awk, and shell scripting** while also being more flexible and powerful.

#### 🗓️ Key Milestones in Perl's History:

- **1987**: The first version of Perl (Perl 1.0) was released on December 18, 1987. It was intended to be a general-purpose Unix scripting language that made report processing easier.
- **1991**: Perl 4.0 was released, focusing on bug fixes and improvements rather than introducing new features. Perl 4 is notable because it solidified Perl’s role as a versatile scripting language.
- **1994**: Perl 5.0 was released, marking a significant evolution in the language. Perl 5 introduced several new features, such as the ability to use modules (which could be included in scripts), object-oriented programming, and references, making the language more powerful and adaptable.
- **1995**: The Comprehensive Perl Archive Network (CPAN) was established. CPAN became a central repository for Perl modules and extensions, significantly expanding Perl's capabilities by allowing developers to share and reuse code.
- **2010**: Perl 6 was officially released, although it was not a direct upgrade of Perl 5 but rather a sister language. Eventually, Perl 6 was renamed **Raku** to distinguish it from Perl 5, which continued to evolve.
- **2020s**: Perl remains widely used, particularly in system administration, web development, network programming, and text processing. The language continues to be maintained and updated, with new versions of Perl 5 still being released.

### 🔍 Full Meaning of Perl

The full form of Perl is **"Practical Extraction and Report Language,"** although Larry Wall, the creator of Perl, also humorously suggested that it could stand for **"Pathologically Eclectic Rubbish Lister."** This reflects the language's versatility and the somewhat chaotic (but effective) nature of Perl programming.

### 💡 Why Learn Perl?

1. **📝 Text Processing**: Perl is exceptionally good at text processing, making it ideal for tasks involving large amounts of text data, such as log analysis, report generation, and data extraction.
2. **🖥️ System Administration**: Perl is widely used in system administration due to its ability to automate complex tasks, manage files, and handle system operations efficiently.
3. **🌐 Web Development**: Although other languages like Python and PHP have become more popular, Perl's CGI scripting was foundational in the development of early dynamic websites.
4. **📡 Network Programming**: Perl provides robust libraries for network programming, making it a powerful tool for developing network-based applications.
5. **🔐 Cyber Security**: Perl's flexibility and powerful text processing capabilities make it an excellent tool for automating security tasks, analyzing logs, and developing custom security tools.
6. **🤖 Automation and Scripting**: Perl is highly efficient for automating repetitive tasks, allowing for the quick development of scripts that can manage system operations, data processing, and other routine tasks, significantly improving productivity.
7. **📊 Log Analysis**: Perl excels at parsing and analyzing log files, making it an invaluable tool for extracting, filtering, and reporting critical information from large volumes of log data.
8. **🔧 Versatility and Extensibility**: With CPAN, Perl can be extended to perform virtually any task. Thousands of modules are available, allowing Perl to handle tasks ranging from web scraping to database management.
9. **📈 Job Market**: Perl skills are still in demand, particularly in legacy systems and companies that require strong text processing and system administration capabilities. It's also valued for its scripting capabilities in automating repetitive tasks.

Perl continues to be a relevant and powerful language for specific tasks, especially where text processing and system scripting are involved. Its community remains active, and it’s supported by a vast repository of modules and tools, ensuring it remains a valuable skill for developers and administrators.

---

## 🗂️ Repository Structure

### 1. [**Input** 📥](./input)
Contains Perl scripts demonstrating basic user input handling.

- **Prompt for User Input**: 
  - Captures user name and age.
  - Utilizes Perl’s `<STDIN>` to read input.
  - **Removes newline characters** with `chomp`.
- **Display User Input**: 
  - Greets the user with their entered name and age.

### 2. [**Array** 🧩](./array)
Showcases various array operations.

- **Creating an Array**: Initialize and display arrays.
- **Accessing Elements**: Retrieve specific elements.
- **Modifying Elements**: Change existing values.
- **Adding Elements**: Use `push` and `unshift`.
- **Removing Elements**: Use `pop` and `shift`.
- **Slicing Arrays**: Extract sublists.
- **Array Length**: Get the number of elements.
- **Sorting Arrays**: Order elements.
- **Reversing Arrays**: Reverse order.
- **Splicing Arrays**: Remove or replace elements.
- **Joining Arrays into a String**: Combine elements.
- **Splitting a String into an Array**: Convert a string.
- **Combining Arrays**: Merge two arrays.
- **Iterating over Arrays**: Loop through elements.
- **Multidimensional Arrays**: Work with arrays of arrays.
- **Array References**: Create and use references.
- **Using `map`**: Transform each element.
- **Using `grep`**: Filter elements.
- **Array Slices**: Access multiple elements.
- **Advanced Splicing**: Remove elements without replacement.
- **Flattening Multidimensional Arrays**: Convert arrays of arrays.
- **Anonymous Arrays**: Create arrays without named variables.
- **Advanced Iteration with Index**: Iterate with index using `each`.
- **Reducing Arrays**: Combine elements.
- **Using a Stack or Queue**: Perform stack and queue operations.

### 3. [**Hashes** 🗝️](./hashes)
Focuses on working with hashes.

- **Creating a Hash**: Initialize with key-value pairs.
- **Accessing Hash Elements**: Retrieve values by keys.
- **Modifying Hash Elements**: Change values.
- **Adding New Key-Value Pairs**: Insert entries.
- **Deleting Key-Value Pairs**: Remove entries.
- **Checking Existence of a Key**: Verify key presence.
- **Hash Size**: Determine the number of pairs.
- **Iterating over a Hash**: Loop through keys and values.
- **Extracting Keys and Values**: Retrieve all keys/values.
- **Hash Slices**: Access multiple values.
- **Merging Hashes**: Combine two hashes.
- **Hash Reference**: Create and use references.
- **Anonymous Hash**: Create hashes without named variables.
- **Hash of Arrays**: Use arrays as values.
- **Hash of Hashes**: Use hashes as values in another hash.
- **Using `map` with Hashes**: Transform hash values.
- **Using `grep` with Hashes**: Filter keys based on values.
- **Inverting a Hash**: Swap keys and values.
- **Hash Sorting**: Sort hash keys or values.
- **Complex Keys in Hash**: Use multi-part keys.
- **Accessing Complex Keys Dynamically**: Dynamic key access.
- **Modifying Hash with `splice`**: Simulate value replacement.

### 4. [**File Handling** 📁](./file_handling)
Demonstrates basic file operations.

- **Check if a File Exists**: Verify file presence using `-e`.
- **Prompt for User Input**: Get filenames from the user.
- **Read from a File**: Open and read file contents.
- **Write to a File**: Create or overwrite file content.
- **Append to a File**: Add content to an existing file.
- **Write to a New File**: Create and write to a new file.
- **Read the Newly Created File**: Verify new file’s content.

### 5. [**Data Structure** 📚]
Covers fundamental data structures.

- [**Stack**](./stack):
  - **LIFO Principle**: Demonstrates stack operations like `push`, `pop`, and `peek`.
- [**Queue**](./queue):
  - **FIFO Principle**: Demonstrates queue operations like `enqueue`, `dequeue`, and `peek`.
- [**Linked List**](./linked_list):
  - **Single Linked List**: Operations include insertion, deletion, and traversal.
- [**Binary Tree**](./binary_tree):
  - **Tree Operations**: Includes insertion, traversal (in-order, pre-order, post-order), and searching.

### 6. [**Object-Oriented Programming** 🏷️](./Object-Oriented_Programming)
Illustrates Object-Oriented Programming (OOP) principles with practical examples.

- **Base Class (`Animal`)**:
  - **Constructor**: Initializes attributes like `name` and `age`.
  - **Methods**: 
    - **Getters**: Retrieve attribute values.
    - **Setters**: Update attribute values.
    - **`display_info` Method**: Displays the basic information of the animal.

- **Derived Classes**:
  - **`Dog`**:
    - Inherits from `Animal`.
    - **Attributes**: Adds `breed` attribute.
    - **Method Overrides**: 
      - **`display_info`**: Extends the base class method to include the breed information.
  
  - **`Cat`**:
    - Inherits from `Animal`.
    - **Attributes**: Adds `color` attribute.
    - **Method Overrides**:
      - **`display_info`**: Extends the base class method to include the color information.

  - **`Pet`**:
    - Inherits from `Animal`.
    - **Attributes**: Adds `species` attribute.
    - **Method Overrides**:
      - **`display_info`**: Extends the base class method to include species information, demonstrating **polymorphism**.

- **Main Script**:
  - **Creating Objects**: Shows how to instantiate objects of `Dog`, `Cat`, and `Pet`.
  - **Modifying Objects**: Demonstrates how to update and access attributes.
  - **Displaying Information**: Uses `display_info` to output details for each object.

---

Thank you for visiting the repository! Happy coding!
