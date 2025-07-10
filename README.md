# advanced
A version of the simulator with a separate page having input of four initial conditions for model factors: S&P 500 annual volatility, S&P 500 bubble valuation measure, Moody's BAA bond rate, long-short Treasury spread. See the blog post https://my-finance.org/2025/07/10/advanced-version/

HTML files
main_page.html for landing page with the main version of the simulator, complete_page.html for the page with the advanced complete version of the simulator, and response_page.html for the page which provides the PNG output and a link to download output PDF file

Python files
flask_app.py is the main Python/Flask file, while validation.py is the same file as in the previous repository: https://github.com/asarantsev/simplified-simulator innovations.py is the Python file which adds missing residuals data

Excel files
overall.xlsx is the main original data file, innovations.xlsx is the file where we write regression residuals with missing data, filled.xlsx is the file with filled residuals data

