https://application-zomato.herokuapp.com/

Page 1
List of city
> http://localhost:6700/location
> https://application-zomato.herokuapp.com/location

List of restaurants 
> http://localhost:6700/restaurant
> https://application-zomato.herokuapp.com/restaurant

restaurants wrt to city 
> http://localhost:6700/restaurant?state_id=4
> https://application-zomato.herokuapp.com/restaurant?state_id=4

quick search data  
> http://localhost:6700/mealType
> https://application-zomato.herokuapp.com/mealType

(http://localhost:6700/restaurant?state_id=4&meal_id=5)

Page 2
restaurants wrt to quickSearch 
> http://localhost:6700/restaurant?meal_id=5
> https://application-zomato.herokuapp.com/restaurant?meal_id=5


filter
> cuisine filter
  data respect to cuisine and quickSearch 
  > http://localhost:6700/filter/3?cuisine=4
  > https://application-zomato.herokuapp.com/filter/3?cuisine=4

> cost filter
  > http://localhost:6700/filter/1?lcost=200&hcost=500
  > https://application-zomato.herokuapp.com/filter/1?lcost=200&hcost=500

 data respect to cuisine and cost 
> cuisine filter + cost filter 
  > http://localhost:6700/filter/1?lcost=200&hcost=500&cuisineId=1
  >https://application-zomato.herokuapp.com/filter/1?lcost=200&hcost=500&cuisineId=1

> sort
    sort low to high in same quickSearch
    http://localhost:6700/filter/1?cuisineId=1&sort=1
    https://application-zomato.herokuapp.com/filter/1?cuisineId=1&sort=1

    sort high to low in same quickSearch
    http://localhost:6700/filter/1?cuisineId=1&sort=-1
    https://application-zomato.herokuapp.com/filter/1?cuisineId=1&sort=-1

> pagination
   > http://localhost:6700/filter/1?cuisineId=1&skip=2&limit=2
   > https://application-zomato.herokuapp.com/filter/1?cuisineId=1&skip=2&limit=2


Page 3
> restaurants details
> http://localhost:6700/details/2
> https://application-zomato.herokuapp.com/details/2

> Menu of that restaurants
> http://localhost:6700/menu/2
> https://application-zomato.herokuapp.com/menu/2


page 4
> menu items on user selection
  > http://localhost:6700/menuItems
  > body [1,4,5]

> api to place order
  > localhost:6700/placeOrder

page 5
> list all order
  > http://localhost:6700/orders
  > https://application-zomato.herokuapp.com/orders

Delete order 
> localhost:6700/deleteOrder
 

 update order
 > localhost:6700/updateOrder/61ffab62c39f96bf7ba39676?status=Success

 users
 >localhost:5000/api/auth/users
 login
 >localhost:5000/api/auth/login
 Register
 >localhost:5000/api/auth/register
 userInfo
 >localhost:5000/api/auth/userInfo