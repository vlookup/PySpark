# PySpark DataFrame Schema Demo

**All data used in this project is synthetic and created solely for demonstration purposes.**

This project demonstrates how to create a PySpark DataFrame from in‑memory Python data, define column names, and inspect the resulting schema. It serves as a simple, foundational example of working with Spark’s DataFrame API.

---

## 🚀 Project Overview

The script initializes a local SparkSession, constructs a small dataset directly in Python, and loads it into a Spark DataFrame using an explicit schema defined by a list of column names. It then prints the schema to verify data types and structure.

This example highlights:

- Creating a SparkSession  
- Building a DataFrame from Python lists  
- Assigning column names  
- Inspecting schema with `printSchema()`  

---

## 🧱 Technologies Used

- **PySpark**
- **Python 3.x**

---

## 🧠 What the Script Does

### **1. Creates a SparkSession**
Runs Spark locally using:

```python
spark = SparkSession.builder.master("local").appName("test").getOrCreate()
