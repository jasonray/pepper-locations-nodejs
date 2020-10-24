# pepper-locations
I am using this as a way to explore using a few AWS services, which I have not done in years.  Boy, am I rusty.

I am implementing one of the solutions for Pepper (suite of applications to run a sports organization), with Locations providing functionality to manage a set of fields.

# components
database: have implemented a MySql instance in AWS to host the data.  At the moment, it is insecure (publically accessible, password hardcoded in application).
middleware: I am implementing a set of middlware services in node.js, although I think I really want to in java.  Java is just so much slower to get started with.  Will deploy this to AWS beanstalk
front-end: no idea yet

# API
fetch locations
fetch location
create location
set status to open
set status to closed
add geolocation
