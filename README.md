# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

Prerequisites: Python 3.10+, Git.

```bash
git clone git@github.com:Van-Huu-Phuc/lab01-Van-Huu-Phuc.git
cd lab01-Van-Huu-Phuc
python3 -m venv .venv
source .venv/bin/activate       #Windows: .venv\Scripts\Activate.ps
pip install -r requirements.txt
pip install -e .

## Run

python3 -m assistant "where is the IT helpdesk?"
IT Helpdesk: room E.005, open Mon-Fri 08:00-17:00.

## Test

pytest -q           

## Project structure

 
