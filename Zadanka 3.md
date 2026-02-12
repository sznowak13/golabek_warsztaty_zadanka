**Exercise: Read messy data and clean it using a list.** 
Task: 
1. Create a text file named raw_data.txt with several lines of numbers, some with extra spaces and some blank lines.
2. Read the file into Python.
3. Use a for loop to strip the whitespace and ignore the blank lines. 4. Store the cleaned integers in a list and print the final list.
raw_data:
```
10
  25
    
40

   100
  
5
invalid_line
  60
```

---


**Exercise: Use tuples to represent fixed "records" and save them.**
Task:
1. Create a list of tuples, where each tuple represents an item: (name, quantity, price). Example: ("Hammer", 10, 15.99).
2. Open a new file inventory_report.txt for writing.
3. Use a for loop to iterate through the tuples and write a formatted string (<name> x <quantity> for <price> PLN) for each item to the file.

```python
inventory_data = [
    ("Hammer", 15, 12.50),
    ("Screwdriver", 42, 5.99),
    ("Power Drill", 8, 89.00),
    ("Nails (100pk)", 120, 3.50),
    ("Level", 5, 22.75)
]
```

---

**Exercise: Use a while loop to search through a file until a condition is met.**
1. Given a large text file system.log with various lines of text.
2. Use a while  loop and .readline() to read the file one line at a time.
3. If a line contains the word "ERROR", print the line and break the loop immediately.
4. If you reach the end of the file without finding an error, print "Log Clean" and exit the loop.

system_log.log:
```
[001] INFO: Service started.
[002] DEBUG: Checking disk space.
[003] INFO: Disk space 85% free.
[004] WARN: Latency spike detected on API gateway.
[005] INFO: Retrying connection...
[006] INFO: Retrying connection...
[007] ERROR: Timeout reached. Gateway unreachable.
[008] INFO: Shutdown sequence started.
[009] DEBUG: Closing sockets.
```
Larger log file can be found on the repo:  [larger_log.log](https://github.com/sznowak13/golabek_warsztaty_zadanka/blob/main/large_log.log)
