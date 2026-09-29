# ComicCraft - AI Comic Story Creator

An AI-powered tool that converts simple text prompts into full comic stories with images.

### Team Members
- Vinitha
- Pavithra

### Tech Stack
- Frontend: HTML, CSS, Jinja2
- Backend: FastAPI
- AI Models: Google Gemini 1.5 Pro (Story) + Stable Diffusion (Images)
- Export: FPDF (PDF Generation)

### Features
- Scenario 1: Generate comic from prompt like "A brave fox exploring an enchanted forest"
- Scenario 2: Customize tone (funny/dramatic) and art style (anime/comic-book)
- Scenario 3: Preview and Download as PDF

### How to Run
pip install -r requirements.txt
uvicorn app.main:app --reload
