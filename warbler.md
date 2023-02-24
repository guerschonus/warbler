Follows has an unusual arrangement : it has two foreign keys to the same table because a user can follow multiple users and be followed by multiple users.

Step Seven

The logged-in user is being kept track thanks to session.

The Flask's g object is a simple namespace object that has the same lifetime as an application context. The g object is used to mange resources during a request.

The purpose of add_user_to_g is to store the current user into the global (within a context) object g.

The before_request (@app before_request) decorator allows to execute a function before any request. 

