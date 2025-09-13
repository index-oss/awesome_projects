### 🐛 Exbow-Offensive – XBOW-lite Autonomous Bug-Hunting Tool

**What it does:**  
An automated tool aimed at bug hunting, combining reconnaissance, AI-analysis, and exploitation, with report generation.

**Tech stack:**  
Python, Shell scripts

**Features / Workflow:**
- Recon module (`recon/scan.py`) to scan targets  
- AI analysis module (`ai/analyze.py`)  
- Exploit module (`exploit/exploit.py`)  
- Reports are generated in `reports/` folder, with report template etc.  

**Getting Started:**
```bash
git clone <repo URL>
cp .env.example .env   # fill in any API keys or env vars
sh setup.sh             # to set up environment
python recon/scan.py example.com
python ai/analyze.py
python exploit/exploit.py
