#### Table having list of flights. Let's suppose one wants to travel from Banglore to Ahmedabad by taking minimum direct/connecting flights. Write a query get those flight numbers in order.

flights

| flight     | source     | destination |
|:----------:|:----------:|:-----------:|
| AIR 0087   | Pune       | Rajasthan   | 
| AIR 0187   | Delhi      | Ahmedabad   | 
| AIR 0767   | Rajasthan  | Delhi       |
| AIR 1678   | Kolkata    | Ahmedabad   |
| AIR 0369   | Bangalore  | Pune        |
| AIR 0029   | Rajasthan  | Ahmedabad   |
| AIR 8878   | Delhi      | Hyderabad   |


Travel - Banglore ==> Ahmedabad

Expected Output
| flight   |
|:--------:|
| AIR 0369 |
| AIR 0087 |
| AIR 0029 |


Answer :
use 2 self joins one each on another with source and destination put filter banglore and ahmedabad