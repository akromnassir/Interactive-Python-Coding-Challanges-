

interactive-coding-challenges
============


**120+ continually updated, interactive, and test-driven coding challenges**, with [Anki flashcards](#anki-flashcards-coding-and-design).

Challenges focus on **algorithms** and **data structures** found in **coding interviews**.

Each challenge has one or more reference solutions that are:

* Fully functional
* Unit tested
* Easy-to-understand

Challenges will soon provide on-demand [incremental hints] (https://github.com/akromnassir/Interactive-Python-Coding-Challanges-.git) to help you arrive at the optimal solution.

Notebooks also detail:

* Constraints
* Test cases
* Algorithms
* Big-O time and space complexities




## Anki Flashcards: Coding and Design

<p align="center">
  <img src="http://i.imgur.com/b4YtAEN.png">
  <br/>
</p>

The provided [Anki flashcard deck](https://apps.ankiweb.net/) uses spaced repetition to help you retain key concepts.

* [Coding deck](anki_cards/Coding.apkg)

Great for use while on the go.

### Design Resource: The System Design Primer

Looking for resources to help you prep for the **System Design** and **Object-Oriented Design interviews**?

<p align="center">
  <img src="http://i.imgur.com/zdCAkB3.png">
  <br/>
</p>

Check out the sister repo [The System Design Primer](http://i.imgur.com/b4YtAEN.png), which contains additional Anki decks:

* [System design deck](https://github.com/akromnassir/Interactive-Python-Coding-Challanges-)



## Notebook Structure

Each challenge has two notebooks, a **challenge notebook** with unit tests for you to solve and a **solution notebook** for reference.

### Problem Statement

* States the problem to solve.

### Constraints

* Describes any constraints or assumptions.

### Test Cases

* Describes the general and edge test cases that will be evaluated in the unit test.

### Algorithm

* [Challenge Notebook] Empty, refer to the solution notebook algorithm section if you need a hint.
* [Solution Notebook] One or more algorithm solution discussions, with Big-O time and space complexities.

### Hints


### Code (Challenge: Implement Me!)

* [Challenge Notebook] Skeleton code for you to implement.
* [Solution Notebook] One or more reference solutions.

### Unit Test

* [Challenge Notebook] Unit test for your code.  Expected to fail until you solve the challenge.
* [Solution Notebook] Unit test for the reference solution(s).

## Index

### Challenges Categories

**Format**: Challenge Category - Number of Challenges

* [Arrays and Strings](#arrays-and-strings) - 10
* [Linked Lists](#linked-lists) - 8
* [Stacks and Queues](#stacks-and-queues) - 8
* [Graphs and Trees](#graphs-and-trees) - 21
* [Sorting](#sorting) - 10
* [Recursion and Dynamic Programming](#recursion-and-dynamic-programming) - 17
* [Mathematics and Probability](#mathematics-and-probability) - 6
* [Bit Manipulation](#bit-manipulation) - 8
* [Online Judges](#online-judges) - 16
* [System Design](https://github.com/donnemartin/system-design-primer#system-design-interview-questions-with-solutions) - 8
* [Object Oriented Design](https://github.com/donnemartin/system-design-primer#object-oriented-design-interview-questions-with-solutions) - 8

**Total number of challenges: 120**

### Reference Implementations: Data Structures


### Reference Implementations: Algorithms




### Installing and Running Challenges

* [Repo Structure](#repo-structure)
* [Notebook Installation](#notebook-installation)
* [Running Challenges](#running-challenges)

### Misc

* [Contributing](https://github.com/akromnassir/Interactive-Python-Coding-Challanges-)
* [Credits](#credits)
* [Contact Info](#contact-info)
* [License](#license)






## Repo Structure

```
interactive-coding-challenges        # Repo
├─ arrays_strings                    # Category of challenges
│  ├─ rotation                       # Challenge folder
│  │  ├─ rotation_challenge.ipynb    # Challenge notebook
│  │  ├─ rotation_solution.ipynb     # Solution notebook
│  │  ├─ test_rotation.py            # Unit test*
│  ├─ compress
│  │  ├─ compress_challenge.ipynb
│  │  ├─ compress_solution.ipynb
│  │  ├─ test_compress.py
│  ├─ ...
├─ linked_lists
│  ├─ palindrome
│  │  └─ ...
│  ├─ ...
├─ ...
```

<i>\*The notebooks (.ipynb) read/write the associated unit test (.py) file.</i>


Run the notebook of challenges:

```
$ git clone  https://github.com/akromnassir/Interactive-Python-Coding-Challanges-.git
$ cd interactive-coding-challenges 
$ jupyter notebook
```

This will launch your web browser with the list of challenge categories:

* Navigate to the **Challenge Notebook** you wish to solve
* Run the cells within the challenge notebook (Cell->Run All)
    * This will result in an expected unit test error
* Solve the challenge and verify it passes the unit test
* Check out the accompanying **Solution Notebook** for further discussion



### Used Resources

* [Cracking the Coding Interview](http://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/098478280X) | [GitHub Solutions](https://github.com/gaylemcd/ctci)
* [Programming Interviews Exposed](http://www.amazon.com/gp/product/1118261364/)
* [The Algorithm Design Manual](http://www.amazon.com/Algorithm-Design-Manual-Steve-Skiena/dp/0387948600) | [Solutions](http://www.algorithm.cs.sunysb.edu/algowiki/index.php/The_Algorithms_Design_Manual_(Second_Edition))
* [CareerCup](http://www.careercup.com/)
* [Quora](http://www.quora.com/)
* [HackerRank](https://www.hackerrank.com)
* [LeetCode](https://leetcode.com/)

### Images

* [Arrays and Strings: nltk.org](http://www.nltk.org/images/string-slicing.png)
* [Linked Lists: wikipedia.org](https://upload.wikimedia.org/wikipedia/commons/6/6d/Singly-linked-list.svg)
* [Stacks: wikipedia.org](https://upload.wikimedia.org/wikipedia/commons/2/29/Data_stack.svg)
* [Queues: wikipedia.org](https://upload.wikimedia.org/wikipedia/commons/5/52/Data_Queue.svg)
* [Sorting: wikipedia.org](https://upload.wikimedia.org/wikipedia/commons/6/6a/Sorting_quicksort_anim.gif)
* [Recursion and Dynamic Programming: wikipedia.org](https://upload.wikimedia.org/wikipedia/commons/b/bf/PascalTriangleFibanacci.svg)
* [Graphs and Trees: wikipedia.org](https://upload.wikimedia.org/wikipedia/commons/f/f7/Binary_tree.svg)
* [Mathematics and Probability: wikipedia.org](https://upload.wikimedia.org/wikipedia/commons/d/d2/Gaussian_distribution_2.jpg)
* [Bit Manipulation: wikipedia.org](https://upload.wikimedia.org/wikipedia/commons/5/5c/Rotate_left_logically.svg)
* [Online Judges: topcoder.com](https://www.topcoder.com/wp-content/uploads/2014/05/topcoder_logo_home_sm.png)

## Contact Info

Feel free to contact me to discuss any issues, questions, or comments.

My contact info can be found on my https://github.com/akromnassir/ 

