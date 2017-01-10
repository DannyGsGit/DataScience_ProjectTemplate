# Project Charter

## Business background

* Who are the stakeholders
* What are the basic business problems we are trying to address?
* What is this problem worth to the stakeholders?

## Scope
* Why is Data Science the right approach?
* What Data Science solutions are we trying to build?
* What will we do?
* How is it going to be consumed by the customer?

## Personnel
* Project Team:
	* Data Science Team:
		* Project lead
		* PM
		* Data scientist(s)
	* Customers:
		* Business analyst or other business data steward
		* Business contact
		* End users of data product
	* External Partners:
		* Consulting
	
## Metrics
* What are the qualitative objectives? (e.g. reduce user churn)
* What are the quantifiable metrics, their baseline (current) values and target values  (e.g. reduce the fraction of users with 4-week inactivity from 60% to 40%)
* How will we measure the metric? (e.g. A/B test on a specified subset for a specified period; or comparison of performance after implementation to baseline)

## Plan
* Phases (milestones), timeline, short description of what we'll do in each phase.

## Architecture
* Data
  * What data do we expect? Raw data in the customer data sources (e.g. on-prem files, SQL, on-prem Hadoop etc.)
  * What quantity of data do we expect? (e.g. Megabytes, Terabytes?)
* Data movement to an analytical environment
  * Is the data tractable on a single machine, or will it require clustered resources?
     * If cloud resources are required, obtain permission of data owners

* What tools and data storage/analytics resources will be used in the solution e.g.,
  * Apache Kafka for stream ingestion
  * R/Python for feature construction, aggregation and sampling
  * OpenCPU for operationalization as microservice
* How will the operationalized web service(s) be consumed in the business workflow of the customer?
  * How will the customer use the model results to make decisions
  * Data movement pipeline in production
  * Document any substantive changes to customer workflow

## Communication
* Communication schedule
* Who are the contact persons on both sides?