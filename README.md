# ML-Recruitment-Anay-
Contains the required documents for the tasks
- It has a jupyter nb which contains my journey, challenges I faced, solutions and explanantions
- It also has a pdf document which contains the same thing. Reading the jupyter nb is preffered cause it is more structured and more readable

  Task 1

  
Level 1: Variable Identification Protocol (Basically used corr heatmap and some plots)

    Approach:

      -   Read the document

      -   Hypothesized Feature 1 to be age based on distribution and correlation with other variables (failures, grades, etc.).

      -   Used correlation heatmaps and statistical plots (e.g., boxplot, scatterplot) to validate hypotheses for Features 1–3.

      -   Feature 2 inferred as academic groupings based on grades.

      -  Feature 3 inferred as behavioral categorization based on its correlation with alcohol use, gender, and grades.

Level 2: Data Integrity Audit (used corr heatmap)

    Approach:

      -   Chose not to drop NaN rows to preserve data.

      -   Used logic based on correlation and graphs to impute missing values.

      -   Imputed some features using correlated values (e.g., Fedu from Medu, traveltime from address).

      -   Used KNN imputation for variables like Feature 2, Feature 3, and G2.

Level 3: Exploratory Insight Report (used plots)

    Approach:

      -   Used correlation matrices and plots to compare schools, genders, and family situations.

      -   Identified educational and socio-economic disparities (e.g., rural MS school students more disadvantaged).

      -   Examined how health, parental status, and absences impact performance and well-being.

       -  Concluded with actionable insights like supporting students from disadvantaged backgrounds.

Level 4: Relationship Prediction Model (used random forest)

    Approach:

       -  Chose logistic regression initially due to binary nature of prediction but found poor performance (~60%).

       -  Switched to Random Forest, which improved accuracy to ~66%.

       -  Concluded that absences and low grades may be effects of relationships, not causes.

       -  Proposed a rule-based tool for teachers 

Task 2: Multi-Agent System Development
Level 1: Core Activation

    Approach:

      -   Studied Langchain and Langgraph documentation.

      -   Integrated tool APIs after understanding the interfaces.

      -   Overcame syntax and structure issues through trial and error and by referring to examples.

Level 2: Senses of the World

    Approach:

      -   Integrated Tavily and OpenWeather APIs to fetch real-world data.

      -   Used online resources (e.g., YouTube tutorial) to generate and use weather API keys.

      -   Commented code for testing the tools.

Level 3: Judgement and Memory

    Approach:

       -  Extended existing logic by adding memory-saving and update functionality.

       -  Modified and tested graph execution to ensure memory handling works.

       -  Faced and resolved execution issues (mentioned in notebook).

Level 4: Multi-Agent Evolution

    Approach:

       -  Spent considerable time understanding multi-agent coordination via Langgraph.

       -  Attempted multiple ideas and finally built a travel packing assistant using a supervisor-agent structure.

       -  Designed agents for weather, fashion, and event planning, and used structured prompting for alignment.

       -  Balanced between swarm and supervisor models for effective implementation.
