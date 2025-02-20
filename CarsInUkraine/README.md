# Vehicle Registration in Ukraine Dataset

## 📌 Overview

This dataset contains information about vehicle registration in Ukraine from the [official source](https://data.gov.ua/dataset/06779371-308f-42d7-895e-5a39833375f0). It is designed for analyzing, downloading, and processing data to explore trends in vehicle ownership, including identifying the most popular car colors and brands over a period of time from 2013 to 2024. The data was processed using Jupyter Notebook using the Pandas library. Flourish service was used for visualization.

---

## 🎯 Research Objectives

- 🛒 Studying car purchases in Ukraine.
- 🚗 Identifying the most popular car brands.
- 🎨 Determining the most popular car colors.
- 🗓️ Analyzing vehicle registration dynamics over time.
- 🌱 Examining trends in fuel types, including electric vehicles.

---

## 📑 Field Descriptions

| **Field Name**       | **Description**                                                                 |
|--------------------- |------------------------------------------------------------------------------- |
| `person`            | Type of owner (individual or legal entity).                                    |
| `reg_addr_koatuu`   | Code of the owner's territorial location according to the KOATUU classifier.  |
| `oper_code`         | Registration operation code.                                                   |
| `oper_name`         | Name of the operation (e.g., initial registration, re-registration, etc.).    |
| `d_reg`             | Vehicle registration date.                                                     |
| `dep_code`          | Code of the department that performed the registration.                        |
| `dep`               | Name of the department that performed the registration.                        |
| `brand`             | Car brand (e.g., Toyota, BMW, Mercedes).                                       |
| `model`             | Car model (e.g., Camry, X5, C-Class).                                          |
| `make_year`         | Year of manufacture.                                                           |
| `color`             | Car color.                                                                     |
| `kind`              | Type of vehicle (e.g., passenger, truck, bus).                                |
| `body`              | Body type (e.g., sedan, hatchback, station wagon).                            |
| `purpose`           | Vehicle purpose (e.g., personal, commercial, special).                        |
| `fuel`              | Type of fuel (e.g., gasoline, diesel, electric, gas).                         |
| `capacity`          | Engine capacity (in cubic centimeters, if applicable).                        |
| `own_weight`        | Vehicle's own weight (in kilograms).                                           |
| `total_weight`      | Vehicle's total weight (in kilograms).                                         |
| `n_reg_new`         | New vehicle registration number.                                               |

---

№№ 🧩 Fields Used for Analysis

The following fields are used for analysis:

- PERSON
- OPER_NAME
- D_REG
- BRAND
- MODEL
- MAKE_YEAR
- COLOR
- KIND
- BODY
- PURPOSE
- FUEL

---

## 📊 Possible Analysis Directions

- 📈 Analyzing trends in new and used vehicle registrations.
- 🚗 Determining the most common car brands and models in Ukraine.
- 💡 Investigating the rise of electric vehicles and alternative fuel types.
- 🎨 Identifying the most preferred vehicle colors among Ukrainians.
- 🌍 Studying the correlation between economic factors and car purchases.

---

## 📈 [Interactive Visualization](https://public.flourish.studio/story/2894458/)

