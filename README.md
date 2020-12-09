# SalonInteractive Interview Exercise

---

The SalonInterview exercise will be implementing a ORM in Ruby and and integrating it with Rails. You will basically be mimicing the CRUD functionality of ActiveRecord.

This exercise is expected to take around 4 hours.

If you have any questions about the exercise, please don't hesitate to reach out to your interviewer.

---

## Part 1. Abstract Model

In this project, you will find: 
- `app/models/product.rb` - Model to extend the abstract model 
- `tests/models/product_test.rb` - Unit tests for you to write out

The `Product` Model extends a parent class `AbstractModel`, which you will build. 

To Start: 
1. Create a MySQL database and use any MySQL adapter of your choosing. 
2. Run the migration in the project to create the product table.
3. Feel free to change the Ruby version if needed

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

With Rails, create routes that will let you manage the product(s) using your ORM implentation—not ActiveRecord.

### Required
- Page that lets you view the products 
- Page that allows to create a product 
- Page that allows to view/edit/delete a product 

---

## Part 3. Submission

---

Once complete, submit a pull request with your implementation and send your interviewer an email that it is completed.
