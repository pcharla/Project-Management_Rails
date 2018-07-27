For Managing my applications in progress. You can use it if you want.. In fact its so good that you should

  Real time usage cases
  Multi Tenancy : Multi layered structure for application's users.  For example Organizations and its employees.Organizations sign up to use the application pay if necessary , and invite their employees or teams to join
  and make progress.
 2 types of Plans.

 Free Plan: One project at a time. Unlimited number of employees to work on the project.
 Premium Plan: Paid. Multiple projects at a time. Unlimited number of employees.

 Once signed up, organizations can switch plans according to their needs but have to be careful since there is  a limit on number of projects in free plan.

 Features:

 Account activation links through Emails when User/Admin signs up.
 using Transactional email services provider SendGrid to send emails. It is a free add on that comes with heroku through which this application is deployed into production. SendGrid is very well documented and easy to get started. Devise confirmable to build this functionality.

 To accept payments from organizations, Stripe API is worked with. Not basic form stripe provides us, but our own form with credit card details built and added to registration page provided by devise and customization of Devise registrations. Make use of gem documentation to extend the functionality provided by the gem to fit our needs.

 AWS S3 bucket is used to handle storage in production.












* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
