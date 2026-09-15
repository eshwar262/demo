class Product:
    def __init__(self, product_id: int, name: str, price: float):
        self.id = product_id
        self.name = name
        self.price = price

    def __repr__(self):
        return f"Product(ID: {self.id}, Name: '{self.name}', Price: ${self.price})"
