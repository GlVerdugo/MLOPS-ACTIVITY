# Virtual Environments
Alumno: Guadalupe López Verdugo
Matricula:A01688491

Follow the instructions below to do the activity.
### Run the existing notebook
1. Create a virtual environment with Python 3.10.9 (windows)
    * Create venv
        ```
        py3.10 -m venv venv310
        ```

    * Activate the virtual environment
    * Go to the SCRIPTS folder and run the file activate

        ```
        1. cd venv310
        2. cd Scripts
        3. activate
        ```

2. Install libraries
    Run the following command to install the other libraries.

    ```bash
    pip install -r ACTIVIDAD SESION3\requirements-310.txt
    ```
    Verify the installation with this command:
    ```bash
    pip freeze
    ```
    Output:
    <details open>
    <summary>List of packages, click to collapse</summary>
  
        cycler==0.11.0
        fonttools==4.41.1
        joblib==1.3.1
        kiwisolver==1.4.4
        matplotlib==3.7.2
        numpy==1.25.1
        packaging==23.1
        pandas==2.0.3
        Pillow==10.0.0
        pyparsing==3.1.0
        python-dateutil==2.8.2
        pytz==2023.3
        scikit-learn==1.1.1
        scipy==1.11.1
        seaborn==0.12.2
        setuptools-scm==7.1.0
        six==1.16.0
        threadpoolctl==3.2.0
        tomli==2.0.1
        typing_extensions==4.7.1
         tzdata==2023.3
        
    </details>
    

4. Open the `SESION3\end_to_end_machine_learning_project_3-10.ipynb` notebook and click on `Run All`. 
    > **IMPORTANT!**  
    Do not forget to select the Python 3.9.10 kernel you have already created.

    If everything was ok, you should be able to see the last cell with this output:
    ```bash
    Predictions:	 [263527.   331884.02 221119.   ... 105722.   213199.   459125.66]
    ```
**Congrats, the notebook is running in a virtual environment with Python 3.10.9!**
