# Flutter & Firebase Shopping App

A shopping mobile app which is made with Flutter and Firebase.

## Screenshots

|                                               |                                               |                                               |
|-----------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| <img width="100%" src="./Screenshots/0.png"> | <img width="100%" src="./Screenshots/1.png"> | <img width="100%" src="./Screenshots/2.png"> |
| <img width="100%" src="./Screenshots/3.png"> | <img width="100%" src="./Screenshots/4.png"> | <img width="100%" src="./Screenshots/5.png"> | <img width="100%" src="./Screenshots/7.png"> | <img width="100%" src="./Screenshots/8.png"> |  |  

## Firebase Structure

- **Users** (Collection)
	- email (String)
	- name (String)
	- surname (String)
	- phoneNumber (String)
- **Vendors** (Collection)
	- city (String)
	- contact (String)
	- email (String)
	- name (String)
- **Brands** (Collection)
	- name (String)
	- website (String)
- **Cards** (Collection)
	- name (String)
- **Products** (Collection)
	- **Assessments** (Collection)
		- assessmentId (String)
		- score (Number)
		- userReference (Reference)
	- brandReference (Reference)
	- categoryIds (Array)
	- features (Map)
	- name (String)
	- vendors (Array)
		- cartDiscount (Number)
		- discount (Number)
		- price (Number)
		- vendorReference (Reference)
		- paymentOptions (Array)
			- cardReference (Reference)
			- installments (Array)
				- amount (Number)
				- month (Number)

