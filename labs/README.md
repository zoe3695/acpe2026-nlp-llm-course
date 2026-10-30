# Hands-on labs

## Part 1: NLP coding laboratory

- [Student notebook](ACPE26_NLP%20Workshop_student.ipynb) · [Open in Colab](https://colab.research.google.com/github/zoe3695/acpe2026-nlp-llm-course/blob/main/labs/ACPE26_NLP%20Workshop_student.ipynb)
- [Practice dataset](acpe26_nlp_dataset.xlsx)

Open either notebook in Colab and use **File → Save a copy in Drive** to work on your own copy. The classification notebook includes the worked evaluation results.

**Instructor:** Crystal Leung 

## Part 2: LLM prompting laboratory

[Open the student lab in Google Colab](https://colab.research.google.com/drive/1dyXt0pZRqkVmmbshcT4ECdzgV1lTdctf) · [Download the notebook](ED_Group_Challenge_Student.ipynb)

- Save a copy in Drive; choose **Runtime → Change runtime type → T4 GPU**.
- Run setup to load **Qwen3 1.7B**. No paid model API or lesson ZIP is needed.
- Explore the illustrated tips, then edit the prompts and parameters in one playground cell.
- Enter a unique team name. Each experiment saves its prompts, settings and results locally in your team’s runtime. Rerun the `team_attempts` dataframe cell to compare strategies and F1.
- Test on **20 public notes** for an immediate local F1 score, then improve your prompt.
- The final cell selects your highest-scoring saved preview prompt (earliest on a tie), keeps its 20 predictions, and runs the **50 unseen notes**. Only the complete **70-note entry** is submitted; no extra Google credential grant is needed.
- Progress bars show completed notes, elapsed time and estimated time remaining. Rerun the same batch cell to resume an interrupted run while its runtime files remain available.
- Open the live leaderboard from the notebook: it shows **20-note public F1 only** and updates in about 1–2 minutes. The instructor’s separate private ranking uses **one F1 across all 70 notes**.
- Download `team_attempts.csv` and `prompt_experiments.json` before resetting the runtime to keep your experiments.

**Instructor:** Harvey Koh. Student version; solutions and the private scorer are distributed separately.
