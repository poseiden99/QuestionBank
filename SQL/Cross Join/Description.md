### get me dishes along with the drinks available if person is Vegetarian
--dont give outputs right away let them ask questions like could you please explain this 
-- we need to understand if candidate is understanding the requirement or just saying yes to everything

| main_dish_id  | dish_name        | is_veg         |
| -------------- | --------------- | -------------- |
| 1              | Grilled Chicken | false          |
| 2              | Veggie Burger   | true           |
| 3              | Pasta Alfredo   | true           |


| drink_id  | drink_name   |
| --------- | ------------ |
| 1         | Cola         |
| 2         | Orange Juice |


Expected Output =>

| main_course   | drink        |
| ------------- | ------------ |
| Veggie Burger | Cola         |
| Veggie Burger | Orange Juice |
| Pasta Alfredo | Cola         |
| Pasta Alfredo | Orange Juice |
