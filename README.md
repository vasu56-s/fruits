def fruit_prices():
    fruits = {
        "Apple": 120,
        "Banana": 40,
        "Mango": 90,
        "Orange": 60,
        "Grapes": 80
    }

    print("🍎 Welcome to the Fruit Trading System 🍌")
    print("-----------------------------------------")
    for fruit, price in fruits.items():
        print(f"{fruit}: ₹{price} per kg")

if __name__ == "__main__":
    fruit_prices()

