# Aaditya Upadhyay

Computer Science student at Manipal University Jaipur. I like building something all the way through: an Android app and the API behind it, a data pipeline with real failure handling, an ML experiment someone else can re-run. I write the limits of each project into its README.

## Building now: AIIMIN

[**AIIMIN**](https://github.com/Addy48/AIIMIN) is a personal Life OS for India: your day, your money and your family's papers in one app. It reads bank SMS on the phone to build a month of spending, keeps tasks and focus time, and holds documents and an emergency card offline. It only compares you with you, and there are no ads, no lending and no data sales.

- Native Android app in Kotlin, Jetpack Compose, Hilt, Room and Navigation 3. The [4.0.0-beta01](https://github.com/Addy48/AIIMIN/releases/latest) APK is public.
- React 19 web app at [aiimin.in](https://aiimin.in), and a Hono + Better Auth + Supabase API behind both.
- Two branches: `main` is the live site, `dev` is where work happens.

## Data engineering

| Project | What it does |
|---|---|
| [automated-data-pipeline](https://github.com/Addy48/automated-data-pipeline) | S&P 500 and Nifty 50 daily bars (about 550 tickers, 138k rows a year) into a bronze / silver / gold S3 lake with Pandera gates, Glue and Athena, Terraform, and a Streamlit dashboard. A failed stage or upload fails the run and the exit code says so. |
| [alphaflow-market-pipeline](https://github.com/Addy48/alphaflow-market-pipeline) | The same two exchanges as a factor mart (14 vectorised factors) plus a serverless alert sentinel on Lambda, EventBridge and DynamoDB. [Live terminal](https://alphaflow-terminal.vercel.app). |

## Machine learning and research

| Project | What it shows |
|---|---|
| [EEG-Stress-Detection-](https://github.com/Addy48/EEG-Stress-Detection-) | Seven classifiers and three ensembles on the SAM 40 EEG dataset. Subject-dependent accuracy reaches 97.4%; the file-group split tops out at 55.3%. Manuscript under submission; the repo says exactly what the numbers do and do not show, and the tables rebuild from the saved results. |
| [cps-fault-prediction](https://github.com/Addy48/cps-fault-prediction) | Distributed fault prediction on NASA C-MAPSS. Test F1 0.839 distributed vs 0.841 centralised, and with 30% of nodes dropped the distributed model holds 0.856 while the centralised one fails (0.000). |
| [llm-log-explainer](https://github.com/Addy48/llm-log-explainer) | Three Docker services: a log generator, a FastAPI explainer and a small dashboard. Co-built with Rasagya Vatsal. |
| [urban-crime-intelligence](https://github.com/Addy48/urban-crime-intelligence) | California police incidents: KMeans risk clusters, an arrest model, a FastAPI service and a Power BI view. |
| [bw-image-colorizer](https://github.com/Addy48/bw-image-colorizer) | Inference wrapper and Tkinter GUI for the Zhang et al. 2016 colourisation network. |

## Stack

Kotlin and Compose · Python (pandas, scikit-learn, FastAPI) · TypeScript and React · Node and Hono · Postgres and Supabase · AWS (S3, Glue, Athena, Lambda) · Terraform · Docker · GitHub Actions
