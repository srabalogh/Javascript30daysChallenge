# Update CSS Variables with JS


# How to set CSS vars?


In the element root use the sintax bellow:
    "--<variablename>"

#How to access data custom attributes in JS?


Select element and use the property dataset to access custom data attr.
    const suffix = this.dataset.sizing
    
# How to select and update css root variables?


document.documentElement.style.setProperty(`--${this.name}`, value);
