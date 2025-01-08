# Advice from Data Science Subreddit

* Key performance indicators and metrics in industry (if not explicitly notated) are likely to be either specifically developed for your field or you will utilize ones that are already proven indicators.

* In the event you do need to develop them on your own, that’s okay - just think it through. What data points might be useful to aggregate and represent what you want to see? What points are most relevant to the metric you are trying to measure? Think in terms of overall health and year-on-year benchmarks - the specific metric will probably be tied to a business problem like sales improvement, marketing engagement, etc.

* The summary is that metrics are about translating what success means from a business perspective into a quantity you can measure and use to select which model you deploy. This might mean accuracy of a prediction model, but often there's a lot of other, more relevant metrics. I think it mainly boils down to critical/analytic thinking skills and knowing how to communicate with and understand people from the business side.

# Business

* [How to Measure Anything by Douglus Hubbard](https://www.professionalwargaming.co.uk/HowToMeasureAnythingEd2DouglasWHubbard.pdf)

* Metrics should be measurable, meaningful, and movable.

* Good learning from [Eliahu Goldratt (Theory of Constraints)](https://brharnetc.edu.in/br/wp-content/uploads/2018/11/5.pdf): use metrics that encourage the behaviors that enable success. As an internal metric, measurements of reliability help flag the need to fix broken connections between people and processes. Goldratt invites the creation of metrics that measure 1) "the things you did not do, when you should've done them", and 2) "the things you did when you should have not ".

* When these reliability metrics complement other tried and true, standard success metrics, interdependencies come to light, allowing you to see what, when, where, how big, and how much "things" contribute to a series of symptoms and underlying problems.

* [KPI's](https://www.kpi.org/KPI-Basics/KPI-Development/)

1. Core Framework Components:
- Measure: Develop and select meaningful KPIs
- Perform: Execute and track initiatives
- Review: Analyze performance data
- Adapt: Adjust strategy based on learnings

2. Pre-Measurement Essential Steps:
- Launch program with leadership engagement
- Establish clear roles and teams
- Articulate strategic intent before creating KPIs
- Choose an appropriate framework (Balanced Scorecard, SMART, OKRs, etc.)

3. Measurement Development Process:
- Identify objectives and intended results
- Evaluate alternative measures
- Select right metrics based on relevance and data availability
- Document measure definitions thoroughly

4. Key Criteria for Selecting Metrics:
- Answers key strategic questions
- Supports better decision making
- Measures what's intended
- Encourages desired behaviors
- Avoids excessive data collection burden

5. Performance Management Cycle:
- Set clear targets and thresholds
- Implement improvement initiatives
- Collect and visualize data
- Analyze results and draw conclusions
- Adapt strategy as needed

6. Best Practices:
- Don't "set and forget" KPIs
- Use regular review cycles (typically quarterly)
- Focus on short list of high-impact initiatives
- Create meaningful visual comparisons
- Maintain continuous improvement focus
- Share learnings to improve decision-making

7. Important Principles:
- Strategy must precede metrics
- Buy-in from stakeholders is critical
- Data visualization enables better interpretation
- Regular adaptation is necessary
- Performance review meetings should focus on improvement

# Product Team
* [Amplitude Guide](https://info.amplitude.com/rs/138-CDN-550/images/The%20Amplitude%20Guide%20to%20Product%20Metrics.pdf)
  * gives you a sense of the different flavors of product metrics that product analysts measure. While some like blended metrics, preference to simple and mostly out of the box. This makes it easy to explain to stakeholders and easy to investigate why the metric has changed

* There are some instances where I will attempt to track a custom metric. If you know your product's Aha moment (eg. when users first experience the value that your product offers) or if you have a sense of what good behavior looks (eg. using the product x number of times) it might make sense to invest the time to track and socialize a metric that's specific to your company. However, the most important quality of a successful product metric is that people believe that it measures the quality they are trying to track. It doesn't matter how good the metric is if your stakeholders don't believe it's important.

# LLM Evaluations
* [FACTS Grounding: A new benchmark for evaluating the factuality of large language models](https://deepmind.google/discover/blog/facts-grounding-a-new-benchmark-for-evaluating-the-factuality-of-large-language-models/?utm_source=tldrai)

1. Purpose and Goal
- Introduces a new benchmark to evaluate how accurately LLMs ground their responses in source material
- Aims to measure and reduce hallucination in LLM outputs
- Launched with a public leaderboard on Kaggle to track industry progress

2. Dataset Structure
- 1,719 total examples split into:
  - 860 public examples (released)
  - 859 private examples (held out)
- Covers diverse domains: finance, technology, retail, medicine, law
- Documents up to 32,000 tokens (~20,000 words)
- Focus on tasks requiring factual responses, excluding creativity/complex reasoning

3. Evaluation Methodology
- Uses three frontier LLM judges:
  - Gemini 1.5 Pro
  - GPT-4
  - Claude 3.5 Sonnet
- Two-phase judging process:
  1. Eligibility check (adequately addresses request)
  2. Factual accuracy assessment (grounded in provided document)

4. Key Features
- Requires long-form responses
- Tests grounding in provided context
- Focuses on various tasks like summarization, Q&A, and rewriting
- Evaluates both comprehensiveness and factual accuracy

5. Future Plans
- Will continue to evolve as field progresses
- Open for community engagement and model submissions
- Aims to continuously raise standards for LLM factuality

This benchmark represents an important step in measuring and improving LLMs' ability to provide accurate, well-grounded responses based on source materials.  

# Search Performance Metrics
* [Google vs. ChatGPT Search](https://searchengineland.com/chatgpt-search-vs-google-analysis-449676?utm_source=tldrai)

# Review Main Concepts
* [Interactive Dashboard to Test Knowledge](http://192.168.1.250:8501/)
