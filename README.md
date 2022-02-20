# API Document for Zomato

## Page 1

**List of City**

> https://zomato-apis.herokuapp.com/location

**List of Restaurants**

> https://zomato-apis.herokuapp.com/restaurants

**Restaurants WRT City**

> https://zomato-apis.herokuapp.com/restaurants/?state_id=3

**Quick Search or mealType**

> https://zomato-apis.herokuapp.com/mealtype

## Page 2

**Restaurants WRT Quick Search or mealType**

> https://zomato-apis.herokuapp.com/restaurants/?meal_id=3

## Page 3

**Restaurants Details**

> https://zomato-apis.herokuapp.com/details/3

**Menu of that Restaurant**

> https://zomato-apis.herokuapp.com/menu/12

## Page 4

**Menu Items on User Selection**

> https://zomato-apis.herokuapp.com/menuItem body [1,4,5]

## Page 5

**Place Order**

> https://zomato-apis.herokuapp.com/placeOrder body {}

**List Orders or Get Orders**

> https://zomato-apis.herokuapp.com/orders?email=david20@gmail.com

## Filter Page

**Cuisine Filter**

> https://zomato-apis.herokuapp.com/filter/1?cuisine=1

**Low Cost and High Cost Filter**

> https://zomato-apis.herokuapp.com/filter/2?lcost=200&hcost=500

**Low Cost, High Cost and Cuisine Filter**

> https://zomato-apis.herokuapp.com/filter/2?cuisine=2&lcost=200&hcost=500

**Sort Filter**

> https://zomato-apis.herokuapp.com/filter/1?cuisine=1&sort=-1

## Pagination

> https://zomato-apis.herokuapp.com/filter/1?sort=-1&skip=6&limit=2

## Update Order

> https://zomato-apis.herokuapp.com/updateOrder/ body {}

## Delete Order

> https://zomato-apis.herokuapp.com/deleteOrder remove {condition}
