# Stock Market Training Platform
A beginner’s platform where one can learn and understand the stock market world using virtual money with Real time stock prices

## Technologies Used
- backend:- Flask
- frontend:- HTML, CSS, JavaScript
- <a href="https://pypi.org/project/yfinance/" >Yfinance </a>:- for realtime  stock prices

## installation
For Linux:<br/>
```bash
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
export FLASK_ENV=development
export DATABASE_URL=postgresql:///stocks_dbms
flask run
```

Live Demo
<br />
https://stocks-dbms.herokuapp.com/
