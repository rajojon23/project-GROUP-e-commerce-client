# project-GROUP-e-commerce-client
Client version only of [project-GROUP-e-commerce](https://github.com/cb-wd-5/project-GROUP-e-commerce)

We have to make use of stacks that we have learned thus far in the bootcamp to build an e-commerce app that will showcase all of the provided _wearables_ items.

The stack is React.Js, Redux, Node.Js, and styled-components.

The node server should be RESTful and follow REST principles.

---

**✋ We CANNOT use any external UI libraries, including, but not limited to, Material UI, Bootstrap.**

---

## How to run locally
1. Run `yarn install`
2. Run `yarn start`
3. The application should automatically open up in your browser, if not you can access at `http://localhost:3000/`

## REST API


The base URL used is `https://ecommerce-299100.uc.r.appspot.com/`

# Endpoints
* **URL**

`/allitems`

* **Method:**

`GET`

*  **Description:**

Returns all the wearables items.

* **URL**

`/items/:id`

* **Method:**

`GET`

*  **Description:**

Returns a specific item, based on the id.

* **URL**

`/companies`

* **Method:**

`GET`

*  **Description:**

Returns all the companies available.

* **URL**

`/inventory/update`

* **Method:**

`PUT`

*  **Description:**

Updates an existing item, you can update the following parameters:


```javascript
   {
      "name": "Barska GB12166 Fitness Watch with Heart Rate Monitor",
      "price": "$49.99",
      "bodyLocation": "Wrist",
      "category": "Fitness",
      "id": 1213,
      "image": "https://via.placeholder.com/150"
      "numInStock": 9,
      "companyId": 19962
    }

```


