# 2D Reflection in Computer Graphics

## 📌 Description

2D Reflection is a basic transformation technique used in computer graphics to flip an object across a given axis. This transformation changes the orientation of the object while maintaining its shape and size.

Common types of 2D reflection:
- **Over X-axis:** Changes the sign of the y-coordinate → `(x, -y)`
- **Over Y-axis:** Changes the sign of the x-coordinate → `(-x, y)`
- **Over Origin:** Changes both x and y signs → `(-x, -y)`
- **Over Line y = x:** Swaps x and y → `(y, x)`

Reflection is widely used in computer graphics, image processing, and game development to achieve symmetrical effects or mirror images.

---

## 🧮 Algorithm: 2D Reflection of a Square

**Step 1:** Define the original square by listing its corner points `(x, y)`.

**Step 2:** Reflect over the X-axis:  
For each point `(x, y)`, calculate `(x, -y)` and store in a new list.

**Step 3:** Reflect over the Y-axis:  
For each point `(x, y)`, calculate `(-x, y)` and store in another list.

**Step 4:** To close the squares visually, add the first point again at the end of each list.

**Step 5:** Separate the x and y coordinates of:
- Original square
- Reflected over X-axis
- Reflected over Y-axis

**Step 6:** Plot all three shapes using Matplotlib with different colors and labels.

**Step 7:** Add axis lines, grid, labels, and a title to make the reflection clear.

---

## 🖼 Output

The output shows:
- The original square 
- The square reflected over the X-axis 
- The square reflected over the Y-axis 

---

## 🛠 Technologies Used

- Python
- Matplotlib
