# Crime Data Analysis Website

### Necessary Packages to Install:
1. Flask 
   - Install with: `pip install Flask`
2. Google Spreadsheets
   - Install with: `pip install gspread oauth2client`

### Steps to Run Code:
1. Download the repository.
2. Open `app.py` in VS Code.
3. Use `Ctrl+Shift+P` to select the Python interpreter.
4. Run `app.py`.
5. When the server is initialized, copy the link and paste it into your web browser.

### Points to Remember for Developers:
- All `.html` files should be kept in the **templates** folder.
- All associated static files such as `.css`, `.js`, and images should be kept in the **static** folder.
- Paths should be mentioned like this:
    ```html
    <link rel="stylesheet" href="{{url_for('static', filename='index.css')}}"> 
    ```
