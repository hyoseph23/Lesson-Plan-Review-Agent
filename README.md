# RainCheck - K-12 Lesson Plan Tool

RainCheck helps teachers create and review lesson plans using AI. RainCheck is a perfect solution for when teachers are out and substitutes are needed. 

## What It Does

**Create Plan** - Answer 8 questions about your class and get a complete, ready-to-use lesson plan for your substitute teacher. Covers schedule, step-by-step instructions, materials, classroom routines, and more.

**Review Plan** - Upload an existing lesson plan and get section-by-section feedback on formatting, content quality, and standards alignment. Accept or override each suggestion, then generate a corrected version in one click.

## Setup

```
pip install -r requirements.txt
export ANTHROPIC_API_KEY=your-key-here
python app.py
```

Open http://127.0.0.1:5001

## Files

- agent.py -- review logic and Claude integration
- app.py -- web interface and document generation
- requirements.txt -- dependencies
