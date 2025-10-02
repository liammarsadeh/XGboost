#### Hello everyone 

This Project is technically one of the most interesting projects I have ever done, and I would recommend it to any beginner.
1- I have made it within 2 days; it didn't take that long 
2- It makes you familiar with many topics, such as 
  - Data cleaning & Exploration
  - Handling NaN Values in multiple ways
  - Trying Cross Validation so it gives you the best suitable model for your Dataset
  - GridSearchCV, as we saw how XGBoost was performing poorly without the hyperparameters, but when we maximize them, it blew up
  - Finally, you will learn how to evaluate the Algorithm you have picked using (Classification_report) & (Confusion_matrix)

| Column                      | Explanation                                                               |
| --------------------------- | ------------------------------------------------------------------------- |
| `num_young_drivers`         | Number of young drivers in the household (likely under 25).               |
| `date_of_birth`             | The policyholder’s date of birth.                                         |
| `age`                       | The policyholder’s age in years.                                          |
| `num_of_children`           | Number of children living at home.                                        |
| `years_job_held_for`        | How long the policyholder has been at their current job.                  |
| `income`                    | Annual income of the policyholder.                                        |
| `single_parent`             | Whether the policyholder is a single parent (1 = yes, 0 = no).            |
| `value_of_home`             | Market value of the home.                                                 |
| `married`                   | Marital status (1 = married, 0 = not married).                            |
| `gender`                    | Gender of the policyholder.                                               |
| `highest_education`         | Highest level of education completed.                                     |
| `occupation`                | Job or occupation category.                                               |
| `commute_dist`              | Average commute distance or time.                                         |
| `type_of_use`               | How the car is primarily used (e.g., personal, business).                 |
| `vehicle_value`             | Estimated value of the vehicle.                                           |
| `policy_tenure`             | How long the insurance policy has been held.                              |
| `vehicle_type`              | Type or class of the vehicle.                                             |
| `red_vehicle`               | Whether the car is red (some studies say red cars get more claims).       |
| `5_year_total_claims_value` | Total monetary value of claims made in the past 5 years.                  |
| `5_year_num_of_claims`      | Total number of claims made in the past 5 years.                          |
| `licence_revoked`           | Whether the driver’s license has ever been revoked.                       |
| `license_points`            | Number of points on the license due to violations.                        |
| `new_claim_value`           | Value of the current or new insurance claim.                              |
| `vehicle_age`               | Age of the vehicle in years.                                              |
| `is_claim`                  | Whether a claim was filed (1 = yes, 0 = no).                              |
| `address_type`              | Type of area where the policyholder lives (e.g., urban, suburban, rural). |

- This will automatically install all the packages your project needs.  

---

### ** Optional tip**

- If you use a **virtual environment**, it’s even cleaner:  

```bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
pip install -r requirements.txt
