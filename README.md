# Springboot-mvc-security-LoginPageProject
spring-security

This Is an Springboot MVC Security Project, which has a Secured login page
users will login the page and access the hyper link based on the ROLES assigned
new User can register and the password will be stored using bcrypt encryption in the Database which is created using custom tables.

/employees -> All Roles can access this URL

/leaders -> Only MANAGER Roles can access this URL

/systems -> only ADIM Roles can access this URL

This Username, Password, Roles are Stored encrypted in the database using custome tables
