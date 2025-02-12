# Buggy Checkout System - Activity & Instructions

## Overview
This project is a **buggy checkout system** designed as an educational activity to help students practice **debugging and logical problem-solving** in coding. The checkout system allows users to select quantities for shirts, pants, and shoes, apply a discount code, and calculate the total. However, it contains a **logic error** that must be identified and fixed.

## Learning Objectives
- Understand the importance of **logical sequencing** in calculations.
- Identify and correct **errors in tax and discount application**.
- Practice **debugging** in JavaScript.

## Setup Instructions
1. **Download or Fork the Repository**
   - Clone the repository or download the HTML, CSS, and JavaScript files.

2. **Open `index.html` in a Browser**
   - Run the application in a browser to test the checkout system.

3. **Interact with the App**
   - Adjust the **quantity** of shirts, pants, and shoes.
   - Enter a discount code (`SAVE10`) and press **Checkout**.
   - Observe the total calculation.

## Activity Steps
1. **Analyze the Bug**
   - Identify the error in the **order of operations** for calculating the total.
   - Notice that **tax is applied before the discount**, leading to an incorrect final amount.

2. **Plan the Fix**
   - Write down the correct order:
     1. Calculate **subtotal** (sum of item prices based on quantity).
     2. Apply **discount first**, if applicable.
     3. Calculate **sales tax on the discounted total**.
     4. Add tax to get the **final total**.

3. **Implement the Fix**
   - Modify the JavaScript function `calculateTotal()` to apply the discount **before** calculating tax.
   - Test different **quantities and discount codes** to verify the fix.

4. **Discuss & Optimize**
   - What would happen if **tax rates changed**?
   - How can we make the function **more modular**?
   - Could we add **new features** like free shipping for orders over $100?

## Expected Outcome
After debugging, the checkout system should correctly calculate:
- **Subtotal** (based on user-selected quantities)
- **Discounted subtotal** (if a discount code is applied)
- **Tax** (calculated on the discounted subtotal)
- **Final total** (subtotal - discount + tax)

## Extensions
- Add **automated tests** to validate different discount codes and quantities.
- Allow users to **remove items** from their cart.
- Introduce **multiple discount tiers** (e.g., 15% off for orders over $200).

---
**Happy Debugging! 🛠️💡**
