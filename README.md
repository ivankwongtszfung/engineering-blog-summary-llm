# Engineering Blog Summary and Visualization Project Using LLM
[![Python](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/)
[![PyPI](https://img.shields.io/pypi/v/danger-python)](https://pypi.org/project/danger-python/)
[![Build Status](https://travis-ci.org/danger/python.svg?branch=master)](https://travis-ci.org/danger/python)
[![Status](https://img.shields.io/badge/status-development-red.svg)](https://github.com/ivankwongtszfung/engineering-blog-summary-llm)
## Description
This project is a Python-based web application that utilizes Language Learning Models (LLMs) to summarize multiple engineering blog articles from a tech company. Additionally, it analyzes and visualizes the company's architecture over a specified period, providing insights into architectural changes and trends.

## Features
- Input multiple blog URLs or upload articles in bulk.
- Generate concise summaries for each article using LLM.
- Analyze and visualize architectural changes over time.
- User-friendly interface for article submission, summary retrieval, and visualization display.

## Technology Stack
- **Backend:** Python, Flask/Django
- **Frontend:** HTML, CSS, JavaScript (React optional)
- **Libraries:** Hugging Face Transformers, Beautiful Soup, Matplotlib/Plotly
- **Database:** SQLite/PostgreSQL

## Setup and Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/engineering-blog-summary-llm.git
    cd engineering-blog-summary-llm
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up the database:
    ```bash
    flask db init
    flask db migrate -m "Initial migration."
    flask db upgrade
    ```

5. Run the application:
    ```bash
    flask run
    ```

## Usage
1. Navigate to the web interface at `http://127.0.0.1:5000`.
2. Submit blog URLs or upload articles in bulk.
3. Retrieve summaries and visualize the architectural changes over time.

## Project Structure
- `app/` - Contains the Flask/Django application.
- `static/` - Contains static files (CSS, JavaScript, images).
- `templates/` - Contains HTML templates for the web interface.
- `models.py` - Database models.
- `routes.py` - API endpoints and routes.
- `summarizer.py` - LLM integration for summarization.
- `visualizer.py` - Analysis and visualization of architectural changes.

## Contribution
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or inquiries, please contact [Ivan Kwong](mailto:ivankwong22@gmail.com).

---

### Roadmap

- [ ] Phase 1: Project Planning and Requirements Gathering
- [ ] Phase 2: Design and Architecture
- [ ] Phase 3: Development
  - [ ] Setup Development Environment
  - [ ] Backend Development
  - [ ] Database Integration
  - [ ] Frontend Development
  - [ ] Visualization Engine Development
- [ ] Phase 4: Testing
- [ ] Phase 5: Deployment
- [ ] Phase 6: Documentation and Maintenance

Feel free to contribute to the project and help improve it!

