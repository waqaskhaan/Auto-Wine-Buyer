Wine Shop Auto Buyer

Overview

ineShopAutoBuyer is a Python-based bot designed to automate the purchasing process on the "Fine Wine and Good Spirits" website. By simply providing the product link, this bot efficiently handles the entire purchase process, ensuring you can secure limited-stock or high-demand products quickly and easily.

Features
Automated Product Purchase: Provide the product link, and the bot will handle the rest—navigating the site, adding the item to the cart, and completing the purchase.
Speed and Precision: Optimized to execute the purchase process swiftly, helping you secure items before they go out of stock.
Ease of Use: User-friendly design with minimal input required—just the product link.
Customizable Settings: Adjust bot parameters to fit your specific purchasing needs.
Installation
1-Clone the Repository:
git clone https://github.com/yourusername/WineShopAutoBuyer.git
cd WineShopAutoBuyer

2-Install Required Dependencies:
pip install -r requirements.txt

3-Set Up Environment Variables: Create a .env file in the project directory and add the following variables:
USER_EMAIL=your_email@example.com
USER_PASSWORD=your_password
PAYMENT_METHOD=your_payment_method
DELIVERY_ADDRESS=your_delivery_address

4- run the bot
python auto_wine_buyer.py --product_link "https://finewineandgoodspirits.com/product-link"

5-Arguments:
--product_link: The URL of the product you wish to purchase.
Customization
Timeout Settings: Modify the timeout settings in config.py if you need to adjust the bot’s speed to match the website's response time.
Retry Logic: Customize the retry logic to handle cases where the site might be slow or the product goes out of stock temporarily.

Contributing
Contributions are welcome! Please submit a pull request or open an issue for any bugs or feature requests.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Disclaimer
This bot is provided for educational purposes only. Use it responsibly and in accordance with the terms of service of the "Fine Wine and Good Spirits" website.
