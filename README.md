# 🐍 Python List Operations Assignment

## 📌 Description
This project demonstrates basic **Python list operations** — appending, inserting, extending, removing, sorting, and finding the index of a value — using a step-by-step approach.

---

## 📝 Steps Performed
1. **Create** an empty list called `my_list`.
2. **Append** the values `10`, `20`, `30`, and `40` to the list.
3. **Insert** the value `15` at the second position in the list.
4. **Extend** `my_list` with another list `[50, 60, 70]`.
5. **Remove** the last element from `my_list`.
6. **Sort** the list in ascending order.
7. **Find and print** the index of the value `30` in `my_list`.

---

## 💻 Code Example

```python
 # 1. Create an empty list
my_list = []

# 2. Append 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
print(my_list)

# 3. Insert 15 at the second position (index 1)
my_list.insert(1, 15)
print(my_list)

# 4. Extend with another list [50, 60, 70]
new_list = [50, 60,70]
my_list.extend(new_list)
print(my_list)

# 5. Remove the last element
my_list.remove(70)

# 6. Sort in ascending order
my_list.sort()
print(my_list)

# 7. Find and print the index of value 30
index_30 = my_list.index(30)
print("Index of 30:", index_30)

# Print final list for clarity
print("Final list:", my_list)


## 🚀 How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
Navigate to the project folder:

bash
Copy
Edit
cd your-repo-name
Run the Python file:

bash
Copy
Edit
python list_operations.py
##📜 License
This project is open-source and available under the MIT License.
