How to run technical_analysis_app on Windows using Anaconda Navigator

- Step1: Create a new environment in Anaconda Navigator and open 
terminal in that environment (so you don't fuck up other stuffs)

- Step2: Install packages you need in that environment:
pip install streamlit
pip install yfinance
pip install cufflinks

- Step3: Change directory to where directory with file technical_analysis_app.py
is located
cd (drag directory in command prompt)

- Step4: run the .py script with the command
streamlit run technical_analysis_app.py

If everything goes smoothly your web browser should open with the "deployed app"
