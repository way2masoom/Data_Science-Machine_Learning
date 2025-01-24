# Data_Science-Machine_Learning

# Setting Up Python Environment in VS Code for Data Science & Machine Learning

Creating a Python virtual environment ensures that your projects are isolated and dependencies are managed effectively. Follow these steps to set up your environment on Windows, Linux, or macOS.

---

## **For Windows**

1. **Create a Virtual Environment:**  
   Run the following command in your terminal:  
   ```bash
   python -m venv myenv
   ```

2. **Activate the Virtual Environment:**  
   Navigate to the `Scripts` folder inside your environment and activate it:  
   ```bash
   myenv\Scripts\activate
   ```

3. Once activated, you can start installing dependencies for your project.

---

## **For Linux or macOS**

1. **Install Virtualenv:**  
   Ensure `virtualenv` is installed by running:  
   ```bash
   pip install virtualenv
   ```

2. **Create a Virtual Environment:**  
   Use the following command to create a virtual environment:  
   ```bash
   virtualenv -p python3 virtual_env
   ```

3. **Activate the Virtual Environment:**  
   Activate the environment using the command:  
   ```bash
   source virtual_env/bin/activate
   ```

4. You are now ready to install your project dependencies.

---


