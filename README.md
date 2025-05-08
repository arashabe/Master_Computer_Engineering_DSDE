# [Computer Engineering (Master's Degree)](https://unibg.coursecatalogue.cineca.it/corsi/2024/89/insegnamenti/8865?schemaid=77076)

## Course Description
The Master's Degree in Computer Engineering aims to provide students with a versatile professional training capable of addressing the many technical, methodological, and economic aspects that characterize the development of information technology, its application to the construction of complex computer systems, and its use in the management and analysis of large datasets.

A characteristic of the Computer Engineer will be to possess, in addition to a solid base of technical skills in information engineering, guaranteed by the characterizing educational activities of the class, in-depth knowledge on topics such as: the mathematical principles underlying the construction of algorithms and efficient IT solutions, the construction of models for system analysis for effective system monitoring and control, the principles of device design at different levels of integration, the definition of strategies for managing large projects, and advanced knowledge on the use of statistical techniques to improve the quality of processes based on collections of large datasets.


## Data Science and Data Engineering (DSDE) Pathway

### DSDE Pathway Description
The DSDE pathway provides advanced knowledge of engineering, mathematical, and statistical techniques for the acquisition, integration, management, analysis, and visualization of large datasets. It includes courses related to statistical methods and advanced data management technologies.

**Selected Courses:**

- Models and Algorithms for Optimization
- Artificial Intelligence
- Advanced Programming
- Design, Algorithms and Computability
- Information and Transmission Theory
- Deep Learning
- Adaptive Learning, Estimation and Supervision of Dynamical Systems
- Advanced Data Management
- Databases 2
- Formal Languages and Compilers
- Telecommunication Networks
- Statistical Learning and Optimization
- Statistics for High Dimensional Data




## Specific Courses and Related Projects

### [Design, Algorithms, and Computability](https://unibg.coursecatalogue.cineca.it/insegnamenti/2024/38090-MOD1/2021/8865/89?coorte=2024&schemaid=77076&adCodRadice=38090)


#### Course Description
The course covers comprehensive design and analysis methodologies, including both large-scale and small-scale system designs. Large-scale design focuses on subdividing software into functional components and ensuring efficient data exchange via APIs in distributed environments, covering topics such as agile development, requirement management, UML-based design, software architecture quality analysis, advanced design patterns, and object-oriented development for desktop and mobile applications. In contrast, small-scale design delves into the detailed analysis and definition of individual components and algorithms, addressing algorithms and data structures, computational complexity, Java implementation, sorting algorithms, tree and graph management, and algorithm design methodologies. Additionally, the course explores the theory of computability, encompassing fundamental concepts, theorems, and Turing machines.

#### Project
A web app designed to facilitate communication and collaboration among university students. Users can register, log in, update their profiles, and send notifications to form study groups based on common interests. The system does not directly manage students but allows them to interact and organize themselves into study groups autonomously. The app follows the MVC (Model-View-Controller) pattern to separate concerns and enhance maintainability.

**Technologies Used:** Spring Boot, Spring Security, Thymeleaf, Bootstrap, H2 Database, JUnit, Playwright, Postman, Maven.

**Link to Project on GitHub:** [Link to the project](https://github.com/arashabe/SpringMVCWebApp)

---

### [Database 2](https://unibg.coursecatalogue.cineca.it/insegnamenti/2024/8244_43613_12905/2021/8244/89?coorte=2023&schemaid=77316)

#### Course Description
During the Database 2 course, we delved into numerous topics, including Transactional Systems, Internal Architecture of a Relational Server, Distributed and Parallel Architectures, Active Databases, and XML Databases.

#### Project
The project focuses on active databases, Event/Condition/Action (ECA) rules, and the integration of XML data with relational databases. The project revolves around analyzing a COVID-19 clinical studies dataset from Kaggle, which contains over 5000 XML files. Each file represents a study, with details such as title, sponsor/collaborators, status, start and completion dates, and other metadata.

The goal of this project is to design and implement a database system that leverages SQL Server, XML storage, and advanced querying techniques such as XQuery to automate data extraction, maintenance, and updates. This aligns with the concepts learned in the course, specifically focusing on triggers, active rules, and XML data processing in relational databases.

**Technologies Used:** SQL Server, BaseX, XQuery, Triggers, Stored Procedures.

**Link to Project on GitHub:** [Link to the project](https://github.com/arashabe/covid-clinical-xml-db-xquery)

---

### [Formal Languages and Compilers](https://unibg.coursecatalogue.cineca.it/insegnamenti/2023/3212_35538_10011/2021/3212/89?coorte=2022&schemaid=68842)

#### Course Description
In the Formal Languages and Compilers course, we explored a wide range of fundamental theoretical and practical concepts for understanding and implementing programming languages and compilers. The main topics of the course include:

- **Basic Concepts:** Introduction to alphabets, strings, languages, and operations on them.
- **Regular Expressions and Languages:** Study of regular expressions, their composition rules, and the properties of regular languages.
- **Finite State Automata:** Exploration of deterministic (DFA) and non-deterministic (NFA) automata, including those with ε-moves.
- **BNF (Backus-Naur Form) Grammars:** Analysis of formal grammars, derivation, parse tree construction, and parsing techniques such as LL(1), LR(0), and LALR(1).


#### Project
This project aims to create a code analyzer capable of detecting lexical, syntactic, and semantic errors in a simple programming language using a custom Java-like grammar.

The grammar, while not complete, was designed to explore the capabilities of ANTLR4 and demonstrate how to bridge theoretical concepts with practical applications. The project aims to showcase the process of building a lexer and parser for a Java-like language, integrating these components with a PyQt5-based user interface to allow interactive analysis of code.

The analyzer uses ANTLR4 to generate the lexer and parser, while the user interface (GUI) is built using PyQt5, providing a platform to visualize and correct errors in the source code.

The application allows users to:
- Perform tokenization of source code through a lexer generated by ANTLR.
- Analyze the syntactic structure of the code with a parser and create a syntax tree.
- Conduct semantic checks on the code using a visitor pattern to verify the validity of declarations and operations.
- Provide an interactive graphical interface to load code, view errors, and easily correct them.

**Technologies Used:** Python 3.x, PyQt5, ANTLR4

**Link to Project on GitHub:** [Link to the project](https://github.com/arashabe/ANTLR4-BugBuster)

---

### [Adaptive Learning, Estimation And Supervision Of Dynamical Systems](https://unibg.coursecatalogue.cineca.it/insegnamenti/2024/8244_43621_16329/2021/8244/89?coorte=2023&schemaid=77316)

#### Course Description
In the Adaptive Learning, Estimation And Supervision Of Dynamical Systems course, we explored a diverse range of topics and methodologies essential for understanding and implementing adaptive learning and estimation techniques in dynamic systems. The main topics of the course include:

- **Recursive Least Squares Algorithm (RLS):** Fundamental concepts and practical applications.
- **Instrumental Variables (IV):** Methods and their significance in dynamic system estimation.
- **Oblivion Factor:** Techniques for handling time-variant systems.
- **Least Mean Squares Algorithm (LMS):** Overview and applications in adaptive filtering.
- **PEM Identification:** Approaches for identifying systems within a closed-loop setting and comparison with open-loop identification.
- **Review Of Linear Algebra Concepts:** Essential theories and applications in estimation.
- **State Space Modeling:** Estimation of dynamic models using N4SID and MOESP methods, and their extension to MIMO systems.
- **Model-Based Fault Diagnosis:** Introduction to fault diagnosis, including additive and multiplicative faults, parity space, and observer approaches.
- **Robust Diagnosis:** Strategies for fault diagnosis against disturbances, signal-based fault diagnosis, and knowledge-based approaches.
- **Statistical Process Monitoring (SPM):** Techniques for monitoring processes and identifying faults using the RLS-based approach.

#### Project
This project aims to study and reproduce the results of the paper: **[A Robust Variable Forgetting Factor Recursive Least-Squares Algorithm For System Identification](https://ieeexplore.ieee.org/document/4639569)** by Constantin Paleologu, Jacob Benesty, And Silviu Ciochină.

The objective is to demonstrate the performance of the VFF-RLS algorithm in system identification tasks, particularly in the presence of noise and abrupt system changes. The project involves implementing the VFF-RLS algorithm in MATLAB, analyzing its performance, and comparing the results with those presented in the paper.

**Technologies Used:** MATLAB

**Link to Project on GitHub:** [Link to the project](https://github.com/arashabe/Variable-Forgetting-Factor-Recursive-Least-Squares)

---


### [Statistics for High Dimensional Data and CompStat Lab](https://unibg.coursecatalogue.cineca.it/insegnamenti/2024/8244_43632_21827/2021/8244/89?coorte=2023&schemaid=77318)

#### Course Description
The Statistics for High Dimensional Data and CompStat Lab course provides a comprehensive foundation in analyzing spatio-temporal data sets—datasets associated with phenomena evolving across space and time. The course focuses on statistical methodologies and modeling techniques designed to capture spatial and temporal correlations, predict outcomes, and quantify prediction uncertainties. 

Students gain hands-on experience with the **MATLAB** and **R** programming environments, enabling them to estimate spatio-temporal statistical models and carry out spatial and temporal predictions effectively.

Key topics covered include:
- **Spatio-Temporal Data Analysis:** Methods for understanding spatial and temporal dependencies.
- **Statistical Modeling:** Tools for describing correlations and uncertainty in spatio-temporal datasets.
- **Predictive Modeling:** Techniques for forecasting outcomes in space and time.
- **Software Utilization:** Practical experience with MATLAB and R for spatio-temporal analysis.

#### Project
This project focuses on analyzing Washington, DC’s bike-sharing system by employing spatio-temporal models to uncover demand patterns and enhance urban mobility. The study integrates bike rental data with weather and temporal variables to evaluate the effects of external factors on usage patterns. Additionally, two predictive models are compared for accuracy: the **Dynamic Coregionalization Model (DCM)** and the **Hidden Dynamic Geostatistical Model (HDGM)**. 

**Objectives:**
- Investigate the influence of weather and time on bike-sharing demand.
- Compare the predictive accuracy of DCM and HDGM models.
- Develop data-driven strategies for optimizing bike allocation and improving service efficiency.

**Technologies and Tools Used:**
- **Data Preprocessing & EDA:** Cleaned and analyzed data using Python libraries like Pandas, NumPy, and Matplotlib/Seaborn.
- **Modeling Approaches:**
  - **DCM:** A hierarchical model capturing spatio-temporal dependencies.
  - **HDGM:** A latent process model for dynamic geospatial patterns.
- **Tools:** Implemented and validated the models in MATLAB (D-STEM v2) using cross-validation.


**Link to Project on GitHub:** [Link to the project](https://github.com/arashabe/BikeSpatioTemporal-Analysis)

---

### [Statistical Learning](https://unibg.coursecatalogue.cineca.it/insegnamenti/2024/38091-MOD2/2021/8865/89?coorte=2024&adCodRadice=38091)

#### **Course Description**
The **Statistical Learning** course provides students with essential methods and tools to extract meaningful insights from complex datasets for decision-making. The course emphasizes understanding dataset complexity, recognizing correlation structures, selecting appropriate methodologies for information extraction, and implementing algorithms efficiently.

Students develop practical skills in **data preprocessing, classification, clustering, regression techniques, and model validation**, applying various statistical learning approaches to real-world problems.

Key topics covered include:
- **Regression Shrinkage Methods:** Stepwise regression, Ridge regression, and Lasso.
- **Classification Techniques:** Linear discriminant analysis, logistic regression.
- **Clustering Methods:** Unsupervised learning approaches for grouping data.
- **Kernel Smoothing:** Non-parametric techniques for pattern recognition.
- **Polynomial & Spline Models:** Advanced regression techniques.
- **Functional Data & Regression:** Methods for analyzing functional datasets.
- **Model Validation & Selection:** Strategies for evaluating model effectiveness.
- **Monte Carlo & Bootstrap Methods:** Simulation-based techniques for statistical inference.

#### **Project**
This project focuses on estimating **obesity levels** in individuals from Mexico, Peru, and Colombia using machine learning classification models. By analyzing dietary habits and physical conditions, the study aims to identify key patterns and improve prediction accuracy in obesity assessment.

**Objectives:**
- Predict obesity levels based on lifestyle and health indicators.
- Compare the performance of different classification models.
- Enhance prediction accuracy using optimized machine learning techniques.

**Methodology & Tools Used:**
- **Data Preprocessing & EDA:** Standardization, **PCA** for dimensionality reduction, and **SMOTE** for class balancing.
- **Classification Models:**
  - **Decision Tree:** Simple interpretable model.
  - **Random Forest:** Ensemble learning for improved accuracy.
  - **AdaBoost:** Boosting technique for model optimization.
  - **SVM:** Support Vector Machine for effective classification.
  - **Logistic Regression:** Probabilistic approach to classification.
- **Optimization & Validation:**
  - **Hyperparameter Tuning:** **GridSearchCV** for optimal parameter selection.
  - **Cross-Validation:** **5-Fold CV** to ensure robustness.
  - **Evaluation Metrics:** Accuracy, **F1 Score**, Confusion Matrix, Precision, Recall.

**Technologies Used:** Python libraries including **Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn** for data analysis, modeling, and visualization.

**Link to Project on GitHub:** [Link to the project](https://github.com/arashabe/ML_Obesity_Estimation)

---

