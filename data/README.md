# Honeycomb Test Data

This dataset contains a set of reviews for individuals within an organization. A person may review themselves or be reviewed by their peers, their line manager, and their direct reports.

Reviewers and reviewees are grouped into **populations**, which represent organizational subgroups or cohorts. Each review consists of scores on one or more **behaviours**, and each row in the dataset represents a score given to a specific behaviour.

---

## 📊 Variables

| Column | Description |
|--------|-------------|
| `reviewer_id` | Unique ID of the person providing the review |
| `user_id` | Unique ID of the person being reviewed |
| `review_id` | Unique ID of the review (groups all behaviours per review) |
| `relationship` | Relationship of reviewer to reviewee (`peer`, `line_manager`, `direct_report`, etc.) |
| `behaviour_id` | Unique ID for the behaviour being rated |
| `behaviour_title` | Human-readable label for the behaviour |
| `value` | Numeric score assigned for the behaviour |
| `completed_at` | Date when the review was completed |
| `self_review` | Boolean; `TRUE` if the reviewer is reviewing themselves |
| `u.population_id` | Population ID of the reviewee |
| `u.gender_identity` | Gender identity of the reviewee |
| `u.sexuality` | Sexual orientation of the reviewee |
| `u.ethnicity` | Ethnicity of the reviewee |
| `u.age` | Age of the reviewee |
| `r.population_id` | Population ID of the reviewer |
| `r.gender_identity` | Gender identity of the reviewer |
| `r.sexuality` | Sexual orientation of the reviewer |
| `r.ethnicity` | Ethnicity of the reviewer |
| `r.age` | Age of the reviewer |

---

## 🧠 Notes

- Each `review_id` may include multiple rows (one per behaviour).
- Reviewees and reviewers can belong to different populations.
- Behaviour scores can be used to analyze trends, compare self vs. peer perception, and evaluate cultural patterns across identity dimensions.

📌 **Important Notice**

This dataset contains **fabricated but realistic behavioural review data**.  
Some patterns (e.g., bias in scores, missing data, demographic imbalances) have been deliberately included to support analysis and insight generation.  

We encourage you to explore the data and highlight one interesting insight in your submission. We’re curious about what you notice, how you interpret it, and how you communicate it.

**No real individuals are represented.**

