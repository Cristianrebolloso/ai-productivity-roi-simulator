# AI Productivity ROI Simulator

This project models how generative AI shifts productivity, labor cost, and operating margin in Finance, HR, Operations, Marketing, and IT. Executives can adjust adoption levels and see risk-adjusted projections through 2030.

**Author**: Cristian Rebolloso (Baylor MBA/MSBA candidate, BBA Economics)  
**Core stack**: Python · PyMC · Pandas · Streamlit

## Why I’m building it
Boards want a concrete economic case before funding large AI programs. My aim is to convert public benchmarks and Bayesian modelling into a board-ready decision tool.

## Quick start  *(pipeline under construction)*
> The commands below will work once the first notebook, `requirements.txt`, and `app/main.py` are committed.  
> Follow the repo’s Issues tab for build progress.

```bash
git clone https://github.com/Cristianrebolloso/ai-productivity-roi-simulator
cd ai-productivity-roi-simulator
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
streamlit run app/main.py
