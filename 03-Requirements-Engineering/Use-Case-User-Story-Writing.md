<img width="1024" height="1536" alt="ChatGPT Image Jul 23, 2026, 09_09_35 PM" src="https://github.com/user-attachments/assets/3968dda4-385a-4706-b245-71036b49e844" />

# 📋 Use Case & User Story Writing: Understanding What Users Need

Imagine you are building a **food delivery app**. 🍔📱

Before developers start coding, we need to understand:

👉 Who will use the app?
👉 What do they want to do?
👉 What should the system do?

This is where **Use Cases** and **User Stories** help.

---

# 🔹 What Is a User Story?

A **User Story** describes a feature from the user's point of view.

The common format is:

> **As a [user], I want [something], so that [reason].**

### Example:

> **As a customer, I want to search for restaurants so that I can easily find food I like.**

This tells us:

👤 **Who?** Customer
🎯 **What?** Search for restaurants
💡 **Why?** Find food easily

---

# 🛒 Example: Online Marketplace

### User Story:

> **As a customer, I want to add products to my cart so that I can buy multiple products together.**

This is simple and easy to understand.

---

# 🧩 The 3 Parts of a User Story

## 👤 1. User

Who wants the feature?

Examples:

👤 Customer
🏪 Seller
👨‍💼 Admin

---

## ⚙️ 2. Action

What does the user want to do?

Examples:

🔍 Search products
🛒 Add to cart
📦 Track order
🏪 Create a shop

---

## 🎯 3. Benefit

Why does the user want it?

Examples:

💡 To find products easily
💡 To buy multiple items
💡 To know the delivery status

---

# 📌 Good User Story Example

> **As a seller, I want to add products to my shop so that customers can view and purchase them.**

This is clear because we know:

👤 User: Seller
⚙️ Action: Add products
🎯 Benefit: Customers can buy products

---

# 🔹 What Is a Use Case?

A **Use Case** describes how a user interacts with a system to achieve a goal.

It usually contains more detail than a User Story.

### Example:

## Use Case: Place an Order

### Actor:

👤 Customer

### Goal:

Place an order successfully.

### Main Flow:

1. Customer logs in.
2. Customer searches for a product.
3. Customer selects the product.
4. Customer adds the product to the cart.
5. Customer clicks Checkout.
6. Customer enters the delivery address.
7. Customer makes payment.
8. System confirms the order.

---

# 🔄 Alternative Flow

What happens if something goes wrong?

### Payment Failed:

1. Customer tries to make payment.
2. Payment fails.
3. System shows an error message.
4. Customer tries another payment method.

This is an **Alternative Flow**.

---

# 🧩 Use Case Components

A Use Case may include:

👤 **Actor**
What person or system interacts with the system?

🎯 **Goal**
What does the actor want to achieve?

📝 **Precondition**
What must happen before the process starts?

🔄 **Main Flow**
What happens normally?

⚠️ **Alternative Flow**
What happens if something goes differently?

🏁 **Postcondition**
What happens after the process finishes?

---

# 🛒 Complete Use Case Example

## Use Case: Add Product to Cart

### Actor:

👤 Customer

### Goal:

Add a product to the shopping cart.

### Preconditions:

✅ Customer can access the marketplace.
✅ Product is available.

### Main Flow:

1. Customer searches for a product.
2. System displays the product.
3. Customer opens the product details.
4. Customer selects quantity.
5. Customer clicks "Add to Cart."
6. System adds the product to the cart.
7. System shows a confirmation message.

### Alternative Flow:

❌ Product is out of stock.

The system shows:

> "This product is currently unavailable."

### Postcondition:

🛒 Product is added to the customer's cart.

---

# 📊 User Story vs. Use Case

| User Story              | Use Case                  |
| ----------------------- | ------------------------- |
| Short and simple        | More detailed             |
| Describes user need     | Describes interaction     |
| Common in Agile         | Used in detailed analysis |
| Focuses on What and Why | Focuses on How            |

### Simple Example:

### User Story:

> As a customer, I want to track my order so that I know when it will arrive.

### Use Case:

1. Customer opens "My Orders."
2. Customer selects an order.
3. System retrieves tracking information.
4. System displays order status.
5. Customer views estimated delivery date.

---

# ⭐ INVEST Principle for User Stories

A good User Story should follow the **INVEST** principle.

---

## 🔹 I = Independent

The User Story should be as independent as possible.

### ❌ Bad:

> As a customer, I want to pay for an order after the payment system is completed.

This story depends too much on another story.

### ✅ Better:

> As a customer, I want to make a payment so that I can complete my order.

---

## 🔹 N = Negotiable

A User Story is not a final contract.

The team can discuss and improve the details.

### Example:

> As a customer, I want to pay online.

The team may discuss:

💳 Card payment?
📱 Mobile banking?
🏦 Bank transfer?

The exact details can be discussed.

---

## 🔹 V = Valuable

The User Story should provide value to the user or business.

### ❌ Weak:

> As a customer, I want the button to be blue.

This may not provide important value.

### ✅ Valuable:

> As a customer, I want to add products to my cart so that I can purchase them later.

---

## 🔹 E = Estimable

The development team should be able to estimate the work.

### ❌ Too unclear:

> Make the system very fast.

### ✅ Better:

> As a customer, I want the product search results to load quickly so that I can find products easily.

The team can discuss and estimate this requirement.

---

## 🔹 S = Small

A User Story should not be too large.

### ❌ Too Large:

> As a customer, I want to use the entire shopping system.

This includes many different features.

### ✅ Smaller Stories:

📝 Create Account
🔐 Login
🔍 Search Product
🛒 Add to Cart
💳 Make Payment
📦 Track Order

Smaller stories are easier to develop and test.

---

## 🔹 T = Testable

We should be able to test whether the User Story works.

### ❌ Not Testable:

> As a customer, I want a beautiful website.

"Beautiful" can mean different things to different people.

### ✅ Testable:

> As a customer, I want to search for products by name so that I can find products easily.

We can test:

🔍 Enter product name
⬇️
📋 System displays matching products

---

# 🎯 SMART Principle

SMART is another useful principle for defining clear goals and requirements.

SMART stands for:

### 🔹 S = Specific

Be clear about what you want.

### ❌ Vague:

> Improve the website.

### ✅ Specific:

> Improve the product search feature.

---

### 🔹 M = Measurable

We should be able to measure success.

### ❌ Not Measurable:

> Make the website faster.

### ✅ Measurable:

> Product search results should load within 2 seconds.

---

### 🔹 A = Achievable

The goal should be realistic.

### ❌ Unrealistic:

> Build a complete marketplace in one day.

### ✅ Achievable:

> Develop the basic product search feature within two weeks.

---

### 🔹 R = Relevant

The requirement should support the business goal.

### Business Goal:

🎯 Increase online sales.

### Relevant Requirement:

> Improve the checkout process to reduce abandoned carts.

---

### 🔹 T = Time-Bound

There should be a deadline or time period.

### ❌ No Time:

> Improve the checkout process.

### ✅ Time-Bound:

> Improve the checkout process before the next product release.

---

# 🧩 INVEST vs. SMART

These principles are related but used for slightly different purposes.

### ⭐ INVEST

Mainly helps us write:

📋 Better User Stories

It checks whether a User Story is:

✅ Independent
✅ Negotiable
✅ Valuable
✅ Estimable
✅ Small
✅ Testable

---

### 🎯 SMART

Mainly helps us create:

🎯 Clear Goals
📊 Measurable Objectives
📋 Requirements

It checks whether something is:

✅ Specific
✅ Measurable
✅ Achievable
✅ Relevant
✅ Time-Bound

---

# 📱 Complete Example

### Business Goal:

🎯 Increase online shopping orders.

### SMART Objective:

> Increase completed orders by 20% within the next three months by improving the checkout process.

### User Story:

> **As a customer, I want a simple checkout process so that I can complete my order quickly.**

### Acceptance Criteria:

✅ Customer can review the cart.
✅ Customer can enter a delivery address.
✅ Customer can select a payment method.
✅ Customer can confirm the order.
✅ The order confirmation is displayed after successful payment.

Now the requirement is:

✔️ Clear
✔️ Valuable
✔️ Measurable
✔️ Testable

---

# 👨‍💼 Why Is This Important for a Business Analyst?

A Business Analyst must convert:

💡 Business Needs
⬇️
📋 Requirements
⬇️
👥 User Stories / Use Cases
⬇️
💻 Software Features

For example:

### Business Need:

> Customers are abandoning their shopping carts.

### Analysis:

🔍 The checkout process is too complicated.

### User Story:

> As a customer, I want a simple checkout process so that I can complete my purchase easily.

### Acceptance Criteria:

✅ Fewer steps
✅ Clear payment options
✅ Order confirmation
✅ Error messages when payment fails

This gives developers a clear understanding of what to build.

---

# 🎯 The Main Idea

Imagine you tell a developer:

> "Build something good for customers." ❌

This is not clear.

But if you say:

> **As a customer, I want to track my order so that I know when it will arrive.** ✅

Now everyone understands the requirement better.

A good requirement should answer:

👤 **Who wants it?**
⚙️ **What do they want?**
🎯 **Why do they want it?**
✅ **How do we know it works?**

> **User Stories explain what users need. Use Cases explain how users interact with the system. INVEST helps us write better User Stories, while SMART helps us create clear and measurable goals.** 🚀

#BusinessAnalysis #BusinessAnalyst #UserStories #UseCase #INVEST #SMARTGoals #RequirementsEngineering #Agile #SoftwareEngineering #ProductManagement
