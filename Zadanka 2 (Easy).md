#### 1. The "Off-by-One" Hunter (For Loops & Slicing)

**The Setup:** Give students a string and ask them to print every 3-character "window" or "frame."

* **Learning Point:** Managing loop boundaries so the slice doesn't return empty strings at the end of the sequence.

#### 2. The Unique Accumulator (Lists & If Statements)

**The Setup:** Provide a list with many duplicates and ask them to build a new list containing only unique items **without** using `set()`.

* **Learning Point:** The computational cost of `if item not in new_list` (O(n) inside a loop) and the importance of membership testing.

#### 3. The Sentinel Loop (While Loops & Data Types)

**The Setup:** A loop that asks for integers to sum them up, but stops if the user types "done".

* **Learning Point:** Handling `ValueError` when `int()` is called on a string, and how to structure a "Loop and a Half."

#### 4. The List Shifter (Lists & Modulo)

**The Setup:** Take a list and an integer `n`, then "rotate" the list to the right by `n` positions.

* **Learning Point:** Using the modulo operator `%` for wrap-around logic and the power of list concatenation (`list[n:] + list[:n]`).

#### 5. The Profile Formatter (String Manipulation & F-Strings)

**The Setup:** A list of dictionaries (or tuples) containing messy names and floating-point IDs.

* **Learning Point:** Using f-string padding and alignment (e.g., `{name:<10} | {id:0>5}`) to create a perfectly aligned terminal table.

---


### Basic exercises

### Exercise 1: The Temperature Filter (Variables & If)

**Goal:** Practice basic conditional logic and variable assignment.
**Task:** 1. Create a variable called `threshold` and set it to `30`.
2. Ask the user to input the current temperature.
3. **If** the temperature is greater than the `threshold`, print "It's too hot!".
4. **Otherwise**, print "The temperature is fine."

---

### Exercise 2: The Shopping List (Lists & Loops)

**Goal:** Iterate through a list and format output.
**Task:**

1. Create a **list** named `cart` containing: `"apples"`, `"bread"`, and `"milk"`.
2. Use a **for loop** to print each item in the list.
3. **Bonus:** Print the message as "Item: [item_name]" for each one.

---

### Exercise 3: The Even Number Finder (Loops, Ifs, & Lists)

**Goal:** Combine all concepts to filter data.
**Task:**

1. Given a list of numbers: `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`.
2. Create an empty list called `evens`.
3. Use a **for loop** to check each number.
4. **If** the number is even (use `number % 2 == 0`), add it to the `evens` list using `.append()`.
5. After the loop, print the final `evens` list.

---
