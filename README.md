# Little Lemon Database & Analysis

In this project, we designed and modeled a database for Little Lemon Restaurant. We also created stored procedures for the database and implemented data analysis using Tableau to gain business insights. This project is the Meta Database Engineer Capstone.

---

## Information Required to be Stored in the Database

### Database Requirements

1. **Bookings:** To store information about booked tables in the restaurant, including booking ID, date, and table number.
2. **Orders:** To store information about each order, such as order date, quantity, and total cost.
3. **Order Delivery Status:** To store information about the delivery status of each order, such as delivery date and status.
4. **Menu:** To store information about cuisines, starters, courses, drinks, and desserts. Each menu is a set of meals or a package offered by the restaurant.
5. **Customer Details:** To store information about customer names and contact details.
6. **Staff Information:** Including role and salary.

---

After we defined and examined the relationships, the database model was implemented in MySQL Workbench.

![Database Model](LittleLemonDbModel/db_model.png)

## Data Analytics with Tableau

We used Tableau to perform data analytics using relevant charts and dashboards. Here are some visualizations used.

### Fig 1.
Bar Chart that shows customer sales and filters data based on sales of at least $70. The chart is in descending order to start with the highest.

![BarChart](Tableau%20Graphs/fig1.png)

### Fig 2.
Line chart showing the sales trend from 2019 to 2022.

![LineChart](Tableau%20Graphs/fig2.jpg)

### Fig 3.
Bubble chart of sales for the top 31 Customer Sales.

![BubbleChart](Tableau%20Graphs/fig3.jpg)

### Fig 4.
Bar Chart displaying the sales of different cuisines from 2020 to 2022. It also shows the profits located at the top of the bars.

![BarChart](Tableau%20Graphs/fig4.png)

### Fig 5.
Interactive dashboard that combines the Bar Chart and the Bubble Chart.

![Dashboard](Tableau%20Graphs/fig5.png)

