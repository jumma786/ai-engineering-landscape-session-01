# AI Engineering Landscape – Session 01

## Project Overview

This project explores the AI Engineering Landscape by mapping real business processes to possible AI solutions. The focus is on understanding when to use Predictive Machine Learning, Generative AI, both approaches, or no AI at all.

The project demonstrates how AI engineering is not only about building models. It also includes problem framing, data understanding, interface design, evaluation, deployment planning, and responsible AI governance.

## Key Learning Objectives

- Understand the difference between AI, Machine Learning, Deep Learning, and Generative AI
- Compare Predictive ML and Generative AI use cases
- Map business processes to suitable AI approaches
- Identify data inputs, model choices, user interfaces, evaluation metrics, and deployment routes
- Recognise governance risks such as privacy, bias, hallucination, and human oversight

## Project Files

| File | Description |
|---|---|
| `Session_01_AI_Engineering_Landscape.ipynb` | Jupyter Notebook used for practical AI use-case mapping |
| `Session_01_AI_Engineering_Landscape.pdf` | Main session learning material |
| `data/business_process_ai_mapping_examples.csv` | Dataset containing workplace AI mapping examples |
| `data/blank_ai_use_case_canvas.csv` | Blank template for creating an AI use-case canvas |
| `outputs/ai_use_case_canvas.md` | Completed AI use-case canvas output |

## Dataset Description

The dataset contains workplace examples from areas such as healthcare, retail, housing, finance, HR, legal operations, manufacturing, and sales.

Each example includes:

- Business process
- Data inputs
- Predictive ML opportunity
- Generative AI opportunity
- User interface
- Evaluation metric
- Deployment route
- Governance risks

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- CSV files
- Markdown
- AI Engineering workflow

## AI Engineering Workflow

The project follows this structure:

```text
Business Problem
      ↓
Data Inputs
      ↓
Model Approach
      ↓
User Interface
      ↓
Evaluation
      ↓
Deployment
      ↓
Governance

AI Concepts Covered
Artificial Intelligence
AI is the broad field of creating systems that can perform tasks normally requiring human intelligence.
Machine Learning
Machine Learning allows systems to learn patterns from historical data and make predictions or classifications.
Deep Learning
Deep Learning is a type of Machine Learning that uses neural networks, often for complex tasks such as image recognition, speech processing, and natural language processing.
Generative AI
Generative AI creates new content such as text, summaries, answers, images, code, or reports.
Predictive ML vs Generative AI
ApproachBest Used ForExamplePredictive MLForecasting, classification, ranking, risk scoringPredicting customer churn or product defectsGenerative AISummarising, drafting, extracting, answering questionsSummarising complaints or reviewing documentsBothWhen prediction and explanation are both neededPrioritising customer cases and generating response draftsNo AIWhen simple rules or automation are enoughSending a fixed reminder email
Example Business Use Case: Aluminium Ingot Quality Control
As an example, this AI engineering approach can be applied to an aluminium recycling and ingot manufacturing business.
Business Process
Checking aluminium scrap quality before melting and ingot production.
Data Inputs


Supplier records


Scrap type


Batch weight


Impurity test results


Furnace temperature


Rejection history


Previous batch quality results


Model Approach
Predictive Machine Learning can be used to predict the risk of low-purity output before production starts.
Generative AI can be used to summarise quality issues and produce inspection notes for managers.
User Interface
A Power BI dashboard or web application showing:


Batch risk level


Supplier quality history


Scrap category performance


Purity trend


Recommended actions


Evaluation Metrics


Prediction accuracy


Reduction in rejected batches


Improvement in purity consistency


Time saved in inspection reporting


Reduction in manual quality-checking effort


Governance Risks


Wrong predictions could affect product quality


Human quality checks are still required


Supplier data should be handled fairly


Model performance should be monitored regularly


Sensitive business data should be protected


Example AI Use-Case Canvas
Section Details Business Process Aluminium scrap quality checking before melting Data Inputs Supplier data, scrap type, impurity tests, furnace readings, rejection historyModel ApproachPredictive ML for quality risk prediction and GenAI for inspection summaries Interface Power BI dashboard or web-based quality monitoring tool Evaluation Accuracy, rejected batch reduction, purity improvement, time savedDeploymentNotebook prototype → dashboard → production quality workflowGovernanceHuman review, supplier fairness, data protection, model monitoring
How to Run This Project


Clone this repository:


git clone https://github.com/jumma786/ai-engineering-landscape-session-01.git


Open the project folder:


cd ai-engineering-landscape-session-01


Install the required Python libraries:


pip install pandas matplotlib notebook


Open Jupyter Notebook:


jupyter notebook


Run the notebook:


Session_01_AI_Engineering_Landscape.ipynb
Suggested Repository Structure
ai-engineering-landscape-session-01/│├── README.md├── Session_01_AI_Engineering_Landscape.pdf├── Session_01_AI_Engineering_Landscape.ipynb│├── data/│   ├── business_process_ai_mapping_examples.csv│   └── blank_ai_use_case_canvas.csv│└── outputs/    └── ai_use_case_canvas.md
Key Insights


AI projects should start with a clear business problem, not only a model.


Predictive ML is useful when the goal is to predict, classify, forecast, rank, or score risk.


Generative AI is useful when the goal is to summarise, draft, extract, explain, or answer questions.


Some workflows need both Predictive ML and Generative AI.


Responsible AI governance is important before deployment.


Human review is still necessary for high-impact business decisions.


Portfolio Value
This project demonstrates practical AI engineering thinking, including:


Business problem framing


Data-to-solution mapping


Predictive ML vs GenAI decision-making


AI product thinking


Evaluation planning


Responsible AI governance


This project is useful for roles such as:


Data Analyst


Business Intelligence Analyst


AI Business Analyst


Junior AI Engineer


Data Science Trainee


Analytics Consultant


Future Improvements
Possible future improvements include:


Building a simple predictive ML model using the example dataset


Creating a Power BI dashboard for AI use-case mapping


Adding a completed AI use-case canvas for a real business scenario


Creating a Streamlit app to explore AI use cases interactively


Adding more industry examples from recycling, manufacturing, finance, and customer service


Author
Jumma Mohammad
Data Analyst | AI & Business Intelligence Enthusiast
GitHub: jumma786
LinkedIn: [Jumma Mohammad](https://www.linkedin.com/in/jumma-mohammad/)
