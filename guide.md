# Start virtual environment
#python3 -m venv crawl
#source ./crawl/bin/activate

# Install dependencies
pip install flask crawl4ai openai
playwright install

# Set your OpenAI API key
export OPENAI_API_KEY='your-key-here'

# Run the app
python app.py

