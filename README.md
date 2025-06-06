# 🚗 Used Car Pricing API

**A modern NestJS backend for estimating used car prices, collecting sales data, and empowering both car owners and admins.**

---

## 📋 **Project Overview**

Do you want to sell your car but don't know how much it's worth?  
This project is a simple yet powerful API to help users get a realistic estimate for their used cars.  
**Sign up, get an estimate, report your real sale, and help improve future price accuracy!**

---

## ✨ **Features**

- **🔐 User Authentication:**  
  Sign up and log in with email & password for a secure experience.

- **💸 Get Car Price Estimates:**  
  Instantly receive an estimated value for your vehicle based on:

  - Make
  - Model
  - Year
  - Mileage

- **📝 Submit Real Sales Reports:**  
  After selling your car, submit the actual sale price to enhance our dataset and accuracy.

- **🧑‍⚖️ Admin Moderation:**

  - Admin users review and approve reported sales before they're included in the price dataset.
  - Prevents spam, fake sales, or unrealistic prices.

- **📊 Data-driven Improvements:**  
  More real sales → More accurate price estimates for everyone!

---

## 🛠️ **Tech Stack**

- **Backend Framework:** [NestJS](https://nestjs.com/)
- **Language:** TypeScript
- **Authentication:** JWT (JSON Web Token)
- **Database:** (to be added, e.g., PostgreSQL or MongoDB)
- **Validation & Security:** class-validator, class-transformer

---

## 🚦 **API Flow**

1. **User Registration & Login**
2. **Submit Car Details** (make, model, year, mileage) → **Get Instant Price Estimate**
3. **Report Actual Sale** (after you sell your car)
4. **Admin Reviews & Approves Reports**
5. **Approved reports improve future price estimations!**

---

## 🧑‍💻 **How to Run Locally**

```bash
# Clone the repository
git clone https://github.com/ShayanRezvanii/mycv.git

# Go to project directory (if backend is in a subfolder)
cd mycv/backend

# Install dependencies
npm install

# Start the development server
npm run start:dev
```
