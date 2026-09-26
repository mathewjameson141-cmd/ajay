from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return """
    <!DOCTYPE html>
    <html>
    <head>
        <title>My PaaS Application</title>
    </head>
    <body>
        <h1>Hello! Welcome to My PaaS Application</h1>
        <p>This is a simple Python Flask web application.</p>
        <p>It is deployed using GitHub and Render.</p>
    </body>
    </html>
    """

if __name__ == "__main__":
    app.run()
