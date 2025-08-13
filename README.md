# Natural-language-to-SQL

This project converts **natural language queries** into **SQL queries** using the **T5 (Text-To-Text Transfer Transformer)** model. T5 is a versatile transformer-based architecture that treats every NLP problem as a text-to-text task, making it suitable for translating user-friendly queries into structured SQL statements.

---

##  Objectives
- **Natural Language → SQL Translation**: Train T5 to generate SQL queries from natural language questions.
- **Utilize Spider Dataset**: Use the [Spider dataset](https://yale-lily.github.io/spider) — a benchmark containing complex SQL queries across multiple database schemas — to ensure robustness and generalization.

---

##  Dataset
We use the **Spider dataset**, known for its complexity and cross-domain variety:

- **Natural Language Questions** – English phrases describing database queries.
- **SQL Queries** – Corresponding structured queries.
- **Database Schemas** – Tables, columns, and relationships from multiple databases.

📄 **Spider Paper**: [Read here](https://yale-lily.github.io/spider)

---

##  Model
The **T5 (Text-To-Text Transfer Transformer)** model treats every NLP task as a text-to-text problem. This allows it to be trained for various tasks, including **NL-to-SQL translation**.

📄 **T5 Paper**: [Read here](https://arxiv.org/abs/1910.10683)

---

##  Training & Evaluation
- **Training**: Fine-tune T5 on the Spider dataset to learn NL → SQL mapping.
- **Evaluation Metrics**:
  - Query Accuracy
  - Execution Accuracy
  - Generalization to complex queries

---

##  Use Cases
- **Database Query Generation** – Auto-generate SQL queries from user-friendly input.
- **Query Understanding** – Make database interaction more intuitive.

---

##  Expected Outcomes
- **Enhanced User Interaction** – Simplified database access via natural language.
- **Robust Model** – Trained on diverse schemas and queries.

---

##  Acknowledgements
- **T5 Model** – Developed by [Google Research](https://arxiv.org/abs/1910.10683)
- **Spider Dataset** – Created by [Yale University & University of Hong Kong](https://yale-lily.github.io/spider)

---

##  License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
