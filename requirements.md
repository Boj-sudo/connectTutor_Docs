## 2. Requirements Extraction

### 2.1. Functional requirements

1. The system shall be able to manage users and User Authentication.
2. The system shall be able to provisionally accept bookings until confirmation.
3. The system shall allow the user to be able to pay from the system using EFT and PayPal.
4. The system shall be able to generate reports
5. Admin shall be able to view transactional history.
6. Admin should be able to deal with complaints and issues such as registration and payments from the system.
7. 
- The language used shall be English.
- The currency shall be Rand.
- The date format shall be date/month/year.

8. The system shall be able able to show all available tutors around where the user stays.
9. The system shall be able to filter all the tutors according to the types of all the modules available at that location.
10. The system shall be able to show the estimated tutoring time the user has left with.
11. The system shall be able to generate invoices.
12. The system shall be able to allow the user to extend their tutoring time.

### 2.2 Non Functional requirements

1. The system should be fast.

- The system website loading page and the mobile application home screen should not take 5 seconds to render.
- The system calls to the backend API from both the mobile application and website should not exceed 1 minute including the rendering of text and images over a 4G connection.

2. The system should not be hard to use and it must have a great user experience.

- First time users should be able to figure out how to use the main actions quickly.
- Users must be able to use the system with ease the second time they access the system and the user interface will always be consistent.
- The design should be pleasant to use and users will do this by reviewing if they are happy after every transaction.
- Developers must create an interface that minimizes the mistakes made by users.

3. The system should be maintainable.

- Our maintainability of the system should be 70% of 24 hours, that is there is a 70% chance the component can be fixed in 24 hours.

4. The system should be portable and compatible.

- The systems website should run on all browsers and mobile app should be compatible with old and latest versions of android.
- The systems website should be mobile responsive.

5. The system should be have Data Integrity.

- The system should not share users information with the third parties, e.g. advertisers.

6. The system should be Reliable.

- The system should always be operational during 24 hours of the day.
- The system should have 10% chance of failure of 24 hours.

7. The system should be scaleable.

- The system should be hosted on a cloud platform like azure to avoid crashing due to many users trying to access the system at the same time.

8. The system should be secure.

- The system should use Microsoft Identity API to manage users and their roles to avoid users accessing parts of the system they are not supposed to.
- The system should use a Content Security Policy (CSP) to protect against Cross-Site-Scripting attacks.
- The system should use third party payment gate to process payments, this is more secure from intruders than using our own system to process payments.
- The system should use tokens to authenticate the credibility of the user trying to access the system.