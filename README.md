# Data Analytics Basics Foundation

A beginner-friendly foundation for learning the concepts, tools, and habits used in data analytics.

This repository is designed to take you from the fundamentals of working with data to completing small, explainable analysis projects. It is intentionally tool-agnostic at the start: the focus is on asking good questions, understanding data, and communicating evidence clearly.

## Learning goals

By working through this repository, you should be able to:

- Understand the data analytics lifecycle from problem definition to recommendation.
- Describe common data types, structures, and sources.
- Clean, validate, and document a dataset.
- Use descriptive statistics to summarize data.
- Write foundational SQL queries.
- Analyze data with Python or spreadsheets.
- Build clear charts and dashboards.
- Explain findings without overstating what the data supports.
- Present a reproducible analysis that another person can review.

## Suggested learning path

### 1. Analytics fundamentals

- What data analytics is and how it differs from data science and business intelligence
- Asking measurable questions
- Population, sample, observation, feature, and metric
- Qualitative versus quantitative data
- Structured versus unstructured data
- The analytics lifecycle: define, collect, prepare, analyze, communicate, act

### 2. Spreadsheets

- Formulas and relative versus absolute references
- Sorting, filtering, and conditional formatting
- Lookup functions and logical functions
- Pivot tables
- Basic charts
- Data validation and documenting assumptions

### 3. SQL

- `SELECT`, `FROM`, and `WHERE`
- Sorting and limiting results
- Aggregations with `GROUP BY`
- Filtering groups with `HAVING`
- Joins and relationships between tables
- Common table expressions and subqueries
- Handling missing values and duplicate records

### 4. Data cleaning

- Inspecting a new dataset
- Standardizing formats and categories
- Handling missing and invalid values
- Identifying duplicates and outliers
- Checking keys and relationships
- Keeping a record of transformations

### 5. Statistics for analysis

- Mean, median, mode, range, variance, and standard deviation
- Percentages, rates, ratios, and weighted averages
- Distributions and skew
- Correlation versus causation
- Sampling and uncertainty
- Interpreting results in context

### 6. Visualization and communication

- Choosing a chart for the question
- Designing readable axes, labels, and legends
- Avoiding misleading visual encodings
- Writing an insight-oriented chart title
- Separating observations from recommendations
- Presenting limitations and next steps

### 7. Practice projects

Use small projects to combine the skills above. A good project should include:

1. A clearly stated question.
2. A short description of the data and its limitations.
3. Reproducible preparation steps.
4. Analysis and supporting visualizations.
5. Findings written in plain language.
6. Recommendations that are connected to the evidence.

## Repository structure

The repository is intentionally lightweight while the curriculum is being built. A suggested structure is:

```text
.
├── README.md
├── data/
│   ├── raw/             # Original data; do not edit in place
│   └── processed/       # Cleaned data used for analysis
├── notebooks/           # Exploratory analysis notebooks
├── sql/                 # SQL exercises and solutions
├── spreadsheets/        # Spreadsheet exercises and templates
├── src/                 # Reusable Python analysis code
├── reports/             # Project write-ups and exported visuals
└── tests/               # Data-quality or transformation checks
```

Only add directories when they contain useful learning material. Small, focused examples are preferable to a large collection of unexplained files.

## Getting started

### Option 1: Start with the concepts

Read the learning path above and choose one topic. Write down a question you would like to answer with data before choosing a tool or dataset.

### Option 2: Work locally

Clone the repository:

```bash
git clone https://github.com/AGfinx/Data-Analytics-Basics-Foundation.git
cd Data-Analytics-Basics-Foundation
```

If Python exercises are added, create an isolated environment before installing project dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies only when a lesson or project provides a dependency file such as `requirements.txt` or `pyproject.toml`.

## Recommended analysis checklist

Before sharing an analysis, check that:

- [ ] The business or learning question is specific.
- [ ] The dataset and time period are identified.
- [ ] Important assumptions are documented.
- [ ] Missing values, duplicates, and unusual records were investigated.
- [ ] Calculations use the correct denominator and grain.
- [ ] Charts have clear titles, labels, and units.
- [ ] Findings distinguish facts from interpretations.
- [ ] Limitations are stated.
- [ ] Another person can reproduce the main result.

## Working principles

- **Start with the question.** Tools and charts should support the question, not replace it.
- **Understand the grain.** Know what one row represents before aggregating data.
- **Prefer simple explanations.** A clear answer is more valuable than unnecessary complexity.
- **Make transformations visible.** Keep raw data unchanged and document cleaning steps.
- **Validate before interpreting.** A polished chart cannot fix incorrect data.
- **Communicate uncertainty.** Avoid causal claims when the analysis only shows association.
- **Respect data responsibility.** Do not commit confidential, personal, or restricted data.

## Contributing

Contributions are welcome, especially:

- Clear beginner-level explanations
- Small practice datasets with appropriate licenses
- SQL, spreadsheet, or Python exercises
- Data-quality checks
- Corrections to inaccurate terminology or calculations
- Project ideas with an answer key or discussion guide

When contributing, keep examples self-contained, explain the expected outcome, and avoid including sensitive data. For larger changes, open an issue first to discuss the proposed direction.

## License and data use

A license has not yet been selected for this repository. Until one is added, treat the contents as all rights reserved and ask before reusing them in another project.

Any external dataset, image, or reference added to the repository should include its source, access date where relevant, and license or usage conditions.

## Next steps

The next useful additions are a small set of guided exercises, a sample dataset, and one end-to-end project that demonstrates the complete analytics workflow.
