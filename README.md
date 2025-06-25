# Assignment-11.1 - Used Car Price Analysis

## 🔍 Purpose
To help used car dealerships understand what features make a car more or less expensive, and provide a simple pricing guide based on patterns from over 100,000 past listings.

---

## 📈 What We Found

After reviewing thousands of real used car listings, we found clear patterns in what drives vehicle price:

- **Newer cars cost more.** The year of the car is the strongest predictor of price.
- **Cars with fewer miles are worth more.** Odometer readings were the second most important factor.
- **Engine size matters.** Cars with more cylinders (like V6 or V8) tend to be priced higher.
- **Condition adds value.** Cars listed as "excellent," "like new," or "new" are priced higher than "fair" or "good."

Other features that play a role:
- **Fuel type** (gas, hybrid, electric)
- **Body style** (truck, sedan, SUV, etc.)
- **Color and transmission type** have a smaller effect but still contribute.

---

## 📊 Why This Matters

These patterns help us estimate what a fair price might be for any car, based on its basic features. This can help sales teams:

- **Set competitive prices** when listing inventory  
- **Spot undervalued trade-ins**  
- **Have more confidence** when discussing price with customers

---

## 🗓️ How You Can Use This

We've built a pricing model that takes into account these key details:

- Year  
- Mileage  
- Engine type (cylinders)  
- Vehicle condition  
- Body type  

The model gives an estimated price range that reflects what similar cars sold for across the country.

---

## 📂 What's in This Folder?

| File                       | Description                                      |
|---------------------------|--------------------------------------------------|
| `used_car_modeling.ipynb` | The full notebook showing our process and results |
| `data/vehicles.csv`       | The cleaned dataset we analyzed                  |
| `README.md`               | This file                                        |

---

## 📅 View the Notebook

To see the full pricing analysis:  
👉 [Click here to open the notebook](./prompt_II.ipynb)

---

If you're interested in using this model to help price your inventory or want a simplified tool to test it out, let us know!

