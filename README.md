# 🏋️‍♀️ Online Fitness App Database

This project is a **relational database design** for an Online Fitness App that helps users plan workouts, track their fitness journey, and manage subscriptions. The database includes:

- ✅ Complete **relational schema**
- 📊 A visual **ER diagram**
- 🔍 A collection of **sample SQL queries**
- 🧪 Ready-to-run seed data for testing

---

## 📌 Project Highlights

This database supports the following **core functionalities**:

1. **User Management**
   - Store user information (name, email, age, etc.)
   - Manage different user types (e.g., regular users, trainers, admins)

2. **Workout Planning**
   - Store pre-designed workout plans
   - Map workouts to exercises (many-to-many relationship)

3. **Exercise Library**
   - Store details about different exercises: name, targeted muscles, description

4. **Workout Tracking**
   - Users can log completed workouts with details like date, duration, calories burned

5. **Subscription System**
   - Handle user subscriptions, plans (monthly, yearly), and payment tracking

6. **Trainer Management**
   - Assign trainers to users
   - Store trainer details and their available slots

7. **Progress Monitoring**
   - Users can view history of completed workouts
   - Track improvements over time

---

## 🧱 Database Structure

### Included Files:
- `schema.sql`: SQL code to create all tables, primary keys, and foreign keys
- `data.sql`: Sample insert statements to populate the database
- `queries.sql`: Useful SQL queries to explore data (e.g. progress tracking, top workouts)
- `ER_Diagram.png`: A visual representation of the entire schema and relationships

### Tables:
- `users`
- `trainers`
- `exercises`
- `workouts`
- `workout_exercises`
- `exercise_logs`
- `subscriptions`
- `payments`
- `user_trainer_map`
- `plans`

> ✅ Relationships are built using **foreign keys** to ensure data integrity.

---

## 💡 Example Use Cases

- Get all exercises under a specific workout plan
- Show a user's workout history with progress details
- List all users under a particular trainer
- Identify top-performing workouts based on frequency
- Find users whose subscriptions are about to expire

---

## 🎯 Who Can Use This?

This project is useful for:

- 🎓 Students learning **Database Management Systems (DBMS)**
- 👨‍💻 Developers building **fitness or health tracking apps**
- 🧱 Backend developers looking for a **clean, normalized schema**
- 🔧 Engineers building APIs or admin dashboards over structured fitness data

---

## 🙋‍♀️ About the Author

Made with ❤️ by **Visha Sitapara**  
🔗 [GitHub Profile](https://github.com/VishaSitapara)

---

