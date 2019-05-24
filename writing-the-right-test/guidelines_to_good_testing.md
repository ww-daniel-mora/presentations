# Guidelines to Good Testing
<!-- .element style="background: black" -->
<!-- .slide: data-background="images/test-pattern-152459.png" -->


## No Change Detectors

```python
// Production code:
def abs(i: Int)
  return (i < 0) ? i * -1 : i

// Test code:
for (line: String in File(prod_source).read_lines())
  switch (line.number)
    1: assert line.content equals def abs(i: Int)
    2: assert line.content equals   return (i < 0) ? i * -1 : i
```
[Google ToT - Change detector](https://testing.googleblog.com/2015/01/testing-on-toilet-change-detector-tests.html)


## Verify the Public Contract

* Identify the public contract
* Write tests as statements about the contract
* Avoid tests that assert something other then the public contract
* Do not use any tricks to expose the internals


## Use Descriptive Names

### Good

```c++
TEST_F(CustomerDao, getCustomerById_invalidId_returnsNullCustomer)
```

<!-- .element: style="width: 100%" -->

### Bad

```c++
TEST_F(CustomerDao, getCustomerbyId)
```


## Use Descriptive Names

<pre>
CustomerDao
  #get_customer_by_id
  <div style="color: green">
    returns the nil customer when the id is not found int the database
  </div>
</pre>


## Use Descriptive Names

<pre>
CustomerDao
  #get_customer_by_id
    when the id is invalid
<div style="color: green">
    returns the nil customer
    other statements about behavior with invalid ids...
</div>
</pre>


## Test it Once 

### (or as few times as possible)<!-- .element: class="fragment" -->


## Focus on what matters

* High churn
* High complexity
* High risk
Note: High churn or source of bugs


## Get low

* Remember the pyramid<!-- .element: class="fragment" -->
* Remember the purpose<!-- .element: class="fragment" -->
* Change the process -- not the state of the world<!-- .element: class="fragment" -->
* Take the long view<!-- .element: class="fragment" -->


<!-- .slide: data-background="images/massiveattack-mezzanine_1800x.jpg" -->
Note: Massive Attack background
