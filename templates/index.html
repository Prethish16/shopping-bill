from flask import Flask, render_template, request

app = Flask(__name__)

def calculate_total(price, quantity):
    try:
        p = float(price)
        q = int(quantity)
        if p < 0 or q < 0:
            return 0.0
        return round(p * q, 2)
    except ValueError:
        return 0.0

@app.route("/", methods=["GET", "POST"])
def index():
    total = None
    price = ""
    quantity = ""
    if request.method == "POST":
        price = request.form.get("price", "")
        quantity = request.form.get("quantity", "")
        total = calculate_total(price, quantity)
    return render_template("index.html", total=total, price=price, quantity=quantity, phase=1)

if __name__ == "__main__":
    app.run(host="0.0.0.0", port=5000)
