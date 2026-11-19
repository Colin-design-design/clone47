# clon47 — AGI Framework Builder (Colab → VS Code)

Your Google Colab notebook, running locally in VS Code.

## Setup

- **Python environment:** `colab47` (Python 3.12, matching Colab's runtime)
  - Path: `C:\Users\ghoas\Miniconda3\envs\colab47\python.exe`
- All dependencies installed and verified (`requirements.txt`)
- NLTK `cmudict` corpus downloaded

## Gemini API key

1. Get a key: https://aistudio.google.com/apikey
2. Open the `.env` file in this folder and paste your key:
   ```
   GEMINI_API_KEY=your_actual_key
   ```
3. Run the notebook — the first cell auto-loads the key.

## Running

Open `clon47.ipynb` in VS Code → select kernel `colab47` → run cells.

## Syncing back to Colab

- Commit/push changes to this GitHub repo, then in Colab: **File → Open notebook → GitHub** tab.
- Or upload `clon47.ipynb` directly: **File → Upload notebook**.
