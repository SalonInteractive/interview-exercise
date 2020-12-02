# SalonInteractive Interview Exercise

---

The SalonInterview exercise will be implementing a ORM in Ruby and and integrating it with Rails. You will basically be mimicing the CRUD functinality of ActiveRecord.

This Exercise is expected to take around 4 hours 

If you have any questions about the exercise or any questions during the exercise, please reach out to your interviewer

---

## Part 1. Abstract Model

In this project, you will find: 
- `app/models/product.rb` - Model to extend the abstract model 
- `tests/models/product_test.rb` - Unit Tests for you to write out

The `Product` Model extends a parents class `AbstractModel` that you will build. 

To Start: 
1. Create a mysql database and use any mySQL adapter of your choosing. 
2. Run the migration in the project to create the product table.
3. Feel free to change the ruby version if needed

### Required Methods 
- def self.create(params)
- def self.save(params)
- def self.find(id)
- def self.all
- def update(parmas)
- def delete 

Note: Assume that the Product Model is using a Primary Key and not composite keys. 

Once implemented, make sure that your unit tests are written and that they pass successfully. 

---

## Part 2. FrameWork

---

With Rails, Create routes that will let you manage the product(s) using the ORM implentation and not ActiveRecord.

### Required
- Page that lets you view the products 
- Page that allows to create a product 
- Page that allows to view/edit/delete a product 

---

## Part 3. Submission

---

Once complete, submit a pull request with your implementation and send us an email back that it is completed.
