# Capstone Project Description

Congratulations on making it to the Capstone project! It's time to show off and flex your data analytics muscles with your own **_Capstone Project_**! This project will allow you to showcase everything you've learned as a data analyst by completing a professional-level regression project. This project will be the crown jewel of your portfolio.

## Project Overview

Your Capstone project should develop a **regression analysis** related to a single topic of your choice.

### Business Problem and Data

It is up to you to define a stakeholder and a business problem. You have the option to use the provided home sale data or to choose your own dataset.

If you choose to use the provided dataset, submit your project proposal then you can jump right into the project. If you would like to propose your own dataset, make sure you have your instructor's approval before starting your project.

### Choosing a Topic/Data

When choosing a topic/data, think through these questions:  

* What would I be motivated to work on?
* What data could I use?
* How could an individual or organization use my product or findings?
* What will I be able to accomplish in the time I have available?
* What challenges do I foresee with this project?

#### Your Get Hired 'Game Plan'

Help set yourself up for success by being strategic about your project/dataset choices.

**Already know what your job search focus will be?** Consider choosing a dataset that relates to the companies/industries you are interested in and the types of business problems/data they navigate day to day. Doing so demonstrates your subject matter knowledge in their area, significantly elevating your relevant and value as a candidate -- we've seen this strategy WOW companies time and time again!

**Still exploring what type of role you would like to get once you graduate?** That's okay! Try to focus on a topic or problem that you are interested in and passionate about. Doing so will help you produce a better project overall that you enjoy creating and that you can speak about confidently and naturally.

Your projects will be listed on your resume and will showcase your specific subject matter knowledge and interest/passions once you're job seeking. Help yourself put your best foot forward and make the strongest first impression possible.

Here are two grads who successfully did just this...

> This student was interested in working with government and public sector data, and focused specifically on traffic data and safety. They utilized the Chicago Car Crashes dataset in [one project](https://github.com/jmarkowi/Chicago-Crashes)&#42; then later created a bike lane image dataset from multiple sources for their [capstone project](https://github.com/jmarkowi/NYC_bike_lanes)&#42;. Based on their combination of technical skills and subject-matter expertise, this student landed a government consulting role at ***ASR Analytics*** where they work to prevent identity theft in tax fraud.

> This student ([GitHub link here](https://github.com/kbaranko/NYC-Building-Energy-Intensity/blob/master/README.md)&#42;) focused on working in the clean energy sector, and created their project *NYC Building Energy Density* using data from the 2016 Energy and Water Data Disclosure for New York City Local Law 84. The student landed a role at ***Kevala***, a clean energy software company, in under two months of job seeking.

&#42;*Keep in mind that the program has changed over time, so these projects do not reflect the current project requirements. They are intended as inspiration for your dataset/project choice.*

#### Provided Dataset: King County Home Sales

Under the `/data` folder you can find a file `kc_house_data.csv` which contains data for 2021-2022 home sales in King County, Washington. The description of the column names can be found in `column_names.md` under that same folder. As with most real world datasets, the column names are not perfectly described, so you'll have to do some research or use your best judgment if you have questions about what the data means.

#### Sourcing Your Own Data

Sourcing new data is a valuable skill for data professionals, but it requires a great deal of care. An inappropriate dataset or an unclear business problem can lead you spend a lot of time on a project that delivers underwhelming results. The guidelines below will help you complete a project that demonstrates your ability to engage in the full data analysis process.

Your data must be...

1. **Appropriate for a linear regression analysis.** Please use the data from previous projects as a guide here in terms of what your data should look like.

2. **Usable to solve a specific business problem.** This solution must rely on your model(s).

3. **Somewhat complex.** It should contain a minimum of 1000 rows and 10 features, though ideally it would have thousands of rows and features that require creativity to use. You _can_ use a pre-existing clean dataset, but you should consider combining it with other datasets and/or engineering your own features/columns whenever possible.

4. **Unfamiliar.** It can't be one we've already worked with during the course or that is commonly used for demonstration purposes. (Check with your instructor here if needed.)

5. **Manageable.** Stick to data that you can model with the knowledge and computational resources you have.

Once you've sourced your own data and identified the business problem you want to solve with it, you must **run them by your instructor for approval**.

#### Problem First, or Data First?

There are two ways that you can source your own dataset: **_Problem First_** or **_Data First_**. The less time you have to complete the project, the more strongly we recommend a Data First approach to this project.

**_Problem First_**: Start with a problem that you are interested in that you could potentially solve using one of the four project models. Then look for data that you could use to solve that problem. This approach is high-risk, high-reward: very rewarding if you are able to solve a problem you are invested in, but frustrating if you end up sinking lots of time in without finding appropriate data. To mitigate the risk, set a firm limit for the amount of time you will allow yourself to look for data before moving on to the Data First approach.

**_Data First_**: Start with the King County dataset, and take a look at some of the most popular internet repositories of cool datasets we've listed below. If you find a dataset that's particularly interesting for you, then it's totally okay to build your problem around that dataset.

There are plenty of amazing places that you can get your data from. We recommend you start looking at datasets in some of these resources first:

* [UCI Machine Learning Datasets Repository](https://archive.ics.uci.edu/ml/datasets.php)
* [Kaggle Datasets](https://www.kaggle.com/datasets)
* [Awesome Datasets Repo on Github](https://github.com/awesomedata/awesome-public-datasets)

### Key Points

* **Your goal in regression modeling is to yield findings to support relevant recommendations. Those findings should include a metric describing overall model performance as well as at least two regression model coefficients.** As you explore the data and refine your stakeholder and business problem definitions, make sure you are also thinking about how a linear regression model adds value to your analysis. "The assignment was to use linear regression" is not an acceptable answer! You can also use additional statistical techniques other than linear regression, so long as you clearly explain why you are using each technique.

* **You should demonstrate an iterative approach to modeling.** This means that you must build multiple models. Begin with a basic model, evaluate it, and then provide justification for and proceed to a new model. After you finish refining your models, you should provide 1-3 paragraphs in the notebook discussing your final model.

* **Project management is key.**  You have a lot of freedom in this project - this can feel liberating, but also means that you can accidentally lose a lot of time if you're not careful. Map out a rough daily project plan with key milestones and due dates for deliverables - you can adjust this as needed as you progress. Use this to make sure you're making timely progress towards successful completion. Ask for help if you find yourself struggling to keep up with your plan.

* **Create an MVP, then refine it.** Once you've chosen a project, define a Minimum Viable Product (MVP) that you feel confident you can deliver, and set daily and/or weekly goals to get that done as soon as you can. This will reduce your anxiety about whether or when you can finish the project, and will give you the time you need to polish all of your deliverables so that they are super shiny for sharing with employers.

## The Deliverables

There are two deliverables for this project:

* A **non-technical presentation**
* A **Jupyter Notebook**

### Non-Technical Presentation

Recall that the non-technical presentation is a slide deck presenting your analysis to ***business stakeholders***.

We recommend that you follow this structure, although the slide titles should be specific to your project. New elements (since the Phase 2 project) are listed in **bold**.

1. Beginning
   * Overview
   * Business and Data Understanding
2. Middle
   * **Modeling**
   * **Regression Results**
3. End
   * Recommendations
   * Next Steps
   * Thank you

Make sure that your discussion of modeling and regression results is geared towards a non-technical audience! Assume that their prior knowledge of regression modeling is minimal. You don't need to explain how linear regression works, but you should explain why linear regression is useful for the problem context. Make sure you translate any metrics or coefficients into their plain language implications.

Feel free to review the [Phase 2 Project Description](https://github.com/learn-co-curriculum/da-phase2-project-enterprise) for a reminder or some hints about presentation best practices and techniques for creating presentations.

### Jupyter Notebook

Recall that the Jupyter Notebook is a notebook that uses Python and Markdown to present your analysis to a ***data analyst audience***. You will submit the notebook in `.ipynb` format on Canvas.

We recommend that you follow this structure:

* Business Understanding
* Data Understanding
* Data Preparation
* Modeling
* Regression Results
* Conclusion

## Grading

This project has a combination of Complete/Incomplete rubric items and rubric items graded on a scale from "Exceeds Objective" down to "Does Not Meet Objective".

### Complete/Incomplete Rubric Items

These items will be graded as Complete/Incomplete:

1. Presentation
2. Business Understanding
3. Data Understanding

#### 1. Presentation

This element assesses the content, style, and delivery of the presentation.

The presentation must contain a beginning, middle, and end. The style must be reasonably professional. The delivery must clearly state the value of the project to stakeholders.

#### 2. Business Understanding

This element assesses the business understanding as conveyed in the notebook.

The notebook must identify a ***real-world problem*** for a specific ***stakeholder***.

#### 3. Data Understanding

This element assesses the data understanding as conveyed in the notebook.

The notebook must describe the ***source(s)*** of the dataset, what a ***record*** represents, which column is being used as the regression ***target***, and any relevant summary data about the features or other attributes of the dataset.

### 3-Point Graded Rubric Items

These items will be graded on a scale from "Exceeds Objective" to "Does Not Meet Objective". They are:

1. Statistical Communication
2. Data Preparation for Modeling
3. Linear Regression Modeling

#### 1. Statistical Communication

We define Statistical Communication as:

> Communicating **results of statistical analyses** to diverse audiences via writing and live presentation

Note that this is the same as the Phase 2 project, except that we are replacing "basic data analysis" with "statistical analyses".

High-quality Statistical Communication includes rationale, results, limitations, and recommendations:

* **Rationale:** Explaining why you are using statistical analyses rather than basic data analysis
  * For example, why are you using regression coefficients rather than just a graph?
  * What about the problem or data is suitable for this form of analysis?
  * For a data analyst audience, this includes your reasoning for the changes you applied while iterating between models.
* **Results:** Describing the overall model metrics and feature coefficients
  * You need at least one overall model metric (e.g. r-squared or RMSE) and at least two feature coefficients.
  * For a business audience, make sure you connect any metrics to real-world implications. You do not need to get into the details of how linear regression works.
  * For a data analyst audience, you don't need to explain what a metric is, but make sure you explain why you chose that particular one.
* **Limitations:** Identifying the limitations and/or uncertainty present in your analysis
  * This could include p-values/alpha values, confidence intervals, assumptions of linear regression, missing data, etc.
  * In general, this should be more in-depth for a data analyst audience and more surface-level for a business audience.
* **Recommendations:** Interpreting the model results and limitations in the context of the business problem
  * What should stakeholders *do* with this information?

##### Exceeds Objective

Communicates the rationale, results, limitations, and specific recommendations of statistical analyses

> See above for extended explanations of these terms.

#### Meets Objective

Successfully communicates the results of statistical analyses without any major errors

> The minimum requirement is to communicate the results, meaning at least one overall model metric (e.g. r-squared or RMSE) as well as at least two feature coefficients. See the Approaching Objective section for an explanation of what a "major error" means.

#### Approaching Objective

Communicates the results of statistical analyses with at least one major error

> A major error means that some aspect of your explanation is fundamentally incorrect. For example, if a feature coefficient is negative and you say that an increase in that feature results in an increase of the target, that would be a major error. Another example would be if you say that the feature with the highest coefficient is the "most statistically significant" while ignoring the p-value. One more example would be reporting a coefficient that is not statistically significant, rather than saying "no statistically significant linear relationship was found"

> **"If a coefficient's t-statistic is not significant, don't interpret it at all.** You can't be sure that the value of the corresponding parameter in the underlying regression model isn't really zero." *DeVeaux, Velleman, and Bock (2012), Stats: Data and Models, 3rd edition, pg. 801.* Check out [this website](https://web.ma.utexas.edu/users/mks/statmistakes/TOC.html) for extensive additional examples of mistakes using statistics.

> The easiest way to avoid making a major error is to have someone double-check your work. Reach out to peers on Slack and ask them to confirm whether your interpretation makes sense!

##### Does Not Meet Objective

Does not communicate the results of statistical analyses

> It is not sufficient to just display the entire results summary. You need to pull out at least one overall model metric (e.g. r-squared, RMSE) and at least two feature coefficients, and explain what those numbers mean.

#### 2. Data Preparation for Modeling

We define this objective as:

> Applying appropriate preprocessing and feature engineering steps to tabular data in preparation for statistical modeling

The two most important components of preprocessing for the Capstone project are:

* **Handling Missing Values:** Missing values may be present in the features you want to use, either encoded as `NaN` or as some other value such as `"?"`. Before you can build a linear regression model, make sure you identify and address any missing values using techniques such as dropping or replacing data.
* **Handling Non-Numeric Data:** A linear regression model needs all of the features to be numeric, not categorical. For this project, **(be sure to pick at least one non-numeric feature and try including it in a model***. You can identify that a feature is currently non-numeric if the type is `object` when you run `.info()` on your dataframe. Alternatively you can make your own categorical feature by binning numeric data. Once you have identified the non-numeric features, address them using techniques such as ordinal or one-hot (dummy) encoding.

There is no single correct way to handle either of these situations! Use your best judgement to decide what to do, and be sure to explain your rationale in the Markdown of your notebook.

Feature engineering is encouraged but not required for this project.

##### Exceeds Objective

Goes above and beyond with data preparation, such as feature engineering or merging in outside datasets

> One example of feature engineering could be using the `date` feature of the King County dataset to create a new feature called `season`, which represents whether the home was sold in Spring, Summer, Fall, or Winter.

> One example of merging in outside datasets could be finding data based on ZIP Code, such as household income or walkability, and joining that data with the provided CSV.

##### Meets Objective

Successfully prepares data for modeling, including converting at least one non-numeric feature into ordinal or binary data and handling missing data as needed

> As a reminder, you can identify the non-numeric features by calling `.info()` on the dataframe and looking for type `object`.

> Your final model does not necessarily need to include any features that were originally non-numeric, but you need to demonstrate your ability to handle this type of data.

##### Approaching Objective

Prepares some data successfully, but is unable to utilize non-numeric data

> If you simply subset the dataframe to only columns with type `int64` or `float64`, your model will run, but you will not pass this objective.

##### Does Not Meet Objective

Does not prepare data for modeling

#### 3. Linear Regression Modeling

In this project you are required to use linear regression as the primary statistical analysis, although you are free to use additional statistical techniques as appropriate.

##### Exceeds Objective

Goes above and beyond in the modeling process, such as recursive feature selection

##### Meets Objective

Successfully builds a baseline model as well as at least one iterated model, and correctly extracts insights from a final model without any major errors

> We are looking for you to (1) create a baseline model, (2) iterate on that model, making adjustments that are supported by regression theory or by descriptive analysis of the data, and (3) select a final model and report on its metrics and coefficients

> Ideally you would include written justifications for each model iteration, but at minimum the iterations must be *justifiable*

> For an explanation of "major errors", see the description below

##### Approaching Objective

Builds multiple models with at least one major error

> The number one major error to avoid is including the target as one of your features. For example, if the target is `price` you should NOT make a "price per square foot" feature, because that feature would not be available if you didn't already know the price.

> Other examples of major errors include: using a target other than `price` with the King County dataset, attempting only simple linear regression (not multiple linear regression), dropping multiple one-hot encoded columns without explaining the resulting baseline, or using a unique identifier (`id` in this dataset) as a feature.

##### Does Not Meet Objective

Does not build multiple linear regression models

## Summary

The Capstone Project is the most critical part of the program. It gives you a chance to bring together all the skills you've learned into a realistic project, including the project management, business analysis, and communication.  Most importantly, it provides a strong signal about your technical abilities and allows you to show the world what an amazing data professional you've become!
