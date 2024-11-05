# This is Flask Introduction Tutorial.



> `This tutorial covers Flask Concepts and a project of To-Do-List in Flask.`

``` Python

from flask import Flask, render_template, url_for


app = Flask(__name__)

@app.route("/")
def index():
    return render_template('index.html')
    
if __name__ == "__main__":
    app.run(debug=True)

```

### Flask:
![Python logo](./download.png)


> This is Daily practise series.

