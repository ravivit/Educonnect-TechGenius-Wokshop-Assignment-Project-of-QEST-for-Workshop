# EduConnect-TechGenius Wokshop - Assignment Project of QEST




Welcome to the **EduConnect TechGenius Assignment Project**! This is a **Point of Sale (POS) Interface** built using **React** for managing workshops and services offered by EduConnect TechGenius. The interface allows users to select services, manage a cart, simulate payments, and generate receipts.

---

## **Features**
1. **Select Services**:  
   - Choose from a list of available workshops (e.g., Robotics, AI, Drones, Web Development).  
   - Each workshop includes details like name, price, and duration.

2. **Add to Cart**:  
   - Add selected workshops to the cart.  
   - View and edit cart details (e.g., update quantity, remove items).  

3. **Customer Management**:  
   - Optionally add customer details (name, email, phone) during checkout.  

4. **Simulated Payment**:  
   - Simulate a payment flow (no real payment integration).  
   - Display a success message upon payment completion.  

5. **Receipt Generation**:  
   - Generate and display a receipt with transaction details (e.g., customer info, workshop details, total amount).  

6. **Responsive Design**:  
   - The interface is fully responsive and works seamlessly on both desktop and mobile devices.  

---

## **Tech Stack**
- **Frontend Framework**: React  
- **Styling**: Tailwind CSS  
- **State Management**: React Context API  
- **Routing**: React Router DOM  
- **Mock Data**: JSON for workshops and transactions  

---

## **Optional Enhancements (Bonus)**
- **Search/Filter**: Add functionality to search or filter workshops by name, price, or duration.  
- **Analytics**: Display insights like total revenue or number of workshops sold.  
- **Internationalization**: Add support for multiple languages and currencies.  

---

## **Installation and Setup**
Follow these steps to set up and run the project locally:

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/EduConnect-TechGenius.git
   cd EduConnect-TechGenius
   ```

2. **Install Dependencies**:  
   ```bash
   npm install
   ```

3. **Run the Project**:  
   ```bash
   npm start
   ```

4. **Open in Browser**:  
   Visit `http://localhost:3000` to view the project.

---

## **Project Structure**
```
src/
├── components/       # Reusable components (e.g., WorkshopCard, CartItem)
├── pages/            # Main pages (e.g., Home, Cart, Checkout)
├── context/          # React Context for state management
├── data/             # Mock data for workshops
├── App.jsx           # Main app component
├── main.jsx          # Entry point
```

---

## **Key Functionality**
1. **Workshop Selection**:  
   - Users can browse and select workshops from the home page.  
   - Each workshop card displays details like name, price, and duration.  

2. **Cart Management**:  
   - Users can add/remove workshops and update quantities in the cart.  
   - The cart dynamically calculates the total price.  

3. **Checkout Process**:  
   - Users can enter customer details and simulate a payment.  
   - A receipt is generated upon successful payment.  

---

## **Screenshots**
1. **Home Page**:  
   ![Home Page](screenshots/home.png)  
   - Displays a list of available workshops.  

2. **Cart Page**:  
   ![Cart Page](screenshots/cart.png)  
   - Shows selected workshops and allows editing.  

3. **Checkout Page**:  
   ![Checkout Page](screenshots/checkout.png)  
   - Collects customer details and simulates payment.  

4. **Receipt Page**:  
   ![Receipt Page](screenshots/receipt.png)  
   - Displays transaction details after payment.  

---

## **Assumptions and Limitations**
- **Mock Data**: Workshops and transactions are stored in a JSON file.  
- **Payment Simulation**: No real payment integration is included.  
- **Responsiveness**: The interface is optimized for desktop and mobile devices.  

---

## **Contributing**
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:  
1. Fork the repository.  
2. Create a new branch (`git checkout -b feature/YourFeatureName`).  
3. Commit your changes (`git commit -m 'Add some feature'`).  
4. Push to the branch (`git push origin feature/YourFeatureName`).  
5. Open a pull request.  

---


---

## **Contact**

For any questions or feedback, feel free to reach out:  
- ** Ravi Kasaudhan
+91 9672932630 |     ravikasaudhan01@gmail.com
  
https://www.linkedin.com/in/ravikasaudhan11/ |

https://github.com/ravivit
---

T
