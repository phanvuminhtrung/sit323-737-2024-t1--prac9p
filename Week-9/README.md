TASK:

- Install MongoDB into the Kubernetes cluster, either as a standalone instance or a replica set,
depending on your requirements.
- Create a MongoDB user with appropriate permissions for your application.
- Configure persistent storage for the MongoDB database by creating a Persistent Volume and
Persistent Volume Claim.
- Create a Kubernetes Secret for the MongoDB user credentials and add them to the deployment
manifest.
- Modify the Kubernetes deployment manifest for your application to include the newly added
MongoDB database. Ensure that the configuration includes information such as the database
type, credentials, and other necessary parameters.
- Test the deployment to ensure that the application can connect to the MongoDB database and
perform basic CRUD (Create, Read, Update, Delete) operations.

TEST:
