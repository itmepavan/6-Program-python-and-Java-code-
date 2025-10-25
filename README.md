✅ *Programming Basics – Part 6: Sets* 📚🧠

✅ *What is a Set?*  
A *set* is a collection of *unique, unordered* elements. It doesn’t allow duplicates.

➊ *How to Create a Set*

📍 *Python*  
```python
fruits = {"apple", "banana", "cherry"}
```

📍 *Java*  
```java
Set<String> fruits = new HashSet<>();
fruits.add("apple");
fruits.add("banana");
fruits.add("cherry");
```

➋ *Properties of Sets*  
✔️ No duplicate values  
✔️ No guaranteed order  
✔️ Fast membership tests (`in`, `contains`)

➌ *Add Elements*

📍 *Python:* `fruits.add("mango")`  
📍 *Java:* `fruits.add("mango");`

➍ *Remove Elements*

📍 *Python:* `fruits.remove("banana")`  
📍 *Java:* `fruits.remove("banana");`  

➎ *Check Membership*

📍 *Python:* `"apple" in fruits`  
📍 *Java:* `fruits.contains("apple")`  

➏ *Loop Through a Set*

📍 *Python:*  
```python
for fruit in fruits:
    print(fruit)
```

📍 *Java:*  
```java
for(String fruit : fruits) {
    System.out.println(fruit);
}
```

➐ *Why Use Sets?*

- Eliminate duplicates from data  
- Fast checks for existence
- Efficient in set operations (union, intersection)

➑ *Real-World Uses of Sets*

- Store unique tags or categories  
- Track visited pages  
- Remove duplicates from a list  
- Fast user lookup in access control systoperations fast!*  
