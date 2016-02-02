### Who Am I?

* Michael Goetz
* Solutions Engineering Manager @ Chef
* mpgoetz@chef.io
* @michaelpgoetz



### Tests Suck
##### Yours are especially awful
Mine are the worst



### TDD Is Dead

![alt text](images/tdd-is-dead.png)

##### I'm not quite dead yet!

![alt text](images/tdd-is-good.png)



### Test Coverage Is A Lie

![alt text](images/CoverageTrend.png)

And a tool of our oppressors



### Why Are We Kidding Ourselves?



### Automation is a Test's best friend
![alt text](images/Agile-Testing-Quadrants.png)
Note: Automation moves quickly, so you have to have a robot check changes. It's impossible to validate all of the integrations and complexities of software at the speed of git commit.



### What is a Test?
![alt text](images/test-def.png)



### What is a Change?
![alt text](images/change-def.png)



### How Do You Validate Your Change?
![alt text](images/changes.jpg)



### The 'Type and Look'
![alt text](images/preview.png)



### The 'Red-Green'
![alt text](images/red-green-refactor.png)



### The 'Red-Red-Red-Fuck-I'll-Mark-It-As-Pending'
![alt text](images/pending-steps.png)



### The 'It's Probably Fine'
![alt text](images/do-it-live.jpg)



### The 'We failed the audit....again'
![alt text](images/FAIL.png)



### Your job isn't to write Tests

It's to deliver business value to your customers



### Tests Are Not Validation
<span class="yellow">Validation</span>: to establish the **fitness** or **worth** of a software product for its operational
mission.

<small>Barry Boehm</small>



### A Tale of Two Customers

* The primary customer is whoever is consuming on your code - Validation

* The secondary customer is you - Test



### The Primary Customer

* They don't care if your unit test coverage is at 100% if they can't log in.

* Did you write a validation for your primary customer?

* Know how your work contributes to what the primary customer wants and make sure you have a validation for it working properly.



### Who is the Primary Customer?

* Website visitor

* Auditor

* API consumers

* Management



### The Secondary Customer

* Protect your hard work. If your change works on your machine, write whatever test proves it works if someone else checks it out.

* Pick the level of test that proves your work is solid.



### So don't write tests?

Testing the <span class="yellow">*construction*</span> is not enough. We also must validate the <span class="yellow">*expectations*</spa> of the customer.

* Determine what validation or test is necessary to serve both customers

* Create something that automatically confirms that expectations are met
