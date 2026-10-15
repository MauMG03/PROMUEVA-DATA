# PROMUEVA DATA

This repository contains a collection of pseudonymized datasets gathered from X (formerly Twitter) and YouTube as part of the [PROMUEVA Project](https://sites.google.com/view/promueva/english-version). We collected and analyzed more than 620,000 social media posts (270,000 in X and 350,000 in YouTube) covering topics in Colombia between June 2024 and June 2026. The distribution of posts is (approximately):

- For X

| Topic                                      | Volume  | Date Range (dd/mm/yyyy) |
|--------------------------------------------|---------|-------------------------|
| Pension Reform                             | 10,000  | 22/06/2024 - 19/07/2024 |
| COP16 Biodiversity Conference              | 10,000  | 17/10/2024 - 10/11/2024 |
| Pegasus (surveillance software)            | 5,000   | 08/11/2024 - 15/11/2024 |
| Deportados (deportations to Colombia)      | 15,000  | 28/01/2025 - 08/02/2025 |
| Gender Violence     (Univalle case)        | 1,000   | 18/05/2025 - 24/05/2025 |
| Gender Violence     (general)              | 7,000   | 20/05/2025 - 03/06/2025 |
| Gustavo Petro visit to Cali                | 4,500   | 06/06/2025 - 11/06/2025 |
| Labor Referendum (labor reform)            | 5,000   | 06/06/2025 - 18/06/2025 |
| Miguel Uribe Attempt                       | 7,500   | 07/06/2025 - 18/06/2025 |
| Colombia Presidential Elections 2026       | 205,000 | 21/11/2025 - 18/06/2026 |

- For YouTube

| Topic                                      | Volume  | Date Range (dd/mm/yyyy) |
|--------------------------------------------|---------|-------------------------|
| Pension Reform                             |  20,700 | 11/06/2024 - 28/07/2024 |
| Álvaro Uribe Trial                         | 185,900 | 15/04/2025 - 14/09/2025 |
| Colombia Presidential Elections 2026       | 143,000 | 21/04/2026 - 25/06/2026 |

For each case, we combined qualitative contextualization with quantitative measures of audience stance and polarization using the [MEC (Mass Event Consensus)](https://arxiv.org/abs/2606.13997) index.

This datasets illustrates how different issues mobilize publics in distinct ways, providing empirical grounding for models of opinion dynamics and polarization. It is directly relevant to interdisciplinary research in computer science, political science, and social sciences, offering a testbed for validating theoretical models of bias, consensus, and polarization against real-world data.

## Privacy and Data Protection

The datasets have been processed to reduce the disclosure of personal and platform-identifying information. Original post and comment text has been removed, and the original identifiers of users, posts, comments, and videos have been replaced with transformed identifiers. Publication timestamps have been reduced to calendar dates, removing the exact time of publication.

These measures are intended to reduce direct identifiability while preserving information relevant to the temporal and quantitative analysis of social media activity. They do not, by themselves, guarantee that individual records cannot be re-identified through linkage with publicly available information.

A future release may include lemmatized text or other derived linguistic features. Such data will require additional assessment to mitigate the risk of matching records to their original public posts.

Users of the datasets should consider these limitations when processing, sharing, or interpreting the data.

-----------------

If you need more details about the datasets or the PROMUEVA project, please contact the PROMUEVA Team at: mauricio.munoz-gutierrez@lix.polytechnique.fr
